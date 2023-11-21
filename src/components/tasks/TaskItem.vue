<template>
<div class="d-flex justify-content-between p-1">
    <div>
        <CheckboxComponent />
        <span class="ms-3">Задача</span>
    </div>
    <div>
        <TaskItemProject />
    </div>
</div>
</template>

<script>
import CheckboxComponent from '../ui/Checkbox.vue'
import TaskItemProject from './Items/TaskItemProject.vue'
export default{ 
    name: 'TaskItem',
    components: { 
        CheckboxComponent,
        TaskItemProject
    }
}
</script>