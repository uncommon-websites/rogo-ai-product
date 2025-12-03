<script lang="ts">
  import Button from './ui/Button.svelte';
</script>

<header class="sticky top-0 z-50 w-full bg-white/80 backdrop-blur-md border-b border-transparent">
  <div class="mx-auto flex h-20 max-w-7xl items-center justify-between px-6 lg:px-8">
    <div class="flex lg:flex-1">
      <a href="/" class="-m-1.5 p-1.5 text-2xl font-semibold tracking-tight">
        rogo
      </a>
    </div>
    <nav class="hidden lg:flex lg:gap-x-8">
      <a href="#product" class="text-sm font-medium leading-6 text-gray-900 hover:text-gray-600">Product</a>
      <a href="#security" class="text-sm font-medium leading-6 text-gray-900 hover:text-gray-600">Security</a>
      <a href="#company" class="text-sm font-medium leading-6 text-gray-900 hover:text-gray-600">Company</a>
      <a href="#news" class="text-sm font-medium leading-6 text-gray-900 hover:text-gray-600">News</a>
      <a href="#careers" class="text-sm font-medium leading-6 text-gray-900 hover:text-gray-600">Careers</a>
    </nav>
    <div class="flex flex-1 items-center justify-end gap-x-6">
      <a href="#login" class="hidden text-sm font-medium leading-6 text-gray-900 hover:text-gray-600 lg:block">Log in</a>
      <Button href="#demo">Request Demo</Button>
    </div>
  </div>
</header>
