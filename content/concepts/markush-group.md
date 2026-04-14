---
type: concept
title: Markush Group（Markush 群組）
aliases: [Markush 群組, Markush claim]
tags: [claim-type, claim-drafting, chemical]
source_count: 3
---

# Markush Group（Markush 群組）

## 定義

Markush group 是一種請求項撰寫方式，以「selected from the group consisting of A, B, and C」的固定格式列舉一組替代方案。源自 *Ex parte Markush* 案，主要用於化學與材料領域。

## 詳細說明

### 形式（§6.4.4.1）

標準格式：
```
...a material selected from the group consisting of A, B, and C.
```

替代表述（一般的 alternative language 如 "A or B"）通常不被允許，除非替代方案之間有明確的共同特性。Markush group 提供了一種被接受的替代表述方式。

### 替代方案之間的關係（§6.4.4.2）

群組中的成員必須具有共同的特性或功能，形成「人為的群組（artificial group）」。

Faber（Landis §6.2）提出有效 Markush 群組的**四要件**：
1. 替代方案共享**相同性質或功能**（same property or function）
2. 均屬於**公認的化學類別**（recognized chemical class）
3. 均在說明書中揭露為**安全替代方案**（safe substitutes for each other）
4. **功能上可互換**（functionally interchangeable in the invention）

### 主要用途（§6.4.4.3）

- 定義化學成分的替代物
- 定義材料選擇
- 列舉具體的化合物
- 也可用於**機械請求項和製程請求項**（不限於化學）

### Sheldon 的建議（§6.4.4.4）

Markush group 應**謹慎使用（with extreme caution）**，原因：
- 可能導致 restriction requirement（限制要求）
- 群組成員過多會增加審查難度
- 封閉式語言（"consisting of"）限制了範圍的靈活性

### MPEP §2173.05(h) 的重要補充：必須使用封閉群語言

**關鍵規則**：Markush 群組**必須**使用 "selected from the group **consisting of**"（封閉群），不可使用：
- "selected from the group **comprising**" → **不確定**（*In re Kiely*, 2022）
- "selected from the group **consisting essentially of**" → **不確定**

**理由**：Markush grouping 在定義上是封閉群組，若使用開放式語言（comprising），則無法確定還有哪些替代方案涵蓋在內，造成範圍不明。

**混合物/組合的例外**：若請求項需涵蓋成員的組合（mixture），可加入修飾語：
- "selected from **at least one member** of the group consisting of A, B, and C"
- "...selected from the group consisting of A, B, C, **or mixtures thereof**"

### 關鍵例外：請求項層級 comprising vs. Markush 層級 consisting of（*Amgen v. Amneal*, 2020）

**核心規則**：Markush 群組內部的 "consisting of" **不能覆蓋**請求項層級過渡語的開放性。

- **情境 A**（請求項層級 = comprising）：
  ```
  A tablet comprising:
    a binder selected from the group consisting of X, Y, and Z.
  ```
  → **開放式請求項**：整體請求項仍是開放的，不排除其他黏合劑（non-X/Y/Z binders）的存在。"consisting of" 僅在 Markush 群組層級封閉，不影響請求項整體的 comprising 開放性。

- **情境 B**（請求項層級 = consisting of）：
  ```
  A tablet consisting of:
    a binder selected from the group consisting of X, Y, and Z.
  ```
  → **封閉式請求項**：整體請求項封閉，排除所有未列舉成分（包括其他黏合劑）。

**實務意涵**：若希望整體請求項是開放式（允許額外成分），使用 "comprising" 作為請求項過渡語即可——Markush 群組內部的 "consisting of" 不會使整體請求項變成封閉式。

### 其他 MPEP §2173.05(h) 規則

- **廣度不等於不確定**：Markush 群組成員多、範圍廣不因此不確定（*In re Gardner*）
  - 例外：若化合物種類過多至 PHOSITA 無法確定範圍，可能構成不確定
- **雙重包含（Double Inclusion）**不自動不確定：同一化合物被多個成員涵蓋沒問題
  - 例：群組含「halogen」和「chloro」——chloro 屬於 halogen，但不構成不確定（*Eli Lilly v. Teva Parenteral Meds.*）
- **"optionally"**：「containing A, B, and optionally C」可接受——無歧義的替代表述（*Ex parte Cordova*）
- **縮減範圍（Diminishing Scope Markush）**：不同請求項使用不同範圍的 Markush 群不自動不確定

### 格式的靈活性

MPEP 允許以不同格式表述 Markush 替代方案：
- "selected from the group consisting of A, B, and C"
- "wherein the material is A, B, or C"（等效）
治療原則不依格式而定，而依實質是否為封閉群。

## 來源參照
- [[sheldon-ch6-claim-drafting]]：§6.4.4 完整說明 Markush group 的形式、要求與建議
- [[mpep-2173-indefiniteness]]：§2173.05(h) 確認 Markush 必須用 "consisting of"；說明 "comprising" 版本不確定；解釋 "optionally" 的可接受性
- [[landis-ch06-composition-of-matter]]：§6.2 說明 Markush 四要件、*Amgen v. Amneal*（2020）開放式例外、Markush 在機械/製程請求項的擴展應用

## 相關概念
- [[transition]]：Markush group 使用封閉式過渡語 "consisting of"；對比 comprising（開放）vs. consisting of（封閉）
- [[independent-claim]]：Markush group 通常出現在獨立項的 body 中
- [[indefiniteness]]：Markush 群組的 §112(b) 不確定性風險

## 實務要點

1. **Markush 群組內部必須用 "consisting of"**——不可用 "comprising" 或 "consisting essentially of"，否則直接導致不確定性核駁（§2173.05(h)）
2. **請求項層級過渡語決定整體開放/封閉**——Markush 內部的 "consisting of" 不影響請求項整體的開放性（*Amgen v. Amneal*, 2020）
3. **四要件必須滿足**：共同性質、公認類別、安全替代、功能可互換
4. 若需涵蓋混合物，加入 "or mixtures thereof" 或 "at least one member selected from"
5. 注意封閉式語言的範圍限制效果——成員外的替代方案將不受保護
6. 考慮是否有更寬泛的上位概念可以替代具體列舉
7. 雙重包含（generic + specific 都在同一群組）可接受，無需特別處理
8. **Markush 不限於化學**——機械元件的材料選擇、製程步驟的替代方案均可使用
