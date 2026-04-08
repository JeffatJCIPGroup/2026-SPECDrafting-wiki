---
type: concept
title: Claim Construction（請求項解釋）
aliases: [請求項解釋, claim interpretation, Phillips standard]
tags: [claim-construction, litigation, phillips, plain-meaning]
source_count: 1
---

# Claim Construction（請求項解釋）

## 定義

Claim construction 是法院（或 USPTO）就請求項中每個用語的含義所作的法律認定。它決定了請求項的保護範圍，是侵權分析（infringement analysis）與有效性分析（validity analysis）的前提。在 USPTO 審查中採用 BRI（Broadest Reasonable Interpretation，最寬合理解釋）標準；在聯邦地方法院訴訟中採用 *Phillips* 標準。

## 詳細說明

### Phillips 標準（2005 en banc）

*Phillips v. AWH Corp.*, 415 F.3d 1303（Fed. Cir. 2005）確立了現行聯邦法院解釋請求項的主要框架：

**請求項用語以「專利文件脈絡中、具有相關技術領域通常知識之人所理解的平義（plain and ordinary meaning）」為準。**

解釋時應依序參考以下證據層次：

#### 內在證據（Intrinsic Evidence）——主要依據

1. **請求項本身**
   - 請求項用語在該請求項中的上下文
   - 同一專利中其他請求項的用法（claim differentiation）
   - 獨立項與附屬項之間的關係

2. **說明書（Specification）**
   - 最重要的內在證據來源
   - 可顯示發明人如何使用特定術語
   - 但說明書中的優選實施例**不自動**限制請求項範圍（除非有明確 disavowal）
   - 若說明書提供術語的明確定義，該定義優先（lexicographer rule）

3. **審查歷史（Prosecution History）**
   - 申請人在審查過程中的陳述與修正
   - 可顯示申請人放棄（disavow）的範圍
   - 通常比說明書更不清晰，但有時具有決定性

#### 外在證據（Extrinsic Evidence）——次要工具

- 字典（尤其是技術字典）、百科全書、教科書
- 專家證詞（但不得與內在證據矛盾）
- 先前核准的相關專利

> *Phillips* 推翻了 *Texas Digital*（2002）的字典優先方法，確立**內在證據優先**。字典可用於理解普通含義，但不能以此推翻說明書的脈絡意義。

### 兩種偏離平義的例外

1. **自任詞典編纂者（Lexicographer Rule）**
   - 專利權人在說明書中為術語提供明確、不同於平義的定義
   - 必須有「明確意圖」（clear intent）且「清晰陳述」（clearly expressed）
   - 若成立，說明書中的定義取代字典意義

2. **Disavowal（明確放棄）**
   - 在說明書或審查歷史中明確放棄特定主題
   - 門檻高：必須「明確且無歧義」
   - 詳見 [[disavowal]]

### BRI（USPTO 審查標準）vs. Phillips（法院標準）

| | BRI（USPTO） | Phillips（法院） |
|--|--|--|
| 適用場合 | 審查中、PTAB | 聯邦地院、ITC |
| 解釋寬度 | 最寬合理解釋 | 最正確解釋 |
| 說明書角色 | 限制 BRI | 主要依據 |
| 目的 | 促進審查效率，鼓勵申請人精確撰寫 | 確定實際保護範圍 |

*Cuozzo Speed Technologies v. Lee*（2016）：最高法院確認 PTAB 可採用 BRI 標準。

### Claim Differentiation（請求項差異原則）

- 若兩個請求項唯一的差異是某一限制，則該限制在有此限制的請求項中具有限縮意義
- 推論：獨立項的範圍不應等同於已加入額外限制的附屬項
- 此原則僅為推定，可被說明書或審查歷史推翻

### 混合請求項的不確定性風險

若一個請求項同時涵蓋**裝置（apparatus）**與**方法（method）**的行為，可能被認定違反 §112 不確定性——因為侵權的發生時點不清楚（裝置存在時即侵權？還是使用時才侵權？）。
> *IPXL Holdings v. Amazon.com*, 430 F.3d 1377（Fed. Cir. 2005）

## 來源參照
- [[landis-ch01-statutory-provisions]]：§1:4 以大量 Federal Circuit 判例（包括 *Phillips* en banc 全文分析）詳述內在/外在證據層次與字典使用規則

## 相關概念
- [[disavowal]]：專利權人如何在說明書或審查歷史中縮限請求項範圍
- [[preamble]]：preamble 是否限制請求項範圍，本身就是一個 claim construction 問題
- [[means-plus-function]]：§112(f) 的功能性請求項有特殊解釋規則
- [[statute-35usc112]]：§112(b) 明確性要求與 claim construction 密切相關

## 實務要點

1. **撰寫時預設 Phillips 標準**——想像法官在沒有字典、只有你的說明書和審查歷史的情況下解讀請求項
2. **說明書要支持最寬解釋**：確保說明書包含各種不同結構、材料、數值範圍的實施例，避免被限縮
3. **避免在說明書中使用「the present invention is...」限縮整個發明範圍**——這可能構成 [[disavowal]]
4. **若要自任詞典編纂者，必須明確宣告**：「As used herein, term X means...」
5. **審查中的論述（argument）也算數**：為克服核駁所做的陳述，即使未修改請求項文字，也可能被法院引用以縮限範圍
6. **Claim differentiation 是雙面刃**：精心設計的附屬項可彰顯獨立項的廣度，但也可能產生非預期的縮限效果
