<script lang="ts">
  import '../app.css';                        // global styles
  import Nav from '$lib/components/Nav.svelte';
  import Footer from '$lib/components/Footer.svelte';
  import favicon from '$lib/assets/favicon.svg';

  let { children } = $props();
</script>

<svelte:head>
  <link rel="icon" href={favicon} />
</svelte:head>

<div class="min-h-screen flex flex-col bg-[#0f1220] text-zinc-100">
  <Nav />
  <main class="flex-1">
    {@render children?.()}
  </main>
  <Footer />
</div>
