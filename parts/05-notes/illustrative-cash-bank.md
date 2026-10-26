# Cash and bank balances / 現金及銀行結餘

**Allen lock 2026-10-02.** EN + editorial 繁體中文. Chinese is **not** an official HKICPA translation.  
Cash and bank balances disclosure. Note numbers remain **`[N]`** placeholders.

**Scope / 適用：** Eligible SME-FRS Hong Kong private company limited by shares; company-level; normal annual period.  
符合 SME-FRS 資格之香港私人股份有限公司；公司層面；正常年度。

**SoFP face caption (locked 2026-09-19):** **Cash and bank balances**  
**財務狀況表面列標題（2026-09-19 鎖定）：** **現金及銀行結餘**

**Not this page / 不屬本頁：**
- Amounts **due from/to** related parties stay in locked **Notes 13/15** — do **not** reclassify dues as cash.  
  應收／應付關聯方款項留在已鎖定 **Notes 13/15** — **勿**改列為現金。
- Restricted cash / bank overdraft presentation: fact-specific; do not invent a house default beyond this draft.  
  受限制現金／銀行透支呈列：按事實處理；本草稿不另設行內預設。

---

## Rules / 選用規則

- Include when **Cash and bank balances** is live on the SoFP.  
  財務狀況表有**現金及銀行結餘**時納入。
- Note number remains **`[N]`** (wiki ancestry **N-14**) until a later house-sequence lock.  
  附註編號維持 **`[N]`**（wiki 先祖 **N-14**），待其後編定套裝次序。
- Tie the note total to the SoFP face amount (CY and PY).  
  附註合計須與財務狀況表面列金額核對（本年度及上年度）。
- Omit empty component rows only when that component is nil **and** house practice for the pack allows; otherwise show `nil` / `無`.  
  僅於該分項為零**且**該套裝實務允許時刪列；否則列示 `nil`／`無`。

---

## Situation map / 情況對照

| Code | Module | 模組 | Use when |
| --- | --- | --- | --- |
| **CB-A** | Cash and bank — breakdown | 現金及銀行 — 明細 | Standard SoFP line present (usual) |
| **CB-S** | Single-line only | 僅一行合計 | Breakdown not meaningful / immaterial — rare; prefer CB-A |

---

## CB-A — Breakdown (wiki N-14 shape) / 明細（wiki N-14 形）

### English

```
[N]. CASH AND BANK BALANCES

| | [CY] | [PY] |
|:---|---:|---:|
| Cash at bank | [XXX,XXX] | [XXX,XXX] |
| Cash on hand | [X,XXX] | [X,XXX] |
| | --------- | --------- |
| Cash and bank balances | [XXX,XXX] | [XXX,XXX] |
| | ========= | ========= |
```

### 中文

```
[N]. 現金及銀行結餘

| | [本年度] | [上年度] |
|:---|---:|---:|
| 銀行結存 | [XXX,XXX] | [XXX,XXX] |
| 手頭現金 | [X,XXX] | [X,XXX] |
| | --------- | --------- |
| 現金及銀行結餘 | [XXX,XXX] | [XXX,XXX] |
| | ========= | ========= |
```

**Notes / 備註**
- Total row caption matches locked SoFP **Cash and bank balances** / **現金及銀行結餘**.  
  合計列標題須與已鎖定財務狀況表一致。
- Add foreign-currency bank lines only when material and live.  
  僅於重大且實際存在時另加外幣銀行戶口列。

---

## CB-S — Face total only (optional) / 僅面列合計（可選）

### English

```
[N]. CASH AND BANK BALANCES

Cash and bank balances comprise cash at bank and cash on hand.
```

### 中文

```
[N]. 現金及銀行結餘

現金及銀行結餘包括銀行結存及手頭現金。
```

Use only when house practice accepts a narrative without a schedule; otherwise prefer **CB-A**.  
僅於行內實務接受無附表敘述時使用；否則優先 **CB-A**。

---

## Related / 相關

- SoFP face: [../04-fs/financial-position-draft.md](../04-fs/financial-position-draft.md)
- Notes 13/15 (dues, not cash): [illustrative-accounts-receivables-payables.md](./illustrative-accounts-receivables-payables.md)
- Investments (separate): [illustrative-investments.md](./illustrative-investments.md)

---

??? note "使用及來源 / Application and sources"

    **Allen lock 2026-10-02.** SoFP-friendly cash and bank disclosure note (wiki N-14 ancestry).

    **Allen 鎖定 2026-10-02。** 財務狀況表友好之現金及銀行披露附註（wiki N-14 先祖）。

    **Wiki template ancestry:** `wiki/docs/index.md` N-14; `wiki/docs/05-notes/n13-15-current.md` Note 14.

    Prefer bilingual pattern (`### English` / `### 中文`) consistent with investment and commitments drafts.
