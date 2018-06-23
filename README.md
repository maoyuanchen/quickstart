# React Native 学习备忘录

### React Native CN

[文档、教程](https://reactnative.cn/)

### React Native 视频教程

[百度云盘](https://pan.baidu.com/s/1ef5LT4jWrt1jHmEwXQgFOQ)

### Homebrew

- Mac系统的包管理器，用于安装NodeJS和一些其他必需的工具软件
- 安装过程中git报错：RPC failed; curl 18 transfer closed with outstanding read data remaining
```
解决方法：
git config --global http.postBuffer 524288000
注意 http.postBuffer 单位是b，524288000B也就500M左右
```

[brew.sh](https://brew.sh/index_zh-cn)

### Node.js

- 注意 环境变量配置

### Android Studio (Android SDK Tool)

- Java SDK 1.8
- 注意 环境变量配置

[下载](http://www.android-studio.org/)

### Oracle VM VirtualBox

- Genymotion 安卓模拟器运行依赖
- 需要CPU支持虚拟化
- Mac系统新安全特性会阻止外部内核扩展的安装，需在终端手动禁用此安全特性。

```
sudo spctl --master-disable
```

[下载](https://www.virtualbox.org/wiki/Downloads)

### Genymotion 安卓模拟器

- 先注册，再下载，个人免费。

[下载](https://www.genymotion.com/download/)

### Ant Design Mobile RN of React

- 一个基于 React Native 的 UI 组件库。
- 在 WebStorm 中开发，组件一定要通过 WebStorm install，否则会在编译时报错。

[官方文档](https://rn.mobile.ant.design/docs/react/introduce-cn)

### WebStorm

- 注意 将`javascirpt`版本换成`React JSX`或`Flow`
- Plugin [React Native Console](https://github.com/beansoftapp/react-native-console )

### ReactNative-LiveTemplate

- WebStorm React Native 代码提示插件。

[virtoolswebplayer/ReactNative-LiveTemplate](https://github.com/virtoolswebplayer/ReactNative-LiveTemplate)
