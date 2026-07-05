/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /

---

# The Torsion Null Test

**Status:** DESIGN DRAFT. Pre-registration pending: this design is committed before any null ensemble is run, and it is frozen by a designated freeze commit (tagged `mass-null-v1.0`) after review. No randomization has been executed at draft time. The single-run policy below governs execution.

**The claim under audit** ([mass-spectrum.md](../../../../spectrum/files/mass-spectrum.md), §III): with the electron as the scale benchmark, 6 of the remaining 8 charged fermions land within a factor of 3 of a quantum-number-compatible entry (down outside at 3.22, charm without a compatible entry). The page itself states the caveat this test quantifies: "at this entry density a measured mass sits near some entry largely by counting."

**Dependencies:** mass formula and 24-entry table (mass-spectrum.md §II-III), torsion tables (§II.4), Coxeter-Galois gate and stabilizer decompositions (§IV), PDG masses as frozen below.

**Related:** [Claim Ledger](claim-ledger.md), [McKay Propagator Correction](mckay-propagator-correction.md) (the closed correction route; its residual scatter is context for this test), [R from the Mass Spectrum](r-from-mass-spectrum.md).

---

## I. The Question

How much of the 6-of-8 hit rate survives when the Reidemeister torsion values are randomly reassigned across the entry table, holding everything else fixed?

The formula is $m(\rho, \sigma) = \mu_\Lambda \cdot C_{\text{geom}}(\rho) \cdot (\sqrt{\Omega_\Lambda})^{\text{dist}(\rho)/30} \cdot T^2(\rho \otimes \sigma)$. The first three factors set the coarse ladder (thirteen orders of magnitude of placement); the torsion is the fine dial within each shell. This test isolates the dial. It does not test the ladder, the entry count, the quantum-number gates, or the exact ratios; those are held fixed as the skeleton, and their standing is unaffected by any outcome here.

---

## II. What Is Frozen (the skeleton)

| Item | Frozen value / source |
|---|---|
| Overall scale $\mu_\Lambda$ | $\rho_\Lambda^{1/4} \approx 2.25$ meV, from measured $\Lambda$; no refit per draw |
| Seats $C_{\text{geom}}(\rho)$ | the 8 published values (mass-spectrum.md §II.2) |
| Elevator | $(\sqrt{\Omega_\Lambda})^{\text{dist}(\rho)/30}$, $\sqrt{\Omega_\Lambda} = 1.019 \times 10^{61}$, McKay distances as published |
| Quantum numbers per slot | $(T_3, \text{color channels}, Q)$ for all 24 $(\rho, \sigma)$ slots, computed from the published rules (spectral parity, Coxeter-Galois gate, $Z_3$ channels, Gell-Mann-Nishijima); torsion-independent by construction |
| Scoring rule | Section IV below, verbatim |
| Measured masses (GeV) | $u$ $2.16 \times 10^{-3}$, $d$ $4.67 \times 10^{-3}$, $s$ $9.34 \times 10^{-2}$, $c$ $1.27$, $b$ $4.18$, $t$ $172.7$, $\mu$ $1.057 \times 10^{-1}$, $\tau$ $1.777$ (page values; charm from PDG since the page leaves it unassigned) |
| Excluded from scoring | electron (benchmark), the three neutrinos (absolute masses unmeasured) |

The quantum-number map is skeleton because every ingredient of the gates ($j_\text{first}$ parity, the $(13,17)$ Coxeter pair, Galois-fixed content, $Z_3$ channels) is representation theory with no torsion input. Reassigning torsions moves masses; it never moves a slot's kind.

---

## III. What Is Randomized (four nulls)

| Null | Operation | Question it answers |
|---|---|---|
| **A (primary)** | Permute the 24 published $T^2(\rho \otimes \sigma)$ values uniformly across the 24 slots | Do the specific value-to-slot pairings matter at all, or does density plus spread suffice? |
| B | Permute within each vacuum column separately ($8!$ each) | Same, controlling for each vacuum's torsion distribution |
| C | Redraw each $\log T^2$ i.i.d. log-uniform over the observed 24-value range | Does anything beyond the overall spread matter? |
| D | Permute the 9 base torsions $T^2(\tau)$ within spin class ($R_3, R_4, R_5, R_7$ among themselves; $R_1, R_2, R_6, R_8$ among themselves; $R_0$ fixed), then re-derive all 24 via $\log T^2(\rho \otimes \sigma) = \sum_\tau N_{\rho\sigma\tau} \log T^2(\tau)$ | The structure-preserving counterfactual: does it matter which irrep carries which torsion, keeping the tensor algebra intact? |

Null A is primary because it is the direct reading of the published caveat ("a random reassignment of the torsions, holding the quantum-number structure fixed"). Null D is the sharpest secondary: it respects the generative algebra, its ensemble is exactly enumerable ($4! \times 4! = 576$ permutations, no Monte Carlo error), and a divergence between A and D would itself be informative (it would mean the tensor rule, not the base values, carries the fit).

The verdict hangs on Null A alone. B, C, D are reported as texture and cannot rescue or overturn the primary verdict.

---

## IV. The Scoring Rule (frozen)

For each of the 8 scored fermions $f$ with measured mass $m_f$:

1. A slot $(\rho, \sigma)$ is **compatible** with $f$ iff its frozen quantum numbers admit $f$'s kind: matching $T_3$, and a color channel of $f$'s type (singlet for leptons, colored pair for quarks), with $Q$ closed by Gell-Mann-Nishijima.
2. $f$ **hits** iff some compatible slot has $\max(m_f/m_{\text{slot}},\ m_{\text{slot}}/m_f) \leq 3$.
3. Sharing is allowed: two fermions of different kind may hit the same slot through different channels (the published $\mu/s$ case at rank 15).

Primary statistic $S_1$ = number of the 8 that hit. Observed scorecard under this rule, reproducing the page:

| $f$ | best compatible ratio | hit at $\times 3$? |
|---|---|---|
| $u$ | 1.06 | yes |
| $d$ | 3.22 | no |
| $s$ | 1.10 | yes |
| $c$ | none in range | no |
| $\mu$ | 1.02 | yes |
| $\tau$ | 2.42 | yes |
| $b$ | 1.28 | yes |
| $t$ | 1.51 | yes |

Observed $S_1 = 6$.

Named secondaries, computed identically on real and null spectra: $S_2$ = hits at $\times 2$; $S_3$ = hits at $\times 1.5$; $S_4$ = median over the 8 of the log-ratio to the nearest compatible slot; $S_5$ = count of distinct slots used. One scoring variant is also pre-registered: $S_1'$ = hits at $\times 3$ ignoring compatibility (proximity to any slot), which measures raw density with no quantum-number skeleton.

---

## V. Ensembles, Seed, Single Run

Nulls A, B, C: $M = 100{,}000$ draws each. Null D: exact enumeration (576). RNG seed fixed at **120**. One execution, no re-draws, no post-hoc statistics beyond those named above. Reported per null: the full distribution of $S_1$ (as a count table), its mean and standard deviation, and the one-sided $p = \Pr(S_1 \geq 6)$; the same for the secondaries.

---

## VI. Step 0: Reproduction Gates

The pipeline must pass three deterministic gates before any randomization runs. Failing a gate stops the test and opens a reconciliation item against the source page instead.

- **G1 (masses):** recompute the 24 entry masses from the four frozen factors; match the published §III table to displayed precision.
- **G2 (torsion algebra):** recompute the 24 torsion values from the 9 base values and the character-table multiplicities $N_{\rho\sigma\tau}$; match the published §II.4 table (spot-check already passed at draft time: $T^2(R_7, \text{std}) = T^2(R_6) \cdot T^2(R_8) = 4.328 \times 0.257 \approx 1.113$ against printed 1.114).
- **G3 (scorecard):** the frozen scoring rule applied to the real spectrum returns exactly the Section IV table: $S_1 = 6$, down out at 3.22, charm with no compatible slot in range, $\mu/s$ sharing one slot.

Gate G3 requires the full 24-slot quantum-number map, which the published page prints only for the 10 SM-assigned rows. Completing it for all 24 slots from the stated rules is a Step 0 deliverable, committed as a frozen input artifact at freeze time, and is worth having independently of this test (it completes §IV.4 from 10 rows to 24).

---

## VII. Decision Ledger (pre-named verdicts)

The number itself is the deliverable; the bands only fix the headline language in advance.

- **$p_A \geq 0.1$:** the $\times 3$ comparison is declared uninformative about the torsion dial. Verdict text: "Random torsion reassignment reproduces the published hit rate; the mass table's evidential weight rests on the exact structural outputs (the 24-entry count, the 10/10 $T_3$ gate, the $\varphi^{-4}$ ratio) and the falsifiable outliers ($\nu_2$, rank 16, the dead zone), not on the $\times 3$ proximity count."
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
