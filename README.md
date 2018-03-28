# wechat-planpro
调接口 验证码 微信页跳转带的类似于时间戳的code
空白页 不论如何 都会有一个code 微信自带 微信访问才会有 。
空白页跳到注册页 什么都不带 。只带了微信自己的code  在注册页会拿到这个code 
用于第一次获取验证码 。第一次申请验证码 需要post过去 手机号 code。 就两个
然后code会过期 ， 第一次post会拿回来 openid unionid heading
第二次  获取验证码。post过去 这三个值。加手机号
这三个值。除了用于第二次获取验证码。也用来注册。注册的时候post过去
换来uid和token
下次再次进入，可以通过code抓到 uid和token 这个用户就有uid和tokn 
直接去第一页了
