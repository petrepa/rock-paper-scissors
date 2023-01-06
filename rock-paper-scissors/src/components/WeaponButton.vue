<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: "Weapon Button",
  props: {
    weapon: {
      type: Array,
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
        {{ weapon.name }} hshs
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
    min-width: 5rem;
    min-height: 5rem;
    border: .2em solid c.$gray;
    border-radius: 25%;
    filter: drop-shadow(0 0 15px c.$gray) drop-shadow(0 0 50px c.$gray) contrast(2) brightness(2);
    transition: .5s;
    cursor: pointer;
    margin: .75em;

    &:hover {
      border: .4em solid c.$gray-lighter;

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
