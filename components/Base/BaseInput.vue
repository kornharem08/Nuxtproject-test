<template>
  <div>
      <label>
  {{ label }}
    <t-input
      :type="type"
      :placeholder="placeholder"
    />
      </label>
  </div>
</template>

<script>
export default {
  props: {
    label: String,
    type: String,
    placeholder: String
  }
}
</script>