# 正常／首份期間董事報告（標準版） / Normal / first-period directors’ report (house standard)

**Status:** **LOCKED UPGRADED 2026-10-02** (Allen). House **standard** statutory directors’ report for the SME-FRS normal-company pack, upgraded to match Allen’s two live common Clarity specimens.  
EN + editorial 繁體中文 (**Allen approved ZH 2026-10-02**). Chinese is **not** an official HKICPA / CR translation.  
**Approval:** [`review/approvals/2026-10-02-normal-dr-standard.json`](../../review/approvals/2026-10-02-normal-dr-standard.json)  
**Alias:** pack / AutoFS checks may resolve this as [`standard.md`](./standard.md) (pointer to this locked specimen). Filename `normal-sme-shares-draft.md` kept for history.

HKCO reporting-exemption private company limited by shares · SME-FRS · no subsidiaries · company-level **going-concern** report (normal annual **or** first / multi-period from incorporation to year-end).  
**Not for:** guarantee company, consolidated report, dormant company (draft: [dormant-sme-shares-draft.md](./dormant-sme-shares-draft.md) — pending Allen lock), deregistration or liquidation (use locked [Case 4 dereg DR](./case4-dereg.md) where that path applies).  
Eligibility and use of the reporting exemption for the actual year/period must be documented separately; “SME” in a company description is insufficient.

適用於已核實於相關年度／期間採用提交報告豁免的香港私人股份有限公司，按 SME-FRS 擬備公司層面持續經營報表（正常年度或由成立日至年結日的首份／多年期間），且沒有附屬企業。中文為編輯譯稿，並非官方範本。措辭已於 2026-10-02 按 Allen 兩份實務樣本升級鎖定。

### Source note / 來源說明

HKICPA SME-FRF & SME-FRS **Appendix 2 / 3** contains **no** directors’ report specimen. This lock is the Clarity house modular DR assembled to match Allen’s pasted live specimens (first-period Specimen A; normal-year Specimen B), still grounded in Cap. 622 / Cap. 622D (see [normal-dr-provenance.md](../review/pilot-pack/normal-dr-provenance.md)). Sample-book FS wording was **not** copied. Cap. 622 positive-trigger modules remain available as alternatives to the verified-nil shells.

示例書附錄2／3 **沒有**董事報告範例；本鎖定版按 Allen 兩份實務樣本（首份期間 A；正常年度 B）組裝，並保留 Cap. 622 觸發時的正面披露模組作為「已核實概無」殼段的替代。

## Assembly decisions / 組合選擇

1. Choose **Opening A or B**.
2. Keep shared note-cross-ref sections (principal activities / state of affairs / share capital).
3. Choose **Articles** branch (**AA**, alias A — all-directors retirement/re-election **or** **B** — no mandatory retirement / continue). When Articles / AA are **unknown**, default **Articles AA** and exactly: “In accordance with the Company's Articles of Association, all directors retire and, being eligible, offer themselves for re-election.” (Allen lock 2026-10-17). Do not fall back to Articles B / Art. 20(2).
4. Choose **Dividend** branch (nil final — common **or** positive recommendation).
5. Keep the three **verified-nil** shells only after verification; otherwise swap in Cap. 622 **positive** modules.
6. Keep **business review exemption** only where reporting exemption is verified.
7. Choose **Auditor** branch (continuing firm / mid-year resignation+appointment / first appointment).
8. End with **On behalf of the Board** signature block.
9. Replace every placeholder; omit only after checking the trigger. An uncompleted bracket is a preparation gap, not a nil fact.

先選開首 A／B → 保留附註交叉引用段 → 選章程分支 → 選股息分支 → 核實後才用「概無」殼或改用正面模組 → 業務審視豁免 → 選核數師分支 → 董事會代表簽署。未填欄位不代表「無」。

---

## Opening / 開首

### Opening A — first report (period from START to END) / 首份報告（由[開始日]至[結束日]）

Use for Specimen A / first (or multi-) period from incorporation (or other period start) to reporting date. Prefer “period”, not “year ended”.

=== "English"

    ```text
    DIRECTORS' REPORT

    The directors of [COMPANY NAME] (the "Company") present their first report and the audited financial statements of the Company for the period from [START DATE][ (date of incorporation)] to [END DATE].
    ```

=== "繁體中文"

    ```text
    董事報告

    [公司名稱]（「本公司」）董事提呈其首份董事報告及本公司由[開始日][（成立日期）]至[結束日]之經審核財務報表。
    ```

### Opening B — normal year (year ended DATE) / 正常年度（截至[年結日]止年度）

Use for Specimen B / subsequent annual reporting year.

=== "English"

    ```text
    DIRECTORS' REPORT

    The directors of [COMPANY NAME] (the "Company") present their report and the audited financial statements of the Company for the year ended [REPORTING DATE].
    ```

=== "繁體中文"

    ```text
    董事報告

    [公司名稱]（「本公司」）董事提呈其董事報告及本公司截至[年結日]止年度之經審核財務報表。
    ```

---

## Principal activities and principal place of business / 主要業務及主要營業地點 → note 1

House style: **cross-ref Note 1 only** — do not repeat the full description in the DR.

=== "English"

    ```text
    PRINCIPAL ACTIVITIES AND PRINCIPAL PLACE OF BUSINESS

    The Company's principal activities and principal place of business are set out in note 1 to the financial statements.
    ```

=== "繁體中文"

    ```text
    主要業務及主要營業地點

    本公司之主要業務及主要營業地點載於財務報表附註1。
    ```

---

## State of affairs and appropriations / 業務狀況及撥款 → annexed FS + dividend

### Performance / state of affairs cross-ref / 業績及業務狀況交叉引用

Use “period from … to …” after Opening A; use “year ended …” after Opening B.

=== "English"

    ```text
    STATE OF THE COMPANY'S AFFAIRS AND APPROPRIATIONS

    The Company's financial performance for the [period from [START DATE] to [END DATE] / year ended [REPORTING DATE]] and the state of affairs of the Company as at [REPORTING DATE] are set out in the annexed financial statements.
    ```

=== "繁體中文"

    ```text
    本公司業務狀況及撥款

    本公司於[由[開始日]至[結束日]之期間／截至[年結日]止年度]之財務表現及於[年結日]之業務狀況載於隨附財務報表。
    ```

### Dividend — nil final (common) / 不建議派付末期股息（常見）

=== "English"

    ```text
    The directors do not recommend the payment of a final dividend.
    ```

=== "繁體中文"

    ```text
    董事不建議派付末期股息。
    ```

### Dividend — positive recommendation branch / 建議派息分支

=== "English"

    ```text
    The directors recommend the payment of a final dividend of [CURRENCY AND TOTAL AMOUNT] for the [period / year].
    ```

=== "繁體中文"

    ```text
    董事建議就本[期間／年度]派付末期股息合共[貨幣及總額]。
    ```

Nil final recommendation does **not** mean no interim / other dividends were paid. Select from board evidence.

不建議派付末期股息，不代表年內沒有派付中期或其他股息；須按董事會實際決定選用。

---

## Share capital / 股本 → note [N]

Default house shell is a **cross-reference** (live specimens commonly note 6). If shares were issued in the year/period, also insert the Cap. 622 s5 **positive** module below (or ensure Note [N] carries the statutory particulars).

=== "English"

    ```text
    SHARE CAPITAL

    Details of the Company's share capital are set out in note [N] to the financial statements.
    ```

=== "繁體中文"

    ```text
    股本

    本公司股本詳情載於財務報表附註[N]。
    ```

---

## Directors / 董事 + Articles branches

### Directors list / 董事名單

=== "English"

    ```text
    DIRECTORS

    The directors of the Company who held office during the [period / year] and up to the date of this report were:-

    [DIRECTOR NAME][ (appointed on [DATE])][ (resigned on [DATE])]
    ```

=== "繁體中文"

    ```text
    董事

    於本[期間／年度]及截至本報告日期止任職之本公司董事為：-

    [董事姓名][（於[日期]委任）][（於[日期]辭任）]
    ```

List everyone who served during the reporting interval **or** between period/year end and the report date, including leavers. Do not invent appointment dates.

須列出報告期間內或由期間／年結日至報告日期任職的每位董事（包括已離任者）；不得虛構委任日期。

### Articles AA — all-directors retirement / re-election (alias Articles A) / 章程分支 AA：全體董事退任及膺選連任

**Forever house name: Articles AA** (alias Articles A). **Allen lock 2026-10-16 (all cases):** when the M&A **has director retirement** / rotation, use **Articles AA** and the exact sentence below (no named-director placeholders). That includes **Cap. 32 + Table A** (or other pre-622H articles) that provide director retirement / rotation — those packs are **Articles AA**, not Articles B and not Art. 20(2).

**Allen lock 2026-10-17 (forever-correct):** When Articles / AA are **unknown** (no M&A on file, or the retirement rule is not verified), **default to Articles AA** and the exact generic sentences already shown below. Use exactly this English line (no case-specific AA required): “In accordance with the Company's Articles of Association, all directors retire and, being eligible, offer themselves for re-election.” ZH already locked alongside: 「按照本公司組織章程細則，全體董事退任，並合資格願意膺選連任。」 Do **not** require case-specific AA wording or named-director variants. Do **not** fall back to Articles B / Art. 20(2) when Articles are unknown. Art. 20(2) continue-in-office is **never** a substitute for director retirement (auditor continue-in-office is never that substitute); cite 20(2) only when Cap. 622H Model Articles with 20(2) are verified on file (unchanged). Cap. 32 + Table A ≠ Art. 20(2) remains as locked 2026-10-16.

=== "English"

    ```text
    In accordance with the Company's Articles of Association, all directors retire and, being eligible, offer themselves for re-election.
    ```

=== "繁體中文"

    ```text
    按照本公司組織章程細則，全體董事退任，並合資格願意膺選連任。
    ```

### Articles B — no mandatory retirement / continue in office / 章程分支 B：並無強制退任／繼續留任

**Directors continue-in-office (not auditors) — Allen locks 2026-10-12 and 2026-10-16:** Art. **20(2)** is **directors** continue in office / unlimited period under **Cap. 622H Schedule 2 Model Articles**. It is **not** an auditor clause. Cite **20(2) only when Cap. 622H-style Model Articles that contain Art. 20(2) are verified on file**. **Article 10** is directors’ meeting quorum only — never cite Art. 10 for appointment or continuance. Wrong article on DR = hard fail. Prefer Articles B wording (no mandatory retirement / continue) without article numbers unless the face must cite; if citing continue-in-office, **20(2) only**. **Unknown Articles / unknown AA (no M&A on file, or the retirement rule is not verified) → default Articles AA** (Allen lock 2026-10-17; generic forever line: “In accordance with the Company's Articles of Association, all directors retire and, being eligible, offer themselves for re-election.”). Do not ask Allen. Do not assume Model Articles or Art. 20(2). **Never assume Model Articles or quote Art. 20(2) without verification.**

**Cap. 32 + Table A ≠ Art. 20(2) (Allen lock 2026-10-16, all cases):** Cap. 32 + Table A (or other pre-622H articles) with no Art. 20(2) — including when there is “no auditor clause” — is **not** Art. 20(2). Never cite Art. 20(2) on those packs. If those M&A provide director retirement / rotation → **Articles AA**, not Articles B / 20(2).

Specimen B / common Clarity live branch — use when the Articles do **not** provide for retirement and rotation.

=== "English"

    ```text
    The articles of association of the Company do not provide for mandatory retirement of directors and all the existing directors will continue in office for the ensuing year.
    ```

=== "繁體中文"

    ```text
    本公司組織章程細則並無董事強制退任之規定，所有現任董事將於來年繼續留任。
    ```

---

## Verified-nil shells (common live house) / 已核實「概無」殼段（實務常見）

Use these **only** after verification. If any fact is positive, replace with the Cap. 622 positive module in the next major section.

僅在核實後使用。若有正面事實，改用下一節 Cap. 622 正面模組。

### Permitted indemnity provision — verified nil / 獲准許的彌償條文 — 已核實概無

=== "English"

    ```text
    PERMITTED INDEMNITY PROVISION

    At no time during the financial [period / year] or up to the date of this report was a permitted indemnity provision in force for the benefit of any director of the Company or an associated company.
    ```

=== "繁體中文"

    ```text
    獲准許的彌償條文

    於本財政[期間／年度]任何時間或截至本報告日期，概無惠及本公司或相聯公司任何董事的獲准許的彌償條文有效。
    ```

### Equity-linked arrangements — verified nil / 股票掛鈎安排 — 已核實概無

=== "English"

    ```text
    EQUITY-LINKED ARRANGEMENTS

    The Company did not enter into any equity-linked agreement during the [period / year], and no such agreement subsisted at the end of the [period / year].
    ```

=== "繁體中文"

    ```text
    股票掛鈎安排

    本公司於本[期間／年度]內並無訂立任何股票掛鈎協議，於本[期間／年度]結束時亦無任何上述協議存續。
    ```

### Management contracts — verified nil / 管理合約 — 已核實概無

=== "English"

    ```text
    MANAGEMENT CONTRACTS

    No contracts concerning the management and administration of the whole or any substantial part of the business of the Company were entered into or existed during the [period / year].
    ```

=== "繁體中文"

    ```text
    管理合約

    於本[期間／年度]內，本公司並無就全部或任何重大部分業務的管理及行政工作訂立或存在任何合約。
    ```

---

## Business review exemption / 業務審視豁免

Keep only when reporting-exemption eligibility for the year/period is verified.

=== "English"

    ```text
    BUSINESS REVIEW

    The Company falls within the reporting exemption for the financial [period / year]. Accordingly, the Company is exempt from preparing a business review.
    ```

=== "繁體中文"

    ```text
    業務審視

    本公司於本財政[期間／年度]屬提交報告豁免範圍。因此，本公司獲豁免編製業務審視。
    ```

---

## Auditor / 核數師

Replace `[Firm]` with the engagement firm (live Clarity specimens: `Clarity CPA & Co.`). Choose **one** branch.

以實際核數事務所名稱取代 `[Firm]`（Clarity 實務樣本常用 `Clarity CPA & Co.`）。只選用一個分支。

### Auditor A — continuing firm / 持續委任（續聘）

=== "English"

    ```text
    AUDITOR

    The financial statements have been audited by [Firm].

    A resolution for the re-appointment of [Firm] as auditor of the Company is to be proposed at the forthcoming annual general meeting.
    ```

=== "繁體中文"

    ```text
    核數師

    本財務報表已由[事務所]審核。

    本公司將於應屆股東週年大會上提呈決議案，續聘[事務所]為本公司核數師。
    ```

### Auditor B — prior auditor resigned; Clarity (or firm) appointed during year / 前任辭任並於年內委任（Specimen B）

=== "English"

    ```text
    AUDITOR

    During the year, [PRIOR AUDITOR] resigned and [Firm] was appointed as the auditor of the Company.

    A resolution for the appointment of [Firm] as auditor of the Company is to be proposed at the forthcoming annual general meeting.
    ```

=== "繁體中文"

    ```text
    核數師

    年內，[前任核數師]辭任，[事務所]獲委任為本公司核數師。

    本公司將於應屆股東週年大會上提呈決議案，委任[事務所]為本公司核數師。
    ```

### Auditor C — first appointment / 首次委任（常見於 Opening A）

=== "English"

    ```text
    AUDITOR

    The financial statements have been audited by [Firm].

    A resolution for the appointment of [Firm] as auditor of the Company is to be proposed at the forthcoming annual general meeting.
    ```

=== "繁體中文"

    ```text
    核數師

    本財務報表已由[事務所]審核。

    本公司將於應屆股東週年大會上提呈決議案，委任[事務所]為本公司核數師。
    ```

---

## Approval / signature / 批准及簽署

House live style (both specimens):

=== "English"

    ```text
    On behalf of the Board

    [SIGNING DIRECTOR'S NAME]
    Director
    [REPORT DATE]
    ```

=== "繁體中文"

    ```text
    代表董事會

    [簽署董事姓名]
    董事
    [報告日期]
    ```

s391 also permits the company secretary to sign on the directors’ behalf, with the signatory’s name stated — use only if that is the actual execution path.

第391條亦容許公司秘書代董事簽署並述明簽署人姓名；僅在實際簽署安排如此時使用。

---

## Cap. 622 positive modules (alternatives to verified-nil shells) / Cap. 622 正面模組（替代「概無」殼）

Insert **before** the approval/signature block when triggered. Repeat as needed. These remain part of the locked standard as alternatives to the verified-nil shells above.

觸發時於簽署欄前插入；可重複。此等正面模組屬鎖定標準的一部分，用以替代上文「概無」殼段。

### Shares issued — s5 / 發行股份

=== "English"

    ```text
    Shares issued
    During the [period / year], the company issued [NUMBER] [CLASS] shares for [REASON]. The consideration received was [CURRENCY/AMOUNT AND DETAILS OF NON-CASH CONSIDERATION].
    ```

=== "繁體中文"

    ```text
    發行股份
    [期間／年度]內，本公司因[原因]發行[數目]股[類別]股份。所收取的代價為[貨幣／金額及非現金代價詳情]。
    ```

### Debentures issued — s5A / 發行債權證

=== "English"

    ```text
    Debentures issued
    During the [period / year], the company issued [CLASS] debentures amounting to [CURRENCY AND AMOUNT] for [REASON]. The consideration received was [DETAILS].
    ```

=== "繁體中文"

    ```text
    發行債權證
    [期間／年度]內，本公司因[原因]發行金額為[貨幣及金額]的[類別]債權證。所收取的代價為[詳情]。
    ```

### Equity-linked agreements — positive s6 / 股票掛鈎協議（正面）

=== "English"

    ```text
    Equity-linked agreements
    On [DATE], the company entered into [AGREEMENT] for [REASON]. Its nature and terms were [DETAILS, INCLUDING CONDITIONS FOR THE COMPANY TO ISSUE SHARES OR FOR A THIRD PARTY TO REQUIRE ISSUE, AND MONETARY OR OTHER CONSIDERATION RECEIVED OR RECEIVABLE]. Under the agreement, [NUMBER] shares of [CLASS] were issued during the [period / year].

    At [REPORTING DATE], [AGREEMENT] remained in force. It may result in the issue of [NUMBER] shares of [CLASS]. The consideration received or receivable is [DETAILS]. The remaining conditions and terms before issue are [DETAILS].
    ```

=== "繁體中文"

    ```text
    股票掛鈎協議
    本公司於[日期]因[原因]訂立[協議]。協議的性質及條款為[詳情，包括本公司發行股份或第三方可要求發行股份的條件，以及已收或應收的金錢或其他代價]。本[期間／年度]內根據該協議已發行[數目]股[類別]股份。

    於[年結日]，[協議]仍然有效，可能導致發行[數目]股[類別]股份。已收或應收的代價為[詳情]。發行前尚須達成的條件及條款為[詳情]。
    ```

### Permitted indemnity — positive s9 / 獲准許的彌償條文（正面）

=== "English"

    ```text
    Permitted indemnity provision
    During [RELEVANT DATES WITHIN THE YEAR/PERIOD], a permitted indemnity provision [IDENTIFY PROVISION] was in force for the benefit of [RELEVANT DIRECTORS OF THE COMPANY OR ITS ASSOCIATED COMPANY].
    At the date of approval of this report, a permitted indemnity provision [IDENTIFY PROVISION] is in force for the benefit of [RELEVANT DIRECTORS OF THE COMPANY OR ITS ASSOCIATED COMPANY].
    ```

=== "繁體中文"

    ```text
    獲准許的彌償條文
    於[年度／期間內的相關日期]，惠及[本公司或其相聯公司的相關董事]的獲准許的彌償條文[識別條文]曾有效。
    於本報告批准日期，惠及[本公司或其相聯公司的相關董事]的獲准許的彌償條文[識別條文]正有效。
    ```

### Management contract — positive s543 / 管理合約（正面）

=== "English"

    ```text
    Management contract
    During the [period / year], a contract with [PARTY] for the management and administration of [BUSINESS OR SUBSTANTIAL PART] was in force. Its duration is [DURATION]. [DIRECTOR/SHADOW DIRECTOR NAME] has [NATURE AND EXTENT OF INTEREST] in the contract.
    ```

=== "繁體中文"

    ```text
    管理合約
    [期間／年度]內，與[訂約方]訂立、涉及[業務或其重大部分]的管理及行政工作的合約有效，合約期限為[期限]。[董事／幕後董事姓名]在該合約中的利害關係性質及程度為[詳情]。
    ```

### Other material matters — s390(2) / 其他重大事項

Fact-specific; no automatic nil assertion.

=== "English"

    ```text
    Other material matters
    [PARTICULARS OF EACH MATTER REQUIRED BY SECTION 390(2).]
    ```

=== "繁體中文"

    ```text
    其他重大事項
    [第390(2)條要求披露的每項事項詳情。]
    ```

---

## Module map (EN outline) / 模組地圖

| Module | Branches / default |
| --- | --- |
| Opening | **A** first report (period START→END) · **B** annual report (year ended DATE) |
| Principal activities & place of business | Note 1 cross-ref (shared) |
| State of affairs & appropriations | Annexed FS cross-ref + **nil final** (common) / **positive** dividend |
| Share capital | Note [N] cross-ref (+ s5 positive module if issued) |
| Directors | List + Articles **AA** (alias **A**) retire/re-elect · **B** no mandatory retirement / continue |
| Indemnity / equity-linked / management | Verified-nil shells **or** Cap. 622 positive modules |
| Business review | Reporting-exemption shell |
| Auditor | **A** continuing re-appointment · **B** resignation + mid-year appointment · **C** first appointment |
| Signature | On behalf of the Board / Director / Date |

---

??? note "條件及法定分類 / Conditions and statutory classification"

    | Topic / 項目 | Classification and decision / 分類及選擇 |
    | --- | --- |
    | Opening A vs B / 開首 | House modular: first/multi-period vs normal year. Still Cap. 622 s388/s390 annual-report framing; choose timeline words to match facts. / 按事實選首份期間或正常年度開首。 |
    | Principal activities; place of business / 主要業務及地點 | Statutory: Cap. 622 s390(1). House style cross-ref Note 1 only. / 法定；實務只交叉引用附註1。 |
    | State of affairs; dividend / 業務狀況；股息 | House annexed-FS cross-ref + Cap. 622D s7 dividend (nil final common; positive branch available). / 隨附報表交叉引用 + 第7條股息。 |
    | Share capital / 股本 | House note cross-ref; Cap. 622D s5 positive module when shares issued. / 附註交叉引用；有發行時用第5條正面模組。 |
    | Directors; Articles / 董事；章程 | Statutory director list s390(1). Articles retirement wording is **house conventional**. Unknown Articles / AA → default Articles AA (exact all-directors retire / re-elect line). Verified Articles → select AA or B from the actual Articles. / 董事名單法定；章程不明時預設章程分支 AA（全體董事退任及膺選連任）；已核實章程則按實際章程選 AA 或 B。 |
    | Indemnity; equity-linked; management / 彌償；股票掛鈎；管理合約 | Cap. 622D ss6, 9; Cap. 622 s543. Verified-nil shells match common Clarity live reports; replace with positive modules when triggered. / 「概無」殼僅於核實後；觸發則改用正面模組。 |
    | Business review / 業務審視 | Exempt within verified reporting-exemption profile: Cap. 622 s388(3)(a). / 已核實提交報告豁免時適用。 |
    | Auditor AGM resolution / 核數師決議 | House conventional (appointment / re-appointment / mid-year change). Not Cap. 622D core content; select from engagement facts. Dereg path remains Case 4 (no further appointment). / 實務慣用段落；撤銷登記仍用 Case 4。 |
    | Other material matters / 其他重大事項 | Statutory when s390(2) applies; business-review exemption does not switch this off. / 第390(2)條仍可適用。 |
    | Acquisition-benefit arrangements; donations; resignation reasons; specified-undertaking interests / 購入獲益安排；捐款；辭任理由；指明企業利害關係 | Exempt within this verified profile: Cap. 622D ss3(3A), 4(3), 8(3), 10(7)(a). / 本適用情況獲豁免。 |

## Lock / upgrade decisions (Allen 2026-10-02) / 鎖定及升級決定

**Initial lock (earlier 2026-10-02):** former minimal statutory core locked as house standard.

**Upgrade (same date, Allen pastes):** rewrite to modular house style matching:

1. **Specimen A — first period (earlier message):** “present their **first** report and the audited financial statements” for period from [START] to [END]; principal activities & place of business → note 1; state of affairs & appropriations → annexed FS + nil final dividend; share capital → note [N]; directors list + Articles retirement/re-election; verified nils (indemnity / equity-linked / management); business review exemption; auditor audited by Clarity + AGM appointment resolution; On behalf of the Board / Director / Date.
2. **Specimen B — normal year (this message):** “present their report and the audited financial statements” for year ended [DATE]; same note-cross-ref sections; Articles do **not** provide mandatory retirement — existing directors continue; same verified nils + business review exemption; prior auditor resigned and Clarity appointed during year + AGM appointment resolution.

Accepted modular outcomes: Opening A/B; Articles AA (alias A)/B; Auditor A/B/C; Dividend nil-final (common) + positive; Cap. 622 positive modules retained as alternatives to verified-nil shells. Public locks pack **not** updated. Articles AA exact all-directors sentence and Cap. 32 ≠ Art. 20(2) are the 2026-10-16 lock (see Articles AA / B above). When Articles / AA are unknown, default Articles AA and that same exact English line (Allen lock 2026-10-17).

---

## Evidence and limits / 依據及限制

Legal baseline verified on 13 September 2026 against [Cap. 622D](https://www.elegislation.gov.hk/hk/cap622D) (version 23 May 2025) and [Cap. 622](https://www.elegislation.gov.hk/hk/cap622) ss388, 390, 391 and 543; see [detailed provenance](../review/normal-dr-provenance.md). House wording upgraded 2026-10-02 from Allen’s two live Clarity specimen pastes.

This is a locked conditional specimen, not a finding that a particular company qualifies or that its completed report is compliant. No company facts, approval, signature, dividend decision or absence of transactions have been verified for any engagement. Apply only after verifying reporting-exemption eligibility, auditor history and actual facts for the year/period. When Articles / AA are unknown, default Articles AA (Allen lock 2026-10-17).
