# 操作日誌

> 按時間順序記錄所有 Wiki 操作。由 LLM 自動維護。
> 查詢最近 5 筆紀錄：`grep "^## \[" wiki/log.md | tail -5`

---

## [2026-04-15] ingest | Patent Profanity（專利髒話）— 兩份來源

- **來源 1**：`RAW/Patent Profanity 2024.docx`（Aurora Patents, Kristen Hansen, 2024/7/2）
- **來源 2**：`RAW/20260415-patent profanity整理成中英對照.docx`（使用者整理，2026-04-15）
- **新增頁面**：[[patent-profanity-2024-aurora]], [[patent-profanity-2026-bilingual-guide]], [[patent-profanity]]
- **更新頁面**：index.md, log.md
- **備註**：Patent profanity 完整體系建立。核心洞見：(1) 不是禁字令，而是風險管理工具；(2) 兩條法律傷害路徑——prosecution history disclaimer + claim construction；(3) 最危險的三句話："the present invention is/requires/includes"；(4) 關鍵判例：Inpro II（"very important feature"）、Atofina（"solely"）、Pharmacia（"critical" → estoppel，阻礙均等論）；(5) 替代語策略："in some embodiments"、"may/can"、"for example"；(6) AI 起草的清洗需求。

## [2026-04-15] ingest | Landis CH05 — Other Types of Claims

- **來源**：`RAW/2024-Mechanics of Claim Drafting/Chap05-Other Type Claims.md`（+ `Chap05-Other Types of Claims Contents.docx`，僅目錄大綱）
- **作者**：Robert C. Faber（修訂自 Landis）
- **新增頁面**：[[landis-ch05-other-types-of-claims]], [[product-by-process]], [[design-claims]], [[continuing-applications]]
- **更新頁面**：index.md, log.md
- **備註**：§5.1–§5.7 完整涵蓋。核心洞見：(1) PBP 可專利性看產品（非製程），侵權看製程（Atlantic Thermoplastics）；(2) 設計請求項只有一項，格式固定為 "as shown"，禁用 "substantially"，圖式即請求項；(3) Divisional 不可被 double patenting 核駁（分割案的關鍵優勢）；(4) CIP 有效申請日逐項計算（依賴新事項則取 CIP 日）；(5) Provisional 建議仍加請求項（支持外國優先權、確認揭露完整性）。

## [2026-04-15] ingest | Landis CH04 — Method or Process Claims

- **來源**：`RAW/2024-Mechanics of Claim Drafting/Chap04-Method or Process Claims.md`（+ `Chap04 Method or Process Claims Contents.docx`，僅目錄大綱）
- **作者**：Robert C. Faber（修訂自 Landis）
- **新增頁面**：[[landis-ch04-method-process-claims]], [[method-claims]]
- **更新頁面**：index.md, log.md
- **備註**：§4.1–§4.8 完整涵蓋。核心洞見：(1) 方法描述 DOES（做什麼），裝置描述 IS（是什麼）；(2) 步驟用動名詞 "-ing"，需要實際執行不只是能力；(3) 步驟順序非必要時勿明確表述；(4) 避免在方法請求項中加入裝置限制（能免則免），化學/組成物限制則無問題；(5) 方法+裝置混合請求項 = indefinite（IPXL）；(6) Tarczy-Hornoch：方法不因為是裝置固有功能而被拒；(7) Ochiai：使用新穎起始物的方法可獲專利（整體非顯而易見性測試）。

## [2026-04-11] ingest | MPEP §2173 — Claims Must Particularly Point Out and Distinctly Claim the Invention

- **來源**：`RAW/MPEP 2173 Claims Must Particularly Point Out and Distinctly Claim the Invention.docx`
- **作者**：USPTO（Manual of Patent Examining Procedure, R-01.2024）
- **新增頁面**：[[mpep-2173-indefiniteness]], [[indefiniteness]]
- **更新頁面**：[[antecedent-basis]]（source_count 2→3，新增 §2173.05(e) 繼承性前提基礎、例外規則、審查員義務）、[[markush-group]]（source_count 1→2，新增 §2173.05(h) 必須用 "consisting of"、"comprising" 版本不確定、"optionally" 可接受、雙重包含規則）、index.md
- **備註**：本文件（§2173–§2173.06）涵蓋 §112(b) 不確定性的完整 USPTO 審查指引，共 22 種具體失敗模式。核心洞見：(1) *Nautilus*（2014）確立「合理確定性」標準，取代更寬鬆的「不可理解」標準；(2) 廣度不等於不確定性；(3) 裝置+方法混合請求項自動不確定（*IPXL*）；(4) Markush 群組必須用 "consisting of"；(5) 否定限制需要說明書正面基礎；(6) Compact prosecution 要求 §112(b) 和 §102/103 核駁同時提出。

## [2026-04-06] create | Wiki 初始化

- **操作**：建立 Wiki 架構、CLAUDE.md Schema、index.md、log.md
- **新增頁面**：index.md, log.md
- **備註**：Wiki 知識庫正式啟動，準備開始 ingest 原始來源

## [2026-04-07] ingest | Sheldon CH7 — Specification Drafting

- **來源**：`RAW/Sheldon/Sheldon-CH07_Specification Drafting.docx`
- **作者**：Jeffrey G. Sheldon, *How to Write a Patent Application*, Chapter 7 (2006)
- **新增頁面**：[[sheldon-ch7-specification-drafting]], [[written-description]], [[enablement]], [[best-mode]], [[utility]], [[specification-structure]]
- **更新頁面**：[[statute-35usc112]]（新增 CH7 來源參照）, index.md
- **備註**：CH7 涵蓋 §112 三大說明書要求（written description、enablement、best mode）及 utility 要求（§101），並提供說明書各節（Title → Abstract）的完整實務撰寫指南。關鍵洞見：說明書是「銷售文件」，避免使用 "the invention"，以 Theme 方法組織全文。

## [2026-04-11] ingest | Landis（Faber）CH3 — Apparatus or Machine Claims

- **來源**：`RAW/2024-Mechanics of Claim Drafting/Chap03-Apparatus or Machine Claims.pdf`（118 頁掃描版）及 `.md` 文字版
- **作者**：Robert C. Faber（*Landis on Mechanics of Patent Claim Drafting*, 8th ed., 2023）
- **新增頁面**：[[landis-ch03-apparatus-machine-claims]], [[apparatus-claims]]
- **更新頁面**：[[means-plus-function]]（source_count 1→2，全面增補 Williamson nonce word、軟體MPF、DOE vs MPF、single means、means at novelty）、index.md
- **備註**：本章（118頁）以 Shaker 裝置為貫穿範例，涵蓋 §3:1–§3:16。核心洞見：(1) 裝置請求項描述結構而非行為（"configured to" ✓，使用者動作 ✗）；(2) 所有元素必須「綁在一起」否則 aggregation 核駁；(3) "means for" 觸發 §112(f) 自動限縮；(4) *Williamson*（2015）nonce words 擴大 MPF 觸發範圍；(5) 軟體 MPF 必須在說明書揭露演算法。Faber 明確建議：**以具名元素 + "configured to" 替代 "means for"**，以避免 §112(f) 縮限而保留廣度。

## [2026-04-07] ingest | Landis（Faber）CH1 — Statutory Provisions and Some Basic Principles

- **來源**：`RAW/2024-Mechanics of Claim Drafting/Chap01-Statutory Provisions-Some Basic Principles.pdf`
- **作者**：Robert C. Faber（*Landis on Mechanics of Patent Claim Drafting*, 8th ed., 2023）
- **新增頁面**：[[landis-ch01-statutory-provisions]], [[claim-construction]], [[disavowal]], [[statutory-classes]]
- **更新頁面**：index.md
- **備註**：本章（48 頁掃描版 PDF）涵蓋 §1:1–§1:5。核心主題：(1) 請求項的雙重法定要求——point out & distinctly claim；(2) Omnibus Claim 在美國絕對禁止；(3) §101 四大法定類別與 *Alice* 適格性框架；(4) *Phillips* en banc 確立的 intrinsic-first 請求項解釋標準；(5) Disavowal——說明書中的限縮性語言（"The present invention requires..."）與審查歷史中的論述均可縮限請求項範圍，門檻為「明確且無歧義」。關鍵實務警示：優選實施例不自動限縮請求項；"The present invention is..." 語言危險。

## [2026-04-07] ingest | Landis（Faber）CH2 — Claim Forms and Formats in General

- **來源**：`RAW/2024-Mechanics of Claim Drafting/Chap02-Claim Forms and Formats in General.pdf`
- **作者**：Robert C. Faber（*Landis on Mechanics of Patent Claim Drafting*, 8th ed., 2023）
- **新增頁面**：[[landis-ch02-claim-forms-formats]], [[whereby-wherein-clauses]]
- **更新頁面**：[[preamble]]（source_count 1→2，新增 Catalina 五指標來源參照）、[[transition]]（source_count 1→2，新增 comprising 細節與 "having" 爭議）、[[antecedent-basis]]（source_count 1→2，新增 "a" vs "the"/"said" §2.13 分析）、index.md
- **備註**：本章（130 頁掃描版 PDF）以大量 Federal Circuit 判例為基礎，涵蓋 §2.1–§2.26：preamble 範圍限制（Catalina 五指標）、transition 精確法律效果（comprising 不等於完全開放）、"a" vs "the" 前提基礎、whereby/wherein 子句、數值範圍、Festo prosecution history estoppel 等。關鍵洞見：Faber 直言「use comprising, no other word works as well」，以及 "a" 在 comprising 請求項中代表「一個或多個」。

## [2026-04-06] ingest | Sheldon CH6 — Claim Drafting

- **來源**：`RAW/Sheldon/Sheldon-CH6_Claim Drafting.docx`
- **作者**：Jeffrey G. Sheldon, *How to Write a Patent Application*, Chapter 6 (2006)
- **新增頁面**：[[sheldon-ch6-claim-drafting]], [[preamble]], [[transition]], [[claim-body]], [[independent-claim]], [[dependent-claim]], [[means-plus-function]], [[antecedent-basis]], [[jepson-claim]], [[markush-group]], [[statute-35usc112]]
- **更新頁面**：index.md
- **備註**：首次 ingest，建立 1 份來源摘要、8 個概念頁、1 個實體頁。本章是請求項撰寫的全面指南，涵蓋形式結構（Preamble-Transition-Body）、請求項類型（獨立項、附屬項、Jepson、Markush、Product-by-Process）、撰寫策略（由寬到窄、Picture Claim 法）以及常見缺陷檢查。
