<template>
  <div>
    <h1>Lo que buscas no está aquí</h1>
    <p>{{route}}</p>
  </div>
</template>

<script>
export default {
  computed: {
    route () {
      return this.$route.path
    }
  }
}
</script>
