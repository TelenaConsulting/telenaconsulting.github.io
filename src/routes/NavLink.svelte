<script lang="ts">
  import clsx from 'clsx';

  let className: string | undefined = undefined,
    href: string = '#';
  export { className as class, href };
</script>

<a class={clsx(className, 'px-3 py-2 duration-200 hover:text-african-violet-700')} {href}>
  <slot />
</a>
