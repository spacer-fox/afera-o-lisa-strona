
<script lang="ts">
  // later we can import your decorative font + scroll effects here
</script>

<section class="relative overflow-hidden bg-linear-to-r/srgb from-indigo-500 to-teal-400">
  <!-- psychedelic background pattern -->

  <div class="bg-linear-to-r/srgb from-indigo-500 to-teal-400">
  <h1>Afera o lisa</h1>
  </div>

  <div class="mx-auto max-w-6xl grid grid-cols-1 md:grid-cols-2 gap-10 px-6 py-20 items-center bg-mid-900/80 backdrop-blur">
    <!-- Left: placeholder for book cover -->
    <div class="flex justify-center">
      <div class="w-64 h-96 bg-slate-700/40 border border-silver flex items-center justify-center text-silver">
        Book Cover
      </div>
    </div>

    <!-- Right: tropes, description, button -->
    <div class="space-y-6">
      <!-- Tropes -->
      <ul class="flex flex-wrap gap-2">
        <li class="rounded-full bg-silver-deep/20 border border-silver/30 px-3 py-1 text-sm text-silver-light">Enemies → Lovers</li>
        <li class="rounded-full bg-silver-deep/20 border border-silver/30 px-3 py-1 text-sm text-silver-light">Found Family</li>
        <li class="rounded-full bg-silver-deep/20 border border-silver/30 px-3 py-1 text-sm text-silver-light">Political Intrigue</li>
      </ul>

      <!-- Description -->
      <p class="text-lg text-ink-faded leading-relaxed">
        In a world where foxes carry secrets and magic hums like neon, <strong>Afera o lisa</strong> 
        entwines love, betrayal, and the weight of destiny.
      </p>

      <!-- CTA -->
      <a href="#reader" class="inline-flex items-center rounded-full bg-gradient-to-r from-silver to-silver-light px-6 py-3 font-semibold text-mid-900 shadow hover:brightness-110">
        Czytaj teraz
      </a>
    </div>
  </div>
</section>


<!-- ========== SECTION 1: HERO / BIG TITLE ========== -->
<section id="hero" class="container mx-auto px-4 py-24 md:py-32 text-center">
  <!-- Big fantasy title (swap to your font when ready) -->
  <h1 class="text-5xl md:text-7xl font-brookshire tracking-tight">
    Afera o lisa
  </h1>


  <p class="mt-4 max-w-2xl mx-auto text-lg opacity-90">
    Oficjalna strona książki — czytaj rozdziały online, poznaj świat i bohaterów.
  </p>

  <div class="mt-8 flex justify-center gap-4">
    <a href="/read" class="px-6 py-3 rounded-md bg-white text-black font-semibold">
      Czytaj teraz
    </a>
    <a href="#about" class="px-6 py-3 rounded-md ring-1 ring-white/40">
      Dowiedz się więcej
    </a>
  </div>

  <!-- scroll hint -->
  <a href="#about" class="mt-12 inline-block opacity-80 hover:opacity-100 transition">
    ↓ Przewiń niżej
  </a>
</section>

<!-- ========== SECTION 2: ABOUT (2 COLUMNS) ========== -->
<section id="about" class="container mx-auto px-4 py-20">
  <div class="grid gap-10 md:grid-cols-2 md:items-center">
    <!-- LEFT: book mock (placeholder) -->
    <div class="relative mx-auto w-[240px] h-[320px]">
      <!-- Replace this box with your mockup/3D component later -->
      <div class="absolute inset-0 rounded-xl bg-gradient-to-br from-[#2a2243] to-[#1b1230] ring-1 ring-white/10 shadow-2xl"></div>
      <div class="absolute -top-3 -left-3 w-[240px] h-[320px] rounded-xl bg-white/10 blur-sm"></div>
      <div class="absolute inset-0 grid place-items-center text-sm opacity-80">Mockup książki</div>
    </div>

    <!-- RIGHT: copy about the book -->
    <div>
      <h2 class="text-2xl md:text-3xl font-semibold mb-4">O książce</h2>
      <p class="opacity-90 mb-4">
        „Afera o lisa” to opowieść o intrygach, magii i konsekwencjach decyzji.
        Świat oparty na potencjale, zderzenie tradycji i nowoczesności, bohaterowie
        którzy muszą wybrać między lojalnością a prawdą.
      </p>
      <p class="opacity-90 mb-6">
        Czytaj online w wygodnym trybie czytnika. Nowe rozdziały pojawiają się stopniowo.
      </p>

      <div class="flex gap-3">
        <a href="/read" class="px-5 py-2 rounded-md bg-white text-black font-medium">Zacznij czytać →</a>
        <a href="/about" class="px-5 py-2 rounded-md ring-1 ring-white/30">O autorce</a>
      </div>
    </div>
  </div>
</section>

<!-- ========== SECTION 3: WIP / STATUS ========== -->
<section id="wip" class="container mx-auto px-4 py-20">
  <h2 class="text-2xl md:text-3xl font-semibold mb-6">Status prac</h2>

  <div class="grid gap-6 md:grid-cols-3">
    <div class="rounded-xl p-5 bg-white/5 ring-1 ring-white/10">
      <h3 class="font-semibold mb-2">Beta 0 — strona startowa</h3>
      <ul class="list-disc pl-5 space-y-1 opacity-90">
        <li>Landing + nawigacja + stopka</li>
        <li>Tryb czytania — podstawy</li>
        <li>Styl bazowy (fiolet/gold)</li>
      </ul>
    </div>

    <div class="rounded-xl p-5 bg-white/5 ring-1 ring-white/10">
      <h3 class="font-semibold mb-2">Beta 2 — wiki</h3>
      <ul class="list-disc pl-5 space-y-1 opacity-90">
        <li>Hasła w Markdown</li>
        <li>Lista i wyszukiwarka</li>
        <li>TOC i tagi</li>
      </ul>
    </div>

    <div class="rounded-xl p-5 bg-white/5 ring-1 ring-white/10">
      <h3 class="font-semibold mb-2">Beta 3 — komentarze</h3>
      <ul class="list-disc pl-5 space-y-1 opacity-90">
        <li>Giscus / Utterances</li>
        <li>Moderacja</li>
        <li>Powiadomienia (opcjonalnie)</li>
      </ul>
    </div>
  </div>
</section>
