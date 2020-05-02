<template>
  <div class="container">
    <h1 v-if="error.statusCode === 404">エラー 404!!!!</h1>
  </div>
</template>

<script>
    export default {
            props: ['error']
    }
</script>