<template>
    <div class="info-box hover-zoom-effect">
        <div class="icon bg-blue">
            <i class="material-icons">{{icon}}</i>
        </div>
        <div class="content">
        <div class="text">{{title | uppercase}}</div>
            <div class="number">{{value}}</div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'InfoBox',
  props: {
    icon: {
      required: true
    },
    title: {
      required: true
    },
    value: {
      required: true
    }
  },
  data () {
    return {
    }
  }
}
</script>

<style scoped>

</style>
