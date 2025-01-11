<script lang="ts">
    import Counter from "./lib/counter.svelte";
</script>

<style lang="scss">

:root {
    font-family: sans-serifs;
    font-size: 20px;
    text-align: center;
}

.c {
    width: 100vw;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

c {
    border: 1px solid black;
    border-radius: 10px;
    padding: 20px;
    box-shadow: 1px 1px 1px 2px black;
}

</style>

<div class="c">
    <c>
        <Counter/>
    </c>
</div>