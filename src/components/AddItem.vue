<template>
  <form @submit="addItem" class="add-items d-flex">
    <input type="text" class="form-control todo-list-input" placeholder="What do you need to do today?" v-model="title">
    <button class="add btn btn-primary font-weight-bold todo-list-add-btn">Add</button>
  </form>
</template>

<script>
import { ref } from '@vue/composition-api'
export default {
name: "AddItem",
  setup(props,context) {
  const title = ref('')
  const addItem = event => {
    event.preventDefault()
    const newItem = {
      title: title.value,
      completed: false
    }
    context.emit('add-item', newItem)
    title.value = ''
  }
  return {
    title,
    addItem
  }
  }
}
</script>

<style scoped>

</style>
