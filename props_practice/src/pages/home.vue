<template>
    <h2>Props Practice</h2>
    <student name="Poonam"/>
</template>

<script>
import student from '../components/student.vue';

export default{
    components:{student},

    data(){
        return{
            name : "Vishu"
        }
    }
}
</script>