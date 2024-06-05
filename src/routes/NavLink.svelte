<script lang="ts">
  import clsx from 'clsx';

  let className: string | undefined = undefined,
    href: string = '#',
    title: string;
  export { className as class, href, title };
</script>

<a class={clsx(className, 'duration-200 hover:text-african-violet-700')} {href} {title}>
  {#if $$slots.default}
    <slot />
  {:else}
    {title}
  {/if}
</a>
