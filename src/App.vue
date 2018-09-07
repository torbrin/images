<template>
    <AppHeader></AppHeader>
</template>

<script>
    import { mapActions } from 'vuex';
    import AppHeader from './components/AppHeader';

	export default {
		name: "App",
		components: {AppHeader},
        methods: mapActions(['login'])
	}
</script>

<style scoped>

</style>