/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /

---

# Euclid DR1 Scorecard: A Pre-Registered Contender Showdown

The Euclid Data Release 1 is expected in October 2026. Five Mode Identity Theory predictions are locked here, before the data, against four named contenders: flat ΛCDM, w<sub>0</sub>w<sub>a</sub>CDM (CPL), early dark energy (EDE), and MOND / relativistic MOND. Each row is a head-to-head with a stated falsification threshold for MIT. A separate post-DR1 column will be added in a later commit when the data arrive.

The point is not to claim victory in advance. It is to make every contender's position on every observable visible *now*, so the reading of DR1 cannot be retrofit.

---

## :lock: Pre-Registration

| Field | Value |
|---|---|
| Freeze date | 2026-05-20 |
| Reference | Tagged GitHub release of this commit, archived to Zenodo |
| Expected Euclid DR1 release | October 2026 |
| Data products in scope | Cosmology release: spectroscopic BAO (<i>z</i> = 0.9–1.8), photometric weak lensing, high-<i>z</i> stellar mass function. Quick-look products are not bound by this card. |

**Ground rules.**

1. MIT prediction cells, contender prediction cells, and falsification thresholds are immutable after the tagged release. Any edit voids the pre-registration for that row.
2. Post-DR1 results enter via a new column ("DR1 outcome") on a clearly dated later commit. Earlier columns are not edited at that time.
3. Contender predictions cite either a published canonical source or the best-fit posterior from the most recent public data release of that framework. Where a contender is silent on an observable, the cell reads "no prediction" and that silence counts as data.
4. The card adjudicates the five rows independently. A single falsification falsifies that row; the framework as a whole stands or falls on the collective pattern, evaluated in Section VI.

---

## :ringed_planet: Summary Matrix

| # | Observable | MIT prediction | Falsifies MIT if | DR1 outcome |
|---|---|---|---|---|
| I | $\Lambda$ epoch-independence | $\Lambda_\text{obs} = 3/R^2$ is the topological ground eigenvalue; $\Omega_\text{DE}(z)$ flat across all DR1 redshift bins | Reconstructed $\Omega_\text{DE}(z)$ varies at $\geq 2\sigma$ across DR1 bins, or $w_a \neq 0$ at $\geq 2\sigma$ in the CPL fit | *(to be recorded after October 2026)* |
| II | $a_0(z)$ evolution | $a_0(z) = a_0(0) \cdot H(z)/H_0$; $a_0(z{=}2) \approx 3\times$ local | $a_0(z{=}2)$ consistent with $a_0(0)$ at $\geq 2\sigma$ | *(to be recorded after October 2026)* |
| III | $w_\text{eff}(z)$ trajectory and apparent $z_\text{cross}$ | $w_\text{eff}(z) > -1$ at all $z$ (fiducial split); if a CPL crossing is detected, $z_\text{cross} \approx 0.663$ as a template artifact | Fiducial split gives $w_\text{eff}(z) < -1$ at $\geq 2\sigma$; or detected $z_\text{cross}$ outside $[0.50, 0.85]$ at $\geq 2\sigma$ | *(to be recorded after October 2026)* |
| IV | Stellar mass function at $z \gtrsim 10$ | JWST-style massive galaxies persist in Euclid wide-area statistics; reachable with $\varepsilon_\text{SF} \lesssim 1$ under $a_0(z{=}10) \approx 20.5\times$ | Early massive galaxy abundance falls within standard ΛCDM expectations at $\geq 2\sigma$ | *(to be recorded after October 2026)* |
| V | $(1+z)^1$ coefficient in $H^2(z)$ | Negative, magnitude $\|\beta\| < 0.012$ tied to $s_0$ | Coefficient positive at $\geq 2\sigma$, or magnitude inconsistent with fitted $s_0$ | *(to be recorded after October 2026)* |

---

## I. $\Lambda$ Epoch-Independence

This is the framework's deepest claim. $\Lambda$ is not a free parameter fit to the cosmic-expansion data; it is the ground eigenvalue of the Möbius surface embedded in $S^3$, $\lambda_0 = 2/R^2$, with $\Lambda_\text{obs} = 3/R^2$ after the Gauss equation conversion. The value test was passed by Planck ($\Lambda_\text{obs} \cdot \ell_P^2 \approx 2.84 \times 10^{-122}$, predicted 2.9 × 10<sup>−122</sup>). What Euclid DR1 adjudicates is whether $\Lambda$ stays constant across cosmic time, or whether the dark-energy density evolves.

| Framework | Prediction | Source |
|---|---|---|
| **MIT** | $\Lambda_\text{obs}$ is a topological eigenvalue; $\Omega_\text{DE}(z)$ is flat at every DR1 redshift bin | [cosmological-constant.md](cosmological-constant.md), [framework/ground-eigenvalue.md](../../framework/ground-eigenvalue.md) |
| **ΛCDM** | $\Lambda$ constant by construction | Standard Friedmann cosmology |
| **w<sub>0</sub>w<sub>a</sub>CDM** | DESI DR2 best fit prefers $w_a \approx -0.86$, implying time-varying dark energy density; $\Omega_\text{DE}(z)$ not flat | DESI DR2 BAO+SN combined fit |
| **EDE** | Early dark energy component active near $z \sim 3000$; at low $z$, $\Omega_\text{DE}(z)$ approximately flat | Poulin, Smith, Karwal class |
| **MOND / RelMOND** | No prediction | Standard MOND has no cosmology |

*Falsification of MIT.* Direct reconstruction of $\Omega_\text{DE}(z)$ across DR1 redshift bins shows variation at $\geq 2\sigma$; equivalently, the CPL fit returns $w_a \neq 0$ at $\geq 2\sigma$ from the same data combination.

*DR1 outcome:* *(to be recorded after October 2026)*

---

## II. $a_0(z)$ Evolution

Euclid DR1 photometric weak lensing combined with high-<i>z</i> kinematic samples will probe the acceleration scale at $z > 1$ through stacked rotation curve and cluster-scale tests. MIT predicts $a_0$ scales with $H(z)$; standard MOND predicts $a_0$ is universal and constant; ΛCDM has no acceleration scale at all. This is the sharpest head-to-head on the card.

| Framework | Prediction | Source |
|---|---|---|
| **MIT** | $a_0(z) = a_0(0) \cdot H(z)/H_0$; $a_0(z{=}2) \approx 3\times$ local, $a_0(z{=}10) \approx 20.5\times$ | [early-galaxies.md](early-galaxies.md) |
| **ΛCDM** | No acceleration scale; rotation curves explained by dark matter halos of mass-dependent profile | Navarro-Frenk-White, standard structure formation |
| **w<sub>0</sub>w<sub>a</sub>CDM** | No acceleration scale | Same as ΛCDM |
| **EDE** | No acceleration scale | Same as ΛCDM |
| **MOND / RelMOND** | a<sub>0</sub> = const ≈ 1.2 × 10<sup>−10</sup> m/s² at all <i>z</i> | Milgrom (1983); AeST in cosmological regime |

*Falsification of MIT.* DR1 measurement of $a_0$ at $z = 2$ consistent with the local value at $\geq 2\sigma$ falsifies the MIT scaling and is simultaneous vindication of MOND on this row.

*DR1 outcome:* *(to be recorded after October 2026)*

---

## III. $w_\text{eff}(z)$ Trajectory and Apparent $z_\text{cross}$

Euclid DR1 will deliver spectroscopic BAO in four redshift bins between <i>z</i> = 0.9 and 1.8, combined with photometric weak lensing. The headline cosmology result will be reported in the w<sub>0</sub>w<sub>a</sub>CDM (CPL) parameterization. This row carries two linked claims: that the underlying $w(z)$ never crosses $w = -1$, and that any apparent crossing in CPL fits is a template-projection artifact concentrated near $z \approx 0.663$.

| Framework | Prediction | Source |
|---|---|---|
| **MIT** | $w_\text{eff}(z) > -1$ at all $z$ in the fiducial-matter split; no real crossing | [dark-energy.md](dark-energy.md) §III (proof) |
| **ΛCDM** | $w(z) = -1$ exactly, no crossing possible | Standard Friedmann cosmology |
| **w<sub>0</sub>w<sub>a</sub>CDM** | Parameterization permits crossing; DESI DR2 best fit ($w_0 \approx -0.75$, $w_a \approx -0.86$) implies a crossing near <i>z</i> ≈ 0.4–0.5 | DESI DR2 BAO+SN combined fit |
| **EDE** | $w(z) \approx -1$ at Euclid DR1 redshifts; the EDE component is active near $z \sim 3000$ | Poulin, Smith, Karwal class |
| **MOND / RelMOND** | No prediction | Standard MOND has no cosmology; AeST does not constrain $w(z)$ at this precision |

**If a crossing is detected.** MIT's sub-claim is that any CPL crossing is a template-projection artifact of a non-phantom truth, located near $z \approx 0.663$. ΛCDM predicts no crossing exists. w<sub>0</sub>w<sub>a</sub>CDM does not predict a specific $z_\text{cross}$ value; its current best fit puts the crossing near <i>z</i> ≈ 0.4–0.5. EDE and MOND give no late-time crossing.

*Falsification of MIT.* Fiducial split of the DR1 best-fit $H(z)$ gives $w_\text{eff}(z) < -1$ at $\geq 2\sigma$ for any $z$ in the DR1 range; or a CPL crossing is detected at $z_\text{cross}$ outside $[0.50, 0.85]$ at $\geq 2\sigma$.

*DR1 outcome:* *(to be recorded after October 2026)*

---

## IV. Stellar Mass Function at $z \gtrsim 10$

Euclid's wide-area photometric survey will dramatically extend the JWST-discovered population of high-redshift massive galaxies, replacing small-area surprise with cosmologically significant statistics. The question this row asks is whether the abundance of $M_{*} \sim 10^{10}\ M_\odot$ galaxies at $z \gtrsim 10$ is what standard structure formation expects or what JWST already suggests it is not.

| Framework | Prediction | Source |
|---|---|---|
| **MIT** | Wide-area statistics confirm JWST-class abundance; reachable under standard $\varepsilon_\text{SF} \lesssim 1$ with $a_0(z{=}10) \approx 20.5\times$ local | [early-galaxies.md](early-galaxies.md) |
| **ΛCDM** | Stellar mass function at $z \gtrsim 10$ within standard halo-abundance forecasts; the JWST tension is anomalous and resolves with better selection / dust corrections | Standard structure formation |
| **w<sub>0</sub>w<sub>a</sub>CDM** | Same as ΛCDM (dark energy modifications do not change early structure growth) | Standard structure formation |
| **EDE** | Marginal enhancement of early structure from shifted matter-radiation equality, insufficient to reach JWST levels | Klypin, Murray, Macciò calculations |
| **MOND / RelMOND** | Enhanced gravity at low accelerations qualitatively eases early structure formation; no clean quantitative mass-function prediction available | Sanders, McGaugh review |

*Falsification of MIT.* Euclid wide-area abundance of $M_{*} \sim 10^{10}\ M_\odot$ galaxies at $z \gtrsim 10$ falls within standard ΛCDM forecasts at $\geq 2\sigma$, indicating the JWST tension was a selection or systematics artifact.

*DR1 outcome:* *(to be recorded after October 2026)*

---

## V. $(1+z)^1$ Coefficient in $H^2(z)$

This is the distinctive signature row. The phase-clock expansion produces a $(1+z)^1$ term in $H^2(z)$ that is absent from every canonical FLRW component (radiation, matter, curvature, $\Lambda$). The coefficient is strictly negative for $s_0 > 0$ and tied to the fitted phase parameter. No other model on this card predicts this term at all.

| Framework | Prediction | Source |
|---|---|---|
| **MIT** | Negative coefficient $-\beta$ with $\|\beta\| < 0.012$ at 95% CL from current data; magnitude tied to $s_0$ | [dark-energy.md](dark-energy.md) §II, §VI |
| **ΛCDM** | Exactly zero (Friedmann has no $(1+z)^1$ component) | Standard Friedmann cosmology |
| **w<sub>0</sub>w<sub>a</sub>CDM** | Approximately zero; CPL has no isolated linear-in-<i>z</i> coefficient in $H^2$ | Linder (2003) parameterization |
| **EDE** | Approximately zero at Euclid DR1 redshifts | Poulin et al. class |
| **MOND / RelMOND** | No prediction | Same as above |

*Falsification of MIT.* DR1 BAO precision (forecast 1–2% per bin) is marginal for direct detection of this term at the current $s_0$ bound. The falsification threshold is a positive coefficient detected at $\geq 2\sigma$, or a magnitude inconsistent with the fitted $s_0$ from the same data combination.

*DR1 outcome:* *(to be recorded after October 2026)*

---

## VI. How to Read the Result

The five rows are independent observables, not a single combined likelihood. Each row's falsification threshold is a hard statement about MIT, evaluated row by row.

The honest readings of post-DR1 patterns are:

* **All five MIT cells survive.** No contender clears more than two rows without "no prediction" gaps. The pre-registration becomes citable evidence that MIT made specific, falsifiable claims and the data did not falsify them.
* **One row falsifies, four survive.** That row is closed. The framework continues on the remaining structure, with the falsified row triggering a derivation review of the failing prediction.
* **Two or more rows falsify.** The phase-clock and edge-mode structure that connects these rows is no longer holding the predictions together; the underlying postulate stack needs reexamination.
* **No row clearly resolves.** DR1 precision is insufficient to falsify or confirm; predictions roll forward to DR2 (~2028) or LiteBIRD / CMB-S4 / next-generation BAO without modification.

The MOND column is silent on four of five rows by construction. That silence is itself a statement: standard MOND has no late-time cosmology and offers no contender position on $\Lambda$, $w(z)$, the $(1+z)^1$ signature, or the high-<i>z</i> stellar mass function. The second row, $a_0(z)$, is the head-to-head where MOND and MIT disagree sharply on whether the acceleration scale evolves.

The ΛCDM column is the null hypothesis. It carries definite predictions on every row, and it agrees with MIT on the headline question of $\Lambda$ constancy. The two diverge on the dynamics (rows II–V), where MIT predicts specific shapes and signatures and ΛCDM predicts none of them.

---

## VII. Full Scorecard

The compact view. Theories down the rows, the five observables across the columns, with a final column for the per-theory Euclid result once DR1 lands.

|  | Λ | a₀(z) | w(z) | SMF z ≳ 10 | (1+z)¹ in H² | Euclid result |
|---|---|---|---|---|---|---|
| **MIT** | $\Lambda = 3/R^2$ | $a_0 \propto H(z)$; ≈ 3× at $z = 2$ | $w > -1$; $z_\text{cross} \approx 0.663$ | JWST-class persists | negative, \|β\| < 0.012 | — |
| **ΛCDM** | $\Lambda$ | no $a_0$ | $w = -1$ exact | within forecasts | zero | — |
| **w<sub>0</sub>w<sub>a</sub>CDM** | $\Omega_\text{DE}(z)$ varies | no $a_0$ | crossing near $z$ ≈ 0.4–0.5 | within forecasts | ≈ zero | — |
| **EDE** | $\Lambda$ at low $z$ | no $a_0$ | $w \approx -1$ at DR1 $z$ | marginal help | ≈ zero | — |
| **MOND** | — | $a_0$ const ≈ 1.2 × 10<sup>−10</sup> m/s² | — | qualitative help | — | — |

**Glyph legend.** ✓ prediction satisfied. ✗ falsified. ~ ambiguous (within DR1 noise). — no prediction.

Post-October 2026: each prediction cell gets a trailing glyph indicating its DR1 status; the **Euclid result** column gets the per-theory tally.

---

*The scorecard does not predict victory. It locks the bets and prints the date.*

---

/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /
