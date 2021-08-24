<template>
  <Child />
</template>

<script>
import Child from '~/components/Child'

export default {
  components: {
    Child
  }
}
</script>



<style scoped lang="scss">
.btn {
  display: inline-block;
  margin: 4px;
  padding: 6px 12px;
  border-radius: 4px;
  background-color: darkmagenta;
  color: white;
  cursor: pointer;
  &.large {
  font-size: 20px;
  padding: 10px 20px;
  }
}

</style>