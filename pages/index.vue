<template>
  <div>
    <navbar />
    <main>
      <div class="container">
        <h1>nuxt</h1>
      </div>
    </main>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar'
export default {
  components: {Navbar},
  name: 'IndexPage'
}
</script>
