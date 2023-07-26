<script>
  import { current } from '../store.js';
  import TabLink from './TabLink.svelte';

</script>


<div class="tab" >
  <TabLink label="London" on:click = { ()=> $current = "London"}/>
  <TabLink label="Paris" on:click = { ()=> $current = "Paris"} />
  <TabLink label="Tokyo" on:click = { ()=> $current = "Tokyo"}/>
  <TabLink label="New York" on:click = { ()=> $current = "New York"}/>
  <TabLink label="Athens" on:click = { ()=> $current = "Athens"}/>
  <TabLink label="Rome" on:click = { ()=> $current = "Rome"}/>
</div>




<style>
  .tab {
    display: flex;
    justify-content: flex-start;
    flex-wrap: wrap;
    gap: 1rem 0.5rem;
    background-color: grey;
    padding: 1rem;
  }

</style>