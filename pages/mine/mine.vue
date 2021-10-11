<template>
	<view class="page">
		<view class="header">
			<image style="width: 100px; height: 100px; background-color: #eeeeee;" src="../../static/logo.png"
				@error="imageError"></image>
			<view>
				<view>18092564370</view>
				<view>电话：18092564370</view>
				<view>汇检测</view>
			</view>
		</view>
		
		<view class="money">
			
		</view>

		<view></view>
	</view>
	</view>
</template>

<script>
	export default {
		setup() {}
	}
</script>

<style lang="scss">
	.page {
		padding: 20px;

		.header {
			display: flex;
			margin-bottom: 16px;
		}
		.money{
			border-radius: 5px;
			height:50px;
			background-color: #F0AD4E;
		}
	}
</style>
