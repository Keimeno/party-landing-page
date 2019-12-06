<template>
	<div class="home">
		<img class="party__gif" src="@/assets/party.gif" alt="Party Gif" />
		<a class="party__link" target="_blank" href="https://github.com/Keimeno">
			<img src="@/assets/GitHub-Mark-Light-32px.png" alt="Github" />
		</a>
	</div>
</template>

<script lang="ts">
import Vue from "vue";
export default Vue.extend({
	name: "home"
});
</script>

<style lang="scss" scoped>
.home {
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	height: 100vh;

	.party__gif {
		margin-bottom: 40px;
		background-color: rgb(26, 26, 26);
		border-radius: 5px;
		padding: 10px;
		box-shadow: 0px 3px rgba($color: rgb(26, 26, 26), $alpha: 0.7);
	}
}
</style>
