<script lang="ts">
/* ----- IMPORT:PACKAGES ------------------------- */
import { defineComponent } from "vue";

/* ----- IMPORT:LAYOUT ------------------------- */
import LayoutDefault from "./layouts/default.vue";

export default defineComponent({
	/* ----- SETUP:PAGE NAME ------------------------- */
	name: "App",
	/* ----- SETUP:COMPONENTS ------------------------- */
	components: {
		LayoutDefault,
	},
	setup() {
		/* ----- SETUP:INTERFACE ------------------------- */

		/* ----- SETUP:DATA ------------------------- */

		/* ----- SETUP:METHOD ------------------------- */

		/* ----- SETUP:ONMOUNTED ------------------------- */

		/* ----- RETURN:VARIABLES ------------------------- */
		return {};
	},
});
</script>

<template>
	<LayoutDefault>
		<router-view />
	</LayoutDefault>
</template>
