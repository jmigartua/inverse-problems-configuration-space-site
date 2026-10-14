# Third audit report — 14 October 2026

**Review record · L013 · awaiting Josu's and Iñigo's review.** Prepared by Codex (AI assistant), following the review reported in the project conversation. This is a further assessment of the citation audit, published as the third report alongside the original audit and Claude's review. It is not an independent external assessment, a peer-reviewed publication, or authorization to revise the scientific pages.

**Suggested citation:** Codex (2026), *Third audit report — 14 October 2026*, inverse-problems-configuration-space project, review record L013. No DOI assigned. Permanent URL: [third audit report](https://jmigartua.github.io/inverse-problems-configuration-space-site/sources/third-audit-2026-10-14/).

**Scope and method:** The preceding conversation review reread the original 42 claim records, compared their website locations, and rechecked selected critical source passages. It also accessed Raue's full online article, whose definitions had previously been assessed only through the abstract. The seven findings below preserve that review's substantive conclusions, with stable identifiers R01–R07 and links added for this public edition. They are seven methodological and substantive issues, not a new classification of all 42 claims. The mathematical cautions and additional gaps are reviewer reasoning unless a source is explicitly identified.

**Relationship to earlier reports:** The first report is the citation support audit (L009–L011); the second is Claude's *The audit reviewed* (L012). This third report qualifies the original audit and records where its assessment differs from the second report's broad acceptance. It does not claim to have independently repeated every check in L012. In particular, the second report accepts C34 as a factual error and summarizes C25–C27 together; this report distinguishes ambiguous wording from a contradicted factual assertion. All three records remain proposals for human review.

**Version and preservation:** The original audit concerns website commit `bcdd0903be508931384d24f672fe3cc9d1e17c25`. This edition was prepared against project commit `308b665`, which includes the second report. Existing scientific pages, original claim records, and both earlier reports are preserved. Links open the current pages; quoted wording identifies what was assessed. No revised verdict totals or scientific corrections are applied by publication.

[First report](../citation-audit-2026-10-14/index.html) · [Second report](../audit-review-2026-10-14/index.html) · [This report's log](../../log/index.html#L013) · [Sources](../index.html) · [Download this report](report.md) · [Provenance](provenance.json)

The audit is useful, but it needs corrections before its verdicts should be treated as settled. Its strongest findings survive this second pass by Codex; some classifications are too strong, some paraphrases are unfair to the original text, and several important claims escaped assessment. These criticisms concern the audit's precision, not a rejection of the underlying research programme.

## Findings at a glance

| Verdict | Review findings |
| --- | ---: |
| Narrow the assessment | 3 |
| New evidence to incorporate | 1 |
| State the assumptions | 1 |
| Extend the coverage | 1 |
| Revise the reporting method | 1 |

The seven review findings group related issues. Their counts are navigation aids, not a quality score and not a replacement for the original audit's 42 verdicts. The original identifiers C01–C42 always refer to the first audit; R01–R07 identify this report's findings.

## Review findings

### R01

**The audit sometimes strengthens a statement before criticizing it**

**Verdict:** Narrow the assessment.

**Audit finding:** [C24 in the original audit](../citation-audit-2026-10-14/index.html#c24); [C34 in the original audit](../citation-audit-2026-10-14/index.html#c34); [C24 in the second report](../audit-review-2026-10-14/index.html#c24); [C34 in the second report](../audit-review-2026-10-14/index.html#c34)

**Website sentence:** The Rietveld page says “What none of these does is what T07 and T09 together ask for” after discussing three studies. The Drude page says the laser-driven source “reaches the surface-plasmon resonance near 190 nm”.

**Website locations:** [Rietveld: what is scripted](../../cases/rietveld/index.html); [Drude: Fig. 9 discussion](../../cases/drude/index.html)

**Assessment:** C24 paraphrases a comparison with three papers as a claim that the wider field does not perform the proposed workflow. Those are different assertions. Broader novelty claims occur elsewhere on the website, but require their own exact quotations and locations. The second report also recognizes this distinction in C24. In C34, the audit inserts “peak” into its paraphrase. The measurement begins at 205 nm, so it excludes the peak near 190 nm but captures part of the resonance feature. Clarification is useful; ambiguous wording is a fairer assessment than an unequivocal factual error in the original sentence.

**Checked against:** The website sentences and Daun's measured range and explanation of the SPR feature.

- Printed pp. 152 and 154, Fig. 7 and discussion of Fig. 9 (full-text passage). [daun2019 — source](https://doi.org/10.1016/j.jqsrt.2019.01.021) · [DOI 10.1016/j.jqsrt.2019.01.021](https://doi.org/10.1016/j.jqsrt.2019.01.021) · PDF page 7 (reviewed local copy) · PDF page 9 (reviewed local copy)

**Proposed wording or action:** Split C24's narrow comparison from the field-wide novelty claim. In C34, distinguish the resonance feature from its peak and describe the shoulder captured by the measured band. Retain the evidence; narrow the verdict.

### R02

**C25's detailed assessment is more careful than the surrounding summaries**

**Verdict:** Narrow the assessment.

**Audit finding:** [C25 in the original audit](../citation-audit-2026-10-14/index.html#c25); [C25 in the second report](../audit-review-2026-10-14/index.html#c25); [L009 summary](../../log/index.html#L009); [L012 summary](../../log/index.html#L012)

**Website sentence:** The dielectric case describes “a free causal function anchored by a few oscillators”.

**Assessment:** Kuzmenko combines a limited-parameter background model with a dense variational representation. The website phrase can reasonably refer to the background. C25 acknowledges that interpretation and asks for clarification. L009 instead summarizes the issue as the dense mesh being described as a few oscillators, making the original wording sound more clearly wrong than it is. L012 likewise groups this with misdescriptions of the method. The careful distinction in the detailed finding should govern the summaries.

**Checked against:** Kuzmenko's two-step construction, including the fixed background and adjustable variational contribution.

- Printed 083108-4, §IV.D, especially Eq. (17) (full-text passage). [kuzmenko2005 — source](https://doi.org/10.1063/1.1979470) · [DOI 10.1063/1.1979470](https://doi.org/10.1063/1.1979470) · PDF page 6 (reviewed local copy)

**Proposed wording or action:** Distinguish the background from the dense variational mesh. Do not claim that the website necessarily confused them. Any later correction to a historical summary should be explicitly dated rather than silently replacing the original assessment.

### R03

**The full Raue article exposes a consequential difference in definitions**

**Verdict:** New evidence to incorporate.

**Audit finding:** [C06](../citation-audit-2026-10-14/index.html#c06); [C17](../citation-audit-2026-10-14/index.html#c17); [C39](../citation-audit-2026-10-14/index.html#c39)

**Assessment:** Raue's full article was accessible during the conversation review. In §2.3.2, its operational definition of practical non-identifiability requires an unbounded likelihood-based confidence region despite a unique likelihood minimum. That is more specific than a parameter being poorly constrained or having a small sensitivity. C06 correctly identifies the paper's subject, but this does not establish that the website uses its definitions faithfully. The earlier abstract-only limitation was honestly recorded; the newly accessible full text allows that evidence gap to be narrowed.

**Checked against:** Full online article, §§2.3.1–2.3.2, Definition 1, and §3. Selected sections were read; this is not a claim to have read the entire article in full.

- §§2.3.2 and 3, practical non-identifiability and limits of curvature-based diagnostics (full-text passage). [raue2009 — source](https://academic.oup.com/bioinformatics/article/25/15/1923/213246) · [DOI 10.1093/bioinformatics/btp358](https://doi.org/10.1093/bioinformatics/btp358)

**Proposed wording or action:** Qualify C06 by stating the definition actually used. Distinguish local sensitivity, broad practical imprecision, and Raue's particular criterion. Preserve the earlier access status as historical and record this evidence update separately; do not promote the source to read in full.

### R04

**The mathematical corrections need explicit assumptions and limits**

**Verdict:** State the assumptions.

**Audit finding:** [C13](../citation-audit-2026-10-14/index.html#c13); [C17](../citation-audit-2026-10-14/index.html#c17); [C28](../citation-audit-2026-10-14/index.html#c28); [C41](../citation-audit-2026-10-14/index.html#c41)

**Independent reasoning:** C13 correctly rejects information creation through an invertible change of coordinates. Mode coordinates can nevertheless make identifiable combinations easier to interpret and computation easier to perform. C17's counterexamples distinguish local Jacobian rank from global uniqueness, but discrete global ambiguity and continuous local non-identifiability need separate names; literature conventions must be stated. C41's inverse-information covariance argument requires nonsingular information and the relevant local likelihood approximation. A prior changes posterior curvature, and a singular matrix cannot simply be inverted. C28's uniqueness of a partial-fraction representation does not by itself prove identifiability of every physical oscillator parameterization: it challenges universal non-uniqueness without supplying a complete general proof.

**Assessment:** These qualifications preserve the core mathematical criticisms. They prevent a corrective report from replacing one unconditional assertion with another or from dismissing useful computational and interpretive benefits.

**Proposed wording or action:** Attach the assumptions to each formula or counterexample. State precisely which assertion is disproved, and distinguish that result from a full identifiability proof for a specified physical model.

### R05

**C35 establishes a printed discrepancy, not what the authors actually computed**

**Verdict:** Narrow the assessment.

**Audit finding:** [C35 in the original audit](../citation-audit-2026-10-14/index.html#c35); [C35 in the second report](../audit-review-2026-10-14/index.html#c35)

**Assessment:** Daun's printed approximation-error sampling intervals and prior intervals differ. The audit correctly identifies this and leaves possible typographical errors unresolved. The supported conclusion is that the website's claim of matching ranges is not supported by the printed intervals. The audit cannot establish which ranges were used in the computation without code, supplementary evidence, or author clarification.

**Checked against:** The sampling text following Eq. (18) and the priors accompanying Eq. (22).

- Printed pp. 152–153, sampling intervals and prior bounds (full-text passage). [daun2019 — source](https://doi.org/10.1016/j.jqsrt.2019.01.021) · [DOI 10.1016/j.jqsrt.2019.01.021](https://doi.org/10.1016/j.jqsrt.2019.01.021) · PDF page 7 (reviewed local copy) · PDF page 8 (reviewed local copy)

**Proposed wording or action:** Describe the discrepancy as printed. Keep the implementation question open and do not silently choose corrected numerical inputs for a replication.

### R06

**Important claims remain outside the original audit's direct assessments**

**Verdict:** Extend the coverage.

**Website locations:** [Discourse: dielectric example](../../discourse/index.html#elsewhere); [Discourse: learning](../../discourse/index.html#learning); [Discourse: definitions](../../discourse/index.html#three)

**Independent reasoning:** The following are additional issues identified by this reviewer, not new results attributed to the cited papers.

- The statement that only a distribution is honest and every point estimate should be rejected is too strong. A point estimate can be useful when its assumptions, uncertainty and decision purpose are explicit; non-identifiability does not impose one mandatory reporting format.
- The requirement that mode parameters vary smoothly with temperature is a conditional physical assumption. A discontinuity can reflect a real transition.
- Repeated structured residuals can arise from shared calibration errors, instrument effects or preprocessing; they do not uniquely diagnose a wrong physical model.
- Published databases reflect selection, measurement and publication practices as well as the configurations observed in nature. They are not automatically a representative distribution of nature's configurations.
- A large ratio between sensitivity eigenvalues does not alone establish inadequate absolute precision. Sloppiness and practical identifiability require separate assessment with stated scales and noise.

**Assessment:** Coverage of all 21 source entries is not equivalent to checking every associated scientific assertion. The first audit was explicit that it was targeted, but its broad coverage statement can still be overread. The second report identifies further gaps of its own; neither gap list should be treated as exhaustive.

**Proposed wording or action:** Give these assertions their own exact quotations, locations and assessments in a future revision. Do not infer that unlisted statements have passed review.

### R07

**Verdict totals are bookkeeping, not a quality score**

**Verdict:** Revise the reporting method.

**Assessment:** The original totals are internally consistent, but the categories mix different dimensions: truth, citation support, access limitations and research proposals. Several findings also concern the same underlying passage. Counts of claim groups are neither independent observations nor an error rate for the website. The second report's acceptance totals likewise record that reviewer's judgments, not human approval to apply changes.

**Proposed wording or action:** For each assessed assertion, record the exact website quotation, source evidence, reviewer reasoning, assessment, confidence and proposed action separately. Distinguish contradicted, unsupported, ambiguous and dependent on assumptions. Keep access status separate from scientific correctness and an implementation proposal separate from an accepted decision.

## Findings that remain valuable

The strongest findings survive this review: Daun discounts surface scattering for the particles considered in that case (C33); a thresholded misfit set is not a posterior distribution (C18); amplitude magnitude is not uncertainty (C14); and an invertible coordinate change cannot manufacture experimental information (C13). These are reasons to retain the audit while making its own claims equally precise.

[Surface-scattering assessment](../citation-audit-2026-10-14/index.html#c33) · [Misfit set and posterior](../citation-audit-2026-10-14/index.html#c18) · [Amplitude and uncertainty](../citation-audit-2026-10-14/index.html#c14) · [Coordinates and information](../citation-audit-2026-10-14/index.html#c13)

## Status and next decision

This report records the review for future reference. It does not replace the original report, approve its proposed wording, or apply corrections to the scientific pages. Josu and Iñigo can review the differences among the three records before deciding which changes to accept. A later revision should identify the finding behind each accepted change and be logged separately.

The downloadable public edition and the rendered page have the same report content. The provenance file records the source versions and hashes of the earlier reports and this edition. No collected PDFs or private software snapshots are redistributed here.
