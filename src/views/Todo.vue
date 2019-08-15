<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <TodoList/>
  </div>
</template>

<script lang="ts">
  import { Component, Vue } from 'vue-property-decorator'
  import TodoList from '@/components/TodoList.vue'

  @Component({
    components: {
      TodoList,
    },
  })
  export default class Todo extends Vue {}
</script>
