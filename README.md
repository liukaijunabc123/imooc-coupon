# imooc-coupon
微服务项目
imooc-coupon  父模块
|——coupon-eureka
|——coupon-gateway
|——imooc-coupon-service
|	|——coupon-common（通用模块）
|	|——coupon-distribution（依赖coupon-common）
|	|——coupon-settlement（依赖coupon-common）
|	|——coupon-template （依赖coupon-common）

个模块依赖关系