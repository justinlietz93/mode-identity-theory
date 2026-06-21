/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`working`](../)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /

---

# Entropy as Realization Budget

A candidate MIT account of the thermodynamic arrow in a static universe, scoped to the realization sector. The temporal budget already cools the universe without an exterior; this note asks where the entropy increase comes from, and answers it only where it can.

**Status:** MOTIVATED. Not derived. Research note for a future paper. The cooling half is ESTABLISHED (temporal budget §I.A); the entropy half rests on one unwalked map.

**Dependencies:** Temporal budget identity $\Psi^2 + S^2 = 1$ and §I.A (Cooling Without an Outside); energy as resolution amplitude; the $2I$-invariant (Molien) shell spectrum of $S^3/2I$; the chronon and the 120-domain.

**Related:** [The Temporal Budget Identity](temporal-budget.md), [Energy as Resolution Amplitude](energy-as-resolution-amplitude.md), [CMB Anomalies](../../cosmos/files/cmb-anomalies.md) (the same Molien shells), [The Waltz](../../spectrum/files/the-waltz.md).

**Notation.** $S = \sin(t/2)$ is the realization amplitude, kept from the temporal budget. Entropy is written $\Sigma$ to avoid collision with it; the accessible-mode count is $W$, with $\Sigma = k_B \ln W$. The action $\mathcal{S}$ is unaffected.

---

## I. The question

A static space at fixed volume has no exterior to radiate into and no growing volume to dilute into. Cooling is already answered: budget weight transfers $\Psi^2 \to S^2$ as the phase advances, photon energies scale by $S(\text{emit})/S(\text{obs}) = 1/(1+z)$, every wavelength by the same factor, so a blackbody stays a blackbody at $T \propto 1/S$ (temporal budget §I.A). That is the temperature half, and it is settled.

The status line of §I.A names what it does not settle: the thermodynamic entropy. A temperature law is not an entropy law. This note is the gameplan for the entropy, and it claims only the realization sector: the arrow of time as the budget resolves, not the gravitational arrow that Penrose's puzzle is about (§V).

---

## II. Energy, realization, entropy

The reframe is inherited, not invented here. [Energy as Resolution Amplitude](energy-as-resolution-amplitude.md) reads energy not as a substance an object carries but as the amplitude of the wave resolved at an observer's sampling coordinates. Carry that into the budget and entropy has a natural home.

$S = \sin(t/2)$ is the realized-mode content of the wave, the fraction expressed as resolvable modes at phase $t$. If energy is resolution amplitude, then the realized modes are where energy lives, and **entropy is how that energy is spread across them**. A budget concentrated in a few modes is ordered; the same budget spread across many is not.

| Question | Standard (FLRW) reading | MIT realization reading |
|---|---|---|
| What cools the bath | growing volume; comoving photon entropy conserved | budget spreads $\Psi^2 \to S^2$; per-mode amplitude falls |
| Why the low-entropy past | unexplained boundary condition (Penrose) | realization sector: forced by $\Psi(0) = +1$, $S(0) = 0$ |
| Where the arrow comes from | initial conditions, external | the direction of budget transfer |

---

## III. The second law as budget transfer

At early phase ($t \to 0$): $\Psi^2 \approx 1$, $S^2 \approx 0$. The budget sits concentrated in the unresolved standing wave, the formal hot dense limit of the unit-circle table. Few realized modes, the amplitude piled into them: low realization-entropy, high $T$.

As the phase advances the budget flows $\Psi^2 \to S^2$, out of the concentrated reservoir and into distributed realized modes. Per-mode amplitude falls (this is $T \propto 1/S$, the cooling), while the budget spreads over more modes. **The realization entropy climbs, and its increase is the same transfer that does the cooling.** The arrow of time is the direction of that flow; the low past is not tuned, it is where the wave starts.

**The crux, stated honestly.** A naive photon gas in a fixed volume with $T \propto 1/S$ has entropy $\propto V T^3 \propto 1/S^3$, which falls as $S$ grows: the wrong direction. In the FLRW picture the growing volume rescues it; a static domain has no such term. So this account cannot rest on $T^3$ box entropy. The entropy that rises counts realized modes, not $T^3$: per-mode energy falls while the number of accessible modes grows, and the product climbs. This is ordinary thermalization, a few hot modes giving way to many cool ones at fixed total budget. Stating it any other way puts the second law backward.

---

## IV. The mode-count map (the whole physics)

Everything above is qualitative until one function is fixed: $W(S)$, the count of accessible modes at realization $S$. **This map is not one open item among several; it is the physics of the page, and it is also its only guard against circularity.** Write $\Sigma = S$ by hand, or $W = e^{S}$, and the rising entropy is the definition read back, a second law assumed rather than derived. Draw $W$ from the structure instead, and "$\Sigma$ rises" becomes a statement about microstates.

The structure offers a concrete candidate. The accessible modes are the $2I$-invariant harmonics on $S^3/2I$, graded by degree into the Molien shells $N = 0, 12, 20, 24, 30, \ldots$ (the same shells that set the low-ℓ CMB gap; see [CMB Anomalies](../../cosmos/files/cmb-anomalies.md)). Each realized shell contributes its invariant degeneracy. The count up to the highest shell realized at $S$ is

$$W(S) = \sum_{N \le N_\text{max}(S)} d_N, \qquad \Sigma(S) = k_B \ln W(S),$$

with $d_N$ the $2I$-invariant degeneracy of shell $N$. At $S \to 0$ only $N = 0$ is realized, $W = 1$, $\Sigma = 0$: a Boltzmann ground state forced by the boundary condition. As $S$ grows, $N_\text{max}$ climbs and $W$ with it. A second candidate ties $N_\text{max}$ to phase resolution through the chronon $\pi/30$: finer phase structure becomes resolvable as the budget realizes, unlocking higher shells.

**The load-bearing, unwalked step is the link $S \mapsto N_\text{max}(S)$:** how much realization unlocks which shell. Until it is derived from the 120-domain or the McKay grading, the monotonicity of $\Sigma$ is a candidate, not a theorem.

$$\begin{aligned}
\text{energy} = \text{resolution amplitude} & \quad \text{[IMPORTED, MOTIVATED]} \\
\Psi^2 + S^2 = 1,\; S = \sin(t/2) & \quad \text{[temporal budget]} \\
\text{realized-mode content grows with } S & \quad \text{[FOLLOWS]} \\
S \mapsto N_\text{max}(S) \text{ from } S^3/2I & \quad \text{[OPEN; load-bearing; anti-circularity]} \\
W(S) = \textstyle\sum_{N \le N_\text{max}} d_N & \quad \text{[FOLLOWS once the map is fixed]} \\
\Sigma = k_B \ln W(S) & \quad \text{[Boltzmann]} \\
d\Sigma/dt > 0 \text{ on } 0 < t < \pi & \quad \text{[THEOREM if } W \text{ monotone; OPEN until the map is fixed]}
\end{aligned}$$

---

## V. Scope: two entropy ledgers

The reframe accounts for the arrow in one sector. It does not touch Penrose's puzzle, because Penrose's puzzle is the other ledger.

| | Realization entropy (this note) | Gravitational entropy (Penrose's subject) |
|---|---|---|
| What it counts | budget spread over realized modes | Weyl curvature, clumping, black holes |
| Early state | low: the wave concentrated at $S = 0$ | low: the early universe smooth |
| Why the low past | forced by $\Psi(0) = +1$ | the open puzzle |
| Through turnaround | peaks at full realization, then falls | keeps rising; black holes stay formed |
| Share of the total | subdominant | dominant |

The honest claim is the left column: realization entropy starts low because the wave starts at $S = 0$, a genuine account of the arrow in that sector. The right column is Penrose's, and this note leaves it open. The realization budget gives the thermodynamic arrow of the radiation and mode sector; it does not explain the smoothness of the gravitational initial state, and it should not be advertised as if it does.

---

## VI. The turnaround is a sub-budget feature

$S = \sin(t/2)$ peaks at $t = \pi$ and returns to $0$ at the $t = 2\pi$ turnaround, so the realization entropy $\Sigma(S)$ rises to a maximum at full realization and then falls. This is a reversal of the realization sub-budget, not of the second law. The dominant ledger is gravitational, and gravitational entropy rides straight through the turnaround: black holes stay formed, clumping does not un-clump, so total entropy keeps climbing. The reversal is a real and unusual prediction about the realization sector alone, and it costs nothing observationally: the present sits at $t_\text{now} < 0.38$ rad, far inside the rising branch ($S \approx 0.19$, about a fifth of the way to full realization).

---

## VII. Observational anchors

The thermal history is a phase ladder, every epoch a value of $S = S_\text{now}/(1+z)$: recombination at $S \approx 1.7 \times 10^{-4}$, BBN near $S \sim 10^{-10}$, the pure-wave limit at $S \to 0$. The temperature law $T \propto 1/S$ reproduces these as the FLRW history does, kinematically (temporal budget §I.A).

For the entropy the bar should sit where it can be cleared. **The honest target is that the realized-mode count must not contradict the observed entropy:** the photon-to-baryon ratio $\eta \approx 6 \times 10^{-10}$ and the absolute CMB entropy ($\sim 10^{88}\,k_B$). Reproducing $\eta$ from harmonic counting would be a baryogenesis number falling out of group theory, which is upside, not the pass condition; it is unlikely to come out cleanly and the page should not stake itself on it. Consistency is the pass; prediction is the bonus.

---

## VIII. What needs to be derived

1. **The map $S \mapsto N_\text{max}(S)$.** Load-bearing and anti-circularity, per §IV. Without it the second law here is assumed, not derived.
2. **A statistical-mechanical definition of $\Sigma$.** A Gibbs or microcanonical measure over the realized modes, not a relabeling of $S$, with $\Sigma = k_B \ln W$ following from the count.
3. **Consistency with $\eta$ and the CMB entropy** (§VII), as a floor; clean reproduction as upside.
4. **Reconciliation with §I.A.** The entropy account must agree with the established kinematic $T \propto 1/S$ wherever the FLRW thermal history agrees.
5. **The boundary of scope held explicitly:** realization sector in, gravitational ledger out (§V).

---

## IX. What this is not

A solution to Penrose's low-entropy past. That is the gravitational ledger, and it stays open (§V).

A claim that total entropy reverses at turnaround. Only the realization sub-budget peaks and falls; gravitational entropy carries the total monotonically through (§VI).

Tired light. The redshift here is a uniform phase-ratio rescaling that preserves the Planck spectrum, not a scattering loss that would smear it (temporal budget §I.A).

A derived result. The reframe is consistent and framework-native, and it rests on one unwalked map. Until that map is drawn from the structure, this is MOTIVATED.

---

*Cooling is the budget spreading. Entropy is the spread, counted.*

*The wave starts ordered because it starts as one mode.*

---

/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`working`](../)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /
