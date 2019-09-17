<template>
    <div>
        <h3>Uppsssss..... presentamos un error en la carga</h3>
        <br>
        <button @click="inicio">Cliceka para el inicio</button>
    </div>
</template>
<script>
export default {
        
    methods : {
        inicio:function(){               
            this.$router.push('/')
        }
    },
}
</script>