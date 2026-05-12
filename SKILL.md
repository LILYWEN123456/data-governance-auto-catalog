---
name: data-governance-auto-catalog
skill_id: data_governance_auto_catalog
version: 1.0.0
author: Data Governance Team
description: 从Excel或数据库自动生成标准数据编目，自动字段匹配、自动资源挂载、生成编目草稿
type: data
tags:
  - 数据治理
  - 智能编目
  - 字段映射
  - 资源挂载
  - 目录生成
trigger:
  - 生成数据编目
  - 自动编目
  - 数据目录
  - 生成编目草稿
  - 数据库表编目
---

# 数据治理智能编目 Skill

## 功能
1. 读取客户A上传的Excel源数据
2. 或读取指定数据库表结构
3. 自动匹配标准编目模板字段
4. 自动生成信息项、字段说明、数据来源
5. 生成标准化编目Excel（客户B模板）
6. 输出：编目草稿 + 字段映射报告

## 输入
- 源数据Excel（.xlsx）
- 或 数据库连接信息 + 表名
- 标准编目模板（内置）

## 输出
- 标准数据编目.xlsx
- 字段映射清单.json
- 待确认字段提示