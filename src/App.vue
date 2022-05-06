<template>
    <ul>
        <LearningResources v-for="item in storedResources" :key="item.id" :resource="item" />
    </ul>
</template>
<script>
import LearningResources from './components/LearningResources.vue'


export default {
    name: 'App',
    components: {
        LearningResources
    },
    data(){
        return {
            storedResources: [
                {
                    id: 1,
                    title: 'Vue.js',
                    description: 'Learn vue.js',
                    link: 'https://vuejs.org',
                },
                {
                    id: 2,
                    title: 'Google',
                    description: 'Learn to use google',
                    link: 'https://google.com',
                },
            ]
        }
    }
}
</script>
<style lang="">
    
</style>