<template>
    <div>
        <header>
            <!-- router-link 定义点击后导航到哪个路径下 -->
            <router-link to="/list/123">List</router-link>
            <router-link to="/bar">Bar</router-link>
        </header>
        <!-- 对应的组件内容渲染到router-view中 -->
        <router-view></router-view>
    </div>
</template>

<script>
export default {};
</script>
