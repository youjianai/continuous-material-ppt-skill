# continuous-material-ppt

一个自包含的、可持续打磨的连续材质 PPT 设计 Skill 仓库。它把视觉规则、页面类型、可编辑模板、真实示例和 QA 规则放在一起，便于在 Codex、Claude、Cursor 或其他 Agent 中复用。

## 使用方式

把本仓库交给 Agent，并说明：

```text
使用 continuous-material-ppt，制作一份关于「主题」的 N 页 PPT。
听众是「听众」，目标是「目标」，素材在「目录」。
```

Agent 应先读取 `SKILL.md`，再读取 `references/`，并使用 `assets/templates/continuous-material-template.pptx` 作为视觉参考。

## 版本建议

每次视觉系统有实质变化时更新版本号和 CHANGELOG。项目内容、客户材料和未获授权的第三方素材不要提交到公共仓库。
