---
type: concept
title: Means-Plus-Function（手段加功能）
aliases: [means clause, 手段加功能請求項, 35 USC 112 paragraph 6]
tags: [claim-drafting, functional-language, 112]
source_count: 1
---

# Means-Plus-Function（手段加功能）

## 定義

Means-plus-function 是一種請求項撰寫方式，以「means for + 功能描述」的形式定義請求項中的元素，而非以具體結構來定義。根據 [[statute-35usc112|35 U.S.C. §112]] 第六段，此種表述的範圍被限制為說明書中揭露的對應結構及其均等物。

## 詳細說明

### 法律基礎

35 U.S.C. §112 ¶6 規定：請求項中的元素可以「用於執行特定功能的手段或步驟」的形式表述，而不需記載支持該功能的結構、材料或行為。但該元素的範圍被限制為說明書中揭露的**對應結構、材料或行為**及其**均等物**。

### 與純功能性語言的區別

| 類型 | 範例 | 範圍 |
|------|------|------|
| Means clause | "means for fastening" | 限於說明書揭露的結構及均等物 |
| 純功能性語言 | "a fastener configured to..." | 涵蓋所有能執行該功能的結構 |

純功能性語言（不使用 "means for"）通常不觸發 §112 ¶6，因此範圍可能更寬。但如果純功能性語言過於寬泛，可能被認為 indefinite 或不具可實施性。

### 撰寫策略

- Means clause 提供了一種簡潔的方式來寬泛定義元素
- 但因範圍限於說明書揭露的結構，**說明書必須充分揭露對應結構**
- 若說明書未揭露對應結構，means clause 將因 indefinite 而無效
- Sheldon 建議同時使用 means clause 版本與純功能性語言版本的請求項

## 來源參照
- [[sheldon-ch6-claim-drafting]]：§6.3.5.1.4（功能性定義）、§6.5.3.3（策略性使用）

## 相關概念
- [[claim-body]]：means clause 出現在 body 中
- [[statute-35usc112]]：法律依據
- [[independent-claim]]：在獨立項中使用 means clause 的策略

## 實務要點

1. 使用 means clause 時，務必確保說明書中有充分的結構對應揭露
2. 考慮同時撰寫有 means clause 和無 means clause 的請求項版本
3. 若 "means for" 後的功能描述過於空泛（如 "means for processing"），可能被認為毫無意義（meaningless means clause）
4. 注意：在方法請求項中使用 "step of" 可能觸發類似的 step-plus-function 解釋
