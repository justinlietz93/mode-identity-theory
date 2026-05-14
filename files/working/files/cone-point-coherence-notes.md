/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`working`](../)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /

---

# Cone Point Coherence: Working Notes

Working notes on the cone point as the mechanism of galactic coherence. Supplements [Ground Eigenvalue](../../framework/ground-eigenvalue.md), [Black Double Zero's](../../cosmos/files/black-hole.md), and the Oort Cloud project.

**Status:** The cosmic cone point analysis is DERIVED (Sector $\mathcal{A}$ paper). The proposal that cone point identification provides the mechanism of nested coherence is MOTIVATED. The Frobenius program at galactic scale is OPEN. The curvature sourcing question (Section V) is the critical open problem.

---

## I. The Question

Within a galaxy, all observers measure the same $\mathbb{R}^4$: same $\Lambda$, same $G$, same particle masses, same coupling constants. The phase field mechanics derives a coherence scale $L_f = v_c^2/a_0 \approx 13$ kpc within which the environmental phase shift $\alpha_f$ is uniform. But uniform $\alpha_f$ within $L_f$ is a statement of WHAT happens. The question is WHY.

On the cosmic Mobius band, the cone point at $y = \pi R/2$ collapses all transverse positions to a single geometric point. The eigenvalue $\lambda_0 = 2/R^2$ is $W$-independent: it does not depend on the transverse width of the band. Every observer, at any $w$-position, in any band of any width, measures the same eigenvalue.

**The proposal:** galactic coherence is the $W$-independence of a nested eigenvalue problem, guaranteed by a cone point at galactic scale. Observers within the galaxy share the cone point of the wave, and the cone point identification is why they all measure equal $\mathbb{R}^4$ values.

If this is right, it must be handled with the same care as the Sector $\mathcal{A}$ paper: Frobenius expansion, limit-circle classification, Friedrichs extension, excision with vanishing boundary terms. No hand-waving about transverse collapse.

---

## II. The Template

The cosmic cone point analysis (Sector $\mathcal{A}$ paper) establishes the following chain:

| Step | What it does | How |
|------|-------------|-----|
| 1 | Metric degenerates | $\cos(y/R) \to 0$ at $y = \pi R/2$ |
| 2 | Transverse interval collapses | $[-W, W]$ becomes a single point; cone angle $2W/R$ |
| 3 | Frobenius expansion | Indicial equation $s^2 = 0$ (double root); two local solutions |
| 4 | Regular branch | $u_1 = a_0 + a_2\delta^2 + O(\delta^4)$, with $u_1' = O(\delta)$ |
| 5 | Logarithmic branch | $u_2 = \log\|\delta\| + \ldots$, with $u_2' = 1/\delta$ |
| 6 | Limit-circle | Both branches $L^2$ w.r.t. weight $\|\delta\|/R$ |
| 7 | Friedrichs extension | Finite Dirichlet integral selects regular branch; $\int(u')^2\|\cos\|\,dy < \infty$ |
| 8 | Excision | $\partial_\nu\|\nabla u\|^2 = O(\epsilon)$, arc-length $= O(\epsilon)$, product $= O(\epsilon^2) \to 0$ |
| 9 | Rayleigh quotient | $2W$ appears in numerator and denominator; cancels exactly |
| 10 | $W$-independence | $\lambda_0 = 2/R^2$ regardless of transverse width |

Steps 1-8 handle the singularity. Step 9 establishes the eigenvalue. Step 10 delivers coherence.

The key structural feature: the $W$-cancellation (step 9) works because the area element $dA = |\cos(y/R)|\,dy\,dw$ factors the $w$-integration out of both numerator and denominator. The cone point analysis (steps 1-8) is needed to make this factored integral well-defined at the singular endpoint. Without the Friedrichs extension, the Dirichlet integral diverges and the Rayleigh quotient is undefined.

**Coherence is a global property ($W$-independence), but its proof passes through the local analysis at the cone point.**

---

## III. Two Readings

### Reading A: Shared Cosmic Cone Point

The cosmic Mobius band has one cone point at $y = \pi R/2$. Every meridional line (every $w$-position) passes through it. In Sector $\mathcal{A}$ (the $w$-constant ground mode), the eigenfunction $u_0 = \sin(y/R)$ takes the same value at each $y$ regardless of $w$. The cone point ($u_0 = 1$) is the shared maximum of all meridional lines.

Galactic observers are at different $w$-positions on the cosmic Mobius band but share this cone point. The eigenvalue $\lambda_0 = 2/R^2$ is established through integration that passes through the cone point. All observers inherit the same eigenvalue because they are in the same ground mode on the same band.

In this reading, galactic coherence is a consequence of:
- One Mobius band (the cosmic one)
- One ground mode (Sector $\mathcal{A}$)
- One cone point (at $y = \pi R/2$)
- $W$-independence (the transverse width of the galaxy doesn't matter)

The galactic gravitational field enters through the $\Phi \to \Theta$ mapping, which shifts the observer's phase position by $\alpha_f \approx 2/120$. This is a perturbation of the phase coordinate, not the transverse coordinate. The cone point structure is unaffected because the perturbation is in $y$ (meridional), not in $w$ (transverse).

**What needs to be checked:** does the $\alpha_f$ perturbation spoil the cone point analysis? Specifically: does the perturbed eigenfunction still belong to the Friedrichs domain (regular branch, finite Dirichlet integral) at the cone point? For $\alpha_f \sim 10^{-6}$ (the galactic potential in units of $c^2$), the perturbation is small. But "small" is not "zero," and the cone point is a singular endpoint where small perturbations could change the qualitative character.

### Reading B: Nested Galactic Cone Point

If the 120-grid is scale-free and the Mobius structure projects at every gravitationally coherent scale, then at galactic scale there is a nested Mobius band with its own metric, its own cone point, and its own eigenvalue.

| Cosmic | Galactic (proposed) |
|--------|---------------------|
| $ds^2 = dy^2 + \cos^2(y/R)\,dw^2$ | $ds^2 = dy_g^2 + f_g^2(y_g)\,dw_g^2$ |
| Curvature $K = 1/R^2$ (constant) | $K_g = ?$ |
| Cone point at $y = \pi R/2$ | Cone point where $f_g = 0$ |
| $\lambda_0 = 2/R^2$ | $\lambda_g = ?$ |
| Coherence: all of $S^3$ | Coherence: $L_f \approx 13$ kpc |

In this reading, galactic coherence is the $W_g$-independence of the nested eigenvalue. The galactic cone point plays the same structural role at galactic scale that the cosmic cone point plays at cosmic scale.

**What needs to be derived:** the galactic metric coefficient $f_g$, its zeros, the Frobenius expansion at those zeros, and the full chain (steps 1-10) at galactic scale.

### Which reading?

Both may be correct at different levels. Reading A says all observers share the cosmic cone point (one band, one mode). Reading B says the structure nests (one band per scale, each with its own cone point). The Oort Cloud project's nested coherence picture (Piece B) leans toward Reading B. The question is whether Reading B requires new derivations at each scale, or whether it follows from Reading A plus the scale-free 120-grid.

---

## IV. The Budget Identity at Galactic Scale

At cosmic scale: $u_0^2 + J^2 = 1$, where $u_0 = \sin(y/R)$ and $J = \cos(y/R)$.

At the cone point ($y = \pi R/2$): $u_0 = 1$, $J = 0$. Full budget in sampling, none in transverse geometry.
At the central circle ($y = 0, \pi R$): $u_0 = 0$, $J = 1$. Full budget in geometry, none in sampling.

The budget identity holds because both $u_0$ and $J$ satisfy second-order ODEs sourced by the same constant curvature $K = 1/R^2$, and both are trigonometric functions of $y/R$.

For Reading A: the budget identity holds as written. The galactic perturbation shifts the observer's $y$-position by $\alpha_f$, changing the $u_0/J$ balance slightly, but the identity itself is unperturbed.

For Reading B: the budget identity at galactic scale requires $u_g^2 + J_g^2 = \text{const}$. This holds if $K_g$ is constant (same trigonometric solutions). If $K_g$ varies, the identity takes a different form, or may not hold as a simple sum-of-squares.

| Budget | Cone point | Central circle | Interpretation |
|--------|-----------|----------------|----------------|
| $u_0 = 1,\; J = 0$ | All sampling, no extent | | Coherence maximum: transverse positions identified |
| $u_0 = 0,\; J = 1$ | | All extent, no sampling | Coherence minimum: transverse positions maximally distinct |
| $u_0^2 + J^2 = 1$ | | | Fixed total: what the surface spends on extent, it loses in sampling |

At the galactic cone point (if it exists): all spatial positions within the galaxy are metrically identified. The galactic eigenfunction is at maximum. The transverse geometry has collapsed. This is the geometric content of the statement "observers within the galaxy measure equal $\mathbb{R}^4$ values."

---

## V. The Curvature Sourcing Problem

This is the critical open question. What sets the curvature of the galactic-scale band?

### GR tidal curvature alone does not produce a galactic cone point

The coherence domain is centered on Sagittarius A* (Sgr A*), the supermassive black hole at the galactic center ($M \approx 4 \times 10^6\,M_\odot$). The gravitational field has two regimes:

**Keplerian regime** ($r \lesssim 0.7$ pc): Sgr A* dominates. Tidal curvature $K = 2GM/(r^3 c^2)$ is strong and falls as $1/r^3$. At $r \sim 1.9$ pc, the Keplerian curvature matches $K_g$. The Jacobi equation is oscillatory; tidal focusing can produce zeros.

**Flat-curve regime** ($r \gtrsim 0.7$ pc, spanning 99.99% of $L_f$): The tidal curvature is $K(r) = v_c^2/(r^2 c^2)$. The Jacobi equation becomes Euler-type:

$$J'' + \frac{v_c^2}{r^2 c^2}\,J = 0$$

with solutions $J \sim r^p$ where $p(p-1) + v_c^2/c^2 = 0$. Since $v_c^2/c^2 \approx 5 \times 10^{-7}$, the exponents are $p \approx 0$ and $p \approx 1$. These are power laws, not oscillatory. **A power-law Jacobi field has no zero for $r > 0$.** This is not a matter of the curvature being too weak at some particular radius; the Euler-type equation is structurally non-oscillatory regardless of where it is evaluated.

### The curvature needed

If $\pi R_g = L_f = v_c^2/a_0$, then $R_g = L_f/\pi$ and:

$$K_g = \frac{1}{R_g^2} = \frac{\pi^2}{L_f^2} = \frac{\pi^2\,a_0^2}{v_c^4} \approx 6.1 \times 10^{-41}\;\text{m}^{-2}$$

This is $10^7$ times larger than $K_{\text{GR}}$. It is NOT sourced by the gravitational tidal field alone.

### Where the curvature comes from

The coherence scale $L_f = v_c^2/a_0$ sits at the interface between gravity ($v_c$) and topology ($a_0$, derived from $C(13/120)$). The curvature $K_g = \pi^2 a_0^2/v_c^4$ lives at this interface. It is neither purely gravitational nor purely topological.

| Scale | Curvature | Source | Character |
|-------|-----------|--------|-----------|
| Cosmic | $K = 1/R^2 \approx 5 \times 10^{-53}\;\text{m}^{-2}$ | Totally geodesic $S^2 \subset S^3$ | Constant; oscillatory Jacobi field |
| Galactic (needed) | $K_g \approx 6 \times 10^{-41}\;\text{m}^{-2}$ | Topology-gravity interface ($a_0$, $v_c$) | Must be constant or oscillatory |
| Sgr A* core ($r < 0.7$ pc) | $K \sim 4 \times 10^{-40}\;\text{m}^{-2}$ at 1 pc | Keplerian tidal ($2GM/r^3c^2$) | Oscillatory (tidal focusing) |
| Flat-curve ($r > 0.7$ pc) | $K = v_c^2/(r^2c^2) \sim 10^{-47}$ at 8 kpc | Galactic mass distribution | **Euler-type; power-law Jacobi field; no zeros** |

The problem is not the magnitude; it is the character. The flat rotation curve produces an Euler-type Jacobi equation whose solutions are power laws. Power laws do not oscillate and do not cross zero. The Sgr A* Keplerian core does produce oscillatory behavior, but it spans only $\sim 0.005\%$ of $L_f$. The vast bulk of the coherence domain lives in the structurally non-oscillatory regime.

This is parallel to the MOND regime: $a_0$ marks where Newtonian gravity alone fails to account for the dynamics. Here, GR tidal curvature fails not just quantitatively but qualitatively: the Jacobi equation has the wrong character (power-law instead of oscillatory) to produce a cone point within $L_f$. The topology must supply the missing structure.

The [SPARC phase field notes](sparc-phase-field-notes.md) test $L_f$ empirically across 175 galaxies. That analysis asks whether $L_f$ predicts the gravitational transition radius; this section asks why $L_f$ is the coherence scale geometrically. If the SPARC correlations hold, the curvature sourcing question sharpens: whatever sources $K_g$ must produce $L_f = v_c^2/a_0$ as a consequence.

**Assessment:** The galactic cone point (Reading B) cannot be sourced by GR curvature. It requires the topological scale $a_0$. If the 120-grid projects at every scale with constant curvature inherited from the Mobius structure (not from the gravitational field), then $K_g = \pi^2/L_f^2$ is set by the topology-gravity interface, and the cone point exists. If the curvature must be sourced purely by GR, the cone point does not exist within the galaxy, and galactic coherence must work by a different mechanism (Reading A or something else).

This is the fork. The Frobenius program (Section VI) sits on the far side of it.

---

## VI. The Frobenius Program

If the galactic cone point exists ($f_g$ vanishes at some $y_g^*$), the following must be executed with full rigor:

### Step 1: Identify the galactic metric coefficient $f_g(y_g)$

Three scenarios, ordered by assumption strength:

**Scenario A (constant curvature).** If $K_g = 1/R_g^2$ is constant, then $f_g = \cos(y_g/R_g)$. The entire Sector $\mathcal{A}$ analysis carries over with $R \to R_g$. The Frobenius expansion, limit-circle classification, Friedrichs extension, and excision are identical. The eigenvalue is $\lambda_g = 2/R_g^2 = 2\pi^2/L_f^2$. The budget identity $u_g^2 + J_g^2 = 1$ holds. This is the cleanest case but the strongest assumption.

**Scenario B (variable curvature, linear zero).** If $K_g$ varies but $f_g$ still has a simple (linear) zero at $y_g^*$, then near the zero: $f_g \sim |\delta_g|/R_{\text{eff}}$ for some effective radius $R_{\text{eff}}$. The indicial equation is still $s^2 = 0$ (double root from the linear zero of the weight). Limit-circle classification still holds. The Friedrichs extension still selects the regular branch. The excision terms still vanish as $O(\epsilon^2)$. The eigenvalue changes (no longer $2/R_g^2$) but the $W_g$-independence mechanism is preserved if the metric factors as $ds^2 = dy_g^2 + f_g^2(y_g)\,dw_g^2$.

**Scenario C (no zero, or non-linear zero).** If $f_g$ does not vanish, there is no cone point, and the coherence mechanism of Reading B fails. If $f_g$ vanishes quadratically or with higher order, the indicial exponents change and the analysis must be reworked from scratch.

### Step 2: Frobenius expansion

For Scenarios A and B, near $\delta_g = y_g - y_g^*$:

$$(|\delta_g|/R_{\text{eff}} \cdot u')' + \lambda\,|\delta_g|/R_{\text{eff}} \cdot u = 0$$

Frobenius substitution $u = |\delta_g|^s \sum a_k \delta_g^k$. Leading balance gives $s^2 = 0$.

- Regular: $u_1 = a_0 + a_2\delta_g^2 + O(\delta_g^4)$, with $a_2 = -\lambda a_0/4$
- Logarithmic: $u_2 = \log|\delta_g| + b_2\delta_g^2 + O(\delta_g^4)$

Check: are higher-order terms in the Frobenius expansion modified by $K_g$ being non-constant? If $K_g$ varies, the $a_2$ coefficient acquires corrections from the curvature gradient $K_g'$. The leading-order structure ($s^2 = 0$, two branches) is unchanged because the Frobenius expansion is local and the weight vanishes linearly regardless of the curvature profile.

### Step 3: Limit-circle classification

Both branches are $L^2$ w.r.t. weight $|\delta_g|/R_{\text{eff}}\,d\delta_g$ because:
- $u_1^2 \cdot |\delta_g| \sim |\delta_g|$ (integrable)
- $u_2^2 \cdot |\delta_g| \sim (\log|\delta_g|)^2 \cdot |\delta_g|$ (integrable)

This classification depends only on the LINEAR vanishing of the weight, not on the global curvature profile. For any metric of the form $ds^2 = dy^2 + f^2(y)\,dw^2$ where $f$ has a simple zero, the cone point is limit-circle.

### Step 4: Friedrichs extension

The Dirichlet integral distinguishes the branches:
- Regular: $(u_1')^2 |\delta_g| \sim \delta_g^2 \cdot |\delta_g| = O(|\delta_g|^3)$. Integrable.
- Logarithmic: $(u_2')^2 |\delta_g| \sim \delta_g^{-2} \cdot |\delta_g| = O(|\delta_g|^{-1})$. Divergent.

The Friedrichs extension selects the regular branch. This holds for any simple zero of $f$, regardless of the curvature profile.

### Step 5: Excision estimates

For any eigenfunction in the Friedrichs domain:
- $u = O(1)$, $u' = O(\delta_g)$, $u'' = O(1)$
- $\partial_\nu|\nabla u|^2 = 2u'u'' = O(\epsilon)$
- Arc-length of excision curve: $|f_g| \cdot 2W_g \sim (\epsilon/R_{\text{eff}}) \cdot 2W_g = O(\epsilon)$
- Product: $O(\epsilon) \cdot O(\epsilon) = O(\epsilon^2) \to 0$

This estimate depends only on the regular-branch Frobenius asymptotics and the linear vanishing of $f_g$. It holds for Scenarios A and B.

### Step 6: $W_g$-independence

The Rayleigh quotient for $w_g$-constant functions:

$$\frac{\int_0^{\pi R_g}(u')^2\,|f_g|\,dy_g \cdot 2W_g}{\int_0^{\pi R_g} u^2\,|f_g|\,dy_g \cdot 2W_g}$$

$2W_g$ cancels if and only if the metric coefficient $f_g$ depends on $y_g$ alone (no $w_g$-dependence in $f_g$). For any metric of the factored form $ds^2 = dy_g^2 + f_g^2(y_g)\,dw_g^2$, the cancellation holds. This is guaranteed by the $S^2$-type embedding structure, which forces the metric to factor.

### Step 7: Budget identity

For constant curvature (Scenario A): $u_g^2 + J_g^2 = 1$ holds by the Pythagorean identity.

For variable curvature (Scenario B): the eigenfunction $u_g$ and Jacobi field $J_g$ satisfy different ODEs ($u_g$ has the eigenvalue $\lambda_g$; $J_g$ solves $J'' + K_g J = 0$). The sum $u_g^2 + J_g^2$ is not generally constant. A Wronskian-type conservation law may replace it, but this must be derived.

---

## VII. What This Means for the Oort Cloud Project

### If Reading B holds (nested cone point exists):

The coherence boundary at each scale is $2W$ (the transverse width of that scale's Mobius band). The cone point identification guarantees $W$-independence of the eigenvalue, which guarantees coherence within the domain.

| Scale | $2W$ | Coherence domain |
|-------|------|------------------|
| Cosmic | $2\pi R$ (full $\mathbb{RP}^2$; no boundary, no deficit) | All of $S^3$ |
| Galactic | $2W_g$ | $L_f \approx 13$ kpc |
| Stellar | $2W_\odot$ | Oort Cloud $\approx 144{,}000$ AU? |

At each boundary: the dominant mode's transverse identification no longer covers the observer. The observer transitions from one mode's cone point to the next. The wave is continuous through the transition (Omega Constraint), but the witness stand changes.

This reframes Gap 1 of the Oort Cloud project: instead of asking "does $L_f = v_c^2/a_0$ generalize?" the question becomes "what sets $W$ at each scale?" The mechanism is the same ($W$-independence from cone point analysis); only the width parameter changes.

### If Reading A holds (one cone point, perturbative):

Galactic coherence follows from all observers being in the cosmic ground mode (Sector $\mathcal{A}$), with the galactic potential introducing a small perturbation in the meridional direction. The Oort Cloud project's nested structure would need a different geometric explanation than cone point nesting.

### The Oort Cloud radius

If Reading B holds and the stellar-scale Mobius band has meridional length $\pi R_\odot$, the Oort Cloud radius is $L_\odot/2 = \pi R_\odot/2$ (half the meridional length, the stellar cone point location measured from the edge). Alternatively, $2W_\odot$ (the transverse width) sets the domain, and the boundary is at $w_\odot = \pm W_\odot$ where the dominant stellar mode's potential gives way to the galactic one.

To derive the Oort Cloud radius, one would need: the stellar analog of $L_f$, or equivalently, $R_\odot$ from the stellar potential. What plays the role of $v_c$ and $a_0$ at stellar scale?

---

## VIII. Open Questions

| # | Question | Depends on | Priority |
|---|----------|-----------|----------|
| 1 | What sources $K_g$? GR tidal curvature in the flat-curve regime is Euler-type with power-law Jacobi solutions (no zeros at any radius); the Keplerian core near Sgr A* is oscillatory but spans $< 0.01\%$ of $L_f$. The topology-gravity interface ($a_0$, $v_c$) gives oscillatory solutions with a zero at $L_f/2$. What justifies constant curvature across the coherence domain? | Curvature sourcing (§V) | CRITICAL |
| 2 | Does the 120-grid force constant curvature at every scale? If yes, the cone point exists by algebraic structure, not by gravitational focusing. | Scale-free projection (Oort §Joint 2) | HIGH |
| 3 | Reading A or B? One cone point or many? | Questions 1 and 2 | HIGH |
| 4 | Variable-curvature budget identity: what replaces $u^2 + J^2 = 1$ when $K$ is not constant? | Frobenius program, Step 7 | MEDIUM |
| 5 | What sets $W_g$? The meridional length is $L_f$ (from $v_c$ and $a_0$). What sets the transverse width? | Reading B | MEDIUM |
| 6 | Perturbative stability of the cosmic cone point: does $\alpha_f \sim 10^{-6}$ spoil any step in the chain? | Reading A | LOW (almost certainly stable, but unproven) |

---

## IX. Falsification

| Prediction | Falsified if... |
|------------|-----------------|
| Nested cone point exists (Reading B) | Galactic-scale Jacobi field proved to have no zero from any curvature source |
| Frobenius structure preserved | Indicial exponents differ from $s^2 = 0$ at galactic scale (requires non-linear vanishing of $f_g$) |
| $W_g$-independence | Galactic eigenvalue shown to depend on galaxy size (different-sized galaxies measure different $\Lambda$) |
| Curvature from topology-gravity interface | $K_g$ shown to require fine-tuning rather than following from $a_0$ and $v_c$ |
| Omega Constraint | Cone point identification produces observer isolation at any scale; FATAL |

---

## X. Priorities

The curvature sourcing question (§V) is the fork. Everything else sits on one side or the other.

**Before the fork:** determine whether the 120-grid projects constant curvature at every scale (Question 2). This is an algebraic question about the Mobius structure, not a dynamical calculation. If the answer is yes, the cone point exists at every scale and the full Frobenius program (§VI) runs with known tools. If the answer is no, the curvature must be sourced by the gravitational field (which fails by a factor of $10^7$) or by the topology-gravity interface (which needs its own derivation).

**After the fork:** run the Frobenius program at galactic scale (§VI), establish or exclude $W_g$-independence, and connect to the Oort Cloud project's nested coherence picture.

The fork question is coupled to Gap 1 of the Oort Cloud project (nested $L_f$ derivation) and to the discrete snap mechanism (working file). All three ask the same thing at different levels: how does the topological structure interface with the gravitational field at sub-cosmic scales?

---

*The cone point collapses the transverse direction. The eigenvalue survives the collapse. The observers share the survival.*

---

/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`working`](../)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /
