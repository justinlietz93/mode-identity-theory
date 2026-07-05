/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /

---

# The Tick Lemma

**Status (2026-07-05):** DEFINITION FROZEN at this commit; the computation is not yet run. This is gate (ii) of the [half-power clock](friedmann-as-output.md), the decider. Sections I-V (the frozen definition, the generic uniqueness lemma, the disambiguation menu, and the verdict table) are committed before any computation; Sections VI-VII are filled by a separate computation commit and by nothing else. The git history is the audit trail: the definition below is built from primitives already in service elsewhere, and the target exponent appears nowhere in it.

**Related:** [The Half-Power Clock](friedmann-as-output.md) (the tracker), [The Level Exchange](half-power-involution.md) (gate i; supplies the level measures), [Temporal Budget](temporal-budget.md), [Entropy as Realization Budget](entropy-as-realization-budget.md) (the armed consequence channel; not touched here).

---

## I. The Question

Is a tick a joint-registration event? Everything else in the half-power program is closed, armed, or fenced: gate (i) gives the level-exchange structure, gate (iii)'s first consequence is pre-committed on the entropy page, and the fits eliminated the rungs and the skipped midpoint. What remains is whether the observer's elementary tick, once defined from the framework's own primitives, induces the overlap density of the two level measures or something else. A kill here is as valuable as a landing.

---

## II. Primitives and the Frozen Definition

Three primitives, each already in service, none introduced for this page:

1. **The chronon** $\Delta t_{\min} = 4\pi/120$: the smallest phase advance the domain registers. It supplies the tick's counting side and its units. Its measure-theoretic role here: the count-level measure $dt$ is the *base measure* against which the level densities are taken.
2. **The two ledgers**, fixed at gate (i) as the level measures relative to that base: the amplitude ledger $d\mu_A = S\,dt$ (section-level bookkeeping of realized content available to sample) and the intensity ledger $d\mu_I = S^2\,dt$ (function-level bookkeeping of registered results; the level of the measurement rule $C(\Theta) = 2\sin^2(\pi\Theta)$). These are stocks: the standing weight each level assigns to a phase interval. Flows (transfer rates like $d(S^2) = S\Psi\,dt$) are outputs of tick counting, not ledger weights; using a flow as a ledger weight is the already-dead R-REAL construction, named in Section IV so the stocks-versus-flows adjudication is visibly pre-committed.
3. **The sampling act**: the framework's elementary act of observation, registration of realized content. Per the sampling ontology the framework already carries: registration constitutively *draws on* realized content (amplitude level) and *deposits* a registered result (intensity level). The irreversibility of observation lives in the accumulation of such acts, not in the wave ([entropy page](entropy-as-realization-budget.md) §IX).

> **Definition (the tick; FROZEN).** An elementary tick is one sampling act at chronon resolution: a single event that draws on the amplitude ledger and deposits on the intensity ledger. One event, two ledger entries. The tick measure $d\mu_{\text{tick}}$ is the rate density of such events on the phase interval, taken relative to the count base $dt$; the chronon fixes its normalization (ticks are discrete, one per registered chronon), and the ledgers fix its $S$-dependence.

**Why the tick cannot live on one ledger (the necessity argument).** An amplitude-only event keeps the section-level $4\pi$ bookkeeping but is not registered: nothing is deposited, no observation occurred. An intensity-only event is registered but holonomy-blind: $S^2$ is $2\pi$-periodic, invariant under the lap sign flip, so a purely intensity-native tick cannot see the period it is supposed to keep. A tick must preserve the section-level temporal bookkeeping *and* produce a registered result, so it lives at the amplitude-intensity interface. (Caveat carried from gate (i): measures on the positive quadrant are sign-blind, so the holonomy half of this argument attaches to how the densities are built, not to their values; it is support for the definition, not a proof of the induced weight.)

---

## III. The Interface-Measure Uniqueness Lemma (generic)

Independent of everything above, a piece of elementary mathematics, stated conditionally: it says nothing about which reading the tick satisfies.

> **Lemma.** Let $F(\mu, \nu)$ assign a measure to a pair of measures on the phase interval, and suppose $F$ is (a) local (acts pointwise on densities relative to the base), (b) exchange-symmetric, $F(\mu, \nu) = F(\nu, \mu)$, (c) covariant under independent rescaling of the two arguments, and (d) idempotent, $F(\mu, \mu) = \mu$. Then $F(\mu, \nu) = \sqrt{\mu\nu}$, the overlap density.

*Proof.* Locality gives $F(w_1\,dt, w_2\,dt) = f(w_1, w_2)\,dt$. Rescaling covariance gives $f(c\,w_1, d\,w_2) = c^\alpha d^\beta f(w_1, w_2)$; setting $c = d$ and using idempotence on equal arguments forces $\alpha + \beta = 1$; symmetry forces $\alpha = \beta = 1/2$; so $f(w_1, w_2) = f(1,1)\sqrt{w_1 w_2}$, and idempotence fixes $f(1,1) = 1$. $\square$

Two physical faces of the same selection, expected to merge and confirmed to: the *overlap* face ($\sqrt{\mu\nu}$ is the integrand of the Bhattacharyya and Hellinger affinities, the standard similarity density of two bookkeepings), and the *detailed-balance* face (a kernel exchanging quanta between ledgers of weights $w_1, w_2$, symmetric under the ledger swap, runs at the balanced rate $\propto \sqrt{w_1 w_2}$; swap symmetry alone confines the flux to the product-power family $(w_1 w_2)^s$ and idempotence pins $s = 1/2$). One computation viewed twice, which is coherence, not double evidence. What the lemma does *not* supply: that the tick measure satisfies (b). Symmetry of the elementary kernel is a physical premise, examined in Section VI, not a mathematical freebie.

---

## IV. The Disambiguation Menu (posted before computing)

"An event both bookkeepings register" has distinct formalizations with different induced weights. All four are named now, so the adjudication in Section VI is against a fixed menu:

| Reading | Structure | Induced weight | Note |
|---|---|---|---|
| Coincidence | two independent event streams, one per ledger; tick = both fire within one chronon | $S^3\,dt$ | product of densities; requires two stochastic streams |
| One-sided | tick counted on a single ledger | $S\,dt$ or $S^2\,dt$ | endpoints; both already eliminated as observer clocks by the fits |
| Flow-weighted | ledger entry taken as the transfer increment $d(S^2) = S\Psi\,dt$ | $\propto S^{1/2}\Psi^{1/2}\,dt$ or $S\Psi\,dt$ | level-mixed; the $S\Psi$ form is R-REAL, already dead analytically |
| Conversion | one event carried on two ledgers; tick measure is the interface measure of the stock pair | $\sqrt{\mu_A\,\mu_I} = S^{3/2}\,dt$ | requires the Lemma's premises, including kernel symmetry |

---

## V. The Verdict Table (posted before computing)

| Computation returns | Recorded outcome |
|---|---|
| $S^{3/2}\,dt$ | gate (ii) closes, with its premise ledger stated; scoring moves to the armed channels (entropy bound, registered fit) and review. The budget page's FORCED label is NOT flipped by this note. |
| $S^3\,dt$ or an endpoint | route dies; the tracker's failure bar activates; the program closes as kinematics native, one named dynamical import |
| off-ladder or level-mixed | route dies the same way, with the added note that the tick violates definite level |

If the tick cannot be shown to be a joint-registration event at all, the level-exchange structure remains elegant but non-derivational, and $S^{3/2}\,dt$ reverts to a motivated clock postulate. That sentence is the failure condition, registered before the attempt.

---

## VI. The Computation

*Not yet run. This section is filled by the computation commit and by nothing else.*

---

## VII. Premise Ledger and Verdict

*Not yet run. Filled with Section VI.*

---

*One event, two ledgers, one base. The definition is frozen; the calculation decides.*

---

/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /
