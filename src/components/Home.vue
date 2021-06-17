<template>
  <div class="flex flex-col justify-between px-10 h-screen">
      <div class="header mb-10 mt-10 flex flex-row justify-between align-baseline">
        <h1 class="text-white text-4xl">Toby Dart</h1>
        <div class="flex flex-col sm:flex-row justify-center items-end sm:items-center">
          <a class="text-green-500 hover:text-indigo-500 text-xl sm:mr-2" href="https://twitter.com/yhchkn_">twitter</a>
          <a class="text-green-500 hover:text-indigo-500 text-xl sm:mr-2" href="https://www.artstation.com/tobydart">artstation</a>
          <a class="text-green-500 hover:text-indigo-500 text-xl" href="https://www.linkedin.com/in/tobydart/">linkedin</a>
        </div>
      </div>
      <div class="content" style="height: 80%;">
        <div class="flex justify-center">
          <iframe src="https://player.vimeo.com/video/564171310?title=0&byline=0&portrait=0" width="1280" height="720" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
        </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
}
</script>
