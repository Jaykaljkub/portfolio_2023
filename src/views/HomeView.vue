<script setup lang="ts">
import { ref } from 'vue'
import TheWelcome from '../components/TheWelcome.vue'
import TheLanding from '../components/TheLanding.vue'

var msg = ref('words');
</script>

<template>
  <main>
   <TheLanding>
    <template #bob>Not a thingy</template>
   </TheLanding>

   <TheLanding>
    <template #bob>Maybe a thingy</template>
   </TheLanding>

   <TheLanding>
    <template #bob>Most defintely a thingy</template>
   </TheLanding>
   
  </main>
</template>
