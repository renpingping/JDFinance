<template lang="html">
    <div :class="$style.home">
        <Heador></Heador>
        <Hslider></Hslider>
    </div>
</template>

<script>
import Heador from "../public/header"
import Hslider from "./hslider"
export default {
  components:{
    Heador,
    Hslider
  }
}
</script>

<style lang="scss" module>

</style>
