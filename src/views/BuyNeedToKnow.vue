<template lang="pug">
  #buyneedtoknow
    b-container
      b-row
        b-col.d-flex.justify-content-center
          img(src="shoesimg/needtoknow.png")
</template>

<script>
export default {
  mounted: function () {
    this.$store.commit('boxshow')
  }
}
</script>
