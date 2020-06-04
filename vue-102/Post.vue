<template>
  <div>
    <div>
      <h5 style="color: #554d3f">{{item.title}}</h5>
      <p>{{item.body}}</p>
    </div>
    <div>
      <button type="button" @click="$emit('edit-item', item)" style="margin-right: 3px">Edit</button>
      <button type="button" @click="$emit('delete-item', item)">Delete</button>
    </div>
  </div>
</template>

<script>
export default {
  props: ["item"]
};
</script>

<style>
</style>