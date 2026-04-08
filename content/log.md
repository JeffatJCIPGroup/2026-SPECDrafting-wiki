# 操作日誌

> 按時間順序記錄所有 Wiki 操作。由 LLM 自動維護。
> 查詢最近 5 筆紀錄：`grep "^## \[" wiki/log.md | tail -5`

---

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
