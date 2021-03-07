<script>
  import BrewItem from './BrewItem.svelte';
  export let title;
  export let items = [];
</script>

<style lang="scss">
  .panel {
    margin-top: 1rem;
  }
</style>

<div class="panel">
  <div class="panel-header">
    <div class="panel-title h4">{title}</div>
  </div>
  <div class="panel-body">
    {#each items as item (item.id)}
      <BrewItem brew={item}/>
    {/each}
  </div>
</div>
