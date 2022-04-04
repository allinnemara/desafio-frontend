<script setup>
defineProps({
  title: { 
    type: String
  },
  company: { 
    type: String
  },
  image: { 
    type: String
  },
  link: { 
    type: String
  }
})
</script>

<template>
  <a
    :href="link || 'https://www.youtube.com/watch?v=YJgGKnCVCg8'"
    target="_blank"
    class="card"
    :aria-label="title || 'Vem pra nova economia digital'"
    :title="title || 'Vem pra nova economia digital'"
  >
    <img
      class="card__image"
      :src="image || 'src/assets/img/capaMercadoBitcoin.png'"
      alt="Capa video"
    >

    <div>
      <h3 class="card__title">
        {{title || "Vem pra nova economia digital"}}
      </h3>

      <p class="card__description colorSecondary">
        {{ company || "Mercado Bitcoin"}} <span class="material-icons">check_circle</span>
      </p>
    </div>
  </a>
</template>

<style src="./Card.scss" lang="scss" scoped />
