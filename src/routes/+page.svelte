<script>
    import Lista from "./Lista.svelte";
    let inputValue = 0;
</script>
<input type="number" min="0" bind:value="{inputValue}">
<br>
<Lista n={inputValue}></Lista>





