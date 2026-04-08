---
type: concept
title: Statutory Classes（法定專利類別）
aliases: [法定類別, 101 eligibility, patent eligibility, 專利適格性]
tags: [101, statutory-classes, patent-eligibility, software, business-method]
source_count: 1
---

# Statutory Classes（法定專利類別）

## 定義

35 U.S.C. §101 規定，任何「**發明或發現**任何新穎且有用的 process（方法）、machine（機器）、manufacture（製品）或 composition of matter（物質組成），或其新穎且有用的改良」的人，可申請並獲得專利。這四大類別即為法定專利類別（statutory subject matter）。

## 詳細說明

### 四大法定類別

| 類別 | 定義 | 常見例子 |
|------|------|----------|
| **Process（方法）** | 一系列步驟或行為 | 製造方法、資料處理方法、化學合成步驟 |
| **Machine（機器）** | 具有機械部件的具體裝置 | 電腦、引擎、機械手臂 |
| **Manufacture（製品）** | 人造物品（非機器、非組成物） | 電路板、工具、容器 |
| **Composition of Matter（物質組成）** | 化學物質、混合物、化合物 | 藥物分子、合金、聚合物 |

**「anything under the sun made by man」**——最高法院在 *Diamond v. Chakrabarty*（1980）確認 §101 應廣泛解釋，涵蓋所有人造的有用事物。

### 法定排除（Judicial Exceptions）

三類主題**本質上不可專利**（judicially created exceptions）：
1. **抽象思想（abstract ideas）**：數學公式、基本概念
2. **自然規律（laws of nature）**：自然界固有的現象
3. **自然現象（natural phenomena）**：自然存在的物質或事件

但若發明**整合**（integrate）這些不可專利的要素到**實際應用**（practical application）中，仍可能具有專利適格性。

### Alice/Mayo 兩步驟框架

*Alice Corp. v. CLS Bank International*（2014）與 *Mayo Collaborative Services v. Prometheus*（2012）確立了分析軟體、商業方法與生物技術專利適格性的現行框架：

**Step 1**：請求項是否指向法定類別之一（process, machine, manufacture, composition）？
- 若否 → 不具適格性
- 若是 → 繼續 Step 2

**Step 2A**：請求項是否指向司法例外（abstract idea, law of nature, natural phenomenon）？
- 若否 → 具有適格性
- 若是 → 繼續 Step 2B

**Step 2B**：請求項中是否有「顯著更多」（significantly more）超越司法例外本身的元素？
- 若有明確的改良、特定技術效果 → 可能具有適格性
- 若僅是對例外的「apply it」指示 → 不具適格性

### 商業方法（Business Methods）

- *State Street Bank & Trust Co. v. Signature Financial Group*（1998）：商業方法可專利（若產生「有用、具體且有形的結果」）
- *Bilski v. Kappos*（2010）：最高法院限縮，但未完全否定商業方法專利
- *Alice v. CLS Bank*（2014）：以「在電腦上執行」的一般指示不足以使抽象的商業方法具有適格性
- 現狀：商業方法仍可申請，但必須展現具體技術改良

### 軟體發明

- 演算法本身不可專利，但**應用於特定技術問題**的軟體發明可能具有適格性
- 關鍵是：請求項是否「改良電腦本身的功能」或「改良特定技術領域」？
- *Enfish, LLC v. Microsoft*（Fed. Cir. 2016）：改良資料庫結構的軟體 → 具有適格性
- 撰寫技巧：強調技術問題與技術解決方案，而非僅描述功能結果

### 人類有機體的排除

35 U.S.C. §33（Leahy-Smith America Invents Act）明確禁止對人類有機體的請求項。基因工程改造的微生物可專利（*Diamond v. Chakrabarty*），但人類胚胎、人體等不可。

### 混合類別請求項（Mixed-Class Claim）的風險

若一個請求項同時涵蓋**裝置**的存在（apparatus）與**使用者操作**的方法行為（method），可能因涵蓋兩個法定類別而違反 §112 不確定性要求——侵權時點不明（裝置存在即侵？還是使用時才侵？）。

> *IPXL Holdings, L.L.C. v. Amazon.com, Inc.*, 430 F.3d 1377（Fed. Cir. 2005）

**解決方案**：
- 分別撰寫裝置請求項與方法請求項
- 若要在裝置請求項中描述功能，使用「configured to」或「adapted to」而非直接描述方法步驟

## 來源參照
- [[landis-ch01-statutory-provisions]]：§1:3 詳述四大法定類別的定義與案例，並分析商業方法、軟體發明的適格性問題及混合類別請求項風險

## 相關概念
- [[claim-construction]]：適格性分析的前提是正確理解請求項的範圍
- [[independent-claim]]：獨立項應清楚落入特定法定類別
- [[means-plus-function]]：功能性請求項語言的特殊規則

## 實務要點

1. **確定每個獨立項落入哪個法定類別**，並在說明書中明確支持
2. **軟體/AI 發明**：在說明書中詳述技術問題與技術解決方案，請求項中強調硬體架構的具體改良
3. **商業方法**：主張電腦/網路系統的特定技術改良，而非僅描述「在電腦上執行商業邏輯」
4. **分開撰寫裝置與方法請求項**，避免混合類別風險
5. **「configured to」是安全用語**：在裝置請求項中使用 "configured to perform..."，而非直接描述方法步驟
6. **生物技術**：天然存在的序列/物質需要顯著的人工修飾才具適格性（*Association for Molecular Pathology v. Myriad Genetics*，2013）
