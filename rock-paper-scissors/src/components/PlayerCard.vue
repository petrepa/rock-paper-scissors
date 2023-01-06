<template>
  <div>
    <div class="button-container">
      <div class="button-group">
        <weapon-button v-for="weapon in weapons" :key="weapon.name" :weapon="weapon"></weapon-button>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use '../assets/colors' as c;

.button-container {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
}

.button-group {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
}


</style>

<script lang="ts">
import { defineComponent } from 'vue';
import WeaponButton from './WeaponButton.vue';

interface Weapon {
  icon: string,
  name: string,
  beats: string,
}

export default defineComponent({
  components: { WeaponButton },
  name: "PlayerCard",
  emits: ["chosenWeapon"],
  props: {
    weapons: {
      type: Array,
      default: [
        {
          icon: "🪨",
          name: "rock",
          beats: "scissors"
        },
        {
          icon: "📃",
          name: "paper",
          beats: "rock"
        },
        {
          icon: "✂️",
          name: "scissors", 
          beats: "paper"
        }
      ]
    }
  },
  methods: {
    chooseWeapon(weapon: string): Weapon {
      this.chosenWeapon = weapon;
    },
  },
});

export { Weapon };

</script>