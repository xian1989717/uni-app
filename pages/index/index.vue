<template>
	<view class="page-body">
		<view style="display: flex;">
			<view style="flex:1;">123</view>
			<input class="uni-input" confirm-type="search" placeholder="键盘右下角按钮显示为搜索"
				style="border:1px solid #007AFF;border-radius: 5px;flex:1;flex-grow: 5;" />
			<view style="flex:1;">1234</view>
			<view style="flex:1;">1234</view>
		</view>

	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin-top: 200rpx;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 50rpx;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
</style>
