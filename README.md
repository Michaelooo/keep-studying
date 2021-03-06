# 知识体系

总结目前接触到的知识，大部分可能是概念，或者是一些思路，可能不会有参考链接，用于个人知识梳理，也可用于面试装逼。

## 做技术必须要明白的几件事

这部分的内容我认为比其他技术的要求更重要。

- **要逼着自己读英语**：学会搭梯子，把“百度搜索”替换成“谷歌搜索”吧，即使英语差也要硬着头皮去读英语。

- **要有不进则退的觉悟**: 做技术的更应该明白“不进则退”的道理，要时刻保持对技术的好奇心。
- **不要怕犯错、踩坑**： 每个人都是从小白过来的，程序崩溃、服务宕机不用慌，经验都是踩坑踩出来的。
- **学会甩锅**：说的好听点是更好的理解责任，毕竟你终究会变成老油条的。

## 开发基本技能

- **vscode 必装的插件 [Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)**：通过 gist 来存储你的用户配置，用于多台电脑同步插件配置，省却很多麻烦，（插个话：减小平台化的差异性）。
- **你平时怎么解决问题**：dash 结合 Alfred 用作离线查找文档， msdn 查 web 相关的api。 遇到问题优先搜索， 谷歌 -> github issues -> stackoverflow。
- **vim 的基本操作要掌握**
- **熟悉常用的 Linux 命令**
- **要有不进则退的觉悟**: 做技术的更应该明白“不进则退”的道理，要时刻保持对学习的好奇心。

## 前端

## Javascript 部分

- **什么是面向对象，js 的面向对象又 skr 啥？** 一般大佬们都喜欢说，面向对象就是“你办事、我放心”。
- **Js 的原型链、class、this**: 大概明白又说不明白的概念，没事多翻翻。
- **promise 得了解下**： 单从前端来说，js 玩来玩去就是同步、异步的，所以要搞清楚这个。最好还能了解 js 异步的进化史，回调到 yield 再到 promise 的一个过程。

### react 部分

- **理解 diff 算法**：最好结合 vue 和 angular 的来理解，本质是 virtual dom 与 AST 的知识。

- **react + redux 最佳实践**： [https://github.com/sorrycc/blog/issues/1](https://github.com/sorrycc/blog/issues/1)。
- **redux 中文文档**：[https://cn.redux.js.org/。](https://cn.redux.js.org/)
- **redux-saga中文文档**：[https://redux-saga-in-chinese.js.org/。](https://redux-saga-in-chinese.js.org/)
- **react-router中文文档**：[https://react-guide.github.io/react-router-cn/。](https://react-guide.github.io/react-router-cn/)
- **使用 dva 来代替 redux**: [https://github.com/dvajs/dva/blob/master/README_zh-CN.md](https://github.com/dvajs/dva/blob/master/README_zh-CN.md)。dva 内部实现： redux + redux-saga + react-router。
- **react 服务端渲染 next.js**： [https://github.com/zeit/next.js](https://github.com/zeit/next.js)。
- **react-native**: [react-native 中文网](https://reactnative.cn/)，可以看官网。
- ……

### angular 部分

- **ng 快速上手**：[https://angular.cn/guide/quickstart](https://angular.cn/guide/quickstart)。
- **ng的概念理解**：[http://www.chengpengfei.com/2018/02/05/。](http://www.chengpengfei.com/2018/02/05/)
- **typescript 的使用**: [https://www.tslang.cn/](https://www.tslang.cn/)。
- **rxjs 的使用（可以适用多个框架）**: [rxjs 中文。](https://cn.rx.js.org/)
- **coffeescript**: [coffeescript](https://github.com/jashkenas/coffeescript)已经被淘汰，作为一个语法糖，编译太变态。
- **angular 的依赖注入**：可以结合 [java中的解释](https://blog.csdn.net/bestone0213/article/details/47424255) 理解。
- ……

### vue 部分

- **vue 双向绑定的实现**： 过去是 es5 的 Object.defineProperty ，现在开始使用 es6 的 proxy。
- **vuex 状态管理**： [vuex 类比 redux](https://vuex.vuejs.org/zh/guide/)。
- **vue 的服务端渲染实现**： [nuxt.js 可以理解为 vue 对于 next.js 的实现。](https://github.com/nuxt/nuxt.js)
- ……

### 其他

- **打包工具的选择**： webpack v5 了貌似都 , [parcel， 2017年末忽然火的一个打包工具](https://github.com/parcel-bundler/parcel), [rollup，直接支持 es-modules 的打包工具](https://github.com/rollup/rollup) 。 webpack 贵在使用基数大，生态圈良好，但劣在复杂的配置项，后面两个都是新的打包工具。
- **grunt 和 gulp**: 项目构建工具，考虑老的业务还会使用，可作为了解，会些基本的微操就可以。
- **一些3D库**：canvas 也先放在这儿、webgl、[three.js](https://threejs.org/)
- **js 放弃篇**：[webassembly](https://webassembly.org/)
- **pwa**: [pwa skr 啥，有人和你说小程序就是pwa，你要打他吗？](https://zhuanlan.zhihu.com/p/22578965)
- ……

## 后端

### Nodejs

- **Nodejs 源码了解下**：[深入理解Node.js：核心思想与源码分析](https://yjhjstz.gitbooks.io/deep-into-node/content/)。
- **node 的事件机制和浏览器端的差异**：[一篇文章教会你Event loop——浏览器和Node](https://segmentfault.com/a/1190000013861128)。
- **koa@2.0 的基本操作**: 我为啥叫洋葱模型？
- **egg.js** : [eggjs](https://eggjs.org/zh-cn/intro/)，可以理解为阿里关于 koa 的最佳实践。
- **node 监控**：[Node应用内存泄漏分析方法论与实战](https://github.com/alibaba/beidou/blob/master/packages/beidou-docs/articles/node-memory-leak.md)。
- ……

### Golang

- **go 用来做 web 编程**： [https://www.kancloud.cn/kancloud/web-application-with-golang/44105](https://www.kancloud.cn/kancloud/web-application-with-golang/44105)。
- **go 的基本概念**： [https://www.kancloud.cn/kancloud/the-way-to-go/72675](https://www.kancloud.cn/kancloud/the-way-to-go/72675)。
- **go 的优势**：和 c++ 比起来，良好的 GC。 和 java 比起来，代码量小，性能更高，并发处理方便。劣势是没有自己的包管理机制，生态圈不是很完美。
- ……

### 其他

- **nginx**: [tegine 淘宝的最佳实践](http://tengine.taobao.org/index_cn.html)。
- **api 管理工具**：大搜车 [easy-mock](https://www.easy-mock.com/login) , 阿里 [rap](http://rapapi.org/org/index.do) , swagger。
- **api gateway**: 微服务化下的 api 网关，[kong](https://konghq.com/kong-community-edition/) , [nginx-plus](https://www.nginx.com/products/nginx/)。
- **docker**: [http://dockone.io/article/101](http://dockone.io/article/101)。
- **ci**: [travis.ci](https://travis-ci.org/),  [gitlab.ci](https://gitlab.com/),  jerkins。
- **集群 k8s**
- ……

**待补充……**