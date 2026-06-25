/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /

---

<img src="https://img1.wsimg.com/isteam/ip/21cc2ac0-6dc4-4b19-93ef-6a7079ac9d3c/Euclid%20DR1.png" width="100%" alt="Euclid DR1">

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20563048.svg)](https://doi.org/10.5281/zenodo.20563048)

The Euclid Data Release 1 is expected in October 2026. Five Mode Identity Theory predictions are locked here, before the data, against four named contenders: flat ΛCDM, w<sub>0</sub>w<sub>a</sub>CDM (CPL), early dark energy (EDE), and MOND / relativistic MOND. Each row is a head-to-head with a stated falsification threshold for MIT. DR1 results will be added in a later commit when the data arrive.

---

## :lock: Pre-Registration

| Field | Value |
|---|---|
| Freeze date | 2026-06-05 |
| Reference | Standalone Zenodo deposit: [10.5281/zenodo.20563048](https://doi.org/10.5281/zenodo.20563048) |
| Expected Euclid DR1 release | October 2026 |
| Data products in scope | Cosmology release: spectroscopic BAO (<i>z</i> = 0.9–1.8), photometric weak lensing, high-<i>z</i> stellar mass function. Quick-look products are not bound by this card. |

**Ground rules.**

1. MIT prediction cells, contender prediction cells, and falsification thresholds are immutable after the tagged release. Any edit voids the pre-registration for that row.
2. Post-DR1 results enter via the Winner(s) row of the Scoreboard and the per-observable DR1 outcome lines on a clearly dated later commit. Earlier content is not edited at that time.
3. Contender predictions cite either a published canonical source or the best-fit posterior from the most recent public data release of that framework. Where a contender is silent on an observable, the cell reads "no prediction" and that silence counts as data.
4. The card adjudicates the five rows independently. A single falsification falsifies that row; the framework as a whole stands or falls on the collective pattern.

---

## :crystal_ball: Prediction Summary

| # | Observable | MIT prediction | Euclid DR1 channel | Falsifies MIT if |
|---|---|---|---|---|
| I | $\Lambda$ epoch-independence | $\Lambda_\text{obs} = 3/R^2$ is the topological eigenvalue; $\Omega_\text{DE}(z)$ flat across all DR1 redshift bins | Spectroscopic BAO across four $z$ bins + photometric weak lensing (3×2pt); $\Omega_\text{DE}(z)$ reconstruction and CPL fit | Reconstructed $\Omega_\text{DE}(z)$ varies at $\geq 2\sigma$ across DR1 bins in a model-independent (binned or non-parametric) reconstruction |
| II | $a_0(z)$ evolution | $a_0(z) = a_0(0) \cdot H(z)/H_0$; $a_0(z{=}1.5) \approx 2.4\times$ local | Galaxy-galaxy weak lensing stellar-mass-halo-mass relation; photometric/spectroscopic galaxy samples for high-<i>z</i> scaling relations | Euclid DR1 galaxy-galaxy lensing and stellar-mass-halo-mass scaling show no enhancement consistent with the predicted $a_0(z)$ evolution, while external $z \approx 1$–1.5 kinematic follow-up finds $a_0$ consistent with $a_0(0)$ at $\geq 2\sigma$ |
| III | $w_\text{eff}(z)$ trajectory | $w_\text{eff}(z) > -1$ at all $z$ (fiducial split, proven) | Spectroscopic BAO ($z = 0.9$–1.8, four bins) combined with photometric weak lensing; CPL parameter posterior | Fiducial split gives $w_\text{eff}(z) < -1$ at $\geq 2\sigma$ |
| IV | Stellar mass function at $z \gtrsim 10$ | JWST-style massive galaxies persist in Euclid wide-area statistics; reachable with $\varepsilon_\text{SF} \lesssim 1$ under $a_0(z{=}10) \approx 20.5\times$ | Wide-area photometric source catalog with high-<i>z</i> selection; NISP/ancillary spectroscopic confirmation where available | Abundance of $M_{*} \sim 10^{10}\ M_\odot$ galaxies at $z > 10$ falls within Boylan-Kolchin (2023) ΛCDM SMF forecast at $\geq 2\sigma$ |
| V | $(1+z)^1$ coefficient in $H^2(z)$ | Negative, magnitude $\|\beta\| < 0.012$ tied to $s_0$ | Spectroscopic BAO precision across $z = 0.9$–1.8 (forecast 1–2% per bin); coefficient extracted from the $H^2(z)$ form | Coefficient positive at $\geq 2\sigma$, or magnitude inconsistent with fitted $s_0$ |

---

## I. $\Lambda$ Epoch-Independence

This is the framework's deepest claim. $\Lambda$ is not a free parameter fit to the cosmological redshift–distance data; it is the first positive eigenvalue of the Möbius surface embedded in $S^3$, $\lambda_1 = 2/R^2$, with $\Lambda_\text{obs} = 3/R^2$ after the Gauss equation conversion. The value test was passed by Planck ($\Lambda_\text{obs} \cdot \ell_P^2 \approx 2.90 \times 10^{-122}$, predicted 2.9 × 10<sup>−122</sup>). What Euclid DR1 adjudicates is whether $\Lambda$ stays constant across cosmic time, or whether the dark-energy density evolves.

| Framework | Prediction | Source |
|---|---|---|
| **MIT** | $\Lambda_\text{obs}$ is a topological eigenvalue; $\Omega_\text{DE}(z)$ is flat at every DR1 redshift bin | [cosmological-constant](cosmological-constant.md), [first-eigenvalue](../../framework/files/bedrock/first-eigenvalue.md) |
| **ΛCDM** | $\Lambda$ constant by construction | Standard Friedmann cosmology |
| **w<sub>0</sub>w<sub>a</sub>CDM** | DESI DR2 best fit: $(w_0, w_a) = (-0.42 \pm 0.21,\; -1.75 \pm 0.58)$ (BAO+CMB), implying time-varying dark energy density; $\Omega_\text{DE}(z)$ not flat | DESI DR2 BAO+CMB combined fit |
| **EDE** | Early dark energy component active near $z \sim 3000$; at low $z$, $\Omega_\text{DE}(z)$ approximately flat | Poulin, Smith, Karwal class |
| **MOND / RelMOND** | No prediction | Standard MOND has no cosmology |

> 🎯 *DR1 outcome to be recorded after October 2026.*

---

## II. $a_0(z)$ Evolution

MIT predicts $a_0$ scales with $H(z)$; standard MOND predicts $a_0$ is universal and constant; ΛCDM has no acceleration scale at all. This is the sharpest three-way split on the card. The $z = 10$ extrapolation ($\approx 20.5\times$ local) is for JWST and ELT; Euclid DR1's contribution comes through galaxy-galaxy weak lensing and the stellar-mass-halo-mass relation at $z \approx 1$–1.5.

| Framework | Prediction | Source |
|---|---|---|
| **MIT** | $a_0(z) = a_0(0) \cdot H(z)/H_0$; $a_0(z{=}2) \approx 3\times$ local, $a_0(z{=}10) \approx 20.5\times$ | [early-galaxies](early-galaxies.md) |
| **ΛCDM** | No acceleration scale; rotation curves explained by dark matter halos of mass-dependent profile | Navarro-Frenk-White, standard structure formation |
| **w<sub>0</sub>w<sub>a</sub>CDM** | No acceleration scale | Same as ΛCDM |
| **EDE** | No acceleration scale | Same as ΛCDM |
| **MOND / RelMOND** | a<sub>0</sub> = const ≈ 1.2 × 10<sup>−10</sup> m/s² at all <i>z</i> | Milgrom (1983); AeST in cosmological regime |

> ⚠️ *Euclid DR1 galaxy-galaxy lensing constrains the stellar-mass-halo-mass relation but does not directly measure $a_0(z)$. If DR1 lensing data lack the sensitivity to distinguish the predicted enhancement from standard halo-mass scatter, this row is deferred to DR2 and external kinematic follow-up and is not counted in the row-by-row tally.*

> 🎯 *DR1 outcome to be recorded after October 2026.*

---

## III. $w_\text{eff}(z)$ Trajectory

Euclid DR1 will deliver spectroscopic BAO in four redshift bins between <i>z</i> = 0.9 and 1.8, combined with photometric weak lensing. The headline cosmology result will be reported in the w<sub>0</sub>w<sub>a</sub>CDM (CPL) parameterization. This row carries a single core claim: the underlying $w(z)$ never crosses $w = -1$. The Waltz-clock distance-redshift relation satisfies $w_\text{eff}(z) > -1$ for all $z \geq 0$ in the fiducial-matter split (proven analytically). Any apparent crossing reported in CPL fits is a template-projection artifact: two-parameter bases (CPL, BA, JBP) produce spurious phantom crossings when applied to non-phantom distances of this type. The specific location of such an artifact depends on the template basis, the dataset, and the covariance structure; MIT does not predict a crossing redshift because the crossing is not physical.

| Framework | Prediction | Source |
|---|---|---|
| **MIT** | $w_\text{eff}(z) > -1$ at all $z$ in the fiducial-matter split; no real crossing | [dark-energy](dark-energy.md) §III (proof) |
| **ΛCDM** | $w(z) = -1$ exactly, no crossing possible | Standard Friedmann cosmology |
| **w<sub>0</sub>w<sub>a</sub>CDM** | Parameterization permits crossing; DESI DR2 best fit $(w_0, w_a) \approx (-0.4,\; -1.8)$ implies a crossing near <i>z</i> ≈ 0.4–0.5 | DESI DR2 BAO+CMB combined fit |
| **EDE** | $w(z) \approx -1$ at Euclid DR1 redshifts; the EDE component is active near $z \sim 3000$ | Poulin, Smith, Karwal class |
| **MOND / RelMOND** | No prediction | Standard MOND has no cosmology; AeST does not constrain $w(z)$ at this precision |

> ⚠️ **If a crossing is detected.** *MIT's position is that any CPL crossing is a template-projection artifact of a non-phantom truth; the framework does not predict a specific crossing redshift. The diagnostic is reconstruction-basis dependence: crossings that appear in two-parameter bases (CPL, BA, JBP) but vanish in non-parametric reconstructions are template artifacts; a crossing that persists across reconstruction methods would constitute evidence against that interpretation.*
>
> *Other contenders: ΛCDM predicts no crossing. w<sub>0</sub>w<sub>a</sub>CDM best fit puts the crossing near <i>z</i> ≈ 0.4–0.5. EDE and MOND give no late-time crossing.*

> 🎯 *DR1 outcome to be recorded after October 2026.*

---

## IV. Stellar Mass Function at $z \gtrsim 10$

Euclid's wide-area photometric survey will dramatically extend the JWST-discovered population of high-redshift massive galaxies, replacing small-area surprise with cosmologically significant statistics. The question this row asks is whether the abundance of $M_{*} \sim 10^{10}\ M_\odot$ galaxies at $z \gtrsim 10$ is what standard structure formation expects or what JWST already suggests it is not. MIT and EDE both predict enhanced high-redshift abundance relative to ΛCDM, by different mechanisms (epoch-dependent $a_0$ vs. shifted matter-radiation equality). This row discriminates MIT from ΛCDM and w<sub>0</sub>w<sub>a</sub>CDM; the MIT-vs-EDE tiebreaker is Row II ($a_0(z)$ evolution).

| Framework | Prediction | Source |
|---|---|---|
| **MIT** | Wide-area statistics confirm JWST-class abundance; reachable under standard $\varepsilon_\text{SF} \lesssim 1$ with $a_0(z{=}10) \approx 20.5\times$ local | [early-galaxies](early-galaxies.md) |
| **ΛCDM** | Stellar mass function at $z \gtrsim 10$ within standard halo-abundance forecasts; the JWST tension is anomalous and resolves with better selection / dust corrections | Boylan-Kolchin (2023) SMF forecast; standard structure formation |
| **w<sub>0</sub>w<sub>a</sub>CDM** | Same as ΛCDM (dark energy modifications do not change early structure growth) | Standard structure formation |
| **EDE** | Enhanced early structure from shifted matter-radiation equality; consistent with JWST UV luminosity functions at $z \sim 4$–16 with moderate $\varepsilon_\text{SF}$; quantitative SMF at $z > 10$ TBD | Klypin et al. (2021); Shen, Vogelsberger, Boylan-Kolchin (2024) |
| **MOND / RelMOND** | Enhanced gravity at low accelerations qualitatively eases early structure formation; no clean quantitative mass-function prediction available | Sanders, McGaugh review |

> ⚠️ *Euclid DR1 wide-area photometry at z > 10 may yield a catalog too sparse or selection-dominated to distinguish the MIT and ΛCDM mass-function forecasts at the stated threshold. If DR1 uncertainties or selection systematics are too large to determine whether the abundance of M<sub>*</sub> ~ 10<sup>10</sup> M<sub>☉</sub> galaxies at z > 10 lies above or within the Boylan-Kolchin (2023) ΛCDM forecast at the stated 2σ threshold, this row is deferred to DR2 / JWST cross-calibration and is not counted in the row-by-row tally.*

> 🎯 *DR1 outcome to be recorded after October 2026.*

---

## V. $(1+z)^1$ Coefficient in $H^2(z)$

This is the distinctive signature row. The phase-clock $H^2(z)$ form contains a $(1+z)^1$ term that is absent from every canonical FLRW component (radiation, matter, curvature, $\Lambda$). The coefficient is strictly negative for $s_0 > 0$ and tied to the fitted phase parameter. No other model on this card predicts this term at all.

| Framework | Prediction | Source |
|---|---|---|
| **MIT** | Negative coefficient $-\beta$ with $\|\beta\| < 0.012$ at 95% CL from current data; magnitude tied to $s_0$ | [dark-energy](dark-energy.md) §II, §VI |
| **ΛCDM** | Exactly zero (Friedmann has no $(1+z)^1$ component) | Standard Friedmann cosmology |
| **w<sub>0</sub>w<sub>a</sub>CDM** | Approximately zero; CPL has no isolated linear-in-<i>z</i> coefficient in $H^2$ | Linder (2003) parameterization |
| **EDE** | Approximately zero at Euclid DR1 redshifts | Poulin et al. class |
| **MOND / RelMOND** | No prediction | Same as above |

> ⚠️ *DR1 BAO precision (forecast 1–2% per bin) is marginal for direct detection of this term at the current $s_0$ bound; a null result here is consistent with the MIT prediction and a stronger DR2 test.* **A null DR1 result on this row is not counted in the row-by-row tally.**

> 🎯 *DR1 outcome to be recorded after October 2026.*

---

## :musical_score: Scoreboard

|  | Λ | a₀(z) | w(z) | SMF z ≳ 10 | (1+z)¹ in H² |
|---|---|---|---|---|---|
| **MIT** | $\Lambda = 3/R^2$, fixed by topology | $a_0 \propto H(z)$; ≈ 3× at $z = 2$ | $w > -1$ at all $z$; any apparent crossing is template artifact | abundance matches JWST under $a_0(z{=}10) \approx 20.5\times$ | negative; \|β\| < 0.012 tied to $s_0$ |
| **ΛCDM** | fixed by construction | no $a_0$ | $w = -1$ exact | predicted SMF below JWST (tension) | coefficient = 0 (term absent from Friedmann) |
| **w<sub>0</sub>w<sub>a</sub>CDM** | $\Omega_\text{DE}(z)$ varies | no $a_0$ | crossing near $z$ ≈ 0.4–0.5 | same tension as ΛCDM | no tied standalone (1+z)¹ coefficient |
| **EDE** | fixed at low $z$, EDE component at $z \sim 3000$ | no $a_0$ | $w \approx -1$ at DR1 $z$ | consistent with JWST UVLFs; quantitative SMF at $z > 10$ TBD | coefficient ≈ 0 at DR1 $z$ |
| **MOND** | no prediction | $a_0$ fixed ≈ 1.2 × 10<sup>−10</sup> m/s² | no prediction | enhanced gravity qualitatively helps; no quantitative SMF | no prediction |
| 🎯 **DR1 outcome** |  |  |  |  |  |
| 🏆 **Winner(s)** |  |  |  |  |  |

---

/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /
