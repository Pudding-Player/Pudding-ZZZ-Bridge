# Pudding zzz Bridge

[桥与插件说明](plugins/zzz/README.md) · [Pudding 主仓](https://github.com/Pudding-Player/Pudding)

本仓独立包含桥源码、插件清单、技能和生成协议，不依赖主仓源码即可编译。Windows 安装 Visual Studio 2022 C++ Build Tools 后执行：

```cmd
plugins\zzz\bridge\build.cmd --production
```

产物位于 target/bridge/zzz/。生成文件已纳入版本控制；契约或公共协议变化时由主仓的 scripts/generate-adapter-disclosure.mjs 同步，并将结果提交本仓。插件与本机桥分别连接，不自动启动工具或游戏。编译不代表真实宿主或游戏执行已验收。
