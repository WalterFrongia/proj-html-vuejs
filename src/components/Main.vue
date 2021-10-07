<template>
    <div id="main-section">
        <Welcome/>
        <Doctors/>
        <Healt/>
    </div>
</template>

<script>
import Welcome from '../components/Welcome.vue'
import Doctors from '../components/Doctors.vue'
import Healt from '../components/Healt.vue'
export default {
    name:'Main',
    components: {
        Welcome,
        Doctors,
        Healt,
    }
}
</script>

<style lang="scss" scoped>

@import "../style/variables.scss";

</style>