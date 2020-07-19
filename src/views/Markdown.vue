<template>
  <div class="markdown">
    <textarea class="editor" v-bind:placeholder="placeholder"></textarea>
  </div>
</template>

<script>
export default {
  name: 'Markdown',
  data () {
    return {
      placeholder: "Markdown記法で入力してみてください"
    }
  }
}
</script>

<style>
.markdown {
  height: 500px;
}
.editor {
  width: 80%;
  height: 70%;
  font-size: 1.6rem;
}
</style>