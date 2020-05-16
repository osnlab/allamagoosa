<template>
  <div>
    <h1 v-if="error.statusCode == 404">
      Page not found
    </h1>
    <h1 v-else>
      An error occured
    </h1>
  </div>
</template>

<script>
export default {
  props: ['error']
}
</script>
