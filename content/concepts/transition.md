---
type: concept
title: Transition（過渡語）
aliases: [過渡語, transitional phrase]
tags: [claim-structure, claim-drafting]
source_count: 2
---

# Transition（過渡語）

## 定義

Transition 是連接 [[preamble|前言]] 與 [[claim-body|請求項主體]] 的過渡詞語，決定了請求項的開放或封閉程度——即請求項是否排除未列出的額外元素。

## 詳細說明

### 三種主要過渡語

| 過渡語 | 類型 | 含義 | 適用情境 |
|--------|------|------|----------|
| **comprising** | 開放式（open-ended） | 包含所列元素，但**不排除**未列出的額外元素 | 最常用，適用於幾乎所有情境 |
| **consisting of** | 封閉式（closed） | **僅由**所列元素組成，排除所有未列出的元素 | 化學組成物、需要精確定義時 |
| **consisting essentially of** | 半開放式 | 排除會**實質改變發明基本特徵**的額外元素，但允許不影響基本特徵的添加物 | 化學/材料領域，需在開放與封閉之間取得平衡 |

### Comprising 的重要細節（Landis §2.5）

- Comprising **確實要求**每個列出的元素必須存在——不可省略任何一個
- Comprising **不等於完全開放**——說明書或審查歷史可能縮小其範圍
- **"Having"** 在實務上有爭議：在某些脈絡下被解讀為開放式，但在其他脈絡下等同封閉式，應謹慎使用
- **"Including"** 與 comprising 同義，完全開放
- "Comprising the steps of" **不**將方法請求項轉為 step-plus-function 解釋（§112 ¶6）
- 元素前的不定冠詞 "a" 在 comprising 請求項中代表「**一個或多個**」，而非僅限「一個」

### 同義詞

- **comprising** 的同義詞：including, containing, characterized by（"having" 有爭議，慎用）
- **consisting of** 的同義詞：composed of, having only, being（在某些語境下）

### 元素到子元素的過渡

在請求項 body 內部，當某元素包含子元素時，也需要使用過渡語。此時同樣適用上述三種類型。

### 方法請求項中的過渡

方法（method/process）請求項中，傳統上使用 "the steps of" 作為過渡語的一部分（如 "A method comprising the steps of..."）。但 "step of" 的使用可能觸發 35 U.S.C. §112 ¶6 的 step-plus-function 解釋，Sheldon 建議**避免使用 "step of"**。

## 來源參照
- [[sheldon-ch6-claim-drafting]]：§6.3.4 詳述各種過渡語的法律效果、同義詞與使用範例
- [[landis-ch02-claim-forms-formats]]：§2.5-§2.6 以大量 Federal Circuit 判例詳述 comprising（開放式）、consisting of（封閉式）、consisting essentially of（半開放式）的精確法律效果；強調 comprising 不等於完全開放、"having" 的爭議性，以及 "comprising the steps of" 不觸發 step-plus-function 解釋

## 相關概念
- [[preamble]]：過渡語之前的前言
- [[claim-body]]：過渡語之後的主體
- [[means-plus-function]]：功能性語言的法律效果（與 "step of" 相關）

## 實務要點

1. **預設使用 "comprising"**——Faber 直言「沒有其他詞能做到同樣效果」
2. 避免使用 "having" 作為過渡語——其開放性在訴訟中有爭議，易產生不確定性
3. 在策略上，"consisting of" 雖然窄，但在化學組成物中可能是必要的
4. 若需擴大請求項範圍，首先檢查是否可將 "consisting of" 改為 "comprising"
5. 避免在方法請求項中使用 "step of"，改用 "A method comprising: [步驟動名詞]..."
6. 記住：comprising 確保每個元素都必須存在，但不排除額外元素——兩者缺一不可
