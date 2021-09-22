<template>
  <div class="comment">

  </div>
</template>

<script>
export default {
  name: 'Comment',
  props: {
    commentProp: Object
  },
  setup (props) {
    return {
      comment: props.commentProp
    }
  },
  components: {}
}
</script>

<style lang="scss" scoped>

</style>
