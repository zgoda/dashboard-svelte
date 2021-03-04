<script>
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
    <ul>
      {#each items as item}
        <li>{item.text}</li>
      {/each}
    </ul>
  </div>
</div>
