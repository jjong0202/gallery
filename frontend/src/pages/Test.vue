<template>
  <div>
    {{ str }}
    {{obj.name}}
    test
    test    test
    test
    test    test
    test
    test
  </div>
</template>

<script setup>
import {reactive, ref} from "vue";



const str = ref("까꿍....");
const obj = reactive({
  name:'fadsfdasfdasfdasfdas',
  age:99
})

</script>

<style scoped>

</style>

}
