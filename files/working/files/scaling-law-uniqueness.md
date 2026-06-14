/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`working`](../)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /

---

# The Scaling Law as Forced Measurement Postulate on S³/2I

**Status:** ACTIVE. The form is largely closed in argument. The open mechanisms are the α_W twist operator and the self-adjoint extension selection. Well assignments remain the separate next layer.

**Dependencies:** Sector A paper (first positive eigenvalue), Lemma 8 (Θ ⊥ spectral parameter), mass-spectrum paper (R determination), gauge-ladder note (coupling exponents).

---

## The Question

Given S¹ = ∂(Möbius) ↪ S³, ∂S³ = ∅, with anti-periodic boundary conditions and the 120-domain native to S³, is there any measurement rule other than

$$\frac{A}{A_P} = C(\Theta) \cdot (\sqrt{\Omega})^{-n}$$

that produces finite, well-defined observables?

If not, the scaling law is forced by the topology. Not derived from it in the usual sense. Forced by it, the way Born's rule is forced by Hilbert space structure (Gleason's theorem).

---

## What This Session Closed

The proof splits, and the form mostly closes. The factored structure, the phase operator, and the integer-depth hierarchy reduce to three transparent results. The heavy machinery once aimed at the hierarchy addresses a target that dimensional analysis already settles.

| Piece | Status | Mechanism |
|---|---|---|
| Factored form C(Θ) × g(Ω, n) | Argument identified, one link pending | Schur decoupling gives Θ ⊥ spectral parameter s (Lemma 8). The factorization needs Θ ⊥ (Ω, n). Connecting the spectral parameter to the depth index is the remaining step. |
| Phase operator C(Θ) = 2sin²(πΘ) | DERIVED | The anti-periodic mode intensity at any Θ. One operator across sectors: cosmology samples a single well, the mass sector samples Kostant exponent sets. |
| Integer-depth hierarchy (√Ω)^(−n) | DERIVED (units) | Dimensional analysis. n is the length-dimension of the observable, R/ℓ_P is the only scale ratio, √Ω = R/ℓ_P. Form and base both follow from dimensions. |
| Coupling exponents (1/60, 1/120) | ESTABLISHED | The grid ladder selection rule sets the grid per coupling, and the exponent is 1/\|grid\|. α_EM closed via convergent paths and Lemma 8; α_s established. Units stay silent here, since the couplings are dimensionless, so the ladder rule supplies the exponent that dimensions cannot. |
| α_W twist, cos(π/10) | MOTIVATED | The one injected multiplicative factor. Dodecahedron angular defect π/5, halved by the ℤ₂ holonomy to π/10. The operator-level mechanism from holonomy to projection is the open link. |
| Self-adjoint extension | OPEN | Friedrichs keeps the zero mode as the m_h = 0 background. The selection rule is pending, via the smoothed-cone limit in the companion eigenvalue paper. |

The form is forced in the first three rows. The coupling exponents follow from the ladder rule, with units staying silent because the couplings carry no dimension. The two genuinely open mechanisms are the α_W twist and the extension selection. The "61 orders from topology" reads honestly as R/ℓ_P ≈ 10⁶¹ given a calibrated R. The powers of ten are units. The physics is the dimensionless coefficient C(Θ).

---

**Note on calibration vs form.** The engine file writes the scaling law with $\approx$, reflecting that the kinematic identification of $\Omega$ with a physical quantity (e.g., $\Omega_H = (c/(H\ell_P))^2$ for edge modes) is approximate: the hierarchy normalization is fixed by calibrating through one measured anchor per sector ($H_0$ for edge modes, measured $\Lambda$ for surface and space modes, the mass-sector normalization for fermions).

The surface radius $R$ enters as the geometric parameter in the first positive eigenvalue $\lambda = 2/R^2$, and it is not yet fixed independently. The reason is structural, and it is the same reason the Yang-Mills gaps cannot fix it. Every observable is the single product $C(\Theta)\cdot(\sqrt{\Omega})^{-n}$, so one observable gives one equation, and $R$ reads out only as $R$-given-the-assumed-$C$. $R$ separates only when two observables share it at different powers. Same-power families return $R$-free ratios and nothing more: the Yang-Mills gaps live at $1/R^2$, $\Lambda$ lives at $1/R^2$, and within each the scale divides out. The mass spectrum is the one family carrying different powers, through the McKay elevator $(\sqrt{\Omega_\Lambda})^{\,\mathrm{dist}/30}$: the electron and muon sit at different McKay distances, so the same $R$ appears at two exponents, two equations, $R$ overdetermined. That is the route from calibration to forward prediction, and it is the mass-spectrum paper's open item.

The uniqueness question addressed here is about the *functional form* $C(\Theta) \times g(\Omega, n)$, separate from calibration.

---

## The Precedent: Gleason's Theorem

Gleason (1957) proved that on a Hilbert space of dimension ≥ 3, the only probability measure consistent with the lattice of projections is the Born rule: p = |⟨ψ|φ⟩|². The theorem doesn't derive Born from dynamics. It shows Born is the unique measure compatible with the structure.

The MIT analog: show that C(Θ) × (√Ω)⁻ⁿ is the unique sampling rule compatible with the bounded, closed topology of S¹ = ∂M ↪ S³, ∂S³ = ∅.

---

## The Constraints and What They Eliminate

| # | Constraint | Source | What it eliminates |
|---|-----------|--------|-------------------|
| 1 | Anti-periodic BC: ψ(y+L) = -ψ(y) | Möbius non-orientability (AXIOM) | All non-sinusoidal phase operators. The mode intensity is sin²(πΘ). No polynomial, exponential, or rational alternative survives the BC. |
| 2 | Bounded domain: ∂S³ = ∅ | Poincaré (THEOREM) | Any hierarchy that fails to terminate. Ω is finite. The dilution is a function of a finite ratio, not an asymptotic series. |
| 3 | Discrete 120-domain: \|2I\| = 120 | Largest exceptional discrete subgroup of SU(2) (THEOREM) | Continuous sampling rules. Phase positions are quantized to multiples of 1/120. |
| 4 | Observer at √Ω | IR↔UV fixed point on bounded domain (DERIVED) | Any other normalization point. The geometric midpoint is unique: x = Ω/x has one positive solution. |
| 5 | Dimensionless output | A/Aₚ is a ratio | Additive forms like C + Ω⁻ⁿ. A dimensionless ratio requires a multiplicative decomposition of dimensionless factors. |
| 6 | Factorization into position and depth | Schur decoupling: Lemma 8 gives Θ ⊥ s; the link to Θ ⊥ (Ω, n) is the pending step | Mixed forms like C(Θ, Ω). Phase and spectral data occupy different blocks of the decomposition. Once the depth index is shown to ride the spectral block, the rule separates. |

---

## The Argument Shape

**Step 1:** Establish the space of candidate measurement rules.

Any rule maps (phase position Θ, manifold depth n, hierarchy Ω) to a dimensionless observable ratio. The output space is ℝ⁺. The input space is {Θ ∈ k/120} × {n ∈ ℤ or ℤ/2} × {Ω ∈ ℝ⁺, finite}.

**Step 2:** Apply constraint 5. A dimensionless output from dimensionless inputs requires a product of dimensionless functions:

$$\frac{A}{A_P} = f(\Theta) \cdot g(\Omega, n)$$

Constraint 6 (Schur decoupling) supplies the factored form, pending the link from the spectral parameter to the depth index.

**Step 3:** Apply constraint 1. f(Θ) satisfies the anti-periodic BC. The anti-periodic mode intensity on the Möbius strip is 2sin²(πΘ) at any Θ. This is one operator read at different positions: cosmology samples a single well, the mass sector samples Kostant exponent sets. The sinusoidal form is the only L² intensity the BC admits, so f(Θ) = C(Θ) = 2sin²(πΘ) across all sectors.

**Step 4:** Apply constraints 2 and 4. g(Ω, n) encodes dilution from Planck to observation on a bounded domain. Ω is the hierarchy ratio, finite by constraint 2; the observer sits at √Ω by constraint 4; n counts depth. Step 5 fixes the function.

**Step 5, resolved for integer depth.** Read n as the length-dimension of the observable. Λ is 1/length² (n = 2), H₀ and a₀ are 1/length (n = 1). An observable normalized to its Planck value is the ratio of its natural scale R⁻ⁿ to its Planck scale ℓ_P⁻ⁿ, which is (ℓ_P/R)ⁿ = (R/ℓ_P)⁻ⁿ = (√Ω)⁻ⁿ. Form and base both follow from dimensions: dimensions multiply, so depth adds and the dilution is a power; R is the only scale, so the base is R/ℓ_P. Constraint 2 keeps Ω finite so the ratio is well-defined, and constraint 4 is the geometric reading of R/ℓ_P as the observer's scale, the same number the dimensions deliver. This closes the integer-depth case without the rigidity machinery below.

**Step 5, the coupling exponents.** A dimensionless coupling has length-dimension 0, so dimensions fix no Ω dependence. The exponent the couplings do carry, 1/60 for EM and 1/120 for the strong and weak forces, comes from the grid ladder selection rule: the carrier character sets the phase grid, the confinement target sets the exponent grid, and the exponent is one cell of that grid, 1/\|grid\|. The ladder rule is ESTABLISHED, α_EM closed through two convergent paths and Lemma 8, α_s established. So the exponents are supplied, not open. What this paper's standard adds is lifting the ladder rule from established to forced, which is the live target for the representation-theoretic route below.

---

## What the Residual Requires

The integer-depth rigidity is units, and the coupling exponents come from the ladder rule, so the heavy approaches below come off both. They are kept for the record, and because the representation-theoretic row is the candidate for lifting the ladder rule from established to forced.

| Approach | Idea | Status |
|----------|------|--------|
| Volume scaling | The ratio of n-dimensional volumes at scale √Ω vs scale Ω is (√Ω)⁻ⁿ. | RETIRED. Units settle the integer case. |
| Spectral | Eigenvalue spacing at depth n scales as Ω⁻ⁿ/². | RETIRED for the integer case. |
| Information-theoretic | The observer at √Ω has ½ log Ω bits per dimension; depth n gives n × ½ log Ω. | RETIRED for the integer case. |
| Representation-theoretic | The Peter-Weyl decomposition on S³/2I organizes modes by spin j; Casimir scaling under the 2I quotient sets the amplitude. | LIVE. Candidate route to lift the ladder rule from established to forced, by deriving 1/\|grid\| from the Casimir under the quotient. |
| Selberg trace formula | Eigenvalue sums equal geodesic sums, with geodesics fixed by the 9 conjugacy classes of 2I. | RETIRED for the integer case. Possibly relevant to the representation-theoretic route. See note below. |

The two open mechanisms sit outside this table. The α_W twist needs an operator-level derivation from the ℤ₂ holonomy to a multiplicative projection. The self-adjoint extension needs a selection rule, expected from the smoothed-cone limit.

---

## What This Paper Would Establish

The form is the unique measurement postulate compatible with S¹ = ∂M ↪ S³, ∂S³ = ∅, with anti-periodic BC and the 120-domain: the factored structure (Schur), the phase operator (anti-periodic intensity), and the integer-depth hierarchy (units). For these, the audit verdict moves from DECLARED to AXIOM (forced). Everything downstream that rides the integer hierarchy inherits that upgrade.

What stays as work: the α_W twist mechanism and the extension selection, both stated precisely enough to attack directly. The well assignments, manifold indices, and grid types remain the next layer, the traffic rules on the bridge, with "why 13 is the exponent floor" the load-bearing item there. Lifting the ladder rule from established to forced belongs to that layer too.

---

## Note: The Selberg Merge

The spectral approach and the representation-theoretic approach may not be independent. The Selberg trace formula equates sums over eigenvalues to sums over geodesics, with geodesics fixed by conjugacy classes of the fundamental group. On S³/2I the fundamental group is 2I, with 9 conjugacy classes and geodesic lengths fixed by group structure. Peter-Weyl gives the eigenvalues; Selberg locks them to the geodesic lengths.

This was flagged as the unifying rigidity for the hierarchy. With the integer hierarchy settled by units and the coupling exponents supplied by the ladder rule, the formula's possible role narrows to the representation-theoretic route, if the finite geodesic-length set turns out to fix the 1/\|grid\| scaling. That connection is unproven and speculative.

**Source:** The Selberg connection was flagged during review of Schepis, *Observer-Resonance Theory* (2026), Ch. F §3.3-3.4. Schepis identifies the Selberg trace formula as the structural analog of the Euler product for bounded manifolds and cites Connes' spectral triples matching zeta zeros at 10⁻⁵⁵ precision using primes ≤ 13. He does not apply the formula to any specific manifold. The application to S³/2I is new.

---

## A Consequence: Why the Propagator Correction Had to Fail

The composition reading of depth (dilution multiplies across layers, so the depth function is a power) explains, after the fact, why the McKay propagator correction failed empirically. A path-product correction is not depth-only, so it falls outside the forced form. The data agreed: the down quark overshot and the tau undershot, in opposite directions, which is the signature of a correction pulling against a structure that was already fixed. The negative result is now expected rather than puzzling.

---

## Relationship to Existing Papers

| Paper | What it establishes | What this paper adds |
|-------|--------------------|--------------------|
| Sector A (eigenvalue) | First positive eigenvalue 2/R² on Möbius in S³; the ground state is the extension-dependent zero mode | That paper gives the eigenvalue. This paper shows the rule that reads it is unique. |
| Lemma 8 | Θ decouples from the spectral parameter s | The same Schur mechanism supplies constraint 6, once the depth index is connected to the spectral block. |
| Mass spectrum | Fermion masses via torsion × C_geom × McKay elevator | Supplies the only route to an independent R (electron and muon at different McKay distances), and hosts the R-determination open item. |
| Gauge ladder | Coupling exponents from carrier and confinement character | Supplies the 1/60 and 1/120 exponents. This paper would lift that rule from established to forced. |
| Scaling Law (this paper) | Uniqueness of the sampling rule | Completes the triad: eigenvalue, boundary, measurement. |

---

## Notes

The strongest version of this result shows the scaling law is the ONLY measurement rule, not merely the simplest. The form reaches that bar: the factored structure, the phase operator, and the integer hierarchy are forced, by Schur, by the anti-periodic BC, and by units. Simplicity never entered.

The honest deflation that came with closing the integer hierarchy: the apparent miracle of "many orders of magnitude from topology" is units. R/ℓ_P is a calibrated ratio, and raising it to the observable's dimension is dimensional analysis. The genuine content sits in C(Θ), and the coupling exponents sit in the ladder rule that units do not reach. Naming this plainly is what lets the open mechanisms stand out as the real work.

---

*"The topology leaves no room for anything else" is now true for the form, established for the coupling exponents, and a precise open question for the two mechanisms.*

---

/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`working`](../)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /
