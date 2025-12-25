<script lang="ts">
  import { page } from '$app/stores';
</script>

<nav class="bg-black text-white py-4 px-6 flex items-center justify-between sticky top-0 z-50 border-b border-gray-900">
  <div class="flex items-center gap-8">
    <a href="/" class="flex items-center gap-2">
      <svg width="32" height="32" viewBox="0 0 101 99" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M0.0224609 40.6496L50.0225 0L100.022 40.6496V99H76.2711V81.7109C76.2711 67.1159 64.5192 55.2842 50.0224 55.2842C35.5256 55.2842 23.7737 67.1159 23.7737 81.7109V99H0.0224609V40.6496Z" fill="white"/>
      </svg>
      <span class="text-xl font-medium tracking-tight">Toby Beavers</span>
    </a>
    
    <div class="hidden md:flex items-center gap-6 text-[13px] font-medium text-gray-300">
      <a href="#properties" class="hover:text-white transition-colors">Properties</a>
      <a href="#neighborhoods" class="hover:text-white transition-colors">Neighborhoods</a>
      <a href="#process" class="hover:text-white transition-colors">How it works</a>
      <a href="#about" class="hover:text-white transition-colors">About</a>
      <a href="#contact" class="hover:text-white transition-colors">Contact</a>
    </div>
  </div>

  <div class="flex items-center gap-4">
    <button class="text-gray-300 hover:text-white transition-colors">
      <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.3-4.3"/></svg>
    </button>
    <a href="#schedule" class="bg-[oklch(0.696_0.17_162.48)] hover:bg-[oklch(0.596_0.145_163.225)] text-white px-4 py-2 rounded-full text-[13px] font-medium transition-colors">
      Schedule consultation
    </a>
  </div>
</nav>
