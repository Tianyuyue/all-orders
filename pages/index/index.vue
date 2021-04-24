<!-- 由于个人时间安排问题页面样式细节没来的及改 -->
<!-- 数据绑定渲染 未完成实现  希望有机会完善 -->
<template>
	<view class="index">
		<!-- tab -->
		<view class="tab">
			<van-tabs v-model="active">
				<van-tab title="全部">
					<!-- 列表 -->
					<view class="wholelist p-5 spacing">
						<van-cell icon="shop-o" is-link>
							<view slot="title">
								<view class="van-cell-text">cdf会员购北京</view>
							</view>
						</van-cell>
						<van-card desc="创建时间: 2020-09-01 17:22:03" title="肌肤只钥光凝前霜 37MLx2" thumb="https://pic.cdfgsanya.com/assets/upload/product/601/603/225510/228588/228604/277568_1_pic400_6786.jpg">
							<view slot="tags">
								<text class="salesorder">销单时间：2020-09-01 17：22:03</text>
								<view class="sign">
									<text>支付时间:</text>
									<van-tag color="#fde9df" text-color="#ec7653">去支付订单</van-tag>
								</view>
							</view>
							<view slot="footer">
								<van-button size="mini">再来一单</van-button>
								<van-button size="mini" class="orange">分享得500积分</van-button>
							</view>
						</van-card>
					</view>
					<!-- er -->
					<view class="wholelist p-5 spacing">
						<van-cell icon="shop-o" is-link>
							<view slot="title">
								<view class="van-cell-text">cdf会员购北京</view>
							</view>
						</van-cell>
						<van-card desc="创建时间: 2020-09-01 17:22:03" title="肌肤只钥光凝前霜 37MLx2" thumb="https://pic.cdfgsanya.com/assets/upload/product/601/603/225510/228588/228604/277568_1_pic400_6786.jpg">
							<view slot="tags">
								<text class="salesorder">销单时间：2020-09-01 17：22:03</text>
								<view class="sign">
									<text>支付时间:</text>
									<van-tag color="#fde9df" text-color="#ec7653">去支付订单</van-tag>
								</view>
							</view>
							<view slot="footer">
								<van-button size="mini">再来一单</van-button>
								<van-button size="mini" class="orange">分享得500积分</van-button>
							</view>
						</van-card>
						<van-card desc="创建时间: 2020-09-01 17:22:03" title="肌肤只钥光凝前霜 37MLx2" thumb="https://pic.cdfgsanya.com/assets/upload/product/601/603/225510/228588/228604/277568_1_pic400_6786.jpg">
							<view slot="tags">
								<text class="salesorder">销单时间：2020-09-01 17：22:03</text>
								<view class="sign">
									<text>支付时间:</text>
									<van-tag color="#fde9df" text-color="#ec7653">去支付订单</van-tag>
								</view>
							</view>
							<view slot="footer">
								<van-button size="mini">再来一单</van-button>
								<van-button size="mini" class="orange">分享得500积分</van-button>
							</view>
						</van-card>
					</view>
					<!-- san -->
					<view class="wholelist p-5 spacing">
						<van-cell icon="shop-o" is-link>
							<view slot="title">
								<view class="van-cell-text">cdf会员购北京</view>
							</view>
						</van-cell>
						<van-card desc="创建时间: 2020-09-01 17:22:03" title="肌肤只钥光凝前霜 37MLx2" thumb="https://pic.cdfgsanya.com/assets/upload/product/601/603/225510/228588/228604/277568_1_pic400_6786.jpg">
							<view slot="tags">
								<text class="salesorder">销单时间：2020-09-01 17：22:03</text>
								<view class="sign">
									<text>支付时间:</text>
									<van-tag color="#fde9df" text-color="#ec7653">去支付订单</van-tag>
								</view>
							</view>
							<view slot="footer">
								<van-button size="mini">再来一单</van-button>
								<van-button size="mini" class="orange">分享得500积分</van-button>
							</view>
						</van-card>
					</view>
					<!-- si -->
					<view class="wholelist p-5 spacing">
						<van-cell icon="shop-o" is-link>
							<view slot="title">
								<view class="van-cell-text">cdf会员购北京</view>
							</view>
						</van-cell>
						<van-card desc="创建时间: 2020-09-01 17:22:03" title="肌肤只钥光凝前霜 37MLx2" thumb="https://pic.cdfgsanya.com/assets/upload/product/601/603/225510/228588/228604/277568_1_pic400_6786.jpg">
							<view slot="tags">
								<text class="salesorder">销单时间：2020-09-01 17：22:03</text>
								<view class="sign">
									<text>支付时间:</text>
									<van-tag color="#fde9df" text-color="#ec7653">去支付订单</van-tag>
								</view>
							</view>
							<view slot="footer">
								<van-button size="mini">再来一单</van-button>
							</view>
						</van-card>
					</view>
					<!-- wu -->
					<view class="wholelist p-5 spacing">
						<van-cell icon="shop-o" is-link>
							<view slot="title">
								<view class="van-cell-text">cdf会员购北京</view>
							</view>
						</van-cell>
						<van-card desc="创建时间: 2020-09-01 17:22:03" title="肌肤只钥光凝前霜 37MLx2" thumb="https://pic.cdfgsanya.com/assets/upload/product/601/603/225510/228588/228604/277568_1_pic400_6786.jpg">
							<view slot="tags">
								<text class="salesorder">销单时间：2020-09-01 17：22:03</text>
								<view class="sign">
									<text>支付时间:</text>
									<van-tag color="#fde9df" text-color="#ec7653">去支付订单</van-tag>
								</view>
							</view>
							<view slot="footer">
								<van-button size="mini">支付订单</van-button>
							</view>
						</van-card>
					</view>
					<!-- liu -->
					<view class="wholelist p-5 spacing">
						<van-cell icon="shop-o" is-link>
							<view slot="title">
								<view class="van-cell-text">cdf会员购北京</view>
							</view>
						</van-cell>
						<van-card desc="创建时间: 2020-09-01 17:22:03" title="肌肤只钥光凝前霜 37MLx2" thumb="https://pic.cdfgsanya.com/assets/upload/product/601/603/225510/228588/228604/277568_1_pic400_6786.jpg">
							<view slot="tags">
								<text class="salesorder">销单时间：2020-09-01 17：22:03</text>
								<view class="sign">
									<text>支付时间:</text>
									<van-tag color="#fde9df" text-color="#ec7653">去支付订单</van-tag>
								</view>
							</view>
							<view slot="footer">
								<van-button size="mini">删除订单</van-button>
							</view>
						</van-card>
					</view>
					<!-- qi -->
					<view class="wholelist p-5 spacing">
						<van-cell icon="shop-o" is-link>
							<view slot="title">
								<view class="van-cell-text">cdf会员购北京</view>
							</view>
						</van-cell>
						<van-card desc="创建时间: 2020-09-01 17:22:03" title="肌肤只钥光凝前霜 37MLx2" thumb="https://pic.cdfgsanya.com/assets/upload/product/601/603/225510/228588/228604/277568_1_pic400_6786.jpg">
							<view slot="tags">
								<text class="salesorder">销单时间：2020-09-01 17：22:03</text>
								<view class="sign">
									<text>支付时间:</text>
									<van-tag color="#fde9df" text-color="#ec7653">去支付订单</van-tag>
								</view>
							</view>
							<view slot="footer">
								<van-button size="mini">再下一单</van-button>
							</view>
						</van-card>
					</view>
				</van-tab>
				<van-tab title="代下单">内容 2</van-tab>
				<van-tab title="待结算">内容 3</van-tab>
				<van-tab title="已结算">内容 4</van-tab>
				<van-tab title="已作废">内容 4</van-tab>
			</van-tabs>
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
	/* 引入css */
	@import url("../../common/index.css");
</style>
