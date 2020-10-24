<template>
  <div id="app">
    <div class="block" :style="{'margin-left': left + 'px'}"></div>
  </div>
</template>

<style lang="scss">
.block {
  width: 50px;
  height: 50px;
  background-color: #000;
}
</style>

<script>
export default {
  data() {
    return {
      count: 0,
      someVar: "",
    };   
  },
  methods: {
    handleIncrement() {
      this.count = this.count + 1;
    }
  },
};
</script>