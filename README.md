**联系方式**

* 手机： 15927063036
* Email ： <a href="mailto:sean.yuan.shu@gmail.com">sean.yuan.shu@gmail.com</a>

**个人信息**

* 舒远 / 男 / 1996
* 本科 / 武汉大学/物联网工程 / 2014.09 - 2018.07 
* 工作年限: <b>2.5</b>年
* 期望职位: web前端工程师


**工作经历**

* **上海奇虎360科技有限公司 云安全事业部（2019-11月 -- 至今）**
   + **磐云后台管理系统**<br>
     + 基于 Create-React-App 基础脚手架开发的 SPA 应用
       1. 视图框架：React。
       2. 组件库：Antd。
       3. 脚本语言： TypeScript。
     + 担任的角色：完成了项目的早期技术选型、架构，中期开发，后期优化工作。
     + 遇到的问题:
       1. 刚进入公司的时候该系统使用 PHP 作为 BFF 层以及基础后端，以及使用JQuery + HTML + CSS 传统开发界面的方式。导致开发效率低下。每做一次修改或者切换到不同功能模块都需要刷新页面，影响用户体验。所使用的组件库功能不完善，不够美观。无法使用现代的各种工具库来加强项目功能，无法通过工具来规避开发时期一些基本的错误和约束团队成员代码质量和风格统一。解决方式：从0到1重写 [查看详情](https://juejin.cn/post/6844904185343770638)
       2. 用户访问管理系统后会有一定时间的白屏。解决方式：在基础 HTML 文件上加上 Loading 效果来让用户第一时间看到的不是白屏。通过Code-Spliting 以及 一些比较大的 js 模块的 Dynamic Import 以及通过 Gzip 来压缩代码体积来降低渲染延时。
  + **磐云态势感知**<br>
    + 基于 Echarts React 开发出来的可视化大屏
      1. 视图框架：React
      2. 图表库： Echarts
      3. 通信方式： WebSocket
    + 担任的角色：完成了项目的早期技术选型、架构，中期开发，后期优化工作。
    + 遇到的问题：
    1. 大屏布局比较复杂，需要在各种分辨率屏幕下有基本一致的表现。解决方式：以 1920 x 1080 分辨率的设计稿为原型，使用 rem 作为单位 以及 flex 布局开发（不同分辨率改变根元素字体大小）。由于屏幕宽高比不一致，可以使核心部分保持固定宽高比，拉长背景和增加滚动条来优化。
    2. WebSocket 在连接一定时长后会断开连接。解决方式：每 30s 发送一次心跳包来保持连接，增加断开重连机制，重连间隔指数型递增。
  + **磐云后台运营系统**<br>
    + 基于 React 开发出来的后台运营系统
      1. 视图框架：React
      2. 组件库：Antd。
      3. 脚本语言： TypeScript。
      4. 打包编译工具： Webpack
    + 担任的角色：基于老旧项目进行新功能开发和优化工作。
    + 遇到的问题：
    1. 项目打包编译工具版本比较老旧，配置比较简陋，导致构建打包编译都比较缓慢，影响发布和开发体验，基于该版本进行优化比较困难（插件不兼容，坑比较多）。解决方式： 重新基于当前最新版本（V4）重写了打包编译配置。引入 thread-loader 以及 cache-loader来采用多进程多实例构建，以及缓存构建后结果。来加快构建及二次构建速度。
  + **连接云相关多个管理系统开发（类似于磐云管理系统）**<br>
  
* **新蛋信息技术（中国）有限公司（2018-11月--2019-11月）担任前端工程师**

   + **ngm-site [https://www.newegg.com](https://www.newegg.com)**<br>
     + 该项目是一个React同构应用，其具体技术组成为：
       1. 服务端框架：nest.js。
       2. 双端渲染引擎：React。
       3. 状态管理： mobx。
       4. 类型检查： TypeScript.
       5. 项目打包构建编译: webpack、gulp、tsc。
     + 担任的角色：界面开发、组件封装、业务逻辑实现以及一些小型优化任务。
     + 遇到的问题:
       1. webpack项目打包编译速度优化： 使用thread-loader来进行多进程多实例构建。 并通过配置相关参数开启多进程并行压缩和引入缓存来提升第二次打包速度。通过code-splite 和 动态import来缩小打包产物体积。
       2. web唤端兼容：通过定时以及 `visibilitychange` 和  `pagehide` （兜底）事件解决。
   + **ngm-app**<br/>
     + 该项目使用  `react-native、mobx`开发，页面跳转使用的`navgation`库实现。
     + 担任的角色：界面开发、组件封装、业务逻辑实现。
     + 遇到的问题：
       1. 数据量过大性能问题: 当数据量达到一定数目时，通过数据切片的方式（保留前一屏和后一屏数据）以及``scroll``事件来实现。
* <u>**上海拓链科技有限公司(2018-7月--2018-10月) 担任前端工程师**</u>
   
   + **cybex交易所项目**<br>
     + 该项目使用用`react`开发。
     + 数据可视化开发。
     + 遇到的问题：
       1. 多种类型的图形相互不规则排列实现问题：将图形抽象成数据结构，通过操作数据来排列图形。
       2. react-stockcharts库原理： 在使用前自行使用原生js、canvas通过多次迭代封装功能比较齐全的K线图组件。
   + **ico-web项目**
     + 该项目用 ``angular``开发。
     + 界面开发。     

**技能清单**
  * **语言基础:** 熟悉 ``JavaScript``，以及对 V8 有一定了解。
  * **框架经验:** 视图框架：``React`` 。
  * **工程化经验:** 对 ``Webpack`` 有一定使用经验 ，对其原理以及loader plugin开发都有一定了解。
  * **后端语言:** 对 ``Node`` 运行时有一定了解。
  * **前端优化:** 对前端优化有一定了解及开发经验。

**致谢**

 * **感谢您花时间阅读我的简历，期待能有机会和您共事。**    