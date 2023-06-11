### 项目简介
这是一个基于`uniapp`网易云音乐Api开发的音乐播放器，支持多端发布

### 开发准备
* 接口请求封装
* 自定义头部
* 自定义tabbar
* uniapp基础组件和项目搭建
* colorUI基础组件
* iconfont图标库
* 网易云音乐Api,感谢大佬提供的node服务： <a href="https://github.com/Binaryify/NeteaseCloudMusicApi">NeteaseCloudMusicApi</a>

### 实现功能
- 用户登录
- 每日推荐
- 排行榜
- 热门歌手和歌手所有歌曲
- 推荐歌单和歌单详情
- 点击播放和播放全部
- 播放列表
- 背景音频播放
- 歌词查看
- 歌曲切换
- 歌曲进度条切换
- 添加喜欢音乐
- 播放历史记录
- 我喜欢的音乐
- 搜索
- 搜索建议和搜索历史记录
- 搜索播放
- ......

### 如何运行
- 先启动网易云 `NeteaseCloudMusicApi` 服务

 ```shell
	node app.js
 ```
 注意 `utils/request.js` 中的 `baseURL` 后续自行配置
- HBuilder X 编译和启动项目
