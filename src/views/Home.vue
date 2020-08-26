<template>
  <div class="home">
    Base URL is <strong>{{ baseUrl }}</strong>.
  </div>
</template>

<script>
export default {
  name: 'Home',

  computed: {
    baseUrl () {
      return process.env.BASE_URL
    }
  }
}
</script>
