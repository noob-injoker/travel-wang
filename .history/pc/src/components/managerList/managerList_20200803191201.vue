<template>
  <div class="container">
    <div class="box">
      <div class="box-item"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "",
  props: {},
  components: {},
  data() {
    return {};
  },
  methods: {},
  mounted() {},
  watch: {},
  computed: {},
};
</script>

<style scoped lang='scss'>
.container {
  background: rgb(250, 250, 250);

  width: 100%;
  height: 600px;
  background: yellow;
  display: flex;
  justify-content: center;

  .box {
    width: 60%;
    border: 1px solid red;
  }
}
</style>