<script lang="ts">
  import '../app.css';                        // global styles
  import Nav from '$lib/components/Nav.svelte';
  import Footer from '$lib/components/Footer.svelte';
  import favicon from '$lib/assets/favicon.svg';

  let { children } = $props();
</script>

<svelte:head>
  <link rel="icon" href={favicon} />
    <link 
    rel="preload" 
    href="/fonts/EFCO-Brookshire.woff2" 
    as="font" 
    type="font/woff2" 
    crossorigin="anonymous"
  />
</svelte:head>

<div class="min-h-screen flex flex-col">
  <Nav />
  <main class="flex-1">
    {@render children?.()}
  </main>
  <Footer />
</div>
