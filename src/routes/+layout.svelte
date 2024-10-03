<script>
    import "../app.css";
</script>
<div id="nav" class="bg-slate-900 text-slate-50">
    <h1 class="text-4xl text-green-500">Terminal</h1>
    <h1 class="text-4m"><a href="/">Home</a> | <a href="/games">Games</a> | <a href="/about">About</a></h1>
</div>
<slot />
<div id="nav" class="bg-slate-900 text-slate-700 text-center">
    <p>With ❤️, from CO</p>
    <p>(C) 2024</p>
</div>
<style>
    * :global() {
        background-color: bg-slate-900;
        color: text-slate-50;
    }
</style>