<script lang="ts">
  export let asset, description, name;
</script>

<div class="my-3">
  <p class="pb-2 text-lg lg:text-2xl">{name}</p>
  <img width="1280" height="863" src={asset} alt="service" />
  <div class="h-1 bg-violet-400" />
  <p class="pt-2 lg:text-lg">{description}</p>
</div>
