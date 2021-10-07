<template>
    <div id="main-section">
        <Welcome/>
        <Doctors/>
    </div>
</template>

<script>
import Welcome from '../components/Welcome.vue'
import Doctors from '../components/Doctors.vue'
export default {
    name:'Main',
    components: {
        Welcome,
        Doctors,
    }
}
</script>

<style lang="scss" scoped>

@import "../style/variables.scss";

</style>