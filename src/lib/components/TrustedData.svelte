<script lang="ts">
  const providers = [
    { name: "Your Firm's Data", icon: "database" },
    { name: "LSEG", icon: "chart-bar" },
    { name: "Dow Jones", icon: "newspaper" },
    { name: "FactSet", icon: "cube" },
    { name: "Capital IQ", icon: "presentation-chart-line" },
    { name: "PitchBook", icon: "book-open" },
    { name: "Preqin", icon: "globe-alt" },
    { name: "Real-time Web & News", icon: "rss" },
    { name: "SEC Filings", icon: "document-text" },
    { name: "Transcripts", icon: "microphone" },
    { name: "Investor Presentations", icon: "desktop-computer" },
    { name: "International Filings", icon: "globe" },
  ];
</script>

<section class="bg-white py-24 sm:py-32">
  <div class="mx-auto max-w-7xl px-6 lg:px-8">
    <div class="mx-auto max-w-2xl lg:mx-0 mb-16">
      <h2 class="text-3xl font-serif font-medium tracking-tight text-gray-900 sm:text-5xl">Trusted Data</h2>
      <p class="mt-6 text-lg leading-8 text-gray-600 font-light">
        We partner with trusted data providers to bring the highest-quality financial information to our platform. Their expertise, combined with Rogo's technology, gives customers the clarity and confidence they need to move fast.
      </p>
    </div>
    <div class="grid grid-cols-1 gap-4 sm:grid-cols-2 lg:grid-cols-3">
      {#each providers as provider}
        <div class="flex items-center gap-x-4 rounded-xl bg-gray-50 p-6 hover:bg-gray-100 transition-colors">
          <div class="flex h-10 w-10 flex-none items-center justify-center rounded bg-white shadow-sm text-gray-900">
             <!-- Generic Icon based on name/type -->
             <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
               {#if provider.icon === 'database'}
                 <path stroke-linecap="round" stroke-linejoin="round" d="M20.25 6.375c0 2.278-3.694 4.125-8.25 4.125S3.75 8.653 3.75 6.375m16.5 0c0-2.278-3.694-4.125-8.25-4.125S3.75 4.097 3.75 6.375m16.5 0v11.25c0 2.278-3.694 4.125-8.25 4.125s-8.25-1.847-8.25-4.125V6.375m16.5 0v3.75m-16.5-3.75v3.75m16.5 0v3.75C20.25 16.153 16.556 18 12 18s-8.25-1.847-8.25-4.125v-3.75m16.5 0c0 2.278-3.694 4.125-8.25 4.125s-8.25-1.847-8.25-4.125" />
               {:else if provider.icon === 'chart-bar'}
                 <path stroke-linecap="round" stroke-linejoin="round" d="M3 13.125C3 12.504 3.504 12 4.125 12h2.25c.621 0 1.125.504 1.125 1.125v6.75C7.5 20.496 6.996 21 6.375 21h-2.25A1.125 1.125 0 0 1 3 19.875v-6.75ZM9.75 8.625c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125v11.25c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 0 1-1.125-1.125V8.625ZM16.5 4.125c0-.621.504-1.125 1.125-1.125h2.25C20.496 3 21 3.504 21 4.125v15.75c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 0 1-1.125-1.125V4.125Z" />
               {:else if provider.icon === 'newspaper'}
                 <path stroke-linecap="round" stroke-linejoin="round" d="M12 7.5h1.5m-1.5 3h1.5m-7.5 3h7.5m-7.5 3h7.5m3-9h3.375c.621 0 1.125.504 1.125 1.125V18a2.25 2.25 0 0 1-2.25 2.25M16.5 7.5V18a2.25 2.25 0 0 0 2.25 2.25M16.5 7.5V4.875c0-.621-.504-1.125-1.125-1.125H4.125C3.504 3.75 3 4.254 3 4.875V18a2.25 2.25 0 0 0 2.25 2.25h13.5M6 7.5h3v3H6v-3Z" />
               {:else}
                 <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 0 0-3.375-3.375h-1.5A1.125 1.125 0 0 1 13.5 7.125v-1.5a3.375 3.375 0 0 0-3.375-3.375H8.25m0 12.75h7.5m-7.5 3H12M10.5 2.25H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 0 0-9-9Z" />
               {/if}
             </svg>
          </div>
          <div class="text-sm font-medium leading-6 text-gray-900">{provider.name}</div>
        </div>
      {/each}
    </div>
  </div>
</section>
