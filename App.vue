<template>
  <div id="app">
    <CustomHeader />
    <router-view />
    <CustomFooter />
  </div>
</template>

<script>
import CustomHeader from './components/CustomHeader.vue';
import CustomFooter from './components/CustomFooter.vue';

export default {
  components: {
    CustomHeader,
    CustomFooter,
  },
};
</script>

