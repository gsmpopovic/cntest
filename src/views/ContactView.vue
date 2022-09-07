<template>
    <div class="contact-form">
      <ContactForm/>
    </div>
  </template>
  
  <script>
  // @ is an alias to /src
  import ContactForm from '@/components/ContactForm.vue'
  
  export default {
    name: 'ContactView',
    components: {
      ContactForm
    }
  }
  </script>