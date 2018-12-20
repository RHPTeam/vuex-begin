<template>
	<div>
		<p>This is name result: {{ nameResult }}</p>
	</div>
</template>

<script>
import { mapGetters } from "vuex";
export default {
	computed: {
		...mapGetters(["nameResult"])
	}
};
</script>

<style></style>
