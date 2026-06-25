/ **[`main`](../../../../README.md)** / **[`framework`](../../../framework/)** / **[`working`](../)** / **[`cosmos`](../../../cosmos/)** / **[`spectrum`](../../../spectrum/)** /

---

# The Scaling Law as Forced Measurement Postulate on S³/2I

**Status:** ACTIVE. All three structural pieces of the form are forced: the phase operator by the anti-periodic BC, the integer-depth hierarchy by units, and the factored form by the Schur separation (Lemma 8 + homothety reduction + sector independence; [Proof](#proof-the-schur-separation)). The factored form carries two named, scale-invariant conditions, both met by the Friedrichs default: a parity-preserving cone condition and δ₀/R > 2/e. The remaining open mechanisms, the α_W twist operator and the self-adjoint extension selection, are off the form: neither alters C(Θ) or reintroduces a cross-term. Well assignments remain the separate next layer.

**Dependencies:** Sector A paper (first positive eigenvalue), Lemma 8 (Θ ⊥ spectral parameter), mass-spectrum paper (R determination), gauge-ladder note (coupling exponents).

---

## The Question

Given S¹ = ∂(Möbius) ↪ S³, ∂S³ = ∅, with anti-periodic boundary conditions and the 120-domain native to S³, is there any measurement rule other than

$$\frac{A}{A_P} = C(\Theta) \cdot (\sqrt{\Omega})^{-n}$$

that produces finite, well-defined observables?

If not, the scaling law is forced by the topology. Not derived from it in the usual sense. Forced by it, the way Born's rule is forced by Hilbert space structure (Gleason's theorem).

---

## What's Closed

The proof splits into three structural pieces, and all three close. The phase operator and the integer-depth hierarchy reduce to transparent results (anti-periodic BC; dimensional analysis). The third, the factored form, follows from the Schur separation (Lemma 8 + homothety reduction; dimensionlessness does not supply it), proved below. The heavy machinery once aimed at the hierarchy addresses a target that dimensional analysis already settles.

| Piece | Status | Mechanism |
|---|---|---|
| Factored form C(Θ) × g(Ω, n) | FORCED (Schur + homothety + sector independence) | Dimensionlessness does not force a product (additive/mixed forms survive constraint 5); Lemma 8 supplies the separation once the homothety reduction makes (Ω, n) spectral-block data, and C(Θ) is the extension-independent symmetric mode, so δ₀ never reaches it. Conditions: parity-preserving cone, δ₀/R > 2/e (Friedrichs). See [Proof](#proof-the-schur-separation). |
| Phase operator C(Θ) = 2sin²(πΘ) | DERIVED | The anti-periodic mode intensity at any Θ. One operator across sectors: cosmology samples a single well, the mass sector samples Kostant exponent sets. |
| Integer-depth hierarchy (√Ω)^(−n) | DERIVED (units) | Dimensional analysis. n is the length-dimension of the observable, R/ℓ_P is the only scale ratio, √Ω = R/ℓ_P. Form and base both follow from dimensions. |
| Coupling exponents (1/60, 1/120) | ESTABLISHED | The grid ladder selection rule sets the grid per coupling, and the exponent is 1/\|grid\|. α_EM closed via convergent paths and Lemma 8; α_s established. Units stay silent here, since the couplings are dimensionless, so the ladder rule supplies the exponent that dimensions cannot. |
| α_W twist, cos(π/10) | MOTIVATED | The one injected multiplicative factor. Dodecahedron angular defect π/5, halved by the ℤ₂ holonomy to π/10. The operator-level mechanism from holonomy to projection is the open link. |
| Self-adjoint extension | OPEN | Friedrichs keeps the zero mode as the m_h = 0 background. The selection rule is pending, via the smoothed-cone limit in the companion eigenvalue paper. |

The two genuinely open mechanisms, the α_W twist and the extension selection, are off the form: neither can alter C(Θ) or reintroduce a cross-term. (The deflation that came with the integer row, "61 orders from topology" is units, is in the closing Notes.)

---

**Note on calibration vs form.** The engine file writes the scaling law with $\approx$, reflecting that the kinematic identification of $\Omega$ with a physical quantity (e.g., $\Omega_H = (c/(H\ell_P))^2$ for edge modes) is approximate: the hierarchy normalization is fixed by calibrating through one measured anchor per sector ($H_0$ for edge modes, measured $\Lambda$ for surface and space modes, the mass-sector normalization for fermions).

The surface radius $R$ enters as the geometric parameter in the first positive eigenvalue $\lambda = 2/R^2$, and it is not yet fixed independently. The reason is structural, and it is the same reason the Yang-Mills gaps cannot fix it. Every observable is the single product $C(\Theta)\cdot(\sqrt{\Omega})^{-n}$, so one observable gives one equation, and $R$ reads out only as $R$-given-the-assumed-<i>C</i>. $R$ separates only when two observables share it at different powers. Same-power families return $R$-free ratios and nothing more: the Yang-Mills gaps live at $1/R^2$, $\Lambda$ lives at $1/R^2$, and within each the scale divides out. The mass spectrum is the one family carrying different powers, through the McKay elevator $(\sqrt{\Omega_\Lambda})^{\,\mathrm{dist}/30}$: the electron and muon sit at different McKay distances, so the same $R$ appears at two exponents, two equations, $R$ overdetermined. That is the route from calibration to forward prediction, and it is the mass-spectrum paper's open item.

The uniqueness question addressed here is about the *functional form* $C(\Theta) \times g(\Omega, n)$, separate from calibration.

---

## The Precedent: Gleason's Theorem

Gleason (1957) proved that on a Hilbert space of dimension ≥ 3, the only probability measure consistent with the lattice of projections is the Born rule: p = |⟨ψ|φ⟩|². The theorem doesn't derive Born from dynamics. It shows Born is the unique measure compatible with the structure.

The MIT analog: show that C(Θ) × (√Ω)⁻ⁿ is the unique sampling rule compatible with the bounded, closed topology of S¹ = ∂M ↪ S³, ∂S³ = ∅.

The precedent is exact for one piece only. C(Θ) is a normalized mode intensity (∫₀¹ C dΘ = 1), so a Gleason-type measure-uniqueness statement is the right tool there. The hierarchy (√Ω)⁻ⁿ is dimensional analysis (Buckingham π), not a measure; the factored form is a separation-of-variables result (the Schur separation, proved below). The three rows are three different rigidity claims of three different types, and only the phase operator is Gleason-shaped; this note keeps them separate rather than letting one banner blur the kinds of argument. All three are now forced, each by its own mechanism.

---

## The Constraints and What They Eliminate

| # | Constraint | Source | What it eliminates |
|---|-----------|--------|-------------------|
| 1 | Anti-periodic BC: ψ(y+L) = -ψ(y) | Möbius non-orientability (AXIOM) | All non-sinusoidal phase operators. The mode intensity is sin²(πΘ). No polynomial, exponential, or rational alternative survives the BC. |
| 2 | Bounded domain: ∂S³ = ∅ | Poincaré (THEOREM) | Any hierarchy that fails to terminate. Ω is finite. The dilution is a function of a finite ratio, not an asymptotic series. |
| 3 | Discrete 120-domain: \|2I\| = 120 | Largest exceptional discrete subgroup of SU(2) (THEOREM) | Continuous sampling rules. Phase positions are quantized to multiples of 1/120. |
| 4 | Observer at √Ω | IR↔UV fixed point on bounded domain (DERIVED) | Any other normalization point. The geometric midpoint is unique: x = Ω/x has one positive solution. |
| 5 | Dimensionless output | A/Aₚ is a ratio | Leftover units only. A dimensionless output removes dimensionful candidates; it does NOT force a multiplicative split. Additive and mixed dimensionless forms (C + Ω⁻ⁿ, or C·Ω⁻ⁿ + h(Θ, Ω)) all survive this constraint. The factorization is not delivered here; it comes, if at all, from constraint 6. |
| 6 | Factorization into position and depth | Schur decoupling: Lemma 8 gives Θ ⊥ s; the link to Θ ⊥ (Ω, n) is proved | This is the *only* source of the factored form (constraint 5 does not supply it). Phase and spectral data occupy different blocks of the decomposition; the depth index rides the spectral block via the homothety reduction ([Proof](#proof-the-schur-separation)), so the rule separates. |

---

## The Argument Shape

**Step 1:** Establish the space of candidate measurement rules.

Any rule maps (phase position Θ, manifold depth n, hierarchy Ω) to a dimensionless observable ratio. The output space is ℝ⁺. The input space is {Θ ∈ k/120} × {n ∈ ℤ or ℤ/2} × {Ω ∈ ℝ⁺, finite}.

**Step 2:** Constraint 5 narrows the output but does not factor it. A dimensionless output from dimensionless inputs need not be a product: $f(\Theta) + g(\Omega, n)$ and $f(\Theta)g(\Omega, n) + h(\Theta, \Omega)$ are equally dimensionless. The factored form

$$\frac{A}{A_P} = f(\Theta) \cdot g(\Omega, n)$$

is supplied only by constraint 6 (Schur decoupling), and only if Θ ⊥ s extends to Θ ⊥ (Ω, n). That extension is proved below ([Proof](#proof-the-schur-separation)) via the homothety reduction, so the factorization is a result, not an assumption.

**Step 3:** Apply constraint 1. f(Θ) satisfies the anti-periodic BC, whose eigenfunctions are trigonometric: the BC kills every polynomial, exponential, or rational candidate and admits the tower 2sin²((2m+1)πΘ). The constant zero mode is the extension-dependent background (the spatial-eigenvalue ground, distinct from the temporal harmonic ground of the cosmic wave) and carries no phase structure. The BC fixes the family but not the member; the member is selected physically. For background observables, isotropy and orthogonality exclude the higher harmonics, the same conditions that fix the cosmic background wave, leaving the lowest nonconstant mode, the first-positive eigenmode at 2/R², whose intensity is 2sin²(πΘ). So f(Θ) = C(Θ) = 2sin²(πΘ) is the first-positive-mode intensity, not the constant zero mode. This is one operator read at different positions: cosmology samples a single well, the mass sector samples Kostant exponent sets on the same mode. Two inputs enter here that the BC alone does not give: the harmonic selection (isotropy + orthogonality, for background observables) and the normalization (∫₀¹ C dΘ = 1 fixes the leading 2). Both are selection principles and should be named, not absorbed into "the BC forces it."

**Step 4:** Apply constraints 2 and 4. g(Ω, n) encodes dilution from Planck to observation on a bounded domain. Ω is the hierarchy ratio, finite by constraint 2; the observer sits at √Ω by constraint 4; n counts depth. Step 5 fixes the function.

**Step 5, resolved for integer depth.** Read n as the length-dimension of the observable. Λ is 1/length² (n = 2), H₀ and a₀ are 1/length (n = 1). An observable normalized to its Planck value is the ratio of its natural scale R⁻ⁿ to its Planck scale ℓ_P⁻ⁿ, which is (ℓ_P/R)ⁿ = (R/ℓ_P)⁻ⁿ = (√Ω)⁻ⁿ. Form and base both follow from dimensions: dimensions multiply, so depth adds and the dilution is a power; the geometric R is the scale, so the base is R/ℓ_P. Constraint 2 keeps Ω finite so the ratio is well-defined, and constraint 4 is the geometric reading of R/ℓ_P as the observer's scale, the same number the dimensions deliver. This closes the integer-depth case without the rigidity machinery below.

**Scope: one scale or two.** The "R is the only scale" reading holds for surface and space modes, which dilute from the geometric curvature radius R via Ω_Λ = (R/ℓ_P)². Edge modes do not: they reference the kinematic horizon, Ω_H = (c/Hℓ_P)², so their base is c/H, not the geometric R. The two coincide only through Ω_H ≈ Ω_Λ at the present epoch, which the framework records as an observed coincidence, not a derived identity (see [calibration-structure.md](calibration-structure.md)). So units force the *form* (√Ω)⁻ⁿ in every sector, but the *identification* √Ω = R/ℓ_P is a surface/space statement; for edge modes √Ω = c/(Hℓ_P) is a separate anchor. Deriving Ω_H = Ω_Λ would collapse the two and turn Λ (n = 2) and H₀ (n = 1) into a second route to R, alongside the mass sector.

**Step 5, the coupling exponents.** A dimensionless coupling has length-dimension 0, so dimensions fix no Ω dependence. The exponent the couplings do carry, 1/60 for EM and 1/120 for the strong and weak forces, comes from the grid ladder selection rule: the carrier character sets the phase grid, the confinement target sets the exponent grid, and the exponent is one cell of that grid, 1/\|grid\|. The ladder rule is ESTABLISHED, α_EM closed through two convergent paths and Lemma 8, α_s established. So the exponents are supplied, not open. What this paper's standard adds is lifting the ladder rule from established to forced, which is the live target for the representation-theoretic route below.

---

## Audit: n as length-dimension vs manifold index

Step 5 reads n as the observable's length-dimension; the engine's selection rule (framework/README.md, "Manifold Index") reads n as the manifold the mode lives on (edge / surface / space). These are two different rules. They agree exactly on the dimensionful dilution sector and diverge everywhere else, so the manifold rule is not redundant with dimensional analysis: it is needed for the rows units cannot reach.

| Observable | length-dimension | manifold index n | agree? | governing rule |
|---|---|---|---|---|
| H₀ | −1 (rate, via c) | 1 (edge) | yes | units = manifold |
| a₀ | −1 (acceleration, via c) | 1 (edge) | yes | units = manifold |
| Λ | −2 | 2 (surface) | yes | units = manifold |
| null dark-matter detection | −3 (number density) | 3 (space) | yes, if the observable is a 1/length³ density | units = manifold; observable to be pinned |
| G | nonzero (defines ℓ_P) | 0 (Planck floor) | NO | Planck anchor: A/A_P = 1 by construction, not by length-dimension |
| Λ_obs/Λ_top = 3/2 | 0 (ratio) | 3/2 (Gauss) | NO | Gauss-Codazzi conversion, not a dilution exponent |
| α, α_s, α_W | 0 | fractional (1/60, 1/120) | NO | grid ladder, not units |

**Verdict.** n_(length-dim) = n_(manifold) on the dimensionful dilution observables (edge + surface + space), and only there. Three rows sit outside the identity: G is the Planck-defining anchor (ratio 1, n = 0 by construction, not because its length-dimension is 0); the 3/2 row is a Gauss-Codazzi conversion factor, not a dilution; the couplings carry length-dimension 0 yet pick up fractional exponents from the ladder. The units argument of Step 5 therefore legitimately closes the dilution sector and only the dilution sector; the manifold and ladder rules carry the rest. This is consistent with the note's own split between Step 5 (integer depth) and the coupling exponents; the table adds G and the 3/2 conversion as the two further exceptions.

---

## Proof: the Schur Separation

*Supplies constraint 6 and promotes the factored form to forced. The hypotheses are stated in the Proposition; the load-bearing one is discharged at the end.*

The factored form was the one structural row left open. Dimensionlessness does not separate Θ from (Ω, n), and Lemma 8 separates Θ only from the spectral parameter s. The gap is the step from Θ ⊥ s to Θ ⊥ (Ω, n). It closes once (Ω, n) is recognized as spectral-block data: the metric scale R entering the eigenvalues, nothing more.

**Proposition.** Let A be an admissible observable: a quantity built SU(2)-equivariantly from the Hodge-Laplace spectral data of S³/2I and the first-positive anti-periodic mode on the Möbius boundary S¹, under a parity-preserving self-adjoint extension with δ₀/R > 2/e (the Friedrichs default included). Then A/A_P = C(Θ) · g(Ω, n) with no cross-term, where C(Θ) = 2sin²(πΘ) is the boundary-phase factor and g(Ω, n) the scale-and-depth factor.

**Step A, positional reduction.** By Peter-Weyl, sections of a natural bundle split into SU(2)-isotypic blocks V_l; by Schur any admissible operator is scalar a(l) on each block (the spectral-zeta reduction, the-mirror Step 2). On the bulk S³/2I the right-SU(2) action is transitive, so no continuous bulk position survives (the S³/2I half of Lemma 8: the twisted heat kernel is constant on each fiber diagonal). The only continuous positional coordinate left in A is the Möbius boundary phase Θ.

**Step B, scale reduction.** The round metric of radius R is R² times the unit metric, so the Hodge Laplacian scales as R⁻² and a_R(l) = â(l)/R², with the unit-radius eigenspaces and their internal bases R-independent. The whole (Ω, n) dependence is therefore carried by the scalar weights a_R(l): Ω = (R/ℓ_P)² is their common scale, and n is the homothety weight, the power of R the observable carries (its length-dimension). On the spectral zeta this reads as Z(s) ↦ λ²ˢ Z(s) under R ↦ λR: a pure s-power, staying inside the spectral block, never touching the eigenspace basis where Θ lives. This is the precise sense in which the depth index rides the spectral block.

**Step C, separation.** Extract the homothety weight: A/A_P = (√Ω)⁻ⁿ · K, where K is the R-invariant coefficient. K depends on Θ (positional) and on R-invariant spectral data (eigenvalue ratios, multiplicities, the bundle label n). Lemma 8 proves Θ ⊥ s for the zeta *parameter*; the upgrade to Θ ⊥ (all spectral-block data) is a zeta-completeness step. The spectral zeta Z(s) = Σ_l m(σ, l)(2l+1) a(l)⁻ˢ is a complete invariant of the eigenvalue-multiplicity data, so its proven Θ-independence is the Θ-independence of every a(l) and m(σ, l), hence of all eigenvalue ratios and multiplicities; the bundle label n is discrete (it names which spectral problem, not where within it), so it too is Θ-blind. There is therefore no natural map between Θ and any spectral-block datum, K carries no Θ-spectral cross-term, and it splits as C(Θ) · F(n). Hence

$$\frac{A}{A_P} = C(\Theta) \cdot [F(n)(\sqrt{\Omega})^{-n}] = C(\Theta) \cdot g(\Omega, n).$$

A would-be cross-term h(Θ, Ω) is exactly a Θ-spectral coupling, which Lemma 8 forbids. ∎

**What dimensionlessness could not do, Lemma 8 does.** Constraint 5 leaves h(Θ, Ω) alive because it is dimensionless; Lemma 8 kills it because it is a Θ-spectral map. The factorization rests on spectral inaccessibility, not on units, which is why the form is forced here and not at Step 2.

**Scope: dimensionful observables and couplings.** Steps B and C extract n as a length-dimension, the dimensionful case (H₀, a₀, Λ). Dimensionless couplings have n = 0, so the homothety weight is trivial and their Ω-dependence is not a length-dimension; it is the grid exponent 1/\|grid\| from the ladder rule. But that exponent is 2I representation data (the grid is the \|I\| = 60 or \|2I\| = 120 image), which is spectral-block data, and C(Θ) at the coupling wells is the same boundary phase operator. So the separation argument applies verbatim with the spectral block now supplying a fractional weight: K still splits as C(Θ) · F, with F carrying Ω^(−1/\|grid\|). The factored form holds in both sectors; only the source of the exponent differs (length-dimension for dimensionful observables, the grid for couplings), and both sources live in the spectral block, so both are Θ-blind by the same zeta-completeness step.

**The load-bearing assumption, discharged by the eigenvalue paper.** Step B needs the boundary profile sin(πΘ) to be R-independent. [first-eigenvalue.md](../../bedrock/first-eigenvalue.md) supplies this directly, and answers the ε/R question two ways.

First, the renormalization length δ₀ (the ε of the smoothed cone) enters the spectrum only through the dimensionless ratio δ₀/R: the bridging secular condition is G(λ) = ln(δ₀/2R) with G a function of the dimensionless degree ν alone (§4.4), and the robustness threshold is δ₀ > 2R/e (Prop 4.4), both functions of δ₀/R. No absolute length enters the secular data. The one absolute-length object, the bound state λ_b ≈ −4e⁻²ᵞ/δ₀², is the antisymmetric ground state, which §7 names an extension artifact, not an intrinsic invariant.

Second, and decisively, C(Θ) does not depend on δ₀ at all. It is built from the first-positive mode, which is the *symmetric* zonal mode sin(y/R) = sin(πΘ) at 2/R² (§4.2), and the symmetric tower is shared by the parity-preserving extensions (Friedrichs and the bridging family); δ₀ deforms only the *antisymmetric* sector (Prop 4.4, Thm 5.1). So for these extensions the covariance of the phase profile is a theorem, not an assumption: sin(πΘ) is the explicit Legendre mode, manifestly R-independent, with eigenvalue 2/R² scaling as 1/R². Two scale-invariant conditions bound the discharge, and both are named rather than assumed: (i) the cone condition is parity-preserving, since a parity-mixing (Robin-type) condition *can* deform the symmetric subsector (Thm 5.1 claims the symmetric tower's robustness only for Friedrichs and bridging, and its proof notes a general cone condition is not claimed robust); and (ii) δ₀/R > 2/e, below which the first-positive mode becomes the δ₀-dependent antisymmetric root and the profile would change. Friedrichs, the framework's default, is parity-preserving and sits at the δ₀ → ∞ end, so it satisfies both automatically.

**This decouples the factorization from the extension selection.** The factorization does not wait on which extension is chosen: C(Θ) is the same symmetric mode across the whole admissible regime, and the extension question governs only the ground state, which the factorization never samples.

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

The form is the unique measurement postulate compatible with S¹ = ∂M ↪ S³, ∂S³ = ∅, with anti-periodic BC and the 120-domain. All three pieces reach that bar: the phase operator (anti-periodic intensity, with the harmonic selection (isotropy + orthogonality) and normalization named), the integer-depth hierarchy (units, on the dilution sector), and the factored structure (the Schur separation, constraint 6). For these the audit verdict moves from DECLARED to AXIOM (forced), and everything downstream that rides the form inherits that upgrade.

What stays as work: the α_W twist mechanism and the extension selection, both off the form and both stated precisely enough to attack directly. The well assignments, manifold indices, and grid types remain the next layer, the traffic rules on the bridge, with "why 13 is the exponent floor" the load-bearing item there. Lifting the ladder rule from established to forced belongs to that layer too.

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
| Lemma 8 | Θ decouples from the spectral parameter s | The same Schur mechanism supplies constraint 6: the depth index is connected to the spectral block by the homothety reduction (proved here), extending Θ ⊥ s to Θ ⊥ (Ω, n). |
| Mass spectrum | Fermion masses via torsion × C_geom × McKay elevator | Supplies the only route to an independent R (electron and muon at different McKay distances), and hosts the R-determination open item. |
| Gauge ladder | Coupling exponents from carrier and confinement character | Supplies the 1/60 and 1/120 exponents. This paper would lift that rule from established to forced. |
| Scaling Law (this paper) | Uniqueness of the sampling rule | Completes the triad: eigenvalue, boundary, measurement. |

---

## Notes

The strongest version of this result would show the scaling law is the ONLY measurement rule, not merely the simplest. All three of its pieces reach that bar: the phase operator and the integer hierarchy by the anti-periodic BC and by units, and the factored structure by the Schur separation, with dimensionlessness explicitly not standing in for it. Simplicity never entered.

The honest deflation that came with closing the integer hierarchy: the apparent miracle of "many orders of magnitude from topology" is units. R/ℓ_P is a calibrated ratio, and raising it to the observable's dimension is dimensional analysis. The genuine content sits in C(Θ), and the coupling exponents sit in the ladder rule that units do not reach. Naming this plainly is what lets the open mechanisms stand out as the real work.

---

*"The topology leaves no room for anything else" is now true for the phase operator, the integer-depth hierarchy, and the factorization (the Schur separation), established for the coupling exponents, and a precise open question for the α_W twist and the extension selection.*

---

/ **[`main`](../../../../README.md)** / **[`framework`](../../../framework/)** / **[`working`](../)** / **[`cosmos`](../../../cosmos/)** / **[`spectrum`](../../../spectrum/)** /
