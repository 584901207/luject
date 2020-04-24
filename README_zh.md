<div align="center">

  <h1>luject</h1>

  <div>
    <a href="https://github.com/lanoox/luject/releases">
      <img src="https://img.shields.io/github/release/lanoox/luject.svg?style=flat-square" alt="Github All Releases" />
    </a>
    <a href="https://github.com/lanoox/luject/blob/master/LICENSE.md">
      <img src="https://img.shields.io/github/license/lanoox/luject.svg?colorB=f48041&style=flat-square" alt="license" />
    </a>
  </div>
  <div>
    <a href="https://www.reddit.com/r/tboox/">
      <img src="https://img.shields.io/badge/chat-on%20reddit-ff3f34.svg?style=flat-square" alt="Reddit" />
    </a>
    <a href="https://gitter.im/tboox/tboox?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge">
      <img src="https://img.shields.io/gitter/room/tboox/tboox.svg?style=flat-square&colorB=96c312" alt="Gitter" />
    </a>
    <a href="https://t.me/tbooxorg">
      <img src="https://img.shields.io/badge/chat-on%20telegram-blue.svg?style=flat-square" alt="Telegram" />
    </a>
    <a href="https://jq.qq.com/?_wv=1027&k=5hpwWFv">
      <img src="https://img.shields.io/badge/chat-on%20QQ-ff69b4.svg?style=flat-square" alt="QQ" />
    </a>
    <a href="https://xmake.io/#/zh-cn/about/sponsor">
      <img src="https://img.shields.io/badge/donate-us-orange.svg?style=flat-square" alt="Donate" />
    </a>
  </div>

  <p>A static injector of dynamic library for application</p>
</div>

## 简介

luject是一个可以将动态库静态注入到指定应用程序包的工具，目前支持以下应用程序的注入：

* Android APK
* iPhoneOS IPA 
* Windows可执行程序
* MacOS可执行程序
* Linux可执行程序

如果你想要了解更多，请参考：

* [在线文档](https://xmake.io/#/zh-cn/getting_started)
* [项目主页](https://xmake.io/#/zh-cn/)
* [Github](https://github.com/lanoox/luject)
* [Gitee](https://gitee.com/lanoox/luject)

## 准备工作

我们需要先安装[xmake](https://github.com/xmake-io/xmake)来编译此项目。

## 编译

```console
$ xmake
```

## 安装

```console
$ xmake install
```

## 使用

```console
$ luject -i app.apk lib1.so lib2.so
$ luject -i app.ipa lib1.dylib lib2.dylib
$ luject -i liba.so lib1.so lib2.so
$ luject -i app.exe lib1.dll lib2.dll
$ luject -i a.dll lib1.dll lib2.dll
$ luject -i liba.dylib lib1.dylib lib2.dyib
$ luject -i bin lib1.so lib2.so
```

## 开发

### 编译运行

```console
$ xmake
$ xmake run luject -i [input] liba.so libb.so
```

### 执行测试

```console
$ xmake build test
$ xmake run test
```

## 联系方式

* 邮箱：[waruqi@gmail.com](mailto:waruqi@gmail.com)
* 主页：[tboox.org](https://tboox.org/cn)
* 社区：[Reddit论坛](https://www.reddit.com/r/tboox/)
* 聊天：[Telegram群组](https://t.me/tbooxorg), [Gitter聊天室](https://gitter.im/tboox/tboox?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
* QQ群：343118190(满), 662147501
* 微信公众号：tboox-os

## 支持项目

luject项目属于个人开源项目，它的发展需要您的帮助，如果您愿意支持xmake-gradle项目的开发，欢迎为其捐赠，支持它的发展。 🙏 [[支持此项目](https://opencollective.com/xmake#backer)]

<a href="https://opencollective.com/xmake#backers" target="_blank"><img src="https://opencollective.com/xmake/backers.svg?width=890"></a>

## 赞助项目

通过赞助支持此项目，您的logo和网站链接将显示在这里。[[赞助此项目](https://opencollective.com/xmake#sponsor)]

<a href="https://opencollective.com/xmake/sponsor/0/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/1/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/2/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/3/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/4/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/5/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/6/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/7/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/8/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/9/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/9/avatar.svg"></a>


