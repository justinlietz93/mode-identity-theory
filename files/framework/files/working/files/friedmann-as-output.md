/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /

---

# Friedmann as Output

**Status (2026-07-05):** OPEN; tracker created. The program reduces to a single number: the Waltz clock exponent $-1/2$ in $dt/d\tau = S^{-1/2}$, which is currently FORCED by $S^3$ dimensionality plus GR ([temporal-budget](temporal-budget.md) §VII) and empirically unique in its family (integer alternatives ruled out at $\Delta\chi^2 > 60$, Λcos paper). Everything else in the chain from postulate to $H(z)$ is axiom, definition, established kinematic dictionary, or algebra. A derivation of the exponent from the postulate layer, with GR entering only for comparison, would flip the §VII line from FORCED to DERIVED and make $H^2 \propto \rho$ output in form. A route-specific failure across the enumerable clock menu below is also a recorded outcome: it would close this program honestly as "kinematics native, one dynamical import."

**Dependencies:** [Temporal budget identity](temporal-budget.md), Waltz clock, spatial budget $u_0^2 + J^2 = 1$, Molien shell map (shared with [Entropy as Realization Budget](entropy-as-realization-budget.md)), Gauss-Codazzi embedding (assembly stage only).

**Related:** [The Budget Map](budget-map.md), [Redshift and Cooling](redshift-and-cooling.md), [The Waltz](../../../../spectrum/files/the-waltz.md), [first-eigenvalue](../../bedrock/files/first-eigenvalue.md) (the spatial twin's pair).

---

## I. The Reduction

The chain, with the epistemic status of each link:

| Link | Status |
|---|---|
| $\Psi = \cos(t/2)$ on the temporal edge | AXIOM (anti-periodicity, initial maximum, lowest harmonic) |
| $\Psi^2 + S^2 = 1$, $S = \sin(t/2)$ | PROPOSED reading; trigonometric identity |
| $1 + z = S(t_\text{obs})/S(t_\text{emit})$, $T \propto 1/S$ | ESTABLISHED kinematic equivalence with the FLRW thermal law ([Redshift and Cooling](redshift-and-cooling.md)) |
| $a \propto S$ | the same kinematic dictionary, at the level of observables |
| $dT = a\,d\tau$ | definition of proper vs conformal time |
| $dt/d\tau = S^{-1/2}$ | **FORCED by $S^3$ dimensionality + GR; the one imported line** |
| $H \propto \Psi/(2S^{3/2})$, $H^2 \propto (1-S^2)/S^3$ | algebra from the two lines above ([temporal-budget](temporal-budget.md) §VI) |
| Fit: $\Delta\chi^2 = +0.11$ vs flat ΛCDM (SN+BAO), $\Omega_m = 0.315$ recovered | ESTABLISHED at model level |

So Friedmann-as-output is not a broad program; it is one exponent. Derive $dt/d\tau = S^{-1/2}$ from the postulate layer (anti-periodic holonomy, the sampling rules, the 120-domain) and the matter-like $(1+z)^3$, the bounded-budget $(1+z)^1$ correction, and the recovered $\Omega_m$ all become consequences rather than imports. Two scope fences. First, "output" will mean the *form* $H^2 \propto \rho_\text{realized} + \Lambda$-term; the normalization ($G$, and the unit constants) stays external, per the calibration structure. Second, deriving $t_\text{now}$ from topology is a separate open item ([temporal-budget](temporal-budget.md) §X) and is not this tracker's target.

**What is circular and why.** The current forcing decomposes the exponent as (matter dilution in 3 dimensions, $S^{-3}$ on density) against (the Friedmann square root on the rate): $1 - 3/2 = -1/2$. Both legs are GR's. That is legitimate as validation and as the identification of the target value; it is circular as a derivation, which is exactly what the §VII chain records.

**What the data already did.** The Λcos fits killed the integer family: Models A ($S^0$, $+218.7$), B ($S^{-1}$, $+1821.9$), C ($S^{+1}$, $+7276.6$) against D ($S^{-1/2}$, $+0.11$). Any candidate clock below that reduces to an integer power is dead on arrival, no new fit needed. The derivation target is sharp: the half power, and only the half power.

---

## II. Stage 0: The Reconciliation Gate

The spatial-to-temporal reconciliation is the gatekeeper because every native clock candidate is built from objects that live either on the spatial pair $(u_0, J)$ or on the temporal pair $(S, \Psi)$, and the dictionary between them is currently structural parallel, not theorem.

**Lemma 0.1 (half-angle; the cheap first result).** $\Psi = \cos(t/2)$ is anti-periodic under one lap ($t \to t + 2\pi$ gives $\Psi \to -\Psi$) and periodic under the full edge circuit ($t \to t + 4\pi$). This is exactly the section structure of the orientation line bundle over the core circle, pulled back to the edge, where it becomes a genuine function: the sign flips once per lap of the strip, and the edge closes after two laps. The half-angle is therefore not a modeling choice; $t/2$ is the lap coordinate, and the temporal twin's half-angle is forced by the same holonomy that quantizes the spatial half-integer tower. Writing this lemma out formalizes the dictionary $t/2 \leftrightarrow$ lap angle and makes the twin correspondence $(S, \Psi) \leftrightarrow (u_0, J)$ ($\sin \leftrightarrow \sin$, $\cos \leftrightarrow \cos$) principled rather than typographic.

**Gap 0.2 (the domain mismatch).** The dictionary is local, not global: the meridional coordinate $y/R$ runs over an interval with seam and cone endpoints, while the lap coordinate runs over a circle. Any route that borrows a spatial functional must say which curve the observer's worldline is (the edge) and how meridional data pulls back to it. This gap is the honest content of "spatial-to-temporal reconciliation."

**Prerequisite bookkeeping, already diagnosed elsewhere.** The $\Phi \leftrightarrow t$ discrepancy is quantified on the budget page (§VIII): the engine phase folded in the ΛCDM 13.8 Gyr age instead of the clock-inverted $T_\text{now} \lesssim 0.79$ Gyr, a factor of $\sim 17$ in one substituted number. Its resolution (re-derive $\Phi_\text{now}$ by inverting the clock) is prescribed there and is bookkeeping relative to this tracker: it uses the clock, it does not derive it.

**Hazards carried at every stage.** The clock 3/2 (matter dilution / Friedmann root) and the Gauss-Codazzi 3/2 (Ricci trace / de Sitter normalization) are numerically equal and not shown to be the same object; the budget page fences them and this tracker keeps the fence. The space is static: dilution language is the kinematic dictionary, never expansion. And the temporal harmonic ground ($m = 0$ selection of $\Psi$) is not the spatial zero mode; the two "grounds" stay separate.

---

## III. The Route Menu

Each candidate is a framework-native definition of the observer's tick, stated without GR, with the exponent it induces and the gate that lands or kills it. The target is $dt/d\tau = S^{-1/2}$, equivalently a lapse $N = S^{1/2}$, $N^2 = S$: the metric element linear in the realized amplitude.

| Route | Clock definition | Induced $dt/d\tau$ | Verdict / gate |
|---|---|---|---|
| R-PHASE | tick per chronon of phase, $\tau \propto t$ | $S^0$ | DEAD: Model A, $\Delta\chi^2 = +218.7$ |
| R-INT | tick rate $\propto$ realized intensity, $d\tau \propto S\,dt$ | $S^{-1}$ | DEAD: Model B, $+1821.9$ |
| R-REAL | tick per realized quantum, $d\tau \propto d(S^2) = S\Psi\,dt$ | mixed $S^{-1}\Psi^{-1}$ | DEAD analytically: reduces to Model-C behavior early ($S \approx t/2$, $\Psi \approx 1$), and the $\Psi$ factor leaves the $S^n$ family |
| R-TRANS | tick per unit amplitude transfer, $d\tau \propto \lvert dS\rvert = (\Psi/2)\,dt$ | $\Psi$-clock | DEAD analytically: Model-A behavior early, wrong family late |
| R-GM | the geometric mean of the two flanking clocks: $\sqrt{S^0 \cdot S^{-1}}$ | $S^{-1/2}$ exactly | LANDS arithmetically. The open content is the principle: why is the observer's clock the geometric mean of the phase clock and the intensity clock? The candidate is the framework's own self-dual midpoint selection (the same move that places the observer at $\sqrt{\Omega}$). MOTIVATED until that selection is stated at operator level; a rhyme is not a mechanism. |
| R-AMP | ticks are amplitude-level events: the lapse squared is linear in the realized amplitude, $N^2 = S$ | $S^{-1/2}$ by construction | LANDS by construction; the derivation burden moves to the sampling operator. The half power is the signature of a pre-squaring (amplitude-level) process, the same $\psi$ vs $\lvert\psi\rvert^2$ split that separates the 120-grid from the 60-grid. Gate: write the tick as an operator statement and show it returns $N^2 = S$ rather than $N^2 = S^2$. |
| R-COUNT | tick per unlocked mode: $d\tau \propto dN/N$ with $N = N_\text{max}(S)$ from the Molien shell map | exponent set by $d\log N/d\log S$ | OPEN, and deliberately fused: this is the same unwalked map that is load-bearing on the entropy page. One unknown map, two independent constraints (the clock exponent here, the phase-space growth there). Over-determination is the feature: a candidate map must land $-1/2$ here and the accessible-mode count there, or it dies twice. |
| R-TWIN | spatial functionals of $(u_0, J)$ pulled back along the lap dictionary (lengths, areas, Jacobi spread) | mostly $\Psi$-powers or integer $S$-powers | Enumerate and record. Expected negative for the simple functionals; a landing would be the fully geometric derivation. Blocked on Gap 0.2 for anything beyond the local dictionary. |
| R-STAB | read $3/2$ as face/edge stabilizer orders; the budget page's §VI names the vertex for the $\Psi$ numerator | $S^{-1/2}$ by arithmetic | HAZARD-GATED: numerical equality is not a mechanism (the arch lesson). Admissible only with an operator-level bridge from stabilizer order to clock exponent; otherwise this is the two-3/2s fusion the fence exists to prevent. |

**Order of attack.** Lemma 0.1 first (cheap, upgrades the dictionary). Then R-AMP and R-GM, the two that land, because each is one sharp question: state the tick operator; state the midpoint principle. Then R-COUNT, because its lemma is shared with the entropy page and pays double. R-TWIN enumeration last, as the systematic sweep. R-STAB is not attacked; it is fenced.

---

## IV. Verdict Semantics

**Success bar.** DERIVED means: the exponent follows from postulate-layer primitives, with GR appearing only in the comparison to Friedmann form. On success, the budget page's §VII line flips FORCED $\to$ DERIVED, the $(1+z)^3$ coefficient and the negative $(1+z)^1$ signature become outputs in form, and the framework produces dynamics for the first time. The claim stays scoped: form, not normalization.

**Failure bar.** If the menu exhausts with the landing routes killed at their gates (no operator-level tick giving $N^2 = S$, no principled midpoint selection, no shell map satisfying both constraints, no geometric functional landing the half power), the recorded verdict is route-specific: the clock exponent is dynamical input at the kinematic layer, Friedmann stays input, and the program closes honestly. The fits are untouched either way; the budget page's own $s_0 \to 0$ paragraph already prices the distance-sector stakes, and none of the particle or topology content rides on this.

**Discipline.** No new numerology: any 3/2 that surfaces must clear the two-3/2s fence before it counts, the same way any $2/R^2$ in the bridge program had to clear the curvature-scale-coincidence check.

---

*One exponent stands between kinematics and dynamics. The menu is finite. Either a clock lands it, or the import gets named for what it is.*

---

/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /
