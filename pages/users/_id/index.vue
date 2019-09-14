<template>
    <div class="container">
        <h2>
            <center>Este es el usuario que selecionaste{{ $route.params.id }}</center>
        </h2>
        
        
    </div>
</template>
<script>
export default {
    validate ({ params }) {
    // Must be a number 
        return /^\d+$/.test(params.id)
    }
}
</script>