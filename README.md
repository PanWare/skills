# 🧩 Skills

个人创建的 AI Agent Skill 合集。所有 Skill 按分类文件夹组织，便于查找与复用。

## 目录结构

```
skills/
├── category-a/            # 分类 A（示例）
│   └── my-skill/
│       ├── skill.md       # Skill 定义（名称、描述、触发条件、指令）
│       └── ...            # 辅助脚本、模板等资源
├── category-b/            # 分类 B（示例）
│   └── ...
└── LICENSE
```

- **一级目录** — Skill 分类，按领域或用途划分
- **二级目录** — 单个 Skill，文件夹名即 Skill 名称
- **skill.md** — 每个 Skill 的核心定义文件，包含名称、描述、触发规则与执行指令

## 使用方式

1. 找到所需 Skill 文件夹
2. 将整个文件夹复制到你的 Agent 项目的 Skill 目录中
3. 按照 Skill 内 `skill.md` 的说明完成配置，即可启用

## Skill 规范

每个 Skill 文件夹应至少包含一个 `skill.md`，建议结构如下：

```markdown
---
name: skill-name
description: 一句话描述 Skill 的功能
triggers:
  - 触发关键词或条件
---

# Skill 名称

## 功能说明
详细描述 Skill 的作用与适用场景。

## 使用方法
配置步骤与注意事项。

## 依赖
所需的外部工具、API 或环境变量（如有）。
```

## License

[MIT](LICENSE) © PanWare/AI天下仓  
[MIT](LICENSE) © JasonShane
