<template>
  <div class="home">
    <nav>
      <Navbar/>
    </nav>
    <h1 class="p-3">Configurator pachet turistic</h1>
    <div class="row">
      <Cards/>
    </div>
    <form>
      <Selects/>
    </form>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'
import Selects from '@/components/Selects.vue'
import Cards from '@/components/Cards.vue'

export default {
  name: 'home',
  components: {
    Navbar,
    Selects,
    Cards
  }
}
</script>