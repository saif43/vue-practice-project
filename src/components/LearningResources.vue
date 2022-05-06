<template>
    <li>
       <div>
           <header>
               <h3>{{resource.title}}</h3>
               <button>Delete</button>
           </header>
       </div>
       <p>{{resource.description}}</p>
       <nav>
           <a href="resource.link">View resource</a>
       </nav>
    </li>
</template>
<script>
export default {
    name: 'LearnResources',
    props: {
        resource: Object
    }
}
</script>
<style lang="">
    
</style>