<script>
  import Contact from './Contact.svelte';
</script>

<svelte:head>
  <title>Contact us - Telena Consulting</title>
  <link rel="preload" as="image" href="/assets/contact-us.webp" />
</svelte:head>

<div class="h-screen bg-contact-us bg-cover bg-center">
  <div
    class="flex h-full flex-col place-content-center place-items-center bg-russian-violet-400 bg-opacity-75 p-12"
  >
    <h1 class="mb-10 text-2xl lg:text-4xl">Contact us</h1>
    <div class="flex flex-wrap place-content-center place-items-center text-center md:text-left">
      <Contact name="Leanne Graham" email="Sincere@april.biz" phone="1-770-736-8031" />
      <Contact name="Ervin Howell" email="Shanna@melissa.tv" phone="010-692-6593" />
    </div>
  </div>
</div>
