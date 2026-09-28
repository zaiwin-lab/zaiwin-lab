# ZKB-10 Contribution Capture Ledger

This ledger records evidence-backed GitHub portfolio repairs. It does not measure success by commit count and does not backdate, rewrite or manufacture activity.

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
