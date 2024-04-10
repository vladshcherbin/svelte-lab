<script lang="ts">
  import bostonOverviewImage from '$lib/assets/images/boston-overview.jpg?enhanced'
</script>

<enhanced:img
  src={bostonOverviewImage}
  class="image"
  alt="boston overview"
  sizes="(width >= 700px) 500px, 100px"
/>

<style lang="scss">
  .image {
    width: 100px;
    height: auto;
  }

  @media (width >= 700px) {
    .image {
      width: 500px;
    }
  }
</style>
