<template>
    <div id="main-section">
        <Welcome/>
        <Doctors/>
        <Healt/>
        <Facilities/>
        <Service/>
        <Appointment/>
        <InteractiveIcon/>
    </div>
</template>

<script>
import Welcome from '../components/Welcome.vue'
import Doctors from '../components/Doctors.vue'
import Healt from '../components/Healt.vue'
import Facilities from './Facilities.vue'
import Service from './Service.vue'
import Appointment from './Appointment.vue'
import InteractiveIcon from './InteractiveIcon.vue'

export default {
    name:'Main',
    components: {
        Welcome,
        Doctors,
        Healt,
        Facilities,
        Service,
        Appointment,
        InteractiveIcon,
    }
}
</script>

<style lang="scss">

@import "../style/variables.scss";

</style>