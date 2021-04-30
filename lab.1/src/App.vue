<template>
  <div>
    <appNavbar />
    <Hero imgURL="https://media.istockphoto.com/photos/couple-eating-lunch-with-fresh-salad-and-appetizers-picture-id944478708?k=6&m=944478708&s=612x612&w=0&h=LE6WIw919-89Ktb4po4YfgYZa05WUwHHyWELEdz6viM=" imgURL2="https://drsannas.se/wp-content/uploads/2019/04/shutterstock_617760569.jpg"/>
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
