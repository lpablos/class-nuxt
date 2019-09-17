<template>
    <ul>
        <li> <button @click="raiz">inicio</button> </li>
        <li> <button @click="usuarios">Usuarios</button> </li>
        <li> <button @click="usuario"> Usuario 1</button> </li>
        <nuxt-link to="about">Algun error</nuxt-link>
    </ul>
</template>


<script>
    export default {
        methods:{

            raiz:function(){
                this.$router.push('/')
                // this.$router.push('users')  
            },
            usuarios: function(){
                this.$router.push('users')
            },
            usuario:function(){
                this.$router.push('users/1')
            }

        }
        
    }
</script>