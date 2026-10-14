# Citation support audit — 14 October 2026

**Project review record · L009 / L010 · awaiting author review.** Prepared by Codex (AI assistant) for this project. This is an AI-assisted assessment, not a peer-reviewed publication or an approved revision of the scientific pages. Its verdicts and proposed wording remain open to correction by the project authors.

**Suggested citation:** Codex (2026), *Citation support audit — 14 October 2026*, inverse-problems-configuration-space project, review record L009, public edition L010. No DOI assigned. Permanent URL: [citation audit](https://jmigartua.github.io/inverse-problems-configuration-space-site/sources/citation-audit-2026-10-14/).

**Version and preservation:** This report assesses website commit `bcdd0903be508931384d24f672fe3cc9d1e17c25`. Original claim labels C01–C42, assessments and proposed wording are retained. Navigation and mathematical typesetting are adapted for the website. File line numbers refer to the reviewed snapshot; website links open the current pages. Publishing this report does not apply its proposed corrections.

[Publication log (L010)](../../log/index.html#L010) · [Original audit log (L009)](../../log/index.html#L009) · [Sources](../index.html) · [Download this public report](report.md) · [Archive provenance](provenance.json)

<details><summary>Browse the 42 findings</summary>

- [C01 — Hadamard and the modern definition](#c01)
- [C02 — Probabilistic inverse problems](#c02)
- [C03 — Kaipio and Somersalo and approximation error](#c03)
- [C04 — Kennedy and O’Hagan and physical parameter meaning](#c04)
- [C05 — Bias and overconfidence from ignored discrepancy](#c05)
- [C06 — Raue and the identifiability distinction](#c06)
- [C07 — Homometry versus a linear null space](#c07)
- [C08 — Rietveld profile refinement and forward-model certainty](#c08)
- [C09 — What mode crystallography demonstrably provides](#c09)
- [C10 — AMPLIMODES decomposition and refinement output](#c10)
- [C11 — ISODISPLACE and orthonormal basis conventions](#c11)
- [C12 — Primary-mode hierarchy and sparse priors](#c12)
- [C13 — Symmetry modes do not necessarily diagonalize the data sensitivity](#c13)
- [C14 — Amplitude magnitude is not uncertainty](#c14)
- [C15 — Sloppy sensitivity spectra](#c15)
- [C16 — A small singular value needs a parameter scale](#c16)
- [C17 — Local Jacobian rank is not a complete structural-identifiability test](#c17)
- [C18 — A likelihood region is not a posterior](#c18)
- [C19 — The model-manifold description](#c19)
- [C20 — Cranmer supports approximate amortized inference, not guaranteed recovery](#c20)
- [C21 — Park dataset and accuracy figures](#c21)
- [C22 — Lee dataset size and chemical scope](#c22)
- [C23 — Szymanski probabilities are phase-classification confidence](#c23)
- [C24 — The three ML papers are precedents, not the proposed mode-refinement pipeline](#c24)
- [C25 — Kuzmenko’s background model and dense variational mesh](#c25)
- [C26 — Phase recovery needs analytic and geometry conditions](#c26)
- [C27 — Unmeasured spectral weight is not generically invisible](#c27)
- [C28 — Oscillator non-identifiability is not universal](#c28)
- [C29 — difes software claims and optical assumptions](#c29)
- [C30 — A missing primary source for finite-range correction](#c30)
- [C31 — The thesis cannot yet support a detailed technical claim](#c31)
- [C32 — Daun experimental conditions and tabulated parameters](#c32)
- [C33 — Daun surface scattering explanation is reversed](#c33)
- [C34 — The LDLS sees the shoulder, not the 190 nm peak](#c34)
- [C35 — Daun approximation-error sampling is not the stated prior range](#c35)
- [C36 — Low-frequency Drude degeneracy is a limiting approximation](#c36)
- [C37 — A surrogate does not automatically remove model error](#c37)
- [C38 — Expected information gain is not determined by a Jacobian alone](#c38)
- [C39 — The P1 diagnostic cannot identify all three failure types alone](#c39)
- [C40 — Data availability and reproducibility claims](#c40)
- [C41 — A covariance diagonal is not a conditional tube cross-section](#c41)
- [C42 — Transferability and parameter-point dependence](#c42)

</details>

Reviewed 14 October 2026 against website commit `bcdd090`.

Several references support the website’s factual summaries, but the surrounding argument sometimes makes stronger claims than those sources establish. The corrections concern both fidelity to a paper and the distinction between an established result and a proposed extension. A verified DOI is not evidence that a particular sentence is supported.

All 21 source-table entries and their associated uses in the Discourse, three Cases and Programme; 42 claim groups, including closely related mathematical extrapolations. The founding brief is preserved as attributed ideas. This is a targeted citation and claim audit, not independent replication of every paper or a proof audit of every sentence.

Relevant passages in 14 local PDFs; four author/publisher abstracts for unavailable articles; indirect attribution for the unavailable Kaipio book; versioned difes documentation/code; the thesis remains bibliographic only. PDF page numbers count repository covers. Proposed wording is for review and has not been applied to the scientific pages.

## Findings at a glance

| Verdict | Claim groups |
| --- | ---: |
| Supported within stated scope | 11 |
| Needs qualification or a better citation | 13 |
| Incorrect as written | 11 |
| Not fully verified | 3 |
| Proposal presented too strongly | 4 |

These counts concern the 42 selected claim groups, not the quality of 42 papers. A paper can support one sentence and fail to support another. “Incorrect” applies to the website wording; it does not imply that the cited paper is incorrect.

## Priority corrections

- [C33](#c33): Daun’s treatment of surface scattering is reversed in the website.
- [C25](#c25): Kuzmenko’s background model and dense variational mesh need to be distinguished.
- [C26](#c26): Reflection phase recovery omits necessary analytic and geometry conditions.
- [C13](#c13): A symmetry basis does not automatically remove experimental ambiguity.
- [C17](#c17): Local Jacobian rank, global ambiguity and continuous non-identifiability are conflated.
- [C18](#c18): The data-misfit tube is a set, not a posterior distribution.
- [C35](#c35): Daun’s printed approximation-error ranges do not match its prior ranges.

## Source coverage

PDF page numbers below are file page numbers, including covers. Printed page numbers and sections appear in the detailed findings. Public links open publisher or repository records. PDF page locators refer to the local copies reviewed; those copies are not hosted here. Reading selected passages does not mean that a whole book or article has been read in full.

| Source | Evidence available for this audit | Findings |
| --- | --- | --- |
| [daun2019](https://linkinghub.elsevier.com/retrieve/pii/S0022407318309178) | full-text passage; PDF pages 2, 4, 6, 7, 8, 9, 10 | [C03](#c03), [C18](#c18), [C32](#c32), [C33](#c33), [C34](#c34), [C35](#c35), [C36](#c36), [C37](#c37), [C38](#c38), [C40](#c40) |
| [perezmato2010](https://journals.iucr.org/paper?S0108767310016247) | full-text passage; PDF pages 1, 7, 8 | [C09](#c09), [C12](#c12), [C13](#c13), [C14](#c14) |
| [orobengoa2009](https://journals.iucr.org/paper?S0021889809028064) | full-text passage; PDF pages 1, 4, 5, 13 | [C10](#c10), [C11](#c11) |
| [campbell2006](https://journals.iucr.org/paper?S0021889806014075) | full-text passage; PDF pages 5, 8 | [C11](#c11) |
| [rietveld1969](https://onlinelibrary.wiley.com/doi/abs/10.1107/S0021889869006558) | abstract only | [C08](#c08) |
| [patterson1944](https://journals.aps.org/pr/abstract/10.1103/PhysRev.65.195) | abstract only | [C07](#c07), [C17](#c17) |
| [hadamard1902](https://illposed.net/hadamard.pdf) | full-text passage; PDF pages 1, 2 | [C01](#c01) |
| [tarantola2005](https://epubs.siam.org/doi/book/10.1137/1.9780898717921) | full-text passage; PDF pages 13, 49 | [C02](#c02), [C18](#c18), [C38](#c38) |
| [kaipio2005](https://link.springer.com/10.1007/b138659) | indirect attribution only | [C03](#c03) |
| [kennedy2001](https://academic.oup.com/jrsssb/article/63/3/425/7083367) | abstract only | [C04](#c04) |
| [brynjarsdottir2014](https://iopscience.iop.org/article/10.1088/0266-5611/30/11/114007) | full-text passage; PDF pages 1, 3 | [C04](#c04), [C05](#c05), [C39](#c39) |
| [raue2009](https://pubmed.ncbi.nlm.nih.gov/19505944/) | abstract only | [C06](#c06), [C17](#c17), [C39](#c39) |
| [gutenkunst2007](https://dx.plos.org/10.1371/journal.pcbi.0030189) | full-text passage; PDF pages 2, 3 | [C14](#c14), [C15](#c15), [C41](#c41) |
| [transtrum2015](https://pubs.aip.org/jcp/article/143/1/010901/566995/Perspective-Sloppiness-and-emergent-theories-in) | full-text passage; PDF pages 3, 5, 6 | [C13](#c13), [C15](#c15), [C16](#c16), [C19](#c19), [C39](#c39), [C42](#c42) |
| [cranmer2020](https://pnas.org/doi/full/10.1073/pnas.1912789117) | full-text passage; PDF pages 7, 8 | [C20](#c20), [C37](#c37), [C42](#c42) |
| [park2017](https://journals.iucr.org/paper?S205225251700714X) | full-text passage; PDF pages 1, 3, 5 | [C21](#c21), [C24](#c24) |
| [lee2020](https://www.nature.com/articles/s41467-019-13749-3) | full-text passage; PDF pages 1, 2 | [C22](#c22), [C24](#c24) |
| [szymanski2021](https://pubs.acs.org/doi/10.1021/acs.chemmater.1c01071) | full-text passage; PDF pages 3, 4 | [C23](#c23), [C24](#c24) |
| [kuzmenko2005](https://pubs.aip.org/rsi/article/76/8/083108/822925/Kramers-Kronig-constrained-variational-analysis-of) | full-text passage; PDF pages 3, 5, 6 | [C25](#c25), [C26](#c26), [C27](#c27), [C28](#c28) |
| [difes2026](https://github.com/jmigartua/difes) | versioned software source | [C29](#c29), [C30](#c30) |
| [gonzalezdearrieta2020](https://hdl.handle.net/10810/50263) | bibliographic context only | [C31](#c31) |

## Claim by claim assessment

### C01 {#c01}

**Hadamard and the modern definition**

**Verdict:** Needs qualification or a better citation.

**Website claim:** Hadamard 1902 supplies existence, uniqueness and continuous dependence; an underdetermined inverse problem fails the second and third.

**Website locations:** [ecosystem/data/sources.yml:70](../index.html)

**Evidence and assessment:** The original scan opens on printed p. 49 by explaining bien posé in terms of possibility and determinacy. It is an appropriate historical reference, but the modern three-part formulation needs a precise modern source. Non-uniqueness alone does not establish a separate instability result for a chosen regularized solution.

- Printed pp. 49–50; opening definition and Cauchy/Dirichlet discussion (full-text passage). [hadamard1902 — source](https://illposed.net/hadamard.pdf) · PDF page 1 (reviewed local copy) · PDF page 2 (reviewed local copy)

**Proposed wording or action:** Hadamard provides a historical discussion of well-posedness. In the modern formulation, existence, uniqueness and continuous dependence are separate requirements; non-uniqueness violates uniqueness. Add a modern definition with its spaces and topology.

### C02 {#c02}

**Probabilistic inverse problems**

**Verdict:** Supported within stated scope.

**Website claim:** Tarantola represents the inverse solution as a probability distribution over models.

**Website locations:** [ecosystem/data/sources.yml:79](../index.html)

**Evidence and assessment:** The preface explicitly describes the update from prior to posterior, and §1.5 gives posterior density proportional to prior density times likelihood. This supports the stated use.

- Preface p. xi; §1.5 p. 35, Eqs. (1.94)–(1.100) (full-text passage). [tarantola2005 — source](https://epubs.siam.org/doi/book/10.1137/1.9780898717921) · [DOI 10.1137/1.9780898717921](https://doi.org/10.1137/1.9780898717921) · PDF page 13 (reviewed local copy) · PDF page 49 (reviewed local copy)

**Proposed wording or action:** Retain; cite the preface, p. xi, and §1.5, p. 35, Eqs. (1.94)–(1.100).

### C03 {#c03}

**Kaipio and Somersalo and approximation error**

**Verdict:** Not fully verified.

**Website claim:** Kaipio and Somersalo supply the mean-and-covariance approximation-error method used by Daun.

**Website locations:** [ecosystem/data/sources.yml:88](../index.html)

**Evidence and assessment:** Daun p. 152 explicitly attributes the Gaussian approximation-error construction to reference [40]. This verifies Daun’s use and attribution. The Kaipio–Somersalo book itself is unavailable locally, so its exact chapter and formulation have not been independently checked.

- Full book unavailable (indirect attribution only). [kaipio2005 — source](https://link.springer.com/10.1007/b138659) · [DOI 10.1007/b138659](https://doi.org/10.1007/b138659)
- Printed p. 152, discussion of Eq. (18) (full-text passage). [daun2019 — source](https://linkinghub.elsevier.com/retrieve/pii/S0022407318309178) · [DOI 10.1016/j.jqsrt.2019.01.021](https://doi.org/10.1016/j.jqsrt.2019.01.021) · PDF page 7 (reviewed local copy)

**Proposed wording or action:** Daun et al., p. 152, Eq. (18), use an approximation-error distribution following Kaipio and Somersalo. Retain the book as a secondary attribution until its relevant pages are obtained.

### C04 {#c04}

**Kennedy and O’Hagan and physical parameter meaning**

**Verdict:** Needs qualification or a better citation.

**Website claim:** The parameters lose their physical meaning when discrepancy is omitted.

**Website locations:** [ecosystem/data/sources.yml:96](../index.html)

**Evidence and assessment:** The publisher summary supports Bayesian calibration with model discrepancy and parameter uncertainty. It does not establish the unconditional statement that all calibrated parameters lose physical meaning. Brynjarsdóttir and O’Hagan directly examine bias and confounding and are the more precise source for that warning.

- Publisher summary (abstract only). [kennedy2001 — source](https://academic.oup.com/jrsssb/article/63/3/425/7083367) · [DOI 10.1111/1467-9868.00294](https://doi.org/10.1111/1467-9868.00294)
- Author manuscript abstract and p. 3 principal findings (full-text passage). [brynjarsdottir2014 — source](https://iopscience.iop.org/article/10.1088/0266-5611/30/11/114007) · [DOI 10.1088/0266-5611/30/11/114007](https://doi.org/10.1088/0266-5611/30/11/114007) · PDF page 1 (reviewed local copy) · PDF page 3 (reviewed local copy)

**Proposed wording or action:** Ignoring a nonzero model discrepancy can bias estimates of physical parameters. Adding a discrepancy term does not by itself identify those parameters; informative assumptions about discrepancy may be needed.

### C05 {#c05}

**Bias and overconfidence from ignored discrepancy**

**Verdict:** Supported within stated scope.

**Website claim:** Ignoring model discrepancy can produce biased and overconfident parameter inference.

**Website locations:** [ecosystem/data/sources.yml:105](../index.html); [ecosystem/site/discourse/index.qmd:24](../../discourse/index.html)

**Evidence and assessment:** The manuscript abstract and principal findings support this claim, and also warn that a flexible discrepancy function is confounded with calibration parameters. The website’s main warning is sound when stated conditionally.

- Manuscript pp. 1 and 3; §2 gives the observation model (full-text passage). [brynjarsdottir2014 — source](https://iopscience.iop.org/article/10.1088/0266-5611/30/11/114007) · [DOI 10.1088/0266-5611/30/11/114007](https://doi.org/10.1088/0266-5611/30/11/114007) · PDF page 1 (reviewed local copy) · PDF page 3 (reviewed local copy)

**Proposed wording or action:** Retain “can” rather than an unconditional “are”; add that discrepancy modelling requires physically meaningful priors when physical parameter recovery is the goal.

### C06 {#c06}

**Raue and the identifiability distinction**

**Verdict:** Supported within stated scope.

**Website claim:** Raue distinguishes structural from practical non-identifiability and uses profile likelihood.

**Website locations:** [ecosystem/data/sources.yml:113](../index.html); [ecosystem/site/discourse/index.qmd:18](../../discourse/index.html)

**Evidence and assessment:** The author abstract reproduced in PubMed explicitly supports these three points: structural functional relationships, practical limitations from data quantity and quality, and profile-likelihood confidence intervals. Only the abstract was accessible; it does not validate all later Jacobian claims on the website.

- Author abstract, Results (abstract only). [raue2009 — source](https://pubmed.ncbi.nlm.nih.gov/19505944/) · [DOI 10.1093/bioinformatics/btp358](https://doi.org/10.1093/bioinformatics/btp358)

**Proposed wording or action:** Retain the terminology citation. Mark the evidence as abstract-level; verify detailed algorithmic claims against the full article before assigning page-level support.

### C07 {#c07}

**Homometry versus a linear null space**

**Verdict:** Needs qualification or a better citation.

**Website claim:** Homometric structures give identical intensities and constitute an exact null space.

**Website locations:** [ecosystem/data/sources.yml:59](../index.html); [ecosystem/site/cases/rietveld/index.qmd:20](../../cases/rietveld/index.html); [ecosystem/site/discourse/index.qmd:20](../../discourse/index.html)

**Evidence and assessment:** Patterson’s publisher abstract supports distinct non-congruent point sets with the same vector-distance set. It supports non-uniqueness, not the stronger characterization as a linear null space or necessarily a continuous family. For weighted atomic species the relevant equality is the weighted autocorrelation, not an unweighted set of vectors alone.

- Publisher abstract (abstract only). [patterson1944 — source](https://journals.aps.org/pr/abstract/10.1103/PhysRev.65.195) · [DOI 10.1103/PhysRev.65.195](https://doi.org/10.1103/PhysRev.65.195)

**Independent reasoning:** A nonlinear map can have disconnected preimages without a positive-dimensional fibre. For F(x)=x², F⁻¹(1)={−1,+1}, while F′(±1) is nonzero.

**Proposed wording or action:** Homometric structures provide distinct solutions with the same diffraction intensities. Describe these as exact ambiguities; reserve “null space” for a linear map or its local Jacobian.

### C08 {#c08}

**Rietveld profile refinement and forward-model certainty**

**Verdict:** Needs qualification or a better citation.

**Website claim:** Rietveld supplies profile least squares, and nothing in the forward map is in doubt.

**Website locations:** [ecosystem/site/cases/rietveld/index.qmd:16](../../cases/rietveld/index.html); [ecosystem/data/sources.yml:51](../index.html)

**Evidence and assessment:** The original publisher abstract supports direct use of step-scan neutron profile intensities in least-squares refinement and parameter constraints. It does not support the absolute assertion of a doubt-free forward model. Background, peak shapes, preferred orientation, microstructure and missing phases remain modelling choices.

- Original publisher abstract (abstract only). [rietveld1969 — source](https://onlinelibrary.wiley.com/doi/abs/10.1107/S0021889869006558) · [DOI 10.1107/S0021889869006558](https://doi.org/10.1107/S0021889869006558)

**Proposed wording or action:** Rietveld refinement fits calculated profile intensities to observed powder data by least squares. Its physical and instrumental model must still be assessed for adequacy.

### C09 {#c09}

**What mode crystallography demonstrably provides**

**Verdict:** Supported within stated scope.

**Website claim:** Mode analysis exposes hidden structural correlations, separates important and marginal degrees of freedom, and can reduce effective positional parameters.

**Website locations:** [ecosystem/data/sources.yml:25](../index.html); [ecosystem/site/discourse/index.qmd:39](../../discourse/index.html)

**Evidence and assessment:** These uses are stated in Perez-Mato et al.’s abstract and illustrated in the paper. The citation fits this sentence well.

- Printed p. 558, abstract and introduction (full-text passage). [perezmato2010 — source](https://journals.iucr.org/paper?S0108767310016247) · [DOI 10.1107/S0108767310016247](https://doi.org/10.1107/S0108767310016247) · PDF page 1 (reviewed local copy)

**Proposed wording or action:** Retain with a locator to p. 558 and the relevant worked structural example; distinguish this supported description from the later statistical-identifiability extrapolations.

### C10 {#c10}

**AMPLIMODES decomposition and refinement output**

**Verdict:** Supported within stated scope.

**Website claim:** AMPLIMODES decomposes a distortion relative to a parent and supplies mode amplitudes usable in refinement.

**Website locations:** [ecosystem/data/sources.yml:34](../index.html); [ecosystem/site/cases/rietveld/index.qmd:26](../../cases/rietveld/index.html)

**Evidence and assessment:** The paper describes the parent/distorted-structure input and symmetry-mode decomposition. Its final section explicitly describes FullProf-compatible output using basis-mode amplitudes as alternative positional parameters.

- Printed pp. 820 and 832 (full-text passage). [orobengoa2009 — source](https://journals.iucr.org/paper?S0021889809028064) · [DOI 10.1107/S0021889809028064](https://doi.org/10.1107/S0021889809028064) · PDF page 1 (reviewed local copy) · PDF page 13 (reviewed local copy)

**Proposed wording or action:** Retain; cite pp. 820 and 832, especially the paragraph on AMPLIMODES–FullProf output.

### C11 {#c11}

**ISODISPLACE and orthonormal basis conventions**

**Verdict:** Needs qualification or a better citation.

**Website claim:** The mode decomposition is presented generically as an orthonormal change of basis, with the same number of independent coordinates.

**Website locations:** [ecosystem/data/sources.yml:43](../index.html); [ecosystem/site/discourse/index.qmd:40](../../discourse/index.html)

**Evidence and assessment:** Campbell et al. support an invertible change of basis within the chosen distortion space and equal independent degrees of freedom. They also note that their CLIROP modes need not be mutually orthogonal in non-rectangular cells. AMPLIMODES adopts an orthonormal convention. Neither statement means that selecting a subgroup or freezing modes preserves the original unrestricted space.

- Printed pp. 610 and 613; CLIROP caveat and basis transformation (full-text passage). [campbell2006 — source](https://journals.iucr.org/paper?S0021889806014075) · [DOI 10.1107/S0021889806014075](https://doi.org/10.1107/S0021889806014075) · PDF page 5 (reviewed local copy) · PDF page 8 (reviewed local copy)
- Printed pp. 823–824, basis normalization (full-text passage). [orobengoa2009 — source](https://journals.iucr.org/paper?S0021889809028064) · [DOI 10.1107/S0021889809028064](https://doi.org/10.1107/S0021889809028064) · PDF page 4 (reviewed local copy) · PDF page 5 (reviewed local copy)

**Proposed wording or action:** For a fixed parent, cell, subgroup and complete set of allowed modes, the mode amplitudes are alternative coordinates for the same allowed displacements. Specify normalization and orthogonalization; imposing additional symmetry or fixing modes restricts the model.

### C12 {#c12}

**Primary-mode hierarchy and sparse priors**

**Verdict:** Needs qualification or a better citation.

**Website claim:** One or two primary modes dominate; such prior knowledge cannot be written in atomic coordinates.

**Website locations:** [ecosystem/site/discourse/index.qmd:42](../../discourse/index.html); [ecosystem/site/cases/rietveld/index.qmd:27](../../cases/rietveld/index.html)

**Evidence and assessment:** Perez-Mato et al. §4 explains energetic hierarchies, induced secondary modes and coupling-dependent amplitudes. This supports using a hierarchical prior in suitable displacive systems. It is not a universal one-or-two-mode theorem. An invertible basis change permits the same prior to be expressed in atomic coordinates, though less simply.

- Printed pp. 564–565, §4, especially Eq. (9) (full-text passage). [perezmato2010 — source](https://journals.iucr.org/paper?S0108767310016247) · [DOI 10.1107/S0108767310016247](https://doi.org/10.1107/S0108767310016247) · PDF page 7 (reviewed local copy) · PDF page 8 (reviewed local copy)

**Proposed wording or action:** For many pseudosymmetric displacive structures, a small subset of distortions dominates. Mode coordinates can make a physically motivated hierarchical prior easier to express and apply; the equivalent prior can also be transformed into atomic coordinates.

### C13 {#c13}

**Symmetry modes do not necessarily diagonalize the data sensitivity**

**Verdict:** Incorrect as written.

**Website claim:** Switching to symmetry modes turns ambiguous correlated coordinates into well-determined single amplitudes and aligns the Jacobian near-null space.

**Website locations:** [ecosystem/site/discourse/index.qmd:43](../../discourse/index.html); [ecosystem/site/cases/rietveld/index.qmd:27](../../cases/rietveld/index.html)

**Evidence and assessment:** The papers support useful physical organization and sometimes reduced correlations. They do not establish that symmetry modes are the singular vectors of a particular instrument-weighted diffraction Jacobian. Perez-Mato’s discussion of privileged eigenmodes concerns the energy Hessian, not the measurement Fisher matrix.

- Printed pp. 564–565, energy eigenmodes (full-text passage). [perezmato2010 — source](https://journals.iucr.org/paper?S0108767310016247) · [DOI 10.1107/S0108767310016247](https://doi.org/10.1107/S0108767310016247) · PDF page 7 (reviewed local copy) · PDF page 8 (reviewed local copy)
- Printed 010901-4, parameterization dependence (full-text passage). [transtrum2015 — source](https://pubs.aip.org/jcp/article/143/1/010901/566995/Perspective-Sloppiness-and-emergent-theories-in) · [DOI 10.1063/1.4923066](https://doi.org/10.1063/1.4923066) · PDF page 5 (reviewed local copy)

**Independent reasoning:** If u=B a with B invertible, J_a=J_u B and rank(J_a)=rank(J_u). If B is orthogonal, J_a and J_u have the same singular values. Symmetry alone does not force B to diagonalize J_uᵀJ_u.

**Proposed wording or action:** Test how well the symmetry basis aligns with sensitive and insensitive directions for the chosen experiment. A complete invertible reparameterization preserves exact identifiability; improvement in inference requires additional constraints, priors, data, or a numerical benefit.

### C14 {#c14}

**Amplitude magnitude is not uncertainty**

**Verdict:** Incorrect as written.

**Website claim:** Large amplitudes are determined and small amplitudes are undetermined.

**Website locations:** [ecosystem/site/discourse/index.qmd:44](../../discourse/index.html); [ecosystem/site/cases/rietveld/index.qmd:27](../../cases/rietveld/index.html)

**Evidence and assessment:** The mode papers rank the contribution of distortions to structure and stability. They do not equate amplitude size with statistical precision. That requires uncertainty or sensitivity analysis for the actual data.

- §4 amplitude hierarchy (full-text passage). [perezmato2010 — source](https://journals.iucr.org/paper?S0108767310016247) · [DOI 10.1107/S0108767310016247](https://doi.org/10.1107/S0108767310016247) · PDF page 7 (reviewed local copy) · PDF page 8 (reviewed local copy)
- Printed p. 1873, Fig. 1 and sensitivity directions (full-text passage). [gutenkunst2007 — source](https://dx.plos.org/10.1371/journal.pcbi.0030189) · [DOI 10.1371/journal.pcbi.0030189](https://doi.org/10.1371/journal.pcbi.0030189) · PDF page 3 (reviewed local copy)

**Independent reasoning:** In d=A+ε with known noise variance σ², the local information about A is 1/σ², independent of whether A is zero, small, or large.

**Proposed wording or action:** Report mode amplitudes together with their uncertainties and correlations. Rank structural contribution and statistical identifiability separately.

### C15 {#c15}

**Sloppy sensitivity spectra**

**Verdict:** Supported within stated scope.

**Website claim:** Sloppy models can have sensitivity eigenvalues spanning many orders of magnitude, with stiff and sloppy parameter combinations.

**Website locations:** [ecosystem/data/sources.yml:124](../index.html); [ecosystem/site/discourse/index.qmd:22](../../discourse/index.html)

**Evidence and assessment:** Gutenkunst et al. study 17 systems-biology models and show this pattern in Fig. 1. Transtrum et al. develop the geometric interpretation. These are appropriate references; they do not prove that every inverse problem or every small parameter is sloppy.

- Printed pp. 1872–1873; Results and Fig. 1 (full-text passage). [gutenkunst2007 — source](https://dx.plos.org/10.1371/journal.pcbi.0030189) · [DOI 10.1371/journal.pcbi.0030189](https://doi.org/10.1371/journal.pcbi.0030189) · PDF page 2 (reviewed local copy) · PDF page 3 (reviewed local copy)
- Printed 010901-4, §III (full-text passage). [transtrum2015 — source](https://pubs.aip.org/jcp/article/143/1/010901/566995/Perspective-Sloppiness-and-emergent-theories-in) · [DOI 10.1063/1.4923066](https://doi.org/10.1063/1.4923066) · PDF page 5 (reviewed local copy)

**Proposed wording or action:** Retain, with the model-family scope and a citation to Gutenkunst Fig. 1; use dimensionless parameter scales when comparing directions.

### C16 {#c16}

**A small singular value needs a parameter scale**

**Verdict:** Incorrect as written.

**Website claim:** An unscaled singular value much smaller than one is a practical non-identifiability.

**Website locations:** [ecosystem/site/discourse/index.qmd:35](../../discourse/index.html); [ecosystem/site/programme/index.qmd:17](../../programme/index.html)

**Evidence and assessment:** Transtrum et al. explicitly warn that Fisher eigenvalues change under parameter units and reparameterization. Noise whitening alone does not make differently dimensioned parameter directions comparable.

- Printed 010901-4, §III, unit-change example (full-text passage). [transtrum2015 — source](https://pubs.aip.org/jcp/article/143/1/010901/566995/Perspective-Sloppiness-and-emergent-theories-in) · [DOI 10.1063/1.4923066](https://doi.org/10.1063/1.4923066) · PDF page 5 (reviewed local copy)

**Proposed wording or action:** Choose meaningful dimensionless parameter scales or a prior metric, then interpret J S and its sensitivity relative to a stated parameter range and noise model. Assess nonlinear/global behaviour separately.

### C17 {#c17}

**Local Jacobian rank is not a complete structural-identifiability test**

**Verdict:** Incorrect as written.

**Website claim:** Zero Jacobian singular values diagnose structural non-identifiability, and structural non-identifiability is always a positive-dimensional fibre.

**Website locations:** [ecosystem/site/discourse/index.qmd:35](../../discourse/index.html); [ecosystem/site/discourse/index.qmd:87](../../discourse/index.html)

**Evidence and assessment:** The website conflates local first-order rank deficiency, continuous non-identifiability, and global discrete ambiguities. Raue’s abstract supports the general distinction but not these equivalences. Exact elementary counterexamples settle the issue.

- Abstract supports only the broader terminology (abstract only). [raue2009 — source](https://pubmed.ncbi.nlm.nih.gov/19505944/) · [DOI 10.1093/bioinformatics/btp358](https://doi.org/10.1093/bioinformatics/btp358)
- Abstract gives multiple non-congruent homometric configurations (abstract only). [patterson1944 — source](https://journals.aps.org/pr/abstract/10.1103/PhysRev.65.195) · [DOI 10.1103/PhysRev.65.195](https://doi.org/10.1103/PhysRev.65.195)

**Independent reasoning:** F(x)=x³ is injective even though F′(0)=0. F(x)=x² has two preimages for positive data but nonzero derivative at each preimage. Thus neither stated equivalence holds without qualifications.

**Proposed wording or action:** Distinguish global from local identifiability, continuous from discrete ambiguities, and first-order rank deficiency from a structural proof. Use the Jacobian as a local diagnostic with regularity assumptions.

### C18 {#c18}

**A likelihood region is not a posterior**

**Verdict:** Incorrect as written.

**Website claim:** The chi-square tube is a posterior distribution.

**Website locations:** [ecosystem/site/discourse/index.qmd:77](../../discourse/index.html); [ecosystem/site/discourse/index.qmd:32](../../discourse/index.html)

**Evidence and assessment:** Tarantola Eq. (1.100) includes a prior multiplying a likelihood. The website’s tube is a thresholded residual set, with no probability density or prior weighting. It is not itself a posterior or automatically a credible region.

- Printed p. 35, Eqs. (1.94) and (1.100) (full-text passage). [tarantola2005 — source](https://epubs.siam.org/doi/book/10.1137/1.9780898717921) · [DOI 10.1137/1.9780898717921](https://doi.org/10.1137/1.9780898717921) · PDF page 49 (reviewed local copy)
- Printed pp. 152–153, Eqs. (19)–(23) (full-text passage). [daun2019 — source](https://linkinghub.elsevier.com/retrieve/pii/S0022407318309178) · [DOI 10.1016/j.jqsrt.2019.01.021](https://doi.org/10.1016/j.jqsrt.2019.01.021) · PDF page 7 (reviewed local copy) · PDF page 8 (reviewed local copy)

**Proposed wording or action:** The tube is a data-misfit acceptance region. A Bayesian posterior weights configurations using both likelihood and prior; a credible region is constructed from that normalized posterior.

### C19 {#c19}

**The model-manifold description**

**Verdict:** Supported within stated scope.

**Website claim:** The image of the forward model in data space can be studied geometrically as a model manifold, often with a hierarchy of widths.

**Website locations:** [ecosystem/data/sources.yml:133](../index.html); [ecosystem/site/discourse/index.qmd:33](../../discourse/index.html)

**Evidence and assessment:** Transtrum et al. provide this formulation and discuss hyperribbons and manifold-boundary approximation. The model image can also have singularities or self-intersections, so “manifold” is a useful regular-model description rather than a universal smoothness guarantee.

- Printed 010901-2, -4 and -5; §§II–IV (full-text passage). [transtrum2015 — source](https://pubs.aip.org/jcp/article/143/1/010901/566995/Perspective-Sloppiness-and-emergent-theories-in) · [DOI 10.1063/1.4923066](https://doi.org/10.1063/1.4923066) · PDF page 3 (reviewed local copy) · PDF page 5 (reviewed local copy) · PDF page 6 (reviewed local copy)

**Proposed wording or action:** Retain with a reference to §§II–IV; qualify the thin-ribbon picture as a common geometry of the studied sloppy models.

### C20 {#c20}

**Cranmer supports approximate amortized inference, not guaranteed recovery**

**Verdict:** Needs qualification or a better citation.

**Website claim:** A network returns the full posterior for any new measurement, including all disconnected branches, at guaranteed campaign-scale speed.

**Website locations:** [ecosystem/data/sources.yml:144](../index.html); [ecosystem/site/discourse/index.qmd:68](../../discourse/index.html); [ecosystem/site/programme/index.qmd:38](../../programme/index.html)

**Evidence and assessment:** Cranmer et al. describe amortized likelihood, likelihood-ratio and posterior surrogates. They also discuss finite-sample, capacity and optimization errors and calibration. The review does not guarantee complete branch recovery, arbitrary out-of-distribution accuracy, or the specific timing claim.

- Local arXiv version pp. 7–8, §3B–D (full-text passage). [cranmer2020 — source](https://pnas.org/doi/full/10.1073/pnas.1912789117) · [DOI 10.1073/pnas.1912789117](https://doi.org/10.1073/pnas.1912789117) · PDF page 7 (reviewed local copy) · PDF page 8 (reviewed local copy)

**Proposed wording or action:** Simulation-based inference can learn an approximate posterior or likelihood surrogate over a specified simulation domain. Validate calibration, branch coverage, robustness to model mismatch, and computational cost on the intended experiment.

### C21 {#c21}

**Park dataset and accuracy figures**

**Verdict:** Supported within stated scope.

**Website claim:** Park uses about 150,000 simulated patterns and reports approximately 95%, 84% and 81% accuracy for crystal system, extinction group and space group.

**Website locations:** [ecosystem/data/sources.yml:153](../index.html); [ecosystem/site/cases/rietveld/index.qmd:31](../../cases/rietveld/index.html); [ecosystem/site/discourse/index.qmd:61](../../discourse/index.html)

**Evidence and assessment:** The dataset size and ordering of percentages are correct. The exact values are 94.99%, 83.83% and 81.14%, evaluated on a randomly selected 20% test split of the simulated dataset. These are benchmark results, not information-theoretic limits of powder diffraction.

- Printed pp. 486, 488 and 490; abstract, §2 and test evaluation (full-text passage). [park2017 — source](https://journals.iucr.org/paper?S205225251700714X) · [DOI 10.1107/S205225251700714X](https://doi.org/10.1107/S205225251700714X) · PDF page 1 (reviewed local copy) · PDF page 3 (reviewed local copy) · PDF page 5 (reviewed local copy)

**Proposed wording or action:** Retain the numbers; say “test accuracies on their simulated-data benchmark” and avoid interpreting the percentages as universal experimental identifiability.

### C22 {#c22}

**Lee dataset size and chemical scope**

**Verdict:** Supported within stated scope.

**Website claim:** Lee uses about 1.8 million synthetic mixture patterns from 170 compounds.

**Website locations:** [ecosystem/data/sources.yml:162](../index.html); [ecosystem/site/discourse/index.qmd:61](../../discourse/index.html); [ecosystem/site/cases/rietveld/index.qmd:31](../../cases/rietveld/index.html)

**Evidence and assessment:** The article gives 1,785,405 patterns and 170 compounds. The chemical scope is the Sr–Li–Al–O quaternary pool. The paper supports the dataset claim, but not an unrestricted capability across all inorganic materials.

- Article pp. 1–2, abstract and Results (full-text passage). [lee2020 — source](https://www.nature.com/articles/s41467-019-13749-3) · [DOI 10.1038/s41467-019-13749-3](https://doi.org/10.1038/s41467-019-13749-3) · PDF page 1 (reviewed local copy) · PDF page 2 (reviewed local copy)

**Proposed wording or action:** Use the exact number when useful and specify the Sr–Li–Al–O reference set.

### C23 {#c23}

**Szymanski probabilities are phase-classification confidence**

**Verdict:** Needs qualification or a better citation.

**Website claim:** Szymanski returns distributions instead of labels, providing the required form of output for an underdetermined inverse problem.

**Website locations:** [ecosystem/data/sources.yml:171](../index.html); [ecosystem/site/discourse/index.qmd:61](../../discourse/index.html)

**Evidence and assessment:** The paper uses 1,000 stochastic dropout predictions and defines a phase’s probability as its fraction of predicted labels. It ranks phases and uses a branching procedure to select a mixture. These are phase-classification confidence scores, not a posterior over continuous atomic or mode parameters, and the final result still identifies phases.

- Publisher-typeset early-access PDF pp. 3–4 (C–D), CNN and branching sections (full-text passage). [szymanski2021 — source](https://pubs.acs.org/doi/10.1021/acs.chemmater.1c01071) · [DOI 10.1021/acs.chemmater.1c01071](https://doi.org/10.1021/acs.chemmater.1c01071) · PDF page 3 (reviewed local copy) · PDF page 4 (reviewed local copy)

**Proposed wording or action:** Szymanski combines physics-based augmentation with dropout-based phase confidence and a branching mixture-identification algorithm. Cite it as a related classification workflow, not as evidence of posterior inference over the refinement configuration space.

### C24 {#c24}

**The three ML papers are precedents, not the proposed mode-refinement pipeline**

**Verdict:** Needs qualification or a better citation.

**Website claim:** The three papers establish the proposed scripted-expertise pipeline and show that the wider field does not yet perform mode-space corpus refinement.

**Website locations:** [ecosystem/site/cases/rietveld/index.qmd:31](../../cases/rietveld/index.html); [ecosystem/site/discourse/index.qmd:61](../../discourse/index.html)

**Evidence and assessment:** They demonstrate synthetic-data classification and phase identification, not posterior mapping of symmetry-mode refinements. Their contents support a narrow comparison with the proposed work. Reviewing these three papers cannot establish priority, absence of competing work, or a ranking of the field’s best results.

- §§2–4 (full-text passage). [park2017 — source](https://journals.iucr.org/paper?S205225251700714X) · [DOI 10.1107/S205225251700714X](https://doi.org/10.1107/S205225251700714X) · PDF page 3 (reviewed local copy) · PDF page 5 (reviewed local copy)
- Abstract and Results (full-text passage). [lee2020 — source](https://www.nature.com/articles/s41467-019-13749-3) · [DOI 10.1038/s41467-019-13749-3](https://doi.org/10.1038/s41467-019-13749-3) · PDF page 1 (reviewed local copy) · PDF page 2 (reviewed local copy)
- CNN and branching workflow (full-text passage). [szymanski2021 — source](https://pubs.acs.org/doi/10.1021/acs.chemmater.1c01071) · [DOI 10.1021/acs.chemmater.1c01071](https://doi.org/10.1021/acs.chemmater.1c01071) · PDF page 3 (reviewed local copy) · PDF page 4 (reviewed local copy)

**Proposed wording or action:** These three examples show how physical modelling enters synthetic training data. The proposed mode-refinement corpus has a different target; its novelty requires a separate literature search.

### C25 {#c25}

**Kuzmenko’s background model and dense variational mesh**

**Verdict:** Needs qualification or a better citation.

**Website claim:** Kuzmenko’s variational dielectric function is anchored by a few oscillators.

**Website locations:** [ecosystem/data/sources.yml:182](../index.html); [ecosystem/site/cases/dielectric/index.qmd:25](../../cases/dielectric/index.html)

**Evidence and assessment:** The central method independently adjusts the imaginary dielectric function on a dense anchor-frequency mesh and couples the real part by KK. The number of variational degrees of freedom can be comparable to the number of data points. A limited-parameter background model supplies extrapolation behaviour in a separate first fitting step. The phrase could refer to that background model, but it is ambiguous without this distinction; it should not stand alone as a description of the variational representation.

- Printed 083108-1, -3 and -4; abstract and §IV, Eqs. (14) and (17) (full-text passage). [kuzmenko2005 — source](https://pubs.aip.org/rsi/article/76/8/083108/822925/Kramers-Kronig-constrained-variational-analysis-of) · [DOI 10.1063/1.1979470](https://doi.org/10.1063/1.1979470) · PDF page 3 (reviewed local copy) · PDF page 5 (reviewed local copy) · PDF page 6 (reviewed local copy)

**Proposed wording or action:** Kuzmenko represents the dielectric function on a dense frequency mesh constrained by KK, with a background model for out-of-range spectral weight. Do not conflate this mesh with a small set of physical oscillators.

### C26 {#c26}

**Phase recovery needs analytic and geometry conditions**

**Verdict:** Needs qualification or a better citation.

**Website claim:** Causality alone fixes reflection phase from its modulus over the whole frequency axis.

**Website locations:** [ecosystem/site/cases/dielectric/index.qmd:25](../../cases/dielectric/index.html); [ecosystem/site/discourse/index.qmd:52](../../discourse/index.html)

**Evidence and assessment:** Kuzmenko explicitly states the extra condition that r has no zeros in the upper complex-frequency half-plane for the logarithmic reflectivity relation. He notes failures for sufficiently oblique incidence and thin films. The standard relation couples phase to log modulus, not directly to modulus.

- Printed 083108-1, Eqs. (3)–(4) and adjacent caveat (full-text passage). [kuzmenko2005 — source](https://pubs.aip.org/rsi/article/76/8/083108/822925/Kramers-Kronig-constrained-variational-analysis-of) · [DOI 10.1063/1.1979470](https://doi.org/10.1063/1.1979470) · PDF page 3 (reviewed local copy)

**Proposed wording or action:** For geometries satisfying the analytic conditions for log r, such as the standard semi-infinite normal-incidence case, KK relates reflection phase to log modulus, with extrapolation assumptions outside the measured range.

### C27 {#c27}

**Unmeasured spectral weight is not generically invisible**

**Verdict:** Incorrect as written.

**Website claim:** Everything outside the measured frequency range lies in the null space.

**Website locations:** [ecosystem/site/cases/dielectric/index.qmd:19](../../cases/dielectric/index.html)

**Evidence and assessment:** Kuzmenko §IV.D explicitly explains that high- and low-frequency spectral weight contributes to the real dielectric function inside the measured band. Extrapolation uncertainty is real, but it is not an arbitrary exact null space of all out-of-band changes.

- Printed 083108-4, §IV.D (full-text passage). [kuzmenko2005 — source](https://pubs.aip.org/rsi/article/76/8/083108/822925/Kramers-Kronig-constrained-variational-analysis-of) · [DOI 10.1063/1.1979470](https://doi.org/10.1063/1.1979470) · PDF page 6 (reviewed local copy)

**Proposed wording or action:** Out-of-band spectral weight can affect in-band optical response through KK coupling. Finite-band data may constrain it weakly and ambiguously, so extrapolation assumptions and additional measurements remain important.

### C28 {#c28}

**Oscillator non-identifiability is not universal**

**Verdict:** Incorrect as written.

**Website claim:** A finite oscillator decomposition is necessarily non-unique even if the dielectric function is known.

**Website locations:** [ecosystem/site/cases/dielectric/index.qmd:19](../../cases/dielectric/index.html); [ecosystem/site/discourse/index.qmd:52](../../discourse/index.html)

**Evidence and assessment:** Kuzmenko’s flexible variational representation is not a theorem that every fixed finite Lorentz model is structurally non-identifiable. Overlap, finite bandwidth, unknown model order and noise can make fits weakly determined. Exact degeneracies require separate conditions.

- Printed 083108-3–4, variational representation (full-text passage). [kuzmenko2005 — source](https://pubs.aip.org/rsi/article/76/8/083108/822925/Kramers-Kronig-constrained-variational-analysis-of) · [DOI 10.1063/1.1979470](https://doi.org/10.1063/1.1979470) · PDF page 5 (reviewed local copy) · PDF page 6 (reviewed local copy)

**Independent reasoning:** A rational response with fixed distinct simple poles has a unique partial-fraction representation up to ordering. Coincident poles can instead make individual strengths degenerate. These are different cases.

**Proposed wording or action:** Different oscillator models may fit finite-band noisy data comparably well. Assess identifiability for the specified model order and parameterization; do not assert universal exact non-uniqueness.

### C29 {#c29}

**difes software claims and optical assumptions**

**Verdict:** Supported within stated scope.

**Website claim:** difes implements additive/multiplicative dielectric terms, Fresnel optics, finite-range KK corrections and textual recipes.

**Website locations:** [ecosystem/data/sources.yml:190](../index.html); [ecosystem/site/cases/dielectric/index.qmd:15](../../cases/dielectric/index.html); [ecosystem/site/cases/dielectric/index.qmd:28](../../cases/dielectric/index.html)

**Evidence and assessment:** Read-only inspection at commit 55e78ff908519322dbf37af22efb0fc8a0223a15 confirms the documented model convention, normal-incidence bulk and slab routines, KK correction routines, and recipe syntax. This confirms implementation/documentation, not numerical accuracy or physical adequacy for every sample.

- README conventions/recipes; optics.py:48–74; kk.py:1–21; recipe example (versioned software source). [difes2026 — source](https://github.com/jmigartua/difes)

**Proposed wording or action:** Retain the software citation with a commit and relevant modules. State the normal-incidence, sample-geometry and opacity assumptions next to the simple Fresnel/emissivity equations.

### C30 {#c30}

**A missing primary source for finite-range correction**

**Verdict:** Needs qualification or a better citation.

**Website claim:** Kuzmenko 2005 is the nearby citation for difes finite-range corrections.

**Website locations:** [ecosystem/site/cases/dielectric/index.qmd:25](../../cases/dielectric/index.html)

**Evidence and assessment:** The inspected difes kk.py explicitly attributes its correction method to De Sousa Meneses et al. 2007. The primary paper Retrieval of linear optical functions from finite range spectra has DOI 10.1366/000370207783292163, independently identified in PubMed. Kuzmenko’s variational approach and this CFRC method should be distinguished.

- kk.py module documentation (versioned software source). [difes2026 — source](https://github.com/jmigartua/difes)

**Proposed wording or action:** Cite De Sousa Meneses, Rousseau, Echegut and Simon (2007), Applied Spectroscopy 61, 1390–1397, DOI 10.1366/000370207783292163, for CFRC; retain Kuzmenko for KK-constrained variational fitting. Full method details in the new paper still require full-text review.

### C31 {#c31}

**The thesis cannot yet support a detailed technical claim**

**Verdict:** Not fully verified.

**Website claim:** The thesis supports the high-temperature emissivity and dielectric-modelling context.

**Website locations:** [ecosystem/data/sources.yml:199](../index.html)

**Evidence and assessment:** Its bibliographic identity and topic were previously established, but no thesis full text is in the collection. This audit cannot assign chapter/page evidence or validate a particular result from it.

- No local full text (bibliographic context only). [gonzalezdearrieta2020 — source](https://hdl.handle.net/10810/50263)

**Proposed wording or action:** Use it as bibliographic context only until the relevant thesis chapters are available. Do not mark its substantive results verified.

### C32 {#c32}

**Daun experimental conditions and tabulated parameters**

**Verdict:** Supported within stated scope.

**Website claim:** The particle size, adopted temperature, spectral ranges and listed Drude estimates summarize Daun’s experiment.

**Website locations:** [ecosystem/site/cases/drude/index.qmd:15](../../cases/drude/index.html); [ecosystem/site/cases/drude/index.qmd:22](../../cases/drude/index.html)

**Evidence and assessment:** The article supports 38.3 nm mean diameter, 5.7 nm standard deviation, an adopted 1550 ± 35 K from earlier silicon work, and the two wavelength ranges. The table reproduces the five parameter pairs correctly. Table 3 concerns fits/comparisons for the LDLS spectrum.

- Printed pp. 147, 152–153; §2, Fig. 7, Table 3 (full-text passage). [daun2019 — source](https://linkinghub.elsevier.com/retrieve/pii/S0022407318309178) · [DOI 10.1016/j.jqsrt.2019.01.021](https://doi.org/10.1016/j.jqsrt.2019.01.021) · PDF page 2 (reviewed local copy) · PDF page 7 (reviewed local copy) · PDF page 8 (reviewed local copy)

**Proposed wording or action:** Retain the values; label Table 3 as the LDLS comparison and keep the temperature’s adopted, rather than directly measured, status explicit.

### C33 {#c33}

**Daun surface scattering explanation is reversed**

**Verdict:** Incorrect as written.

**Website claim:** Daun offers surface-electron scattering at about 40 nm as an explanation of the discrepancy.

**Website locations:** [ecosystem/site/cases/drude/index.qmd:35](../../cases/drude/index.html)

**Evidence and assessment:** On p. 154 the authors estimate an electron mean free path of 0.54 nm, far below the roughly 40 nm particle size, and discount this explanation for their case. They favour inadequacy of the simplistic free-electron model and discuss a reduced effective conduction-electron density.

- Printed p. 154, §5, right column (full-text passage). [daun2019 — source](https://linkinghub.elsevier.com/retrieve/pii/S0022407318309178) · [DOI 10.1016/j.jqsrt.2019.01.021](https://doi.org/10.1016/j.jqsrt.2019.01.021) · PDF page 9 (reviewed local copy)

**Proposed wording or action:** Daun et al. consider surface scattering but judge it too small to explain their discrepancy; they instead discuss limitations of the free-electron description, including fewer effective conduction electrons.

### C34 {#c34}

**The LDLS sees the shoulder, not the 190 nm peak**

**Verdict:** Incorrect as written.

**Website claim:** The 205–585 nm measurement reaches the resonance peak near 190 nm.

**Website locations:** [ecosystem/site/cases/drude/index.qmd:30](../../cases/drude/index.html)

**Evidence and assessment:** The stated lower wavelength is 205 nm. The paper says the LDLS captures more spectral variation associated with a resonance whose peak is near 190 nm; the peak itself is outside the quoted measurement interval. Improved signal-to-noise also contributes to the narrower posterior.

- Printed pp. 151–152 and 154; discussion of Fig. 7 and Fig. 9 (full-text passage). [daun2019 — source](https://linkinghub.elsevier.com/retrieve/pii/S0022407318309178) · [DOI 10.1016/j.jqsrt.2019.01.021](https://doi.org/10.1016/j.jqsrt.2019.01.021) · PDF page 6 (reviewed local copy) · PDF page 7 (reviewed local copy) · PDF page 9 (reviewed local copy)

**Proposed wording or action:** The LDLS captures more of the resonance shoulder and has higher signal-to-noise; the peak near 190 nm is outside its stated 205–585 nm range.

### C35 {#c35}

**Daun approximation-error sampling is not the stated prior range**

**Verdict:** Incorrect as written.

**Website claim:** The approximation-error samples span the same prior range as the inference.

**Website locations:** [ecosystem/site/cases/drude/index.qmd:19](../../cases/drude/index.html)

**Evidence and assessment:** The printed p. 152 sampling intervals differ from the p. 153 prior intervals, including the powers of ten. The published text may contain a typographical problem, but the website silently equates them. The error term is fitted from 1,000 samples; the posterior uses 10⁶ MCMC samples. Specifically, p. 152 prints ωp in [1.5×10¹⁵, 3×10¹⁵] s⁻¹ and τ in [1.5×10⁻¹⁵, 3×10⁻¹⁵] s, whereas Eq. (22) prints [1.5×10¹⁶, 4.5×10¹⁶] rad/s and [1.5×10⁻¹⁶, 4.5×10⁻¹⁶] s. These are transcribed discrepancies, not corrected inputs for a replication.

- Printed pp. 152–153, text after Eq. (18) and Eq. (22) (full-text passage). [daun2019 — source](https://linkinghub.elsevier.com/retrieve/pii/S0022407318309178) · [DOI 10.1016/j.jqsrt.2019.01.021](https://doi.org/10.1016/j.jqsrt.2019.01.021) · PDF page 7 (reviewed local copy) · PDF page 8 (reviewed local copy)

**Proposed wording or action:** Describe the sampling construction without claiming the two ranges match. Before reproducing the calculation, resolve the paper’s inconsistent printed intervals using supplementary material or author clarification.

### C36 {#c36}

**Low-frequency Drude degeneracy is a limiting approximation**

**Verdict:** Needs qualification or a better citation.

**Website claim:** At low frequency only ωp²τ enters the measured spectrum, creating exact non-identifiability of the full model.

**Website locations:** [ecosystem/site/discourse/index.qmd:20](../../discourse/index.html); [ecosystem/site/cases/drude/index.qmd:36](../../cases/drude/index.html)

**Evidence and assessment:** Daun Eq. (4) retains separate parameter dependence at finite frequency. The product controls DC conductivity and the leading dissipative low-frequency term. Treating a finite-band full Drude/Mie measurement as exactly product-only requires an explicit reduced forward model and limit.

- Printed p. 149, Eqs. (4)–(5) (full-text passage). [daun2019 — source](https://linkinghub.elsevier.com/retrieve/pii/S0022407318309178) · [DOI 10.1016/j.jqsrt.2019.01.021](https://doi.org/10.1016/j.jqsrt.2019.01.021) · PDF page 4 (reviewed local copy)

**Independent reasoning:** For ωτ ≪ 1, εI=1−ωp²τ²+O(ω²) while εII=ωp²τ/ω+O(ω). The subleading information can be small, but the full expression is not solely a function of the product.

**Proposed wording or action:** In a reduced DC/leading-order model the data may depend only on ωp²τ. In the full finite-frequency optical model, assess whether the separate sensitivities are merely too weak to resolve.

### C37 {#c37}

**A surrogate does not automatically remove model error**

**Verdict:** Proposal presented too strongly.

**Website claim:** A learned Mie surrogate eliminates the approximation-error term and makes MCMC run on exact theory.

**Website locations:** [ecosystem/site/discourse/index.qmd:70](../../discourse/index.html); [ecosystem/site/cases/drude/index.qmd:40](../../cases/drude/index.html); [ecosystem/site/programme/index.qmd:52](../../programme/index.html)

**Evidence and assessment:** Daun supplies the motivation for a cheaper forward calculation, not a trained or validated surrogate. A learned emulator has its own approximation error. Even exact Mie calculations do not repair an inadequate dielectric model.

- Printed pp. 151–152 and 154 (full-text passage). [daun2019 — source](https://linkinghub.elsevier.com/retrieve/pii/S0022407318309178) · [DOI 10.1016/j.jqsrt.2019.01.021](https://doi.org/10.1016/j.jqsrt.2019.01.021) · PDF page 6 (reviewed local copy) · PDF page 7 (reviewed local copy) · PDF page 9 (reviewed local copy)
- Surrogate inference and calibration discussion (full-text passage). [cranmer2020 — source](https://pnas.org/doi/full/10.1073/pnas.1912789117) · [DOI 10.1073/pnas.1912789117](https://doi.org/10.1073/pnas.1912789117) · PDF page 7 (reviewed local copy) · PDF page 8 (reviewed local copy)

**Proposed wording or action:** Test a surrogate against exact Mie over the inference domain. Propagate or bound its error relative to measurement noise; separately assess Drude model discrepancy. Treat runtime and posterior agreement as measured outcomes.

### C38 {#c38}

**Expected information gain is not determined by a Jacobian alone**

**Verdict:** Proposal presented too strongly.

**Website claim:** The Jacobian alone computes expected information gain and would have selected the UV source in advance.

**Website locations:** [ecosystem/site/discourse/index.qmd:72](../../discourse/index.html); [ecosystem/site/programme/index.qmd:52](../../programme/index.html)

**Evidence and assessment:** The cited Daun paper compares actual sources; it does not perform the proposed design calculation. A Jacobian can enter a local linear-Gaussian approximation, but global Bayesian expected information gain also requires a prior/current posterior, a noise model, a candidate likelihood and averaging over possible data.

- Printed p. 154; source comparison (full-text passage). [daun2019 — source](https://linkinghub.elsevier.com/retrieve/pii/S0022407318309178) · [DOI 10.1016/j.jqsrt.2019.01.021](https://doi.org/10.1016/j.jqsrt.2019.01.021) · PDF page 9 (reviewed local copy)
- Prior and likelihood roles in posterior (full-text passage). [tarantola2005 — source](https://epubs.siam.org/doi/book/10.1137/1.9780898717921) · [DOI 10.1137/1.9780898717921](https://doi.org/10.1137/1.9780898717921) · PDF page 49 (reviewed local copy)

**Proposed wording or action:** Start with a clearly labelled local Fisher-information design approximation, then test it against posterior-based expected information gain and simulated source choices. Do not prestate the ranking as a demonstrated result.

### C39 {#c39}

**The P1 diagnostic cannot identify all three failure types alone**

**Verdict:** Proposal presented too strongly.

**Website claim:** A Jacobian SVD and a two-parameter region show at a glance whether the problem has structural non-identifiability, practical non-identifiability or model inadequacy.

**Website locations:** [ecosystem/site/programme/index.qmd:18](../../programme/index.html)

**Evidence and assessment:** The local Jacobian diagnoses first-order sensitivity under the assumed model. It neither proves global uniqueness nor checks whether the assumed forward model describes reality. No cited source establishes the promised three-way diagnosis.

- Profile-likelihood motivation (abstract only). [raue2009 — source](https://pubmed.ncbi.nlm.nih.gov/19505944/) · [DOI 10.1093/bioinformatics/btp358](https://doi.org/10.1093/bioinformatics/btp358)
- Model discrepancy and confounding (full-text passage). [brynjarsdottir2014 — source](https://iopscience.iop.org/article/10.1088/0266-5611/30/11/114007) · [DOI 10.1088/0266-5611/30/11/114007](https://doi.org/10.1088/0266-5611/30/11/114007) · PDF page 1 (reviewed local copy) · PDF page 3 (reviewed local copy)
- Local sensitivity and parameterization caveats (full-text passage). [transtrum2015 — source](https://pubs.aip.org/jcp/article/143/1/010901/566995/Perspective-Sloppiness-and-emergent-theories-in) · [DOI 10.1063/1.4923066](https://doi.org/10.1063/1.4923066) · PDF page 5 (reviewed local copy)

**Proposed wording or action:** Use scaled SVD as one diagnostic, alongside nonlinear profile/posterior exploration, global ambiguity checks, residual analysis, and model/predictive validation. Present P1 as a proposed suite, not a sufficient classification rule.

### C40 {#c40}

**Data availability and reproducibility claims**

**Verdict:** Not fully verified.

**Website claim:** Daun’s underlying data are not public.

**Website locations:** [ecosystem/site/programme/index.qmd:52](../../programme/index.html)

**Evidence and assessment:** The article lists supplementary material on p. 155. The collection contains the main paper, but this audit has not established what all supplements or repositories contain. Failure to have downloaded data is not evidence that they are unavailable publicly.

- Printed p. 155, Supplementary material note (full-text passage). [daun2019 — source](https://linkinghub.elsevier.com/retrieve/pii/S0022407318309178) · [DOI 10.1016/j.jqsrt.2019.01.021](https://doi.org/10.1016/j.jqsrt.2019.01.021) · PDF page 10 (reviewed local copy)

**Proposed wording or action:** The original measurement data have not yet been obtained for this project. Check the supplementary files and data repositories before claiming that the data are not public.

### C41 {#c41}

**A covariance diagonal is not a conditional tube cross-section**

**Verdict:** Incorrect as written.

**Website claim:** Diagonal covariance uncertainties describe transverse width but exclude the long sloppy directions.

**Website locations:** [ecosystem/site/discourse/index.qmd:22](../../discourse/index.html); [ecosystem/site/discourse/index.qmd:22](../../discourse/index.html)

**Evidence and assessment:** In the local Gaussian approximation, diagonal covariance entries are marginal variances along parameter axes and can already be large because of sloppy directions. Reading only the diagonal loses orientation and dependence, not all contribution from long directions. Nonlinearity can invalidate the approximation.

- Fig. 1 distinguishes projections from intersections (full-text passage). [gutenkunst2007 — source](https://dx.plos.org/10.1371/journal.pcbi.0030189) · [DOI 10.1371/journal.pcbi.0030189](https://doi.org/10.1371/journal.pcbi.0030189) · PDF page 3 (reviewed local copy)

**Independent reasoning:** For H=JᵀJ=V diag(σk²)Vᵀ, Cov_ii=sum_k V_ik²/σk². Small σk explicitly contribute to diagonal marginal variances.

**Proposed wording or action:** Report covariance eigenvectors and correlations as well as marginal standard errors; use nonlinear exploration where the local ellipsoid is inadequate.

### C42 {#c42}

**Transferability and parameter-point dependence**

**Verdict:** Proposal presented too strongly.

**Website claim:** Identifiability learned from synthetic data transfers by construction and is independent of the sample.

**Website locations:** [ecosystem/site/discourse/index.qmd:78](../../discourse/index.html); [ecosystem/site/programme/index.qmd:38](../../programme/index.html)

**Evidence and assessment:** The website itself defines J at a parameter point. Nonlinear sensitivities and identifiable combinations can vary with parameters, nuisance effects, noise and model mismatch. The three cited classification studies show performance in specified tests, not universal transfer.

- Inference reliability and calibration (full-text passage). [cranmer2020 — source](https://pnas.org/doi/full/10.1073/pnas.1912789117) · [DOI 10.1073/pnas.1912789117](https://doi.org/10.1073/pnas.1912789117) · PDF page 8 (reviewed local copy)
- Parameterized model geometry (full-text passage). [transtrum2015 — source](https://pubs.aip.org/jcp/article/143/1/010901/566995/Perspective-Sloppiness-and-emergent-theories-in) · [DOI 10.1063/1.4923066](https://doi.org/10.1063/1.4923066) · PDF page 3 (reviewed local copy) · PDF page 5 (reviewed local copy)

**Proposed wording or action:** Learn identifiability over a stated parameter and instrument domain, then test transfer on held-out regimes and real measurements. Retain parameter-point and model-mismatch dependence.

## Additional primary reference

Domingos De Sousa Meneses; Benoit Rousseau; Patrick Echegut; Patrick Simon (2007). *Retrieval of linear optical functions from finite range spectra*. Applied Spectroscopy 61, 1390–1397. [DOI 10.1366/000370207783292163](https://doi.org/10.1366/000370207783292163); [record](https://pubmed.ncbi.nlm.nih.gov/18198033/).

Primary CFRC reference named by difes kk.py; distinct from Kuzmenko variational fitting. Bibliographic record and abstract-level discovery; full article not obtained.

## What remains unresolved

Obtain the relevant full text of Rietveld, Patterson, Raue, Kennedy–O’Hagan and Kaipio–Somersalo, and the thesis chapters before upgrading their detailed source-content status. The author/publisher abstracts support only the specific statements identified above. The new CFRC paper also needs full-text review.

The numerical algorithms, proposed learning pipeline, novelty claims, experiment-design ranking and runtime estimates have not been replicated or demonstrated by this citation audit. The founding brief remains an attributed research proposal. The recommended edits are recorded for review; the scientific pages have not been rewritten.


## Archive provenance

The original Markdown report, structured claim records, verification record, website hashes and versioned software evidence remain in the private project repository under `sources/library/citation-audit/`. The public edition contains the report and its provenance, with public source links and retained page locators. It does not redistribute the collected PDFs or private software snapshots.

The dated page is a historical review record. Subsequent reviews or accepted corrections should be recorded separately and linked from the log, so that a proposal is not silently turned into an approved finding.
