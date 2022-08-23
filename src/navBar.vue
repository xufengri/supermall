<template>
  <div class="nav-bar">
    <button @click="itemClick">{{count}}</button>
    <div class="left">
      <slot name="left">
      </slot>
    </div>
    <div class="center">
      <slot name="center"></slot>
    </div>
  </div>
</template>

<script>
export default {
  name: 'navbar',
  data() {
    return {
      count: 1
    }
  },
  methods: {
    itemClick() {
      this.count++
    }
  }
}
</script>

<style>
  .nav-bar {
    display: flex;
  }
</style>
