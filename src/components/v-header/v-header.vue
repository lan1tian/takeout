<template>
  <div class="header"></div>
</template>

<script>
export default {
  name: "v-header",
  props: {
    seller: {
      type: Object,
      default() {
        return {};
      },
    },
  },
};
</script>


<style lang="stylus" rel="stylesheet/stylus">
@import 'common/stylus/variable'

.header {
  position: relative;
  overflow: hidden;
  color: $color-white;
  background: $color-background-ss;
}
</style>
