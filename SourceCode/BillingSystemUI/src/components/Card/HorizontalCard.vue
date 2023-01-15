<template>
  <button>{{ buttonText }}, {{ buttonURL }}</button>
</template>

<script>

export default {
  props: {
    buttonText: {
      type: String,
      default: () => "Button Label"
    },
    buttonURL: {
      type: String,
      default: () => "https:nazibmahfuz.com"
    }
  }
};
</script>
