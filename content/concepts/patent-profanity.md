---
type: concept
title: Patent Profanity（專利髒話）
aliases: [專利髒話, patent profanity, 高風險用語, claim scope limitation, self-limiting language]
tags: [patent-profanity, claim-drafting, specification-language, risk-management, prosecution-history]
source_count: 2
---

# Patent Profanity（專利髒話）

## 定義

**Patent profanity（專利髒話）**是指在說明書（specification）、請求項（claims）或答辯文件（prosecution history）中，可能無意間讓請求項被縮限解釋的高風險用語。這些詞語以**絕對性（absolute）**或**限制性（limiting）**的方式描述發明，法院和對手可能據此主張申請人已自我限縮（self-limiting）其保護範圍。

> **核心認識**：Patent profanity 不是「禁字令」，而是「風險管理工具」。遇到這些詞語時，需要有意識地評估：是否真的有必要這樣說？有無替代語？

---

## 詳細說明

### 法律機制：為什麼這些詞會傷害你？

Patent profanity 通過兩條主要法律路徑傷害請求項範圍：

**1. Prosecution History Disclaimer（申請歷史免責／Estoppel）**
- 在與 USPTO 的答辯溝通中使用限制性強調語言
- 競爭對手可引用這些陳述，主張申請人已承認某特徵為必要限制
- 例：在 OA response 中說「the invention requires X」→ 競爭對手主張 X 是必要元素

**2. Claim Construction（請求項解釋）**
- 說明書中的限定性語言可能被法院用來縮限請求項語言的普通含義
- *Phillips v. AWH Corp.* 標準：說明書是最重要的外部解釋工具
- 說明書中的 lexicographer rule：若說明書對某術語給出特殊定義，法院必須接受
- 若說明書以強烈語言描述某特徵，法院可能將其讀入請求項（即使請求項本身未明確限定）

---

### 風險分級詞彙表

#### 🔴 高風險：絕對避免（Never Use）

| 類別 | 典型詞彙 | 風險說明 |
|------|---------|---------|
| **「本發明」系列** | `the present invention`、`the invention`、`this invention`、`the present invention is`、`the present invention requires`、`the present invention includes` | 整體性限定，可能讓特定特徵成為整個發明的必要構成；*Microsoft v. RCT* 的教訓 |
| **必要性詞彙** | `must`、`required`、`necessary`、`essential`、`shall`、`need`、`indispensable`、`imperative` | 讓特徵看起來是不可缺少的構成，而非可選方案 |
| **強調性詞彙** | `critical`、`key`、`very important`、`crucial`、`vital`、`paramount`、`pivotal` | *Inpro II v. T-Mobile*、*Mylan v. Pharmacia*：強調性詞語被用來縮限 claim scope |
| **絕對排除詞** | `only`、`solely`、`merely`、`always`、`never`、`all`、`each*`、`entirely`、`exclusively` | 排除替代方案；*Biovail v. Andrx*（"necessarily"）、*Atofina*（"solely"） |
| **最優/唯一詞** | `best`、`optimal`、`perfect`、`unique`、`superior`、`preferred`（單獨用） | 暗示沒有等效方案，可能阻礙均等論（doctrine of equivalents） |
| **固有詞** | `inherent`、`inherently`、`necessarily`、`inextricable` | 暗示無可分割的技術特性，可能被解讀為必備 |
| **「目的」詞** | `objects of the invention`、`objects of the present invention` | *Microsoft v. RCT*：被用來界定發明的整體目的，進而限縮範圍 |
| **全稱詞** | `all embodiments`、`all cases`、`everywhere`、`everything` | 把描述擴張為普遍規則，無例外空間 |

#### 🟡 中風險：盡量避免（Avoid Using）

| 類別 | 典型詞彙 | 風險說明 |
|------|---------|---------|
| **強調詞** | `important`、`fundamental`、`core`、`principal`、`integral` | 語氣過強時暗示該特徵的核心地位 |
| **最高級詞** | `biggest`/`smallest`、`highest`/`lowest`、`maximum`/`minimum`、`largest`、`widest`、`oldest`/`newest` | 隱含排他性，可能限縮範圍 |
| **固化詞** | `intrinsic`、`invariably`、`constantly`、`perpetual` | 暗示不變性，排除替代實施方式 |
| **優選詞** | `preferred`、`most preferred`、`better`（作為必要性描述時） | 若寫法暗示只有優選例才算發明，有風險；若作為「在某些實施例中的優選方案」則相對安全 |
| **決定性詞** | `conclusive`、`decisive`、`determinative`、`overarching` | 暗示唯一正確答案 |
| **成功/失敗詞** | `successful manufacture`、`successful implementation` | 把「成功」本身變成技術必備條件 |

#### 🟢 相對安全：推薦替代語（Safe Alternatives）

| 替代語 | 取代 | 說明 |
|--------|------|------|
| `in some embodiments` | `in one embodiment`、`in the invention` | 保留多個實施例的解讀空間 |
| `may` / `can` / `optionally` | `must` / `shall` / `required` | 可選而非強制 |
| `for example` / `such as` / `including but not limited to` | 無修飾的列舉 | 明確為舉例，非完整列舉 |
| `advantageously` | `critical` / `essential` | 表達優勢而非必要性 |
| `the current disclosure` / `this example` | `the present invention` | 避免整體性限定 |
| `in certain embodiments` / `in at least one embodiment` | `in all embodiments` | 限定在特定實施例 |
| `configured to [function], for example by [structure]` | 只說 `configured to [function]` | §112 支持需要配合具體結構說明 |

---

### 高風險場景

#### 1. 說明書的背景技術（Background）
- 背景技術中對先前技術的描述，可能被用來限縮請求項中同類用語的解釋
- 避免在背景技術中描述先前技術的「缺點」然後暗示自己的發明「解決了所有問題」

#### 2. 「發明內容（Summary of Invention）」段落
- **最高風險區域**！
- 避免使用 "The present invention is..."、"The present invention requires..."
- 改用：「In accordance with one aspect of the disclosure...」或「In some embodiments...」

#### 3. 答辯（Office Action Response）
- **prosecution history 是永久記錄**
- 對抗先前技術時，避免說「the invention requires X」（除非你真的想限定）
- 謹慎使用強調語言；若要強調差異，聚焦在先前技術的不同而非自身的「必要」特徵

#### 4. 請求項本身
- `each`：問自己「真的必須是每個嗎？」
- `always`、`never`：幾乎不應出現在請求項中
- `the invention`：請求項是「發明」的語言，但不要說「this invention requires...」

#### 5. `configured to` 在說明書中的特殊規則
- 在**請求項**中：`configured to` 是標準的功能性語言，安全
- 在**說明書**中：使用 "X is configured to Y" **必須**緊接說明哪些具體結構執行該功能
- 若只說 "X is configured to Y" 而無對應結構描述，在審查中缺乏 §112(a) 支持

---

### 核心判例速查

| 案例 | 髒話 | 後果 |
|------|------|------|
| **Inpro II v. T-Mobile** | "very important feature"（說明書中描述接口） | 被對手用來縮限 host interface 的解釋，T-Mobile 以此不侵權 |
| **Mylan v. Pharmacia** | "key feature"、"critical feature"（OA response 中） | Pharmacia 在訴訟中範圍被縮限 |
| **Biovail v. Andrx** | "necessarily"（OA response 中） | Andrx 主張縮限，獲勝 |
| **Microsoft v. RCT** | "the present invention"、"objects of the invention" | 整個發明被限縮至特定目的 |
| **Atofina 案** | "solely"（催化劑 solely 為鉻） | 排除含金屬氧化物的變體 |
| **Pharmacia 案** | "critical"（噴霧乾燥乳糖被描述為 critical） | 觸發 estoppel，無法主張均等論 |

---

### 戰略性使用 Patent Profanity

**有時刻意使用是正確的策略**：
- 當你需要一個**窄範圍但有效性確定**的請求項（例如對特定競爭產品的精準保護）
- 當某特徵確實是必要的技術特徵，且你需要清楚地主張它
- 在 independent claim 中避免，但在 dependent claim 中可以有策略性地限縮

> **關鍵原則**：每次使用高風險詞語，都應能回答：「為什麼這裡必須用這個詞？」若無法回答，換掉它。

---

### 申請策略建議

**建立「紅旗審查（Red-Flag Review）」機制**：
- 不是機械式禁用，而是「遇到高風險字眼必須 justify」
- 若使用 `present invention` / `critical` / `essential` / `very important`，起草人在備忘錄中說明為何必須、以及是否有對應的 fallback embodiments（後備實施例）

**Fallback Embodiments（後備實施例）策略**：
- 若說明書中某處使用了強調性語言，在其他段落提供替代實施例
- 確保這些替代實施例也被請求項覆蓋，避免被解讀為唯一實施方式

**AI 起草清洗清單**：
- 特別注意：摘要（Abstract）、背景技術（Background）、發明內容（Summary）、優選實施例（Preferred Embodiments）
- 這些段落最容易被 AI 工具填入誇飾語和套話

**Paris / Bypass vs. PCT §371**：
- 選擇 Paris Convention 或 Bypass 申請路徑，允許在提交美國時對說明書進行「清洗」
- 可修正翻譯錯誤和 patent profanity，確保符合美國撰寫風格

---

### 一句話原則

> **Patent profanity 不是「不能用的字」，而是「可能改變權利範圍解讀的字」。重點不是避免所有強調詞，而是避免把可選特徵（optional feature）寫成必要特徵（mandatory limitation）。**

## 來源參照
- [[patent-profanity-2024-aurora]]：Aurora Patents（Kristen Hansen, 2024）：三級分類詞彙表（Never/Avoid/Only）、四個判例教訓、"configured to" 的特殊規則
- [[patent-profanity-2026-bilingual-guide]]：使用者整理（2026-04-15）：中英對照詞彙表、近年 CAFC 判例（Contour IP、IOENGINE、Inpro II、Atofina、Pharmacia）、§101/§112 2024–2025 審查環境、AI 起草風險

## 相關概念
- [[disavowal]]：Patent profanity 在 prosecution history 中造成的 disclaimer 效果（另一機制）
- [[claim-construction]]：Phillips 標準下說明書語言如何影響請求項解釋
- [[indefiniteness]]：Patent profanity 的 §112(b) 面向（某些詞語可能造成不確定性）
- [[means-plus-function]]：`configured to` 在說明書 vs. 請求項中的不同處理
- [[specification-drafting]]：說明書撰寫中的 patent profanity 風險管理
- [[written-description]]：說明書語言對請求項支持的影響

## 實務要點

1. **「in some embodiments」是你最好的朋友**——幾乎任何對實施例的描述都應加上這個前綴
2. **「the present invention is/requires/includes」是你最壞的敵人**——這三句話可以毀掉一件專利的範圍
3. **答辯文件是永久記錄**——比說明書更危險，因為審查員的理解會反映在核准文件中
4. **Fallback embodiments 是保險政策**——每次說了「critical」，就在別處提供一個不用這個特徵也能運作的實施例
5. **AI 產出必須人工清洗**——AI 最愛在背景技術和發明內容中填入誇飾語和套話
6. **強調語言要用在刀刃上**——dependent claim 中刻意限縮可以是策略，但 independent claim 中的強調語言代價很高
7. **`configured to` 在說明書中要配合結構說明**——裸露的 "X is configured to Y" 缺乏 §112 支持
8. **優選例（preferred embodiment）的文字要小心**——若整個說明書只描述了一個「優選」實施例，法院可能把它讀成唯一實施例
