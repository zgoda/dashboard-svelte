<script>
  import Panel from './Panel.svelte';
</script>

<style lang="scss" global>
  @import '../node_modules/spectre.css/src/spectre.scss';
</style>

<div class="container grid-md">
  <h1>Mój Brewlog</h1>
  <div class="columns">
    <div class="column col-sm-6">
      <Panel title={'Fermentuje'}/>
    </div>
    <div class="column col-sm-6">
      <Panel title={'Dojrzewa'}/>
    </div>
  </div>
  <div class="columns">
    <div class="column col-sm-6">
      <Panel title={'Wyszynk'}/>
    </div>
    <div class="column col-sm-6">
      <Panel title={'Receptury'}/>
    </div>
  </div>
</div>
