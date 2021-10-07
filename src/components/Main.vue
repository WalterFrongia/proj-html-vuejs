<template>
    <div id="main-section">
        <Welcome/>
    </div>
</template>

<script>
import Welcome from '../components/Welcome.vue'
export default {
    name:'Main',
    components: {
        Welcome,
    }
}
</script>

<style lang="scss" scoped>

@import "../style/variables.scss";

</style>