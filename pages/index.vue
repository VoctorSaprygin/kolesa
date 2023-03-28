<template>
<div>
  <Localization/>
  <TheHeader/>
  <Battle/>
</div>
</template>

<script>
import Localization from "@/components/Localization";
import TheHeader from "@/components/TheHeader";
import Battle from "@/components/Battle";
export default {
  name: 'IndexPage',
  components: {
    Localization,
    TheHeader,
    Battle

  }
}
</script>
<style>
* {

  padding: 0px;
  font-family: "Open Sans", sans-serif;

}
</style>
