<script setup>
import { TextBoxComponent as EjsTextbox } from "@syncfusion/ej2-vue-inputs";
import { ButtonComponent as EjsButton } from "@syncfusion/ej2-vue-buttons";
</script>

<template>

  <div>
    <form class="flex flex-col items-center gap-6 p-7">
      <input class="e-input" type="text" placeholder="Enter something" />
    </form>
  </div>

</template>

<style scoped>
  @import "../node_modules/@syncfusion/ej2-base/styles/tailwind.css";
  @import "../node_modules/@syncfusion/ej2-vue-inputs/styles/tailwind.css";
</style>
