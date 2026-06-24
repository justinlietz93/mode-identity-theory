/ **[`main`](../../../README.md)** / **[`cosmos`](../../cosmos/)** / **[`early galaxies`](early-galaxies.md)** /

---

# Early Galaxies Update 1: MUSE-DARK III and the $a_0(z)$ direction

Tracking file for the epoch-dependent $a_0$ prediction between deposit and the formal Euclid DR1 test. Update 1 logs the first intermediate-redshift measurement of the acceleration scale, MUSE-DARK III, which appeared after the deposit and is not in the canonical paper. It is a corroboration of the *direction* with the *normalization* left open, and it is recorded here alongside the paper's own intermediate-z tension so the picture stays whole.

**Measurement.** Ciocan, Bouché, Fensch, Krajnović, Freundlich, Desmond, Famaey & Techi (2026), *A&A* 709, L16; arXiv 2604.22613.

**Prediction (pre-registered).** Shatto, "Proposed Resolution of High-Redshift Galaxy Mass Anomalies via Epoch-Dependent Acceleration Scaling," Zenodo 10.5281/zenodo.18073340, 28 December 2025. Abstract: "the MOND acceleration scale a0 is not a universal constant but an epoch-dependent quantity scaling with the Hubble parameter H(z)," with a0(z=10) ≈ 20 × a0(0). The $a_0 \propto H(z)$ prediction also traces to the foundational deposit, "Mode Identity Theory: Modal realization from nested topology," Zenodo 10.5281/zenodo.18064856 (2025).

**Mechanism (canonical).** Shatto, "Epoch-Dependent Acceleration Scale from Bounded Topology: Predictions for High-Redshift Galactic Dynamics," 13 June 2026; SSRN 6933958; Zenodo concept DOI 10.5281/zenodo.19980665.

**Timing.** The $a_0 \propto H(z)$ prediction was deposited 28 December 2025, four months before MUSE-DARK III reached arXiv (2026-04-24; published 2026-05-19). This comparison is post-publication; the prediction is not.

---

## 1. What MUSE-DARK III measures

79 star-forming galaxies at 0.33 < z < 1.44 (MUSE Hubble Ultra Deep Field). The RAR characteristic acceleration $a_0$ is fit per redshift bin (four quantile bins, ~20 galaxies each). $a_0$ increases systematically with redshift, ~1.99 (lowest bin) to ~2.71 (highest), in units of 10⁻¹⁰ m/s², significant at ~30σ against constant $a_0$. Global linear fit: $a_0(z) = 1.0 + 1.59\,z$ (slope +0.11/−0.10).

## 2. What the framework predicted

$a_0(z) = a_0(0)\,E(z)$, with $E(z) = H(z)/H_0$. The canonical paper adopts the flat ΛCDM Friedmann form ($\Omega_m = 0.315$, $\Omega_\Lambda = 0.685$, $H_0 = 67.4$) as a transparency choice, for direct comparison with published data.

The ratio $a_0/(cH) = C(13/120)/C(34/120) = 0.1845$ is derived from the phase-operator values at the Fibonacci wells 13 and 34 on the 120-domain; $a_0$ and $H$ are both edge modes ($n = 1$), so the ratio holds at every epoch. At $z = 0$, $a_0(0) = 1.20$ × 10⁻¹⁰ m/s² (SPARC), giving observed $a_0/(cH_0) = 1.20/6.548 = 0.1833$, a 0.7% match to the derived ratio.

The deposit fixes both the *direction* ($a_0$ not constant) and the *form* ($a_0 \propto H(z)$). Falsification (canonical paper, Table 5.1) sets two thresholds. A matched-systematics discrepancy at ≥2σ is a reportable tension. Formal falsification requires ≥3σ in one channel, or mutually consistent ≥2σ failures across independent bins or observables.

## 3. Direction and form: CORROBORATED (but non-discriminating)

Pre-registered (28 Dec 2025) that $a_0$ evolves with redshift, scaling as $H(z)$, against the standard-MOND constant. MUSE-DARK III measures $a_0$ rising at ~30σ over 0.33 < z < 1.44, the opposite of the falsification condition. The call was made in advance and came in on the right side.

The direction is not, however, a discriminator. The possibility that $a_0$ varies with cosmic time through its relation to $H$ was raised by Milgrom (1999); Sanders (2008) tested $a_0 \propto H(z)$ against Tully–Fisher data to $z = 1.2$; Hossenfelder & Mistele (2018) derived a redshift-dependent $a_0$ in Covariant Emergent Gravity. ΛCDM is not exempt either: hydrodynamical simulations recover a rising best-fit $a_0$ (Mayer et al. 2023, Magneticum: ~3× from $z = 0$ to $z = 2.3$). So a climbing $a_0$ separates the framework from neither MOND-evolution proposals nor ΛCDM. The framework's distinct content is the mechanism (edge-mode phase wells, the locked exponent structure) and the specific functional form; the discriminating tests live in the form and the exponent lock at $z > 2$, not in the rise.

Scope: the formal falsification test names $z > 2$ (Euclid DR1). MUSE-DARK III reaches $z = 1.44$, so this is corroboration in the predicted direction, with the formal test still owed.

## 4. Rate and normalization: OPEN (shape consistent, normalization-limited)

<img src="https://img1.wsimg.com/isteam/ip/21cc2ac0-6dc4-4b19-93ef-6a7079ac9d3c/muse_dark_iii_a0z_overlay.png/:/rs=w:1280,h:807" width="100%" alt="MUSE-DARK III binned a0(z) against framework a0(0)E(z): the predicted curve at a0(0)=1.2 runs below all four points, the free-fit at about 1.4 threads them, and the points lie in the upper half of the SPARC normalization band.">

*The four MUSE-DARK III binned $a_0$ (read from the paper's Fig. 3) against the framework $a_0(0)\,E(z)$. The predicted normalization ($a_0(0)=1.2$, solid) undershoots; the free fit ($\approx 1.4$, dashed) threads the points, which sit in the upper half of the SPARC band. Eyeball/pixel reads, pending WebPlotDigitizer.*

The SPARC-anchored prediction $a_0(0)\,E(z)$ with $a_0(0) = 1.2$ sits below all four bins. Values read from Figure 3 (eyeball + pixel measurement; pending formal WebPlotDigitizer extraction):

| Bin | z (approx) | a₀ measured | σ (measured) | a₀ predicted (1.2·E(z)) | residual | residual / σ (stat only) |
|-----|-----------|-------------|--------------|-------------------------|----------|--------------------------|
| 1 | ~0.50 | ~2.00 | ~0.10 | 1.59 | +0.41 | ~4σ |
| 2 | ~0.82 | ~2.20 | ~0.10 | 1.93 | +0.27 | ~2.7σ |
| 3 | ~1.05 | ~2.57 | ~0.11 | 2.21 | +0.36 | ~3.3σ |
| 4 | ~1.28 | ~2.71 | ~0.12 | 2.52 | +0.19 | ~1.6σ |

Predicted column: flat ΛCDM $E(z)$, $\Omega_m = 0.315$, $H_0 = 67.4$, per the canonical paper's Table 3.1. The residual/σ column is statistical only; the ~20% normalization uncertainty discussed below dominates and is not folded in.

The per-bin error bars are σ ≈ 0.10 (pixel-measured against the Figure 3 axis: bin 1 spans 45 px at 229 px per 10⁻¹⁰ unit → 0.10; bin 2 ≈ 0.12). An earlier read of ~0.30 was the shaded fit-confidence band, a different element from the grey point bars. So the per-bin statistical residuals are ~2–4σ, all positive.

That statistic is not the limiting figure. The comparison is normalization-limited: the absolute $a_0$ scale is uncertain at ~20% on both sides, the SPARC value the prediction rides is 1.20 ± 0.26, and MUSE's absolute scale is not matched-calibrated to SPARC's (different method; its linear $z = 0$ extrapolation, 1.0, differs from SPARC's 1.2, though that extrapolation is itself unreliable given the curvature). Whether the residual is a real tension or absorbed by cross-calibration cannot be settled at this precision; matched-method analysis would be required, and that is the MUSE team's uncertainty, not a framework knob.

What is settled is the shape. Freeing the normalization, $a_0(0) ≈ 1.4$ threads the four bins at χ²/dof ≈ 1.7. The convex $E(z)$ form is consistent with the data; the open question is purely the normalization.

And the normalization is not a free knob on the framework side. $a_0(0) = 1.2$ is clamped twice, by SPARC (1.20 ± 0.26) and by the derived ratio 0.1845, which at $H_0 = 67.4$ returns 1.21. Tuning $a_0(0)$ up to fit MUSE would overshoot SPARC and break the ratio match. The residual lives in the cross-instrument normalization, not in a re-anchoring of the prediction.

## 5. Where this sits in the intermediate-z record

MUSE-DARK III is not the framework's only intermediate-z test, and the record is mixed.

The canonical paper's intermediate-z test is the Übler et al. KMOS3D Tully–Fisher comparison (§4.1): a **2.9σ trend-shape tension** under the most conservative systematics budget, the data are non-monotonic, the prediction monotonic, held against the prediction without retreat. That is a *different* observable (BTFR zero-point) from MUSE-DARK III's ($a_0$ via the RAR), and MUSE post-dates the paper, so it slots into the paper's §4.4 "Other regimes" rather than replacing the Übler test.

Honest intermediate-z picture, then: BTFR trend-shape in 2.9σ tension (Übler); $a_0$ direction corroborated (MUSE); $a_0$ normalization open (MUSE). Direction confirmed, details contested, clean test pending.

## 6. Summary

| Claim | Status | Detail |
|-------|--------|--------|
| a₀ evolves with z (direction) | CORROBORATED, non-discriminating | Pre-registered 28 Dec 2025; measured ~30σ; but a rising a₀ is also produced by MOND-evolution models and ΛCDM simulations (Mayer 2023) |
| a₀ ∝ H(z) (shape) | CONSISTENT | Free-normalization E(z) fits the bins at χ²/dof ≈ 1.7 |
| a₀(0) = 1.2 (normalization) | OPEN | ~2–4σ statistical; normalization-limited (~20% each side); clamped by SPARC + the 0.1845 ratio; cross-calibration unresolved |
| BTFR trend shape (Übler) | TENSION | 2.9σ, non-monotonic data vs monotonic prediction (canonical paper §4.1) |
| Formal z > 2 test | PENDING | Euclid DR1 (October 2026) |

## 7. Disposition

Logged as a directional corroboration with the normalization open, carried alongside the standing Übler tension. No contact with the MUSE-DARK team: the normalization question is dominated by their own cross-calibration, not sharp enough to warrant it.

The discriminating test remains Euclid DR1 stacked galaxy–galaxy lensing at $z = 0.5$–2: the framework predicts a mass- and aperture-*independent* $M_\text{dyn}/M_b$ enhancement of $\sqrt{E(z)} = 1.74$ at $z = 2$, where ΛCDM halo-concentration evolution gives a mass/aperture-*dependent* shift spanning 0.76–1.13. That universality, not the climb, is the discriminator.

---

*Update 1, drafted 2026-06-24. Pending: formal WebPlotDigitizer extraction of the four Figure 3 points and error bars for a quantitative model comparison ($E(z)$ free-norm vs linear, AIC).*

/ **[`main`](../../../README.md)** / **[`cosmos`](../../cosmos/)** / **[`early galaxies`](early-galaxies.md)** /
