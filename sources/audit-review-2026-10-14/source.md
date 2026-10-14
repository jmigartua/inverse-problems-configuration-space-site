# The audit reviewed — 14 October 2026

**Review record · L012 · a review of the citation audit, awaiting Josu's and Iñigo's reading.** Prepared by Claude (AI assistant) for this project, at Josu's request, on the audit that Codex (AI assistant) made of the site's claims (L009, L010). The audit was of this development's work and of Josu's; this is the audit of the audit: each of its 42 findings re-judged against the source and against the sentence the site actually prints, the audit's method assessed, and a decision proposed for every finding. Nothing on the scientific pages has been changed by this review; the decisions wait for Josu.

**Suggested citation:** Claude (2026), *The audit reviewed — 14 October 2026*, inverse-problems-configuration-space project, review record L012. No DOI assigned. Permanent URL: [audit review](https://jmigartua.github.io/inverse-problems-configuration-space-site/sources/audit-review-2026-10-14/).

**Method:** Every finding was read with the sentence it cites, as printed on the site at commit `546e5e4` (the audit reviewed `bcdd090`; the text of the discourse and the cases is the same at both). Where the audit's evidence could be re-opened — the Daun paper and the PDFs in the project's library — the locator was re-read today: Daun pp. 152–155; Kuzmenko 083108-1 to -4; Transtrum 010901-4; Perez-Mato pp. 564–565. Where it could not (the four abstract-only sources, the Kaipio book, the thesis), the review says so and does not pretend otherwise. The review's verdicts are about the audit's verdicts, not about the papers.

[Audit log (L009)](../../log/index.html#L009) · [Audit publication (L010)](../../log/index.html#L010) · [This review's log (L012)](../../log/index.html#L012) · [The audit](../citation-audit-2026-10-14/index.html) · [Sources](../index.html)

The short version: the audit is good, and it is accepted almost whole. Its seven priority corrections are all right, and the three about the Daun paper (C33, C34, C35) were confirmed today against the printed pages: one sentence of the Drude case reverses what the authors say about surface scattering, one puts the plasmon peak inside a range that stops 15 nm short of it, and one silently equates two sampling intervals that the paper prints with different powers of ten. The most instructive correction is C41: the discourse said the standard uncertainties printed by a refinement are "the width of the valley, not its length", and that is wrong — the marginal variances contain the valley's projection on each axis; what reading the diagonal loses is the valley's direction, which is the correlation matrix. The audit's independent reasoning is right every time it is used.

Where this review narrows the audit, it is in five findings whose "website claim" is a paraphrase stronger than the sentence on the page (C18, C20, C23, C37, C42): the verdicts survive, the proposed wordings are still worth applying, but the reader of the audit should check the quoted claim against the page before concluding that the site said it. Three findings are only partly agreed (C13, C24, C36), for reasons given on their cards; two cannot be settled with the material in hand (C03, C40). None is rejected.

The audit also has gaps, listed under "The audit as a whole": it did not read the comparison table of the Cases page, which carries the same claims in a third place and one claim that C26 contradicts; it did not check the ISODISTORT half of the statement that mode amplitudes are written out as refinable parameters; and it applied the standard of a theorem to a page that announces itself as a first version to be argued over — rightly, since the project chose its three words to be used strictly, but the audit's "incorrect as written" should be read as "false in the strict vocabulary the site adopted", not as "the practitioner's point is wrong".

## Findings at a glance

| Verdict | Findings |
| --- | ---: |
| Agreed: apply | 32 |
| Agreed, with a narrower reading of the text | 5 |
| Partly agreed | 3 |
| Not agreed | 0 |
| Cannot be settled here | 2 |

"Agreed: apply" means the audit's verdict stands and its proposed wording, or a version of it in the site's own voice, should go into the pages. "With a narrower reading" means the audit's paraphrase of the website claim is stronger than the sentence printed, and the correction is to be applied to the sentence, not to the paraphrase. "Partly agreed" means one part of the finding stands and another does not. "Cannot be settled here" means more material is needed before anything is changed.

## What to apply first

- [C33](#c33) The Drude case reverses Daun et al. on surface scattering; confirmed on p. 154 today. Rewrite the sentence.
- [C35](#c35) The approximation-error sampling ranges on p. 152 and the prior ranges of Eq. (22) differ by a power of ten; confirmed today. Say so; ask the authors before P6.
- [C34](#c34) The plasmon peak near 190 nm lies outside the 205–585 nm range; confirmed on p. 152. "Reaches the shoulder", not the peak.
- [C41](#c41) The diagonal of the covariance does not hide the valley's length; it hides its direction. Rewrite §2 and §3 of the discourse.
- [C17](#c17) and [C07](#c07) The vocabulary: a zero singular value is a local statement, homometry is a discrete ambiguity, and neither is "a fibre of positive dimension". Rewrite the glossary and §3.
- [C25](#c25), [C26](#c26), [C27](#c27) The dielectric case misdescribes Kuzmenko's method and overstates what causality gives; confirmed against 083108-1 to -4 today. Rewrite the "external tools" paragraph.
- [C30](#c30) Add De Sousa Meneses et al. 2007 to the Sources page as the primary reference for the finite-range correction difes implements.

## The audit's evidence, spot-checked today

Four of the audit's sources were re-opened at the pages it cites, to see whether the locators carry what the audit says they carry. They do, in every case checked. The other sources were not re-opened; their findings are judged on the audit's quoted passages and on the website's sentence.

| Source | Evidence | Findings |
| --- | --- | --- |
| [daun2019](https://doi.org/10.1016/j.jqsrt.2019.01.021) | re-read today; printed pp. 152–155 (the sampling ranges after Eq. (18), Eq. (22), the plasmon passage, §5 right column, the supplementary note) | [C32](#c32), [C33](#c33), [C34](#c34), [C35](#c35), [C36](#c36), [C40](#c40) |
| [kuzmenko2005](https://doi.org/10.1063/1.1979470) | re-read today; printed 083108-1 (Eqs. (3)–(4) and the condition on $r$), -2 (the ill-posed functional space, Eq. (7)), -3 (§IV.A, the dense anchor mesh), -4 (§IV.D, extrapolations and the two-step scheme) | [C25](#c25), [C26](#c26), [C27](#c27), [C28](#c28) |
| [transtrum2015](https://doi.org/10.1063/1.4923066) | re-read today; printed 010901-4 (§III: the unit-change example, dimensionless parameters, the hyperribbon) | [C13](#c13), [C16](#c16), [C19](#c19) |
| [perezmato2010](https://doi.org/10.1107/S0108767310016247) | re-read today; printed pp. 564–565 (§4: the hierarchy of modes, eigenmodes of the energy Hessian, Eq. (9)) | [C09](#c09), [C12](#c12), [C13](#c13), [C14](#c14) |

## Finding by finding

### C01 {#c01}

**Hadamard and the modern definition**

**Verdict:** Agreed: apply.

**Audit said:** Needs qualification or a better citation — Hadamard's 1902 text is historical; the three-part modern definition needs a modern source.

**Website sentence:** The Sources page: "The definition of a well-posed problem (existence, uniqueness, continuous dependence); an underdetermined inverse problem fails the second and third."

**Audit finding:** [C01 in the audit](../citation-audit-2026-10-14/index.html#c01)

**Assessment:** Right on both counts. The three conditions are the textbook form, not Hadamard's words, and the Sources page attributes them to him. The second half of the sentence is also loose: non-uniqueness fails uniqueness; whether continuous dependence fails is a separate question about the chosen solution.

**Decision:** Keep Hadamard as the historical source and add a modern one for the definition (Tarantola 2005 or Kaipio and Somersalo 2005 would do; both are already on the page). Drop "and third".

### C02 {#c02}

**Probabilistic inverse problems**

**Verdict:** Agreed: apply.

**Audit said:** Supported within stated scope; add the locators (preface p. xi, §1.5 p. 35).

**Audit finding:** [C02 in the audit](../citation-audit-2026-10-14/index.html#c02)

**Assessment:** Nothing to add. The locators are a gift; the Sources page had none.

**Decision:** Add the locators to the Sources entry.

### C03 {#c03}

**Kaipio and Somersalo and approximation error**

**Verdict:** Cannot be settled here.

**Audit said:** Not fully verified — Daun's attribution to the book is verified; the book's own pages are not in the collection.

**Audit finding:** [C03 in the audit](../citation-audit-2026-10-14/index.html#c03)

**Assessment:** Agreed, and nothing in the project changes it: the book is not on disk. The site's use of the reference is through Daun, and says so.

**Decision:** Leave the entry as "cited through Daun et al., p. 152" until the chapter is obtained; that is what the Sources page's "not checked" already means, and the audit's wording makes it explicit.

### C04 {#c04}

**Kennedy and O'Hagan and physical parameter meaning**

**Verdict:** Agreed: apply.

**Audit said:** Needs qualification — the abstract supports calibration with a discrepancy term, not the unconditional "the parameters lose their physical meaning".

**Website sentence:** The Sources page: "the parameters lose their physical meaning when the discrepancy is left out."

**Audit finding:** [C04 in the audit](../citation-audit-2026-10-14/index.html#c04)

**Assessment:** Agreed. "Can be biased" is what the sources show, and Brynjarsdóttir and O'Hagan is the better reference for it. The audit's added caution — that a discrepancy term does not by itself identify the parameters — is the more important point for the programme, since P3 and P4 propose to detect inadequacy at scale and will meet exactly this confounding.

**Decision:** Apply the proposed wording on the Sources page; carry the confounding caution into P4.

### C05 {#c05}

**Bias and overconfidence from ignored discrepancy**

**Verdict:** Agreed: apply.

**Audit said:** Supported within stated scope; keep "can".

**Audit finding:** [C05 in the audit](../citation-audit-2026-10-14/index.html#c05)

**Assessment:** The discourse already says "can be excellent and the parameters meaningless, or worse, meaningful-looking and biased". The audit's condition is the right one.

**Decision:** Keep; add the sentence about physically meaningful priors for the discrepancy where P4 is described.

### C06 {#c06}

**Raue and the identifiability distinction**

**Verdict:** Agreed: apply.

**Audit said:** Supported within stated scope, at abstract level.

**Audit finding:** [C06 in the audit](../citation-audit-2026-10-14/index.html#c06)

**Assessment:** The site uses Raue for the two terms and nothing else. Agreed that the Jacobian claims of §3 do not rest on it and should not be read as if they did.

**Decision:** Keep; the Sources entry already says "not checked", which the audit's "abstract only" refines.

### C07 {#c07}

**Homometry versus a linear null space**

**Verdict:** Agreed: apply.

**Audit said:** Needs qualification — homometric structures are a discrete exact ambiguity, not a linear null space nor a continuous family; the audit's counterexample is $F(x) = x^2$.

**Website sentence:** The discourse's definition: "Structural non-identifiability — an exact null space of the forward map … Patterson's homometric structures … are distinct arrangements with the same set of interatomic vectors and hence the same intensities."

**Audit finding:** [C07 in the audit](../citation-audit-2026-10-14/index.html#c07)

**Assessment:** Agreed. The definition box mixes a continuous notion (null space) with a discrete example (homometry). Since the project fixed its vocabulary deliberately, the fix belongs in the definition itself: an exact ambiguity is any pair of configurations with the same response; it may be a continuous family (a fibre of positive dimension) or a discrete set (homometry, the phase problem's enantiomorph pair); "null space" is the local, linear picture of the first.

**Decision:** Rewrite the definition with the two kinds named; keep Patterson as the discrete example. One change serves C07 and C17.

### C08 {#c08}

**Rietveld profile refinement and forward-model certainty**

**Verdict:** Agreed: apply.

**Audit said:** Needs qualification — "nothing in the forward map is in doubt" is not supported; profile, background, orientation, microstructure, missing phases are modelling choices.

**Website sentence:** The Rietveld case: "It is the known theory of T01 in its purest form: nothing in the forward map is in doubt."

**Audit finding:** [C08 in the audit](../citation-audit-2026-10-14/index.html#c08)

**Assessment:** Agreed; the sentence is literal and overstated. What was meant is that the structure-factor part — kinematic scattering from a periodic density — is settled physics, and that the doubt lives in the profile and the sample terms. The page's own "Off the manifold" list says so two paragraphs later, which is the contradiction the audit caught.

**Decision:** Rewrite: "the scattering physics is settled; the profile, the background and the sample terms are modelling choices, and that is where the third kind of underdetermination enters."

### C09 {#c09}

**What mode crystallography demonstrably provides**

**Verdict:** Agreed: apply.

**Audit said:** Supported within stated scope (p. 558); keep this description apart from the later identifiability extrapolations.

**Audit finding:** [C09 in the audit](../citation-audit-2026-10-14/index.html#c09)

**Assessment:** Agreed, and the audit's "keep apart" is the key to C13 and C14: what Perez-Mato et al. establish is a physical organisation of the degrees of freedom; what the discourse adds about the data's sensitivity is this development's and must be marked as a hypothesis.

**Decision:** Keep; add the locator; the attribution line of §4 already says the reading is this development's, and will say so more plainly after C13.

### C10 {#c10}

**AMPLIMODES decomposition and refinement output**

**Verdict:** Agreed: apply.

**Audit said:** Supported within stated scope (pp. 820, 832).

**Audit finding:** [C10 in the audit](../citation-audit-2026-10-14/index.html#c10)

**Assessment:** Agreed. The audit checked the AMPLIMODES half of the sentence; the ISODISTORT half ("writes the amplitudes as refinable parameters for Rietveld programs") was not checked by the audit and is listed below as a gap.

**Decision:** Add the locators; check the ISODISTORT half (gap G2).

### C11 {#c11}

**ISODISPLACE and orthonormal basis conventions**

**Verdict:** Agreed: apply.

**Audit said:** Needs qualification — Campbell et al.'s CLIROP modes need not be orthogonal in non-rectangular cells; AMPLIMODES normalises; freezing modes restricts the model.

**Website sentence:** The discourse, §4: "writes that same field in a different orthonormal basis … Nothing is lost: the configuration space is the same space, the number of coordinates the same number, the map … linear and invertible."

**Audit finding:** [C11 in the audit](../citation-audit-2026-10-14/index.html#c11)

**Assessment:** Agreed on the facts; the discourse's point survives in the audit's own wording ("alternative coordinates for the same allowed displacements"), with "orthonormal" made a convention rather than a property. The last clause of the audit — that fixing modes restricts the model — is not a correction but the mechanism the discourse describes: the restriction is the prior.

**Decision:** Say "a complete, invertible change of basis, orthonormal in AMPLIMODES's convention"; keep the rest.

### C12 {#c12}

**Primary-mode hierarchy and sparse priors**

**Verdict:** Agreed: apply.

**Audit said:** Needs qualification — §4 of Perez-Mato supports a hierarchy in suitable displacive systems, not a universal one-or-two-mode rule; and the same prior can be written in atomic coordinates, less simply.

**Website sentence:** The discourse, §4, point 1: "In atomic coordinates that knowledge cannot even be written down."

**Audit finding:** [C12 in the audit](../citation-audit-2026-10-14/index.html#c12)

**Assessment:** Agreed; pp. 564–565 were re-read today and say what the audit says: primary eigenmodes unstable, secondary ones induced through Eq. (9), amplitudes "expected to be" smaller. "Cannot even be written down" is rhetoric; the true statement is that the prior is sparse and separable in one basis and dense and correlated in the other, which is the whole point and needs no exaggeration.

**Decision:** Replace the sentence with the audit's: the hierarchical prior is easier to express and apply in mode coordinates; its transform exists in atomic coordinates and is not simple.

### C13 {#c13}

**Symmetry modes do not necessarily diagonalize the data sensitivity**

**Verdict:** Partly agreed.

**Audit said:** Incorrect as written — the papers do not establish that symmetry modes are singular vectors of the instrument-weighted Jacobian; Perez-Mato's privileged eigenmodes are those of the energy Hessian; an orthogonal change of basis preserves the singular values.

**Website sentence:** The discourse, §4, point 2: "When two atoms move together by symmetry, a powder pattern sees their joint displacement and not the difference; in atomic coordinates that is a sloppy valley between two parameters, in mode coordinates it is one amplitude that is well determined and one that is small and may be fixed. The general principle: choose the coordinates in which the near-null space of the Jacobian is aligned with the axes."

**Audit finding:** [C13 in the audit](../citation-audit-2026-10-14/index.html#c13)

**Checked against:** Perez-Mato pp. 564–565, re-read today: the eigenmodes are "eigenmodes of the matrix of second derivatives of the free energy with respect to the atomic displacements" — the energy, as the audit says, not the measurement. Transtrum 010901-4: the Fisher matrix transforms as a metric under reparameterisation.

**Assessment:** The first part stands: the example sentence asserts that the symmetric combination is seen and the antisymmetric one is not, and nothing cited shows it; which combination a powder pattern determines depends on the structure factors, not on the symmetry alone. The audit's algebra is right: an orthogonal $B$ leaves the singular values alone, so no basis change can shorten a valley; it can only name it. Not agreed is the paraphrase: the second sentence states the principle as an aim ("choose the coordinates in which…"), not as a property the papers establish, and the attribution line of §4 already marks the reading as this development's. The honest position, then: the alignment of the symmetry basis with the sensitivity basis is a hypothesis, plausible for symmetry-related pairs, and exactly what P2 is designed to test. The finding sharpens the programme rather than weakening it. A candidate source for the practitioners' experience that mode refinements converge with fewer correlations — Kerman et al. 2012, J. Appl. Cryst., on superstructure determination by symmetry-mode analysis — is noted from memory and *not checked*.

**Decision:** Rewrite point 2 as a hypothesis with its test (P2); keep the principle as an aim; cite Perez-Mato for the energy eigenmodes and say they are not the measurement's; add the candidate source to the Sources page as "not checked".

### C14 {#c14}

**Amplitude magnitude is not uncertainty**

**Verdict:** Agreed: apply.

**Audit said:** Incorrect as written — a large amplitude is not thereby well determined nor a small one undetermined; the information about an additive parameter is $1/\sigma^2$ whatever its value.

**Website sentence:** The discourse, §4, point 3: "this amplitude large and determined, that one small and undetermined."

**Audit finding:** [C14 in the audit](../citation-audit-2026-10-14/index.html#c14)

**Assessment:** Agreed without reservation; the sentence conflates two rankings that the programme itself wants kept apart (P4's "identifiability maps" are precisely the second ranking). The audit's proposed wording — report amplitudes with uncertainties and correlations; rank contribution and identifiability separately — is the right one and should become a rule of the project.

**Decision:** Apply; add the two-rankings rule to CLAUDE.md next to the three words.

### C15 {#c15}

**Sloppy sensitivity spectra**

**Verdict:** Agreed: apply.

**Audit said:** Supported within stated scope; the sources do not show that every inverse problem is sloppy.

**Audit finding:** [C15 in the audit](../citation-audit-2026-10-14/index.html#c15)

**Assessment:** Agreed. The discourse calls sloppiness "the typical case" of practical non-identifiability; "typical" is what Gutenkunst et al. found across their seventeen models, and the word should be tied to that scope.

**Decision:** Keep, with the scope and Fig. 1 cited.

### C16 {#c16}

**A small singular value needs a parameter scale**

**Verdict:** Agreed: apply.

**Audit said:** Incorrect as written — the singular values of the noise-whitened Jacobian change with the units and scales of the parameters; "much smaller than one" means nothing until the parameters are scaled.

**Website sentence:** The discourse, §3: "a singular value of zero is a structural non-identifiability, a singular value much smaller than one is a practical one."

**Audit finding:** [C16 in the audit](../citation-audit-2026-10-14/index.html#c16)

**Checked against:** Transtrum 010901-4, re-read today: changing a rate constant from Hz to kHz scales its row and column of the Fisher matrix by 1000; dimensionless (log) parameters make the eigenvalues meaningful.

**Assessment:** Agreed, and it is a real omission: P1 asks programs to print this spectrum, and without a scale the spectrum is arbitrary. The natural scale is the one the project already talks about — the prior width of each parameter (a mode amplitude's plausible range, an occupancy's 0 to 1) — so the fix is to whiten the parameters as well as the data: $J_s = \Gamma^{-1/2}\,\partial F/\partial\theta\,S$ with $S$ the matrix of parameter scales.

**Decision:** Apply in §3 and in P1; "small" then means "small relative to one standard unit of prior width per unit of noise".

### C17 {#c17}

**Local Jacobian rank is not a complete structural-identifiability test**

**Verdict:** Agreed: apply.

**Audit said:** Incorrect as written — a zero singular value is local and first-order ($x^3$ at 0); a discrete ambiguity has full rank ($x^2$ at $\pm 1$); structural non-identifiability is not always a positive-dimensional fibre.

**Website sentence:** The discourse, §3 and §9: "a singular value of zero is a structural non-identifiability"; "Structural non-identifiability: a fibre of positive dimension."

**Audit finding:** [C17 in the audit](../citation-audit-2026-10-14/index.html#c17)

**Assessment:** Agreed; the counterexamples are elementary and decisive. The glossary should separate four things the discourse ran together: global against local, continuous against discrete, exact against first-order. The repair is small and the discourse is better for it: the Jacobian is the local diagnostic of the continuous case; discrete ambiguities need a global search (which is, incidentally, one more reason for P2's "many starting points").

**Decision:** Rewrite the two definitions and the sentence in §3; one change with C07.

### C18 {#c18}

**A likelihood region is not a posterior**

**Verdict:** Agreed, with a narrower reading of the text.

**Audit said:** Incorrect as written — the chi-square tube is a thresholded misfit set, not a posterior, and not automatically a credible region.

**Website sentence:** The discourse, §8, first objection: "In form, yes: the tube is a posterior, the prior is a prior." And §3, where the tube is defined as "every configuration whose response is within noise of the measurement".

**Audit finding:** [C18 in the audit](../citation-audit-2026-10-14/index.html#c18)

**Assessment:** The definition in §3 is what the audit asks for — a set; the loose sentence is in §8, where "the tube is a posterior" was shorthand for "the tube is what a flat-prior posterior is supported on above a threshold". Shorthand in a section that answers the objection "this is just Bayesian inference" is the wrong place to be loose. The verdict stands for that sentence; the audit's claim that the site defines the tube as a posterior is not what §3 says.

**Decision:** Rewrite the sentence in §8: with a flat prior and Gaussian noise the tube is a highest-likelihood region; with a prior it is reweighted; the posterior is the normalised product. Leave §3.

### C19 {#c19}

**The model-manifold description**

**Verdict:** Agreed: apply.

**Audit said:** Supported within stated scope; "manifold" is a regular-model description, not a smoothness guarantee.

**Audit finding:** [C19 in the audit](../citation-audit-2026-10-14/index.html#c19)

**Assessment:** Agreed; "typically a thin, curved ribbon with boundaries" is what 010901-4 says of the sloppy models studied, and the discourse's "typically" should be read with that scope.

**Decision:** Keep; cite §§II–IV.

### C20 {#c20}

**Cranmer supports approximate amortized inference, not guaranteed recovery**

**Verdict:** Agreed, with a narrower reading of the text.

**Audit said:** Needs qualification — the review describes approximate surrogates with finite-sample and calibration errors; it does not guarantee branch recovery, out-of-distribution accuracy or the timing claim.

**Website sentence:** The discourse, §7: "to return, for any new response, the posterior over configurations … this gives the fibre with its curvature and its disconnected branches, for every pattern of a measurement campaign in the time a single refinement takes."

**Audit finding:** [C20 in the audit](../citation-audit-2026-10-14/index.html#c20)

**Assessment:** The sentence does overclaim: "the posterior" should be "an approximate posterior over the simulated domain", and "its disconnected branches" is a hope, not a property. The audit's "guaranteed campaign-scale speed" is stronger than "in the time a single refinement takes", which is the amortisation argument (training once, evaluating cheaply) and is plausible, though not shown here. The correction applies to the sentence as printed.

**Decision:** Apply the audit's wording in §7 and P4: approximate, over a stated domain, validated for calibration and branch coverage before use.

### C21 {#c21}

**Park dataset and accuracy figures**

**Verdict:** Agreed: apply.

**Audit said:** Supported within stated scope; the exact values are 94.99, 83.83 and 81.14 % on a 20 % test split of simulated data.

**Audit finding:** [C21 in the audit](../citation-audit-2026-10-14/index.html#c21)

**Assessment:** The site's rounded numbers are right; the audit's caution — these are benchmark accuracies, not limits of what a pattern can tell — is the same point the discourse makes about ML in general, and should be said where the numbers are quoted.

**Decision:** Add "on their simulated-data test split" where the numbers appear.

### C22 {#c22}

**Lee dataset size and chemical scope**

**Verdict:** Agreed: apply.

**Audit said:** Supported within stated scope; 1 785 405 patterns, 170 compounds, the Sr–Li–Al–O pool.

**Audit finding:** [C22 in the audit](../citation-audit-2026-10-14/index.html#c22)

**Assessment:** Agreed; the chemical scope matters for the discourse's own argument about transfer (C42) and should be named.

**Decision:** Name the Sr–Li–Al–O pool.

### C23 {#c23}

**Szymanski probabilities are phase-classification confidence**

**Verdict:** Agreed, with a narrower reading of the text.

**Audit said:** Needs qualification — the probabilities are dropout-ensemble confidences over phase labels, not a posterior over continuous parameters; the method still identifies phases.

**Website sentence:** The Sources page: "an ensemble that returns probabilities, not labels — the form the output must take when the problem is underdetermined." The discourse, §6: "train on simulated spectra augmented with physics-informed perturbations and return probabilities from an ensemble."

**Audit finding:** [C23 in the audit](../citation-audit-2026-10-14/index.html#c23)

**Assessment:** The site cites Szymanski for the form of the output and for the physics in the generator, not as posterior inference over a refinement's configuration; the audit's paraphrase adds "providing the required form of output for an underdetermined inverse problem", which the Sources line does say and the discourse does not. The distinction the audit draws — classification confidence against a posterior over continuous parameters — is right and worth stating, because P4 wants the second.

**Decision:** Say "phase-classification confidences from a dropout ensemble" on the Sources page; leave §6.

### C24 {#c24}

**The three ML papers are precedents, not the proposed mode-refinement pipeline**

**Verdict:** Partly agreed.

**Audit said:** Needs qualification — the three papers do classification and phase identification, not posterior mapping of mode refinements; three papers cannot establish novelty or the absence of competing work.

**Website sentence:** The Rietveld case: "What none of these does is what T07 and T09 together ask for: the refinement itself, in mode coordinates, done over a corpus." The discourse, §8: "What is not done is the generalisation of the move to problems without space groups, and its automation over a corpus with the tube kept."

**Audit finding:** [C24 in the audit](../citation-audit-2026-10-14/index.html#c24)

**Assessment:** The first sentence is a statement about these three papers and is correct as printed; the audit's paraphrase ("establish the proposed pipeline") is not what it says — the page says the opposite, that they do something else. The second sentence is a claim about the field and the audit is right that nothing on the site supports it: no search was made. Agreed for §8, not for the case page.

**Decision:** Leave the Rietveld sentence; rewrite §8 as "not done in what this project has read; the search is the first task of P7".

### C25 {#c25}

**Kuzmenko's background model and dense variational mesh**

**Verdict:** Agreed: apply.

**Audit said:** Needs qualification — the central method puts an oscillator at every node of a dense anchor mesh, with as many parameters as data points; a few-parameter model is only the first step that supplies the extrapolation.

**Website sentence:** The Sources page and the dielectric case: "the dielectric function as a free, causal function anchored by a few oscillators".

**Audit finding:** [C25 in the audit](../citation-audit-2026-10-14/index.html#c25)

**Checked against:** Kuzmenko 083108-1 (abstract: "the number of oscillators is on the order of the number of experimental points"), -3 (§IV.A: an oscillator at every anchor frequency), -4 (§IV.D: a model function with a limited number of parameters fitted first, then the variational part added, Eq. (17)), re-read today.

**Assessment:** Agreed; the site's phrase was written from memory and describes the two-step scheme backwards. The audit's correction is confirmed line by line. What the site wanted from the reference survives: the data determine $\epsilon(\omega)$ on the range, and the physical meaning of individual oscillators "may not be always clear" (083108-3) — Kuzmenko says it himself.

**Decision:** Apply the audit's wording; quote 083108-3 for the point the site was making.

### C26 {#c26}

**Phase recovery needs analytic and geometry conditions**

**Verdict:** Agreed: apply.

**Audit said:** Needs qualification — the log-reflectivity relation needs $r \neq 0$ in the upper half-plane; it fails for sufficiently oblique incidence and for thin films; the relation is to $\ln r$, not to $r$.

**Website sentence:** The dielectric case: "the phase is fixed by the modulus over the whole axis, which recovers what the measurement did not record."

**Audit finding:** [C26 in the audit](../citation-audit-2026-10-14/index.html#c26)

**Checked against:** Kuzmenko 083108-1, Eqs. (3)–(4) and the paragraph after them, re-read today: "a necessary condition is that $r(\omega) \neq 0$ for $\mathrm{Im}(\omega) > 0$ … holds for the normal angle of incidence but breaks down, for instance, for off-normal reflectivity if the angle of incidence is large enough. The same problem appears when the sample is a thin film."

**Assessment:** Agreed; and the condition matters to the group, whose emittance measurements are not all at normal incidence on semi-infinite samples. The site's sentence is true for the standard case and silent on the conditions.

**Decision:** Apply, naming the normal-incidence semi-infinite case and the two failures. The same correction fixes the comparison table (gap G1).

### C27 {#c27}

**Unmeasured spectral weight is not generically invisible**

**Verdict:** Agreed: apply.

**Audit said:** Incorrect as written — out-of-band spectral weight contributes to $\epsilon_1$ inside the band through the Kramers–Kronig integral; it is weakly and ambiguously constrained, not in a null space.

**Website sentence:** The dielectric case, under "Exactly": "Everything outside the measured range is in the null space, and the Kramers–Kronig integrals reach into it."

**Audit finding:** [C27 in the audit](../citation-audit-2026-10-14/index.html#c27)

**Checked against:** Kuzmenko 083108-4, §IV.D, re-read today: "the nonzero wings of $\epsilon_2$ at higher and lower frequencies are essential to calculate $\epsilon_1$ inside this region."

**Assessment:** Agreed, and the error is instructive for the discourse's own taxonomy: out-of-band weight is seen in-band, weakly, through a smooth kernel — it is the second kind of underdetermination, not the first, and the sentence filed it under the first. The second clause of the sentence ("the integrals reach into it") already contains the correction.

**Decision:** Move the item to "At the noise" with the audit's wording.

### C28 {#c28}

**Oscillator non-identifiability is not universal**

**Verdict:** Agreed: apply.

**Audit said:** Incorrect as written — a rational response with distinct simple poles has a unique partial-fraction form; exact non-uniqueness needs coincident poles or a free model order; overlap, finite band and noise make fits weakly determined, not degenerate.

**Website sentence:** The dielectric case, under "Exactly": "a smooth $\epsilon(\omega)$ can be written as a sum of overlapping Lorentzians in many ways: the decomposition of a continuous function into a finite set of oscillators is not unique, so the oscillator parameters are not identifiable even when $\epsilon(\omega)$ itself is."

**Audit finding:** [C28 in the audit](../citation-audit-2026-10-14/index.html#c28)

**Assessment:** Agreed; the partial-fraction argument settles the exact case. The practitioner's point — that in practice the number of oscillators is a choice and overlapping ones trade against each other — is true and belongs, again, under the second kind, with the model order named as the hypothesis the human brings (which the Cases table already lists under "What the human still brings").

**Decision:** Move to "At the noise"; say "for a chosen model order the parameters are identifiable in principle; across model orders, and with overlap and noise, the fits are weakly determined."

### C29 {#c29}

**difes software claims and optical assumptions**

**Verdict:** Agreed: apply.

**Audit said:** Supported within stated scope at commit 55e78ff; state the normal-incidence, geometry and opacity assumptions next to the equations.

**Audit finding:** [C29 in the audit](../citation-audit-2026-10-14/index.html#c29)

**Assessment:** Agreed; the commit should be on the Sources page, and the assumptions are the same ones C26 asks for.

**Decision:** Add the commit and the assumptions.

### C30 {#c30}

**A missing primary source for finite-range correction**

**Verdict:** Agreed: apply.

**Audit said:** Needs a better citation — difes's `kk.py` attributes its finite-range correction to De Sousa Meneses, Rousseau, Echegut and Simon 2007, Applied Spectroscopy 61, 1390–1397, not to Kuzmenko.

**Audit finding:** [C30 in the audit](../citation-audit-2026-10-14/index.html#c30)

**Assessment:** Agreed, and it is the audit's most useful addition to the bibliography: the CEMHTI paper is the primary source for the method the group's own tool implements, and FOCUS comes from the same laboratory. Full text not obtained by the audit.

**Decision:** Add the reference to the Sources page with status "checked" (identity confirmed by the audit) and "full text not obtained"; cite it in the dielectric case next to the finite-range correction.

### C31 {#c31}

**The thesis cannot yet support a detailed technical claim**

**Verdict:** Agreed: apply.

**Audit said:** Not fully verified — bibliographic context only.

**Audit finding:** [C31 in the audit](../citation-audit-2026-10-14/index.html#c31)

**Assessment:** Agreed; the site uses the thesis only to place Iñigo's domain, and should keep to that. Iñigo can supply the chapters that matter when the dielectric case is discussed.

**Decision:** Keep as context; ask Iñigo for the chapters.

### C32 {#c32}

**Daun experimental conditions and tabulated parameters**

**Verdict:** Agreed: apply.

**Audit said:** Supported within stated scope; label Table 3 as the LDLS comparison; keep the temperature's adopted status explicit.

**Audit finding:** [C32 in the audit](../citation-audit-2026-10-14/index.html#c32)

**Assessment:** Agreed on both labels. The Drude case already says the temperature is "taken as 1550 $\pm$ 35 K from earlier silicon work".

**Decision:** Label the table.

### C33 {#c33}

**Daun surface scattering explanation is reversed**

**Verdict:** Agreed: apply.

**Audit said:** Incorrect as written — the authors estimate a mean free path of 0.54 nm, far below the 40 nm particle, and discount surface scattering; they favour the inadequacy of the free-electron model.

**Website sentence:** The Drude case: "the authors' reading is that about three electrons per atom, not four, are in the conduction band, or that electron scattering at the surface matters at 40 nm — either way a model that is not Drude with bulk values."

**Audit finding:** [C33 in the audit](../citation-audit-2026-10-14/index.html#c33)

**Checked against:** Daun p. 154, §5, re-read today: "Were the electron mean free path comparable to the diameter of the nanoparticle … Taking $E_F = 1.9 \times 10^{-19}$ J … results in $\lambda_e = 0.54$ nm, which is much smaller than the particles in this study (~40 nm) … A more likely explanation is that the simplistic free electron model … does not capture the true interaction."

**Checked against (second passage):** p. 154: "suggests that each atom contributes three, not four, electrons to the conduction band."

**Assessment:** Agreed; the site's "or" joins an explanation the authors keep with one they discard, and so misreports the paper. The "three, not four" half is right. This is the audit's most valuable single catch, and the kind of error a citation audit exists for.

**Decision:** Rewrite: the authors consider surface scattering and rule it out on the mean free path; what remains is the free-electron model itself.

### C34 {#c34}

**The LDLS sees the shoulder, not the 190 nm peak**

**Verdict:** Agreed: apply.

**Audit said:** Incorrect as written — the measurement starts at 205 nm; the paper says the LDLS captures more of the variation caused by a resonance whose peak is near 190 nm; the higher signal-to-noise also narrows the posterior.

**Website sentence:** The Drude case: "With the laser-driven source, which reaches the surface-plasmon resonance near 190 nm, it is narrower still."

**Audit finding:** [C34 in the audit](../citation-audit-2026-10-14/index.html#c34)

**Checked against:** Daun p. 152, re-read today: "captures more of the spectral variation caused by a surface plasmon resonance (SPR) having a peak near 190-nm … The higher signal-to-noise of the LDLS, combined with the fact that it captures more of the SPR".

**Assessment:** Agreed; "reaches" was careless, and the signal-to-noise half of the explanation was dropped. Both parts of the paper's sentence belong on the page, because both bear on P6's design calculation: range and noise.

**Decision:** Rewrite with the paper's two reasons.

### C35 {#c35}

**Daun approximation-error sampling is not the stated prior range**

**Verdict:** Agreed: apply.

**Audit said:** Incorrect as written — p. 152 samples the model-error term over $[1.5, 3] \times 10^{15}$ $\mathrm{s}^{-1}$ and $[1.5, 3] \times 10^{-15}$ s; Eq. (22) gives priors of $[1.5, 4.5] \times 10^{16}$ rad/s and $[1.5, 4.5] \times 10^{-16}$ s; the site silently equates them.

**Website sentence:** The Drude case: "the difference between the approximation and the exact Mie result, sampled over the prior range of $(\omega_p, \tau)$, gives a mean and a covariance".

**Audit finding:** [C35 in the audit](../citation-audit-2026-10-14/index.html#c35)

**Checked against:** Daun p. 152, text after Eq. (18), and p. 153, Eq. (22), re-read today; the two intervals are printed as the audit transcribes them.

**Assessment:** Agreed. The site smoothed over a discrepancy in the paper that a reader of the paper would want to know about, and that P6 cannot ignore: a replication must choose, and should ask the authors. The audit's reading — a probable typographical problem — is likely (the prior intervals are the physically plausible ones for a metal) but is not the site's to decide.

**Decision:** State the two intervals and the discrepancy; make "ask the authors" the first step of P6.

### C36 {#c36}

**Low-frequency Drude degeneracy is a limiting approximation**

**Verdict:** Partly agreed.

**Audit said:** Needs qualification — Eq. (4) keeps separate dependence on $\omega_p$ and $\tau$ at finite frequency; only in a reduced leading-order model do the data depend on the product alone.

**Website sentence:** The discourse's definition: "In the Drude model at low frequencies only the product $\omega_p^2\tau$, the dc conductivity, is seen: a spectrum confined to that range cannot separate the two parameters at all." The Cases table: "At long wavelengths only $\omega_p^2\tau$ (the dc conductivity) enters."

**Audit finding:** [C36 in the audit](../citation-audit-2026-10-14/index.html#c36)

**Assessment:** The audit's algebra is right: for $\omega\tau \ll 1$, $\epsilon_{\mathrm{II}} \approx \omega_p^2\tau/\omega$ carries the product and $\epsilon_{\mathrm{I}} \approx 1 - \omega_p^2\tau^2$ carries a different combination, so the full expression is not a function of the product alone; what makes the reflectance of a good metal depend on $\sigma_{\mathrm{dc}}$ alone in the Hagen–Rubens regime is that $\epsilon_{\mathrm{II}}$ dominates. The site's sentence says "at low frequencies", which is the limit statement, and the audit's paraphrase ("creating exact non-identifiability of the full model") is stronger than it. But the site files the example under the exact kind, and by its own vocabulary a limit is not exact. Agreed on the placement; not agreed on the paraphrase.

**Decision:** Keep the example, name the Hagen–Rubens limit, and move it to the practical kind: "in the limit, only the product is seen; at finite frequency the separate sensitivities exist and may be too weak to resolve."

### C37 {#c37}

**A surrogate does not automatically remove model error**

**Verdict:** Agreed, with a narrower reading of the text.

**Audit said:** Proposal presented too strongly — a learned emulator has its own approximation error; exact Mie does not repair an inadequate Drude model.

**Website sentence:** The discourse, §7: "A forward model learned once from the exact theory is both fast and exact to within a known tolerance, and takes that term away." The Drude case: "would be unnecessary with a forward surrogate learned once from the exact Mie sums; the MCMC would then run on the exact theory."

**Audit finding:** [C37 in the audit](../citation-audit-2026-10-14/index.html#c37)

**Assessment:** The Drude case's sentence is wrong as printed ("run on the exact theory"); the discourse's is nearly right ("to within a known tolerance") but "takes that term away" is not: it replaces a fixed, structured bias by an error that can be bounded and, with enough training, made smaller than the noise — which is better, not the same as absent. The audit's second point, that exact Mie does not fix Drude, is true and was never claimed by the site. The verdict stands for the Drude case's sentence.

**Decision:** Apply the audit's wording in P6 and the Drude case: test the surrogate against exact Mie over the inference domain, bound its error against the noise, report runtime as a measurement.

### C38 {#c38}

**Expected information gain is not determined by a Jacobian alone**

**Verdict:** Agreed: apply.

**Audit said:** Proposal presented too strongly — Bayesian expected information gain needs a prior or current posterior, a noise model, a candidate likelihood and an average over possible data; the Jacobian gives only a local linear-Gaussian approximation; Daun et al. did not do the calculation.

**Website sentence:** The discourse, §7: "the expected information gain of a candidate measurement … is computable from the Jacobian." P6: "show that the ultraviolet source would have been chosen before the halogen lamp was tried."

**Audit finding:** [C38 in the audit](../citation-audit-2026-10-14/index.html#c38)

**Assessment:** Agreed. The Drude case's own phrasing — "the Fisher information per wavelength band" — is the correct local version, and the discourse should say that rather than "expected information gain". P6's "show that" prejudges the result of a calculation not yet done; the audit is right to call it a demonstrated result stated in advance.

**Decision:** Say "a local Fisher-information design, then the posterior-based gain"; rewrite P6 as a test with two possible outcomes.

### C39 {#c39}

**The P1 diagnostic cannot identify all three failure types alone**

**Verdict:** Agreed: apply.

**Audit said:** Proposal presented too strongly — a local SVD cannot prove global uniqueness nor test the model against reality; no source establishes a three-way diagnosis at a glance.

**Website sentence:** P1: "Shows: which of the three kinds of underdetermination the fit is facing, at a glance."

**Audit finding:** [C39 in the audit](../citation-audit-2026-10-14/index.html#c39)

**Assessment:** Agreed; the sentence promises what the three-kinds section of the discourse itself says cannot come from one diagnostic (model inadequacy is in the residuals, not in the Jacobian; discrete ambiguities are not in either). P1 is the cheapest member of a suite — scaled SVD, profile likelihood along the sloppy directions, residual structure, many starting points — and should be described as that.

**Decision:** Rewrite P1 as the first of a suite; say what each member detects.

### C40 {#c40}

**Data availability and reproducibility claims**

**Verdict:** Cannot be settled here.

**Audit said:** Not fully verified — the paper lists supplementary material; the audit did not open it; not having the data is not evidence they are unavailable.

**Website sentence:** P6: "The paper's data are not public, so the reproduction is on synthetic spectra from its own parameters."

**Audit finding:** [C40 in the audit](../citation-audit-2026-10-14/index.html#c40)

**Checked against:** Daun p. 155, re-read today: "Supplementary material associated with this article can be found, in the online version, at doi:10.1016/j.jqsrt.2019.01.021."

**Assessment:** Agreed that the site asserted what it had not checked. The supplement has not been opened by the audit or by this review either, so the question stays open.

**Decision:** Rewrite as "not obtained"; opening the supplement is the first act of P6, before "ask the authors".

### C41 {#c41}

**A covariance diagonal is not a conditional tube cross-section**

**Verdict:** Agreed: apply.

**Audit said:** Incorrect as written — in the local Gaussian picture the diagonal entries are marginal variances, $\mathrm{Cov}_{ii} = \sum_k V_{ik}^2/\sigma_k^2$, and the small singular values contribute to them; reading the diagonal loses orientation and correlation, not the long directions.

**Website sentence:** The discourse's definition of practical non-identifiability: "The standard uncertainties printed from the diagonal of the covariance matrix are the width of the valley in the chosen coordinates, not its length." And §3: "its length along the sloppy directions is what the covariance matrix hides when only the diagonal is read."

**Audit finding:** [C41 in the audit](../citation-audit-2026-10-14/index.html#c41)

**Assessment:** Agreed, and this is the correction with the most consequence for the discourse's argument, because the two sentences are used to say what P1 should add. The algebra is right: a sloppy direction with a component along a parameter's axis makes that parameter's marginal variance large, so the printed e.s.d. does carry the valley's projection. What the diagonal cannot show is that two large e.s.d.'s belong to one valley — that is the correlation coefficient, which FullProf prints and which the discourse elsewhere says "almost nobody reads". The repaired sentence is stronger: the e.s.d.'s are the valley's shadows on the axes; the correlation matrix is its direction; P1 prints the direction.

**Decision:** Rewrite both sentences; keep the conclusion about P1.

### C42 {#c42}

**Transferability and parameter-point dependence**

**Verdict:** Agreed, with a narrower reading of the text.

**Audit said:** Proposal presented too strongly — the Jacobian is defined at a parameter point; identifiable combinations vary with parameters, nuisance effects, noise and model mismatch; the three ML papers show performance in specified tests, not universal transfer.

**Website sentence:** The discourse, §8, second objection: "the primary targets proposed here — which directions of configuration space a given measurement determines — are properties of the forward map and the instrument, not of the sample; they transfer by construction, because they were never about the sample."

**Audit finding:** [C42 in the audit](../citation-audit-2026-10-14/index.html#c42)

**Assessment:** The sentence is an argument, not a claim about the papers, and the audit's "independent of the sample" is close to what it says. The argument is half right: identifiability is a property of the forward map, the instrument and the noise — but at a configuration, so it depends on where in configuration space the sample sits, and "by construction" claims too much. The honest version: the targets are properties of the forward map over the simulated domain, and transfer to a sample is transfer within that domain, to be tested on held-out regimes, as the audit says.

**Decision:** Rewrite the objection's answer with the domain named; add the held-out test to P4.

## The audit as a whole

What it does well, and what the project should keep doing:

- **It separates fidelity from truth.** Each finding says whether the source supports the sentence, and apart from that whether the sentence is right; the two can come apart (C21: the numbers are right, the meaning drawn from them is not).
- **It states its access.** Full text, abstract only, indirect, bibliographic: the kind of evidence behind every finding is on the page, and the verdicts on abstract-only sources (C07, C08, C17 in part) are about the website's wording, where an abstract is enough.
- **Its independent reasoning is right every time.** The elementary counterexamples of C07, C13, C17, C28, C36 and C41 are correct and decisive; none of them needed a source.
- **It found the three factual errors about the one paper the project read in full** (C33, C34, C35), which is the sharpest test a citation audit can pass: the auditor read the pages more carefully than the author did.

Where the audit should be read with care:

- **Five "website claims" are paraphrases stronger than the printed sentence** (C18, C20, C23, C37, C42; and C13's and C24's in part). A future audit should quote the sentence verbatim and put the paraphrase after it, so that the reader can see the gap. The verdicts survive in all five cases; the paraphrases would not.
- **The standard applied is that of a theorem statement.** Four "incorrect as written" verdicts (C13, C16, C27, C28) turn on the strict meaning of "null space", "singular value" and "not identifiable". The project chose to use its three words strictly and is bound by that choice, so the verdicts are accepted; but the practitioner's points behind the sentences (overlapping oscillators trade against each other; out-of-band weight is poorly constrained; an unscaled spectrum is still informative about order of magnitude) are true, and the corrections should keep them.
- **Some proposed wordings replace an argument with a hedge.** "Assess", "validate", "test" are right as instructions to the programme and flat as sentences of a discourse. The corrections will be applied in the site's voice, with the content the audit asks for.

What the audit did not cover (gaps), each a small task:

- **G1 — the Cases comparison table** (`cases/index.qmd`) was not audited. It repeats the claims of the three case pages in a third place and contains at least one the audit contradicts: "The phase of $\tilde r$ from $|\tilde r|$ alone" is listed under "Folded exactly", which C26 shows is false for the standard case. The table must be corrected together with the pages.
- **G2 — the ISODISTORT half of the mode-output sentence** (that it writes amplitudes as refinable parameters for Rietveld programs) was not checked; C10 checked AMPLIMODES only.
- **G3 — the twelve theses of the brief** are preserved as attributed ideas, rightly; but T07's own claim (that mode analysis "discards" coordinate values by symmetry) is the sentence C11 and C13 bear on, and the discussion with Iñigo should know that.
- **G4 — the discourse's attribution lines** ("this development's", "Iñigo's") were not read as claims. They are the site's own provenance and are what makes C13's correction cheap: the sentence was already marked as a reading, not a result.

## Decisions proposed

Nothing has been applied. The proposal is one revision of the discourse, the three case pages, the comparison table, the programme and the Sources page, logged as a single entry when Josu says so, with each change naming its finding. In four groups:

- **Facts, to apply as the audit words them:** C33, C34, C35 (the Drude case); C25, C26, C27 (the dielectric case); C30 (a reference added); C21, C22, C32 (labels and scopes).
- **Vocabulary, to apply in one pass over §2, §3 and §9 of the discourse:** C07 and C17 (exact ambiguities, continuous and discrete; the Jacobian as the local diagnostic of the continuous case); C16 (parameters scaled before the spectrum is read); C41 (the e.s.d.'s are projections; the correlation matrix is the direction); C36 (the Hagen–Rubens example moved to the practical kind); C28 (the oscillator example moved likewise).
- **Claims softened in the site's voice:** C08, C11, C12, C14, C18, C20, C23, C37, C38, C39, C42; C13 and C24 as hypotheses with their tests (P2, P7).
- **Left as they are, with locators added:** C02, C05, C06, C09, C10, C15, C19, C29, C31; C03 and C40 until the material is obtained.

And three rules for the project, from what the audit taught:

- An audit quotes the sentence it judges, verbatim, before its paraphrase.
- Two rankings are reported apart: a parameter's contribution to the structure and its identifiability from the data (C14).
- A claim about the field ("not done", "the best results") is made only after a search, and says so (C24).

## What this review did not do

It did not re-open the sources the audit read only at abstract level, nor obtain the Kaipio book, the thesis chapters, De Sousa Meneses et al. 2007 or the Daun supplement; those are the open items of the audit and remain open. It did not replicate any calculation. It did not read the audit's private claim records under `sources/library/`, only the public report. It was written by an AI assistant about an audit written by another AI assistant of text written by the first; Josu and Iñigo are the reviewers of record, and the decisions above are proposals until they say otherwise.

## Provenance

This page is generated from `source.md` in its folder by `tools/audit_page.py`, the same way as the audit (L011). The audit's report and provenance file are untouched. The review assesses the audit's public edition as published at commit `546e5e4` and the site's pages at the same commit.
