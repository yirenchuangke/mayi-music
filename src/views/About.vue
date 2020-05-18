<template>
  <div></div>
</template>

<script>
export default {
  created() {
    this.banner();
  },
  methods: {
    async banner() {
      const res = await this.$http.banner();
      console.log(res);
    }
  }
};
</script>

<style lang="sass" scoped>
</style>