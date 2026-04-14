---
type: concept
title: Generic and Species Claims（上位概念與下位概念請求項）
aliases: [上位概念請求項, 下位概念請求項, genus claims, species claims, functional genus, 功能性上位概念]
tags: [claim-type, claim-drafting, chemical, biotech, generic-species, written-description, enablement]
source_count: 1
---

# Generic and Species Claims（上位概念與下位概念請求項）

## 定義

- **上位概念請求項（generic claim / genus claim）**：涵蓋一整類（genus）發明的廣義請求項，所有符合上位概念定義的具體實施方式均落入其範圍
- **下位概念請求項（species claim）**：針對上位概念中某一具體個例（species）的窄義請求項
- **功能性上位概念（functional genus）**：以功能或結果（而非結構）界定上位概念的廣義請求項——為當前 §112(a) 訴訟的高風險形式

---

## 詳細說明

### 基本關係

```
上位概念（Genus）：「一種能抑制 PCSK9 的抗體」
  ↓ 包含
下位概念（Species）：「一種抗體，其重鏈 CDR3 序列為 SEQ ID NO: 5，
                        輕鏈 CDR3 序列為 SEQ ID NO: 6」
```

上位概念越廣，受到的 §112(a) 審查越嚴格；下位概念越窄，有效性越高但保護範圍越小。

---

### 上位概念請求項的策略優勢

1. **先佔廣泛保護**：一個上位概念請求項可以涵蓋未來競爭者開發的所有功能等效方案
2. **預防設計規避**：若只有物種請求項，競爭者可通過微小修改規避
3. **生技/製藥核心工具**：抗體、CAR-T 細胞、CRISPR 系統等通常需要功能性上位概念才能有意義地保護

---

### §112(a) 書面描述要求的危機

**功能性上位概念請求項**（以「能做 X」而非「結構為 Y」界定）面臨嚴峻的 §112(a) 書面描述挑戰：

#### 核心判例脈絡

| 案例 | 裁判 | 核心規則 |
|------|------|---------|
| **Ariad v. Eli Lilly**（CAFC en banc, 2010） | 上位概念無效 | §112(a) 書面描述要求獨立於可實施性；申請人必須用說明書揭示對整個上位概念的「擁有（possession）」 |
| **Synthes v. Spinal Kinetics**（CAFC, 2012） | 廣義功能描述不足 | 廣泛的功能性描述不能替代結構揭露；「能達成 X 功能的元件」≠ 充分書面描述 |
| **Juno Therapeutics v. Kymriah**（CAFC, 2021） | 功能性 CAR-T 請求項無效 | 以抗原結合功能定義的 scFv 上位概念，因說明書僅揭露極少數物種，無效；揭露必須代表整個上位概念 |
| **Amgen v. Sanofi**（最高法院, 2023） | 功能性抗體請求項無效 | 「申請人不能從勞動果實中提取超出其貢獻的回報」；功能性定義的上位概念必須有足以讓 POSA 製造並使用**整個請求範圍**的說明書揭露 |

#### 核心標準（Amgen v. Sanofi 後）

USPTO 和法院評估功能性上位概念的 §112(a) 充分性，考慮以下因素：
1. **揭露廣度 vs. 說明書描述**：請求範圍多廣？說明書提供了多少具體實施例（working examples）？
2. **可預測性（predictability）**：技術領域是否成熟？POSA 能否從有限揭露推斷整個上位概念？
3. **共同結構或功能**：上位概念成員是否共享足夠的共同特性？
4. **負擔（undue experimentation）**：讓 POSA 填補空白需要多大的努力？

---

### 應對 §112(a) 危機的策略

#### 1. 充分的物種揭露
- 在說明書中提供**代表整個上位概念的多樣化物種實施例**
- 分布在上位概念的各個「角落（corners）」
- 包含化學/結構多樣性的範例

#### 2. 結構-功能相關性揭露
- 揭露哪些結構特徵**決定**所需功能
- 提供「構效關係（structure-activity relationship, SAR）」資料

#### 3. Markush 群組替代功能性表述
- 若能以 Markush 形式列舉有限的具體替代方案，比純功能性表述更安全
- 見 [[markush-group]]

#### 4. Jepson 式請求項的 §112(a) 緩解作用
- 將已知技術放入 Jepson 前言，改進特徵放入主體
- 主體部分的範圍更窄，§112(a) 要求相對容易滿足
- 適用場景：在已知 CAR 結構上加入新的功能模組
- 見 [[jepson-claim]]

#### 5. 窄義保護策略
- 放棄廣泛的功能性上位概念，改用具體的物種請求項或有限 Markush 群組
- 犧牲保護廣度換取有效性確定性

---

### 上位/下位概念的侷限制度（Restriction Requirement）

當申請案同時包含上位概念請求項和物種請求項時：
- USPTO 可能要求**限制要求（restriction requirement）**
- 申請人需**選擇（elect）**一組請求項繼續審查
- **策略應對**：
  - 未選擇的物種可在分割案（divisional application）中繼續主張
  - 選擇時考慮哪個物種/上位概念商業價值最高
  - 保留選擇記錄，利用 species 的 Markush 群組充分覆蓋

---

### 上位概念請求項的格式範例

```
1. An antibody that specifically binds to PCSK9 and inhibits
   LDL receptor binding, wherein the antibody reduces LDL
   cholesterol levels when administered to a patient in need thereof.
   [功能性上位概念——高 §112(a) 風險，需要廣泛說明書揭露]

2. An antibody comprising:
   a heavy chain variable region comprising CDR1 having the
   sequence set forth in SEQ ID NO: 1, CDR2 having the sequence
   set forth in SEQ ID NO: 2, and CDR3 having the sequence set
   forth in SEQ ID NO: 3; and
   a light chain variable region comprising CDR1 having the
   sequence set forth in SEQ ID NO: 4, CDR2 having the sequence
   set forth in SEQ ID NO: 5, and CDR3 having the sequence set
   forth in SEQ ID NO: 6.
   [物種請求項——結構性定義，§112(a) 風險低]
```

---

## 來源參照
- [[landis-ch06-composition-of-matter]]：§6.9 完整說明上位/下位概念策略與 §112(a) 危機

## 相關概念
- [[markush-group]]：Markush 群組是上位概念的一種表述方式
- [[jepson-claim]]：Jepson 形式可緩解功能性上位概念的 §112(a) 風險
- [[written-description]]：§112(a) 書面描述要求——上位概念請求項的主要障礙
- [[enablement]]：§112(a) 可實施性要求——與書面描述並列的另一挑戰
- [[composition-of-matter-claims]]：上位/下位概念策略在化學/生技組合物中的應用
- [[independent-claim]]：上位概念請求項通常是最廣的獨立項
- [[dependent-claim]]：物種請求項常作為附屬項，逐步窄化保護

## 實務要點

1. **Amgen v. Sanofi（2023）是新基準**——功能性上位概念請求項在說明書不足時會被無效，不要奢望廣泛的功能性定義能通過
2. **說明書決定上位概念的天花板**——申請之前就應評估說明書能支持多廣的上位概念
3. **多樣化物種揭露是核心保險**——在說明書中提供覆蓋上位概念「四個角落」的代表性實施例
4. **SAR 資料有說服力**——構效關係揭露能幫助建立「整個上位概念確實可預測」的論點
5. **限制要求需要提前規劃**——選擇哪個物種/上位概念應在申請前已有策略考量
6. **Jepson 形式是生技的新工具**——改進型生技發明（對已知平台技術的新功能模組）可考慮 Jepson 以降低 §112(a) 風險
7. **物種請求項是基礎防線**——即使廣泛上位概念最終無效，具體物種請求項仍能保護核心產品
