<template>
  <h2>Sign out</h2>
</template>

<script>
export default {
  asyncData() {
    $nuxt.$fire.auth.signOut()
  },
}
</script>