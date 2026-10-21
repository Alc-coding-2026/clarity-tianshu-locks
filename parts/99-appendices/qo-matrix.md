# QO decision matrix

Live: https://siumon.eternalorigins.net/tianshu/99-appendices/qo-matrix/

> **Branch note (FILE ONLY / PROPOSED until Allen MERGE GO):** rows **B** and **E** added on `tianshu/qo-inventory-take-and-matrix-b`. Existing A / A-369 / A-records / D-1 rows and mid-life lock sentence unchanged. Do not treat B/E as locked until Allen GOs.

| Code | Situation | S.407 |
| --- | --- | --- |
| A | Period >18m + Records | Yes |
| A (369 only) | Period >18m only | No |
| A (records only) | Records incomplete | Yes |
| B | Bank confirmation not obtained | Yes |
| D-1 | FEUPYC, records OK | No |
| E (Inv) | Physical inventory not observed / inventory take | No |

Essential: “S.407 is REQUIRED for records/completeness, NOT required for pure FEUPYC D-1.”

**PROPOSED add-on (E):** Pure physical-inventory observation limitation (records otherwise OK) → S.407 **No**; stack with records/completeness → S.407 **Yes**. See `parts/03-ar/qo-inventory-take-draft.md`.

**PROPOSED add-on (B):** Bank confirmation not obtained, including bank-only → S.407 **Yes** (locked `qo-b-bank.md` + PR #10 proposed INCLUDE rule).

**Allen lock:** mid-life catch-up QUALIFIED (prior audited then multi-year unaudited gap) **includes** s.407 OM. Pure D-1 still omits.