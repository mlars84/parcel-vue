<template>
  <div class="main">
    {{ parcelTest }}
  </div>
</template>

<script>
export default {
  data () {
    return {
      parcelTest: 'Parcel/Vue test'
    }
  }
}
</script>

<style lang="scss">
$primary: #56b983;

.main {
  color: $primary;
}
</style>


