<script lang="ts">
  const steps = [
    {
      num: "01",
      title: "Initial consultation",
      desc: "We discuss your needs, preferences, and budget to understand exactly what you're looking for in a home.",
      img: "/generated/image-professional-real-estate-agent-in-busine-1766622798912-4.webp"
    },
    {
      num: "02",
      title: "Personalized tours",
      desc: "Receive custom video tours of properties and neighborhoods, helping you narrow down options before visiting.",
      img: "/generated/image-real-estate-agent-showing-property-detai-1766622807316-8.webp"
    },
    {
      num: "03",
      title: "Make your offer",
      desc: "With deep market knowledge, I guide you through negotiations to secure the best possible terms.",
      img: "/generated/image-luxurious-open-concept-living-room-with--1766622803057-6.webp"
    },
    {
      num: "04",
      title: "Close with confidence",
      desc: "I manage every detail through closing, ensuring a smooth transaction and successful outcome.",
      img: "/generated/image-smiling-family-of-four-standing-in-front-1766622800952-5.webp"
    }
  ];
</script>

<section class="bg-white py-24 px-6" id="process">
  <div class="max-w-[1200px] mx-auto">
    <h2 class="text-[40px] leading-tight font-light text-gray-900 mb-16 max-w-[600px]">
      Your home buying journey in four simple steps. Guided by local expertise.
    </h2>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-16">
      {#each steps as step}
        <div class="flex flex-col">
          <div class="bg-black text-white text-xs font-bold w-8 h-8 flex items-center justify-center rounded mb-6">
            {step.num}
          </div>
          <h3 class="text-xl font-normal mb-2">{step.title}</h3>
          <p class="text-gray-500 text-sm leading-relaxed mb-6 min-h-[80px]">{step.desc}</p>
          <div class="rounded-xl overflow-hidden h-[200px] bg-gray-100">
            <img src={step.img} alt={step.title} class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-500" />
          </div>
        </div>
      {/each}
    </div>

    <div class="bg-[#f9f9f7] rounded-2xl p-12 flex flex-col md:flex-row items-center justify-between gap-8">
      <div>
        <h3 class="text-2xl font-light mb-2">Ready to get started?</h3>
        <p class="text-gray-500 text-sm">Schedule a consultation to discuss your real estate goals.</p>
      </div>
      <div class="flex gap-4">
        <button class="px-6 py-3 bg-white border border-gray-200 hover:bg-gray-50 rounded-lg text-sm font-medium transition-colors">
          Learn more
        </button>
        <button class="px-6 py-3 bg-[oklch(0.696_0.17_162.48)] hover:bg-[oklch(0.596_0.145_163.225)] text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/></svg>
          Schedule consultation
        </button>
      </div>
    </div>
  </div>
</section>
