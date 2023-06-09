<script setup>
import WelcomeItem from './WelcomeItem.vue'

</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading><div class="bg-white py-24 sm:py-32">
        <h1></h1>
   </div></template>

  
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>


   
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading></template>

  
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading></template>

  
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading></template>

    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener"></a>.
  </WelcomeItem>
</template>
