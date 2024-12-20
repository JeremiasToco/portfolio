<script setup>
import TheWelcome from '../components/TheWelcome.vue'
import Menu from '../components/menu.vue'
import navbar from '@/components/navbar.vue';
import banner from '@/components/banner.vue';
import sobre from '@/components/sobre.vue';
import servico from '@/components/servico.vue';
import tools from '@/components/tools.vue';
import contact from '@/components/contact.vue';
import foote from '@/components/footer.vue';
</script>

<template>
  <div>
    <navbar/>
    <banner/>
    <sobre/>
    <tools/>
    <servico/>
    <contact/>
    <foote/>
  </div>
</template>



