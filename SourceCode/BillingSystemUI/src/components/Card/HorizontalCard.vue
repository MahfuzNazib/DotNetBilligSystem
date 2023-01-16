<template>
  <button class="btnBaseClass">
    {{ buttonText }}
  </button>
</template>

<script>

export default {
  props: {
    buttonText: {
      type: String,
      default: () => "Label"
    },
  }
};
</script>

<style scoped>
.btnBaseClass{
  padding: 15px;
  border-radius: 4px;
  border: 0.5px;
  margin-top: 2px;
  margin-bottom: 2px;
  cursor: pointer;
  width: 100%;
  box-shadow: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.06) 0px 2px 4px -1px;
}
.btnBaseClass:hover{
  border: 0.3px solid gray;
  background-color: black;
  color: white;
  transition: 1ms;
}
</style>
