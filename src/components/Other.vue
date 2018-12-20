<template>
	<div>
		<p>This is result: {{ tenResult }}</p>
		<p>This is name result: {{ nameResult }}</p>
		<hr />
		<h1>Test other component with value in vuex</h1>
		<p>{{ value }}</p>
	</div>
</template>

<script>
import { mapGetters } from "vuex";
export default {
	computed: {
		...mapGetters(["tenResult", "nameResult"]),
		value: {
			get() {
				return this.$store.getters.value;
			}
		}
	}
};
</script>

<style></style>
