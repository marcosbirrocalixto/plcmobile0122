<template>
    <div>
        <header-component></header-component>

        <section>
            <router-view></router-view>
        </section>

        <footer-component></footer-component>
    </div>
</template>

<script>
import HeaderComponent from '@/layouts/components/HeaderComponent.vue'
import FooterComponent from '@/layouts/components/FooterComponent.vue'

export default {
    name: 'DefaultTemplate',
    components: {
       HeaderComponent,
       FooterComponent,
    }
}
</script>

<style scoped>
@import url('../assets/css/plcmobile.css');
@import url('../assets/css/reset.css');

</style>