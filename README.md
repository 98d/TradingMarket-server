# TradingMarket-server
贸易市场 Java springboot+spring mvc+mybatis后端接口项目

## 接口设计
|序号|模块|接口名称|接口功能|
|:---:|:---:|:---:|:---:|
|1|用户|register|注册|
|2|用户|getVerifyCode|获取验证码|
|3|用户|login|登录|
|4|用户|checkLoginValid|校验有无登录|
|5|用户|logout|退出登录|
|6|首页轮播图|getBannerList|获取banner列表|
|7|商品|getProductTypeList|获取商品类别列表|
|8|商品|getProductList|获取商品列表|
|9|商品|publishProduct|发布商品|
|10|商品|updateProduct|修改商品|
|11|商品|productDetails|获取商品详情|
|12|商品|commentOrReply|评论/回复|
|13|商品|getCommentReplyList|获取评论/回复列表|
|14|商品|praiserOrUnPraise|点赞/取消点赞|
|15|商品|getPraiseList|获取点赞列表|
|16|消息|getChatList|获取聊天对话框列表|
|17|消息|getChatDetailList|获取聊天详情|
|18|消息|initChat|初始化聊天|
|19|消息|/socket/{userId}|发送消息|
|20|个人中心|getMyProductList|获取我的商品列表|
|21|个人中心|delProduct|删除我的商品|
|22|个人中心|verifyOldMobile|校验旧手机号|
|23|个人中心|bindNewMobile|绑定新手机号|
|24|个人中心|updatePwd|修改密码|
|25|个人中心|retrieve|找回密码|
|26|个人中心|updateUserInfo|修改用户信息|
|27|个人中心|getProductNum|查询商品数量|
|28|个人中心|getAddressList|获取收货地址列表|
|29|个人中心|saveAddress|新增收货地址|
|30|个人中心|updateAddress|修改收货地址|
|31|个人中心|delAddress|删除收货地址|
|32|支付|placeOrder|下订单（购买商品）|
|33|支付|getOrderDetail|获取订单详情|
|34|支付|cancelOrder|取消订单|
|35|支付|alipay|支付宝支付|
|36|支付|alipayNotify|支付宝支付回调|







