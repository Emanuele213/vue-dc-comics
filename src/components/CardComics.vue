<template>
  <div class="card">
    <div class="in-card">
      <img
        :src="comic.thumb"
        :alt="comic.series"
      >
    </div>
    <h2>{{ comic.series }}</h2>
  </div>
</template>

<script>
export default {
  name: 'CardPasta',
  props: {
    comic: Object,
  },
};
</script>

<style lang="scss" scoped>
  .card {
    color: white;
    margin-top: 4rem;
    flex: 0 0 10%;
    display: flex;
    flex-direction: column;
    align-items: center;

    .in-card {
      img {
        width: 192px;
        height: 200px;
        object-position: top;
        object-fit: cover;
      }
    }

    h2 {
      font-size: 1rem;
    }
  }
</style>
