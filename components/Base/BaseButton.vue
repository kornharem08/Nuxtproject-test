<template>
    <div>
        <t-button variant="primary">{{type}}</t-button>
    </div>
</template>

<script>
export default {
     props: {
    type: String,
  }
}
</script>