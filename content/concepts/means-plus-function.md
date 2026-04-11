---
type: concept
title: Means-Plus-Function（手段加功能）
aliases: [means clause, 手段加功能請求項, MPF, 35 USC 112f]
tags: [claim-drafting, functional-language, 112, means-plus-function]
source_count: 2
---

# Means-Plus-Function（手段加功能）

## 定義

Means-plus-function（MPF）是一種請求項撰寫方式，以「means for + 功能描述」的形式定義請求項元素，而非以具體結構來定義。根據 35 U.S.C. §112(f)（原 §112 ¶6），此種表述的範圍**自動限縮**為說明書中揭露的對應結構及其等同物（equivalents）。

## 詳細說明

### 法律基礎：35 U.S.C. §112(f)

> An element in a claim for a combination may be expressed as a **means or step for performing a specified function** without the recital of structure, material, or acts in support thereof, and such claim shall be construed to cover the corresponding structure, material, or acts **described in the specification** and equivalents thereof.

核心效果：使用「means for」→ 請求項範圍被限縮至**說明書揭露的對應結構 + 等同物**，不再涵蓋所有能執行該功能的任意結構。

### 觸發條件：何時進入 §112(f)

**明確觸發**：
- 使用「**means for** [function]」
- 使用「**step for** [function]」（方法請求項）

**可能觸發（Nonce Words）**——*Williamson v. Citrix Online*（2015 en banc）：
- 使用「mechanism for」「module for」「device for」「element for」「unit for」「system for」等**一般性名詞（nonce words）+ 功能**
- 若該名詞在相關技術領域中**缺乏明確公認的結構意義**，法院將視同「means for」而適用 §112(f)
- *Williamson* 廢除了之前「presumption against MPF for non-means words」的較低標準

**不觸發的情形**：
- 「[具名結構] configured to [function]」——命名了具體結構（如「oscillator configured to oscillate」）
- 「[具名結構] for [function]」——名詞本身在技術領域有公認結構意義（如「circuit for detecting」）
- 術語本身有字典定義且有結構意義（如「filter」「amplifier」「processor」）

### 觸發後的法律效果

| 項目 | 效果 |
|------|------|
| 範圍 | 限縮至說明書揭露的對應結構 + 等同物 |
| 等同物時點 | **申請時**確定（不同於 DOE 的侵權時） |
| 等同物判斷 | 執行相同功能、以相同方式、達到相同結果 |
| 說明書揭露不足 | means 元素→不確定（indefinite）→無效 |

### MPF vs. 一般功能語言的比較

| 寫法 | 觸發 §112(f)？ | 範圍 |
|------|--------------|------|
| "means for fastening" | ✓ | 限於說明書結構及等同物 |
| "a fastener configured to fasten" | ✗ | 涵蓋所有能執行該功能的結構（較寬） |
| "a module for processing" | 可能（nonce word） | 視說明書結構意義而定 |
| "a processor configured to process" | ✗（若 processor 有公認結構含義） | 較寬 |

### Nonce Words 的實務風險（Williamson 後）

後 *Williamson* 時代，以下詞語在缺乏結構修飾時高度危險：
- `module`、`mechanism`、`component`、`element`、`unit`、`system`、`means`
- `arrangement`、`assembly`、`circuitry`、`logic`

**自救策略**：
1. 在說明書中為該詞提供明確的結構定義（"As used herein, 'module' refers to..."）
2. 在請求項中加入結構修飾："a **hardware** module"、"a **software** module comprising..."
3. 用 "configured to" 搭配已有公認結構的名詞："a **processor** configured to..."

### 軟體/計算機實現發明的 MPF 陷阱

- 對於軟體「means for X」，說明書**必須揭露對應的演算法**，否則不確定
- 僅描述「執行功能 X 的通用計算機」不足——必須有具體的演算法流程（*Biomedino, LLC v. Waters Technologies*）
- 例外：若功能本身足夠簡單，一般技術人員無需詳細說明即可實現（*Faber §3:15.10*）

### Means Clause 的範圍設計

**擴大 means 範圍的策略**：
- 在說明書中揭露**多種**執行該功能的替代結構（A、B、C）
- 明確陳述「the means may be implemented as A, B, or C, or any equivalent thereof」
- 包括在「先前技術中已知的」結構作為替代，可擴大等同物範圍

**限縮 means 範圍的反效果（需避免）**：
- 說明書只揭露一種結構 → 等同物範圍極窄
- 說明書強調某結構「必要」或「關鍵」→ 可能構成 [[disavowal]]

### 方法請求項中的 Step-Plus-Function

- 使用「step for [function]」→ 觸發 §112(f) 的 step-plus-function
- 使用「comprising the steps of...」→ **不**觸發（見 [[transition]]）
- 避免在方法請求項中使用「step of [function]」

### Single Means Claim（單一手段請求項）

- 僅包含一個 means 元素的獨立請求項（"means for achieving X"）是**無效**的
- 理由：(1) 因涵蓋所有可能結構而範圍過寬 (2) 違反 §101 適格性
- 解決方案：加入第二個元素作為組合請求項，或改用結構性語言

### Means at the Point of Novelty

- 若發明的新穎點落在 means clause（如「means for oscillating...」是新穎的）
- 以 MPF 表達新穎點 → 說明書揭露的有限結構決定保護範圍
- *Halliburton Oil Well Cementing v. Walker*（1946）：過於廣義的 means 主張引發了現行 §112(f)
- Faber 建議：新穎點元素盡量以具名結構 + "configured to" 表達，而非 "means for"

### MPF 等同物 vs. 均等論（DOE）

| | MPF 等同物 | 均等論（DOE） |
|--|--|--|
| 適用時點 | 申請時確定 | 侵權時確定 |
| 判斷標準 | 相同功能、方式、結果 | 相同功能、方式、結果（但更彈性） |
| 觸發條件 | 自動（§112(f) 觸發時） | 另行主張 |
| 可被 estoppel 排除 | 是（prosecution disclaimer） | 是（*Festo* 原則） |

## 來源參照
- [[sheldon-ch6-claim-drafting]]：§6.3.5.1.4、§6.5.3.3——means clause 的基礎策略
- [[landis-ch03-apparatus-machine-claims]]：§3:15.1–§3:15.20——完整的 MPF 法律分析，含 *Williamson* nonce word 問題、軟體 MPF 陷阱、single means、means at point of novelty、DOE vs. MPF 等同物

## 相關概念
- [[claim-body]]：means clause 出現在 body 中
- [[statute-35usc112]]：法律依據 §112(f)
- [[apparatus-claims]]：MPF 在裝置請求項中的特殊考量
- [[disavowal]]：說明書對 means 結構的過度限縮可能構成放棄
- [[statutory-classes]]：軟體 MPF 與 Alice 適格性問題的交叉

## 實務要點

1. **預設避免「means for」**——Faber 直言：用具名元素（如 oscillator）+ "configured to" 替代，既保留廣度，又避免 §112(f) 縮限
2. **Nonce word 必須在說明書中定義結構**——"module"、"mechanism" 等詞若無結構定義，*Williamson* 後極易被認定為 MPF
3. **軟體 MPF 必須揭露演算法**——說明書中必須有具體演算法描述，「執行功能的一般計算機」不夠
4. **揭露多種替代結構擴大等同物範圍**——讓說明書包含多種實施方式，可在訴訟中主張更廣的等同物
5. **同時撰寫兩個版本**：
   - MPF 版本（較窄但明確）："means for oscillating..."
   - 結構版本（較寬）："an oscillator configured to oscillate..."
6. **避免 single means claim**——必須有至少兩個元素的組合
7. **MPF 不適合主張新穎點**——若核心創新在 means clause，說明書揭露的有限結構會限縮你的保護範圍
