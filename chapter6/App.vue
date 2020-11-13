<template>
  <p class="message">メッセージ: {{ msg }}</p>
</template>

<script>
export default {
  data() {
    return { msg: "こんちは" };
  },
};
</script>

<style>
.message {
  color: aqua;
}
</style>