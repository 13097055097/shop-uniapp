<template>
	<view>
		<!-- 搜索框 -->
		<view class="search-box">
			<view class="search-left"></view>
			<view class="search-content">
				<text class="search-TB">11</text>
				<swiper class="swiper-search" autoplay vertical circular>
						<swiper-item>
								<view class="swiper-item uni-bg-red">A</view>
						</swiper-item>
						<swiper-item>
								<view class="swiper-item uni-bg-green">B</view>
						</swiper-item>
						<swiper-item>
								<view class="swiper-item uni-bg-blue">C</view>
						</swiper-item>
				</swiper>
			</view>
			<view class="search-right"></view>
		</view>
		
		<!-- 导航列表 -->
		<view class="nav-box">
			<view class="nav-list">1</view>
			<view class="nav-list">1</view>
			<view class="nav-list">1</view>
			<view class="nav-list">1</view>
			<view class="nav-list">1</view>
			<view class="nav-list">1</view>
			<view class="nav-list">1</view>
			<view class="nav-list">1</view>
			<view class="nav-list">1</view>
			<view class="nav-list">1</view>
			<view class="nav-list">1</view>
			<view class="nav-list">1</view>
			<view class="nav-list">1</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		onLoad() {

		},
		methods: {
			
		}
	}
</script>

<style lang="scss">
	@import "./index.scss"
</style>
