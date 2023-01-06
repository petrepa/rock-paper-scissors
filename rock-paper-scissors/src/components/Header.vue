<script setup lang="ts">

defineProps<{ title: string }>()

</script>

<template>
  <div>
    <div class="container label button">
      {{ title }}
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use '../assets/colors' as c;

.container {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
}

.label {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    filter: drop-shadow(0 0 15px c.$gray) drop-shadow(0 0 50px c.$gray) contrast(2) brightness(2);
    transition: .5s;
    cursor: pointer;
    margin: .75em;
    font-size: 5em;
    line-height: 1em;
}
</style>
