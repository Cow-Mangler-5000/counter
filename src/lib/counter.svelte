<script lang="ts">
    let count = $state(0);

    const setCountIncrement = () => {
        count++;
    };

    const setCountDecrement = () => {
        count--;
    };
</script>

<div class="c">
    <button onclick="{()=>{setCountIncrement()}}">Increment</button>
    <button onclick="{()=>{setCountDecrement()}}">Decrement</button>
    <p>{count}</p>
</div>

<style lang="scss">

@mixin btn {
    border: 2px solid rgb(0, 0, 0);
    background-color: beige;
    box-shadow: 1px 1px 2px 2px rgb(192, 192, 192);
    border-radius: 4px;
}

button {
    @include btn();
}

</style>