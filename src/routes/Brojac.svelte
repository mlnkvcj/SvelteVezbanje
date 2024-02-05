<script>
    let count = 0;
    let buttonsClicked = 0;
    function increment(){
        count ++;
    }
    function decrement(){
        count--;
    }
    function reset(){
        count = 0;
    }
</script>

<button on:click={decrement}>-</button>
{count}
<button on:click={increment}>+</button>