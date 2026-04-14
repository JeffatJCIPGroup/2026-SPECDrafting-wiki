---
type: concept
title: Method Claims（方法請求項）
aliases: [process claims, 方法請求項, 程序請求項, method steps]
tags: [method-claims, process-claims, claim-drafting, steps, gerund]
source_count: 1
---

# Method Claims（方法請求項）

## 定義

方法請求項（method claim）是專利請求項的一種，描述事物「**做什麼（WHAT it DOES）**」——以步驟或動作（acts/steps）的形式，說明對物件（article）、工件（workpiece）或化學物質（chemical substance）執行的行為序列。

35 U.S.C. §101 稱之為 "process"，並定義為 "process, art or method"。術語 "method" 與 "process" 可互換：化學案件多用 "process"，機械與電氣案件多用 "method"。

## 詳細說明

### 方法 vs. 裝置——根本區別

| 面向 | 方法請求項 | 裝置請求項 |
|------|-----------|-----------|
| 描述什麼 | 事物做什麼（DOES） | 事物是什麼（IS）|
| 元素是 | 步驟/動作（acts/steps） | 結構元件（structural elements）|
| 語言形式 | 動名詞（gerund："-ing"） | 名詞（noun） |
| 需要 | 實際執行（actual performance） | 存在即滿足 |
| 裝置能力 | 不等於方法執行 | 能力語言（"configured to"）即可 |

> **關鍵區別**：即使裝置具備執行某方法步驟的能力，若未實際執行，並不構成方法請求項的侵權。

### 方法請求項的步驟語言

**標準動名詞形式**（gerundial phrase）：

```
heating the mixture to a temperature of ...
separating the alcohol from the aqueous solution
connecting the unknown resistor between terminals A and D
reciprocating a guide point above the barrel
```

每個步驟本質上是一個**動名詞片語（gerundial phrase）**，以動名詞（"-ing" 形式）引入，描述對物件/工件的具體操作。

---

### Generic（廣義）vs. Specific（特定）步驟

方法步驟可廣可窄，視先前技術而定：

| 層次 | 範例 | 說明 |
|------|------|------|
| Generic（廣義/功能性） | `separating` | 只描述結果/功能 |
| Specific（特定/行為） | `distilling` | 描述具體行為，是 separating 的下位 |
| More Specific（更具體） | `distilling the aqueous solution at 78°C` | 進一步加入條件 |

**策略**：在先前技術允許的範圍內，使用**最廣的步驟語言**。若先前技術迫使縮小，再使用更具體的語言。

---

### Step-Plus-Function（§112(f)）

方法請求項中有類似 means-plus-function 的對應：**step-plus-function**（步驟加功能）。

- **觸發語言**："the step of separating"、"a step for performing [function]"
- **法律效果**：限縮至說明書中對應的具體「act」及等效物（不保護語言廣度）
- **現今建議**：直接使用具體的步驟語言（`separating` 或 `distilling to separate`），**避免**使用 "the step of" 前綴，以防被縮限至說明書特定揭露

> 見 [[means-plus-function]] 的類比：方法的 "step of" ≈ 裝置的 "means for"

---

### 前言（Preamble）格式

**標準格式**：
```
A method of [performing X on/with Y] which comprises:
    (a) [gerundial step];
    (b) [gerundial step]; and
    (c) [gerundial step].
```

**Transition 選項**（開放式，均可）：
- `which comprises:`
- `comprising the steps of:`（"the steps of" 可選，非必要）
- `including:`
- `having:`

---

### 與裝置請求項的類比

方法請求項和裝置請求項通常可以對應設計：

> **轉換規則**：在方法步驟前加 "means for" → 裝置元素；裝置元素（means for）刪去 "means for" → 方法步驟

```
方法：    rotating the barrel
裝置：    means for rotating the barrel
更明確：  a motor operably connected to the barrel for rotating the barrel
```

兩類請求項的保護範圍可以大致相當。建議**同時**提出裝置和方法請求項以最大化保護。

---

### 步驟順序（Order of Steps）

**預設規則**：未明確表述順序時，讀者假設步驟依外觀順序執行。

**法律測試**（*MFormation Techs. v. Research in Motion*）：
> 順序要求成立，當「請求項語言，就邏輯或語法而言，要求依書面順序執行」，或「說明書直接或隱含要求」該順序。

**三種情形的處理**：

| 情形 | 做法 |
|------|------|
| 步驟必須依序執行 | 明確表述：`first`、`then`、`subsequently`、`after step (a)` |
| 步驟順序嚴格 | 前言聲明：`comprising the following steps in the order named:` |
| 步驟同時/任意順序 | 勿表述順序；邏輯便利排列 |
| 步驟之間有引用關係 | 隱含順序（如 "on the zinc film" 隱含先執行鍍鋅步驟）|

> **實務原則**：**非必要時勿明確表述順序**——一旦表述，即成為請求項限制，對侵權判斷和有效性均有影響。

---

### 方法請求項中的裝置限制（Apparatus Limitations）

方法請求項中可以包含裝置元素，但**應盡量避免**，理由：

1. **過度限縮**：若方法可不依賴特定裝置執行，加入裝置限制縮小保護範圍
2. **可專利性基礎**：方法請求項的可專利性不能**單靠**裝置結構建立，必須立足於步驟本身

**例外**：
- **化學物質/組成物限制**：無問題，且常作為可專利性基礎（"exposing to reagent X ≠ exposing to reagent Y"）
- 若步驟本質上涉及特定裝置的操作，可包含裝置元素，但需揭示其與方法的「協作關係」

**推斷式引入（Inferential Introduction）**：
```
（正確）rotating a turntable on which the barrel is mounted
（錯誤）further comprising a turntable（只加裝置，未說明與方法的關係）
```
裝置元素作為步驟的賓語推斷引入，而非作為獨立元素存在。

**附屬方法請求項**：增加的限制應以方法步驟表述：
```
（差）A method as recited in claim 1, further comprising a turntable.
（好）A method as recited in claim 1, wherein the step of rotating includes 
      mounting the barrel on a turntable and rotating the turntable.
```

---

### 方法 + 裝置混合請求項的禁忌

> **同一請求項中同時包含裝置元素和方法步驟 → 不確定（§112(b)）**

*IPXL Holdings v. Amazon.com*（2005）確立：若請求項要求「使用者實際使用 input means」，侵權時點不明（製造者？使用者？），故不確定。

解法：**分開**撰寫裝置請求項和方法請求項。

---

### Tarczy-Hornoch 原則（方法 = 裝置固有功能）

*In re Tarczy-Hornoch*（CCPA 1968），MPEP §2173.05(v)：
> 方法請求項不可**僅因**其步驟是揭露裝置的固有功能而被拒絕。

- 若方法步驟均可手動執行，即與特定機器無關
- 目的：保持方法請求項的獨立保護價值

---

### 方法請求項的可專利性特殊情形

**使用新穎起始物的方法**（*In re Ochiai*, 1995）：
- 即使方法步驟本身常規，若使用新穎或非顯而易見的起始物，方法可能仍可獲專利
- 測試：「subject matter as a whole」是否對 PHOSITA 非顯而易見（高度事實特定）
- *Kuehl*：新沸石 + 舊裂解法 → 可專利（選用新沸石本身不顯而易見）
- *Durden*：新穎起始物但其使用方式本身顯而易見 → 不可專利
- **策略**：同時申請起始物（組成物）+ 使用方法 + 非顯而易見產品的保護

**廣泛化學/醫藥方法的 Enablement 風險**（*Idenix v. Gilead*）：
- 涵蓋數百萬化合物的請求項可能因 enablement（§112(a)）失效
- 廣度需與揭露的實驗性支持對應

**醫療/外科手術例外**（PL 104-208, 1996）：
- 醫療或外科手術程序可取得專利，但若未涉及專利機器或藥物，則**無法在法院強制執行**
- 解法：在請求項中引用專利裝置或專利藥物，以確保可執行性

---

### 化學方法的特殊規則

- **單步驟化學方法**：完全可接受（不需要組合步驟）
- **Markush 格式**：多種相關化學試劑可用 "selected from the group consisting of..." 列舉
- **新穎性可來自試劑，而非操作**：即使 "exposing"、"contacting" 本身歷史悠久，用於不同試劑即為不同步驟

---

### 電氣方法

- 遵循與機械方法相同的規則
- 步驟通常對應電路中的操作：`connecting`、`impressing`、`detecting`、`varying`
- "whereby" 子句適用：前述步驟完成後功能確定出現時使用

## 來源參照
- [[landis-ch04-method-process-claims]]：§4.1–§4.8 完整覆蓋，含 Wheatstone Bridge 範例、化學方法範例、步驟順序規則

## 相關概念
- [[apparatus-claims]]：方法 vs. 裝置的對比；混合請求項的 indefiniteness
- [[means-plus-function]]：step-plus-function 的裝置類比；§112(f)
- [[step-plus-function]]：方法請求項的 "step of" 語言（待建立）
- [[transition]]："comprises" / "comprising the steps of" 在方法請求項中的使用
- [[antecedent-basis]]：推斷式引入裝置的前提基礎規則
- [[indefiniteness]]：方法+裝置混合請求項（IPXL）的不確定性；§112(b)
- [[markush-group]]：化學方法中多種試劑的替代列舉格式
- [[whereby-wherein-clauses]]：whereby 子句在方法請求項中的使用

## 實務要點

1. **步驟用動名詞**——gerundial form（"-ing"）是方法步驟的標準形式；不使用被動語態或過去式
2. **能力 ≠ 執行**——方法侵權需要「實際執行步驟」，不僅裝置「有能力執行」
3. **廣義優先**——用最廣的步驟語言（`separating` 優於 `distilling`），除非先前技術需要縮小
4. **避免 "step of" 前綴**——直接寫 `separating`，不寫 "the step of separating"，以免被 §112(f) 限縮
5. **非必要時勿明確表述步驟順序**——順序限制一旦寫入即生效，應謹慎
6. **裝置限制能免則免**——推斷式引入（`rotating a turntable on which...`），且僅在與步驟有協作關係時加入
7. **化學物質限制無問題**——試劑/組成物可作為可專利性基礎
8. **不要混合裝置 + 方法**——同一請求項不可同時是裝置請求項和方法請求項（IPXL）
9. **同時申請裝置 + 方法**——用「加 'means for'」轉換，確保全面保護
10. **Ochiai 原則**——使用新穎起始物的方法可獲專利；應同時主張起始物、方法、產品三類請求項
