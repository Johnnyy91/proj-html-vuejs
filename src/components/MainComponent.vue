<template>
  <main>
    <InitialInfoCardComponent />
    <CompanyComponent />
    <CardContentComponent />
    <SendInfoMessageComponent />
  </main>
</template>

<script>
import InitialInfoCardComponent from '@/components/InitialInfoCardComponent.vue';
import CompanyComponent from './CompanyComponent.vue';
import CardContentComponent from './CardContentComponent.vue';
import SendInfoMessageComponent from './SendInfoMessageComponent.vue';

export default {
name : 'MainComponent',
components : {
    InitialInfoCardComponent,
    CompanyComponent,
    CardContentComponent,
    SendInfoMessageComponent,
}
}
</script>

<style lang="scss" scoped>


</style>