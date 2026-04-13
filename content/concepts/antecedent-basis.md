---
type: concept
title: Antecedent Basis（前提基礎）
aliases: [前提基礎, antecedent support]
tags: [claim-deficiency, claim-drafting, 112]
source_count: 3
---

# Antecedent Basis（前提基礎）

## 定義

Antecedent basis 是指請求項中每個以定冠詞（"the" 或 "said"）引用的元素，必須在同一請求項或其所依附的母項中先以不定冠詞（"a" 或 "an"）正式引入。缺乏前提基礎是最常見的請求項缺陷之一。

## 詳細說明

### 三個層面（§6.6.3）

1. **請求項內的前提基礎（§6.6.3.1）**
   - 首次引入元素時使用 "a" 或 "an"
   - 後續引用時使用 "the" 或 "said"
   - 錯誤範例：直接寫 "the motor" 而未先引入 "a motor"

2. **說明書中的前提基礎（§6.6.3.2）**
   - 請求項中使用的每個術語都應在說明書中有對應的描述
   - 若請求項使用了說明書中未出現的術語，可能被認為缺乏 written description support

3. **圖式中的前提基礎（§6.6.3.3）**
   - 請求項中描述的結構應在圖式中有對應的顯示
   - 機械發明尤其需要注意此點

### "A" vs "The" / "Said" 的規則（Landis §2.13）

- 元素**第一次引入**時用不定冠詞 "**a**" 或 "**an**"
- 後續**再次引用**時用定冠詞 "**the**" 或 "**said**"
- 使用 "the" 或 "said" 而無前置的 "a/an" 引入 → **缺乏前提基礎（lack of antecedent basis）** → §112 不確定性核駁
- 在 comprising 請求項中，"a" 意指「**一個或多個**」，不僅是「一個」——這具有重要的專利範圍意義

### 常見錯誤

- 在附屬項中引用母項未引入的元素
- 使用含糊的引用（如 "the element"），但請求項中有多個可能的指涉對象
- 術語不一致：請求項中用 "the fastener" 引用先前引入的 "a bolt"
- 直接寫 "said motor"（或 "the motor"）而從未以 "a motor" 引入

### MPEP §2173.05(e) 的補充規則

1. **繼承性前提（Inherent Antecedent Basis）**：元素固有的組成部件無需明確引入
   - "the outer surface of said sphere" 可接受——球體必然有外表面（*Bose Corp. v. JBL, Inc.*）
   - "an ellipse having a major diameter" 可接受——橢圓在數學上必然有長軸

2. **可合理確定範圍的例外**：若 PHOSITA 仍能合理確定請求項範圍，即使形式上缺乏前提基礎，也未必構成不確定
   - *Ex parte Porter*："controlled stream of fluid" 為 "the controlled fluid" 提供合理的前提基礎

3. **說明書術語與請求項術語的關係**：請求項中的術語不必與說明書的用語完全相同
   - 請求項術語在說明書中無前提基礎不自動不確定
   - 申請人有廣泛的術語選擇自由，只要定義清楚

4. **審查員義務**：前提基礎問題通常是起草疏漏，審查員應以積極建設的方式指出，而非直接拒絕

5. **體部超越前言（Body vs. Preamble）**：請求項主體包含前言未引入的元素，不因此而不確定（*In re Larsen*）

## 來源參照
- [[sheldon-ch6-claim-drafting]]：§6.6.3 詳述三個層面的前提基礎要求
- [[landis-ch02-claim-forms-formats]]：§2.13 以判例深入分析 "a" vs "the"/"said" 的用法——包括 "a" 在 comprising 請求項中代表「一個或多個」、缺乏前提基礎的不確定性核駁
- [[mpep-2173-indefiniteness]]：§2173.05(e) 系統性說明缺乏前提基礎的類型、例外與審查員職責

## 相關概念
- [[claim-body]]：antecedent basis 規則主要適用於 body 中的元素引用
- [[dependent-claim]]：附屬項中的術語必須在母項中有前提基礎
- [[statute-35usc112]]：缺乏前提基礎可能違反 §112 的明確性要求
- [[indefiniteness]]：缺乏前提基礎是 §112(b) 不確定性核駁的常見來源之一

## 實務要點

1. 撰寫完請求項後，逐一檢查每個 "the" 和 "said" 是否都有對應的 "a/an" 引入
2. 確保請求項中的術語與說明書和圖式保持一致
3. 這是最容易透過系統性檢查避免的缺陷——善用 Sheldon 的 Exhibit 6-13 檢查清單
