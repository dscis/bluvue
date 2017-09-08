<template>
  <li>
    <a v-if="!hasSlot" :href="to">{{ label }}</a>
    <slot></slot>
  </li>
</template>
<script>
import utils from '../../utils/utils';

export default {
  props: {
    label: {
      type: String,
    },
    to: {
      type: String,
      default: '',
    },
  },
  computed: {
    hasSlot() {
      if (utils.isEmpty(this.$slots)) return false;
      return true;
    },
  },
};
</script>
