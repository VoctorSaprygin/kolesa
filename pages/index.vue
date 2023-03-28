<template>
<div>
  <Localization/>
  <TheHeader/>
  <!-- <TheFilter/> -->
  <TheBattle/>
</div>
</template>

<script>
import Localization from "@/components/Localization";
import TheHeader from "@/components/TheHeader";
import TheFilter from "../components/TheFilter.vue";
import TheBattle from '../components/TheBattle.vue';

export default {
  name: 'IndexPage',
  components: {
    Localization,
    TheHeader,
    TheBattle,
    TheFilter
}
}
</script>
<style>
* {

  padding: 0px;
  font-family: "Open Sans", sans-serif;

}
</style>
