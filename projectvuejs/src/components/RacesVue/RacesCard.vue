<template>
  <div
    class="m-2 p-2 rounded border border-black flex justify-between"
  >
    <h3 class="text-lg font-bold">{{ races.Name }}</h3>
    <p>Caractéristique : {{ races.carac}}</p>
    <p>Taille : {{ races.taille}}</p>
    <p>Vitesse : {{ races.vitesse}}</p>
    <p>Competence : {{ races.Competence}}</p>
    <p>Langue : {{ races.langue}}</p>
  </div>
</template>


<script>
export default {
  name: "races-card",
  props: ["races"],
  
};
</script>
