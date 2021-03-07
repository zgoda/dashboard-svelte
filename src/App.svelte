<script>
  import Panel from './Panel.svelte';
  const brews = {
    fermenting: [
      {
        id: 1,
        title: 'Pale Ale',
      },
      {
        id: 2,
        title: 'Dry Stout',
      }
    ]
  }
</script>

<style lang="scss" global>
  @import '../node_modules/spectre.css/src/spectre.scss';
</style>

<div class="container grid-lg">
  <h1>Mój Brewlog</h1>
  <div class="columns">
    <div class="column col-sm-6">
      <Panel title={'Fermentuje'} items={brews.fermenting}/>
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
