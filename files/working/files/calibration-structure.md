/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`working`](../)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /

---

# Calibration Structure (draft for the framework engine)

**Status:** DRAFT. Proposed new section for `files/framework/README.md`, replacing the buried "Calibration structure" paragraph and reframing the "Measured scales" inputs table.

**Dependencies:** a0 paper Appendix A.2 (selection rule), Λ eigenvalue ($\lambda_0 = 2/R^2$), scaling law.

---

## Section draft

## Calibration Structure

The framework is a calibration scheme, not an oracle that produces every absolute scale without input. One measured reference observable anchors each sector's normalization. What the framework supplies are the sector exponents, grid assignments, well locations, and dimensionless ratios. In other words, the measured anchor fixes the ruler; the topology fixes where the marks on the ruler fall.

This is the same logic used throughout effective physical theory. The Standard Model does not derive the numerical values of the gauge couplings from first principles; it measures them at reference scales and predicts how they run and relate across processes. In the same way, $H_0$ is not a failed prediction when it is used as the edge-sector anchor. It plays the role of a measured reference input. The prediction is not the existence of a number called $H_0$; the prediction is that the same calibrated edge hierarchy also fixes $a_0$ through a parameter-free ratio.

| Sector | Locus | Hierarchy | Anchor | Status |
|---|---|---|---|---|
| Edge $(n=1)$ | $S^1$ boundary; kinematic locus, no intrinsic eigenvalue | $\Omega_H = (c/H\ell_P)^2$ | $H_0$ measured | Live |
| Surface $(n=2)$ | Möbius strip; carries $\lambda_0 = 2/R^2$ | $\Omega_\Lambda = (R/\ell_P)^2$ | $\Lambda$ measured, fixing $\Omega_\Lambda$ | Live as calibration |
| Space $(n=3)$ | $S^3$ slice; inherits surface eigenvalue | $\Omega_\Lambda$ | Via surface sector | Live with surface |
| Mass | 120-wells, McKay distance, torsion | $\mu_\Lambda$ and $\Omega_\Lambda^{\mathrm{dist}/60}$ | $\Omega_\Lambda$ from surface; one mass-sector normalization if needed | Live |
| Couplings | Grid wells and fractional hierarchy steps | $\Omega_\Lambda^{-1/60}$, $\Omega_\Lambda^{-1/120}$ | $\Omega_\Lambda$ from surface | Live |

The prediction/calibration split is sector-by-sector. In the edge sector, the measured value of $H_0$ calibrates the edge hierarchy. The acceleration scale then follows from the ratio of wells:

$$\frac{a_0}{cH_0}=\frac{C(13/120)}{C(34/120)}.$$

Thus $H_0$ is the anchor, while $a_0/H_0$ is the prediction.

In the surface sector, the intrinsic eigenvalue statement remains intact:

$$\lambda_0 = \frac{2}{R^2}.$$

What failed was the independent over-determination of $R$ through the CMB-Molien path. Without an independent value of $R$, the framework no longer predicts $\Lambda$ absolutely. Instead, measured $\Lambda$ calibrates the surface hierarchy

$$\Omega_\Lambda = (R/\ell_P)^2.$$

The eigenvalue structure survives; the absolute surface radius is the open piece.

This localizes the blast radius. Losing the independent CMB-Molien anchor demotes exactly one claim: $\Lambda$ is no longer an absolute prediction. It becomes the measured surface-sector calibration input. Downstream mass and coupling calculations do not collapse, because they require the value of $\Omega_\Lambda$, and measured $\Lambda$ still supplies that value. The McKay mass elevator uses powers of $\Omega_\Lambda$; the gauge couplings use fractional powers such as $\Omega_\Lambda^{-1/60}$. They do not require $R$ to be independently predicted, only consistently calibrated.

The edge sector is untouched by this correction. It references $\Omega_H$, not $\Omega_\Lambda$, and is anchored by $H_0$. The surface and space sectors reference $\Omega_\Lambda$, now calibrated by measured $\Lambda$. The mass and coupling sectors inherit that calibrated hierarchy. Thus the correction does not propagate as a global failure; it changes the status of one surface-sector claim from prediction to calibration.

This also clarifies the role of measured inputs. The framework predicts structural relations: the integer floors $n=1,2,3$, the McKay exponents, the grid fractions, the well assignments, and the dimensionless ratios between observables sharing a calibrated sector. It does not claim that every absolute normalization is derived without empirical reference. A measured anchor per sector is part of the calibration architecture. $\mu_\Lambda = \rho_\Lambda^{1/4}$ is the vacuum floor inherited from the calibrated surface sector; $m_e$ is a mass-sector normalization/benchmark, not a second vacuum floor.

The status is therefore honest. The selection rules and well assignments were fixed before this calibration reinterpretation, so the downstream agreements are not produced by retuning them after the fact. But the selection rule itself remains a postulate of the framework, not yet a theorem derived from the topology alone. A first-principles derivation from the Hurwitz/Fibonacci structure of the 120-domain remains open.

---

## Proposed Inputs table patch

Replaces the current "Measured scales" table in the engine.

| Input | Role | Status |
|---|---|---|
| $H_0$ | Edge-sector anchor; fixes $\Omega_H$ | Measured calibration |
| $\Lambda$ or $\Omega_\Lambda$ | Surface-sector anchor; fixes the boundary hierarchy used by surface, space, mass, and coupling sectors | Measured calibration |
| $R$ | Surface-sector radius satisfying $\Omega_\Lambda=(R/\ell_P)^2$ and $\lambda_0=2/R^2$ | Open if claimed independently; calibrated if read from measured $\Lambda$ |
| $m_e$ | Optional mass-sector normalization/check, depending on convention | Measured calibration or benchmark; state explicitly |

---

## Editor notes (resolve before merging into the engine)

- **μ_Λ vs m_e (your caveat).** I added one explicit sentence to the "measured inputs" paragraph: the absolute floor is $\mu_\Lambda = \rho_\Lambda^{1/4}$ from the surface sector, and $m_e$ is the mass-sector normalization, not a second floor. Adjust the wording to taste, or move it to a dedicated mass paragraph.
- **Display math.** Your `[...]` equation blocks were converted to `$$...$$` so GitHub renders them.
- **On merge.** Add the inline links (cosmological-constant, cmb-anomalies pages) where the CMB-Molien path and $\Lambda$ are mentioned, and delete the engine's existing one-paragraph "Calibration structure" note that this section supersedes.
- **Consistency catch.** `scaling-law-uniqueness.md` currently states the per-sector calibration as "H for edge modes, R for surface modes." Update that to "Λ (measured) for surface modes," since the independent R-from-CMB determination is the excluded path.

---

## Mass/gravity reading: the two dials (draft for the-waltz.md §II)

The mass-and-gravity sector is one closed system. The topology fixes every dimensionless ratio; two dimensionful dials, $\Lambda$ (equivalently $R$) and $G$, set the absolute scales. The mass-spectrum reading and the gravity-constant reading are the same system read from different dials, not competing claims.

| Anchors used | Solves for | Reading |
|---|---|---|
| $\Lambda$ and $G$ | Absolute fermion masses | Mass-spectrum reading |
| $\Lambda$ and one measured mass | $G$ plus the remaining masses | Gravity-constant reading |
| Ratios only | $m_i/m_j$ | Dimensionless, anchor-free core |

Key phrase: **same two-dial system, different readout.**

Prose to write in your voice (prompts):

- Lead with the bottom row: the dimensionless ratios are the anchor-free predictions, stated before either dial reading.
- Present the two dial readings as symmetric, not ranked: $\{\Lambda, G\}$ gives the masses; $\{\Lambda, \text{one mass}\}$ gives $G$.
- Keep the ontology honest: not "$G$ is not a measured constant," but "within this calibration, $G$ can be inferred from $\Lambda$ plus one measured mass."

Editor notes:

- Target: the-waltz.md §II ("The dictionary has a definition"), folded in before public.
- Already applied to the-waltz.md alongside this draft: the line-82 fix ($R$ calibrated from measured $\Lambda$, not fixed by topology) and the line-95 softening of the "$G$ is not measured" overclaim.

---

/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`working`](../)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /
