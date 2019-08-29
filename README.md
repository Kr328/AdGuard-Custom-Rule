## AdGuard for Android 的 一些自定义规则

### #0 使用说明

- 基本需求
  - HTTPS 过滤 (需要ROOT)
  - 对第三方应用过滤 (购买正版)
- 如何导入
  - AdGuard 设置
  - 内容拦截
  - 过滤器
  - 自定义过滤器
  - 添加
  - 填入链接
  - **务必选择受信任的过滤器**


### #1 Bilibili 移动客户端增强

* **链接** <https://raw.githubusercontent.com/Kr328/AdGuard-Custom-Rule/master/rule/bilibili.txt>

* **测试版本** 5.46.0

* **功能**
 
  * 去除评论区广告
  * 去除首页卡片广告
  * 允许缓存任意动画
  * 去除首页会员购和游戏中心

* **注意**

  AdGuard 的 **本地 HTTP 代理 (自动)** \[使用 iptables 实现\] 模式 会 影响 Bilibili 运行

  使用此规则 需要在 **本地 VPN** 下运行


### #2 CNBeta 移动端增强

* **链接** <https://raw.githubusercontent.com/Kr328/AdGuard-Custom-Rule/master/rule/cnbeta.txt>
* **功能**
  * 重定向 **桌面版网站** 到 **移动版网站** 


