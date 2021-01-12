<template>
  <div id="app">
    <div>electron模板</div>
  </div>
</template>

<script>

const { dialog,app } = require("electron").remote;
export default {
  name: "App",
  data() {
    return {

    };
  },
  computed: {

  },
  mounted() {
    console.log(dialog)
  },
  watch: {

  },
  methods: {

  },
};
</script>

<style lang="scss">
</style>
