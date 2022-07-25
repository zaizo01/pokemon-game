<template>
  <h1>¿Quién es el pokemon?</h1>
  <PokemonPicture :pokemonId="4" :showPokemon="true" />
  <PokemonOptions />
</template>

<script>
import PokemonPicture from "@/components/PokemonPicture.vue";
import PokemonOptions from "@/components/PokemonOptions.vue";
import getPokemos from "@/helpers/getPokemonOptions";
console.log(getPokemos);
export default {
  name: "PokemonPage",
  components: {
    PokemonPicture,
    PokemonOptions,
  },
};
</script>
