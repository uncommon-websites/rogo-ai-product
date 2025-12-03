<script lang="ts">
  export let variant: 'primary' | 'secondary' | 'outline' = 'primary';
  export let href: string | undefined = undefined;
  export let className: string = '';
</script>

{#if href}
  <a
    {href}
    class="inline-flex items-center justify-center rounded-full px-6 py-2.5 text-sm font-medium transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-offset-2 disabled:pointer-events-none disabled:opacity-50
    {variant === 'primary' ? 'bg-gray-900 text-white hover:bg-gray-800' : ''}
    {variant === 'secondary' ? 'bg-gray-100 text-gray-900 hover:bg-gray-200' : ''}
    {variant === 'outline' ? 'border border-gray-200 bg-white hover:bg-gray-100 text-gray-900' : ''}
    {className}"
  >
    <slot />
  </a>
{:else}
  <button
    class="inline-flex items-center justify-center rounded-full px-6 py-2.5 text-sm font-medium transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-offset-2 disabled:pointer-events-none disabled:opacity-50
    {variant === 'primary' ? 'bg-gray-900 text-white hover:bg-gray-800' : ''}
    {variant === 'secondary' ? 'bg-gray-100 text-gray-900 hover:bg-gray-200' : ''}
    {variant === 'outline' ? 'border border-gray-200 bg-white hover:bg-gray-100 text-gray-900' : ''}
    {className}"
  >
    <slot />
  </button>
{/if}
