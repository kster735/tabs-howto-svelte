<script>
  import {current} from '../store.js';
  export let src;
  export let alt;
</script>


<div
  class = { $current === alt ? 'image' : 'hidden' }
>
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

  .hidden {
    display: none;
  }

</style>
