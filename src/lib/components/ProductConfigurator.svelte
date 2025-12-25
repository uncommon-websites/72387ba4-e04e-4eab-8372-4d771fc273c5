<script lang="ts">
  let selectedNeighborhood = 'historic';
</script>

<section class="bg-[#f9f9f7] py-24 px-6">
  <div class="max-w-[1200px] mx-auto text-center">
    <h2 class="text-[40px] font-light text-gray-900 mb-16">
      Diverse neighborhoods. <span class="text-gray-400">Endless possibilities.</span>
    </h2>

    <div class="mb-8">
      <h3 class="text-2xl font-normal mb-2">Historic Downtown</h3>
      <p class="text-gray-500 text-sm">Walkable charm with proximity to UVA and local amenities.</p>
    </div>

    <!-- Neighborhood Image -->
    <div class="relative w-full h-[400px] bg-white rounded-xl mb-8 flex items-center justify-center overflow-hidden shadow-sm">
      <div class="absolute inset-0 flex items-center justify-between px-4">
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m15 18-6-6 6-6"/></svg>
        </button>
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m9 18 6-6-6-6"/></svg>
        </button>
      </div>
      <img src="/generated/image-charming-tree-lined-residential-street-i-1766622811632-10.webp" class="w-full h-full object-cover" alt="Charlottesville neighborhood" />
    </div>

    <!-- Neighborhood Types -->
    <div class="flex justify-center gap-4 mb-8">
      <button class="px-4 py-2 rounded-full bg-[oklch(0.696_0.17_162.48)] text-white text-xs font-medium">Historic</button>
      <button class="px-4 py-2 rounded-full bg-gray-200 text-gray-700 text-xs font-medium hover:bg-gray-300">Modern</button>
      <button class="px-4 py-2 rounded-full bg-gray-200 text-gray-700 text-xs font-medium hover:bg-gray-300">Estate</button>
      <button class="px-4 py-2 rounded-full bg-gray-200 text-gray-700 text-xs font-medium hover:bg-gray-300">Suburban</button>
    </div>

    <div class="flex justify-center gap-8 text-sm text-gray-600 mb-4 border-b border-gray-200 pb-4 inline-flex mx-auto w-auto px-12">
      <span>Walkable</span>
      <span>Near UVA</span>
      <span>Top Schools</span>
    </div>

    <p class="text-xs text-gray-500 mb-8">
      Average home price: <span class="font-bold text-gray-900">$850,000</span><br>
      Explore properties in this area
    </p>

    <div class="flex justify-center gap-4">
      <button class="px-6 py-3 bg-gray-100 hover:bg-gray-200 rounded-lg text-sm font-medium transition-colors text-left">
        <span class="block text-[10px] text-gray-500">Want to learn more?</span>
        <span class="text-[oklch(0.696_0.17_162.48)]">Explore neighborhoods</span>
      </button>
      <button class="px-6 py-3 bg-gray-100 hover:bg-gray-200 rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22s-8-4.5-8-11.8A8 8 0 0 1 12 2a8 8 0 0 1 8 8.2c0 7.3-8 11.8-8 11.8z"/><circle cx="12" cy="10" r="3"/></svg>
        View on map ->
      </button>
    </div>
  </div>
</section>
