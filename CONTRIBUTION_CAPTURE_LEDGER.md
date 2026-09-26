# ZKB-10 Contribution Capture Ledger

This ledger records evidence-backed GitHub portfolio repairs. It does not measure success by commit count and does not backdate, rewrite or manufacture activity.

## Rolling seven-day window: 21–27 September 2026

| Measure | Verified position |
|---|---|
| Priority repositories inspected | `MVP-EVOS-Mara`, `MVP-MKH`, `zaiwin-lab`, `MVP-EGMH`, `MVP-KB`, `KDP-EGMegah`, `MasterHub`, `google-maps-scraper` |
| Meaningful repair commits made on 27 September | 3 |
| Default-branch repair commits | 2 — My Kenyalang Homes documentation and main-profile portfolio selection |
| Non-default documentation repair | 1 — CEOnita recovery README |
| Recent commits with attribution mismatch | 38 — 33 on the CEOnita branch and 5 on My Kenyalang Homes, all authored/committed as `claude` |
| Stranded development work | CEOnita branch: 46 commits ahead of Attendify’s default branch |
| READMEs corrected | 2 |
| Verified live URL promoted | [mkhomes.win](https://mkhomes.win) |
| Missing or non-canonical projects | CEOnita, BTD Koperasi and the empty `MVP-EGMH` placeholder |

## 27 September 2026 — verified repairs

### CEOnita Strategik

- **Source found:** [`MVP-EVOS-Mara/tree/claude/ceonita-strategik`](https://github.com/zaiwin-lab/MVP-EVOS-Mara/tree/claude/ceonita-strategik)
- **State:** substantial recoverable application, 46 commits ahead of the Attendify default branch.
- **Repair:** replaced the inherited Attendify README on that branch with a CEOnita product, architecture, safety and recovery record.
- **Evidence:** [commit `4b13239`](https://github.com/zaiwin-lab/MVP-EVOS-Mara/commit/4b13239e9890ed25d5596e35c15e88fa5b72f349)
- **Still unresolved:** no dedicated repository, no verified live URL, stale ProgramOS/ANGKASA/Attendify labels in selected files, and non-owner commit attribution.

### My Kenyalang Homes

- **Repository:** [`MVP-MKH`](https://github.com/zaiwin-lab/MVP-MKH)
- **Verified public site:** [mkhomes.win](https://mkhomes.win)
- **Repair:** corrected the README from “no backend” to the evidenced Netlify Forms → signed webhook → Supabase mirror, documented the security model and recorded the live-build/source drift.
- **Evidence:** [commit `dd2fa3d`](https://github.com/zaiwin-lab/MVP-MKH/commit/dd2fa3d81a4061a17cd164618112682b880c8bfe)
- **Still unresolved:** the live Netlify build differs from Git and must be captured before the next repository-driven deployment.

### Main profile

- Replaced the weaker KBT RewardOS concept row with My Kenyalang Homes, which has a verified live platform and stronger operational evidence.
- Added this rolling ledger in the same commit so the profile improvement and its evidence remain one legitimate change set.

## Attribution findings

The CEOnita branch’s recent work and the five My Kenyalang Homes backend commits inspected in this window use GitHub identity `claude` as both author and committer. The CEOnita commits are additionally on a non-default branch.

Do not rewrite that history. The safe forward fix is:

1. make future accepted commits from the `zaiwin-lab` account or an email verified on that account;
2. retain an AI co-author trailer where appropriate;
3. keep each commit substantive;
4. move CEOnita into a dedicated repository through a current-date recovery commit after source reconciliation.

## Missing from GitHub / recovery backlog

| Project | Evidence | Recoverability | Exact next capture action |
|---|---|---|---|
| CEOnita Strategik | substantial source on the CEOnita branch; programme configuration dated 28–29 September 2026 | High | compare against any deployed build, sanitise stale inherited material, then create a dedicated repository with a current-date provenance note |
| BTD Koperasi / ProgramOS Lite | [btdkoperasi.win](https://btdkoperasi.win) verified reachable on 27 September 2026; ProgramOS history exists inside the CEOnita branch ancestry | Medium–High | obtain the exact Netlify deploy source, compare it with the pre-CEOnita commits and recover the canonical BTD repository without rewriting history |
| MVP-EGMH | empty public repository | Unknown | identify the intended product and source before creating documentation or code |
| My Kenyalang Homes live build | repository itself states production drift from Git | High | export the current Netlify artifact/source and reconcile the four documented live-only differences into the default branch |

## Highest-value next move

Recover CEOnita into a dedicated repository **after** comparing the branch with the actual deployed build. That single action will separate it from Attendify, preserve a truthful provenance trail, allow a clean default branch and make future owner-attributed work visible without manufacturing history.
