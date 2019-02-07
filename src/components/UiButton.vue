<template>
  <div class="ui-button">
    <button class="ui-button__element" v-bind="$attrs" v-on="$listeners">
      <div class="ui-button__body">
        <slot></slot>
      </div>
    </button>
  </div>
</template>

<script>
export default {
  name: 'ui-button',
};
</script>

<!-- this is not working -->
<style src="../styles/components/UiButton.scss" lang="scss" />

<!-- this works however -->
<!-- style lang="scss">
@import '../styles/components/UiButton';
</style -->
