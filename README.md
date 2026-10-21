# 忧郁蓝调-录播小助手

基于 [biliLive-tools 4.0.0](https://github.com/renmu123/biliLive-tools) 的非官方修改预览测试版。保留直播录制、看板、压制等功能。

## 下载 Windows 测试版 preview.2

[下载完整 Windows 包（约 362 MB）](https://github.com/tntkr33/moody-blues-recorder/releases/download/v4.0.0-moody-preview.2/MoodyBlues-4.0.0-Windows-test2.zip)

1. 完全退出原版及其后台进程。
2. 将完整 ZIP 解压到一个新文件夹，不覆盖原版。
3. 双击 忧郁蓝调/忧郁蓝调.exe。

无需命令行、Node.js、安装依赖或分卷合并。请下载上面的完整程序包，不要用 Code → Download ZIP 或自动 Source code 压缩包运行程序。

[preview.2 版本说明与 SHA-256](https://github.com/tntkr33/moody-blues-recorder/releases/tag/v4.0.0-moody-preview.2)

## 本版调整
- 端口被占用时显示明确错误，不再误降级至 Web API 登录页。
- EXE 名称、PE 名称和图标、窗口及托盘 Logo 统一。
- 取消自动弹出公告，保留手动查看入口。
- 主页新增打开当前录制目录入口。

## 测试边界
这是预览测试版，不是稳定版。84 项针对性测试、类型检查及后端 production 构建通过；全量测试 923 通过、3 项斗鱼外网请求超时、6 跳过。preview.2 尚未完成 Windows 11 实机启动、录制和压制回归。

程序旁 test-data 保存独立配置、会话和日志，不迁移旧配置。录制与下载仍可能保存到系统 Downloads，请先核对保存目录。请勿使用软件内上游自动更新，以免覆盖改版。

## 完整对应源码
[下载 MoodyBlues-source-test2.zip](https://github.com/tntkr33/moody-blues-recorder/releases/download/v4.0.0-moody-preview.2/MoodyBlues-source-test2.zip)

完整源码同时包含在 Windows ZIP 内，含构建说明、打包脚本和许可文件。GitHub 自动生成的 Source code (zip/tar.gz) 仅为本发布索引仓库的归档，不是应用完整源码。

## 旧版问题记录
[preview.1（不推荐，保留追溯）](https://github.com/tntkr33/moody-blues-recorder/releases/tag/v4.0.0-moody-preview.1) 曾出现与原版并行运行时进入 file://:18010 API 登录页的反馈，完全退出原版后有正常打开反馈，不能认定所有人必然启动失败。旧版名称和图标未全部统一。原资产与问题记录保留，不覆盖。

## 上游与许可
上游为 [renmu123/biliLive-tools](https://github.com/renmu123/biliLive-tools)，基线 tag 4.0.0。原作者、版权声明、GPL-3.0 及第三方许可证保留；LXGW 文楷字体遵循 SIL OFL 1.1。

这是非官方修改版，未获原作者或 JoJo 权利方背书。JoJo 角色相关形象和名称的权利归各自权利人，源码许可不授予角色或商标权利。
