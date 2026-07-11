/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /

---

# The Torsion Null Test

**Status:** DESIGN DRAFT. Pre-registration pending: this design is committed before any null ensemble is run, and it is frozen by a designated freeze commit (tagged `mass-null-v1.0`) after review. No randomization has been executed at draft time. The single-run policy below governs execution.

> **Re-baselined to the canonical torsion table (2026-07-11).** The torsion inputs are the canonical values from [mass-spectrum](../../../../spectrum/files/mass-spectrum.md) §4, including $T^2(R_0) = 1$: the canonical topological value of the non-acyclic trivial local system, not a constant chosen for convenience. This re-baseline updated only the *inputs the test reads*. The statistic, the four nulls, the scoring rule, the RNG seed (120), and the §VII decision bands are unchanged from the pre-correction design. Input error is correctable; the statistic and verdict bands are retained unchanged and are proposed for freeze, the same line drawn for the mass table. The null statistic is $S_1 = 6$ (a compatible-coverage count) while the public headline is 5-of-8 (an assignment count); §I explains why the two differ by exactly one fermion.

**The claim under audit** ([mass-spectrum.md](../../../../spectrum/files/mass-spectrum.md), §III): the ×3 proximity comparison. Under the compatible-coverage reading (§I), $S_1 = 6$ of the 8 scored charged fermions have a quantum-number-compatible entry within a factor of 3 (down outside at 3.22, charm without a compatible entry). The page's assignment headline is 5 of 8; §I explains the one-fermion difference. The page states the caveat this test quantifies: "at this entry density a measured mass sits near some entry largely by counting."

**Dependencies:** mass formula and 24-entry table (mass-spectrum.md §II-III), torsion tables (§II.4), Coxeter-Galois gate and stabilizer decompositions (§IV), PDG masses as frozen below.

**Related:** [Claim Ledger](claim-ledger.md), [McKay Propagator Correction](mckay-propagator-correction.md) (the closed correction route; its residual scatter is context for this test), [R from the Mass Spectrum](r-from-mass-spectrum.md).

---

## I. The Question

How much of the compatible-coverage count ($S_1 = 6$, §IV) survives when the corrected torsion-factor values are randomly reassigned across the entry table, holding everything else fixed?

The formula is $m(\rho, \sigma) = \mu_\Lambda \cdot C_{\text{geom}}(\rho) \cdot (\sqrt{\Omega_\Lambda})^{\text{dist}(\rho)/30} \cdot T^2(\rho \otimes \sigma)$. The first three factors set the coarse ladder (thirteen orders of magnitude of placement); the torsion is the fine dial within each shell. This test isolates the dial. It does not test the ladder, the entry count, the quantum-number gates, or the exact ratios; those are held fixed as the skeleton, and their standing is unaffected by any outcome here.

**The null statistic is a compatible-coverage count, not the public assignment scorecard, and the two differ by one fermion for a principled reason.** The [mass-spectrum](../../../../spectrum/files/mass-spectrum.md) headline reports **5 of 8** under an assignment-level no-slide standard: once $(R_2,\text{gal})$ is named the bottom quark's entry and it sits at 197 GeV under the canonical torsion, the nearest survivor is not renamed to hold the count. This test scores **$S_1 = 6$** under a slot-availability standard: its pre-registered rule (§IV) asks whether *any* quantum-number-compatible slot lies within ×3, and the bottom quark is covered by $(R_4,\text{gal})$ at ratio 1.40. The one-entry gap between the two counts is exactly the bottom quark, which is precisely the fermion whose hit is density-supplied rather than uniquely assigned. The gap is informative, not a disagreement: it localizes, to a single fermion, where the ×3 count depends on density versus unique assignment. "No-slide" is meaningful only for a fixed assignment; under torsion randomization there is no assignment to slide, so the any-compatible rule of §IV is the pre-registered statistic appropriate to the compatible-coverage question.

**The canonical-torsion correction is itself a first data point for this test.** Correcting one load-bearing torsion value, $T^2(R_0)$, displaced the original bottom-quark entry $(R_2,\text{gal})$ by a factor of 37, yet the coverage count did not move: a compatible slot $(R_4,\text{gal})$ was already inside the ×3 window. That is a natural out-of-sample perturbation illustrating the process the ensemble samples: perturb a torsion, ask whether a fermion keeps a compatible slot nearby. It did. (It is not itself a draw from the registered null: the correction was a deterministic provenance fix to one base factor, not a randomization.) The correction is a hand-computed preview of the density effect the null test exists to quantify, pointing the same way the test predicts, which makes the test more necessary, not less.

---

## II. What Is Frozen (the skeleton)

| Item | Frozen value / source |
|---|---|
| Overall scale $\mu_\Lambda$ | $\rho_\Lambda^{1/4} \approx 2.25$ meV, from measured $\Lambda$; no refit per draw |
| Seats $C_{\text{geom}}(\rho)$ | the 8 published values (mass-spectrum.md §II.2) |
| Elevator | $(\sqrt{\Omega_\Lambda})^{\text{dist}(\rho)/30}$, $\sqrt{\Omega_\Lambda} = 1.019 \times 10^{61}$, McKay distances as published |
| Quantum numbers per slot | $(T_3, \text{color channels}, Q)$ for all 24 $(\rho, \sigma)$ slots, computed from the published rules (spectral parity, Coxeter-Galois gate, $Z_3$ channels, Gell-Mann-Nishijima); torsion-independent by construction |
| Scoring rule | Section IV below, verbatim |
| Measured masses (GeV) | $u$ $2.16 \times 10^{-3}$, $d$ $4.67 \times 10^{-3}$, $s$ $9.34 \times 10^{-2}$, $c$ $1.27$, $b$ $4.18$, $t$ $172.7$, $\mu$ $1.057 \times 10^{-1}$, $\tau$ $1.777$ (page values, except $c$ $1.27$ imported from PDG since the page leaves charm unassigned; charm is the one mass not traceable to the source page, and is a miss under both scoring rules, so nothing turns on it) |
| Excluded from scoring | electron (benchmark), the three neutrinos (absolute masses unmeasured) |

The quantum-number map is skeleton because every ingredient of the gates ($j_\text{first}$ parity, the $(13,17)$ Coxeter pair, Galois-fixed content, $Z_3$ channels) is representation theory with no torsion input. Reassigning torsions moves masses; it never moves a slot's kind.

---

## III. What Is Randomized (four nulls)

| Null | Operation | Question it answers |
|---|---|---|
| **A (primary)** | Permute the 24 published $T^2(\rho \otimes \sigma)$ values uniformly across the 24 slots | Do the specific value-to-slot pairings matter at all, or does density plus spread suffice? |
| B | Permute within each vacuum column separately ($8!$ each) | Same, controlling for each vacuum's torsion distribution |
| C | Redraw each $\log T^2$ i.i.d. log-uniform over the observed 24-value range | Does anything beyond the overall spread matter? |
| D | Permute the 9 base torsions $T^2(\tau)$ within spin class ($R_3, R_4, R_5, R_7$ among themselves; $R_1, R_2, R_6, R_8$ among themselves; $R_0$ fixed at its canonical topological value $1$), then re-derive all 24 via $\log T^2(\rho \otimes \sigma) = \sum_\tau N_{\rho\sigma\tau} \log T^2(\tau)$ | The structure-preserving counterfactual: does it matter which irrep carries which torsion, keeping the tensor algebra intact? |

Null A is primary because it is the direct reading of the published caveat ("a random reassignment of the torsions, holding the quantum-number structure fixed"). Null D is the sharpest secondary: it respects the generative algebra, its ensemble is exactly enumerable ($4! \times 4! = 576$ permutations, no Monte Carlo error), and a divergence between A and D would itself be informative (it would mean the tensor rule, not the base values, carries the fit).

The verdict hangs on Null A alone. B, C, D are reported as texture and cannot rescue or overturn the primary verdict.

---

## IV. The Scoring Rule (frozen)

For each of the 8 scored fermions $f$ with measured mass $m_f$:

1. A slot $(\rho, \sigma)$ is **compatible** with $f$ iff its frozen quantum numbers admit $f$'s kind: matching $T_3$, and a color channel of $f$'s type (singlet for leptons, colored pair for quarks), with $Q$ closed by Gell-Mann-Nishijima.
2. $f$ **hits** iff some compatible slot has $\max(m_f/m_{\text{slot}},\ m_{\text{slot}}/m_f) \leq 3$.
3. Sharing is allowed: two fermions of different kind may hit the same slot through different channels (the published $\mu/s$ case at rank 15).

At freeze time the compatibility relation is committed as a machine-readable $8 \times 24$ matrix $C_{f,s} \in \{0,1\}$ (the full 24-slot quantum-number map is the Step-0 deliverable, §VI); the execution code reads $C$ and does not re-derive compatibility during the ensemble. Reproduction gate G3 checks the matrix itself, not only the resulting $S_1$.

Primary statistic $S_1$ = number of the 8 that hit. Observed scorecard under this rule (compatible coverage, §I):

| $f$ | best compatible ratio | hit at $\times 3$? |
|---|---|---|
| $u$ | 1.06 | yes |
| $d$ | 3.22 | no |
| $s$ | 1.10 | yes |
| $c$ | none in range | no |
| $\mu$ | 1.02 | yes |
| $\tau$ | 2.42 | yes |
| $b$ | 1.40 (via $(R_4,\text{gal})$) | yes |
| $t$ | 1.51 | yes |

Observed $S_1 = 6$. (The bottom quark's covering slot $(R_4,\text{gal})$ and charm's non-coverage are the same structural fact: $R_4$ has integer $j_\text{first}$ at every vacuum, hence $T_3 = -1/2$ throughout, a down-type-only irrep that houses $b$ and excludes the up-type charm.)

**Secondaries, computed identically on real and null spectra.** Logarithms are natural throughout. For each fermion $f$ with at least one compatible slot, the **witness slot** is $s_f^\star = \arg\min_{s:\,C_{f,s}=1} |\ln(m_s/m_f)|$, ties broken by the slot's index in the frozen 24-slot list. Then: $S_2$ = hits at $\times 2$; $S_3$ = hits at $\times 1.5$; $S_4 = \operatorname{median}_f\, |\ln(m_{s_f^\star}/m_f)|$ over the scored fermions that have a compatible slot (charm's witness, or its exclusion if the frozen matrix gives it none, is set by the Step-0 map); $S_5$ = number of distinct witness slots $s_f^\star$.

One scoring variant is also pre-registered: $S_1'$ = hits at $\times 3$ **ignoring compatibility** (proximity to any slot), measuring raw density with no quantum-number skeleton. On the real spectrum $S_1' = 8$: every fermion has some slot within $\times 3$. The three structurally forbidden coverings it counts, and which the compatibility gate removes, are frozen here as witnesses: $(t,\ \text{down-type 197 GeV orphan})$ at 1.14, $(d,\ \text{up-quark slot at } 2.03 \times 10^{-3})$ at 2.30, and $(c,\ \text{tau slot at } 0.734)$ at 1.73. Of these, $d$ and $c$ have no compatible slot within $\times 3$, so the gate drops them ($8 \to 6$); $t$ also hits compatibly via $(R_2,\text{std})$ at 1.51, so its forbidden covering is redundant to the count. A high $S_1'$ null therefore speaks only to raw density and carries no bearing on the gated count; the gates take the real spectrum from $S_1' = 8$ (raw density) to $S_1 = 6$ (compatible coverage) to 5 (assignment).

---

## V. Ensembles, Seed, Single Run

Nulls A, B, C: $M = 100{,}000$ draws each. Null D: exact enumeration (576). RNG seed fixed at **120**. One execution, no re-draws, no post-hoc statistics beyond those named above. Reported per null: the full distribution of $S_1$ (as a count table), its mean and standard deviation, and the one-sided $p = \Pr(S_1 \geq 6)$; the same for the secondaries.

**Numerical and Monte Carlo conventions (committed at freeze).** The RNG is NumPy `Generator(PCG64)` seeded at 120; permutations act on the 24 factors as indexed positions, so equal values remain distinct entries. Full-precision base torsions, $C_\text{geom}$, cosmological inputs, tensor multiplicities, the 24 corrected torsion factors, and the 24 resulting masses are committed as a machine-readable artifact; G1 and G2 compare against it to a named tolerance (the rendered Markdown tables are display checks only, since printed values are rounded and cannot exactly reproduce full-precision products). The Monte Carlo point estimator is $\hat p_A = (k+1)/(M+1)$, which never reports zero, quoted with its binomial standard error. The §VII verdict bands use the point estimator only; the interval is numerical uncertainty and does not trigger a re-run, including when $\hat p_A$ falls near 0.01 or 0.1.

---

## VI. Step 0: Reproduction Gates

The pipeline must pass three deterministic gates before any randomization runs. Failing a gate stops the test and opens a reconciliation item against the source page instead.

- **G1 (masses):** recompute the 24 entry masses from the four frozen factors; match the frozen full-precision artifact (§V) to the named tolerance (the printed §III table is a display check).
- **G2 (torsion algebra):** recompute the 24 torsion values from the 9 base values and the character-table multiplicities $N_{\rho\sigma\tau}$; match the frozen full-precision artifact (§V) to the named tolerance (the printed §II.4 table is a display check; spot-check: $T^2(R_7, \text{std}) = T^2(R_6) \cdot T^2(R_8) = 4.328 \times 0.257 \approx 1.113$ against printed 1.114; the diagonal entries carry the canonical $T^2(R_0) = 1$, e.g. $T^2(R_1, \text{std}) = T^2(R_0) \cdot T^2(R_3) = 1 \times 0.306 = 0.306$).
- **G3 (scorecard):** G3 passes iff the **any-compatible** rule of §IV applied to the real spectrum returns $S_1 = 6$, with $b$ covered by $(R_4,\text{gal})$ at 1.40, $d$ out at 3.22, charm with no compatible slot in range, and $\mu/s$ sharing one slot. The 5-vs-6 gap against the public assignment headline is expected (§I), not a gate failure.

Gate G3 requires the full 24-slot quantum-number map, which the published page prints only for the 10 SM-assigned rows. Completing it for all 24 slots from the stated rules is a Step 0 deliverable, committed as a frozen input artifact at freeze time, and is worth having independently of this test (it completes §IV.4 from 10 rows to 24).

---

## VII. Decision Ledger (pre-named verdicts)

The number itself is the deliverable; the bands only fix the headline language in advance.

- **$p_A \geq 0.1$:** the $\times 3$ comparison is declared uninformative about the torsion dial. Verdict text: "Random torsion reassignment reproduces the published hit rate; the mass table's evidential weight rests on the exact structural outputs (the 24-entry count, the $T_3$ gate (ten correct evaluations), the $\varphi^{-4}$ ratio) and the falsifiable outliers ($\nu_2$, rank 16, the dead zone), not on the $\times 3$ proximity count."
- **$p_A \leq 0.01$:** the torsion values carry fit information beyond density. Verdict text: "Random reassignment does not reproduce the published hit rate; the fine dial is doing measurable work. The comparison remains a comparison, and this does not validate the mechanism."
- **$0.01 < p_A < 0.1$:** inconclusive at the $\times 3$ window; the tighter-window secondaries and Null D govern the discussion, and no headline change is licensed in either direction.

**What this test cannot say.** Nothing about the skeleton it holds fixed: the entry count, the gates, the exact ratios, the elevator exponents, or the neutrino sector. A low $p_A$ does not validate the formula's mechanism; a high $p_A$ does not falsify it. The test measures one thing: whether the $\times 3$ scorecard is evidence about the torsions.

**Propagation.** The verdict sentence is copied, on execution, into: the mass-spectrum §III preamble and headline table, the framework README "What the formula delivers" paragraph, the claim-ledger mass-comparison row, and the working README (Data Tests section, with verdict).

---

## VIII. Protocol

1. **Draft** (this commit): design public, no ensemble run.
2. **Redline:** review pass; adjustments land as visible commits against the draft.
3. **Freeze:** status flips to REGISTERED; the execution script and the Step 0 input artifacts (24-slot quantum-number map, transcribed tables) are committed alongside; tag `mass-null-v1.0`. An archival DOI at the freeze tag is optional, following the SPARC pattern.
4. **Run:** single execution; outputs (distribution tables, p-values) and the filled Results section land in one commit.
5. **Propagate:** the verdict sentence to the four locations above, one commit.

Design and execution are separated by the freeze tag, so the git history is the audit trail: anyone can verify the ensembles were specified before they were drawn.

---

## Results

*Not yet run. This section is filled by the execution commit and by nothing else.*

---

*The ladder is held. The dial is shuffled. The count speaks for itself.*

---

/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /
