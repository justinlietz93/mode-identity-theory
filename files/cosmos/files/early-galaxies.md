/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /

---

<img src="https://pbs.twimg.com/media/HLmYdKfWYAANW13?format=jpg&name=4096x4096" width="100%" alt="Early Galaxies">

JWST has found galaxies too massive, too early. Stellar masses of $\sim 10^{10}\,M_\odot$ at $z \approx 10$ require star formation efficiencies exceeding unity under ΛCDM with a constant MOND acceleration scale, a physical impossibility.

Mode Identity Theory resolves this. The MOND acceleration scale $a_0$ and the Hubble rate $H$ are both edge modes ($n = 1$) on the 120-domain (the 120-cell discretisation of $S^3$ from the binary icosahedral group). Their ratio is fixed by the Fibonacci wells:

$$\frac{a_0}{cH} = \frac{C(13/120)}{C(34/120)} = 0.184$$

Because the ratio holds at every epoch, $a_0(z) = a_0(0) \times H(z)/H_0$, where $H(z)$ is the phase-clock Hubble rate derived from the static $S^3$ baseline. At $z = 10$, this gives $a_0 \approx 20.5 \times$ the local value, enhancing effective gravitational acceleration and reducing the required star formation efficiency to $\varepsilon_\text{SF} \sim 0.5$, within the physically permitted range.

MIT predicts $a_0$ evolves while $\Lambda$ remains constant: the inverse of standard assumptions. This is the companion to the dark energy cornerstone, where the same $H(z)$ proves that $\Lambda$ never crosses $w = -1$. One static universe, two signatures.

**Edge mode scaling**

| Quantity | Value |
|---|---|
| Scaling law | $a_0(z) = a_0(0) \times H(z)/H_0$ |
| $a_0/(cH_0)$ ratio | predicted: 0.184 / observed: 0.183 |
| At $z = 10$ | $a_0 \approx 2.46 \times 10^{-9}$ m/s² (20.5× local) |
| Collapse speedup | ~2.1× faster (required $\varepsilon_\text{SF}$ drops below 1) |

## I. The Observational Tension

JWST observations (Labbé et al.) reveal stellar masses $M_\star \sim 10^{10}\,M_\odot$ already assembled at $z \approx 10$, roughly 500 Myr after the standing wave began its cycle. These masses approach or exceed the maximal baryon abundance permitted in standard dark matter halos under ΛCDM, creating the "impossibly early galaxy" problem.

The tension is quantitative. Assembling $10^{10}\,M_\odot$ of stars in 500 Myr requires converting baryons into stars faster than the available gas supply allows. Under standard assumptions (constant $a_0$, ΛCDM collapse timescales), the implied star formation efficiency $\varepsilon_\text{SF}$ exceeds unity: a physical impossibility. Either the observations contain systematic errors, the mass estimates are wrong, or the gravitational physics governing early collapse is different from what we assume locally.

MIT takes the third option. The acceleration scale governing collapse is not constant; it tracks the phase clock.

## II. Epoch-Dependent Acceleration Scale

### Static Baseline

The cosmos is a static three-sphere $S^3$. The phase-clock Hubble rate $H(z)$ is derived from the standing wave $\Psi = \cos(t/2)$ and the Waltz clock $dt/d\tau = S^{-1/2}$:

$$\frac{H^2(z)}{H_0^2} = \frac{1 - \Omega_\Lambda}{1 - s_0^2}(1+z)^3 - \frac{(1 - \Omega_\Lambda)\,s_0^2}{1 - s_0^2}(1+z) + \Omega_\Lambda$$

with $\Omega_\Lambda = 0.685$ fixed by topology and $s_0 = \sin(t_\text{now}/2)$ the single phase parameter. Both $a_0$ and $H$ are edge modes ($n = 1$) on the 120-domain. What follows is why their ratio is locked.

### The Ratio from the Scaling Law

The MIT scaling law relates any observable $A$ to the Planck reference $A_P$ through a phase coefficient and a power of the hierarchy number $\sqrt{\Omega}$:

$$\frac{A}{A_P} = C(\Theta) \cdot (\sqrt{\Omega})^{-n}$$

where $C(\Theta) = 2\sin^2(\pi\Theta)$ is the phase operator (derived from the anti-periodic first positive mode on the Möbius surface, normalised to unit mean) and $n$ is the manifold depth: $n = 1$ for edge modes, $n = 2$ for surface modes.

Both $a_0$ and $H$ sit on the temporal edge ($n = 1$), referencing the same hierarchy number $\Omega_H$. In the ratio, the Planck scales and the $\sqrt{\Omega_H}$ factors cancel, leaving only the phase coefficients:

$$\frac{a_0}{cH} = \frac{C(13/120)}{C(34/120)} = \frac{2\sin^2(13\pi/120)}{2\sin^2(34\pi/120)} = \frac{0.223}{1.208} = 0.184$$

With $H_0 = 67.4$ km/s/Mpc (consistent with the MIT phase-clock best-fit), $cH_0 = 6.55 \times 10^{-10}$ m/s², giving observed $a_0/(cH_0) = 1.2/6.55 = 0.183$. The positions 13/120 and 34/120 are Fibonacci numbers on the 120-grid, occupying stability wells where destructive interference is minimised.

Two scope notes follow from this. The absolute scale is calibrated off the measured $H_0$ through the kinematic hierarchy $\Omega_H = (c/(H\ell_P))^2$, so the prediction does not depend on the open curvature radius $R$; only the companion claim that $\Lambda$ is constant touches it (the open [R problem](../../framework/files/working/files/r-problem.md)). And the ratio rests on the edge-mode positions alone, not on the galactic coherence mechanism $L_f = v_c^2/a_0$ that the SPARC test falsified.

### The Evolutionary Law

Because the ratio is fixed at every epoch, the acceleration scale inherits the full redshift dependence of $H(z)$:

$$a_0(z) = a_0(0) \times \frac{H(z)}{H_0}$$

This is the paper's central prediction. $a_0$ is not a fundamental constant; it is an edge mode that tracks the phase clock. At high redshift, $H(z)/H_0$ grows large, and the acceleration scale that governs gravitational collapse grows with it. The consequences for early structure formation follow in Section III.

## III. Early Structure Formation at z = 10

### The Boost

Using the phase-clock $H(z)$ from the static baseline, with $\Omega_\Lambda = 0.685$ and $s_0 < 0.19$:

$$\frac{H^2(z)}{H_0^2} = \frac{1 - \Omega_\Lambda}{1 - s_0^2}(1+z)^3 - \frac{(1 - \Omega_\Lambda)\,s_0^2}{1 - s_0^2}(1+z) + \Omega_\Lambda$$

At $z = 10$, $(1+z)^3 = 1331$. The matter term dominates: $\frac{1-\Omega_\Lambda}{1-s_0^2}(1+z)^3$ contributes ~421 while the $(1+z)^1$ correction subtracts less than 0.1. The result is effectively independent of $s_0$:

$$\frac{H(z{=}10)}{H_0} \approx \sqrt{422} \approx 20.5$$

Applying the evolutionary law:

$$a_0(z{=}10) \approx 20.5 \times a_0(0) \approx 2.46 \times 10^{-9}\ \text{m/s}^2$$

The acceleration scale governing gravitational collapse at $z = 10$ is twenty times the local value.

### Collapse Dynamics

In the deep-MOND regime ($g \ll a_0$), the effective gravitational acceleration scales as $g_\text{eff} \propto \sqrt{g_N \times a_0}$. Comparing an epoch-dependent $a_0$ to the standard constant assumption:

$$\frac{g_\text{eff}(z{=}10)}{g_\text{eff}(\text{constant})} = \sqrt{\frac{a_0(z{=}10)}{a_0(0)}} = \sqrt{20.5} \approx 4.5$$

This is a factor of 4.5 enhancement in effective gravitational acceleration at fixed epoch. Both MIT and constant- $a_0$ MOND see the same $H(z)$ at $z = 10$; the difference is solely the strength of the acceleration floor.

Since free-fall timescale scales as $t_\text{ff} \propto 1/\sqrt{g}$, structures at $z = 10$ collapse approximately 2.1× faster than constant- $a_0$ MOND would predict. The enhancement is maximal in the deep-MOND limit; inner regions of forming halos where $g$ approaches $a_0(z)$ see a smaller correction, so these estimates are upper bounds.

### The Resolution

For the Labbé et al. observations requiring $\varepsilon_\text{SF} > 1$ under standard assumptions, the 2.1× faster collapse reduces the implied efficiency to $\varepsilon_\text{SF} \sim 0.5$, within the physically permitted range. The "impossibly early galaxy" problem becomes a straightforwardly early galaxy observation, requiring no exotic physics, no new particles, and no modification to general relativity.

*The acceleration scale was simply larger when those galaxies formed.*

## IV. Contrasting Predictions: Edge vs Surface

MIT's dimensional hierarchy draws a sharp line between modes that live on the temporal edge and modes that live on the spatial surface:

| Observable | Manifold depth | Evolves? | Prediction |
|---|---|---|---|
| $a_0$ (acceleration) | $n = 1$ (edge) | Yes, tracks $H(z)$ | Evolves with epoch |
| $\Lambda$ (cosmological constant) | $n = 2$ (surface) | No (antinode, slope zero) | Constant across epochs |

This is an inversion of standard assumptions, where $\Lambda$ is often treated as potentially evolving (the DESI phantom-crossing signal) while $a_0$ is assumed constant (standard MOND). MIT predicts the opposite: $\Lambda$ is topologically locked at the antinode, and $a_0$ rides the phase clock.

The companion paper (*Phantom Dark Energy: Template Artifact in Static Space*) proves that $\Lambda$ never crosses $w = -1$ and that the apparent DESI signal is a template artifact. This paper shows that $a_0$ evolves with $H(z)$ and resolves the JWST early-galaxy tension. Together, the two cornerstones embody the static universe from opposite sides: one observable constant, one evolving, both measured from the same standing wave.

Observations of both quantities at high redshift provide independent, complementary tests. A universe where $\Lambda$ evolves and $a_0$ stays constant would falsify MIT. A universe where $\Lambda$ stays constant and $a_0$ evolves would confirm it.

## V. Falsification

| Prediction | Test | Falsified if |
|---|---|---|
| $a_0(z) \propto H(z)$ | Rotation curves at $z > 2$ | $a_0(z)/a_0(0) = 1$ at $\geq 2\sigma$ |
| $\Lambda$ constant | SNe Ia / BAO at high $z$ | $\Lambda$ varies with redshift at $\geq 2\sigma$ |

At $z = 2$, the prediction is $a_0(z{=}2) \approx 3 \times a_0(0)$. This is within reach of resolved rotation curves from Euclid, JWST/NIRSpec, and the ELT. These predictions distinguish MIT from both standard MOND (constant $a_0$) and ΛCDM (no acceleration threshold).

---

**Update 1 (2026): MUSE-DARK III.** The first intermediate-redshift measurement of the acceleration scale arrived after this prediction was deposited. MUSE-DARK III (Ciocan et al., *A&A* 709) fits $a_0$ in four redshift bins from 79 galaxies in the MUSE Hubble Ultra Deep Field and finds it rising with redshift at ~30σ over 0.33 < z < 1.44, the predicted direction, against the standard-MOND constant.

<img src="https://img1.wsimg.com/isteam/ip/21cc2ac0-6dc4-4b19-93ef-6a7079ac9d3c/muse_dark_iii_a0z_three_line.png/:/rs=w:1280,h:835" width="100%" alt="The framework curve a0(0)E(z) against the two MUSE-DARK III linear fits: the MOND-frame fit sits on the framework curve through the measured window, the dark-matter DC14 fit runs steeper, and both linear fits dip toward 1.0 at z=0 against the SPARC anchor at 1.20.">

*The framework's convex $a_0(0)\,E(z)$ against the two MUSE-DARK III fits. In the MOND frame the data sit on the curve; in the better-fitting dark-matter frame they run steeper. Both linear fits dip toward 1.0 at $z = 0$ against the SPARC anchor at 1.20, the convex curve forced to a straight line. The frames disagree, so the rate is open.*

**Direction: corroborated, not yet a discriminator.** The prediction that $a_0$ evolves was logged before the measurement and came in on the right side of a ~30σ result. But a rising $a_0$ is also produced by other evolving-acceleration models and by ΛCDM simulations, so the climb alone does not single out the framework.

**Rate: decomposition-dependent.** How fast $a_0$ climbs depends on how the rotation curve is split. In the MOND frame the data sit on the framework's $a_0(0)\,E(z)$ curve; in the better-fitting dark-matter frame they run steeper than $H(z)$. Other surveys bracket the framework from both sides, so the rate is open and systematics-limited, not settled.

**Normalization: open.** The anchor $a_0(0) = 1.2$ is fixed by SPARC and echoed by the locked ratio; the comparison is limited by the tens-of-percent cross-calibration between MUSE and SPARC and by the redshift-dependent gas the model omits, not by the framework.

**Universality: the ground test cannot stand in for Euclid.** The per-galaxy test of whether a single $a_0$ holds across mass is now runnable on the public data, and it proves structurally inapplicable: the fitted dark-matter fractions stay flat with mass, which turns any apparent $a_0$ trend into a surface-density artifact degenerate with a fitting prior. The discriminator remains the mass- and aperture-independent Euclid DR1 lensing test, which reads the signal without a stellar mass-to-light scale.

This sits alongside the companion paper's standing 2.9σ trend-shape tension with the Übler KMOS3D Tully–Fisher data: the honest intermediate-redshift record is direction confirmed, details contested, clean test pending. Full comparison and caveats: [Early Galaxies, Update 1](early-galaxies-update1.md).

---

In 1983, Milgrom identified $a_0$ as a fundamental acceleration scale. For four decades the coincidence $a_0 \approx cH_0$ had no explanation. Both are edge modes; the ratio is fixed by where they sit on the standing wave. $a_0$ evolves with $H(z)$.

*The galaxies found too early were formed under a stronger tide.*

---

/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /
