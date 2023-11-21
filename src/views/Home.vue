<template>
    <NavbarComponent />
    <TaskItem />
</template>

<script>
import NavbarComponent from '../components/common/Navbar.vue'
import TaskItem from '../components/tasks/TaskItem.vue'
export default{
    name: 'HomeView',
    components: {
        NavbarComponent,
        TaskItem
    }
}
</script>