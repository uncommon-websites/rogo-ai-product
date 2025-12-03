<script lang="ts">
  import Button from './ui/Button.svelte';
</script>

<section class="relative isolate overflow-hidden bg-white pt-24 lg:pt-32 pb-0">
  <div class="mx-auto max-w-7xl px-6 lg:px-8 text-center">
    <h1 class="mx-auto max-w-4xl text-5xl font-medium tracking-tight text-gray-900 sm:text-7xl font-serif">
      Stop Wasting Your Team's Time
    </h1>
    <p class="mx-auto mt-6 max-w-2xl text-lg leading-8 text-gray-600 font-sans">
      Accelerate firm productivity, automate workflows, and unify financial data at scale with one secure platform
    </p>
    <div class="mt-10 flex items-center justify-center gap-x-6 relative">
      <div class="relative group">
        <!-- Decorative brackets -->
        <div class="absolute -top-2 -left-2 w-4 h-4 border-t-2 border-l-2 border-gray-900"></div>
        <div class="absolute -bottom-2 -right-2 w-4 h-4 border-b-2 border-r-2 border-gray-900"></div>
        
        <Button href="#demo" className="px-8 bg-gray-900 text-white rounded-full">Request a Demo</Button>
      </div>
    </div>
  </div>

  <div class="mt-16 flow-root sm:mt-24 relative">
    <div class="relative rounded-xl bg-gray-900/5 p-2 ring-1 ring-inset ring-gray-900/10 lg:-m-4 lg:rounded-2xl lg:p-4 w-full max-w-[90%] mx-auto h-[500px] overflow-hidden">
      <!-- Image Placeholder -->
      <div class="absolute inset-0 bg-gradient-to-br from-blue-100 to-gray-200 w-full h-full object-cover"></div>
      <img src="https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?q=80&w=2070&auto=format&fit=crop" alt="App screenshot" class="w-full h-full object-cover opacity-80" />
      
      <!-- Search Bar Overlay -->
      <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-full max-w-lg">
        <div class="relative bg-white rounded-lg shadow-2xl p-2 flex items-center">
          <div class="flex-1 px-4 text-gray-900 text-sm font-medium">
            benchmark revenue estimates for AAPL
          </div>
          <div class="flex-none text-gray-400 px-2">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
              <path stroke-linecap="round" stroke-linejoin="round" d="m18.375 12.739-7.693 7.693a4.5 4.5 0 0 1-6.364-6.364l10.94-10.94A3 3 0 1 1 19.5 7.372L8.552 18.32m.009-.01-.01.01m5.699-9.941-7.81 7.81a1.5 1.5 0 0 0 2.112 2.13" />
            </svg>
          </div>
          <button class="bg-[#1a4731] text-white p-2 rounded-md hover:bg-[#133525] transition-colors">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
              <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5 21 12m0 0-7.5 7.5M21 12H3" />
            </svg>
          </button>
        </div>
      </div>
    </div>
  </div>
</section>
