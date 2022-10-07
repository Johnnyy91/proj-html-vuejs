<template>
  <main>
    <InitialInfoCardComponent />
    <CompanyComponent />
    <CardContentComponent />
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

export default {
name : 'MainComponent',
components : {
    InitialInfoCardComponent,
    CompanyComponent,
    CardContentComponent,
    SendInfoMessageComponent,
    NewsletterComponent,
    LatestNewComponent,
}
}
</script>

<style lang="scss" scoped>


</style>