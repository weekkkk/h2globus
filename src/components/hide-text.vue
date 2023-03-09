<script lang="ts" setup>
import { ref } from 'vue';

const visible = ref(false);

const props = defineProps({
  styles: { type: String, default: '' },
});
</script>

<template>
  <div class="f fd-col rg-2">
    <Transition name="text">
      <div v-if="visible" class="f fd-col rg-2">
        <slot />
      </div>
    </Transition>
    <div class="f fd-col ai-c fw-medium" :style="styles">
      <p style="cursor: pointer" v-if="!visible" @click="visible = !visible">
        <u> Показать ещё </u>
      </p>
      <p style="cursor: pointer" v-else @click="visible = !visible">
        <u> Скрыть </u>
      </p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.text-enter-active,
.text-leave-active {
  transition: 0.5s ease-in-out;
  max-height: 1000px;
  overflow: hidden;
}

.text-enter-from,
.text-leave-to {
  opacity: 0;
  max-height: 0;
  overflow: hidden;
}
</style>
