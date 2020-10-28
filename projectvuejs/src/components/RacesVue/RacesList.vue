<template>
  <div>
    <h1 class="text-lg font-bold text-center">
        Liste des  {{racesData.name}}
    </h1>
    <races-card
    v-for="(race,index) in racesData.races"
    :key="index"
    :race="race"
    >
    </races-card>
  </div>
</template>

<script>
import RacesCard from './RacesCard'
import racesData from '../../data/races.json'



export default {
name:"races-list",
components:{
RacesCard,


},
data(){
return {
racesData: racesData,

}

}
}
</script>

<style>

</style>