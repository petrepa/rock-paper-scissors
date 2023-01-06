<template>
  <div>
    <div class="button-container">
      <chosen-weapon v-if="weaponHasBeenSelected" :weapon="selectedWeapon"></chosen-weapon>
      <div class="button-group">
        <weapon-button v-for="weapon in weapons" :key="weapon.name" :weapon="weapon" @click="chooseWeapon(weapon)"></weapon-button>
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
import ChosenWeapon from './ChosenWeapon.vue';
import WeaponButton from './WeaponButton.vue';

interface Weapon {
  icon: string,
  name: string,
  beats: string,
}

export default defineComponent({
  components: { WeaponButton, ChosenWeapon },
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
  data() {
    return {
      selectedWeapon: Object,
      weaponHasBeenSelected: false,
    }
  },
  methods: {
    chooseWeapon(weapon: object): Weapon {
      console.log("Chosen weapon: " + weapon.name);
      this.weaponHasBeenSelected = true;
      this.selectedWeapon = weapon;
      this.$emit('chosenWeapon', weapon.name);
    },
  },
});

export { Weapon };

</script>