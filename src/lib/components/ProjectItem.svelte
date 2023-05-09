<script>
  export let title = "Project Title";
  export let subtitle = "Project Subtitle";
  export let image = "";
</script>

<div class="w-full md:w-1/2 lg:w-1/3 p-4">
  <div class="h-full max-w-xs mx-auto rounded-lg overflow-hidden shadow-md">
    <img class="w-96 h-64 object-cover" src={image} alt={title} />
    <div class="py-3 px-4">
      <h2 class="text-xl font-bold mb-2">{title}</h2>
      <p class="text-gray-600 text-base mb-2">{subtitle}</p>
    </div>
  </div>
</div>
