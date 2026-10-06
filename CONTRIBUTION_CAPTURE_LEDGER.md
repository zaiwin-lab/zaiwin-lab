# ZKB-10 Contribution Capture Ledger

This ledger records evidence-backed GitHub portfolio repairs. It does not measure success by commit count and does not backdate, rewrite or manufacture activity.

## Rolling seven-day window: 30 September–6 October 2026

| Measure | Verified position |
|---|---|
| Priority repositories inspected | `MVP-KBOOST`, `MVP-MKH`, `NFZK`, `MVP-EVOS-Mara` and `zaiwin-lab` |
| New public default-branch source commits found | 20 — 15 Sales Portal, 4 Maths Quest with MARIA and 1 My Kenyalang Homes |
| New commits mapped to `zaiwin-lab` before repair | 0 — all 20 source commits used `claude` as author and committer |
| Meaningful ZKB-10 repair commits | 3 — Sales Portal README, Maths Quest README and this evidence ledger |
| Default-branch repair commits | 3 |
| Project READMEs corrected | 2 |
| Verified live URLs added | [salesmanapps.netlify.app](https://salesmanapps.netlify.app) and [mathquest-my.netlify.app](https://mathquest-my.netlify.app) |
| New missing/recoverable project | Alumni UTHM Sarawak contribution portal |
| Application/deployment changes made by ZKB-10 | 0 |
| Git history rewritten | 0 |
| Fabricated or backdated activity | 0 |

## 6 October 2026 — verified repairs

### Sales Portal

- **Repository:** [`MVP-KBOOST`](https://github.com/zaiwin-lab/MVP-KBOOST)
- **New source activity:** 15 substantive default-branch commits from 1–5 October added authentication, Supabase transaction posting, role isolation, stock replenishment, real document output, language coverage, account management and interface corrections.
- **Attribution:** all 15 use `claude` as GitHub author and committer; history was preserved.
- **Verified deployment:** [salesmanapps.netlify.app](https://salesmanapps.netlify.app), Netlify deploy `6ac317860ce412bd0bbdf3aa`, ready and published 5 October 2026.
- **Deployment provenance:** API upload with a source ZIP but no Git branch, commit reference or commit URL. Exact parity is not proven.
- **Repair:** replaced the stale browser-only product description with the current authenticated pre-pilot architecture, live link, business value, technology, responsible-use boundary and contribution provenance.
- **Evidence:** [commit `12898af`](https://github.com/zaiwin-lab/MVP-KBOOST/commit/12898aff72285a26d2c4fda9aa085e515adfadb9)

### Maths Quest with MARIA

- **Repository:** [`NFZK`](https://github.com/zaiwin-lab/NFZK)
- **New source activity:** four substantive default-branch commits on 4 October created the Year 4 Maths-English portal, 12-week journey, bilingual learning support, deterministic adaptation and local progress tools.
- **Attribution:** all four use `claude` as GitHub author and committer; history was preserved.
- **Verified deployment:** [mathquest-my.netlify.app](https://mathquest-my.netlify.app), Netlify deploy `6ac245726a4261d66354a2dc`, ready and published 4 October 2026.
- **Deployment provenance:** API upload with a source ZIP but no Git branch, commit reference or commit URL. No serverless or edge functions are deployed.
- **Repair:** established a permanent product identity, maturity classification, learning problem, users, strategic value, deterministic-not-generative boundary, privacy and education safeguards, delivery role and exact deployment limitation. The public README was deliberately generalised to avoid increasing disclosure of a child's identity.
- **Evidence:** [commit `1de5a56`](https://github.com/zaiwin-lab/NFZK/commit/1de5a56659bf1db3727f54c23fd5a7e2a579b89f)

### My Kenyalang Homes

- **Repository:** [`MVP-MKH`](https://github.com/zaiwin-lab/MVP-MKH)
- **New source activity:** [commit `665c10f`](https://github.com/zaiwin-lab/MVP-MKH/commit/665c10f9d4dc233136113dbc1fa4e0de14bf8191) corrected the signed Netlify-to-Supabase webhook so it mirrors only the Express lead form rather than inserting blank rows for unrelated partner forms.
- **Verification recorded in the commit:** partner submissions are acknowledged without a write, a real lead still inserts, and unsigned requests remain refused.
- **Attribution:** the commit uses `claude` as author and committer, so it does not map to the owner contribution graph.
- **Documentation decision:** no separate README edit was made because the existing README already documents the signed mirror and its safety boundary; a minor wording-only commit would be filler.

### CEOnita status

- No new CEOnita Git commit or deployment was found in this window.
- The live project remains [ceonita.uk](https://ceonita.uk), deploy `6ab8ebab2fc1f1352fa7da21`.
- Source remains on `claude/ceonita-strategik`, 48 commits ahead of the Attendify default branch.
- The two live functions remain absent from the inspected GitHub branch.
- No unsafe merge, history rewrite or invented recovery was performed.

## Contribution-capture issues

| Repository / project | Verified issue | Safest forward fix |
|---|---|---|
| `MVP-KBOOST` | 15 meaningful source commits map to `claude`; current Netlify deploy has no Git commit reference | configure future Claude/Git commits with a `zaiwin-lab`-verified author email and deploy from the reviewed default-branch commit |
| `NFZK` | 4 meaningful source commits map to `claude`; current deploy has no Git commit reference | use the owner-linked identity for future accepted work and attach the next deployment to its exact commit |
| `MVP-MKH` | the 6 October webhook fix maps to `claude` | preserve history; use the owner-linked identity for the next accepted fix |
| CEOnita | application history remains on a divergent branch and live-function source is missing | recover the exact live source before establishing a canonical repository |
| Netlify deployments | API uploads preserve the live product but often do not identify a Git commit | make reviewed Git-linked deployment the normal release path |

## Missing from GitHub / recovery backlog added this week

| Project | Evidence | Recoverability | Exact next capture action |
|---|---|---|---|
| Alumni UTHM Sarawak contribution portal | [alumniuthmswk.netlify.app](https://alumniuthmswk.netlify.app), ready Netlify deploy `6ac313914e4c5fd9b9df1858`, published 5 October 2026; Next.js server handler present; source ZIP recorded; no matching public GitHub repository found | High | retrieve the deploy source ZIP, remove secrets and generated output, verify payment/receipt behaviour, then create a truthful current-date repository record |
| CEOnita Strategik | live deployment, substantial branch source and two live-only functions | Medium–High | retrieve the exact deployed source and functions, compare with `claude/ceonita-strategik`, then establish a canonical repository |
| My Kenyalang Homes live build | editable source plus partial recovery record, but the production lineage remains fragmented | Medium–High | connect the next production deploy to an exact reviewed commit and recover any remaining live-only function source |

## Green-graph diagnosis

The work was genuinely present on GitHub, but the source commits used the `claude` GitHub identity. GitHub credits a commit only when its author email maps to the profile, and the commit is on the default or `gh-pages` branch of a standalone repository. The three documentation repairs in this section were created through the connected `zaiwin-lab` account on each repository's default branch.

GitHub timestamps contribution squares in UTC and may take up to 24 hours to refresh. Work committed during the morning in Malaysia can therefore appear on the previous calendar date.

## Highest-value next move

Fix attribution at the source: configure Claude's Git author name and email to an address verified on the `zaiwin-lab` account before the next build. Keep Claude as a co-author trailer. This allows genuine application commits—not repair documentation—to count without changing or falsifying existing history.

---

## Rolling seven-day window: 23–29 September 2026

| Measure | Verified position |
|---|---|
| Priority repositories inspected | `MVP-EVOS-Mara`, `MVP-MKH`, `MVP-AI-Tester`, `Prop-Asessor`, `MVP-Property`, `zaiwin-lab`, `KDP-Cecilia`, `MasterHub`, `google-maps-scraper`, `MVP-EGMH`, `MVP-KB`, `KDP-EGMegah` |
| Meaningful ZKB-10 repair commits | 9 — three each on 27, 28 and 29 September |
| Default-branch repair commits | 7 — My Kenyalang Homes, KAPT Digital Clinic, KOBIS Property Concierge and three main-profile/ledger commits |
| Non-default documentation repairs | 2 — CEOnita recovery documentation on its development branch |
| Recent commits with attribution mismatch | 49 — 33 CEOnita commits and 11 My Kenyalang Homes commits attributed to `claude`; 5 KAPT logo-branch commits attributed to `netlify-bot` |
| Stranded branch work | CEOnita: 48 commits ahead of the repository default branch; KAPT logo alternatives: 3 and 2 commits ahead |
| Unique project READMEs corrected | 4 — CEOnita, My Kenyalang Homes, KAPT Digital Clinic and KOBIS Property Concierge |
| Verified live URLs added or promoted | [ceonita.uk](https://ceonita.uk) and [mkhomes.win](https://mkhomes.win); [mydigiclinic.netlify.app](https://mydigiclinic.netlify.app) reverified |
| Newly discovered default-branch application commits | 6 — My Kenyalang Homes recovery and root-routing work, all attributed to `claude` |
| Recovery artifacts captured | 1 — My Kenyalang Homes compiled live-site snapshot; editable live source and deployed functions still missing |
| Application/deployment changes made by ZKB-10 | 0 |
| Git history rewritten | 0 |

## 29 September 2026 — verified repairs

### My Kenyalang Homes

- **Repository:** [`MVP-MKH`](https://github.com/zaiwin-lab/MVP-MKH)
- **New source activity found:** six default-branch commits on 28 September banked a compiled live-site snapshot, documented recovery limits and prepared root-routing and metadata alignment.
- **Attribution:** all six use `claude` as author and committer; history was not rewritten.
- **Verified deployment:** [mkhomes.win](https://mkhomes.win) currently points to Netlify deploy `6ab9aaa3cdaaa081cfc5f605`, published on 28 September through a manual/API workflow with no Git commit or source ZIP attached.
- **Remaining live-only evidence:** `mkhomes-ref-api`, `mkhomes-ref-go` and `mkhomes-stats-api` are deployed but absent from GitHub.
- **Repair:** updated the README to distinguish editable source, compiled recovery artifact and unrecovered production functions.
- **Evidence:** [commit `c44745b`](https://github.com/zaiwin-lab/MVP-MKH/commit/c44745b170bf10b231138ee9169fa1987ba6456b)

### KOBIS Property Concierge

- **Repository:** [`MVP-Property`](https://github.com/zaiwin-lab/MVP-Property)
- **Verified live demonstration:** [mvp-property.netlify.app](https://mvp-property.netlify.app)
- **Deployment evidence:** the live Netlify build was uploaded without a Git commit reference; Netlify records a source ZIP as available, but it has not been reconciled with the current default branch.
- **Implementation findings:** login always reports that authentication is not configured; admin and partner layouts are not session-protected; dashboards use hard-coded demonstration identities and metrics; lead and appointment APIs return mock HTTP-success records when storage fails; the appointment form can show success after a network error.
- **Repair:** replaced broad “Working Prototype” claims with an evidence-based pre-production demonstration classification and a fail-closed production checklist.
- **Evidence:** [commit `0938327`](https://github.com/zaiwin-lab/MVP-Property/commit/09383274e949038e18dba0412a74073f5c8b2b80)

### CEOnita and C-SUITE7 audit

- CEOnita has no new Git commit or Netlify deploy since the 28 September reconciliation. Its source gap and 48-commit branch divergence remain unchanged.
- C-SUITE7 AI was re-inspected. Its README already states that scoring is deterministic and rule-based, so no filler edit was made. Deployment-to-commit provenance remains in the backlog.
- The main showcase was not changed; today’s portfolio-quality improvement is the stronger evidence boundary in the two project READMEs.

## 28 September 2026 — verified repairs

### CEOnita Strategik

- **Source branch:** [`MVP-EVOS-Mara/tree/claude/ceonita-strategik`](https://github.com/zaiwin-lab/MVP-EVOS-Mara/tree/claude/ceonita-strategik)
- **Verified live platform:** [ceonita.uk](https://ceonita.uk)
- **Deployment evidence:** Netlify deploy `6ab8ebab2fc1f1352fa7da21` was published on 27 September 2026 through an API/manual deploy. It has no attached Git branch, commit reference or downloadable source archive.
- **Source gap:** the live deploy contains `ceonita-api` and `ceonita-register` functions that are absent from the inspected GitHub branch.
- **Repair:** reconciled the README with the live deployment, separated verified branch capabilities from live-only evidence, and added an exact recovery checklist.
- **Evidence:** [commit `4cb94d4`](https://github.com/zaiwin-lab/MVP-EVOS-Mara/commit/4cb94d4156a104fa68ce10e3f89d7d1efe0ccab9)
- **Still unresolved:** the branch remains 48 commits ahead of Attendify’s default branch, 46 application commits use the `claude` identity, and inherited Attendify/ProgramOS/ANGKASA labels remain in selected files.

### KAPT Digital Clinic

- **Repository:** [`MVP-AI-Tester`](https://github.com/zaiwin-lab/MVP-AI-Tester)
- **Verified public demonstration:** [mydigiclinic.netlify.app](https://mydigiclinic.netlify.app)
- **Deployment evidence:** the current public build is a static export with no deployed functions and no Netlify Forms capture. Its form validates in the browser, generates a demonstration reference and routes to a confirmation screen without transmitting the case.
- **Source gap:** backend, authentication, storage and Anthropic draft modules exist only in parked source paths and are not part of the public deployment.
- **Repair:** replaced “Pilot Ready” claims with an evidence-based static-demonstration classification and clearly separated present capabilities from the parked architecture.
- **Evidence:** [commit `1848371`](https://github.com/zaiwin-lab/MVP-AI-Tester/commit/1848371fc783e6e9420f61836d3dab7e3cd784f0)
- **Still unresolved:** two alternative logo branches are 3 and 2 commits ahead of default and were committed by `netlify-bot`; neither was merged because the approved design cannot be inferred safely.

### Main profile

- Renamed “Flagship AI Products” to “Flagship Decision-Support Products.”
- Corrected C-SUITE7 AI to a deterministic, rule-based proposal-readiness aid.
- Corrected KAPT Digital Clinic to a static diagnostic journey whose backend and AI workflow are not currently deployed.
- Kept CEOnita out of the flagship table until its live source is recovered and the canonical default-branch record is established.

## Attribution and branch findings

Do not rewrite existing history. The safest forward repair is to:

1. make future accepted commits from the `zaiwin-lab` account or an email verified on that account;
2. retain an AI co-author trailer when appropriate;
3. keep every commit substantive;
4. reconcile application changes before merging or recovering them into a canonical default branch.

| Repository / branch | Finding | Safest forward fix |
|---|---|---|
| `MVP-EVOS-Mara/claude/ceonita-strategik` | 46 application commits attributed to `claude`; branch is 48 commits ahead of default | recover the exact live source, review the diff, then create a dedicated canonical repository with a current-date provenance note |
| `MVP-MKH` | 11 inspected application and backend commits attributed to `claude`, including six new default-branch commits on 28 September | use an owner-verified identity for future accepted fixes; do not rewrite the existing commits |
| `MVP-AI-Tester/agent-the-logo-for-all-instances-1dff` | 3 commits attributed to `netlify-bot` | choose the approved visual first, then integrate it through a reviewed owner-attributed commit |
| `MVP-AI-Tester/agent-with-third-uploaded-logo-1706` | 2 commits attributed to `netlify-bot` | archive or integrate only after the approved logo is established |
| `google-maps-scraper` | repository history and authorship indicate upstream third-party work | keep it outside the personal product portfolio unless provenance and original contribution are documented |

## Missing from GitHub / recovery backlog

| Project | Evidence | Recoverability | Exact next capture action |
|---|---|---|---|
| CEOnita Strategik | live deploy at [ceonita.uk](https://ceonita.uk), substantial branch source and two live-only functions | Medium–High | retrieve the exact source that produced deploy `6ab8ebab2fc1f1352fa7da21`, compare it with the branch, remove secrets, then recover a dedicated repository using the current date |
| BTD Koperasi / ProgramOS Lite | [btdkoperasi.win](https://btdkoperasi.win) previously verified; ProgramOS history exists in CEOnita branch ancestry | Medium–High | obtain the exact Netlify deploy source and recover the canonical BTD record without rewriting history |
| My Kenyalang Homes live build | compiled snapshot recovered; current manual/API deploy has no Git reference and three live-only functions | Medium–High | recover the editable source and all three function sources, compare them with the snapshot and default branch, then deploy from an attached reviewed commit |
| KAPT backend and logo variants | parked backend source plus two non-default visual branches | High for documentation; conditional for code | establish the approved logo and target backend design, then test on a non-production deployment before any reviewed merge |
| KOBIS Property Concierge | README corrected; Netlify source ZIP is available but unreconciled; authentication and persistence fail open | High for source comparison; conditional for production | retrieve and compare the source ZIP, then implement protected auth and durable fail-closed storage before real customer use |
| C-SUITE7 AI deployment provenance | verified live demonstration, but its current Netlify deploy has no Git commit reference | Medium | connect a future verified deploy to the repository default branch and document deterministic scoring limitations |
| `MVP-EGMH` | empty public repository | Unknown | identify the intended product and source before creating documentation or code |

## Highest-value next move

Retrieve the exact CEOnita source bundle that produced Netlify deploy `6ab8ebab2fc1f1352fa7da21`, including both deployed functions, then compare it with `claude/ceonita-strategik`. That is the shortest truthful path to a dedicated CEOnita repository, a canonical default branch and properly attributed future contributions.
