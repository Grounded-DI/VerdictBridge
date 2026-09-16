# VerdictBridge DI² - Litigation-Record Sufficiency and State Control

## Overview

VerdictBridge is a Grounded DI LLC litigation-record sufficiency and state-control system. It focuses on what a particular record can support, what remains disputed or expert-dependent, which procedural paths are open, and whether an analysis is ready for the proposed use.

This repository contains two separate synthetic records, supporting replay certificates, public-facing architecture visuals, and a marketplace-analysis paper. The records must be read separately: the Indiana Trucking / Turner book remains held, while the Lane v. Apex closed-world replay package records a different, completed benchmark state.

## Key records

| Artifact | What it records | Recorded status |
|---|---|---|
| [`Grounded_DI_LLC_Litigation_Artifact_Complete_Book_The_Indiana_Trucking_Demo_271_Pages.pdf`](./Grounded_DI_LLC_Litigation_Artifact_Complete_Book_The_Indiana_Trucking_Demo_271_Pages.pdf) | 271-page public-facing Turner / Indiana Trucking litigation-governance demonstration | Synthetic demonstration; **VerdictReady: No**; export held |
| [`05_verdictbridge_demo-run1.zip`](./05_verdictbridge_demo-run1.zip) and [`05_verdictbridge_demo-run2.zip`](./05_verdictbridge_demo-run2.zip) | Four-file Lane v. Apex controlled replay package | Byte-for-byte identical; **VerdictReady: YES**; export authorized in the benchmark record |
| [`VerdictBridge_Legal_Reasoning_Five_Hash_Replay_Certificate.pdf`](./VerdictBridge_Legal_Reasoning_Five_Hash_Replay_Certificate.pdf) | Comparison of the two replay archives and four internal artifact hashes | **PASS**; 0 byte mismatches; 0 state-transition mismatches |
| [`FastPath_5_6_Instant_Day_One_Canonical_Replay_Certificate.pdf`](./FastPath_5_6_Instant_Day_One_Canonical_Replay_Certificate.pdf) | Three executions of one sealed canonical replay test | **PASS**; 0 record mismatches; 0 hash mismatches; 0 observed replay divergence |
| [`FastPath_5_6_Instant_Day_One_Canonical_Replay_Certificate_Hash_Match_Screenshot.pdf`](./FastPath_5_6_Instant_Day_One_Canonical_Replay_Certificate_Hash_Match_Screenshot.pdf) | Screenshot record of a separate baseline-reproduction / replay-review state | Baseline reproduction pass; replay review required; export held |
| [`VerdictBridge_What_Can_This_Record_Actually_Support_Marketplace_Analysis.pdf`](./VerdictBridge_What_Can_This_Record_Actually_Support_Marketplace_Analysis.pdf) | Public category and business-development explanation | Public-facing analysis |

Supporting visuals are [`VerdictBridge_Runtime_Stack.jpg`](./VerdictBridge_Runtime_Stack.jpg), [`Contradiction_and_Verdict_Pressure_Architecture.PNG`](./Contradiction_and_Verdict_Pressure_Architecture.PNG), and [`Procedural_Integrity_and_Trial_Architecture_Matrix.PNG`](./Procedural_Integrity_and_Trial_Architecture_Matrix.PNG).

## Proposition boundaries

| Proposition | What this repository records |
|---|---|
| Model capability | The underlying model's general ability is not benchmarked here. |
| Controlled execution | The supplied synthetic records show declared gate, state, and export paths for their specified inputs. |
| Replay / provenance | The replay certificates record exact archive identity, internal hashes, serialization, and state-transition results for the named runs. |
| Product status | The book and visuals are public demonstrations; the ZIPs are synthetic benchmark artifacts. |
| External validation | Independent reproduction or legal review outside the supplied records remains **UNVERIFIED**. |

## What the Turner book demonstrates

The 271-page book is a synthetic, public-facing defense-litigation demonstration involving collision facts, testimony, reconstruction opinions, comparative fault, medical causation, damages, exposure, settlement posture, procedural status, controlled sensitivity analysis, review status, and release control.

Its central control is record sufficiency rather than a single probability score. The book separates:

- supported, disputed, expert-dependent, evidentially incomplete, and held propositions;
- liability, damages, expert, procedural, and appellate-record dependencies; and
- generating an output, validating an output, and authorizing reliance on an output.

The visible replay examples preserve competing speed estimates, keep an unsupported future knee-replacement claim held, and maintain separate future-earning-capacity theories. A changed speed predicate changes comparative-fault-adjusted totals while leaving injuries, gross medical damages, wage records, and coverage structure unchanged. The book records the final state as:

```text
VerdictReady: No
FilingReady: Not applicable or not yet determinable for a later filing
Export: Held
```

That is a controlled result, not a failed business outcome: useful analysis was retained without labeling it approved or ready for reliance.

## Controlled replay record

The two ZIPs are a separate synthetic closed-world benchmark for `Lane v. Apex Industrial Tools, Inc.` The package contains a canonical input, normalized record, gate matrix, and assessment. The certificate records:

- both archives at **34,903 bytes** with identical SHA-256 `27aa8744af4143884c3c41b6d7a3ff4a2fe90e585bb914c71bc9fc75c9e3df6a`;
- **0** byte-level mismatches and **0** state-transition mismatches;
- four internal artifact hashes matching between runs;
- 58 facts and 20 benchmark law statements in the canonical record;
- all four requested summary-judgment grounds denied under the benchmark record;
- the Sam Reed statement excluded and not used;
- all listed gates passing except gates marked `NOT_ACTIVE` or `NOT_APPLICABLE`; and
- `VERDICT_READY` with `export_authorized: true` in that synthetic benchmark.

The benchmark's law is a closed-world input. The replay result therefore establishes control and artifact identity for that specified record; it does not establish general legal correctness, predictive validity, or permission to use the output in a real matter.

The FastPath 5.6 certificate is another separate record. It documents three executions of one sealed `controlled_speed_branch_replay` input, all with SHA-256 `84ab1d149c18715b4f2c3646ab6469f00ea453770f7a0ff94738d42310b55f9d`. Its scope is that named test only; it does not establish universal determinism across other inputs, prompts, tools, environments, or runtime conditions.

## Technical significance

VerdictBridge makes a useful distinction operational: a polished memo, a recalculated number, or a model output is not automatically ready for attorney reliance. The records preserve dependencies, contradiction handling, admissibility and procedural gates, replay identity, reviewer state, and export authorization as separate control points. This is valuable for defense-firm evaluation because a new fact can be traced to the conclusions it changes without silently rewriting unrelated parts of the case.

## Scope and regulator-facing boundaries

The Indiana Trucking / Turner book, its visuals, and the replay package are synthetic public-facing materials. They are not an actual case, client matter, legal opinion, claims-handling directive, reserve-setting instruction, coverage determination, settlement authority, product specification, or authorization for reliance.

The repository does not claim:

- a guaranteed verdict, settlement, motion, mediation, trial, or appellate result;
- a statistical jury oracle or universal predictive accuracy;
- that uncertainty can be eliminated from litigation;
- that a closed-world benchmark's law is current law in any jurisdiction;
- that the public visuals disclose the complete proprietary architecture; or
- independent third-party validation of the system, legal conclusions, or business claims.

The public visuals are conceptual explanations. They do not disclose proprietary prompts, source code, private schemas, internal thresholds, confidential client information, or complete routing logic. Attorney and specialist review remains required for real-world use.

## How to review

1. Read the [Turner book](./Grounded_DI_LLC_Litigation_Artifact_Complete_Book_The_Indiana_Trucking_Demo_271_Pages.pdf) introduction and Chapter 9 for the synthetic record, state controls, replay branches, and held export state.
2. Extract either replay ZIP and compare it with the other; confirm the certificate's archive and internal hashes.
3. Read `04_verdictbridge_assessment.txt` and `03_gate_matrix.json` inside the ZIP for the exact benchmark dispositions.
4. Read the [five-hash certificate](./VerdictBridge_Legal_Reasoning_Five_Hash_Replay_Certificate.pdf) and the [FastPath 5.6 certificate](./FastPath_5_6_Instant_Day_One_Canonical_Replay_Certificate.pdf) for their separate scopes.
5. Use the [marketplace analysis](./VerdictBridge_What_Can_This_Record_Actually_Support_Marketplace_Analysis.pdf) and visuals for the public-facing product explanation.

## Provenance

The public repository state reviewed here is commit [`e74351a9ba7c11de44ae6b383337946825147d3c`](https://github.com/Grounded-DI/VerdictBridge/commit/e74351a9ba7c11de44ae6b383337946825147d3c). The replay certificate and ZIP hashes identify the bytes covered by those records; a hash establishes identity of the hashed bytes, not the substantive truth of every legal or factual statement displayed within them.

## Relationship to BriefWise

VerdictBridge asks whether the present litigation record and analysis support the proposed litigation state. BriefWise asks whether a legal proposition is sufficiently supported, verified, and filing-eligible. They are complementary control points, not interchangeable certifications.

## Public status and contact

**PUBLIC-FACING SYNTHETIC DEMONSTRATIONS · REPLAY ARTIFACTS PRESERVED · EXTERNAL VALIDATION UNVERIFIED**

Grounded DI LLC · Mark S. Weinstein

VerdictBridge, BriefWise, and Grounded DI are proprietary to Grounded DI LLC and may be protected by pending patent applications, copyright, trademark, contract, and other applicable rights. No license is granted by this README.

© 2026 Grounded DI LLC.
