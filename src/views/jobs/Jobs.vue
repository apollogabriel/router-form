<template>
    <div>
        <h1>Jobs</h1>
        <div v-for="job in jobs" :key="job.id">
            <h2>{{ job.title }}</h2>
        </div>
    </div>
    
</template>
<script>
    export default{
        data(){
            return{
                jobs:[
                    {
                        title:'Web developer',
                        id:1,
                        details:'Programmer'
                    },
                    {
                        title:'Web Designer',
                        id:2,
                        details:'Design'
                    },
                ]
            
            }
        }
    }
</script>
<style>
</style>