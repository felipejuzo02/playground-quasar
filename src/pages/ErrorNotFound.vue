<template>
  <div
    class="bg-blue flex flex-center fullscreen q-pa-md text-center text-white"
  >
    <div>
      <div>404</div>

      <div class="text-h2">Oops. Nothing here...</div>

      <q-btn
        class="q-mt-xl"
        color="white"
        label="Go Home"
        no-caps
        text-color="blue"
        to="/"
        unelevated
      />
    </div>
  </div>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "ErrorNotFound",
});
</script>
