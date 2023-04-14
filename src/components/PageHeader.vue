<template>
    <div class="header">
        <h2>LOGO</h2>
        <nav>
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Contact</a>

        </nav>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
div{
    min-height: 10vh;
    background-color: black;
    display:grid;
    place-items: center;
    grid-template-columns: 1fr 1fr;
    padding: 16px;

}
h2{
    color:lightgray;
    justify-self:start;
    align-self: center;

    
}
nav{
    justify-self: end;
    align-self: center;
    display:grid;
    place-items: center;
    grid-template-columns: 1fr 1fr 1fr;
}
a{
    color:lightgray;
    width:60px;
   text-decoration: none;
}
</style>