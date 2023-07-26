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
    border: none;
    padding: 0.3rem 1rem;
    cursor: pointer;
    transition: 0.3s ease-in-out;
  }

  button:hover, button:active, button:focus {
      background-color: white;
      color: blue;
    }
</style>