# 3D流水线 V1.5｜公开通用版

一套真实可安装、可运行的 Codex Skill，用于组织 1–30 秒 AI 制作的 UE 质感 3D 广告流程：Blender 工程化、Godot 自动编排、代表帧确认和最终渲染。

> “UE 质感”是画面目标；当前自动编排与渲染引擎为 Godot 4。项目必须进入 Unreal Engine 时，可使用 `export_gate` 产出的 GLB/FBX 继续交接。

## 直接下载

[下载 3d-pipeline-v1.5.0-public.zip](https://github.com/bjdenghao-cn/codex-3d-pipeline/raw/refs/heads/main/3d-pipeline-v1.5.0-public.zip)

## 安装

1. 下载并解压 ZIP。
2. 确认最外层文件夹名为 `3d-pipeline`。
3. 将整个文件夹复制到：`C:\Users\你的用户名\.codex\skills\3d-pipeline`。
4. 重新启动 Codex。
5. 输入：`使用 $3d-pipeline，先检查我的电脑和项目环境。`

ZIP 内的 `INSTALL.md` 提供小白安装、验证命令和 15 秒广告示例提示词。

## 基础环境

- 必需：Codex、Python 3.10+、Blender 4.x、Godot 4.x、FFmpeg / FFprobe
- 可选：Blender MCP，用于需要实时操作 Blender GUI 的项目
- 可选：Mixamo。它是外部服务，不是插件；用户自行合法下载 T-Pose 或动作 FBX
- Godot 默认使用 CLI/GDScript，不要求 Godot MCP

## V1.5 新增门禁

- 正式场景环境：PBR 地面、景深层次、独特地标、重复度、空屏率和镜头路径覆盖
- 角色、载具和道具：接触点、关节角度、父级与运动空间
- 载具动作：模型前轴、运动方向和相机相对方位
- VFX：闪光、火焰、烟、尘、碎片分层，以及上升、扩散、消隐、风向、遮挡和高光裁切
- 关键语义证据缺失时，代表帧和最终渲染会被阻止

## 验证

本公开包已经通过 32 项单元测试、Skill 结构校验、公开信息扫描和解压复测。

## 文件校验

`SHA-256  54E2981AB5A35976D90DF46B2D9CEFF9B7281B42B6A63D106E29F0CE909F9DBF`

本仓库暂未附加开源许可证。除下载、安装和本地评估之外的复制、修改、再分发或商用授权，以权利人后续说明为准。
