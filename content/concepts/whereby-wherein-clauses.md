---
type: concept
title: Whereby / Wherein 子句
aliases: [whereby clause, wherein clause, whereby子句, wherein子句]
tags: [claim-language, functional-language, 請求項語言]
source_count: 1
---

# Whereby / Wherein 子句

## 定義

**Whereby 子句**與 **Wherein 子句**是請求項主體中用於進一步描述功能關係或限制條件的從屬子句，兩者在法律效果上有重要差異。

## 詳細說明

### Whereby 子句（§2.18）

**正確用法**：描述由前述結構或步驟**必然產生**的功能結果。

```
A device comprising:
   a first member; and
   a second member connected to the first member,
   whereby the device can be folded flat.
```

**法律效果**：
- 若 whereby 描述的是前述結構必然帶來的結果 → **構成請求項限制**
- 若只是重複已知後果、未帶來新的技術特徵 → **法院可能不給予限制效果**
- 不可用 whereby 子句**引入新的結構性限制**（應放在 body 中）

**不當用法**：
```
❌ ...whereby a motor drives a gear...
（「motor drives gear」應在 body 中以結構性語言描述，
而非隱藏在 whereby 子句中）
```

**Thereby 子句**：意義與 whereby 相近，意指「由此」，法律效果相同。

### Wherein 子句（§2.19）

用於進一步**限制或描述已引入的元素**，通常加在請求項最後或某元素描述之後。

```
A method comprising:
   heating a composition to a temperature,
   wherein the temperature is from 60°C to 70°C.
```

**注意事項**：
- Wherein 所限定的元素必須已有**前提基礎**（已用 "a/an" 引入）
- Wherein 子句**是**真正的請求項限制（不同於 whereby 可能被虛化）
- 常用於數值範圍、材料規格等附加限制

### 比較表

| 子句 | 典型用途 | 是否為限制 |
|------|----------|-----------|
| **Whereby** | 描述必然產生的功能結果 | 視情況——若是必然結果則是；若是可選結果則否 |
| **Thereby** | 同上，更常用於方法請求項 | 同上 |
| **Wherein** | 進一步限制已引入的元素 | 是，明確的限制 |

## 來源參照
- [[landis-ch02-claim-forms-formats]]：§2.18 whereby/thereby、§2.19 wherein 的詳細討論與判例

## 相關概念
- [[claim-body]]：whereby/wherein 子句置於 body 的末尾
- [[functional-language]]：whereby 子句是功能性語言的一種形式
- [[antecedent-basis]]：wherein 子句中的元素必須有前提基礎

## 實務要點

1. **Whereby 子句用於結論性功能描述**，確保該功能確實是前述結構的必然結果
2. **不要用 whereby 隱藏關鍵結構**——結構性元素應明確列在 body 中
3. **Wherein 子句是可靠的限制工具**，適合加入數值範圍或材料限制
4. 在獨立項中謹慎使用 whereby——審查員可能質疑其是否構成真正限制
