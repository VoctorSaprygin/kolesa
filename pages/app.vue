<template>
<div>
  <Localization/>
  <TheHeader/>
   <TheFilter/>

</div>
</template>

<script>
import Localization from "@/components/Localization";
import TheHeader from "@/components/TheHeader";
import TheFilter from "../components/TheFilter.vue";


export default {
  name: 'IndexPage',
  components: {
    Localization,
    TheHeader,
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
