---
type: concept
title: Jepson Claim（Jepson 式請求項）
aliases: [Jepson 式請求項, Jepson-type claim, improvement claim, characterized in that]
tags: [claim-type, claim-drafting, jepson, improvement, biotech]
source_count: 2
---

# Jepson Claim（Jepson 式請求項）

## 定義

Jepson claim 是一種特殊的請求項形式，將已知的先前技術元素放在 [[preamble|preamble]] 中，改進之處放在 [[claim-body|body]] 中，兩者以 "wherein the improvement comprises" 作為 [[transition|過渡語]] 連接。法規依據：37 C.F.R. Rule 75(e)——允許但不強制使用。

## 詳細說明

### 形式

```
In a [已知裝置/方法/組合物的描述],
wherein the improvement comprises:
[改進的元素或特徵]
```

歐洲等效語：「characterized in that」（在 EPO 申請中廣泛使用）

### 法律效果

- **preamble = 先前技術承認（admission of prior art）**：前言中所有元素推定為申請人對先前技術的承認；對手在訴訟中可利用此自認主張相關特徵為已知
- **過渡語固定**：必須使用 "wherein the improvement comprises"（或等效語言），不可替換為 "comprising" 等標準語
- **body = 改進特徵**：只有主體中的改進特徵才是真正的新穎性所在

### 傳統觀點：不建議使用

Sheldon 認為 Jepson claim 應**謹慎使用（disfavored）**，原因包括：

1. **承認先前技術**：preamble 中的所有元素被推定為先前技術，即使其中部分實際上可能是申請人自己的發明
2. **範圍限制**：Jepson 形式的 preamble 本身構成請求項範圍的限制
3. **均等論限縮**：訴訟中可能因 preamble 的承認而限制均等論（doctrine of equivalents）的適用

### 現代觀點：生技/化學領域的復興用途（§112(a) 緩解策略）

Faber（Landis, §6.8）提出 Jepson 在生技和化學領域的**特殊用途**，尤其在 *Juno v. Kymriah*（2021）和 *Amgen v. Sanofi*（2023）後：

**場景**：功能性上位概念請求項（如「所有能結合抗原 X 的 scFv 片段」）面臨 §112(a) 書面描述要求不足的問題

**Jepson 解法**：
- **前言**：「In a chimeric antigen receptor (CAR) comprising [已知的 CAR 骨架結構和組件],」
- **主體**：「wherein the improvement comprises [新型功能模組/信號域/連接子]」

**優勢**：
1. 主體範圍更**窄**（僅涵蓋改進部分），§112(a) 要求相對容易滿足
2. 已知技術在前言中明確，審查員/法院對「前言 = 先前技術」有共識，減少爭議
3. 若改進特徵本身結構明確，可有效規避功能性上位概念的 §112(a) 危機

**前提條件**：承認前言中的內容為先前技術**不影響請求項的實質保護範圍**，亦即先前技術部分確實已是公知技術。

### 何時考慮使用

✅ **適合使用 Jepson 的情形**：
- 發明確實是對業界公知平台技術的改進（先前技術已非常明確）
- 複雜的先前技術背景使標準請求項可讀性差
- 需要迴避功能性上位概念 §112(a) 問題，且改進部分範圍可精確描述
- 對已知藥物結構/蛋白質骨架的改進
- 已知機械/化學系統中的特定組件改良

❌ **不適合使用 Jepson 的情形**：
- 前言中的元素並非確定的先前技術（承認風險太大）
- 標準請求項形式同樣能達成目的
- 不需要分離「已知部分」和「改進部分」
- 希望保留對前言元素主張均等論的可能性

## 來源參照
- [[sheldon-ch6-claim-drafting]]：§6.4.3 說明 Jepson claim 的形式與傳統不建議使用的理由
- [[landis-ch06-composition-of-matter]]：§6.8 說明 Jepson 在生技/功能性上位概念請求項中的 §112(a) 緩解策略

## 相關概念
- [[preamble]]：Jepson claim 中 preamble 的特殊先前技術承認效果
- [[generic-species-claims]]：功能性上位概念的 §112(a) 危機（Jepson 的使用背景）
- [[written-description]]：§112(a) 書面描述要求——Jepson 試圖緩解的主要挑戰
- [[composition-of-matter-claims]]：化學/生技組合物中的 Jepson 應用
- [[independent-claim]]：Jepson claim 是獨立項的一種特殊形式

## 實務要點

1. **傳統上應避免，但非絕對禁忌**——在先前技術明確的改進型發明中，Jepson 有其價值
2. **確認前言確實是先前技術**——若前言中有任何非先前技術的元素，使用 Jepson 有承認風險
3. **生技改進型發明的新選項**——*Amgen v. Sanofi*（2023）後，Jepson 形式提供了一條降低功能性上位概念 §112(a) 風險的替代路徑
4. **"wherein the improvement comprises" 是固定格式**——不要替換為其他過渡語
5. **配合標準請求項備份**——Jepson 作為附加保護，但標準 comprising 形式請求項仍應同時提交
6. **歐洲申請可沿用**——EPO 廣泛接受 "characterized in that" 形式（等同 Jepson），美國 Jepson 格式有利於國際協調
