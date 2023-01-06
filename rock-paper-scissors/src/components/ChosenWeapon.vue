<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: "Chosen Weapon",
  props: {
    weapon: {
      type: Object,
    }
  }
});
</script>

<template>
  <div>
    <div class="button">
      <div v-if="weapon.icon" class="icon">
        {{  weapon.icon }}
      </div>
      <div v-else class="label">
        {{ weapon.name }}
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use '../assets/colors' as c;

.container {
    height: 100%;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}

.button {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    min-width: 10rem;
    min-height: 10rem;
    // border: .2em solid c.$gray;
    filter: drop-shadow(0 0 15px c.$gray) drop-shadow(0 0 50px c.$gray) contrast(2) brightness(2);
    transition: .5s;
    cursor: pointer;
    margin: .75em;

    &:hover {
      // border: .4em solid c.$gray-lighter;
      scale: 1.2;

      .label {
        font-weight: bold;
        transition: .5s
      }
  
    }

    & .label {
      color: c.$gray;
    }

    & .icon {
      font-size: 3em;
    }

}
</style>
