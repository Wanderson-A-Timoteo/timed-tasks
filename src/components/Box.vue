<template>
  <div class="box has-text-weight-bold" :style="estilos">
    <slot></slot>
  </div>
</template>

<script lang="ts">
  import { defineComponent } from 'vue';
  export default defineComponent({
    // eslint-disable-next-line vue/multi-word-component-names
    name: 'Box',
    data() {
      return {
        estilos: {
          background: '#FFF8E9'
        }
      };
    },
  })
</script>
