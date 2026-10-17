# Auditor's report — unmodified (SME-FRS) shell / 獨立核數師報告 — 無保留意見（SME-FRS）殼段

**Status:** **Allen lock 2026-10-10** (EN + ZH).  
**Purpose:** House **unmodified** auditor's report shell that QO / Other Matter / dereg period modules **slot into**. Does **not** replace locked QO pages.  
**Face source (EN):** Allen-approved QCAC YE2026 specimen — `/workspace/approved-docx-amend-refs/QCAC_FS_20260331_YE_NL-no-revenue-1dir.docx` (AR body + section header).  
**Firm:** Clarity CPA & Co. (迦皓會計師事務所 on letterhead / cover as elsewhere).  
**Language:** English face is house authority. 繁體中文 locked with EN on 2026-10-10 (editorial house ZH, not an official HKICPA / CR translation).  
**Cover statutes:** Cap. 622 ss.405, 406, 409; HKSA 700 (Revised); other information / directors' report per HKSA 720 (Revised) as on the QCAC face.

### Lock status / 鎖定狀態

| Item | Draft uses | Note |
| --- | --- | --- |
| Framework full name | House QCAC / older 天書 form below | **Locked 2026-10-10** — see [`../00-house/framework-name.md`](../00-house/framework-name.md). |
| ZH full AR | Locked 繁體 below | Allen locked with EN 2026-10-10. |
| MURGC EOM / Path B | **Out of this shell** | Unmodified with material uncertainty related to going concern is a separate module — not invented here. Path A (LOS in Note 2 only) uses **this same shell** with no AR wording change. |
| Cap. 622 s.407(2)/(3) "Report on Other Matters" | **Omit on clean UQ** | Present only when a QO module requires it (records / bank completeness etc.). Not on QCAC unmodified face. |

### Related locked modules

- Optional Other Matter (predecessor): [`other-matter-predecessor.md`](./other-matter-predecessor.md) — **LOCKED optional, default OMIT**
- QO-A / B / C / D: [`qo-a-s369.md`](./qo-a-s369.md), [`qo-b-bank.md`](./qo-b-bank.md), [`qo-c-completeness.md`](./qo-c-completeness.md), [`qo-d-feupyc.md`](./qo-d-feupyc.md)
- Period / cessation wording: [`dereg.md`](./dereg.md)

### Assembly / 組裝

1. Title + addressee (on face or AR section header — QCAC puts it in the AR section header with firm letterhead).
2. **Opinion** (unmodified) → swap heading / opinion sentence only when a QO module applies.
3. **Basis for Opinion** (standards + ethics + evidence) → insert QO basis paragraphs **above** the standards sentence when qualified.
4. **Other Matter (predecessor)** — **optional, default omit** (see module).
5. **Other information** (HKSA 720) — directors' report as other information; "nothing to report" when clean.
6. **Responsibilities of directors and those charged with governance**.
7. **Auditor's responsibilities** (including Cap. 622 "solely to you, as a body" sentence as on QCAC).
8. **Do not** add Cap. 622 s.407 Report on Other Matters on this clean shell.
9. Practising-accountant line → firm block → Hong Kong → Date.
10. Replace every `[PLACEHOLDER]`. First-period / cessation: adapt "year ended" period wording per [`dereg.md`](./dereg.md) / DR Opening A — do not invent new AR policy here.

---

## Title and addressee / 標題及致送對象

QCAC places this block in the **AR section header** (with Clarity letterhead). Include it in the shell whether rendered as header or as the first lines of the report body.

=== "English"

    ```text
    INDEPENDENT AUDITOR'S REPORT
    TO THE MEMBERS OF [COMPANY NAME]
    (Incorporated in Hong Kong with limited liability)
    ```

=== "繁體中文"

    ```text
    獨立核數師報告
    致[公司名稱]全體成員
    （於香港註冊成立之有限公司）
    ```

---

## Opinion / 意見

=== "English"

    ```text
    Opinion

    We have audited the financial statements of [COMPANY NAME] (the "Company") as set out on pages [PAGE START] to [PAGE END] which comprise the statement of financial position as at [YEAR END DATE], and the income statement and statement of changes in equity for the year ended [YEAR END DATE], and notes to the financial statements, including a summary of significant accounting policies.

    In our opinion, the financial statements are prepared, in all material respects, in accordance with the Hong Kong Small and Medium-sized Entity Financial Reporting Standard ("SME-FRS") issued by the Hong Kong Institute of Certified Public Accountants ("HKICPA") and have been properly prepared in compliance with the Hong Kong Companies Ordinance.
    ```

=== "繁體中文"

    ```text
    意見

    本核數師已審計[公司名稱]（「貴公司」）載於第[頁起]至第[頁迄]頁之財務報表，此等財務報表包括於[年結日]之財務狀況表、截至[年結日]止年度之損益表及權益變動表，以及財務報表附註，包括主要會計政策概要。

    本核數師認為，該等財務報表已按照香港會計師公會（「香港會計師公會」）頒布之《香港中小型企業財務報告準則》（「SME-FRS」），在所有重大方面妥為編製，並已遵從香港《公司條例》妥為擬備。
    ```

**Framework-name note (EN):** The opinion sentence above is the **QCAC house face** form. It is used here only as the draft default. **Allen's separate lock of the full framework string still controls** FS, AR, engagement letter and representation letter.

**Period note:** For a first or non-annual period, replace "for the year ended [YEAR END DATE]" with the actual period wording (see [`dereg.md`](./dereg.md) / DR Opening A). Do not change the opinion criteria sentence solely because the period is non-annual.

---

## Basis for Opinion / 意見基礎

=== "English"

    ```text
    Basis for Opinion

    We conducted our audit in accordance with Hong Kong Standards on Auditing ("HKSAs") and with reference to Practice Note 900 (Revised), Audit of Financial Statements Prepared in Accordance with the Small and Medium-sized Entity Financial Reporting Standard issued by the HKICPA. Our responsibilities under those standards are further described in the Auditor's Responsibilities for the Audit of the Financial Statements section of our report. We are independent of the Company in accordance with the HKICPA's Code of Ethics for Professional Accountants ("the Code"), and we have fulfilled our other ethical responsibilities in accordance with the Code. We believe that the audit evidence we have obtained is sufficient and appropriate to provide a basis for our opinion.
    ```

=== "繁體中文"

    ```text
    意見基礎

    本核數師按照香港會計師公會頒布之《香港審計準則》（「香港審計準則」），並參照香港會計師公會頒布之《實務說明第900號（經修訂）－按照〈中小型企業財務報告準則〉編製的財務報表的審計》進行審計。本核數師在該等準則下之責任於本報告「核數師就審計財務報表承擔的責任」部分進一步闡述。按照香港會計師公會之《專業會計師道德守則》（「守則」），本核數師獨立於貴公司，並已履行守則規定之其他道德責任。本核數師相信，所獲取之審計憑證屬充分及適當，可為本核數師之意見提供基礎。
    ```

When a **qualified** opinion applies: change the section heading to **Basis for Qualified Opinion** / **保留意見基礎**, insert the locked QO basis paragraph(s) **before** the standards sentence above, and adjust the Opinion section per the QO module. This shell stays the carrier; QO pages supply only the modification text.

---

## Other Matter (predecessor auditor) — OPTIONAL / 其他事項（前任核數師）— 可選

**Rule:** Locked at [`other-matter-predecessor.md`](./other-matter-predecessor.md). **Default: OMIT.** Omitting is not a pack gap. Include only when prior-year FS were audited by a predecessor and the PY opinion was unmodified, and the preparer/partner elects to include.

**Position:** After **Basis for Opinion**, before **Other information** (QCAC has no Other Matter; locked module places it after Basis and before Directors' responsibilities — if Other information is present, keep Other Matter after Basis and before Other information so the HKSA 710 paragraph sits with the opinion block).

=== "English"

    ```text
    Other Matter

    The financial statements of the Company for the year ended [PRIOR YEAR END DATE] were audited by another auditor who expressed an unmodified opinion on those financial statements.
    ```

=== "繁體中文"

    ```text
    [NO APPROVED ZH — locked module is English only. Do not invent Chinese for this paragraph; raise to Allen if a Chinese AR needs it.]
    ```

---

## Other information / 其他資料（HKSA 720）

On the QCAC unmodified face. Keep when the pack includes a directors' report (house normal).

=== "English"

    ```text
    Information other than the financial statements and auditor's report thereon

    The directors of the Company are responsible for the other information. The other information comprises all information included in the report of directors, but does not include the financial statements and our auditor's report thereon.

    Our opinion on the financial statements does not cover the other information and we do not express any form of assurance conclusion thereon.

    In connection with our audit of the financial statements, our responsibility is to read the other information and, in doing so, consider whether the other information is materially inconsistent with the financial statements or our knowledge obtained in the audit or otherwise appears to be materially misstated. If, based on the work we have performed, we conclude that there is a material misstatement of this other information, we are required to report that fact. We have nothing to report in this regard.
    ```

=== "繁體中文"

    ```text
    財務報表及核數師報告以外的資料

    貴公司董事須對其他資料負責。其他資料包括董事報告所載之所有資料，但不包括財務報表及本核數師就此發出之核數師報告。

    本核數師對財務報表之意見並不涵蓋其他資料，本核數師亦不對該等其他資料發表任何形式的鑒證結論。

    就本核數師對財務報表之審計而言，本核數師之責任是閱讀其他資料，在此過程中考慮其他資料是否與財務報表或本核數師在審計過程中所了解的情況存在重大不一致，或似乎存在重大錯誤陳述。基於本核數師已執行的工作，倘本核數師認為該其他資料存在重大錯誤陳述，則須報告該事實。在此方面，本核數師沒有任何報告。
    ```

---

## Responsibilities of directors and those charged with governance / 董事及治理層就財務報表須承擔的責任

QCAC includes the oversight sentence ("Those charged with governance…"). Keep it on this draft shell to match the house face (including sole-director specimens). Do not treat its presence as a defect.

=== "English"

    ```text
    Responsibilities of directors and those charged with governance for the financial statements

    The directors of the Company are responsible for the preparation of the financial statements in accordance with the SME-FRS issued by the HKICPA and the Hong Kong Companies Ordinance, and for such internal control as the directors determine is necessary to enable the preparation of financial statements that are free from material misstatement, whether due to fraud or error.

    In preparing the financial statements, the directors are responsible for assessing the Company's ability to continue as a going concern, disclosing, as applicable, matters related to going concern and using the going concern basis of accounting unless the directors either intend to liquidate the Company or to cease operations, or have no realistic alternative but to do so.

    Those charged with governance are responsible for overseeing the Company's financial reporting process.
    ```

=== "繁體中文"

    ```text
    董事及治理層就財務報表須承擔的責任

    貴公司董事須負責按照香港會計師公會頒布之 SME-FRS 及香港《公司條例》編製財務報表，並對其認為為使財務報表的編製不存在由於欺詐或錯誤而導致的重大錯誤陳述所必需的內部控制負責。

    在編製財務報表時，董事負責評估貴公司持續經營的能力，並在適用情況下披露與持續經營有關的事項，以及使用持續經營為會計基礎，除非董事有意將貴公司清盤或停止經營，或別無其他實際的替代方案。

    治理層負責監督貴公司的財務報告過程。
    ```

---

## Auditor's responsibilities / 核數師就審計財務報表承擔的責任

Matches QCAC: Cap. 622 "solely to you, as a body" sentence; HKSAs bullets including internal control and going-concern conclude; communication with those charged with governance. No "overall presentation / fair presentation" bullet (compliance framework / SME-FRS — as on face).

=== "English"

    ```text
    Auditor's responsibilities for the audit of the financial statements

    Our objectives are to obtain reasonable assurance about whether the financial statements as a whole are free from material misstatement, whether due to fraud or error, and to issue an auditor's report that includes our opinion solely to you, as a body, in accordance with the Hong Kong Companies Ordinance, and for no other purposes. We do not assume responsibility towards or accept liability to any other person for the contents of this auditor's report.

    Reasonable assurance is a high level of assurance, but is not a guarantee that an audit conducted in accordance with HKSAs will always detect a material misstatement when it exists. Misstatements can arise from fraud or error and are considered material if, individually or in the aggregate, they could reasonably be expected to influence the economic decisions of users taken on the basis of these financial statements.

    As part of an audit in accordance with HKSAs, we exercise professional judgment and maintain professional skepticism throughout the audit. We also:

    - Identify and assess the risks of material misstatement of the financial statements, whether due to fraud or error, design and perform audit procedures responsive to those risks, and obtain audit evidence that is sufficient and appropriate to provide a basis for our opinion. The risk of not detecting a material misstatement resulting from fraud is higher than for one resulting from error, as fraud may involve collusion, forgery, intentional omissions, misrepresentations, or the override of internal control.

    - Obtain an understanding of internal control relevant to the audit in order to design audit procedures that are appropriate in the circumstances, but not for the purpose of expressing an opinion on the effectiveness of the Company's internal control.

    - Evaluate the appropriateness of accounting policies used and the reasonableness of accounting estimates and related disclosures made by the directors.

    - Conclude on the appropriateness of the directors' use of the going concern basis of accounting and, based on the audit evidence obtained, whether a material uncertainty exists related to events or conditions that may cast significant doubt on the Company's ability to continue as a going concern. If we conclude that a material uncertainty exists, we are required to draw attention in our auditor's report to the related disclosures in the financial statements or, if such disclosures are inadequate, to modify our opinion. Our conclusions are based on the audit evidence obtained up to the date of our auditor's report. However, future events or conditions may cause the Company to cease to continue as a going concern.

    We communicate with those charged with governance regarding, among other matters, the planned scope and timing of the audit and significant audit findings, including any significant deficiencies in internal control that we identify during our audit.
    ```

=== "繁體中文"

    ```text
    核數師就審計財務報表承擔的責任

    本核數師之目標，是對財務報表整體是否不存在由於欺詐或錯誤而導致的重大錯誤陳述取得合理保證，並按照香港《公司條例》僅向 閣下（作為整體）出具包括本核數師意見的核數師報告，除此以外，本報告別無其他目的。本核數師不會就本報告的內容向任何其他人士負上或承擔任何責任。

    合理保證是高水平的保證，但不能保證按照《香港審計準則》進行的審計，在某一重大錯誤陳述存在時總能發現。錯誤陳述可以由欺詐或錯誤引起，如果合理預期它們單獨或滙總起來可能影響財務報表使用者依賴財務報表所作出的經濟決定，則有關的錯誤陳述可被視作重大。

    在根據《香港審計準則》進行審計的過程中，本核數師運用了專業判斷，保持了專業懷疑態度。本核數師亦：

    - 識別和評估由於欺詐或錯誤而導致財務報表存在重大錯誤陳述的風險，設計及執行審計程序以應對這些風險，以及獲取充分和適當的審計憑證，作為本核數師意見的基礎。由於欺詐可能涉及串謀、偽造、蓄意遺漏、虛假陳述，或凌駕於內部控制之上，因此未能發現因欺詐而導致的重大錯誤陳述的風險高於未能發現因錯誤而導致的重大錯誤陳述的風險。

    - 了解與審計相關的內部控制，以設計適當的審計程序，但目的並非對貴公司內部控制的有效性發表意見。

    - 評價董事所採用會計政策的恰當性及作出會計估計和相關披露的合理性。

    - 對董事採用持續經營會計基礎的恰當性作出結論，並根據所獲取的審計憑證，確定是否存在與事項或情況有關的重大不確定性，從而可能導致對貴公司的持續經營能力產生重大疑慮。如果本核數師認為存在重大不確定性，則有必要在核數師報告中提請使用者注意財務報表中的相關披露。假若有關的披露不足，則本核數師應當發表非無保留意見。本核數師的結論是基於核數師報告日止所取得的審計憑證。然而，未來事項或情況可能導致貴公司不能持續經營。

    本核數師與治理層溝通了計劃的審計範圍、時間安排、重大審計發現等，包括本核數師在審計中識別出內部控制的任何重大缺陷。
    ```

---

## Report on other matters under Cap. 622 — not part of this clean shell

**Unmodified QCAC face has no** "Report on Other Matters under sections 407(2) and 407(3) of the Hong Kong Companies Ordinance" block.

Add that block **only** when a locked QO module requires it (e.g. records / completeness limitations). Wording lives on the QO pages, not here.

Cap. 622 ss.405 / 406 / 409 duties for a clean opinion are met by the Opinion + Basis + responsibilities + signature structure above; do not invent an extra Cap. 622 section for unmodified reports.

---

## Signature / practising certificate block / 簽署及執業證書

QCAC house face (Clarity CPA & Co.):

=== "English"

    ```text
    The practising accountant who signs this independent auditor's report is CHAN Tsz San (Practising Certificate number: P07945).

    Clarity CPA & Co.
    Certified Public Accountants
    Hong Kong
    Date: [REPORT DATE]
    ```

=== "繁體中文"

    ```text
    簽署本獨立核數師報告之執業會計師為陳梓燊（執業證書編號：P07945）。

    Clarity CPA & Co.
    執業會計師
    香港
    日期：[報告日期]
    ```

**Firm name:** Always **Clarity CPA & Co.** for this shell (matches QCAC / Budsilver faces). Do not substitute a sole-practice variant here unless Allen opens a separate lock.

---

## What this shell is not / 本殼段不包括

| Topic | Treatment |
| --- | --- |
| Qualified Opinion paragraphs | Use locked QO-A/B/C/D modules; change Opinion / Basis headings |
| Cap. 622 s.407 Report on Other Matters | Only with applicable QO |
| MURGC Emphasis of Matter | Separate Path B module — **not drafted here** |
| Break-up / dereg EOM | See [`dereg.md`](./dereg.md) — no locked dereg EOM body; do not invent |
| Engagement letter / representation letter | AUDIT MANAGER / AutoFS templates — out of 天書 AR shell |

---

## 中文摘要

**Allen lock 2026-10-10（英＋繁中）。** 此頁為無保留意見獨立核數師報告殼段（英＋編輯繁中），以 QCAC YE2026 英文樣本為準。準則全名已於 2026-10-10 鎖定。前任核數師「其他事項」為可選、預設省略。清潔無保留意見面不附《公司條例》第407(2)/(3)條「其他事項」報告；該段僅在相關保留意見模組要求時加入。簽署行為 Clarity CPA & Co.／陳梓燊 P07945。
