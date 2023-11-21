<template>
    <div>
        <h2>{{ personName }}</h2>
    </div>
</template>

<script>
//组件交互的相关代码（数据，方法等）
// 默认暴露（js模块化）简写 + 省去Vue.extend() （Vue发现传入参数是配置对象的时候自动调用Vue.extend）
export default {
    // 防止其它人对名字进行修改
    name: 'Person',
    data() {
        return {
            personName: "tyler",
        };
    },
};
</script>

<style>
/* 组件的样式 */
.demo {
    background-color: orange;
}
</style>