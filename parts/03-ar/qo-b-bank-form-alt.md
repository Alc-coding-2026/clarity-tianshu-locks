# AR-QO-B Form Alt — Bank confirmation letter (no confirmation received)

> **Allen LOCK+MERGE 2026-11-04 (HKT).** Soft invent default remains locked B+C.
>
> Accepted Form **when Allen elects it** — **not** the default. Do not replace the locked basis in [`qo-b-bank.md`](./qo-b-bank.md).

**Pairs with:** [`qo-c-revenue-cash-basis-form-alt.md`](./qo-c-revenue-cash-basis-form-alt.md) (revenue and cost of sales, cash basis).

**Default (unchanged):** locked [`qo-b-bank.md`](./qo-b-bank.md) — direct confirmation not obtained; always retain bank balances, bank borrowings and contingent liabilities. This Alt is a different Form (no confirmation letter received; completeness, validity, and disclosure). It does not retire that lock.

**S.407:** REQUIRED (same as locked QO-B / QO-C). Use the locked paragraph in [`qo-c-completeness.md`](./qo-c-completeness.md) § S.407. Do not omit it because this Alt was elected.

**RL:** Qualified Opinion Acknowledgement REQUIRED (same as locked QO-B / QO-C). No new RL body is filed here.

**Date:** source example said 31 March 2026. Filed wording uses **[YE DATE]** / **[年結日]**. Do not hardcode that year-end.

## Source as pasted (substance)

```
Due to no bank confirmation received by us. We are therefore unable to verify the bank balances, loans and contingent liabilities in relation to this bank as to their completeness and validity and whether proper disclosures were made to the financial statements. There were no other satisfactory audit procedures that we could adopt to confirm that bank balances, bank loans and contingent liabilities at 31 March 2026 was properly recorded and disclosed in the financial statements.
```

## Basis paragraph — EN (house cleanup)

Light grammar only. Substance unchanged. This is the electable paragraph.

```
Due to no bank confirmation having been received by us, we are therefore unable to verify the bank balances, loans and contingent liabilities in relation to this bank as to their completeness and validity and whether proper disclosures were made in the financial statements. There were no other satisfactory audit procedures that we could adopt to confirm that bank balances, bank loans and contingent liabilities at [YE DATE] were properly recorded and disclosed in the financial statements.
```

House cleanup:

- Fragment “Due to no bank confirmation received by us.” joined as “Due to no bank confirmation having been received by us,”. “we are therefore unable” kept.
- “made to the financial statements” → “made in the financial statements”.
- “31 March 2026 was” → “[YE DATE] were” (placeholder; plural subject).

Kept from the source, and distinct from locked QO-B: “loans” / “bank loans”, “this bank”, “completeness and validity”, “proper disclosures”, “properly recorded and disclosed”. Locked QO-B’s “bank borrowings” and “any adjustments might be necessary” are **not** this Form.

## 保留意見基礎 — 中文（編輯譯文 / editorial）

**Editorial mirror only.** Not an Allen lock and not an HKICPA official translation. Meaning follows the cleaned EN above.

```
由於本核數師未接獲銀行確認書，因此未能核實與該銀行有關之銀行結餘、貸款及或然負債之完整性及有效性，以及財務報表是否已作出適當披露。除此以外，並無其他可予採納之滿意審計程序，以確認於[年結日]之銀行結餘、銀行貸款及或然負債已於財務報表內妥為記錄及披露。
```

## Stacking

| Election | Basis |
| --- | --- |
| Neither Alt (default) | Locked QO-B + locked QO-C. Soft invent stays there. |
| This Alt only | This paragraph replaces the locked QO-B basis only. QO-C stays on [`qo-c-completeness.md`](./qo-c-completeness.md) unless that Alt is also elected. |
| Both Alts | One Basis for Qualified Opinion. Number **1** this bank paragraph, **2** the cash-basis revenue and cost of sales paragraph. |

When both Alts are used:

```
BASIS FOR QUALIFIED OPINION

1. Due to no bank confirmation having been received by us, we are therefore unable to verify the bank balances, loans and contingent liabilities in relation to this bank as to their completeness and validity and whether proper disclosures were made in the financial statements. There were no other satisfactory audit procedures that we could adopt to confirm that bank balances, bank loans and contingent liabilities at [YE DATE] were properly recorded and disclosed in the financial statements.

2. Revenue and cost of sales were recorded only on a cash basis, over which there was no system of internal control upon which we could rely for the purpose of our audit. There were no other satisfactory audit procedures that we could adopt to satisfy ourselves that the recorded revenue and cost of sales were free from material misstatements.
```

AR header when numbered 1 and 2: same locked stack phrase as QO-B + QO-C — “except for the possible effects of the matters described in paragraphs 1 and 2”.

**S.407 still REQUIRED** for this Alt alone and for the 1/2 stack (same as locked B+C). **RL Qualified Opinion Acknowledgement still REQUIRED.**
