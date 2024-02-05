<script>
    import Brojac from "./Brojac.svelte";
    export let n = 0;
    $:lista = Array.apply(null,Array(n));
</script>
{#each lista as i}
    <Brojac></Brojac>
    <br>
{/each}
