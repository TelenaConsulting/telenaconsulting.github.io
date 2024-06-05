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
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous" />
  <link
    href="https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Work+Sans:ital,wght@0,100..900;1,100..900&display=swap"
    rel="stylesheet"
  />
</svelte:head>

<div class="font-work-sans">
  <header class="w-full bg-russian-violet-500 px-5 py-2 md:fixed md:h-16">
    <nav
      class="flex h-full flex-col place-content-center place-items-center md:flex-row md:place-content-between"
    >
      <a class="py-2 font-abril-fatface" href="/" title="Home">
        <p>Telena</p>
        <Separator.Root class="h-px bg-white" />
        <p>Consulting</p>
      </a>
      <ul class="table text-center *:relative *:px-2 *:py-2 *:md:inline *:md:py-0">
        <li>
          <NavLink href="/" title="Home" />
        </li>
        <li>
          <NavLink href="/#services" title="Services" />
        </li>
        <li>
          <NavLink href="/about" title="About Us" />
        </li>
        <li>
          <NavLink href="/contact" title="Contact Us" />
        </li>
      </ul>
    </nav>
  </header>
  <main class="md:pt-16">
    <slot />
  </main>
  <footer class="p-5">
    <div class="flex place-content-between">
      <p>&copy; 2024 Telena Consulting</p>
    </div>
  </footer>
</div>
