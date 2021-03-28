<template>
	<div>
		<MainTop></MainTop>

		<Header></Header>
		<!-- Put content here -->

		<InstagramFeed></InstagramFeed>
		<!-- End Instagram Feed  -->

		<!-- Start Footer  -->
		<Footer></Footer>
	</div>
</template>

<script>
export default {
	components: {
		components: {
			Header: () => import("@/components/Header"),
			Footer: () => import("@/components/Footer"),
			MainTop: () => import("@/components/MainTop"),
			InstagramFeed: () => import("@/components/InstagramFeed"),
			TopSearch: () => import("@/components/TopSearch"),
		},
		data() {
			return {};
		},
	},
};
</script>