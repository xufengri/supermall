<template>
  <div id="app">
    <div class="header">
          设置一段文字设置一段文字设置一段文字设置一段文字设置一段文字设置一段文字设置一段文字设置一段文字设置一段文字
    </div>

  </div>
</template>

<script>

export default {
  data() {
    return {
    };
  },
  watch: {},
  methods: {
  },
};
</script>

<style>
  #app {

  }
  .header {
    width: 200px;
    overflow: hidden;
    text-overflow: ellipsis;
    display: box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
  }
</style>
