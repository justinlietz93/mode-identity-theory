/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`working`](../)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /

---

# The R Problem

**Status (2026-06-15):** Open, one live route. This note tracks every route to an independent curvature radius R and where each stands; it sits above the detail in [r-from-mass-spectrum.md](r-from-mass-spectrum.md).

**Related:** [R from the mass spectrum](r-from-mass-spectrum.md), [Calibration Structure](calibration-structure.md), [Scaling Law Uniqueness](scaling-law-uniqueness.md).

---

## The goal

Λ = 3/R² is derived from the postulate (eigenvalue + Gauss equation), and the coefficient 3 is the real content. But it produces a number only with an independent R. Any route that reads R off Λ, or off a CMB scale that itself needs R, is circular or excluded. An R fixed from somewhere else turns Λ from a tautology into a forward prediction. That is the R problem.

## The routes

| Route | Chain | Verdict |
|---|---|---|
| de Sitter | R = √(3/Λ) | **Circular.** Reads R off Λ, feeds Λ back. |
| Molien gap (CMB) | low-ℓ feature → R ≈ 5.3 Gpc | **Not independent.** The old "sin-fold moves the first peak to ℓ ≈ 42, so R = 5.3 Gpc is excluded" was a coordinate error: the operative cosmology is flat FLRW and CMB-consistent. But the Molien gap still does not *determine* R on its own. |
| L-ratio (CMB) | ℓ_cut → L_fund → ×8 → L_strip = πR → R | **Dead.** The factor of 8 has no topological derivation: three clean kills, and the geometry gives W = πR/2, not the W = R/4 the 8 would require. |
| Particle mass spectrum | m_e, m_μ → R | **Live, executed.** Order of magnitude. See [r-from-mass-spectrum.md](r-from-mass-spectrum.md). |

## The live route

The mass-spectrum route inverts the fermion mass formula's Ω_Λ dependence: electron and muon give R ≈ 20 Gpc and Λ ≈ 8 × 10⁻⁵⁴ m⁻², about 14× (one order of magnitude) below observed. It is independent of Λ, the CMB, and the de Sitter relation, so it genuinely breaks the circularity. The precision is capped at order of magnitude by the McKay-lever amplification (60× for Δd = 1) acting on the mass formula's irreducible few-percent residual scatter, and a full pair scan shows no fermion pair beats electron-muon. Full computation in [r-from-mass-spectrum.md](r-from-mass-spectrum.md).

## The shared engine

The L-ratio and the mass spectrum are not two problems. The candidate value of the factor of 8 is rank(E₈) = φ(30) = 8 (the eight integers coprime to the Coxeter number h(E₈) = 30, which are the Kostant exponents), and those same exponents and that same 30 drive C_geom and the dist/30 lever in the mass formula. So the L ratio and the mass-spectrum R are one problem at two scales, both projections of the 2I / E₈ representation ring scaled by R. If the factor of 8 is ever derived, it comes from the same structure the live route already uses.

## What survives from the L work, on its own

One piece of the L investigation stands independently of the dead factor of 8: the **Molien sparse-zone** explanation of the CMB low-ℓ deficit. Icosahedral filtering removes ~80% of scalar modes on S³/2I below j ≈ 10 (ℓ ≈ 28), with the surviving generators at degrees 12, 20, 30 (the Klein invariants; 30 = h(E₈) again), producing a gradual power deficit in the observed range. This is a cosmos-side CMB result, not a route to R, and it deserves its own home with the CMB notes rather than living here. It uses the flat projection ℓ ≈ √(j(j+2))·χ\*/R − 1/2, so it is consistent with the corrected flat-FLRW cosmology.

## Where it stands

The mass spectrum is the only live route and it is order of magnitude; the floor is structural (the mass formula's residual scatter times the smallest McKay lever), so it will not sharpen by pair selection. Sharpening R would require the mass formula's high-distance residuals to shrink, which the McKay-propagator note found no parameter-free way to do. Until then the L ratio is a downstream consistency check rather than a route, and the current R is too coarse to test the factor of 8: its ~3.7× spread swings L_strip/L_fund anywhere from ~2 to ~30, and the value 8 corresponds to R ≈ 5.3 Gpc.

---

/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`working`](../)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /
