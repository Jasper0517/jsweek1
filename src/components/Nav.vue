<template>
    <div class="nav">
        <ul>
            <li>{{msg}}</li>
            <li>{{msg}}</li>
            <li>{{msg}}</li>
        </ul>
    </div>
</template>

<script>
    export default {
    name: 'nav',
    data () {
        return {
        msg: 'Welcome to Your Vue.js App'
        }
    }
}
</script>

<style lang="scss" scoped>
    .nav{
        width: 600px;
        height: 100px;
        background-color: RGBA(100, 146, 214, 1.00);
    }
</style>

