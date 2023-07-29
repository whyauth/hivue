<template>
    <div>
        <h3>学校组件</h3>
        <Student></Student>
    </div>
</template>


<script>
import Student from './Student.vue';
export default {
    name: 'School',
    data(){
        return {
            name:"上海中学",
            address:"徐汇区666弄",
        }
    },
    props: {},
    components:{Student},
    methods: {}
}
</script>

<style scoped>
    
</style>