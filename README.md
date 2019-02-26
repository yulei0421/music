# 163music
🎵 网易云音乐移动端 web app

项目主体功能已大致完成：
- 用户登录、日推歌单、查看创建歌单、查看动态、音乐播放、单曲搜索等；
- webpack 构建和完善开发、部署流程；
- 单元测试、风格测试；

接下来还会陆续添加一些新功能和对代码进行持续优化。

如果您发现有什么问题或者更好的想法，欢迎提交 issue 和 pr，

## 技术栈
- *vue*：vue 2.6, vue-router, vuex, vue-server-renderer
- *webpack*：webpack 4, webpack-dev-middleware, webpack-hot-middleware
- *node*：express 4
- *test*：karma 4, mocha, sinon-chai, vue/test-utils, eslint

## 上手指南
项目代码涉及 ES6/7 特性，Node 请安装 v8.0 以上版本

本地开发环境：OSX 10.14.1，node v11.8.0，npm 6.5.0，Chrome 72

### 安装依赖
```
npm install
```

### 开发环境运行
```
127.0.0.1
```
```
npm run dev
```
```
浏览器访问 127.0.0.1:8080
```

### 生产环境构建
```
npm run build
```

### 生产环境部署
```
npm run start
```

### 单元测试
单元测试使用 karma + mocha + sinon-chai ，配合 webpack + @Vue/test-utils 来进行单文件组件测试
```
npm run test
```

### 风格测试
风格检测使用 eslint，airbnb 风格
```
npm run lint
```

## 相关资料
[NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi)

[vue-hackernews-2.0](https://github.com/vuejs/vue-hackernews-2.0)

[vue-awesome-swiper](https://github.com/surmon-china/vue-awesome-swiper)

[vuejs-templates/webpack](https://github.com/vuejs-templates/webpack)

