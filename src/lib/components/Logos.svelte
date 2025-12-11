<script>
  const logos = [
    { name: "BRAND", font: "font-sans font-bold tracking-wider" },
    { name: "STORE", font: "font-serif font-bold italic" },
    { name: "SHOP", font: "font-sans font-black tracking-tight" },
    { name: "MARKET", font: "font-mono font-bold" },
    { name: "RETAIL", font: "font-sans font-bold" },
    { name: "COMMERCE", font: "font-sans font-light uppercase tracking-widest" },
    { name: "GOODS", font: "font-serif font-bold" },
    { name: "DIRECT", font: "font-sans font-bold tracking-tight" },
    { name: "CONSUMER", font: "font-mono font-bold" },
    { name: "LIFESTYLE", font: "font-sans font-bold italic" },
    { name: "ESSENTIALS", font: "font-sans font-bold" },
    { name: "BOUTIQUE", font: "font-serif italic font-bold" },
  ];
</script>

<section class="py-16 border-b border-gray-100">
  <div class="container-custom text-center">
    <p class="text-[10px] font-bold tracking-[0.2em] text-gray-400 uppercase mb-10">
      Trusted by 140+ world-class consumer brands
    </p>
    
    <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-x-8 gap-y-12 items-center justify-items-center opacity-60 grayscale hover:grayscale-0 transition-all duration-500">
      {#each logos as logo}
        <div class="text-xl md:text-2xl text-gray-800 flex items-center justify-center w-full">
           <!-- Placeholder for actual SVG logos -->
           <span class="{logo.font}">{logo.name}</span>
        </div>
      {/each}
    </div>
  </div>
</section>
