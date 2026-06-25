/ **[`main`](../../../../../README.md)** / **[`framework`](../../../../framework/)** / **[`working`](../)** / **[`cosmos`](../../../../cosmos/)** / **[`spectrum`](../../../../spectrum/)** /

---

# The Temporal Budget Identity

[![The Phantom Mirage](https://img.youtube.com/vi/23IxzJDo3pM/mqdefault.jpg)](https://www.youtube.com/watch?v=23IxzJDo3pM)

Working notes on the temporal budget $\Psi^2 + S^2 = 1$, the Waltz clock $d\tau/dt = S^{1/2}$, and the Pantheon+ fit that recovers $\Omega_m$ as output.

**Status:** Established at model level. With $S = \sin(t/2)$ and the Waltz clock, Model D+Λ reproduces the Pantheon+ distance ladder at $\Delta\chi^2 = +0.6$ relative to flat ΛCDM on 1701 SNe Ia with full covariance, using two free parameters ($s_0$, $H_0$) — the same count as ΛCDM. $\Omega_m = 0.315$ is recovered from the $(1+z)^3$ coefficient. First-principles derivation of the clock exponent from $S^1 = \partial(\text{Möbius}) \hookrightarrow S^3$ without invoking GR remains open.

**Dependencies:** Sector $\mathcal{A}$ spatial budget $u_0^2 + J^2 = 1$; $S^1 = \partial(\text{Möbius}) \hookrightarrow S^3$; Pantheon+ and DESI DR2 BAO (Λcos paper).

**Related:** [The Budget Map](budget-map.md), [Phantom Crossing as Template Bias](phantom-crossing-template-artifact.md), [The Waltz](../../../../spectrum/files/the-waltz.md).

**Update (May 2026, Λcos paper).** Joint fit to Pantheon+ (1701 SNe Ia) and DESI DR2 BAO (13 data points) tightens the constraint to $\Delta\chi^2 = +0.11$ at equal parameter count, with $s_0 < 0.19$ (95% CL, flat prior). The best-fit sits at the ΛCDM boundary ($s_0 = 0.001$); the posterior median is 0.076. The Pantheon+-only value $s_0 = 0.389$ remains within the Pantheon+ posterior but is disfavored by the BAO data. The prediction ledger (§XI) now carries both values. 

The paper also demonstrates that standard two-parameter $w(z)$ templates (CPL, BA, JBP) produce apparent phantom crossings when fitted to non-phantom Λcos distances, establishing template bias as a structural effect. Clock-exponent selection is empirically validated: integer alternatives $n = 0, -1, +1$ give $\Delta\chi^2 > 60$ relative to ΛCDM (Appendix A of the Λcos paper). A growth-level consistency check against DESI DR1 ShapeFit+BAO $f\sigma_{s8}$ at six tracer effective redshifts gives $\Delta\chi^2_\text{RSD} < 0.3$ relative to flat ΛCDM across the data-allowed parameter range.

---

## I. The Budget Identity

The temporal budget identity sits in structural parallel to the spatial budget $u_0^2 + J^2 = 1$ derived for the Möbius wavefunction. Its temporal twin:

$$\Psi^2 + S^2 = 1, \quad \Psi = \cos(t/2), \quad S = \sin(t/2)$$

$\Psi$ is the cosmic standing wave. $S$ is the **modal realization amplitude** — the bounded fraction of the wave expressed as resolvable modes at phase $t$. The sum closes by construction ($\sin^2 + \cos^2 = 1$), but its content is physical: the realized-mode content and the standing-wave content exhaust the total at every phase.

**Complex phase form.** The budget admits a single complex exponential:

$$\Psi + iS = \cos(t/2) + i\sin(t/2) = e^{it/2}$$

This is a bookkeeping representation of the two real budget components, not an additional complex field. The budget identity is $|e^{it/2}|^2 = 1$. The temporal evolution of the universe is rotation on the unit circle in the complex plane. $\Psi$ (standing wave) is the real part; $S$ (modal realization) is the imaginary part. The half-angle $t/2$ in the exponent is the Möbius signature: two traversals of the boundary restore the sign, giving the $4\pi$ period.

Structural milestones read as positions on the unit circle:

| Phase $t$ | $e^{it/2}$ | Position | Physical epoch |
|---|---|---|---|
| 0 | 1 | Real axis, positive | Pure wave. No realization. Formal hot dense limit. |
| $\pi$ | $i$ | Imaginary axis | First zero crossing. $\Psi = 0$, $S = 1$. Full realization. |
| $2\pi$ | $-1$ | Real axis, negative | Turnaround. $\Psi = -1$. |
| $3\pi$ | $-i$ | Imaginary axis | Second zero crossing. |
| $4\pi$ | 1 | Real axis, positive | Full cycle. Return. |

The present epoch sits partway around the first quadrant ($0 < t_\text{now} < \pi$), between pure wave and full realization.

Bounded realization ($S \leq 1$) is the key feature. Nothing in a standard FLRW decomposition has this constraint. Its fingerprint will appear as a forbidden term (§V).

**What the budget produces alone.** With $H$ defined as $(1/S)(dS/dt)$ (phase-time derivative), the budget gives $H^2 = (1-S^2)/(4S^2)$, which scales as $(1+z)^2 - \text{const}$. This is curvature-like, not matter-like. The $(1+z)^3$ matter scaling requires the Waltz clock (§II), which converts phase time to proper time and contributes the additional $S^{-1}$ factor that turns $S^{-2}$ into $S^{-3}$. The budget identity sets the bounded structure; the clock sets the dimensional content.

### I.A Cooling, in budget terms

Cooling and the redshift it follows from have their own note now: [Redshift and Cooling](redshift-and-cooling.md). In budget terms the content is that the transfer $\Psi^2 \to S^2$ earns the cooling without an exterior: at early phase the weight sits in the standing wave ($\Psi^2 \approx 1$), and as the phase advances it moves into the realized modes, photon energies scaling by $S(t_\text{emit})/S(t_\text{obs}) = 1/(1+z)$, so a blackbody stays a blackbody at $T \propto 1/S$. This is ESTABLISHED as a kinematic equivalence with the FLRW thermal law. The distance side is the clock (§II), and the entropy that rides along is a separate reading ([Entropy as Realization Budget](entropy-as-realization-budget.md)).

---

## II. The Waltz Clock

The relationship between conformal time $\tau$ and the budget phase $t$ is:

$$\frac{dt}{d\tau} = S^{-1/2} \quad \text{together with the budget identity gives} \quad H \propto S^{-3/2}$$

The exponent is not fitted. It is forced by two structural facts.

| Factor | Contribution | Origin |
|---|---|---|
| Matter dilution in 3 spatial dimensions | $S^{-3}$ on energy density | three spatial dimensions |
| Friedmann $H^2 \to H$ | square root on the rate | the Friedmann square root |

Their ratio is 3/2, appearing as the exponent on $H$ and as -1/2 on the clock ($1 - 3/2 = -1/2$). It is numerically the same 3/2 that relates $\Lambda_\text{obs} = (3/2)\Lambda_\text{top}$, but not yet shown to be the same object: that conversion's 3/2 is (isotropic Ricci trace)/(de Sitter normalization), derived-times-imported ([cosmological constant](../../../../cosmos/files/cosmological-constant.md) §IV), while this one is (matter dilution)/(Friedmann square root). Tying both 3's to the $Z_3$ face stabilizer and both 2's to the edge stabilizer is a MOTIVATED correspondence, not a derived identity.

Alternative integer-power clocks ($S^0$, $S^{-1}$, $S^{+1}$ — Models A, B, C) produce $(1+z)^0$, $(1+z)^2$, $(1+z)^1$ in $H^2$. Only the 3/2 clock gives $(1+z)^3$, which is what matter-era Friedmann scaling requires. Data closes the selection; structure forces it.

**Empirical validation (Λcos paper, 2026).** All three integer alternatives were fitted to the joint Pantheon+ + DESI DR2 BAO dataset. Results:

| Model | $n$ | High-<i>z</i> scaling | $\Delta\chi^2$ vs ΛCDM |
|---|---|---|---|
| A (proper time) | 0 | $(1+z)^1$ | +218.7 |
| B (conformal) | -1 | $(1+z)^2$ | +1821.9 |
| C (symmetric) | +1 | $(1+z)^0$ | +7276.6 |
| D (Λcos / budget) | -1/2 | $(1+z)^{3/2}$ | +0.11 |

The selection is decisive. Only $n = -1/2$ is viable.

---

## III. Model D+Λ and Pantheon+

The Hubble parameter derived from the budget identity with the Waltz clock and topology-fixed Λ:

$$H^2(z) = H_0^2\left[\frac{1-\Omega_\Lambda}{1-s_0^2}(1+z)^3 - \frac{(1-\Omega_\Lambda) s_0^2}{1-s_0^2}(1+z) + \Omega_\Lambda\right]$$

Two free parameters: $s_0 = \sin(t_\text{now}/2)$ and $H_0$. Same count as ΛCDM ($\Omega_m$, $H_0$). $\Omega_\Lambda = 0.685$ is input from topology (Möbius eigenvalue), not fitted.

| Quantity | Pantheon+ only | Joint SN+BAO (Λcos paper) | Source |
|---|---|---|---|
| $s_0$ (best-fit) | 0.389 | 0.001 (boundary) | Fit |
| $s_0$ (posterior median) | — | 0.076 | Fit |
| $s_0$ (95% CL) | — | < 0.19 | Flat prior |
| $t_\text{now}$ (budget phase) | 0.80 rad | < 0.38 rad (95%) | From $s_0$ |
| $\Omega_m$ (recovered) | 0.315 | 0.315 | $(1+z)^3$ coefficient |
| $(1+z)^1$ coefficient | −0.056 | > −0.012 (95%) | Budget identity |
| $H_0 r_d$ (km/s) | — | 10008 [9972, 10040] | Fit |
| $\Delta\chi^2$ vs flat ΛCDM | +0.6 | +0.11 | 1701 SNe + 13 BAO |

The joint fit is driven by BAO data at $z > 1$ which constrain the differential Hubble rate, breaking the Pantheon+ distance-integral degeneracy. The Pantheon+-only value $s_0 = 0.389$ remains within the SN posterior alone but is pulled toward zero by the BAO sector. The 95% CL is prior-sensitive (ranging from 0.12 to 0.21 across flat, $s_0^2$-flat, and log-flat priors) but data-driven in character: all priors yield $s_0 \ll 1$.

Pure budget without $\Lambda$ gives $q_0 = +0.5$ (deceleration). Data requires $q_0 \approx -0.55$ (acceleration). $\Lambda$ from topology is necessary; it is also already derived elsewhere in the framework (not a parameter introduced here).

**$\Omega_\Lambda$ sensitivity (Λcos paper).** With $\Omega_\Lambda$ fixed at 0.685, the SN+BAO fit gives $\Delta\chi^2 = +0.11$. The constraint varies smoothly across $\Omega_\Lambda = 0.68-0.715$, with the best $\Delta\chi^2$ near 0.69. Adding compressed Planck distance priors shifts the preferred $\Omega_\Lambda$ to $\sim 0.714$ (in both Λcos and non-flat ΛCDM); with $\Omega_\Lambda$ freed, Λcos and non-flat ΛCDM are indistinguishable ($\Delta\chi^2 = +0.28$). The shift is a background-distance consistency issue in the compressed-prior setup, driven by the BAO sector, and applies to both models. The topology-fixed value $\Omega_\Lambda = 0.685$ is stable for SN+BAO; the CMB tension merits further study with the full Planck likelihood.

---

## IV. $\Omega_m$ as Output

$\Omega_m = 0.315$ is not fitted by the SN+BAO likelihood in this construction; it is inherited from the topology-fixed $\Omega_\Lambda = 0.685$ through flat closure. What the budget dressing changes is the effective $(1+z)^3$ coefficient, not the underlying matter fraction. Two readings of the same quantity:

$$\Omega_m^\text{underlying} = 1 - \Omega_\Lambda = 0.315 \quad \text{(topology)}$$

$$\Omega_m^\text{effective} = \frac{1-\Omega_\Lambda}{1-s_0^2} \quad \text{(what the $(1+z)^3$ coefficient reads)}$$

At best-fit $s_0 = 0.389$, the effective reading is 0.372; the underlying value is 0.315. The Planck value is recovered after removing the budget-identity dressing. The last borrowed cosmological parameter falls out as derived.

**Note on the joint constraint.** At $s_0 < 0.19$ (95% CL from SN+BAO), the dressing factor $1/(1-s_0^2)$ is at most 1.037, so $\Omega_m^\text{effective} < 0.327$. The dressing becomes small enough that the effective and underlying readings are nearly identical. This is consistent: the BAO data pull $s_0$ toward zero, which is the ΛCDM limit where no dressing exists. The $\Omega_m$-as-output result is structurally intact but observationally marginal at the current joint constraint.

---

## V. The $(1+z)^1$ Signature

A negative $(1+z)^1$ term at $\sim 4\%$ of $H^2$ appears in the expansion. It has no source in any standard FLRW component:

| Component | Redshift scaling |
|---|---|
| Matter | $(1+z)^3$ |
| Radiation | $(1+z)^4$ |
| Curvature | $(1+z)^2$ |
| Dark energy ($w=-1$) | $(1+z)^0$ |
| Phantom ($w<-1$) | $(1+z)^n$, $n<0$ |

None gives a $(1+z)^1$. The term is the fingerprint of bounded realization: $\sin(t/2) \leq 1$ at the boundary introduces a lower-order correction that a monotonic density cannot reproduce.

Currently below Pantheon+ detection threshold. Future surveys (Euclid, Roman, LSST) are expected to reach percent-level $H(z)$ precision. The sign and approximate magnitude of the term are prediction.

**Updated magnitude.** At $s_0 = 0.389$ (Pantheon+-only), $|\beta| = 0.056$, contributing $\sim 4\%$ of $H^2$ at $z = 1$. At $s_0 < 0.19$ (joint SN+BAO 95% CL), $|\beta| < 0.012$, contributing $< 0.8\%$ of $H^2$ at $z = 1$. The Λcos paper notes this is below DESI DR2 per-bin precision ($\sim 2-3\%$) but potentially within reach of next-generation surveys projected to reach sub-percent per-bin precision (Euclid DR2, DESI full-survey, MegaMapper-class), where the $(1+z)^1$ signature approaches per-bin detectability for $s_0$ in the upper portion of the data-allowed range with correlated bins improving aggregate sensitivity.

---

## VI. The $\Psi$ Numerator

The clock rate is:

$$\frac{dt}{d\tau} = S^{-1/2}$$

The $\Psi$ factor enters through the phase derivative:

$$\frac{dS}{dt} = \frac{1}{2}\cos(t/2) = \frac{\Psi}{2}$$

Therefore:

$$\frac{1}{S}\frac{dS}{d\tau} = \frac{\Psi}{2S^{3/2}}$$

and:

$$H^2 \propto \frac{\Psi^2}{S^3} = \frac{1 - S^2}{S^3}$$

This $\Psi^2 = 1 - S^2$ numerator is what produces the negative $(1+z)^1$ correction. Without it, the clock gives pure matter scaling. The $(1+z)^1$ term is therefore not produced by an extra denominator in the clock; it is produced by the bounded budget factor already present in $dS/dt$.

Structural reading: face ($Z_3$) contributes to matter dilution, edge ($Z_2$) contributes to the Friedmann square root, and the vertex stabilizer ($Z_5$) is the candidate source of the $\Psi$ numerator's role in the temporal correction. The shape is visible; the derivation is unwalked. If it closes, the vertex's role in the temporal budget becomes the three-stabilizer completion of the 3/2 accounting.

---

## VII. Derivation Chain

$$\begin{aligned}
\Psi = \cos(t/2) & \quad \text{[AXIOM]}\\
\Psi^2 + S^2 = 1 & \quad \text{[PROPOSED; consistent with data]}\\
S = \sin(t/2) & \quad \text{[FOLLOWS]}\\
dt/d\tau = S^{-1/2} & \quad \text{[FORCED by $S^3$ dimensionality $+$ GR; empirically validated, integer alternatives ruled out at $\Delta\chi^2 > 60$]}\\
H^2(z) \text{ from budget} + \Lambda & \quad \text{[DERIVED]}\\
\text{Fit to Pantheon+} & \quad \text{[ESTABLISHED: } \Delta\chi^2 = +0.6\text{]}\\
\text{Joint fit to SN+BAO} & \quad \text{[ESTABLISHED: } \Delta\chi^2 = +0.11, \; s_0 < 0.19 \text{ (95\% CL)]}\\
\Omega_m = 0.315 \text{ recovered} & \quad \text{[ESTABLISHED: from fit coefficient]}\\
\text{Template bias demonstrated} & \quad \text{[ESTABLISHED: CPL/BA/JBP produce phantom crossings from non-phantom input]}
\end{aligned}$$

Steps beyond this point remain open:

- Derive the clock exponent -1/2 from the postulate without invoking GR
- Derive $t_\text{now}$ (equivalently $s_0$) from topology without fitting Pantheon+
- Friedmann as output rather than input
- $\Omega_m$ from topology alone

---

## VIII. Two Phase Parameters

Two parameterizations of the same phase on $S^1$ are in use:

| Parameter | Definition | Value today |
|---|---|---|
| $\Phi$ (engine phase) | $\Phi = 4\pi T/T_\text{cycle}$, linear in proper time | $\Phi_\text{now} = 5.22$ rad ($4\pi\,(13.8/33) = 5.26$, from the observed age; under re-derivation) |
| $t$ (budget phase) | Nonlinear in proper time; argument of $\cos(t/2)$ | $t_\text{now} < 0.38$ rad (joint; 0.80 SN-only) |

They refer to the same underlying phase advance, but the two values as stated remain an open discrepancy, and it traces to one substituted number: the proper-time age fed into $\Phi_\text{now}$. The engine phase is linear in that age, $\Phi_\text{now} = 4\pi\,(T_\text{now}/33\,\text{Gyr})$. Inverting the clock from the measured $t_\text{now} < 0.38$ rad gives $T_\text{now} \lesssim 0.79$ Gyr (the $\Phi \lesssim 0.3$ rad below, in age units). But $\Phi_\text{now} = 5.22$ used the observed ~13.8 Gyr instead: $4\pi\,(13.8/33) = 5.26$, ~0.7% above the stated 5.22, so it drifts even from its own origin. The fold is the same and correctly linear both times; only the age moved, $\lesssim 0.79$ against 13.8 Gyr, a factor of ~17. That single borrow has two bad faces: 13.8 Gyr is a ΛCDM number, and ΛCDM has neither a turnaround nor a $4\pi$ period, so it imports an age from a model lacking the cyclic structure the engine phase assumes; and it skips inverting the clock from $t_\text{now}$. One substitution, two faces, not two errors.

Run through the clock, the two values cannot share one trajectory. Forward, $t_\text{now} < 0.38$ rad maps to $\Phi \lesssim 0.3$ rad; inverse, $\Phi = 5.22$ rad requires $t \approx 2.8$ rad, i.e. $s_0 = \sin(t/2) \approx 0.98$, far above even the loosest Pantheon+-only $s_0 = 0.389$. The direction is forced: $\Phi$ is linear in proper time while $t$ advances through a clock that accrues proper time slowly when $S$ is small, so the engine fraction stays below the budget fraction, and the clock holds $\Phi$ below the 41.5% that 5.22 represents.

This carries a specific quantified discrepancy, and $\Phi_\text{now} = 5.22$ is the value to re-derive: the proper-time age it folds in has to come from inside the cyclic model, the age obtained by inverting the clock from the measured $t_\text{now}$, rather than the observed ΛCDM 13.8 Gyr. The linear fold was always correct; the substituted age is the error. Until then $t(\Phi)$ stays open and the two "now" values remain an open discrepancy.

---

## IX. Connection to Other MIT Results

| Connection | Content |
|---|---|
| [Spatial budget $u_0^2 + J^2 = 1$](../../../../cosmos/files/cosmological-constant.md) | The temporal budget is its twin. Spatial budget sets $\Lambda_\text{obs} = (3/2)\Lambda_\text{top}$; temporal budget sets the Waltz clock. The same numerical 3/2 sits in both; whether it is the same geometric ratio is open. |
| [Sector $\mathcal{A}$ eigenvalue](../../bedrock/files/first-eigenvalue.md) | Fixes $\Lambda_\text{top}$, hence $\Omega_\Lambda = 0.685$ as input to the fit. |
| [Hubble tension](../../../../cosmos/files/hubble-tension.md) | The Waltz clock $H \propto S^{-3/2}$ is the mechanism underlying the early/late discrete snap. |
| [Energy as Resolution Amplitude](energy-as-resolution-amplitude.md) | Same sampling-operation picture. Redshift as phase ratio + energy as resolution amplitude should unify into a single account. Open. |
| [Λcos paper](https://github.com/dmobius3/lambda-cos) | Presents Model D+Λ as a standalone phenomenological model ("Λcos") without framework language. Joint SN+BAO constraint: $s_0 < 0.19$ (95% CL). Template bias demonstrated: CPL/BA/JBP produce phantom crossings from non-phantom input. Clock exponent empirically validated. Linear-growth consistency check against DESI DR1 ShapeFit+BAO at six tracer effective redshifts gives $\Delta\chi^2_\text{RSD} < 0.3$ relative to flat ΛCDM. First quantitative constraint on the budget phase parameter from joint background and growth data. |

---

## X. Open Questions

| Item | Priority | Notes |
|---|---|---|
| Clock from postulate | High | The exponent -1/2 is forced by consistency with budget + GR + $S^3$ dimensionality. Integer alternatives empirically ruled out at $\Delta\chi^2 > 60$ (Λcos paper). A derivation from $S^1 = \partial(\text{Möbius}) \hookrightarrow S^3$ that does not invoke GR would promote this from ESTABLISHED to DERIVED. |
| $t_\text{now}$ from topology | High | The Pantheon+-only fit gives $t_\text{now} = 0.80$ rad; the joint SN+BAO constraint gives $t_\text{now} < 0.38$ rad (95% CL). The BAO data pull the clock toward zero (the ΛCDM limit). Deriving $t_\text{now}$ from topology alone, rather than from data, closes the program, but the empirical value is now uncertain by a factor of $\sim 2$ depending on dataset combination. |
| $\Phi \leftrightarrow t$ relation | High | The two phase parameters must be reconciled. |
| Vertex-<i>Z<sub>5</sub></i> role in bounded-budget correction | Medium | If the $(1+z)^1$ term derives from $Z_5$ in the temporal budget, the face/edge/vertex completion of the 3/2 accounting becomes explicit. |
| Redshift mechanism (fully derived) | Medium | Model D+Λ gives the right distances. The phase-ratio picture on $S^1$ is understood in outline; the full derivation chain from postulate to observed $H(z)$ is partially walked. |
| $(1+z)^1$ detection threshold | Medium (promoted) | At $s_0 < 0.19$, the signature is $< 0.8\%$ of $H^2$ at $z = 1$. Below DESI DR2 per-bin precision ($\sim 2-3\%$). Discriminating regime requires sub-percent per-bin precision: Euclid DR2, DESI full-survey, MegaMapper-class. Signature approaches per-bin detectability for $s_0$ in the upper portion of the data-allowed range; correlated bins improve aggregate sensitivity. |
| SN vs BAO tension on $s_0$ | Medium (new) | Pantheon+ alone accommodates $s_0 \sim 0.4$; BAO pulls toward zero. Whether this reflects a real tension (different aspects of the $H(z)$ trajectory constraining $s_0$ differently) or simply the expected tightening from complementary data needs investigation. The $\Omega_\Lambda$ sensitivity analysis (Λcos paper V.D) shows the constraint varies smoothly with $\Omega_\Lambda$, with the best $\Delta\chi^2$ near $\Omega_\Lambda = 0.69$. |
| What $s_0 \to 0$ would cost | Medium (structural) | At $s_0 = 0$ the phase clock reduces to a conventional scale factor and the budget-specific distance-redshift observables (the $(1+z)^1$ term, the larger-<i>H(z)</i> prediction) go degenerate with flat ΛCDM at current precision: the budget layer becomes a reinterpretation rather than a distinguishable theory. This is the cost of one layer, not the framework: the topology, the mass formula, the gauge couplings, three generations, and $\Lambda = 3/R^2$ do not depend on $s_0$. Honest framing: MIT's distinctive distance-redshift content is staked on $s_0 > 0$; its particle and topology content is not. Data permits but does not require $s_0 > 0$; Euclid DR1 moves it. |

---

## XI. Euclid DR1 Prediction Ledger

Model D+Λ predictions depend on $s_0$, which is now constrained differently by Pantheon+-only ($s_0 = 0.389$) and joint SN+BAO ($s_0 < 0.19$ at 95% CL). The ledger carries both values. If Euclid DR1 BAO confirms the tighter constraint, the model's observable departures from ΛCDM shrink to marginal levels at DR1 precision, and the discriminating test moves to DR2 and next-generation surveys. If Euclid opens room for larger $s_0$, the Pantheon+-only predictions remain live.

### A. Hubble rate $H(z)/H_0$ from BAO

At $s_0 = 0.389$: $\quad H^2/H_0^2 = 0.371(1+z)^3 - 0.056(1+z) + 0.685$

At $s_0 = 0.19$: $\quad H^2/H_0^2 = 0.327(1+z)^3 - 0.012(1+z) + 0.685$

| $z$ | MIT ($s_0 = 0.389$) | MIT ($s_0 = 0.19$) | ΛCDM ($\Omega_m = 0.315$) | Δ (high) | Δ (low) |
|---|---|---|---|---|---|
| 0.3 | 1.195 | 1.178 | 1.173 | +1.8% | +0.4% |
| 0.5 | 1.361 | 1.331 | 1.322 | +3.0% | +0.6% |
| 0.7 | 1.553 | 1.507 | 1.494 | +4.0% | +0.8% |
| 1.0 | 1.882 | 1.810 | 1.790 | +5.1% | +1.1% |
| 1.5 | 2.519 | 2.400 | 2.368 | +6.4% | +1.4% |
| 2.0 | 3.246 | 3.078 | 3.032 | +7.1% | +1.5% |

**Signed direction.** $H_\text{MIT}(z) > H_\text{ΛCDM}(z)$ at all $z > 0$ for any $s_0 > 0$, with the gap growing monotonically with redshift. The prediction is not "different from ΛCDM" — it is **larger than ΛCDM's $H(z)$ by a specific, computable amount**. The $(1+z)^1$ coefficient is forced negative by the budget identity, not a free sign; the leading driver of the larger-<i>H(z)</i> prediction is the budget-dressed $(1+z)^3$ coefficient, with the negative $(1+z)^1$ a subleading partial compensation.

**Discriminating bins.** At $s_0 = 0.389$, the MIT gap exceeds 5% at $z > 1$ — comfortably above Euclid DR1 per-bin sensitivity ($\sim 1-2\%$). At $s_0 = 0.19$, the gap is $\sim 1-1.5\%$ at $z > 1$ — marginal for DR1, requiring correlated multi-bin analysis. The $z > 1$ bins carry the most discriminating power in both cases.

**Context.** Pantheon+ constrains $\int dz/H(z)$, not $H(z)$ directly — so MIT and ΛCDM agree on distance modulus while diverging on the differential Hubble rate. Euclid BAO reads the differential rate. This is where the Pantheon+ degeneracy breaks. The joint SN+BAO fit in the Λcos paper already demonstrates this: BAO data are what pull $s_0$ toward zero.

### B. The $(1+z)^1$ signature

| Quantity | MIT ($s_0 = 0.389$) | MIT ($s_0 = 0.19$) | ΛCDM |
|---|---|---|---|
| coefficient of $(1+z)$ in $H^2/H_0^2$ | −0.056 | −0.012 | 0 |
| fractional contribution at $z=1$ | −3.2% | −0.7% | 0 |

No standard FLRW component produces a $(1+z)^1$ term (§V). At the joint 95% CL, the signature is below current per-bin precision. Detection requires $\sim 0.5\%$ per-bin BAO measurements (Euclid DR2 / DESI full-survey) or aggregate multi-bin analysis.

### C. Growth of structure $f(z)\sigma_8(z)$ from RSD

With EFE unchanged, linear growth obeys $\delta'' + (2 + H'/H)\delta' - (3/2)\Omega_m(z)\delta = 0$ in $x = \ln a$. The Λcos modification enters only through $H(z)$; no perturbation-level sound-speed or anisotropic-stress parameter is needed (the $(1+z)^1$ correction is a background-level term, not an independent clustering component). The full ODE solve at the SN+BAO best fit is reported in the Λcos paper §VI.C.

| Quantity | MIT ($s_0 = 0.076$, posterior median) | MIT ($s_0 = 0.185$, 95% UL) | ΛCDM |
|---|---|---|---|
| $f\sigma_8(z)$ deviation from ΛCDM, per bin | $\leq 0.2\%$ across $z \in [0.3, 1.5]$ | $\leq 1\%$ (peak at $z \approx 1$) | 0 |
| $\chi^2_\text{RSD}$ against DESI DR1 ShapeFit+BAO (6 tracer bins) | 4.68 | 4.90 | 4.64 |
| $\Delta\chi^2_\text{RSD}$ vs ΛCDM | +0.04 | +0.26 | 0 |
| $\Omega_m(z)$ split at $z = 2.3$ (95% UL) | — | -2.9% | 0 |

At current DR1 FS precision (9-23% per bin), the Λcos-vs-ΛCDM gap is buried in the measurement uncertainty: the data carry no discriminating power between the two models at the SN+BAO-allowed $s_0$. The earlier leading-order estimate that placed the gap at $\sim 10\%$ ($f(0) \approx 0.58$ vs 0.53) used the dressed coefficient 0.371 in place of $\Omega_m(z=0)$ in the source term; the source term carries the underlying $\Omega_m = 0.315$ (same as ΛCDM at $z = 0$) and the leading-order f-estimate is identical for both models, with the actual model-to-model difference set by the small $H(z)$ deformation that the full ODE solve captures. Distinguishing the two in growth observables requires Euclid DR2 / DESI full-survey full-shape analyses at sub-percent per-bin precision, or higher-redshift growth measurements extending past $z = 1.49$ (the DR1 FS ceiling) where the $\Omega_m(z)$ split is most pronounced.

### D. Early-galaxies acceleration $a_0(z)$

$a_0(z)/a_0(0) = H(z)/H_0$ (derived, early-galaxies paper).

| $z$ | MIT ($s_0 = 0.389$) | MIT ($s_0 = 0.19$) | ΛCDM | Euclid-adjacent observable |
|---|---|---|---|---|
| 0.5 | $1.36 \times a_{0,\text{local}}$ | $1.33 \times a_{0,\text{local}}$ | $1.32 \times a_{0,\text{local}}$ | Galaxy-galaxy lensing / scaling relations |
| 1.0 | $1.88 \times a_{0,\text{local}}$ | $1.81 \times a_{0,\text{local}}$ | $1.79 \times a_{0,\text{local}}$ | Galaxy-galaxy lensing / scaling relations |
| 2.0 | $3.25 \times a_{0,\text{local}}$ | $3.08 \times a_{0,\text{local}}$ | $3.03 \times a_{0,\text{local}}$ | Galaxy-galaxy lensing / scaling relations |

Direct $a_0(z)$ rotation-curve tests require external kinematic follow-up beyond the Euclid survey footprint.

### E. Phantom-crossing channel  *(Λcos paper)*

| Quantity | MIT | ΛCDM |
|---|---|---|
| True $w_\text{eff}(z) > -1$ at all $z$ (fiducial split) | yes (proven analytically, Λcos paper §III) | yes |
| Apparent CPL crossing of $w = -1$ | yes (template bias artifact, Λcos paper §IV) | no |
| Apparent $w_0$ from CPL fit at $s_0 = 0.19$ | $\approx -1.02$ | -1 |
| Apparent $w_a$ from CPL fit at $s_0 = 0.19$ | $\approx +0.29$ | 0 |
| $\Delta\chi^2$ vs ΛCDM (SN+BAO) | +0.11 | 0 |

The apparent phantom crossing is a structural artifact of projecting a non-phantom $H(z)$ form onto two-parameter templates (CPL, BA, JBP). The three-parameter polynomial does not produce the crossing (Λcos paper Table II). At data-allowed $s_0$, the induced distortion is modest and of opposite sign to the DESI best-fit ($w_0 \approx -0.75$, $w_a \approx -0.86$). The mechanism is established; the amplitude gap remains.

### F. Null channels (topology-fixed)

| Quantity | MIT | ΛCDM |
|---|---|---|
| Λ(z) variation with redshift | 0 | 0 |
| Lensing mass / clustering mass (hidden DM component) | 1 | 1 with particulate DM |
| Fourth fundamental force, SUSY partners, new gauge bosons | 0 | 0 |
| Time variation of $\alpha$ | 0 | 0 |

### G. CMB–galaxy lensing cross-checks  *(from cosmos papers)*

| Quantity | MIT | ΛCDM |
|---|---|---|
| CMB $\ell_\text{cut}$ | ~32 (Molien gap) | no cutoff |
| $C_2/C_3$ | 0.13 | ~0.3 |

*Parity ($R_{TT}$) and the $\ell = 2/3$ alignment are dropped here: chirality severs them from this topology (see [CMB Anomalies](../../../../cosmos/files/cmb-anomalies.md)).*

### H. Clock-setting logic

The prediction set is over-determined in principle. One fit parameter ($s_0$) forecasts $H(z)$, $f\sigma_8(z)$, $a_0(z)$, and the template bias signature simultaneously. If all channels hit within their stated precision, $s_0$ is independently over-determined by Euclid DR1 alone — the clock is empirically set without needing the postulate-level derivation of $t_\text{now}$ to have closed yet. If channels disagree, the model fails before the postulate-level derivation matters.

**Current tension.** Pantheon+ alone accommodates $s_0 \sim 0.39$; joint SN+BAO constrains $s_0 < 0.19$ (95% CL). The BAO data are pulling the clock toward zero. Euclid DR1 BAO will either confirm the tighter constraint (in which case the model's observable departures from ΛCDM become marginal at DR1 precision and the discriminating test moves to DR2/next-generation) or open room for larger $s_0$ (in which case the full prediction ledger remains live). Either outcome is informative.

This remains pre-registration at the deepest level: **predict the time, then look**. The Λcos paper has placed the first joint background-and-growth constraint on the budget phase parameter.

### Status of the two open computations

1. **Closed (Λcos paper §VI.C).** Numerical integration of the linear-growth equation with Model D+Λ $H(z)$, compared to DESI DR1 ShapeFit+BAO at six tracer effective redshifts (BGS, LRG1-3, ELG2, QSO; $z \in [0.30, 1.49]$). The full $f\sigma_{s8}(z)$ trajectory at the SN+BAO posterior median gives $\chi^2_\text{RSD} = 4.68$ (vs 4.64 for ΛCDM); at the 95% UL, $\chi^2_\text{RSD} = 4.90$. The $\Omega_m(z)$ diagnostic shows a 2.9% split at $z = 2.3$ at the upper limit, beyond the current growth-data reach. The earlier leading-order $f(0)$ estimate (§XI.C, prior version) overstated the gap and has been replaced.
2. **Partially closed.** The joint SN+BAO MCMC in the Λcos paper computes $D_M/r_d$, $D_H/r_d$, $D_V/r_d$ at the seven DESI DR2 effective redshifts as part of its likelihood. Explicit Euclid-band forecasts of $D_A(z)$, $D_L(z)$, $D_V(z)$ at allowed parameter values remain to be tabulated for the prediction ledger.

---

*The budget balances. The clock keeps time. The waltz continues.*

---

/ **[`main`](../../../../../README.md)** / **[`framework`](../../../../framework/)** / **[`working`](../)** / **[`cosmos`](../../../../cosmos/)** / **[`spectrum`](../../../../spectrum/)** /
