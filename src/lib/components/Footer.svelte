<script lang="ts">
  import Button from './ui/Button.svelte';
</script>

<footer class="bg-white">
  <div class="mx-auto max-w-7xl px-6 py-16 lg:px-8 lg:py-24">
    <div class="flex flex-col lg:flex-row lg:items-end lg:justify-between mb-24 border-b border-gray-100 pb-24">
      <div class="max-w-2xl">
        <div class="mb-8">
           <!-- Logo Icon -->
           <svg class="w-10 h-10 text-gray-900" viewBox="0 0 24 24" fill="currentColor">
              <path d="M4 4h4v16H4V4zm12 0h4v16h-4V4z" />
           </svg>
        </div>
        <h2 class="text-4xl font-serif font-medium tracking-tight text-gray-900 sm:text-6xl">
          Unlock Financial AI<br>For Your Firm
        </h2>
      </div>
      <div class="mt-10 lg:mt-0">
        <Button href="#demo" className="bg-gray-900 text-white px-8 py-3 rounded-full text-base">Request Demo</Button>
      </div>
    </div>

    <div class="grid grid-cols-2 gap-8 md:grid-cols-4">
      <div>
        <h3 class="text-xs font-semibold leading-6 text-gray-900 uppercase tracking-wider mb-6">Overview</h3>
        <ul role="list" class="space-y-4">
          <li><a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900">Product</a></li>
          <li><a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900">Features</a></li>
          <li><a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900">Security</a></li>
        </ul>
      </div>
      <div>
        <h3 class="text-xs font-semibold leading-6 text-gray-900 uppercase tracking-wider mb-6">Company</h3>
        <ul role="list" class="space-y-4">
          <li><a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900">About</a></li>
          <li><a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900">Careers</a></li>
        </ul>
      </div>
      <div>
        <h3 class="text-xs font-semibold leading-6 text-gray-900 uppercase tracking-wider mb-6">Legal</h3>
        <ul role="list" class="space-y-4">
          <li><a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900">Terms of Use</a></li>
          <li><a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900">Privacy Policy</a></li>
        </ul>
      </div>
      <div>
        <h3 class="text-xs font-semibold leading-6 text-gray-900 uppercase tracking-wider mb-6">Contact</h3>
        <ul role="list" class="space-y-4">
          <li><a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900">Request Demo</a></li>
          <li><a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900">Sales</a></li>
          <li><a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900">LinkedIn</a></li>
          <li><a href="#" class="text-sm leading-6 text-gray-600 hover:text-gray-900">Press</a></li>
        </ul>
      </div>
    </div>
    <div class="mt-16 border-t border-gray-900/10 pt-8 sm:mt-20 lg:mt-24 text-center">
      <p class="text-xs leading-5 text-gray-500 uppercase tracking-widest">&copy; 2025 Rogo AI</p>
    </div>
  </div>
</footer>
