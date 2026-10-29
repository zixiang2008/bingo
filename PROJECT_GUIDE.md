# bingo · Multilingual Project Guide

<p align="center">
  <a href="#简体中文">中文</a> ·
  <a href="#english">English</a> ·
  <a href="#日本語">日本語</a> ·
  <a href="#ภาษาไทย">ไทย</a>
</p>

> Bingo 是一款基于 AI 的 Android 英语词汇学习应用，输入单词后可一键调用 Claude API                                自动填充音标、释义、词根拆解、近义词、形近词和同根词，详情页以结构化方式展示词根构成并基于构词成分相似度自动关联联想词  ，已存在于辞书中的关联词均可点击跳转，同时内置基于艾宾浩斯遗忘曲线的 10 级间隔复习系统和 JSON 格式的辞书导入导出功能。同时也支持解析文章，自动关联辞书词汇。

---

## 简体中文

### 项目概览

- 类型：原创仓库
- 可见性：public
- 主要技术：Gradle / Android
- 默认分支：`master`

本仓库源自 [上游项目](https://github.com/chenhuawang-04/Bingo)，上游文档与许可证条款仍是最终依据。

### 架构与设计原则

项目以 Gradle / Android 为主要技术载体。代码、配置、静态资源与文档按仓库原有结构组织。维护时应保持最小改动、兼容原有入口，并在合并前运行项目现有的构建与测试。

### 使用方法

1. 克隆仓库：`git clone https://github.com/zixiang2008/bingo.git`
2. 阅读原 README 及依赖清单，确认当前分支需求。
3. 安装依赖：`./gradlew dependencies`
4. 启动或构建：`./gradlew build`
5. 验证变更：`./gradlew test`

命令为通用入口；若与原 README 不同，以原项目文档和仓库脚本为准。请勿将密码、API 密钥、私钥或生产环境配置提交到 Git。

---

## English

### Project overview

- Type: Original repository
- Visibility: public
- Primary stack: Gradle / Android
- Default branch: `master`

This repository is derived from [the upstream project](https://github.com/chenhuawang-04/Bingo). Upstream documentation and licensing remain authoritative.

### Architecture and design principles

The project uses Gradle / Android as its primary technical foundation. Source code, configuration, static assets, and documentation follow the repository's existing structure. Maintenance should favor small compatible changes and run the existing build and test checks before merge.

### Usage

1. Clone: `git clone https://github.com/zixiang2008/bingo.git`
2. Read the original README and dependency manifest for branch-specific requirements.
3. Install: `./gradlew dependencies`
4. Run or build: `./gradlew build`
5. Verify: `./gradlew test`

These are safe general entrypoints. If they differ from the original README, follow the repository's own scripts and upstream documentation. Never commit passwords, API tokens, private keys, or production configuration.

---

## 日本語

### プロジェクト概要

- 種別: オリジナルリポジトリ
- 公開範囲: public
- 主な技術: Gradle / Android
- デフォルトブランチ: `master`

このリポジトリは [アップストリーム](https://github.com/chenhuawang-04/Bingo) から派生しています。上流のドキュメントとライセンスが優先されます。

### アーキテクチャと設計原則

Gradle / Android を主要な技術基盤とし、ソース、設定、静的アセット、文書は既存のリポジトリ構成に従います。保守では小さく互換性のある変更を優先し、マージ前に既存のビルドとテストを実行します。

### 使い方

1. クローン: `git clone https://github.com/zixiang2008/bingo.git`
2. 元の README と依存関係を確認します。
3. インストール: `./gradlew dependencies`
4. 実行またはビルド: `./gradlew build`
5. 検証: `./gradlew test`

コマンドが元の README と異なる場合は、リポジトリ固有のスクリプトと上流文書を優先してください。パスワード、API トークン、秘密鍵、本番設定を Git にコミットしないでください。

---

## ภาษาไทย

### ภาพรวมโครงการ

- ประเภท: รีพอสิทอรีต้นฉบับ
- การมองเห็น: public
- เทคโนโลยีหลัก: Gradle / Android
- บรานช์เริ่มต้น: `master`

รีพอสิทอรีนี้ต่อยอดจาก [โครงการต้นทาง](https://github.com/chenhuawang-04/Bingo) โดยให้ถือเอกสารและสัญญาอนุญาตของต้นทางเป็นหลัก

### สถาปัตยกรรมและหลักการออกแบบ

โครงการใช้ Gradle / Android เป็นพื้นฐานหลัก โดยจัดซอร์สโค้ด การตั้งค่า ไฟล์สถิต และเอกสารตามโครงสร้างเดิม ควรแก้ไขทีละน้อยโดยรักษาความเข้ากันได้ และรันการสร้างและทดสอบเดิมก่อนรวมโค้ด

### วิธีใช้

1. โคลน: `git clone https://github.com/zixiang2008/bingo.git`
2. อ่าน README เดิมและไฟล์รายการ dependency
3. ติดตั้ง: `./gradlew dependencies`
4. รันหรือสร้าง: `./gradlew build`
5. ตรวจสอบ: `./gradlew test`

หากคำสั่งต่างจาก README เดิม ให้ยึดสคริปต์ของรีพอสิทอรีและเอกสารต้นทางเป็นหลัก ห้าม commit รหัสผ่าน API token กุญแจส่วนตัว หรือการตั้งค่า production ลง Git
