---
type: concept
title: Continuing Applications（接續申請案）
aliases: [divisional, continuation, CIP, continuation-in-part, 分割申請, 接續申請, 部分接續申請]
tags: [continuing-applications, divisional, continuation, CIP, provisional, patent-prosecution]
source_count: 1
---

# Continuing Applications（接續申請案）

## 定義

接續申請案（continuing applications）是一組申請案策略工具，允許申請人在原始申請案（parent application）的揭露基礎上，延伸或補充所主張的保護範圍。主要類型包括：Divisional（分割）、Continuation（接續）、Continuation-in-Part（CIP，部分接續），以及相關的 Provisional（臨時）申請案。

## 詳細說明

---

### 三種接續申請案的比較

| 類型 | 觸發原因 | 說明書/圖式 | 新事項 | 有效申請日 | Double Patenting |
|------|---------|------------|-------|-----------|-----------------|
| **Divisional** | 限制要求（restriction requirement） | 與母案相同 | 無 | 母案日（全部請求項） | 不可被母案核駁 |
| **Continuation** | 補充請求項策略 | 與母案相同 | 無 | 母案日（全部請求項） | 可能被核駁 |
| **CIP** | 補充新技術/新發現 | 母案 + 新揭露 | **有** | 逐項決定（見下） | 可能被核駁 |

---

### §5.6.1 Divisional Applications（分割申請案）

**觸發機制**：審查員發出**限制要求（restriction requirement）**——認定申請案包含兩個或多個「獨立且不同（independent and distinct）」的發明，要求申請人選擇其一進行審查。

**核心規則**：
- 含有與母案**相同的說明書與圖式**，但只包含被限制排除的請求項（nonelected claims）
- 有效申請日 = **母案申請日**（對所有請求項）
- 審查員**不可**以 double patenting（雙重專利）核駁分割案的請求項（與母案相比）
- 若分割案中的請求項來自多個不限制組別或多個物種，可能再次面臨限制要求

**物種選擇（Species Election）**：
- 審查員也可要求申請人選擇特定物種（species）進行審查
- 若涵蓋所有物種的 generic claim 被核准，則各物種的具體請求項可在分割案中提出

**實務流程**：
```
母案 → 審查員發出 restriction requirement
申請人選擇 Group A 進行審查（母案繼續）
申請人同時或之後提出 Divisional 申請案，包含 Group B 的請求項
```

---

### §5.6.2 Continuation Applications（接續申請案）

**定義**：與母案使用相同揭露（說明書+圖式），但包含母案中**未曾提出**的新請求項。

**與 Divisional 的區別**：
- Divisional = 被動（審查員要求限制）；Continuation = 主動（申請人策略選擇）
- Divisional 的請求項來自被限制排除的組別；Continuation 的請求項可以是任何新的請求項

**雙重專利（Double Patenting）**：
- Continuation 的請求項**可能**因與母案請求項 double patenting 而被核駁
- 解法：提交 Terminal Disclaimer（終止聲明），使兩件專利的期限掛鉤

**範圍限制**：
- Continuation 請求項範圍應與母案已審查請求項有**實質差異**，以避免 double patenting 核駁

**常見用途**：
- 補充不同範圍（更廣或更窄）的請求項
- 針對已知的競爭產品撰寫「量身定做」的請求項
- 在競爭對手公開其技術後，調整請求項範圍以涵蓋其實施方式

---

### §5.6.3 Continuation-in-Part（CIP，部分接續申請案）

**定義**：在母案揭露之外，加入**新事項（new matter）**的申請案。新事項是指母案說明書中未揭露的技術內容。

**有效申請日的逐項計算（Critical Rule）**：

```
每個請求項的有效申請日分別計算：
  ┌ 若請求項的每個元素均由母案說明書支持 → 有效日 = 母案申請日
  └ 若請求項依賴 CIP 中的新事項          → 有效日 = CIP 申請日
```

> 這是 CIP 最複雜、最重要的特性——同一 CIP 申請案中，不同請求項可能有不同的有效申請日。

**後果**：
- 有效日越晚，面臨的先前技術（prior art）越多（因為中間時期的公開文獻均可成為先前技術）
- 特別是 AIA（America Invents Act）後的「先申請制（first-to-file）」體系下，有效申請日尤為重要

**Double Patenting**：
- CIP 的請求項**可能**因與母案請求項 double patenting 而被核駁
- 與 Divisional 不同，Divisional 受限制要求保護，不可被核駁

**何時使用 CIP**：
- 發明人改進了原始發明，有新的技術揭露需要加入
- 希望保留原始申請日（對能由原始揭露支持的請求項）
- 同時需要主張新發明（依賴新事項的請求項取得 CIP 申請日）

---

### §5.7 Provisional Applications（臨時申請案）

**法律要求**：只需書面描述（written description）、必要圖式、發明人姓名；**不需請求項**。

**重要限制**：
- 必須在 1 年內提交非臨時申請（nonprovisional/utility application）
- 臨時申請案**不被審查**，不受 §102、§103、§112 的形式要求

**建議仍在臨時申請中加入請求項**：

| 理由 | 說明 |
|------|------|
| **確認揭露完整性** | 撰寫請求項可確認說明書為每個元素提供前提基礎支持（antecedent basis） |
| **加速轉換** | 含請求項的臨時案可直接轉換為非臨時案，無需重新起草 |
| **外國優先權** | 外國專利局（如 EPO）可能要求臨時案提供嚴格的優先權支持，請求項有助於此 |
| **費用效益** | 臨時階段追加請求項不額外收費 |

**外國優先權策略**：
- 對巴黎公約（Paris Convention）成員國的申請，臨時案可作為優先權基礎
- EPO 等可能審查臨時案的揭露是否逐字支持後續申請的優先權主張
- 具有請求項的臨時案比無請求項的臨時案更能展示優先權基礎

**請求項形式的彈性**：
- 臨時案中的請求項形式無強制要求（不審查）
- 但若計畫主張外國優先權，應注意內容的完整性與準確性

---

### 接續申請策略的整體考量

**建立請求項族（Claim Portfolio）**：
- 利用 Continuation 在競爭對手公開產品後調整請求項
- 利用 Divisional 保護因限制要求而被排除的發明
- 利用 CIP 在原始保護基礎上擴展至改進發明

**有效申請日管理**：
- Divisional / Continuation：所有請求項均享有母案申請日
- CIP：須逐項審查，確認哪些請求項可主張母案申請日
- 主張母案申請日的前提：母案說明書必須充分揭露（§112(a) written description + enablement）

**Terminal Disclaimer（終止聲明）**：
- Continuation 若遭遇 double patenting 核駁，提交 Terminal Disclaimer 可解決
- 代價：使兩件專利的到期日掛鉤，不能各自獨立延伸保護期

## 來源參照
- [[landis-ch05-other-types-of-claims]]：§5.6.1–§5.7 完整說明各接續申請案類型的規則與差異

## 相關概念
- [[written-description]]：CIP 請求項是否能主張母案申請日，取決於母案說明書的書面描述支持
- [[antecedent-basis]]：臨時申請中加入請求項可確認說明書的前提基礎完整性
- [[indefiniteness]]：接續申請案中請求項的明確性仍受 §112(b) 規範
- [[double-patenting]]：Continuation 和 CIP 面臨 double patenting 核駁的風險（待建立概念頁）

## 實務要點

1. **Divisional 自動受保護**：審查員不能以 double patenting 核駁分割案（與母案相比）——這是分割案的重要優勢
2. **Continuation 的時機**：在競爭對手公開產品後，在母案還在審查中時提出 Continuation，撰寫針對競爭產品的請求項
3. **CIP 要逐項確認有效申請日**：每個請求項要分析是否完全由母案說明書支持，否則有效日晚，先前技術範圍更廣
4. **Provisional 要加請求項**：雖然不強制，但撰寫請求項能確認揭露完整、加速後續轉換、支持外國優先權主張
5. **Terminal Disclaimer 不是免費的**：提交後兩件專利的期限掛鉤，評估策略成本
6. **不能在接續案中引入新事項（Divisional / Continuation）**：若有新發明必須走 CIP 路徑，並接受有效申請日後移的後果
