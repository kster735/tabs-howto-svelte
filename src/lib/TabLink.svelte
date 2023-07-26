<script>
  export let label;
</script>

<button class="tablinks" on:click>
  {label}
</button>

<style>
  button {
    background-color: blue;
    color: white;
    border-radius: 2rem;
    transition: 0.5s ease-in-out;
    &:hover {
      background-color: white;
      color: blue;
    }
  }
</style>