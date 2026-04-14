---
type: concept
title: Composition of Matter Claims（組合物請求項）
aliases: [組合物請求項, 化學請求項, composition claims, chemical claims]
tags: [claim-type, claim-drafting, chemical, pharmaceutical, composition]
source_count: 1
---

# Composition of Matter Claims（組合物請求項）

## 定義

**Composition of matter（物質組合物）**是 35 U.S.C. §101 四大可專利標的之一，指化學元素、基（radical）或化合物以特定方式結合而成的物質。組合物請求項以**化學性質**（而非形狀或實體結構）界定受保護的發明。

---

## 詳細說明

### 基本結構

組合物請求項的標準撰寫方式為：列舉所有必要**成分（ingredients）**，並搭配各成分的**比例範圍（proportions）**：

```
A composition comprising:
  component A in an amount of 10-30% by weight;
  component B in an amount of 5-15% by weight; and
  component C in an amount of 1-5% by weight.
```

**注意事項**：
- 所有**必要成分**都必須納入請求項；遺漏必要成分會造成請求項支持不足
- 比例可使用數值範圍，選擇範圍寬度時應考慮說明書實際揭露的實施例
- 純粹選擇性成分（optional ingredients）可不列入，或以 "optionally" 修飾

---

### 過渡語的選擇

過渡語的選擇對組合物請求項的範圍至關重要：

| 過渡語 | 類型 | 效果 | 說明 |
|--------|------|------|------|
| `comprising` | 開放式 | 允許未列舉的額外成分 | 最寬廣；競爭者添加第 4 種成分不能規避 |
| `consisting of` | 封閉式 | 排除所有未列舉成分（含微量雜質） | 最窄；可能因微量雜質存在而難以侵權 |
| `consisting essentially of` | 半封閉 | 允許不影響基本特性的微量成分 | 折衷方案；需要說明什麼算「基本特性」 |

**實務建議**：在組合物請求項中，`comprising` 通常是最佳選擇，除非必須明確排除特定成分。

---

### 化學界定 vs. 物理界定

化學組合物可以從以下角度界定：

1. **成分界定**（最常用）：列舉成分 + 比例
2. **結構界定**：以化學式、立體化學描述
3. **性質界定**（指紋請求項）：以物理化學性質界定（適用於結構未知的情況）
   - X-光繞射（X-ray diffraction）
   - 熔點（melting point）
   - 溶解度（solubility）
   - IR / NMR 光譜
   - 參見：[[fingerprint-claims]]（指紋請求項）

---

### 常見特殊情況

#### 1. 新化合物（Novel Compounds）
- 以化學結構式 + IUPAC 命名請求
- 若結構複雜，配合 Markush 表述請求一類化合物

#### 2. 混合物/配方（Formulations/Mixtures）
- 藥物配方、農用化學品、塗料等
- 注意：`comprising` 在這類請求項中尤其重要（競爭者常通過添加成分試圖規避）

#### 3. 生物組合物（Biological Compositions）
- 抗體、蛋白質、核酸序列等
- §112(a) 書面描述要求特別嚴格（見 [[generic-species-claims]]）
- 功能性定義（functional genus）面臨 *Amgen v. Sanofi*（2023）後的高風險環境

#### 4. 製藥組合物（Pharmaceutical Compositions）
- 可使用「治療有效量（therapeutically effective amount）」語言（*Acorda Therapeutics v. Alkem*, 2019）
- 需配合說明書中的劑量範圍資料

---

### 商標與商品名稱的禁止使用

**Butler 四原則**：
1. 商標是**來源識別符**，不是物質說明
2. 不得以商標作為請求項成分描述（例如："Teflon" 不可作為成分）
3. 必須用通用名稱（generic name）或化學名稱替代
4. 若因此受到 §112 核駁，可提起異議（USPTO 有時會過度核駁）

---

### 新用途（New Use）的特殊處理

**Thuau 原則**：不得將新用途包裝為組合物請求項（即「用於 X 用途的組合物 Y」）
- 理由：組合物本身的化學組成不因使用目的而不同，相同組合物不能因為新用途就獲得另一個組合物專利
- **正確作法**：新用途必須以[[method-claims|方法請求項]]形式主張
- 實務策略：同時提交：
  - 組合物請求項（保護物質本身）
  - 方法請求項（保護使用方法）
  - 製備方法請求項（保護合成路徑）

---

### 子組合（Subcombination）策略

- **子組合**是主要組合中的一部分（fewer elements = broader claim）
- 子組合請求項須具有**獨立效用（utility in itself）**——不能只是附屬功能
- 策略：
  1. 最廣子組合請求項（僅含最核心成分）
  2. 中間範圍請求項（加入部分輔助成分）
  3. 具體完整組合物請求項（所有成分 + 精確比例）

---

## 來源參照
- [[landis-ch06-composition-of-matter]]：§6.1–§6.11 完整涵蓋化學請求項各類型

## 相關概念
- [[markush-group]]：化學替代方案的 Markush 表述形式
- [[jepson-claim]]：用於改進已知組合物的 Jepson 式請求項
- [[generic-species-claims]]：上位概念/下位概念策略，包括功能性上位概念的 §112(a) 風險
- [[product-by-process]]：以製程界定的組合物（PBP 請求項）
- [[method-claims]]：新用途必須以方法請求項主張（Thuau 原則）
- [[enablement]]：「治療有效量」須有充分說明書支持
- [[written-description]]：功能性上位概念請求項的書面描述高標準（Ariad/Amgen）
- [[statutory-classes]]：§101 四大標的類別中的組合物類別

## 實務要點

1. **成分 + 比例**是組合物請求項的基本骨架——不要遺漏必要成分，但選擇性成分可以 "optionally" 納入或省略
2. **`comprising` 是預設選擇**——除非有充分理由排除額外成分，否則不用 `consisting of`
3. **禁用商標名**——必須使用通用化學名稱（IUPAC 或業界通用名）
4. **新用途 ≠ 新組合物**——新用途請求項必須用方法形式（Thuau 原則）
5. **功能性上位概念高風險**——*Amgen v. Sanofi*（2023）後，說明書必須提供足夠的物種揭露以支持廣泛的功能性請求項
6. **治療有效量可接受**——但需搭配說明書中充分的劑量資料
7. **子組合可單獨請求**——前提是有獨立效用，不能只是主發明的附屬功能
8. **指紋請求項是備用工具**——當結構未知時，以性質定義組合物；但需確保 §112(b) 確定性
