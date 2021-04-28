<template>
  <div>
    <appNavbar />
    <Hero />
    <appFooter />
  </div>
</template>

<script>
import navbar from './components/navigation/Navbar'
import Hero from './components/Hero'
import footer from './components/navigation/Footer'

export default {
  name: 'App',
  components: {
    appNavbar: navbar,
    Hero,
    appFooter: footer
  }
}
</script>

<style>

</style>
