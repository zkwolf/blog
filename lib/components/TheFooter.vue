<template>
  <footer class="footer">
    <p>
      <span>Powered by</span>
      <a href="https://vuepress.vuejs.org" target="_blank">Vuepress</a>
      <span>theme</span>
      <a
        href="https://github.com/meteorlxy/vuepress-theme-meteorlxy"
        target="_blank"
      >vuepress-theme-meteorlxy</a>
    </p>
  </footer>
</template>

<script>
export default {
  name: "TheFooter"
};
</script>

<style lang="stylus" scoped>
@require '~@theme/styles/variables';

.footer {
  color: $grayTextColor;
  padding-bottom: 1.5rem;
  text-align: center;
  border-top: 1px solid $borderColor;
}
</style>
