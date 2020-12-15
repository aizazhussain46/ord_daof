<template>
<v-app>
<v-app-bar app class="white" >
<v-toolbar-title class="headline text-uppercase">
    <div style="width: 42%; margin-left:37%;">
    <v-img   src="@/assets/header-logo-img.png" />
    </div>



</v-toolbar-title>
<v-spacer></v-spacer>
<v-btn style="margin:6%;"
class="primary"
text
href="https://salesapp.ordd.tk/">
<span>Dashboard (DEV)</span>
</v-btn>
</v-app-bar>

<v-main class="mt-15">
<Form/>
</v-main>
</v-app>
</template>

<script>
import Form from './components/Form';

export default {
    name: 'App',
    components: { Form },
    data: () => ({
    title:'Digital Account Opening Form',
    }),
};
</script>