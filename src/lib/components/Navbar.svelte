<script>
  
  const navitems = [{ label: "Home", path: "/"}, {label:"Test", path:"/Test"}];
</script>

<div class=" w-full h-[60px] bg-white rounded-md flex gap-10">
    {#each navitems as route}
     <a class="bg-gray-200"href={route.path}>{route.label}</a>
    {/each}
</div>

