# 知识体系

总结目前接触到的知识，大部分可能是概念，或者是一些思路，可能不会有参考链接，用于个人知识梳理，也可用于面试装逼。


## 开发基本技能

* **vscode 必装的插件 [Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)**：通过 gist 来存储你的用户配置，用于多台电脑同步插件配置，省却很多麻烦
* **你平时怎么解决问题**：dash 结合 Alfred 用作离线查找文档， msdn 查 web 相关的api。 遇到问题优先搜索， 谷歌 -> github issues -> stackoverflow
* **vim 的基本操作要掌握**
* **熟悉常用的 Linux 命令**


## 前端

### react 部分

* **react + redux 最佳实践**： [https://github.com/sorrycc/blog/issues/1](https://github.com/sorrycc/blog/issues/1)
* **redux 中文文档**：[https://cn.redux.js.org/](https://cn.redux.js.org/)
* **redux-saga中文文档**：[https://redux-saga-in-chinese.js.org/](https://redux-saga-in-chinese.js.org/)
* **react-router中文文档**：[https://react-guide.github.io/react-router-cn/](https://react-guide.github.io/react-router-cn/)
* **使用 dva 来代替 redux**: [https://github.com/dvajs/dva/blob/master/README_zh-CN.md](https://github.com/dvajs/dva/blob/master/README_zh-CN.md)。dva 内部实现： redux + redux-saga + react-router
* **react 服务端渲染 next.js**： [https://github.com/zeit/next.js](https://github.com/zeit/next.js)
* **react-native**: [react-native 中文网](https://reactnative.cn/)，可以看官网
* ……

### angular 部分

* **ng 快速上手**：[https://angular.cn/guide/quickstart](https://angular.cn/guide/quickstart)
* **ng的概念理解**：[http://www.chengpengfei.com/2018/02/05/](http://www.chengpengfei.com/2018/02/05/)
* **typescript 的使用**: [https://www.tslang.cn/](https://www.tslang.cn/)
* **rxjs 的使用（可以适用多个框架）**: [rxjs 中文](https://cn.rx.js.org/)
* **coffeescript**: [coffeescript](https://github.com/jashkenas/coffeescript)已经被淘汰，作为一个语法糖，编译太变态
* **angular 的依赖注入**：
* ……

### vue 部分

* **vue 双向绑定的实现**： 过去是 es5 的 Object.defineProperty ，现在开始使用 es6 的 proxy
* **vuex 状态管理**： [vuex 类比 redux](https://vuex.vuejs.org/zh/guide/)
* **vue 的服务端渲染实现**： [nuxt.js 可以理解为 vue 对于 next.js 的实现](https://github.com/nuxt/nuxt.js)
* ……

### 其他

* **打包工具的选择**： webpack v5 了貌似都 , [parcel， 2017年末忽然火的一个打包工具](https://github.com/parcel-bundler/parcel), [rollup，直接支持 es-modules 的打包工具](https://github.com/rollup/rollup) 。 webpack 贵在使用基数大，生态圈良好，但劣在复杂的配置项，后面两个都是新的打包工具。
* **grunt 和 gulp**: 项目构建工具，考虑老的业务还会使用，可作为了解，会些基本的微操就可以。
* canvas、webgl、[webassembly](https://webassembly.org/)
* ……

## 后端

### Nodejs

* **Nodejs 源码了解下**：[深入理解Node.js：核心思想与源码分析](https://yjhjstz.gitbooks.io/deep-into-node/content/)
* **node 的事件机制和浏览器端的差异**：[一篇文章教会你Event loop——浏览器和Node](https://segmentfault.com/a/1190000013861128)
* **koa@2.0 的基本操作**
* **egg.js** : [eggjs](https://eggjs.org/zh-cn/intro/)，可以理解为阿里关于 koa 的最佳实践， 
* **node 监控**：[Node应用内存泄漏分析方法论与实战](https://github.com/alibaba/beidou/blob/master/packages/beidou-docs/articles/node-memory-leak.md)
* ……

### Golang

* **go 用来做 web 编程**： [https://www.kancloud.cn/kancloud/web-application-with-golang/44105](https://www.kancloud.cn/kancloud/web-application-with-golang/44105)
* **go 的基本概念**： [https://www.kancloud.cn/kancloud/the-way-to-go/72675](https://www.kancloud.cn/kancloud/the-way-to-go/72675)
* **go 的优势**：和 c++ 比起来，良好的 GC。 和 java 比起来，代码量小，性能更高，并发处理方便。劣势是没有自己的包管理机制，生态圈不是很完美。
* ……

### 其他

* **nginx**: [tegine 淘宝的最佳实践](http://tengine.taobao.org/index_cn.html)
* **api 管理工具**：大搜车 easy-mock , 阿里 rap ,swagger
* **api gateway**: kong , nginx-pro
* **docker**: [http://dockone.io/article/101](http://dockone.io/article/101)
* **ci**: travis, gitlab.ci, jerkins, 
* ……

**待补充……**
