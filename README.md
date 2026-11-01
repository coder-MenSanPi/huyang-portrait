# 胡杨肖像 · Free / Huyang Portrait Free

用自己的照片作为人物身份参考，借助支持图片输入的 AI 图像工具，按三种摄影造型制作肖像。这个仓库提供的是 **Codex Skill、造型说明和 AI 参考图**；它不包含生图模型，也不是独立的在线相机应用。

Create a portrait from your own authorized photo using an image-capable AI tool and one of three photography directions. This repository contains a Codex skill, style guidance, and AI-generated reference images; it does not include an image-generation model or a hosted application.

## 免费版包含什么 / What's included

| 编号 | 造型 | Style |
| --- | --- | --- |
| T01 | 黑西装坐姿 | Seated in a dark suit |
| T02 | 车旁回望 | Looking back beside a car |
| T03 | 桌边肖像 | Portrait at a table |

每款是一组摄影造型与动作方向，实际生成效果取决于原照和所用工具。可以选择其中一款，也可以逐款生成；仓库本身不限制生成次数。示意人物是 AI 虚构形象，不是要求将使用者变成示意人物。

## 安装和使用 / Install and use

1. 下载或克隆这个仓库。在 Codex 的技能目录下创建 `huyang-portrait-free` 文件夹，将本仓库的 `SKILL.md`、`references/` 和 `assets/` 复制进去，保持目录结构。默认技能目录为 `~/.codex/skills/`。
2. 重新打开 Codex 或启动新的会话，确认环境里有可接收参考图片的图像生成或编辑工具。该工具可能需要单独开通并产生费用，具体以服务提供方为准。
3. 提供你本人或已取得授权的清晰单人照片，输入：

   > 使用 $huyang-portrait-free，按 T01 黑西装坐姿帮我制作肖像。先检查人物身份特征和辅助三视图，再生成成片。

4. 检查成片和本人是否相似，以及手部、姿态与光线。如有不满意的地方，描述具体偏差，要求定向调整。

For English use: install the skill folder under `~/.codex/skills/`, start a new Codex session with an image-capable generation/editing tool, supply an authorized clear portrait, and ask for `$huyang-portrait-free` with T01, T02, or T03. The workflow first checks an identity reference and then creates the chosen portrait.

## 照片与隐私 / Photos and privacy

请只使用你有权处理的照片。Skill 的文字不会自行运行图像服务；使用外部生成工具时，原照和参考图可能被发送给该工具及其服务商。请先确认具体工具的数据处理方式，妥善保管本地输入和成片。生成的辅助侧面是推演，并非真实侧面测量；照片相似度和结果质量无法保证。

Use only photos you have permission to process. Depending on the image tool, photos may be transmitted to a third party. Check that provider's data practices before use and protect your local files. Inferred views and identity similarity are not guaranteed.

## 使用许可与版本 / License and editions

本仓库为**非商业用途**发布，具体使用条件以 [LICENSE](LICENSE) 为准；有商业用途请先获得权利人单独授权。由于限制商用，本项目是公开源码项目，不符合开放源代码促进会（OSI）对开源许可证的定义。

Pro 版的更多造型及获取方式仍在规划中；当前仓库没有支付、线上账户或 Pro 解锁服务。免费版能使用上述三款，不要求打赏。

This source-available project is for noncommercial use only; see [LICENSE](LICENSE) for the applicable terms. Commercial use requires separate permission. A Pro edition is planned; no payment, hosted account, or Pro unlock is currently available.
