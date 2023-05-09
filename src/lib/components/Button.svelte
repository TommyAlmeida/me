<script>
  export let href = "/";
  export let rounded = false;
  export let variant = "bg-black";

  const isRounded = rounded ? "rounded-md" : "";
  const adaptHoverBasedOnVariant = "hover:" + variant + "/75";
</script>

<a
  class="{isRounded} {variant} {adaptHoverBasedOnVariant}
    px-5 py-2.5 text-sm font-medium text-white shadow transition-colors
  "
  {href}
>
  <slot />
</a>
