# Inventories disclosure note / 存貨披露附註

**Allen lock 2026-10-02.** EN + editorial 繁體中文. Chinese is **not** an official HKICPA translation.  
Inventories **disclosure** note (not Note 2 policy). Default module **INV-T**; **INV-D** optional. Note numbers remain **`[N]`** placeholders.

**Scope / 適用：** Eligible SME-FRS Hong Kong private company limited by shares; company-level; normal annual period.  
符合 SME-FRS 資格之香港私人股份有限公司；公司層面；正常年度。

**SoFP face caption (locked 2026-09-19):** **Inventories**  
**財務狀況表面列標題（2026-09-19 鎖定）：** **存貨**

**Not this page / 不屬本頁：**
- **Accounting policy** (lower of cost and NRV; FIFO / weighted average) stays on locked Note 2: [illustrative-inventory-tax-policies.md](./illustrative-inventory-tax-policies.md).  
  **會計政策**（成本與可變現淨值較低者；先進先出／加權平均）留在已鎖定附註2。
- **Income tax** Note 5 format is locked separately — **untouched**.  
  **所得稅** Note 5 已另行鎖定 — 本草稿**不改動**。
- This is a **disclosure note**, not Note 2 policy wording.  
  本頁為**披露附註**，不是附註2政策文句。

---

## Rules / 選用規則

- **Omit the entire note** when Inventories is **nil** on the SoFP (both dates) — do not keep a nil inventories note by default.  
  財務狀況表存貨**為零**（兩個日期）時**省略整則附註** — 預設不保留「無存貨」附註。
- Include when Inventories is live on the SoFP.  
  財務狀況表有存貨時納入。
- **Default module: INV-T** (single total). Use **INV-D** (category breakdown) only when a category split is useful.  
  **預設模組：INV-T**（單一合計）。僅於分類拆分有用時使用 **INV-D**（分類明細）。
- Note number remains **`[N]`** until a later house-sequence lock.  
  附註編號維持 **`[N]`**，待其後編定套裝次序。
- Measurement reminder in the note (lower of cost / NRV) is a short cross-check only — full policy remains in locked Note 2.  
  附註內「成本與可變現淨值較低者」僅作簡短覆核 — 完整政策仍見已鎖定附註2。
- Tie the note total to the SoFP **Inventories** face amount.  
  附註合計須與財務狀況表「存貨」面列核對。

---

## Situation map / 情況對照

| Code | Module | 模組 | Use when |
| --- | --- | --- | --- |
| **INV-T** | Inventories — single total (**default**) | 存貨 — 單一合計（**預設**） | Inventories live (usual) |
| **INV-D** | Inventories disclosure — categories (**optional**) | 存貨披露 — 分類（**可選**） | Category split useful |
| **INV-X** | Omit | 省略 | Nil on SoFP (both dates) |

---

## INV-D — Category breakdown (**optional**) / 分類明細（**可選**）

### English

```
[N]. INVENTORIES

| | [CY] | [PY] |
|:---|---:|---:|
| Raw materials | [XXX,XXX] | [XXX,XXX] |
| Work in progress | [XXX,XXX] | [XXX,XXX] |
| Finished goods | [XXX,XXX] | [XXX,XXX] |
| Merchandise / goods for resale | [XXX,XXX] | [XXX,XXX] |
| | --------- | --------- |
| Inventories | [XXX,XXX] | [XXX,XXX] |
| | ========= | ========= |

Inventories are stated at the lower of cost and net realisable value
(see Note 2 — Inventories).
```

### 中文

```
[N]. 存貨

| | [本年度] | [上年度] |
|:---|---:|---:|
| 原材料 | [XXX,XXX] | [XXX,XXX] |
| 在製品 | [XXX,XXX] | [XXX,XXX] |
| 製成品 | [XXX,XXX] | [XXX,XXX] |
| 商品／待轉售貨品 | [XXX,XXX] | [XXX,XXX] |
| | --------- | --------- |
| 存貨 | [XXX,XXX] | [XXX,XXX] |
| | ========= | ========= |

存貨按成本與可變現淨值兩者之較低者列賬（見附註2 — 存貨）。
```

**Notes / 備註**
- Delete unused category rows; do not leave blank specimen labels in issued FS.  
  刪除不適用分類列；已發出財務報表不得留下空白標本標籤。
- If a write-down to NRV is material and disclosed elsewhere (e.g. PBT draft), reconcile — do not double-count.  
  若撇減至可變現淨值屬重大並已於他處披露（例如 PBT 草稿），須核對 — 勿重複計算。
- Cost formula (FIFO / weighted average) is chosen in locked Note 2 — do not restate the formula choice here unless Allen later requires it.  
  成本公式於已鎖定附註2選定 — 除非 Allen 其後要求，否則本附註不重述公式選擇。

---

## INV-T — Single total (**default**) / 單一合計（**預設**）

### English

```
[N]. INVENTORIES

| | [CY] | [PY] |
|:---|---:|---:|
| Inventories | [XXX,XXX] | [XXX,XXX] |
| | ========= | ========= |

Inventories are stated at the lower of cost and net realisable value
(see Note 2 — Inventories).
```

### 中文

```
[N]. 存貨

| | [本年度] | [上年度] |
|:---|---:|---:|
| 存貨 | [XXX,XXX] | [XXX,XXX] |
| | ========= | ========= |

存貨按成本與可變現淨值兩者之較低者列賬（見附註2 — 存貨）。
```

---

## INV-X — Omit when nil / 為零時省略

**Omit the note.** Do not insert a “The Company had no inventories…” sentence by default.  
**省略本附註。** 預設不加入「本公司並無存貨…」一句。

---

## Related / 相關

- Locked Note 2 inventories & tax **policies**: [illustrative-inventory-tax-policies.md](./illustrative-inventory-tax-policies.md)
- SoFP face: [../04-fs/financial-position-draft.md](../04-fs/financial-position-draft.md)
- PBT after-charging draft (inventory provision row, if used): [illustrative-profit-disclosures.md](./illustrative-profit-disclosures.md)
- Income tax Note 5 (locked — untouched): [illustrative-income-tax.md](./illustrative-income-tax.md)

---

??? note "使用及來源 / Application and sources"

    **Allen lock 2026-10-02.** Inventories **disclosure** note (not Note 2 policy). Default **INV-T**; **INV-D** optional. Aligns to locked SoFP caption **Inventories**. Omit when nil on SoFP. Policy points to locked `illustrative-inventory-tax-policies.md`.

    **Allen 鎖定 2026-10-02。** 存貨**披露**附註（非附註2政策）。預設 **INV-T**；**INV-D** 可選。對齊已鎖定財務狀況表「存貨」。面列為零時省略。政策指向已鎖定存貨稅項政策頁。
