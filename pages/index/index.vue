<template>
	<view class="homeLayout">
		<view class="banner">
			<swiper indicator-dots indicator-color="rgba(255,255,255,0.5)" indicator-active-color="#fff" autoplay circular>
				<swiper-item>
					<view v-for="item in 3">
						<image src="../../common/images/banner1.jpg" mode="aspectFill"></image>
					</view>
				</swiper-item>
			</swiper>
		</view>
	</view>
</template>

<script setup>
	
</script>

<style scoped lang="scss">
	.homeLayout {
		.banner {
			width: 750rpx;
			padding: 30rpx 0;
			swiper {
				width: 750rpx;
				height: 340rpx;
				swiper-item {
					width: 100%;
					height: 100%;
					image {
						width: 100%;
						height: 100%;
						border-radius: 10rpx;
					}
				}
			}
		}
	}
</style>
