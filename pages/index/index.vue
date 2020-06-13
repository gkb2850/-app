<template>
	<view>
		<view>
			
			<view class="index_list">
				<view class="index_list1 uni-flex">
					<view class="">
						<image src="../../static/images/userpic/12.jpg" mode="widthFix" lazy-load></image>
						<view>昵称</view>
					</view>
					<view>
						<view class="icon iconfont icon-zengjia">关注</view>
					</view>
				</view>
				<view class="index_list2">我是标题</view>
				<view class="index_list3">
					<image src="../../static/images/datapic/11.jpg" mode="widthFix" lazy-load></image>
				</view>
				<view class="index_list4 uni-flex">
					<view>
						<view class="icon iconfont icon-icon_xiaolian-mian">20</view>
						<view class="icon iconfont icon-kulian">10</view>
					</view>
					<view>
						<view class="icon iconfont icon-pinglun1">10</view>
						<view class="icon iconfont icon-zhuanfa">10</view>
					</view>
				</view>
			</view>
			
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: '第一次调试成功'
			}
		},
		onLoad() {

		},
		watch: {
			
		},
		computed:{
			
		},
		methods: { 
			onNavigationBarButtonTap (e) {
				if (e.index === 0) {
					console.log(签到按钮)
				} else if (e.index === 1) {
					console.log(编辑按钮)
				}
			}
		},
		
	}
</script>

<style>
	.index_list {
		padding: 20rpx;
		border-bottom: 2rpx solid #EEEEEE;
	}
	
	.index_list .index_list1 {
		justify-content: space-between;
		align-items: center;
	}
	
	.index_list .index_list1>view:first-child {
		display: flex;
		align-items: center;
	}
	
	.index_list .index_list1>view:first-child image{
		width: 90rpx;
		height: 90rpx;
		display: block;
		margin-right: 10rpx;
		border-radius: 50%;
	}
	
	.index_list .index_list1>view:first-child view {
		color: #F4F4F4;
	}
	
	.index_list .index_list1>view:last-child {
		
	}
	.index_list .index_list1>view:last-child>view:nth-child(1) {
		background: #F4F4F4;
		border-radius: 5rpx;
		padding: 0 10rpx;
	}
	
	.index_list .index_list2 {
		padding: 15rpx 0;
	}
	.index_list .index_list3 image{
		width: 100%;
		display: block;
		border-radius: 20rpx;
	}
	.index_list .index_list4 {
		justify-content: space-between;
		align-items: center;
		padding: 15rpx 0;
	}
	
	.index_list .index_list4>view:first-child {
		display: flex;
		align-items: center;
		margin-right: 15rpx;
	}
	.index_list .index_list4>view {
		color: #F4F4F4;
	}
	.index_list .index_list4>view:last-child {
		display: flex;
		align-items: center;
	}
	.index_list .index_list4>view>view {
		display: flex;
		align-items: center;
	}
	.index_list .index_list4>view>view:nth-child(1) {
		margin-right: 15rpx;
		padding-left: 10rpx;
	}
</style>
