<template>
  <div class="counter-warp">
    <van-button type="primary">主要按钮</van-button>
  </div>
</template>

<script>
// Use Vuex
export default {
  computed: {
    count () {
    }
  },
  methods: {

  }
}
</script>

<style>
.counter-warp {
  text-align: center;
  margin-top: 100px;
}
.home {
  display: inline-block;
  margin: 100px auto;
  padding: 5px 10px;
  color: blue;
  border: 1px solid blue;
}
</style>
