<template>
  <div class="test1-container">
    hellohellohello{{message}}
  </div>
</template>
<script type="text/javascript">
export default {
  name: "test1",
  data () {
    return {
      message: "暗号"
    }
  },
  mounted () {
    let a = 1;
    for (let n = 0; n < 10; n++) {
      a++;
    }
    this.message = a;
  },
}
</script>
<style scoped>
.test1-container {
  width: 50px;
  height: 100px;
  background-color: bisque;
}
</style>