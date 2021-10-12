<template>
	<view class="page">
		<view class="header">
			<image 
				style="width: 130rpx; height: 130rpx; background-color: #eeeeee;" 
				src="../../static/logo.png"
				@error="imageError"></image>
			<view>
				<view>18092564370</view>
				<view>电话：18092564370</view>
				<view>汇检测</view>
			</view>
		</view>
		
		<view class="money">
			
		</view>

		<view>12345</view>
	</view>
</template>

<script>
	export default {
		setup() {}
	}
</script>

<style lang="scss">
	.page {
		padding: 24px;

		.header {
			display: flex;
			margin-bottom: 16px;
		}
		.money{
			height:234rpx;
			background-image:
			      url("~@/static/mine_money_background.png");
			background-size: 100% 100%;
		}
	}
</style>
