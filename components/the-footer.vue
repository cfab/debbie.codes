<template>
  <footer class="footer px-4 py-6">
    <ul class="flex flex-wrap justify-center">
      <li class="social">
        <a href="https://twitter.com/debs_obrien" class="social twitter">
          &nbsp;
        </a>
      </li>
      <li class="social ml-4">
        <a
          href="https://www.linkedin.com/in/debbie-o-brien-1a199975/"
          class="social linkedin"
        >
          &nbsp;
        </a>
      </li>
    </ul>
    <p class="flex justify-center pt-4 text-nav">Debbie O'Brien</p>
  </footer>
</template>
<script>
export default {}
</script>

<style scoped>
.footer {
  max-height: 173px;
  background-image: url(~assets/imgs/footer_bg.jpg);
}
.social {
  width: 81px;
  height: 81px;
  display: block;
  text-decoration: none;
}
.linkedin {
  background: url(~assets/imgs/social_sprites.png) -162px -0 no-repeat;
}
.twitter {
  background: url(~assets/imgs/social_sprites.png) -243px -0 no-repeat;
}
</style>
