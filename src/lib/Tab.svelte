<script>
  import { current } from '../store.js';
  import TabLink from './TabLink.svelte';

</script>


<div class="tab" >
  <TabLink label="London" />
  <TabLink label="Paris" />
  <TabLink label="Tokyo" />
  <TabLink label="New York"/>
  <TabLink label="Athens" />
  <TabLink label="Rome" />
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