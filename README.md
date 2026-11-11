# 口播视频剪辑

一项面向 [OpenFilm](https://github.com/openfilm/openfilm) 的 Skill：将用户已拍摄的口播素材整理为自然易懂、保留原意且可继续编辑的视频。

## 当前状态

本文件是 0.1.0 初始草案；真实素材对照、OpenFilm 桌面端识别和更新行为尚未验证。不能仅凭文件存在判断该 Skill 已通过验收。

## 使用

推送后可尝试在 OpenFilm 中通过仓库链接添加，再验证桌面端是否识别。以真实用户任务评估时，应先取得所需素材，并按 Skill 中的确认边界处理。

## 文件

| 路径 | 内容 |
| --- | --- |
| `skills/talking-head-edit/` | Skill 需求书和 OpenFilm 展示信息 |
| `evals/README.md` | 有、无 Skill 的真实需求对照记录；素材留在本机 |
| `CHANGELOG.md` | 版本变更 |

编写和评测依据：[OpenFilm Skill 规范](https://github.com/openfilm/skills/blob/main/SPEC.md)。

## 许可证

[MIT](LICENSE)。
