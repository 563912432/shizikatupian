<template>
  <div class="vheader">
    <img src="../assets/header.png" @click="toUrl" alt="">
  </div>
</template>
<script>
export default {
  name: 'vheader',
  props: {
    url: {
      type: String
    }
  },
  methods: {
    toUrl: function () {
      if (this.url) {
        this.$router.push(`/introduce?url=${this.url}`)
      }
    }
  }
}
</script>
<style scoped>
  .vheader{
    height: 75px;
    width: 100%;
    padding: 0;
    z-index: 1;
  }
  .vheader img{
    height: 100%;
    width: 100%;
  }
</style>
