<template>
  <div id="app">
   <Todos v-bind:todos="todos"/>
  </div>
</template>
<script>
import Todos from './components/Todos';
export default {
  name: 'app',
  components: {
    Todos
  },
  data(){
    return{
      todos:[{
        id:1,
        title:'Todo one',
        completed:false

      },{
        id:1,
        title:'Todo two',
        completed:true
        },
        {
        id:1,
        title:'Todo three',
        completed:false
        }]
    }
  }
}
</script>
