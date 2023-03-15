<script lang="ts" setup>
import { ref } from 'vue';

const visible = ref(false);

const props = defineProps({
  styles: { type: String, default: '' },
});
</script>

<template>
  <div class="f fd-col rg-2" style='display: inline;'>
    <Transition name="text">
      <div v-if="visible" class="f fd-col rg-2">
        <slot />
      </div>
    </Transition>
    <div class="hide-text f fs-small-p fd-col ai-fs fw-regular" :style="styles">
      <span style="cursor: pointer" v-if="!visible" @click="visible = !visible">
        Показать ещё
      </span>
      <span style="cursor: pointer" v-else @click="visible = !visible">
        Скрыть
      </span>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.hide-text {
  display: inline !important;  
}
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
