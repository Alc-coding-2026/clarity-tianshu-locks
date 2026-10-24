# Auditor's report — Emphasis of Matter (break-up / deregistration) / 強調事項（變現基礎／撤銷登記）

**Status:** **Allen invent LOCK 2026-10-24** (EN + 繁體中文). FILE ONLY until MERGE GO — do not republish public locks from this page until merged.  
**Approval:** [`review/approvals/2026-10-24-ar-eom-breakup.json`](../../review/approvals/2026-10-24-ar-eom-breakup.json)  
**Overturns:** prior house rule in [`dereg.md`](./dereg.md) / Note 2 page that forbade inventing a dereg EOM and said break-up is explained **only** in Note 2.  
**Ids:** `tianshu.ar.eom.break-up.en` / `tianshu.ar.eom.break-up.zh` (promoted from PR #10 proposed_from_legacy; no longer default OMIT).

## Rule

| Situation | Treatment |
| --- | --- |
| FS prepared on a **break-up** / 變現基礎 (cessation + intended Cap.622 s.750 deregistration) | **Include** this EOM in the AR |
| Clean going-concern unmodified / Path A (LOS in Note 2 only) | **Omit** — this module does not apply |
| Path B MURGC | Separate module — **not** this page |

**Hard rule (Allen):** The EOM **must not** say the FS are prepared on a break-up basis *rather than* a going-concern basis / 而非持續經營基礎. Do **not** use 「持續經營」 or “going concern” in this EOM. Point to **break-up / 變現基礎** and **Note 2** only.

**Disclosure home unchanged:** SoFP caption + Note 2 body stay at [`../05-notes/illustrative-dereg-breakup-basis.md`](../05-notes/illustrative-dereg-breakup-basis.md). This EOM **draws attention** to Note 2; it does not replace Note 2.

**Position:** After **Basis for Opinion** (or Basis for Qualified Opinion), before **Other Matter** / **Other information**.

**Opinion:** Unmodified (or otherwise applicable) opinion is **not modified** in respect of this matter.

---

## Wording / 文句

=== "English"

    ```text
    Emphasis of Matter — Basis of Accounting

    We draw attention to Note 2 to the financial statements, which explains that the Company ceased business operations on [CESSATION DATE] and the directors intend to apply for deregistration with the Companies Registry. Accordingly, the financial statements have been prepared on a break-up basis as described in Note 2. Our opinion is not modified in respect of this matter.
    ```

=== "繁體中文"

    ```text
    強調事項 — 編製基礎

    本核數師提請注意財務報表附註2。附註2說明貴公司已於[結業日期]停止業務營運，且董事擬向公司註冊處申請撤銷登記。因此，財務報表已按變現基礎編製，詳情載於附註2。本核數師之意見並不因此事項而有所修改。
    ```

### Placeholders

| Token | Fill from |
| --- | --- |
| `[CESSATION DATE]` / `[結業日期]` | Cessation / period-end date on the FS face and Note 2 |

Legacy `06-DERE.md` used “rather than on a going concern basis” / 「而非持續經營基礎」— **do not restore** that contrast. House invent omits it.

## Related

- Period wording: [`dereg.md`](./dereg.md)
- Unmodified shell: [`standard.md`](./standard.md)
- Note 2 + SoFP caption: [`../05-notes/illustrative-dereg-breakup-basis.md`](../05-notes/illustrative-dereg-breakup-basis.md)
- Pack index: [`../06-dereg.md`](../06-dereg.md)

## 中文摘要

**Allen 2026-10-24 發明鎖定（英＋繁中）。** 財務報表按變現基礎編製（結業並擬按第750條撤銷登記）時，核數師報告**須**加入本強調事項，提請注意附註2；意見不因此修改。**不得**寫「而非持續經營基礎」／rather than going concern。附註2及財務狀況表面的變現基礎披露維持不變；本段只作提請注意。FILE ONLY，待 MERGE GO 後方可公開 republish。
