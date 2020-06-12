<template>
	<view>
		<view class="icon iconfont icon-icon-test1">
			<navigator url="/pages/ceshi/ceshi" hover-class="other-navigator-hover">
			                    <button type="default">跳转ceshi页面</button>
			                </navigator>
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
</style>
