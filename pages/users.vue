<template>
    <div class="container">
        <h1>Ususarios en la lista</h1>
        <ul>
            <nuxt-link to="users/1">First user</nuxt-link>
            <nuxt-link to="users/2">Second user</nuxt-link>            
        </ul>
        <br>
        <nuxt-child />        
    </div>
</template>

<script>
export default {
    layout : 'users'
}
</script>