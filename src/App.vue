<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style lang="scss">
	@import "uview-ui/index.scss";

	/*每个页面公共css */
	page {
		width: 100%;
		height: 100%;
		text-align: center;
		padding-top: constant(safe-area-inset-top);
		padding-top: env(safe-area-inset-top);
	}
</style>
