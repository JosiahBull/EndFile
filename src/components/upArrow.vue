<template>
  <svg
    class="bi bi-arrow-up"
    :width="width"
    :height="height"
    viewBox="0 0 16 16"
    :fill="iconColor"
  >
    <title :id="iconName" lang="en">{{ iconName }} icon</title>
    <path
      fill-rule="evenodd"
      d="M8 3.5a.5.5 0 0 1 .5.5v9a.5.5 0 0 1-1 0V4a.5.5 0 0 1 .5-.5z"
    />
    <path
      fill-rule="evenodd"
      d="M7.646 2.646a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1-.708.708L8 3.707 5.354 6.354a.5.5 0 1 1-.708-.708l3-3z"
    />
  </svg>
</template>
<script>
export default {
  props: {
    iconName: {
      type: String,
      default: "box"
    },
    width: {
      type: [Number, String],
      default: 18
    },
    height: {
      type: [Number, String],
      default: 18
    },
    iconColor: {
      type: String,
      default: "currentColor"
    }
  }
};
</script>
