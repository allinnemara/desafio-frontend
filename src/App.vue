<script setup>
import Header from './components/Header/Header.vue'
import Card from './components/Card/Card.vue'
import VideoThumbnail from './components/VideoThumbnail/VideoThumbnail.vue'
</script>

<template>
  <Header />

  <main>
    <section class="container mt-5">
      <h2 class="title mb-4">Featured</h2>

      <div class="row">
        <div class="col-12 col-md-6 col-lg-8 mb-5 mb-md-0">
          <VideoThumbnail />
        </div>

        <div class="col-12 col-md-6 col-lg-4">
          <Card
            class="mb-3" 
            image="https://i.ytimg.com/vi/E5nYoxagaXU/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCQ7JlBUVE0nFs8LmFPuSW7Ihe2lQ"
            link="https://www.youtube.com/watch?v=E5nYoxagaXU"
            title="MezaPro Apresenta: o universo das NFTs e as oportunidades para sua carteira"
          />
          <Card
            class="mb-3" 
            image="https://i.ytimg.com/vi/E5nYoxagaXU/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCQ7JlBUVE0nFs8LmFPuSW7Ihe2lQ"
            link="https://www.youtube.com/watch?v=E5nYoxagaXU"
            title="MezaPro Apresenta: o universo das NFTs e as oportunidades para sua carteira"
          />
          <Card
            class="mb-3" 
            image="https://i.ytimg.com/vi/E5nYoxagaXU/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCQ7JlBUVE0nFs8LmFPuSW7Ihe2lQ"
            link="https://www.youtube.com/watch?v=E5nYoxagaXU"
            title="MezaPro Apresenta: o universo das NFTs e as oportunidades para sua carteira"
          />
          <Card
            class="mb-3" 
            image="https://i.ytimg.com/vi/E5nYoxagaXU/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCQ7JlBUVE0nFs8LmFPuSW7Ihe2lQ"
            link="https://www.youtube.com/watch?v=E5nYoxagaXU"
            title="MezaPro Apresenta: o universo das NFTs e as oportunidades para sua carteira"
          />
        </div>
      </div>
    </section>

    <section class="container mt-5">
      <h2 class="title mb-4">More Videos</h2>

      <div class="row">
        <div class="col-12 col-md-6 col-lg-3 mb-4">
          <Card />
        </div>
        <div class="col-12 col-md-6 col-lg-3 mb-4">
          <Card />
        </div>
        <div class="col-12 col-md-6 col-lg-3 mb-4">
          <Card />
        </div>
        <div class="col-12 col-md-6 col-lg-3 mb-4">
          <Card />
        </div>
      </div>
    </section>
  </main>
</template>

<style src="./assets/styles/main.scss" lang="scss" />