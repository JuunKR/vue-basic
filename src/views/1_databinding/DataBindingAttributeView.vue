<template>
  <div>
    <input type="text" name="" id="" v-bind:value="userId" readonly />
  </div>
  <br/>
  <img :src="imgSrc" alt="" style="width:100px; height:auto;">
  <br/>
  <input type="search" name="" id="" v-model="txt1" />
  <button :disabled="txt1 === ''">조회</button>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      userId: 'test',
      imgSrc: 'https://codingapple.com/wp-content/uploads/2021/03/1_oZqGznbYXJfBlvGp5gQlYQ.jpeg',
      txt1: ''
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
