<template>
  <div class="wrapper">
    <a v-for="item in data" :key="item">{{item+2}}</a>
  </div>
</template>

<script>
export default {
  components: {},
  props: {},
  data () {
    return {
      data: [1, 2, 3]
    }
  },
  watch: {},
  computed: {},
  methods: {},
  created () {},
  mounted () {}
}
</script>
<style scoped>
</style>
