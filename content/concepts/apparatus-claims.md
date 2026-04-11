---
type: concept
title: Apparatus Claims（裝置請求項）
aliases: [裝置請求項, machine claim, 機器請求項, product claim]
tags: [apparatus-claim, claim-structure, structural-connection, functional-language]
source_count: 1
---

# Apparatus Claims（裝置請求項）

## 定義

Apparatus claim（裝置請求項）是針對一種機器、裝置或產品的請求項，屬於 35 U.S.C. §101 的「machine」或「manufacture」法定類別。其核心原則是：**請求項描述裝置「是什麼」（structure），而非「做什麼」（behavior）**。

## 詳細說明

### 核心原則：結構 vs. 行為

| 寫法 | 合法？ | 說明 |
|------|--------|------|
| "an arm **capable of** rotating" | ✓ | 描述能力（structural capability） |
| "an arm **configured to** rotate clockwise" | ✓ | 描述結構性設計意圖 |
| "an arm **that rotates** when..." | ✗ | 描述行為（method step） |
| "wherein a user **rotates** the arm" | ✗ | 混合裝置/方法 → §112 不確定性 |

> 裝置請求項可描述裝置元素的**能力**或**用途**（"for" + 名詞/動名詞），但不應描述使用者動作或執行過程中的步驟。

### 請求項結構

標準裝置請求項結構：

```
[Preamble] [Transition], [Body]

1. Apparatus for shaking articles, which comprises:
   (a) a container for the articles;
   (b) a base;
   (c) a plurality of legs, each of which is connected pivotally 
       at one end to the container and at the other end to the base 
       to support the container for oscillating movement; and
   (d) means for oscillating the container on the legs to shake the articles.
```

### 元素引入規則

1. **每個元素必須作為其子句的主語（subject）**，不可「推定引入」（inferential claiming）
   - ❌ "a motor connected to a shaft which drives a gear" → shaft 被推定引入
   - ✓ "a motor; a shaft connected to the motor; a gear driven by the shaft"

2. **不定冠詞引入，定冠詞再引用**
   - 首次：用 "a" 或 "an"
   - 後續：用 "the" 或 "said"（見 [[antecedent-basis]]）

3. **Workpiece（被加工物）推定引入**
   - 被加工物不列為請求項元素
   - 在元素描述中以推定方式提及："a crusher for acting on **a piece of citrus fruit**"
   - 後續引用用 "the"（而非 "said"）：「the citrus fruit」

### 元素命名策略

- **廣義優先**：「fastening element」> 「screw」——越廣泛，越難迴避
- **避免過窄**：「slidably mounted」可能排除等同的「pivotally mounted」
- **功能名稱**：無具體名稱時用「means for oscillating」或「oscillator」+「configured to oscillate」
- **first/second 為中性序號**：不隱含空間位置、順序或大小，僅區分同類元素
- **全文一致**：同一請求項鏈中，同一元素的名詞不可更改（形容詞可省略）

### 結構連接（Structural Connection）

所有元素必須相互連接，否則構成 **aggregation（零件目錄）**核駁：

```
正確：... a container; a base; a plurality of legs, each connected 
          pivotally at one end to the container and at the other end 
          to the base; ...

❌ 聚合：... a container, a base, a plurality of legs, and means for 
           oscillating the container. [元素間無連接描述]
```

**連接詞廣義優先**：
- 優先：「connected to」「mounted on」「engaged with」
- 避免：「fixed to」「bolted to」「welded to」（太窄）

**Means clause 自帶連接**：「means for oscillating the container」隱含 means 必須接觸或連接 container。

### 元素順序

兩種常用順序：
1. **功能性順序**：從最先接觸 workpiece 的元素開始，沿功能流程進行
2. **結構性順序**：從基礎（base/power source）開始，沿結構線路進行

### 功能語言的正確使用

**接受度由高到低**：
1. `for + [名詞/動名詞]`："a container **for** the articles" ← 最安全
2. `configured to`："a motor **configured to** oscillate the container"
3. `capable of`："an arm **capable of** rotating 360°"
4. `adapted to`："a holder **adapted to** receive the workpiece"（部分審查員有異議）
5. `designed to`：可接受，但較少使用

**避免**：直接描述方法步驟（"the motor rotates the container"）

### 過度功能主張的風險

**三大核駁理由**：
1. 涵蓋不可運作的物種（covers inoperative embodiments）
2. 說明書支持不足（lacks disclosure support）
3. 範圍如 *O'Reilly v. Morse*——僅主張結果而非手段

**安全做法**：先描述結構，再加功能陳述說明結果。

### 裝置請求項 vs. 方法請求項

同一發明通常應分開撰寫裝置與方法請求項，避免混合：
- 裝置請求項：涵蓋製造商（製造並銷售裝置）
- 方法請求項：涵蓋使用者（執行方法步驟）
- 混合請求項（*IPXL Holdings*）：侵權時點不明 → §112 不確定性核駁

## 來源參照
- [[landis-ch03-apparatus-machine-claims]]：本章核心內容，含 Shaker 範例、aggregation 規則、naming 策略、functional language、MPF

## 相關概念
- [[means-plus-function]]：裝置請求項中功能語言的最極端形式 §112(f)
- [[preamble]]：裝置請求項 preamble 的型態（功能性描述 vs. 通用名稱）
- [[transition]]：comprising 在裝置請求項中的應用
- [[antecedent-basis]]：元素命名的 a/the/said 規則
- [[statutory-classes]]：apparatus claim 屬於 machine/manufacture 類別
- [[claim-construction]]：元素命名如何影響請求項解釋範圍

## 實務要點

1. **撰寫前先畫「棒棒圖」（stick picture）**：把請求項畫成示意圖，確認所有元素都有連接橋樑，沒有「懸空」的元素
2. **元素 = 島嶼，連接 = 橋樑**：每個島嶼都必須透過橋樑（結構或功能連接）與其他島嶼相連
3. **Workpiece 不入請求項元素**：讓 workpiece 成為請求項元素，等於把使用者（infringer）拉出製造商範圍
4. **功能語言加結構背書**：先寫結構，再加 "configured to [function]"——讓功能語言附著在已揭露的結構上
5. **每個元素的四個問題**：(1) 叫什麼名字？(2) 有哪些組成部件？(3) 如何與其他元素連接？(4) 做什麼功能？
6. **勿讓 means 成為新穎點**：若發明的新穎性在 means clause，說明書揭露的對應結構會限縮保護範圍
