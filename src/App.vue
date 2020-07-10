<template>
  <div class="h-full min-h-full flex flex-col">
    <Header></Header>
    <div class="">
      <router-view/>
    </div>
    <Footer class="mt-auto"></Footer>
  </div>
</template>

<script>
import Header from '@/components/Header'
import Footer from '@/components/Footer'

export default {
  components: {
    Header,
    Footer
  }  
}
</script>

<style lang="scss">

</style>
