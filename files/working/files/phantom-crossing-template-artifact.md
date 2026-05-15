/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`working`](../)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /

---

# Phantom Crossing as Template Bias

Working-note summary of the cosmological-scale phantom-crossing analysis. The full paper, MCMC chains, analysis scripts, and figure-generation code live in the standalone repository [github.com/dmobius3/lambda-cos](https://github.com/dmobius3/lambda-cos), archived at Zenodo ([DOI:10.5281/zenodo.19798852](https://doi.org/10.5281/zenodo.19798852)). The paper title is *Apparent Phantom Crossing as Template Bias: A Bounded-Clock Deformation of ΛCDM*.

---

## What the paper does

It constructs a one-parameter bounded-clock deformation of fiducial flat ΛCDM (the cosmological-scale realization of the Waltz clock from [Temporal Budget Identity](./temporal-budget.md)), and uses it to answer a question made urgent by DESI DR2:

> If the underlying expansion history is non-phantom under the fiducial-matter diagnostic split, can standard two-parameter $w_0 w_a$ templates still produce apparent phantom crossings when fitted to its distances?

The answer is yes, demonstrated both analytically (the diagnostic $w_{\rm eff}(z) > -1$ for all $z \geq 0$ is proved in closed form) and empirically (CPL, BA, and JBP recover apparent crossings from Λcos mock data; the three-parameter polynomial does not).

---

## Current results (v2.0.0)

Joint Pantheon+ + DESI DR2 BAO MCMC fit at fixed $\Omega_\Lambda = 0.685$:

| Quantity | Value |
|---|---|
| $s_0$ posterior median | 0.076 [0.023, 0.143] |
| $s_0$ 95% upper limit | $< 0.19$ (flat prior) |
| $H_0 r_d$ (km/s) | 10008 [9972, 10040] |
| $\Delta\chi^2$ vs flat ΛCDM (equal parameter count) | $+0.11$ |
| Savage-Dickey Bayes factor $B_{01}$ at $s_0$ prior floor | $\approx 7.1$ ($\pm 0.03$ across KDE bandwidths) |

The constraint is prior-sensitive in detail ($s_0 < 0.12$–$0.21$ across flat, $s_0^2$-flat, and $\log_{10}$-flat priors) but data-driven in character: all priors yield $s_0 \ll 1$. The constraint is also stable to $\Omega_\Lambda$ variations over $0.68$–$0.715$; best $\Delta\chi^2$ near $\Omega_\Lambda = 0.69$.

CPL recovery at $s_0 = 0.19$:

| Quantity | MIT | DESI best fit |
|---|---|---|
| $w_0$ from CPL fit | $\approx -1.02$ | $\approx -0.75$ |
| $w_a$ from CPL fit | $\approx +0.29$ | $\approx -0.86$ |

The induced distortion is structurally present but modest at data-allowed $s_0$, and of opposite sign in $w_a$. The paper establishes the mechanism without claiming Λcos at $s_0 < 0.19$ reproduces the DESI signal amplitude.

Linear-growth consistency check against DESI DR1 ShapeFit+BAO $f\sigma_{s8}$ at six tracer effective redshifts (BGS, LRG1-3, ELG2, QSO; $z \in [0.30, 1.49]$):

| Model | $\chi^2_{\rm RSD}$ (6 bins) | $\Delta\chi^2$ vs flat ΛCDM |
|---|---|---|
| flat ΛCDM ($\Omega_m = 0.315$) | 4.64 | 0 |
| Λcos ($s_0 = 0.076$, median) | 4.68 | $+0.04$ |
| Λcos ($s_0 = 0.185$, 95% UL) | 4.90 | $+0.26$ |

The model deviation in $f\sigma_{s8}$ is below 1% per bin at all DR1 effective redshifts, well within the 9-23% per-bin measurement precision. The $\Omega_m(z)$ trajectory shows a $\sim 2.9\%$ split at $z = 2.3$ at the upper limit — the most distinctive available diagnostic, beyond the current growth-data reach ($z_{\rm max} = 1.49$).

Clock-exponent selection is empirically validated: integer alternatives $n = 0, -1, +1$ give $\Delta\chi^2 > 60$ relative to ΛCDM (paper Appendix A).

---

## Connection to MIT framework

| Connection | Content |
|---|---|
| [Temporal budget $\Psi^2 + S^2 = 1$](./temporal-budget.md) | Λcos is the cosmological-scale realization of the Waltz clock $dt/d\tau = S^{-1/2}$. The paper presents Λcos in its own terms (no MIT vocabulary); the framework-level reading is in the temporal-budget note. |
| Bounded auxiliary variable | $S = \sin(t/2)$ on the monotonic branch $0 < t \leq \pi$. Maps to FLRW scale factor through $1+z = s_0/S$. |
| Clock exponent $-1/2$ | Selected by matter-era Friedmann scaling at high $z$; empirically validated against integer alternatives. |
| Reference value $\Omega_\Lambda = 0.685$ | Topology-fixed input from Möbius eigenvalue (sector $\mathcal{A}$); not fitted. |
| $(1+z)^1$ signature | Falsifiable signature absent from canonical FLRW density scalings. Tied coefficient $-\beta(s_0)$ distinguishes from a free-coefficient domain-wall fluid ($w = -2/3$). |

---

## Falsification criteria (paper Table IX)

| Observable | Λcos prediction | Falsified if |
|---|---|---|
| $(1+z)^1$ coefficient in $H^2$ | Non-positive, magnitude tied to $s_0$ | Positive coefficient detected, or negative coefficient inconsistent with fitted $s_0$ |
| Diagnostic $w_{\rm eff}(z)$ | $> -1$ (fiducial split, any $s_0 > 0$) | Same split gives $w_{\rm eff} < -1$ at $\geq 2\sigma$ |
| ΛCDM limit | $s_0 = 0$ recovers fiducial flat ΛCDM | (none required) |

---

## What's not in the paper (deliberate)

- No MIT framework vocabulary. The paper presents Λcos as a standalone phenomenological bounded-clock model with internal selection logic (matter-era scaling + algebraic simplicity). The framework reading lives in the temporal-budget note and is not required for the paper's arguments to stand.
- No microphysical Lagrangian. The paper is phenomenological at the background-and-linear-growth level; deriving Λcos from an action, or specifying the perturbation-level dynamics beyond the standard sub-horizon equation, are deferred.
- No claim that Λcos at $s_0 < 0.19$ explains the full DESI signal amplitude. The mechanism is demonstrated; the amplitude gap to the DESI best fit is acknowledged and characterized.

---

/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`working`](../)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /
