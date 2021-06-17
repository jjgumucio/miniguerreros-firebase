<script >
  export let name;
  export let imgSrc;
  export let description // Can be html
  export let ssnn; // Array of POJOs: [{name: 'instagram', bgColor: 'bg-red-600'}]
</script>

<style>
  .descHeight {
    height: 100px;
  }
</style>

<div class="w-full md:w-6/12 lg:w-3/12 lg:mb-0 mb-12 px-4">
  <div class="px-6">
    <img alt="..." src={imgSrc} class="shadow-lg rounded-full mx-auto max-w-120-px" />
    <div class="pt-6 text-center">
      <h5 class="text-xl font-bold">{name}</h5>
      <p class="mt-3 text-sm text-blueGray-400 uppercase font-semibold descHeight">{@html description}</p>
      {#if ssnn }
        <div class="mt-6">
          {#each ssnn as sn}
            <button
              class="{sn.color} text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1"
              type="button"
            >
              <i class="fab fa-{sn.name}" />
            </button>
          {/each}
        </div>
      {/if}
    </div>
  </div>
</div>
