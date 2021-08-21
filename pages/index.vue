<template>
  <div class="app">
    <div class="container">
      <div class="grid">
          <Header></Header>
      </div>
    </div>
  </div>
</template>

<script>
import Header from "~/components/header";
export default {
  components: {Header},
  layout: 'default'
}
</script>
