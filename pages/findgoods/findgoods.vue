<template>
	<view>
		<uni-drawer :visible="false">
		    <view style="padding:30upx;">
		        <view class="uni-title">抽屉式导航</view>
		    </view>
		</uni-drawer>
	</view>
</template>

<script>
    import {uniDrawer} from '@dcloudio/uni-ui'
 	export default {
		components: {uniDrawer},
		data() {
			return {
				
			};
		}
	}
</script>

<style>
	
</style>
