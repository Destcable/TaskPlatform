<template>
    <NavbarComponent />
    <div class="bg-white m-5">
        <TaskHeader/>
        <SeparatorComponent />
        <TaskItem />
        <SeparatorComponent />
        <TaskItem />
        <SeparatorComponent />
    </div>
</template>

<script>
import NavbarComponent from '../components/common/Navbar.vue'
import TaskHeader from '../components/tasks/TaskHeader.vue'
import TaskItem from '../components/tasks/TaskItem.vue'
import SeparatorComponent from '../components/ui/Separator.vue'
export default{
    name: 'HomeView',
    components: {
        NavbarComponent,
        SeparatorComponent,
        TaskHeader,
        TaskItem
    }
}
</script>

<style>
body{ 
    background-color: #F5F5F5;
}
</style>