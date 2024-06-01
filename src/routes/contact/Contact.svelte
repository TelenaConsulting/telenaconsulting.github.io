<script lang="ts">
  export let name: string, email: string, phone: string, address: string | undefined = undefined;
</script>

<div class="m-4 text-xl">
  <p>{name}</p>
  <p>{email}</p>
  <p>{phone}</p>
  {#if address}
    <p>{address}</p>
  {/if}
</div>