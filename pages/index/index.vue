<template>
	<view class="content">
		<view>
		     <a @tap="goFindgoods">找货</a>
			 <a @tap="goSendgoods">发货</a>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: '这是首页'
			}
		},
		onLoad() {

		},
		methods: {
            goFindgoods(){
				uni.navigateTo({
				    url:'../findgoods/findgoods',
				});
			},
			goSendgoods(){
				uni.navigateTo({
				    url:'../sendgoods/sendgoods',
				});
			},
		}
	}
</script>

<style>

</style>
