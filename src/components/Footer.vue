<template>
  <div class="row bg-dark text-white mt-5">
    <div class="col-6 py-4">
      <h3>About</h3>
      <p class="text-center px-5 py-4">
        Add some information about the album below, the author, or any other background context. Make it a few sentences long so folks can pick up some informative tidbits. Then, link them off to some social networking sites or contact information.
      </p>
    </div>
    <div class="col-6 py-4">
      <h4 class="text-white">Contact</h4>
      <ul class="list-unstyled py-4">
        <li><a href="#" class="text-white">Follow on Twitter</a></li>
        <li><a href="#" class="text-white">Like on Facebook</a></li>
        <li><a href="mailto:mjver@mweb.co.za" class="text-white">Email me</a></li> <!-- change to your email address -->
      </ul>
    </div>
    <div class="col-12 py-4"><a href="https://blackbat023.github.io/" class="text-white" target="_blank">&copy;The DigiCave</a></div>
  </div>
</template>

<script>
export default {
  name: 'FooterVue',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
