<script setup></script>

<template>
  <section class="container">
    <picture class="poster-pic">
      <img src="../../assets/img/poster.webp" alt="" class="poster-img" />
    </picture>

    <div class="text-content">
      <p class="text-item">Переживите первый полёт в космос!</p>
      <p class="text-item">
        Наш проект даёт возможность не просто посмотреть о первом полёте в
        космос, а очутиться там в виртуальной реальности.
      </p>
    </div>
  </section>
</template>

<style scoped>
.container {
  display: flex;
  flex-direction: row;
}

.poster-pic {
  display: flex;
  /* width: 545px; */
  height: 594px;
  margin-right: 70px;
}
.poster-img {
  width: 545px;
  object-fit: cover;
}

.text-content {
  align-items: center;
  justify-content: center;
}

.text-item {
  color: #fff;
  font-size: 50px;
  font-family: var(--sans);
  font-weight: 700;
}
</style>
