<script>
  export let href = "/";
  export let selected = false;
</script>

<li>
  <a class="text-gray-600 transition hover:text-gray-600/75 relative" {href}>
    <slot />
    {#if selected}
      <span
        class="absolute bottom-0 left-0 w-2/3 h-0.5 rounded-md bg-[#2590EB] transform translate-y-2"
      />
    {/if}
  </a>
</li>
