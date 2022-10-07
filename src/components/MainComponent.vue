<template>
  <main>
    <InitialInfoCardComponent />
    <CompanyComponent />
    <CardContentComponent />
    <PriceTableComponent />
    <LatestNewComponent />
    <NewsletterComponent />
    <SendInfoMessageComponent />
  </main>
</template>

<script>
import InitialInfoCardComponent from '@/components/InitialInfoCardComponent.vue';
import CompanyComponent from './CompanyComponent.vue';
import CardContentComponent from './CardContentComponent.vue';
import SendInfoMessageComponent from './SendInfoMessageComponent.vue';
import NewsletterComponent from './NewsletterComponent.vue';
import LatestNewComponent from './LatestNewComponent.vue';
import PriceTableComponent from './PriceTableComponent.vue';

export default {
name : 'MainComponent',
components : {
    InitialInfoCardComponent,
    CompanyComponent,
    CardContentComponent,
    SendInfoMessageComponent,
    NewsletterComponent,
    LatestNewComponent,
    PriceTableComponent
}
}
</script>

<style lang="scss" scoped>


</style>