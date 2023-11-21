<template lang="en">
    <div>
        <Person />
        <School />
    </div>
</template>
<script>
// 引入组件
// 在脚手架中可以不写文件后缀 './Person' ，默认为.vue 
import Person from './Person';
import School from './School';

export default {
    name: 'App',
    template: `<App />`,
    components: {
        Person,
        School
    }

}
</script>
<style lang="">
    
</style>