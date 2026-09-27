# ZKB-10 Contribution Capture Ledger

This ledger records evidence-backed GitHub portfolio repairs. It does not measure success by commit count and does not backdate, rewrite or manufacture activity.

## Rolling seven-day window: 22–28 September 2026

| Measure | Verified position |
|---|---|
| Priority repositories inspected | `MVP-EVOS-Mara`, `MVP-MKH`, `MVP-AI-Tester`, `Prop-Asessor`, `MVP-Property`, `zaiwin-lab`, `KDP-Cecilia`, `MasterHub`, `google-maps-scraper`, `MVP-EGMH`, `MVP-KB`, `KDP-EGMegah` |
| Meaningful repair commits | 6 — three on 27 September and three on 28 September |
| Default-branch repair commits | 4 — My Kenyalang Homes, KAPT Digital Clinic and two main-profile/ledger commits |
| Non-default documentation repairs | 2 — CEOnita recovery documentation on its development branch |
| Recent commits with attribution mismatch | 43 — 33 CEOnita commits and 5 My Kenyalang Homes commits attributed to `claude`; 5 KAPT logo-branch commits attributed to `netlify-bot` |
| Stranded branch work | CEOnita: 48 commits ahead of the repository default branch; KAPT logo alternatives: 3 and 2 commits ahead |
| Unique project READMEs corrected | 3 — CEOnita, My Kenyalang Homes and KAPT Digital Clinic |
| Verified live URLs added or promoted | [ceonita.uk](https://ceonita.uk) and [mkhomes.win](https://mkhomes.win); [mydigiclinic.netlify.app](https://mydigiclinic.netlify.app) reverified |
| Application/deployment changes made by ZKB-10 | 0 |
| Git history rewritten | 0 |

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
| `MVP-MKH` | 5 inspected backend commits attributed to `claude` | use an owner-verified identity for future accepted fixes; do not rewrite the five commits |
| `MVP-AI-Tester/agent-the-logo-for-all-instances-1dff` | 3 commits attributed to `netlify-bot` | choose the approved visual first, then integrate it through a reviewed owner-attributed commit |
| `MVP-AI-Tester/agent-with-third-uploaded-logo-1706` | 2 commits attributed to `netlify-bot` | archive or integrate only after the approved logo is established |
| `google-maps-scraper` | repository history and authorship indicate upstream third-party work | keep it outside the personal product portfolio unless provenance and original contribution are documented |

## Missing from GitHub / recovery backlog

| Project | Evidence | Recoverability | Exact next capture action |
|---|---|---|---|
| CEOnita Strategik | live deploy at [ceonita.uk](https://ceonita.uk), substantial branch source and two live-only functions | Medium–High | retrieve the exact source that produced deploy `6ab8ebab2fc1f1352fa7da21`, compare it with the branch, remove secrets, then recover a dedicated repository using the current date |
| BTD Koperasi / ProgramOS Lite | [btdkoperasi.win](https://btdkoperasi.win) previously verified; ProgramOS history exists in CEOnita branch ancestry | Medium–High | obtain the exact Netlify deploy source and recover the canonical BTD record without rewriting history |
| My Kenyalang Homes live build | repository documents production drift from Git | High | export the current deploy source/artifact and reconcile the documented live-only differences into the default branch |
| KAPT backend and logo variants | parked backend source plus two non-default visual branches | High for documentation; conditional for code | establish the approved logo and target backend design, then test on a non-production deployment before any reviewed merge |
| KOBIS Property Concierge | live deployment is not tied to a Git commit; login is a placeholder and lead submission can return a mock success response | Medium–High | correct the README, connect deployment provenance, and replace mock success/auth placeholders before real customer use |
| C-SUITE7 AI deployment provenance | verified live demonstration, but its current Netlify deploy has no Git commit reference | Medium | connect a future verified deploy to the repository default branch and document deterministic scoring limitations |
| `MVP-EGMH` | empty public repository | Unknown | identify the intended product and source before creating documentation or code |

## Highest-value next move

Retrieve the exact CEOnita source bundle that produced Netlify deploy `6ab8ebab2fc1f1352fa7da21`, including both deployed functions, then compare it with `claude/ceonita-strategik`. That is the shortest truthful path to a dedicated CEOnita repository, a canonical default branch and properly attributed future contributions.
