<script lang="ts">
  const images = [
    "/generated/image-stunning-modern-farmhouse-exterior-with--1766622792655-1.webp",
    "/generated/image-classic-brick-georgian-mansion-with-symm-1766622794730-2.webp",
    "/generated/image-contemporary-luxury-home-with-clean-line-1766622796885-3.webp"
  ];
</script>

<section class="bg-white pb-24 overflow-hidden" id="properties">
  <div class="flex gap-4 overflow-x-auto px-6 pb-8 snap-x">
    {#each images as img}
      <div class="min-w-[80vw] md:min-w-[60vw] lg:min-w-[45vw] h-[400px] snap-center first:pl-0">
        <img src={img} alt="Luxury Charlottesville property" class="w-full h-full object-cover rounded-lg" />
      </div>
    {/each}
  </div>
  
  <div class="text-center mt-4">
    <p class="text-gray-500 text-sm mb-4">Featured Properties <span class="text-gray-400">Luxury homes in prime locations</span></p>
    <div class="flex justify-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-gray-800"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
    </div>
  </div>
</section>
