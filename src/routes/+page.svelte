<script lang="ts">
  import Service from './Service.svelte';
</script>

<svelte:head>
  <title>Telena Consulting</title>
  <link rel="preload" as="image" href="/assets/hero.webp" />
  <link rel="preload" as="image" href="/assets/digital-marketing.webp" />
  <link rel="preload" as="image" href="/assets/money.webp" />
  <link rel="preload" as="image" href="/assets/office.webp" />
</svelte:head>

<div class="bg-hero bg-cover bg-center">
  <div class="bg-russian-violet-500 bg-opacity-45 px-5 md:py-16">
    <div
      class="flex flex-col place-content-center place-items-center stroke-black stroke-1 py-16 text-center *:py-2 lg:my-24"
    >
      <h1 class="text-2xl lg:text-5xl">Expert CFO Consulting for small businesses</h1>
      <h2 class="text-lg lg:text-3xl">
        Maximize your financial potential with Telena's CFO Consulting tailored for small
        businesses.
      </h2>
    </div>
  </div>
</div>
<div class="bg-african-violet-200 p-5 *:py-2" id="services">
  <h2 class="text-center text-lg lg:text-3xl">CFO Consulting Services</h2>
  <div class="flex flex-col *:px-4 md:flex-row">
    <Service
      name="Business Performance Evaluation"
      description="Assessing the financial performance of the business and recommending improvements for growth."
      asset="/assets/digital-marketing.webp"
    />
    <Service
      name="Financial Strategy Planning"
      description="Developing tailored financial strategies to help small businesses achieve their goals."
      asset="/assets/money.webp"
    />
    <Service
      name="Financial Analysis"
      description="Conducting in-depth financial analysis to provide insights for informed decision-making."
      asset="/assets/office.webp"
    />
  </div>
</div>
<div class="bg-african-violet-300 px-5 py-10 md:py-16">
  <div class="flex flex-col place-content-center place-items-center text-center *:py-2">
    <h2 class="text-2xl lg:text-4xl">
      Empowering small businesses with strategic financial guidance.
    </h2>
    <h3 class="text-lg">Transform your finances today!</h3>
  </div>
</div>
