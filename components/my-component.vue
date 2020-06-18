<!--
 * @Author: your name
 * @Date: 2020-06-18 16:12:00
 * @LastEditTime: 2020-06-18 17:57:55
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \bpsp-uie:\doit\html-vue\components\my-components.vue
--> 

<template>
    <div class="hello">
        Hello {{who}}
    </div>
</template>
 
<script>
    module.exports={
        name: 'myComponent',
        data: function () {
            return {
                who: 'world'
            }
        }
    }
</script>
