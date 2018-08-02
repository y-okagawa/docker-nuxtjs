<template>
  <div>
    <p>{{ getMessage() }}</p>
  </div>
</template>

<script lang="ts">
    import Vue from 'vue';
    export default class TypeScriptSample extends Vue {
      message: string;
      constructor() {
        super();
        this.message = "okagaway";
      }

      getMessage(): string {
        return this.message;
      }
    }
</script>

<style scoped>

</style>
