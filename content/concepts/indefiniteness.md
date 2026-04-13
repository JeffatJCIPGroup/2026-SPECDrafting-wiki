---
type: concept
title: Indefiniteness（不確定性）
aliases: [indefinite claim, 不確定請求項, 112b, definiteness]
tags: [indefiniteness, 112b, claim-drafting, USPTO, examination]
source_count: 1
---

# Indefiniteness（不確定性）

## 定義

Indefiniteness 是 35 U.S.C. §112(b) 規定的請求項要件：說明書必須以「特別指出且明確請求」（particularly point out and distinctly claim）發明人認定為其發明的標的。若請求項未達此標準，審查員可提出 §112(b) 核駁，法院可宣告請求項無效。

根據 *Nautilus, Inc. v. Biosig Instruments*（2014）確立的現行標準：請求項必須讓「一位 PHOSITA 在閱讀說明書後，能以合理確定性（reasonable certainty）理解發明的範圍」。

## 詳細說明

### 法律基礎：35 U.S.C. §112(b)

> The specification shall conclude with one or more claims **particularly pointing out and distinctly claiming** the subject matter which the inventor or a joint inventor regards as the invention.

**核心目的（public notice function）**：請求項必須讓公眾知道哪些行為構成侵權，以劃清保護範圍邊界。

### 法律標準的演進

| 時期 | 標準 | 來源 |
|------|------|------|
| 舊標準 | 請求項「不可理解」（not amenable to construction / insolubly ambiguous）才構成不確定 | 較寬鬆 |
| 現行標準（2014 後）| PHOSITA 閱讀說明書後無法以「合理確定性」理解範圍 | *Nautilus*（2014）|

**Nautilus 標準嚴格化的實際影響**：不需要到「完全無法理解」的程度，只要對 PHOSITA 有合理的不確定性即構成 §112(b) 缺陷。

### 審查 vs. 訴訟的不同標準

| 場景 | 請求項解釋方法 | 不確定性標準 |
|------|--------------|------------|
| USPTO 審查期間 | BRI（Broadest Reasonable Interpretation）| Nautilus（reasonable certainty）|
| 聯邦法院訴訟 | Phillips 標準（intrinsic evidence 優先） | Nautilus（reasonable certainty）|

> **重要**：不確定性的後果是整個請求項無效，不只是有問題的限制語言被排除。

### 三因素判斷情境

MPEP §2173.02 指出，不確定性應以三個情境因素判斷：
1. **說明書揭露**：說明書是否提供判斷準則
2. **先前技術背景**：術語在相關技術領域的既有含義
3. **PHOSITA 知識**：一位普通技術人員閱讀後的理解

---

### 主要失敗模式

#### 1. 缺乏前提基礎（§2173.05(e)）→ 見 [[antecedent-basis]]
- "said lever" 或 "the lever" 在請求項中無先前引用 → 不確定
- 若請求項中有兩個 lever 而 "said lever" 未明確指向哪一個 → 不確定
- **例外**：元素固有的組成部件（如球體的外表面）無需明確前提
- **例外**：若 PHOSITA 仍能合理確定範圍，則不構成不確定

#### 2. 程度語言（Terms of Degree）（§2173.05(b)）
- "about"、"substantially"、"essentially" 不自動不確定
- **要求**：說明書必須提供客觀標準或校準點
- **案例**：*Datamize LLC v. Plumtree Software*——"aesthetically pleasing" 純主觀，無客觀標準 → 不確定
- **案例**：*In re Marosi*——"essentially free of alkali metal" + 說明書指引 → 確定

#### 3. 功能性限制（§2173.05(g)）
- 功能語言本身不違法（§112(f) 明確授權 MPF 功能主張）
- **三因素審查**：
  1. 是否有清楚的範圍指示
  2. 是否設定邊界，還是只陳述問題或結果
  3. PHOSITA 是否能從文字了解結構/步驟
- **危險情形**：在新穎點使用功能語言而不揭露結構（*Halliburton Energy Servs. v. M-I LLC*）
- **解決方式**：量化指標、說明書公式+範例、PHOSITA 可辨識的指引、或修正為結構語言

#### 4. 例示性語言（§2173.05(d)）
- "for example"、"such as" 在請求項中可能使範圍不確定
- 請求項應自給自足，不用舉例說明邊界

#### 5. 數值範圍問題（§2173.05(c)）
- 同一請求項中過窄與過廣的範圍並存可能產生矛盾
- 開放式範圍（"at least X"）若有意義通常可接受

#### 6. 新術語（§2173.05(a)）
- 每個術語對 PHOSITA 必須是顯然可理解的
- Lexicographer 使用新術語必須在說明書中清楚定義

#### 7. 裝置 + 方法混合（§2173.05(p)）→ 見 [[apparatus-claims]]
- 同一請求項同時包含裝置元素和方法步驟 → 不確定（*IPXL Holdings v. Amazon.com*）
- 問題：侵權時點不明（製造者？使用者？）
- **區別**：若額外限制聚焦於系統「能力」而非「使用者動作」→ 可接受（*Mastermine Software*）

#### 8. 商標作為限制（§2173.05(u)）
- 商標是來源標識，不是商品描述
- 若用商標名稱描述材料或產品 → 範圍不確定

#### 9. Markush 群組用 "comprising"（§2173.05(h)）→ 見 [[markush-group]]
- Markush 群組必須使用 "selected from the group **consisting of**"（封閉群）
- 用 "comprising" 或 "consisting essentially of" 定義替代列表 → 不確定（*In re Kiely*）

#### 10. 否定限制無揭露基礎（§2173.05(i)）
- 否定限制本身合法，但必須有說明書基礎
- 若說明書未揭露被排除的替代方案 → 違反 §112(a) 書面描述要求

#### 11. Omnibus Claim（§2173.05(r)）
- "A device substantially as shown and described" → 無條件不確定

---

### 廣度 ≠ 不確定性（§2173.04）

> "Breadth is not indefiniteness." ——*In re Gardner*（1970）

請求項範圍廣不構成 §112(b) 不確定性核駁的理由。廣度是申請策略，不是缺陷。
但廣度可能引發 §112(a)（written description / enablement）問題。

---

### 合法的請求項形式（常被誤認為不確定）

| 形式 | 合法？ | 理由 |
|------|--------|------|
| 廣泛請求項 | ✓ | 廣度≠不確定 |
| 否定限制 | ✓（需說明書基礎） | 設定明確邊界 |
| Markush 群組 | ✓（用 consisting of） | 封閉群 |
| "optionally" | ✓（無歧義情境） | 明確涵蓋哪些替代 |
| Product-by-process | ✓ | 以製程定義產品可接受 |
| 功能語言 | ✓（含結構基礎） | §112(f) 授權；需說明書支持 |
| "effective amount" | ✓（說明書有指引） | 提供 PHOSITA 可操作標準 |
| 附屬項引用獨立項 | ✓ | 不因引用就不確定 |
| 化學結構式（部分） | ✓ | 不因缺乏光譜數據而不確定 |

---

### Compact Prosecution 要求（§2173.06）

USPTO 要求審查員在第一次 Office Action 中全面提出所有核駁：
- 當某詞語不確定時，**同時**提出 §112(b) + §102/§103 核駁
- 在先前技術對比核駁中說明如何解釋不確定語言
- 避免片段式審查（piecemeal examination）

---

### 不確定性的解決方式

1. **說明書增補定義**：為模糊術語提供明確操作標準
2. **量化指標**：用數值限制替代程度語言（"less than 5%" 優於 "small amount"）
3. **說明書範例**：同時提供符合和不符合的範例
4. **修正請求項**：
   - 功能語言 → 結構語言
   - 程度語言 → 量化指標
   - 混合請求項 → 分開裝置/方法請求項
   - 商標名稱 → 通用術語

## 來源參照
- [[mpep-2173-indefiniteness]]：§2173–§2173.06 完整涵蓋，含 22 種具體失敗模式及判例分析

## 相關概念
- [[antecedent-basis]]：缺乏前提基礎（§2173.05(e)）
- [[markush-group]]：Markush 群組的 "consisting of" 要求（§2173.05(h)）
- [[means-plus-function]]：功能性限制與 §112(f) 的交叉（§2173.05(g)）
- [[apparatus-claims]]：裝置+方法混合請求項（§2173.05(p)）
- [[claim-construction]]：BRI vs. Phillips 標準在不確定性判斷中的角色
- [[statute-35usc112]]：§112(b) 法律依據
- [[written-description]]：否定限制需要的揭露基礎（§112(a)）
- [[functional-language]]：功能性限制的審查標準

## 實務要點

1. **「廣」不是問題，「模糊」才是**——請求項可以很廣，但範圍邊界必須對 PHOSITA 清楚
2. **說明書是不確定性的急救包**——程度語言、功能語言的確定性靠說明書中的客觀標準、範例和定義支撐
3. **用 "configured to" 而非 "adapted to" 或純功能語言**——提供結構性脈絡後的功能語言比純功能語言更安全
4. **分開裝置和方法請求項**——同一請求項混入方法步驟 → §112(b) + 侵權困難
5. **Markush 一定要 "consisting of"**——用 "comprising" 定義替代列表是常見的致命錯誤
6. **商標名稱不能作為材料限制**——用通用術語替代
7. **否定限制需要說明書正面基礎**——被排除的替代方案必須在說明書中有所描述
8. **審查期間 BRI 更廣**——申請人在 Prosecution 中應注意 BRI 下的解釋比日後訴訟更寬，有助於爭論不確定性核駁
