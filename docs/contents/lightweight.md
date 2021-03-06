# 轻量模式（Lightweight Mode）

## 版本要求

0.15.0 版本更新后，增加轻量模式支持

## 使用说明

依赖于内置 Service Mode，启动轻量模式后，关闭软件界面后 CFW 将会完全关闭，仅保留 Clash 核心继续工作。再次启动 CFW 则会快速恢复并连接核心。

此模式下，CFW 界面关闭后将不再占用系统内存，但同时部分功能将会失效，例如：

- 任务栏图标及菜单
- 配置文件定时更新
- [TAP 模式](./tap)
- [后台启动其他应用](./childprocess)
- 后台更新检测

::: danger
其他未提及功能也可能会受到影响，如追求更好体验，不建议使用此功能
:::

## 开启步骤

1. 点击`General`中`Service Mode`右边`Manage`，在打开窗口中安装服务模式，安装完成应用会自动重启，Service Mode 右边地球图标变为`绿色`即安装成功
2. 点击`Settings`界面中`General`模块中`Lightweight Mode`进行开启

开启后关闭界面操作即自动关闭软件，重新启动软件会自动恢复，已选择配置文件及节点不会丢失。
