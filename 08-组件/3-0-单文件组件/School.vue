<template>
  <div>
    <h2>学校名称：{{name}}</h2>
    <h2>学校地址：{{address}}</h2>
  </div>
</template>

<script>
export default {
    name:'School',
    data(){
        return {
            name:'复旦大学',
            address:'上海市鹤霞路'
        }
    }
}
</script>

<style>
    
</style>