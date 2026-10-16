# anatomy（WorkBuddy 适配版）

等距交互技术图解技能。原作 MIT 许可，上游 [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy)。

本仓库为 **WorkBuddy 技能适配版**：保留了上游的 `kit/` 等距几何与 SVG 生成能力，仅把 `SKILL.md` 从 Claude Code 格式改为 WorkBuddy 格式（frontmatter 用 `name` / `version` / `author` / `description` / `agent_created`），并补充了在 WorkBuddy 中运行的说明。`kit` 仅用 Node 内置模块、零 npm 依赖（Node ≥ 20.10）。

## 目录

- `SKILL.md` — 技能说明（WorkBuddy 格式）
- `kit/` — 等距几何与 SVG 生成工具（`iso-kit.mjs` 等）
- `scripts/` — 截图 / 录制 / drive / audit 等辅助脚本
- `examples/` — 参考案例（含预构建 HTML）
- `references/` — 方法论文档
- `LICENSE` — MIT

## 在 WorkBuddy 中使用

将本仓库放到 `~/.workbuddy/skills/anatomy/`，对话中提及「等距图 / 技术插画 / 交互图解 / SVG 讲解图 / isometric / anatomy」等即触发。

## 许可

MIT。基于 [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy)，由 WorkBuddy 用户「老板」适配移植。
