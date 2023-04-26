<script>
    let name = "World";

    let value = 0;
</script>

<h1>Hello {name}!!!</h1>

<p>{value}</p>
<button
    on:click={() => {
        value--;
    }}>-</button
>
<button
    on:click={() => {
        value++;
    }}>+</button
><br />
<button
    on:click={() => {
        value = 0;
    }}>reset</button
>
