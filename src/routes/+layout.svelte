<script>
    import Navbar from "$lib/components/Navbar.svelte";
import "../app.css";
</script>

<div class="h-screen w-screen bg-slate-800">
    <div class="flex flex-col size-full">
      <Navbar></Navbar>
      <slot></slot>
    </div>
  </div>
