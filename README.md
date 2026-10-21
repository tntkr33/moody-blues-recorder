# 忧郁蓝调-录播小助手

基于 [biliLive-tools 4.0.0](https://github.com/renmu123/biliLive-tools) 的非官方界面修改预览测试版。保留直播录制、看板、压制等原有功能入口。

## 下载与启动

[下载 Windows 完整测试包（约 358 MB）](https://github.com/tntkr33/moody-blues-recorder/releases/download/v4.0.0-moody-preview.1/moody-blues-4.0.0-Windows-preview.zip)

1. 先退出正在运行的原版软件。
2. 将完整 ZIP 解压到一个新文件夹。
3. 双击其中的 忧郁蓝调-测试版/biliLive-tools.exe。

不需要命令行、Node.js、安装依赖或分卷合并。EXE 保留上游文件名，软件界面显示“忧郁蓝调”。

[版本说明与 SHA-256 校验值](https://github.com/tntkr33/moody-blues-recorder/releases/tag/v4.0.0-moody-preview.1)

## 测试边界

这是预览测试版，不是稳定版。应用测试 49 项通过，Node/Web 类型检查与构建通过；全量测试 890 通过、1 项外网超时失败、6 跳过。尚未完成 Windows 11 实机启动、录制、压制和登录验证。

程序旁 test-data 保存独立配置、会话和日志，不迁移旧配置。录制与下载默认仍可能保存到系统 Downloads，请先核对保存目录。请勿使用软件内上游自动更新，以免覆盖改版。

## 完整对应源码

[下载 moody-blues-source.zip](https://github.com/tntkr33/moody-blues-recorder/releases/download/v4.0.0-moody-preview.1/moody-blues-source.zip)

完整源码同时包含在 Windows ZIP 内，含构建说明、打包脚本和许可文件。请选择以上 moody-blues-source.zip。GitHub 自动生成的 Source code (zip/tar.gz) 仅为本发布索引仓库的归档，不是应用完整源码。

## 上游与许可

上游为 [renmu123/biliLive-tools](https://github.com/renmu123/biliLive-tools)，基线 tag 4.0.0。保留 GPL-3.0 及各第三方许可证；LXGW 文楷字体遵循 SIL OFL 1.1。

JoJo 角色相关形象和名称的权利归各自权利人，源码许可不授予角色或商标权利。本项目不是相关权利人的官方作品。
