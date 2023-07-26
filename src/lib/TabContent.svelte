<script>
  export let src;
  export let alt;
</script>


<div class="image">
  <img {src} {alt}>
</div>

<style>

  .image {
    background-color: darkblue;
    width: 100%;
    height: 200px;
  }

  img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

</style>
