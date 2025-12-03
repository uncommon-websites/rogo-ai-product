<script lang="ts">
</script>

<section class="bg-white py-24 sm:py-32">
  <div class="mx-auto max-w-7xl px-6 lg:px-8">
    <div class="mx-auto max-w-4xl text-center mb-20">
      <h2 class="text-3xl font-serif font-medium tracking-tight text-gray-900 sm:text-5xl leading-tight">
        Just as Bloomberg digitized financial data in the <span class="text-gray-500">1980s</span>, <span class="font-semibold">Rogo is now transforming financial workflows.</span>
      </h2>
    </div>

    <div class="mx-auto grid max-w-2xl grid-cols-1 gap-x-16 gap-y-16 lg:mx-0 lg:max-w-none lg:grid-cols-2 lg:items-center">
      <!-- Left Column: Image & Overlay -->
      <div class="relative">
        <div class="aspect-[4/3] w-full overflow-hidden rounded-xl bg-gray-100 relative">
           <img src="https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?q=80&w=2070&auto=format&fit=crop" alt="Office building" class="h-full w-full object-cover" />
           
           <!-- Overlay Card -->
           <div class="absolute inset-0 flex items-center justify-center p-8">
             <div class="bg-white/95 backdrop-blur-sm shadow-2xl rounded-lg p-6 w-full max-w-md border border-gray-100">
               <div class="space-y-4">
                 <div class="flex items-center justify-between text-xs text-gray-400 uppercase tracking-wider">
                   <span>Data rooms, meeting notes</span>
                 </div>
                 <div class="bg-white border border-gray-200 rounded p-4 shadow-sm flex items-center gap-4">
                   <div class="h-8 w-8 bg-blue-600 rounded flex items-center justify-center text-white">
                     <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5">
                       <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12.75V12A2.25 2.25 0 0 1 4.5 9.75h15A2.25 2.25 0 0 1 21.75 12v.75m-8.69-6.44-2.12-2.12a1.5 1.5 0 0 0-1.061-.44H4.5A2.25 2.25 0 0 0 2.25 6v12a2.25 2.25 0 0 0 2.25 2.25h15A2.25 2.25 0 0 0 21.75 18V9a2.25 2.25 0 0 0-2.25-2.25h-5.379a1.5 1.5 0 0 1-1.06-.44Z" />
                     </svg>
                   </div>
                   <div class="text-sm font-medium text-gray-900">Filings and Earnings</div>
                 </div>
                 <div class="text-xs text-gray-300 uppercase tracking-wider text-center">
                   Market data
                 </div>
               </div>
             </div>
           </div>
        </div>
      </div>

      <!-- Right Column: Features List -->
      <div class="lg:pl-8">
        <h3 class="text-3xl font-serif font-medium tracking-tight text-gray-900 mb-12">
          An Integrated, Secure Platform<br>Built to Drive Your Firm Forward
        </h3>
        <dl class="space-y-10">
          {#each [
            { id: '01', title: 'All your content in one place' },
            { id: '02', title: 'Transparent, auditable sources' },
            { id: '03', title: 'Automate your workflows' },
            { id: '04', title: 'Proprietary document interrogation' }
          ] as feature}
            <div class="relative flex gap-x-6 items-center">
              <div class="flex h-12 w-12 flex-none items-center justify-center rounded-xl border border-gray-200 bg-white shadow-sm">
                <!-- Hexagon-ish shape or just number -->
                <span class="text-sm font-semibold text-gray-400 font-mono">{feature.id}</span>
              </div>
              <dt class="text-lg leading-7 text-gray-600 font-light">
                {feature.title}
              </dt>
            </div>
          {/each}
        </dl>
      </div>
    </div>
  </div>
</section>
