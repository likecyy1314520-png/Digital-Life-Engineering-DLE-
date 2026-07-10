---
id: STANDARDS-README
title: Standards Layer Guide
title_zh: 标准层指南
version: Genesis-v0.2
status: Frozen
language:
  - en
  - zh-CN
canonical: true
owner: Digital Life Engineering Project
lifecycle: Frozen
review_round: 2
---

# Standards Layer Guide / 标准层指南

## Purpose / 目的

### English
The Standards Layer defines the engineering standards used by the Digital Life Engineering (DLE) project.

It provides a structured system for creating, maintaining, and applying reusable engineering rules.

### 中文
Standards Layer 用于定义 Digital Life Engineering（DLE）项目所使用的工程标准。

它提供一个结构化体系，用于创建、维护和应用可复用的工程规则。

---

## Standards Layer Overview / 标准层概述

### English
The Standards Layer is positioned between the Repository Layer and Knowledge Layers.

Its responsibility is to define standards, not knowledge content.

### 中文
Standards Layer 位于 Repository Layer 与知识层之间。

它的职责是定义标准，而不是定义知识内容。

---

## Standard Families / 标准分类

### English

| Prefix | Name |
|---|---|
| DDS | Documentation Standards |
| DES | Engineering Standards |
| DPS | Process Standards |
| DAS | Architecture Standards |

### 中文

| 前缀 | 名称 |
|---|---|
| DDS | 文档工程标准 |
| DES | 工程实践标准 |
| DPS | 工程流程标准 |
| DAS | 架构设计标准 |

---

## Directory Structure / 目录结构

### English
```text
standards/
├── README.md
├── documentation/
├── engineering/
├── process/
└── architecture/
```

### 中文
```text
standards/
├── README.md
├── documentation/
├── engineering/
├── process/
└── architecture/
```

---

## Standard Lifecycle / 标准生命周期

### English
Proposal → Draft → Review → Accepted → Published → Superseded

Accepted means the standard has been approved as an official DLE standard.

Published means the standard is available for practical use and can be referenced by DLE documents.

### 中文
Proposal（提案）→ Draft（草稿）→ Review（评审）→ Accepted（采纳）→ Published（发布）→ Superseded（替代）

Accepted 表示该标准已经完成评审，并被批准成为 DLE 正式标准。

Published 表示该标准已经可以被 DLE 文档引用并实际使用。

---

## Creating New Standards / 创建新标准

### English
New standards SHOULD:
- Belong to an existing standard family.
- Follow naming conventions.
- Receive proper review.
- Avoid duplicating existing standards.
- Have a unique identifier.

Format:

<PREFIX>-<NUMBER>-<NAME>

### 中文
新增标准应当：
- 属于已有标准体系。
- 遵循命名规范。
- 经过正式评审。
- 避免重复已有标准。
- 具有唯一编号。

格式：

<PREFIX>-<NUMBER>-<NAME>

---

## References / 引用

### English
- GOVERNANCE
- CONTRIBUTING
- SLAF-0001

### 中文
- GOVERNANCE
- CONTRIBUTING
- SLAF-0001
