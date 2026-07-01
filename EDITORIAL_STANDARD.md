# EDITORIAL_STANDARD.md
## Project Logos Editorial Standard

Version: 0.1
Status: Active

---

# Purpose

本書は、Project Logos（知的主体共生論）における文書作成・編集・更新の基準を定める。

目的は、

・理論の一貫性を維持すること

・議論と成果物を区別すること

・変更履歴を追跡可能にすること

である。

---

# Basic Principles

Repository に保存される文章は、

「研究成果」

として扱う。

チャットでの議論は成果物ではない。

成果物へ反映された時点で正式文書となる。

---

# Language

標準言語は日本語とする。

README.md のみ英語による概要を掲載する。

本文については日本語を正式版とする。

閲覧者は必要に応じて翻訳ツール等を利用するものとする。

将来的な多言語対応は約束しない。

---

# Writing Style

文章は、

・簡潔

・中立

・論理的

であること。

断定できない事項については断定しない。

推測は推測として記述する。

---

# Classification

理論内では必ず以下を区別する。

## Fact

現在確認されている事実。

---

## Definition

Project Logos が採択した定義。

---

## Inference

推論・仮説。

---

## Unknown

未解明事項。

Unknown は研究対象であり、
無理に削除・補完しない。

---

# Definitions

Definition は、

変更履歴が追跡できるようVersion管理する。

例

Subject v0.1

Ability v0.1

など。

---

# Unknown Policy

Unknown を削除してはならない。

Factになった場合のみ変更できる。

Unknown は理論の欠陥ではなく、

今後の研究課題として保存する。

---

# Revision Policy

既存文章への追記よりも、

必要に応じて文章全体を修正する。

変更時は、

CHANGELOG.md

へ記録する。

---

# Repository Structure

Repository は、

議論

成果物

管理文書

を明確に分離する。

例

README.md

CHARTER.md

docs/

research/

CHANGELOG.md

---

# File Naming

英数字・小文字・スネークケースを基本とする。

例

subject_v0.1.md

unknown.md

roadmap.md

---

# Versioning

Version は、

Major.Minor

で管理する。

例

v0.1

v0.2

v1.0

理論の変更履歴は削除しない。

---

# Research Integrity

Project Logos は、

結論を優先しない。

理論は、

Fact

↓

Definition

↓

Inference

↓

Unknown

を区別しながら構築する。

---

# Editorial Responsibility

編集時には、

過去の研究成果との整合性を確認する。

矛盾が発見された場合、

直ちに修正せず、

Unknown または次回議題として扱う。

---

# Living Document

本書は Living Document とする。

研究の進展に応じて更新される。

ただし、

更新履歴は保存される。
