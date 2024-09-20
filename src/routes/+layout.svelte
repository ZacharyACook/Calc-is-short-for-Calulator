<script>
    import Navbar from "$lib/components/Navbar.svelte";
import "../app.css";
</script>

<div class="h-screen w-screen bg-slate-800">
    <Navbar></Navbar>
    <slot></slot>
</div>
