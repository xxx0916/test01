<template>
    <div>
        <CountInfo></CountInfo>
        <hr>
        <Person></Person>
    </div>
</template>

<script>
import CountInfo from "./components/CountInfo.vue";
import Person from "./components/Person.vue";

// 引入组件
export default {
    name: "App",
    components: { CountInfo, Person },

}
</script>
<style>
.container,
.foot {
    display: flex;
    justify-content: space-around;
}

h4 {
    text-align: center;
}
</style>
