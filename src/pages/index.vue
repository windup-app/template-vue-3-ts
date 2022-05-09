<script lang="ts">
/* ----- IMPORT:PACKAGES ------------------------- */
import { defineComponent } from "vue";

/* ----- IMPORT:COMPONENTS ------------------------- */
import WindUpWelcome from "../components/WindUpWelcome.vue";

export default defineComponent({
	/* ----- SETUP:PAGE NAME ------------------------- */
	name: "Page-Home",
	/* ----- SETUP:COMPONENTS ------------------------- */
	components: {
		WindUpWelcome,
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
	<div class="Page-Home">
		<WindUpWelcome />
	</div>
</template>

<style lang="scss" scoped></style>
