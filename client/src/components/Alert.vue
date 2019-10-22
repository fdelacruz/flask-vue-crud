<template>
  <div>
    <b-alert variant="success" :show="dismissCountDown" dismissible>{{ message }}</b-alert>
    <br>
  </div>
</template>

<script>
export default {
  data() {
    return {
      dismissCountDown: 5,
    };
  },
  props: ['message'],
};
</script>
