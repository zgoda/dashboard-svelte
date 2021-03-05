<script>
  import { ChevronsRightIcon, ChevronsDownIcon } from 'svelte-feather-icons';
  export let brew;
</script>

<style lang="scss">
  .brew-title {
    vertical-align: middle;
  }
  .brew-list {
    margin-bottom: 0.5rem;
  }
</style>

<div>
  <div class="columns brew-list">
    <div class="col-5 brew-title">
      <strong>{brew.title}</strong>
    </div>
    <div class="col-7">
      <button class="btn btn-action btn-primary tooltip tooltip-right" type="button" data-tooltip="Przelej">
        <span class="icon"><ChevronsRightIcon/></span>
      </button>
      <button class="btn btn-action btn-primary tooltip tooltip-right" type="button" data-tooltip="Rozlej">
        <span class="icon"><ChevronsDownIcon/></span>
      </button>
    </div>
  </div>
</div>
