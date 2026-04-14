---
type: source
title: Patent Profanity 中英對照實務指南（2026-04-15）
source_file: RAW/20260415-patent profanity整理成中英對照.docx
author: 使用者整理（含 AI 輔助分析）
date_ingested: 2026-04-15
tags: [patent-profanity, claim-drafting, 101, 112, CAFC, AI-patents, prosecution-history, risk-management]
---

# Patent Profanity 中英對照實務指南（2026-04-15）

## 來源資訊
- **檔案**：`RAW/20260415-patent profanity整理成中英對照.docx`
- **作者**：使用者整理（含 AI 輔助分析與 2024–2026 CAFC 近年判例摘要）
- **類型**：內部整理文件（含中英對照詞彙表、判例摘要、實務建議）

---

## 摘要

本文件為使用者自行整理的 patent profanity 中英對照指南，涵蓋三個層次：
1. **概念層**：Patent profanity 的定義、近期討論主軸（2024–2026）、風險管理觀點
2. **詞彙層**：完整中英對照高風險用語清單，分高/中/低風險三級
3. **法律層**：2024–2025 年 USPTO 審查環境中的 §101（Alice 測試）與 §112（明確性、書面描述）最新判例，以及 patent profanity 在訴訟中的實際案例

---

## 重點筆記

### §1 Patent Profanity 的定義與近年轉向

- **核心定義**：Patent profanity 是指那些可能在說明書、請求項或答辯中，讓法院/審查員讀出「自我限縮（self-limiting）」效果的高風險用語
- **近年趨勢（2024–2026）**：焦點已從「字詞黑名單」轉向「這些字會不會在 claim construction 或 prosecution history disclaimer 中被放大」
- **AI 時代的新風險**：AI 起草工具易引入誇飾語、套話及不必要的絕對化表述，形成後續解釋風險
- **成熟立場**：將 patent profanity 視為「風險管理」而非「禁字令」——遇到高風險字眼時必須能 justify（提供理由），而非機械性禁用

---

### §2 中英對照高風險用語清單

#### 高風險詞（High Risk）

| 中文 | English | 風險說明 |
|------|---------|---------|
| 本發明 | the present invention / this invention | 整體性限定；反覆使用可能讓某些特徵成為必要構成 |
| 發明 | invention | 單獨使用也有風險；讀者易以為後文是發明本身的定義 |
| 本發明包含 | the present invention includes | 容易把接下來列出的內容變成發明的必要特徵 |
| 本發明是 | the present invention is | 容易被解讀為定義性語句，進而限縮權利範圍 |
| 本發明需要 | the present invention requires | 直接把某特徵寫成必備條件，風險最高 |
| 必須 | must / require / requires | 讓特徵看起來是不可缺少的構成，而非可選方案 |
| 必要 | necessary | 常見高風險詞，可能被視為自我限縮 |
| 關鍵 | critical / key | 容易把某元件描述成核心限制，對 claim construction 不利 |
| 非常重要 | very important | 典型 patent profanity，Inpro II 案後常被引用 |
| 唯一 | only / sole | 直接把範圍縮成單一方案，通常風險非常高 |
| 僅 / 只有 | only / merely | 容易被理解為排他性或絕對性限定 |
| 總是 | always | 暗示沒有例外，不利於廣泛解釋空間 |
| 從不 | never | 和 always 類似，容易形成絕對性限定 |
| 必然 / 必定 | necessarily | 部分案例中被主張為不可避免的限定效果（Biovail 案） |
| 全部實施例 | all embodiments | 可能把某描述擴張為所有實施方式都必須符合 |
| 物件 / 目的 | object / objects of the invention | 若寫得過強，可能被當成限制依據（Microsoft v. RCT 案） |
| 成功製造 / 成功實現 | successful manufacture / successful implementation | 容易讓人把「成功」本身當作技術必備條件 |

#### 中風險詞（Medium Risk）

| 中文 | English | 風險說明 |
|------|---------|---------|
| 重要 | important | 語氣太強時，可能讓對方主張該特徵是重要限定 |
| 核心 | principal / core | 若太絕對，可能讓其他替代實施方式被排除在外 |
| 基本 / 基本上 | fundamental / basically | 容易造成定義性效果，尤其與「本發明」並用時 |
| 最好 / 較佳 | better / preferred / most | 若暗示為唯一優勢來源，可能造成限縮 |
| 優選 | preferred | 本身常見且可用，但若上下文暗示只有優選例才算發明則有風險 |

#### 相對安全的替代語（Safe Alternatives）

| 替代語 | 說明 |
|--------|------|
| `in some embodiments` / `某些實施例` | 保留變化空間，是最常見的安全寫法 |
| `may` / `can` / `可以` | 比 must 更安全，代表可選而非必要 |
| `for example` / `such as` / `例如` | 表示舉例而非限定 |
| `in one embodiment` → `in some embodiments` | 前者指涉單一，後者保留多個實施例的解讀空間 |
| `advantageously` / `in some embodiments` | 取代 critical / essential / very important |
| `the current disclosure` / `this example` | 取代 the invention / present invention |
| `may` / `can` / `optionally` | 取代 must / only / solely / all |

---

### §3 Patent Profanity 核心判例

| 案例 | 使用的髒話 | 結果 |
|------|-----------|------|
| **Inpro II v. T-Mobile** | "very important feature"（接口被稱為「非常重要特徵」） | T-Mobile 以此主張其不侵權，成功脫身；「very important feature」被用來縮限 host interface 的解釋 |
| **Mylan v. Pharmacia & Upjohn** | "key feature"、"critical feature"（在與 USPTO 溝通中） | Mylan 勝；強調性用語在答辯中的使用可構成 estoppel |
| **Biovail v. Andrx** | "necessarily"（在與 USPTO 溝通中） | Andrx 勝；"necessarily" 導致 Biovail 的保護範圍縮窄 |
| **Microsoft v. RCT** | "the present invention"、"objects of the invention" | Microsoft 勝；這些說法被用來限制整個發明的範圍 |
| **Atofina 案** | "solely"（催化劑「solely」為鉻） | 排除含金屬氧化物的變體，範圍被縮窄 |
| **Pharmacia 案** | "critical"（噴霧乾燥乳糖被描述為 critical） | 觸發 estoppel，無法主張均等論（doctrine of equivalents） |

---

### §4 2024–2025 年 USPTO 審查環境（§101 / §112 更新）

#### §101 軟體適格性（Alice 測試）

**近期 CAFC 判例態勢**：
- **不具適格性（抽象概念）**：僅涉及數據識別、分析、呈現；或將傳統商業行為與通用 GPS 結合（*IBM v. Zillow*、*AI Visualize v. Nuance*）
- **具適格性（技術改進）**：透過**特定技術手段**解決硬體/系統的物理限制（*Contour IP v. GoPro*：並行傳輸雙流媒體解決頻寬限制；*IOENGINE v. Ingenico*：加密數據「隧道化」的通訊過程）

**2025 USPTO AI 審查備忘錄**（回應 *Recentive Analytics v. Fox Corp.*）：
- "Close Call" 標準：§101 核駁前，審查員必須證明不適格性超過 50%
- 人腦無法實際執行的操作（如從語音信號提取光譜特徵、複雜矩陣運算）不屬於心智過程
- **AI 撰寫建議**：描述技術邏輯，不直接標註算法名稱（"Backpropagation"、"Gradient Descent" = 「敘述數學概念」，有風險）

#### §112 明確性與書面描述（2024 判例）

| 案例 | 規則 |
|------|------|
| **Maxell v. Amperex** | 同一請求項多重限制（如 A/B/C 且 A 含量 30-100%）不矛盾，只要 POSA 能找到同時滿足的實施方式 |
| **Janssen v. Teva** | 若測量技術影響請求項範圍，說明書應指明；但挑戰者需證明不同技術產生「實質性差異」才能主張不確定 |
| **Vascular Solutions v. Medtronic** | 不同獨立項的「功能性構造」不需相同物理邊界，只要對 POSA 明確 |
| **Rai Strategic Holdings 案** | 在可預見領域，揭露廣泛範圍（75-125%）及端點，可支持其中的窄範圍（75-85%） |

---

### §5 從業人員實務建議

1. **申請路徑選擇**：Paris Convention（或 Bypass）比 PCT §371 更靈活，允許在提交時對說明書進行「清洗」（修正翻譯錯誤與 patent profanity）
2. **明確主體指派**：避免無主體動詞（"is determined"）；使用「計算設備」或「處理器」作為執行者
3. **多重從屬項**：中國常見但美國費用昂貴，進美前調整結構
4. **IDS 揭露義務**（Rule 1.56）：美國標準遠寬於其他法域，及時呈報所有相關外國審查意見
5. **AI 輔助撰寫的審核**：AI 內容必須人工清洗，特別注意摘要、背景技術、發明內容與優選實施例段落中的誇飾語

---

## 關鍵概念
- [[patent-profanity]]：完整概念頁，綜合兩來源
- [[disavowal]]：Patent profanity 在 prosecution history 中造成的 disclaimer 效果
- [[claim-construction]]：Patent profanity 影響請求項解釋的機制（Phillips 標準）
- [[indefiniteness]]：§112(b) 不確定性與 patent profanity 的交叉
- [[statutory-classes]]：§101 軟體適格性（Alice 測試）的 2024–2025 更新

## 相關來源
- [[patent-profanity-2024-aurora]]：Aurora Patents 的基礎詞彙分類與判例
- [[mpep-2173-indefiniteness]]：§2173 不確定性審查指南（與 §112 相關）

## 引用與註記

> 「這些字不是『不能用』，而是一旦寫進關鍵段落，就可能被對方拿來說你自己把專利範圍縮小了。」

> 「最佳實務：把 patent profanity 當成『起草與答辯的 red-flag checklist』，而不是僵化禁語表，才能兼顧可執行性與權利範圍彈性。」

> 「高品質專利撰寫的核心原則在於『範圍廣度』與『法律防禦性』的精密平衡。」
