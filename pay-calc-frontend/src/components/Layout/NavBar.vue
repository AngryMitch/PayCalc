<template>
    <div class="nav-main">
        <NavButton buttonTitle="Signup" />
    </div>
</template>

<script>
import NavButton from '../UI/NavButton.vue'

export default {
    name: 'NavMain',
    components: {
        NavButton
    },
    props: {
        accountname: String
    }
}
</script>

<style scoped>
.nav-main {
    height: 100px;
    display: inline-block;
}
</style>