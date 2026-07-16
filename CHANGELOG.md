# Changelog

All notable changes to this project are documented here.

## [2.0.3] - 2026-07-16

### Changed（方案A 打磨 · 鲁班/Luban 交叉评估后续）

- **Step 3 接口显式化**：Grand Finale 的「模型2 悲壮热血美学 / 模型6 多重施压」新增**内联执行卡**（落笔顺序），执行者无需翻阅 `references/mental-models.md` 即可落笔，单文件可执行性闭环（补 Luban P1「资源整合度」缺口）。
- **README 安装入口补全**：新增 Codex / Cursor / 通用 Agent 一行安装段；补充 `scripts/selfcheck.md` 与 `test-prompts.json` 的自测/回归入口链接；版本 badge 与版本号同步至 2.0.3。
- **新增 `scripts/selfcheck.md`**：将 Step 5 质检清单固化为可勾选模板（含元信息栏、修复记录表、熔断规则），作为轻量验证资产，对齐同行「可运行验证」差距。

> 评估背景：Darwin 与 Luban 同日基线评估均为 84/100；本版仅做清晰度与公开可用性打磨，**未改动核心协议与 5 条创作伦理铁律**。

## [2.0.2] - 2026-06-11

### Fixed
- Recovered the April hardening features accidentally dropped by the v2.0.2 rewrite: Active Checks dynamic checklist, receipt columns, dynamic memory/feedback alignment, compliance statement, execution-priority anchor, mental-model action index.
- Restored the non-distribution policy for `references/` (verbatim-quote material stays local-only).
- De-duplicated version history out of [SKILL.md](SKILL.md) (this changelog is the single source).

### Added
- Darwin optimization rounds: progressive-disclosure split (deep reference out of SKILL.md), step-level if-then fallbacks (recipe extraction, word-count overflow, scale misjudgment), CHECKPOINT 0/1/2 STOP markers, polish-attachment routing, repair circuit breaker, and an explicit call interface for the model library.

## [2.0.1] - 2026-04-20

### Changed
- Moved detailed version history and roadmap out of [README.md](README.md) into this changelog.
- Reduced [SKILL.md](SKILL.md) frontmatter to the current version only.
- Added stronger user-preference override logic, Checkpoint 2, and persistent receipt constraints.
- Moved theory, model explanations, and influence maps into [README.md](README.md) as the static reference layer.

### Notes
- This is a documentation and protocol-hardening patch release.
- The public distribution still excludes `references/`.

## [2.0.0] - 2026-04-17

### Added
- Initial v2.0 protocol redesign.
- Step 0~6 narrative workflow.
- Fragment / Grand Finale scale split.
- Recipe-card flow, polishing pipeline, and Dragon 5 patch support.

### Changed
- Reframed the skill from a technique manual into a narrative protocol.

## [1.1.0] - 2026-04-17

### Added
- Darwin strategic sampling augmentation.
- Cross-genre DNA and polishing toolchain.

## [1.0.0] - 2026-04-17

### Added
- Initial Nuwa distilled version.
- Core mental models and baseline writing guidance.