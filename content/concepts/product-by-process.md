---
type: concept
title: Product-by-Process Claims（製程界定產品請求項）
aliases: [PBP claim, 製程界定產品, product by process]
tags: [claim-type, product-by-process, patentability, infringement, claim-drafting]
source_count: 1
---

# Product-by-Process Claims（製程界定產品請求項）

## 定義

Product-by-Process（PBP）請求項是以製造該產品的**製程**（process）來定義產品或其元素的請求項，而非以結構特性或化學特性描述。當產品的結構難以用語言描述，或產品的新穎性無法以傳統結構語言有效區別時，PBP 請求項提供了替代的保護途徑。

## 詳細說明

### PBP 請求項的雙軌規則

PBP 請求項在**可專利性（patentability）**和**侵權（infringement）**上適用不同規則：

| 面向 | 規則 | 說明 |
|------|------|------|
| **可專利性** | 取決於最終產品本身 | 製程新穎不等於產品可專利 |
| **侵權** | 製程術語為限制條件 | 被告必須以指定製程製造 |

> **核心原則**：「PBP 請求項的可專利性由最終產品本身決定，而非製造它的製程。」（MPEP §2113；*In re Thorpe*）

---

### 可專利性規則

**基本要求**：PBP 請求項所主張的產品本身必須滿足 §102（新穎性）和 §103（非顯而易見性）。

**關鍵判例**：
- ***SmithKline Beecham v. Apotex*（2006）**：先前技術中已揭露的產品（Paxil 抗憂鬱藥）使後來以特定製程定義的 PBP 請求項無效——即使製程是新的
- *In re Pilkington* / *In re Dilnot*：「在已知產品的請求項中加入方法步驟，無法賦予該舊產品可專利性」
- 製程的新穎性是方法請求項的問題，不是 PBP 請求項的基礎

**「新製程 + 舊產品」= 不可專利的產品**：
```
碳阻電阻（已知於先前技術）
    × 以新方法（氫碳氣分解）沉積碳膜
    = 電阻 PBP 請求項不可專利
    ≠ 製造方法請求項不可專利（方法可能仍可獲專利）
```

---

### 侵權規則

***Atlantic Thermoplastics Co. v. Faytex Corp.***：確立 PBP 請求項中的製程術語在侵權判斷中作為**限制條件**。

- 被控侵權的產品必須**以指定製程製造**，才構成 PBP 請求項的侵權
- 若被告使用不同製程製造相同產品，不侵害 PBP 請求項（但可能侵害純產品請求項）
- 這是 PBP 請求項與「純產品請求項（pure product claim）」的關鍵區別

---

### 「結構性詞語」 vs.「純製程詞語」

某些表面上看起來是製程的詞語，法院可能解釋為**結構性限制**（不適用 PBP 規則）：

| 詞語 | 性質 | 說明 |
|------|------|------|
| "interbonded by interfusion" | 結構性 | 描述粒子之間的連結狀態（*In re Garnero*） |
| "etched" | 結構性 | 描述表面的結構狀態 |
| "welded" | 結構性 | 描述連接的結構狀態 |
| "chemically engraved" | 結構性 | 更描述產品結構而非製程 |
| "deposited by decomposition of hydrocarbon gas" | 製程性 | 典型 PBP 語言 |

若一個詞語**既能描述結構又能描述製程**，法院傾向認定其具有結構性，不視為純粹的 PBP 限制。

---

### 嵌套 PBP（Nested PBP in Method Claim）

當 PBP 限制被嵌套在方法請求項中時（*Biogen MA v. EMD Serono*, 2020；*Purdue Pharma v. Epic Pharma*, 2016；*Monsanto v. Syngenta Seeds*）：

- 嵌套不改變 PBP 限制的可專利性評估規則（仍看最終產品）
- 嵌套的製程步驟**不用於**評估方法的可專利性
- 嵌套的製程步驟**用於**侵權評估（被控侵權方必須執行指定步驟）

---

### 標準格式

**純 PBP 格式**：
```
A [product name] which comprises:
  (a) [element A];
  (b) [element B] deposited [by process step]; and
  (c) [element C].
```

**Cross-class Dependent 格式**：
```
Claim 5B.  A method of manufacturing sodium hydroxide, comprising: ...

Claim 5C.  Sodium hydroxide produced according to the process of claim 5B.
```
（PBP 請求項依附方法請求項，跨越法定類別——合法且常用）

**方法中嵌套 PBP 限制**：
```
A method of treating [condition] comprising:
  administering [a compound made by the process of claim X] to a patient.
```

---

### 撰寫策略

1. **每一個生產/改變物品的方法請求項都應考慮 PBP 請求項**——兩種保護途徑互補
2. **可以同時有純產品請求項和 PBP 請求項**——分別保護不同層次（generic + species）
3. **PBP 請求項範圍較窄**：比純產品請求項更窄，因為多了製程限制
4. **若能以結構描述，優先用純產品請求項**：保護範圍更廣（覆蓋所有製造方式）
5. **PBP 的必要性**：當產品結構難以描述，或新穎性只能透過製程展現時使用
6. **考慮侵權可執行性**：製程限制使侵權調查更困難（需確認製造方式）

---

### 數量與範圍

- 現行法律下，PBP 請求項數量**無限制**
- 可有多個不同範圍（generic + species）的 PBP 請求項
- 可同時提交純產品請求項和 PBP 請求項

## 來源參照
- [[landis-ch05-other-types-of-claims]]：§5.2 完整分析 PBP 的可專利性、侵權規則、嵌套 PBP、歷史演變

## 相關概念
- [[method-claims]]：每個產生物品的方法請求項都應考慮對應的 PBP 請求項
- [[apparatus-claims]]：純產品請求項（pure product claim）不限定製造方式
- [[indefiniteness]]：§2173.05(p) 裝置+方法混合請求項；PBP 的確定性問題
- [[statutory-classes]]：PBP 請求項跨越 §101 的製造物（manufacture）類別

## 實務要點

1. **PBP 可專利性看產品，不看製程**——答辯時強調最終產品的結構差異，而非製程的新穎性
2. **侵權要看製程**——選擇 PBP 或純產品請求項時要評估侵權的可偵查性
3. **並行申請策略**：method claim（保護製程）+ pure product claim（保護產品，不限製造方式）+ PBP claim（保護特定製程製造的特定產品）
4. **「etched」、「welded」等詞可能被解釋為結構性限制**——不適用 PBP 的可專利性限制規則
5. **嵌套 PBP 不影響方法的可專利性評估**，但影響侵權判斷
