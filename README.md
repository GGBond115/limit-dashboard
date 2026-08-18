# Limit Dashboard

一个只保留 Medium 样式的 macOS 悬浮小应用，用来展示 ChatGPT Work 和 Codex 的每周使用限额。

功能：

- 无菜单栏图标
- 悬浮在其他窗口上方
- 拖动卡片即可移动位置
- 自动保存上次位置
- 每 60 秒读取一次本机 Codex 账户限额
- 右键卡片可以立即刷新或退出

应用通过本机已安装的 Codex 服务读取账户数据，不保存或复制登录凭据。使用前请确认 ChatGPT/Codex 已安装并保持登录状态。

## 运行

双击同目录下的 `Limit Dashboard.app`。

如果需要重新编译，在终端执行：

```text
./Scripts/build-app.sh
```

当前构建面向 Apple 芯片 Mac。应用没有菜单栏入口，退出方式是右键卡片后选择 `Quit Limit Dashboard`。
