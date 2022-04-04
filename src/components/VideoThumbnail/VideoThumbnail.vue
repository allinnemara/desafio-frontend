<script setup>
defineProps({
  videoCode: {
    type: String,
  }
})
</script>

<template>
  <div class="videoThumbnail">
    <iframe
      width="100%"
      height="100%"
      :src="videoCode || 'https://www.youtube.com/embed/YJgGKnCVCg8'"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen
      autoplay="true"
      title="YouTube video player"
    ></iframe>
  </div>
</template>

<style src="./VideoThumbnail.scss" lang="scss" scoped />
