<img src="https://user-images.githubusercontent.com/83630775/196994084-2c53ac23-f4be-4b90-b6fc-1b0ba65ea1b8.png" alt="KeYi's logo" align="right" width="400">
<div align="left">
  <h1>KeYi</h1>
  <h3>⚡ 下一代 Minecraft 服务器软件，皆在平衡稳定性与性能。</h3>
  <h5>这个项目仍在积极开发中且极其不稳定，使用它的风险由您自行承担！</h5>

[![Discord](https://img.shields.io/discord/1030133252134027304?color=%235865f2&label=Discord&logo=discord&logoColor=white&style=for-the-badge)](https://discord.gg/Sm2NsY5dpV)
[![Tencent QQ](https://img.shields.io/badge/Tencent%23QQ-%2312B7F5?style=for-the-badge&logo=tencentqq&logoColor=white)](https://jq.qq.com/?_wv=1027&k=tNDYZa7z)
</div>

# 为什么要创建另一个分叉？

答案很简单。

已有的分叉并不能满足我们的需求，所以我们组建了一个小团队并创建了该分叉。

# 路线图

如你所见，这个项目被设计为尽可能稳定的，支持良好的 Purpur 分支，但是同时也取得了一些性能提升。

对于 API 的改进也得到了我们的重视，所以我们正在这方面努力。

# 版本

| 版本   | 支持情况                         | 下载                                                         |
| ------ | -------------------------------- | ------------------------------------------------------------ |
| 1.18.2 | ❌                                | 不存在。                                                     |
| 1.19.2 | ✔️ 长期支持至 2023 年 2 月 1 日。 | [稳定版](https://github.com/KeYiMC/KeYi/releases/tag/main-1.19.2)，[开发版](https://github.com/KeYiMC/KeYi/releases/tag/develop-1.19.2)。 |
| 1.19.3 | ✔️                                | [稳定版](https://github.com/KeYiMC/KeYi/releases/tag/main-1.19.3)，[开发版](https://github.com/KeYiMC/KeYi/releases/tag/develop-1.19.3)。 |

# API

### Maven

#### 添加储存库

```xml
<repository>
    <id>keyi</id>
    <url>https://maven.pkg.github.com/KeYiMC/KeYi</url>
</repository>
```

#### 添加依赖

```xml
<dependency>
    <groupId>cc.keyimc.keyi</groupId>
    <artifactId>keyi-api</artifactId>
    <version>1.19.2-R0.1-SNAPSHOT</version>
    <scope>provided</scope>
</dependency>
```

### Gradle

#### 添加储存库

```groovy
repositories {
    maven("https://maven.pkg.github.com/KeYiMC/KeYi")
}
```

#### 添加依赖

```groovy
dependencies {
    compileOnly("cc.keyimc.keyi:keyi-api:1.19.2-R0.1-SNAPSHOT")
}
```

# 参与贡献

不幸的是，我们的社区规则还没有完全完善。 

目前，如果你想要参与贡献，请在 Discord 或者 腾讯 QQ 上与我们交谈相关事宜。
