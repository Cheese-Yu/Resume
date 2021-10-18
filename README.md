# 于海洋-前端开发-四年半经验
于海洋 / 上海 / yhyclelo@sina.com / 南京林业大学-环境科学(2017届)

## 技术栈
* 熟悉语义化的 HTML 的编写，熟悉 Less 高效编写 CSS
* 熟悉 JavaScript，掌握 ES6 以上常用语法
* 熟悉 Vue 全家桶
* 熟练使用 Egg.js(阿里Node应用库) 编写服务端应用(MongoDB/MySQL)
* 熟悉公众号、小程序、Weex开发
* 使用 Webpack、Rollup、Gulp 等进行前端构建
* 使用 Photoshop、Sketch 等设计工具
* 踏实负责，熟悉业务

  
## 个人经历
* **2013 ~ 2017 南京林业大学** 本科 环境科学
* **2017.10 ~ 2019.04  浙江善红信息技术有限公司**  
善红云金融 SaaS 管理后台，善红云智慧订单系统，智慧菜市场系统
* **2019.05 ~ 至今  萤若(上海)互联网络科技有限公司**  
自研埋点库、UVC-Camera-JSSDK、互动研发、接口优化(耗时缩减80%)、数据管理后台、油罐go小程序(零售商城)、基于 Weex、Webview 开发 App 内嵌页、基于企业微信的 CRM 系统等


## 项目经验
#### Js: [前端全埋点库](https://www.npmjs.com/package/@itmirror/im-track-jssdk)
基于实际业务考量，自研全埋点库，支持原生、Vue使用，可自定义的全埋点，解决了手动埋点遗漏的问题，同时又不会有过多的无效数据。

#### Js: [UVC-Camera-JSSDK](https://www.npmjs.com/package/@itmirror/uvc-camera-jssdk)
封装 Andriod uvc-camera的方法调用，同时支持web端开发模拟（图片数据传输、灯光切换、上传等），保证开发和生产的体验一致性。

#### Vue: 香水问卷(类网易云音乐营销H5)
复杂场景切换，考虑研发时间，兼顾设备稳定性和场景切换自然，采用多 Video 拼接，结合 transition、animation等。资源预加载，压缩内存占用等优化。

#### Weex: 基于Weex的开发
小样售货机、乳液机、货架交互屏等内的页面，包括：扫码关注、商品列表、商品详情、购物车、表单等。  
Weex 各种组件的探索和封装、基于公司目前的 App 内嵌页资源管理模式，编写构建打包上传脚本。 
* Weex 组件和方法封装
* 项目构建和管理优化
* 技术栈：Weex / WebSocket / Node.js / MongoDB

#### Node / PC: 善红云智慧订单系统
订单管理，功能包括：登录、权限验证、订单查询及导出、个人/企业认证、设备管理、日志等。  
负责 MySQL 库表设计，读写分离。使用 Redis 做任务队列/订阅广播(进程间通信)/加锁(防止抢单)；socket.io 与安卓 App 长连接通信，断开时发送邮件和短信告警；json2csv 定时生成报表文件；身份证识别Api对接。
* 使用 Egg.js 开发订单支付系统及后台管理相关接口
* 对接微信、支付宝支付
* 任务队列管理，设备分组管理
* 通过 Redis 优化系统并发支持
* 技术栈：Vue / Egg.js / MySQL / Redis / Quasar / Socket.io

