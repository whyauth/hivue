<template>
    <div>
        <School/>
        <Student/>
    </div>
</template>

<script>

import School from './School.vue'
import Studnet from './Student.vue'

export default {
    name:'App',
    components:{
        School,
        Studnet,        
    }
}
</script>

<style>

</style>