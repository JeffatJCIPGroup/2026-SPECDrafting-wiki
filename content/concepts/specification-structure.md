---
type: concept
title: Specification Structure（說明書結構）
aliases: [說明書結構, 說明書各節, specification sections]
tags: [specification, 說明書, 結構]
source_count: 1
---

# Specification Structure（說明書結構）

## 定義

美國專利說明書的標準結構由 USPTO 規定，各節有固定的順序與功能。Sheldon 在 CH7 中對每一節提供了詳細的撰寫建議。

## 詳細說明

### 標準說明書結構

```
1. Title（發明名稱）
2. Cross-References（交叉引用）
3. Government Rights（政府權利聲明）[適用時]
4. Background（背景技術）
5. Summary（發明摘要）
6. Brief Description of Drawings（圖式簡單說明）
7. Description of the Invention（發明詳細說明）
8. Claims（請求項）
9. Abstract（摘要）
```

### 各節撰寫要點

#### Title（發明名稱）
- 簡短、功能性描述，通常不超過 7 個詞
- 應反映最寬請求項的主題
- 避免商標、發明人姓名

#### Background（背景技術）
- 描述現有技術及其**問題**
- **禁止**過度讚揚先前技術（避免在訴訟中被用於限縮請求項範圍或承認先前技術）
- **禁止**揭露可能被視為承認先前技術的資訊
- 簡短為宜

#### Summary（發明摘要）
- 緊扣最寬的獨立項語言（幾乎逐字轉述）
- **避免使用 "the invention"**（改用 "the present disclosure"、"embodiments" 等）
- 描述各獨立項所代表的不同發明面向
- 可加入「The foregoing and other features and advantages will become apparent...」的標準閉合語

#### Brief Description of Drawings（圖式簡單說明）
- 以 "Figure N is a [類型] view showing..." 格式逐一描述每張圖式
- 使用中性詞描述不同版本（"Version 1"、"alternative embodiment"）
- **不使用** "preferred embodiment"（避免限縮請求項範圍）

#### Description of the Invention（發明詳細說明）
建議的內部結構（§7.5.10.3）：
1. **Definitions（定義）**：定義非通常含義的術語
2. **Overview（概述）**：整體發明的高層次描述，讓陪審員能理解
3. **Detailed Description of Elements（元素詳述）**：逐一描述每個元素的結構與功能
4. **How the Invention Is Used（使用方法）**：說明各元素如何協作以達成功能
5. **Advantages（優點）**：列出發明相對於先前技術的優點
6. **Specific Embodiments and Examples（具體實施例）**：包含 working examples 或 prophetic examples
7. **Alternatives and Closing（替代方案與閉合）**：列舉替代方案、加入標準閉合段

#### Abstract（摘要）
- 不超過 150 個詞
- 摘述最具代表性的請求項
- 不得以宣傳性語言描述（如 "The present invention is a great improvement..."）

### 「Theme」方法（§7.5.1）

在動筆前，發展一個簡短有力的主題句，整份說明書圍繞此主題撰寫。例如：
- "The first easily processed polyimide resin stable at temperatures higher than 700°F"
- "A durable, compact grill scraper that can be inexpensively mass produced"

### 標準閉合段（§7.5.10.3.7）

```
Although the present invention has been described in considerable detail with
reference to certain preferred versions thereof, other versions are possible.
For example, [替代方案列表]. Therefore, the spirit and scope of the appended
claims should not be limited to the description of the preferred versions
contained herein.
```

### §112 ¶6 防護語言

若不意圖使用 [[means-plus-function|means-plus-function]] 解釋，加入：
```
Any element in a claim that does not explicitly state "means for" performing
a specified function, or "step for" performing a specific function, is not
to be interpreted as a "means" or "step" clause as specified in 35 U.S.C.
§112, ¶6.
```

## 來源參照
- [[sheldon-ch7-specification-drafting]]：§7.5 完整逐節說明撰寫要點

## 相關概念
- [[written-description]]：說明書必須滿足的法律要求之一
- [[enablement]]：說明書必須滿足的法律要求之二
- [[best-mode]]：說明書必須滿足的法律要求之三
- [[antecedent-basis]]：說明書中的術語必須為請求項提供前提基礎

## 實務要點

1. 先寫請求項（[[sheldon-ch6-claim-drafting|CH6]] 的建議），再以請求項為骨架撰寫說明書
2. Summary 節直接改寫最寬獨立項
3. Description 節以參考號碼為錨點，逐一描述每個請求項元素
4. 確保每個請求項元素在 Description 中都有對應揭露
5. 數值範圍要完整：最廣範圍、較寬範圍（preferred）、最窄範圍（most preferred）
