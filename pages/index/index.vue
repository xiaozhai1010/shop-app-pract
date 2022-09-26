<template>
	<view class="content-clear-icon" @click="clickWord">
		home page  {{num}}
		<button @click="addOne">addone</button>
	</view>
	
</template>

<script>
	export default {
		data() {
			return {
				num:0
			}
		},
		methods: {
			clickWord(){
				uni.showToast({
					icon:'none',
					title:'你好',
					duration:2000
				})
			},
			addOne(){
				this.num++
			}
		}
	}
</script>

<style>

</style>
