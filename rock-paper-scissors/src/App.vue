<script setup lang="ts">
import Background from './components/Background.vue';
import Header from './components/Header.vue';
import PlayerCard from './components/PlayerCard.vue';
</script>

<template>
  <div>
    <Background style="z-index: -1;"/>

    <Header title="rock paper scissors️"></Header>

    <PlayerCard></PlayerCard>
  </div>

</template>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css?family=Orbitron');

body {
  font-family: "Orbitron";
}


</style>
