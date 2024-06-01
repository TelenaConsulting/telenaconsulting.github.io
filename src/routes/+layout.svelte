<script>
  import '../app.css';
  import NavLink from './NavLink.svelte';
  import { Separator } from 'bits-ui';
</script>

<svelte:head>
  <meta
    name="description"
    content="Telena Consulting - Expert CFO Consulting for small businesses"
  />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="" />
  <link
    href="https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Work+Sans:ital,wght@0,100..900;1,100..900&display=swap"
    rel="stylesheet"
  />
</svelte:head>

<div class="font-work-sans">
  <nav class="w-full bg-russian-violet-500 p-5 md:fixed md:h-16">
    <div
      class="flex h-full flex-col place-content-center place-items-center md:flex-row md:place-content-between"
    >
      <a class="font-abril-fatface py-2" href="/">
        <p>Telena</p>
        <Separator.Root class="h-px bg-white" />
        <p>Consulting</p>
      </a>
      <ul class="table text-center *:relative *:py-2 *:md:inline *:md:py-0">
        <li>
          <NavLink href="/">Home</NavLink>
        </li>
        <li>
          <NavLink href="/#services">Services</NavLink>
        </li>
        <li>
          <NavLink href="/about">About Us</NavLink>
        </li>
        <li>
          <NavLink href="/contact">Contact Us</NavLink>
        </li>
      </ul>
    </div>
  </nav>
  <main class="md:pt-16">
    <slot />
  </main>
  <footer class="p-5">
    <div class="flex place-content-between">
      <p>&copy; 2024 Telena Consulting</p>
    </div>
  </footer>
</div>
