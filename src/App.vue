<template>

	<div>
		<Banner></Banner>
		<HeaderNav></HeaderNav>
		<FooterContent></FooterContent>
	</div>
	
</template>

<script>

import Banner from './components/page/Banner.vue';
import HeaderNav from './components/page/HeaderNav.vue';
import FooterContent from './components/page/FooterContent.vue';

export default {
	components: {
		Banner,
		HeaderNav,
		FooterContent
	}
}
</script>

<style lang="scss">
@import "./style/style.scss";
</style>
