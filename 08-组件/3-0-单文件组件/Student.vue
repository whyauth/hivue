<template>
  <div>
      <h2>学生名称:{{name}}</h2>
      <h2>家庭住址:{{address}}</h2>
  </div>
</template>

<script>
export default {
    name:'Studnet',
    data(){
        return {
            name:'王浩羽',
            address:'鹤霞路600弄'
        }
    }
}
</script>

<style>

</style>