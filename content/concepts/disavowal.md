---
type: concept
title: Disavowal（範圍放棄）
aliases: [範圍放棄, disclaimer, surrender of scope, prosecution disclaimer]
tags: [claim-construction, disavowal, prosecution-history, specification]
source_count: 1
---

# Disavowal（範圍放棄）

## 定義

Disavowal 是指專利權人在說明書或審查歷史中，以**明確且無歧義**的方式放棄（surrender）特定主題或特定範圍的請求，導致請求項被解釋得比其文字平義更窄。Disavowal 是 [[claim-construction]] 中偏離平義的兩種例外之一（另一種是 lexicographer rule）。

## 詳細說明

### 兩種來源

#### 1. 說明書中的 Disavowal

發生情形：
- 在說明書中以限制性語言描述**整個發明**（而非僅描述一個實施例）
  - ❌ 危險：「The present invention requires...」「The invention must have...」「The invention is limited to...」
  - ✅ 安全：「In one embodiment...」「In a preferred embodiment...」「For example...」
- 明確聲明排除某種替代方案（「carrier waves are not included」）
- 以「necessary」「critical」「essential」「important」等詞強調某特徵
- 對比先前技術並強調本發明的差異點，暗示對先前技術的明確排除

#### 2. 審查歷史中的 Disavowal（Prosecution Disclaimer）

發生情形：
- 為克服引證核駁（prior art rejection）而在書面意見（response/remarks）中限縮說明
- 修改請求項以排除特定範圍（claim amendment）
- 未被採用的論述（arguments not adopted）：申請人提出某解釋，但 USPTO 並未接受，則該解釋仍可能被法院採用來縮限範圍

### 門檻：明確且無歧義

Disavowal 不輕易成立，必須：
- **明確（clear）**：不能是隱約暗示或模糊陳述
- **無歧義（unambiguous）**：聲明的意思只有一種合理解讀
- 模糊的陳述或「amenable to multiple reasonable interpretations」者，**不構成** disavowal

> *Intellectual Ventures LLC v. T-Mobile USA, Inc.*, 902 F.3d 1372（Fed. Cir. 2018）：單純提出某種解釋的論述，若未達到「exacting standard」，不構成 disavowal。

### 優選實施例 ≠ 範圍限制

這是最重要的實務規則：

**核心原則**：說明書中的優選實施例（preferred embodiment）或唯一揭露的實施例，**不自動**限縮請求項範圍。

> *Pacing Technologies LLC v. Garmin International, Inc.*, 778 F.3d 1021（Fed. Cir. 2015）：請求項中的「object」一詞不受說明書中提及「object」的特定脈絡限制。

反例（實施例 **確實** 限縮）：
- 說明書明確表示「only」「exclusively」「must be」
- 審查歷史顯示申請人曾以該結構特徵來區別先前技術
- 所有揭露的實施例均具有某特徵，且說明書強調該特徵是「the invention」的核心

### Importing Limitations（引入限制）

即使說明書中的描述不構成正式 disavowal，法院有時仍會「將說明書引入請求項」，原因包括：
- 說明書對某特徵的反覆強調，使法院認為該特徵是發明的必要部分（*ICU Medical v. Alaris*）
- 請求項用語本身範圍不明，說明書提供了解釋的脈絡（*Bell Atlantic v. Covad*）
- 僅揭露一種實施例，且請求項語言本身暗示結構對應（*Toro Co. v. White Consolidated*）

### Abstract 的地位

依 37 C.F.R. §1.72(b)，Abstract **不**構成說明書的一部分，因此原則上不能用來構成請求項的 disavowal。但近年 USPTO 對此有所調整，仍應謹慎措辭。

## 來源參照
- [[landis-ch01-statutory-provisions]]：§1:5 是本概念的主要分析來源，含大量 Federal Circuit 判例（*Pacing Technologies*、*ICU Medical*、*Intellectual Ventures v. T-Mobile*、*SRAM Corp. v. AD-II Engineering*）

## 相關概念
- [[claim-construction]]：Disavowal 是 claim construction 偏離平義的兩種例外之一
- [[preamble]]：Disavowal 有時源於 preamble 中的限縮性語言
- [[written-description]]：說明書揭露內容的廣度直接影響 disavowal 風險

## 實務要點

1. **永遠不要寫「The present invention is limited to...」或「The invention requires...」**——這可能是最昂貴的一句話
2. **以「In one embodiment...」或「For example...」開頭描述具體結構**，保留請求項的廣度
3. **審查中的論述要謹慎措辭**：「The prior art fails to teach X」比「The present invention requires X」更安全
4. **若要排除特定主題（如 carrier waves），明確寫在請求項中**，而不是只在說明書或審查意見中提及
5. **說明書應包含多個實施例**（A、B、C、D），明確說明「element B may be C or D」，避免被限縮到 C
6. **Claim differentiation 工具**：透過精心設計的附屬項，可彰顯獨立項未被限縮
7. **審查意見（Examiner's Interview）中的陳述也有效**：面談中的口頭承諾若記錄在案，同樣構成 prosecution history
