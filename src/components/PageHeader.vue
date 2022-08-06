<template>
    <header>
        <h3>LOGO HERE</h3>
        <nav>
            <a href="">LINK ONE</a>
            <a href="">LINK TWO</a>
            <a href="">LINK THREE</a>
        </nav>
    </header>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    header {
        display: grid;
        grid-template-columns: auto 1fr;
        place-items: center;
    }

    nav {
        justify-self: end;
        display: grid;
        place-items: center;
        grid-auto-flow: column;
        gap: 10px;
    }
</style>