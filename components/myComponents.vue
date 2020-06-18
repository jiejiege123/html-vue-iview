<!--
 * @Author: your name
 * @Date: 2020-06-18 16:12:00
 * @LastEditTime: 2020-06-18 16:12:01
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \bpsp-uie:\doit\html-vue\components\my-components.vue
--> 
<template>
  <Slider v-model="value" range />
</template>
<script>
export default {
  data() {
    return {
      value: [20, 50]
    };
  }
};
</script>