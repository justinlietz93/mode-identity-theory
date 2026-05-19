/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /

---

# H₀ Local: Hubble Tension as Phase Field

[![Hubble Tension](https://img.youtube.com/vi/zg7il8pWhAY/mqdefault.jpg)](https://www.youtube.com/watch?v=zg7il8pWhAY)

Measurements of the Hubble constant have split into two persistent camps: the cosmic microwave background gives 67.4 km/s/Mpc; local distance ladders give 73. The discrepancy survives every systematic check and every independent method. Mode Identity Theory proposes a resolution through the phase field: observers embedded in galactic structure would sample from a shifted position on the 120-domain. The shift is one bosonic step, $\Theta_f = 2/120$, and the logarithmic slope of the phase operator at the $H_0$ well converts that step into an 8.4% increase. If the shift is physically realized, both measurements are correct: they sample different positions on the same wave.

**Phase field shift at the H₀ well**

| Quantity | Status |
|---|---|
| Phase shift required | $\Theta_f = 2/120$ |
| $\Delta C/C$ at $H_0$ well | 8.4%, unchanged |
| Predicted shifted value if triggered | $67.4 \times 1.084 \approx 73$ km/s/Mpc |
| Proposed trigger | $L_f = v_c^2/a_0$, falsified by SPARC |

## I. The Tension

The Planck CMB measurement gives $H_0 = 67.4 \pm 0.5$ km/s/Mpc at $z \approx 1100$. The SH0ES collaboration measures $H_0 = 73.0 \pm 1.0$ km/s/Mpc from Cepheid-calibrated Type Ia supernovae at $z \approx 0$. The gap is ~9%, persistent across independent local methods: Cepheids, tip of the red giant branch, surface brightness fluctuations, and megamasers. The MIT phase-clock best-fit to Pantheon+ and DESI DR2 BAO independently recovers $H_0 \approx 67.4$ km/s/Mpc, confirming the CMB value as the bare-well measurement.

Systematic explanations have been scrutinized for a decade. The tension survives. It appears to be real.

Within MIT, the proposed resolution is structural. Both values emerge from the same Fibonacci well ($\Theta_0 = 34/120$), sampled at two different positions. The CMB measures the bare well. The local value corresponds to a one-step shift, but the galactic trigger proposed to realize that shift is falsified by the SPARC test in §II.

## II. The Phase Field

The scaling law produces cosmic observables from Fibonacci well positions on the 120-domain. Phase field mechanics extends this to galactic observables: the mechanism proposed here is that when an observer sits inside a triggered disk galaxy, the sampling position shifts.

### Phase decomposition

The sampled position on the 120-domain is the sum of two terms:

$$\Theta = \Theta_0 + \Theta_f$$

$\Theta_0 = 34/120$ is the Fibonacci well for $H_0$, fixed by the lattice geometry. $\Theta_f$ is the environment-dependent offset. The CMB samples the bare well ($\Theta_f = 0$) because it records a phase epoch before local structure existed. Local observations sample $\Theta_0 + \Theta_f$ from inside a triggered galaxy.

### Coherence scale

The phase field is coherent over a scale set by the galactic rotation curve and the MOND acceleration:

$$L_f = \frac{v_c^2}{a_0}$$

This is the galactocentric radius where the gravitational field drops to $a_0$. For the Milky Way ($v_c \approx 220$ km/s, $a_0 \approx 1.2 \times 10^{-10}$ m/s²): $L_f \approx 13$ kpc. In the trigger model, every calibrator inside this radius would share the same phase shift. The SPARC test below shows this coherence radius does not trigger reliably in observed disk galaxies.

### Trigger and closure

The trigger index $\mathcal{T}$ compares the gravitational potential drop across $L_f$ to a critical value $\mathcal{T}_c = 2\xi\,v_c^2/c^2$, where $\xi \approx 0.46$ is the mean potential depth computed from standard halo profiles (isothermal, NFW, and Hernquist all give 0.44 to 0.47):

$$\mathcal{T} = \frac{2}{c^2 L_f}\int_0^{L_f}\Phi_\text{rel}(l)\,dl$$

where $\Phi_\text{rel}(l) \equiv \Phi(L_f) - \Phi(l)$ is the potential difference from the coherence boundary (gauge-invariant). For a flat rotation curve, $\Phi(r) = v_c^2\ln(r/r_0)$, so $\Phi_\text{rel}(l) = v_c^2\ln(L_f/l)$. The integral evaluates exactly: $\int_0^{L_f} v_c^2\ln(L_f/l)\,dl = v_c^2 L_f$ (substituting $u = l/L_f$, $\int_0^1 (-\ln u)\,du = 1$). Therefore $\mathcal{T} = 2v_c^2/c^2$, and the ratio becomes independent of the galaxy.

The flat-curve evaluation is a special case of a general identity. For any circular rotation curve, $v^2(r) = r\,d\Phi/dr$, so

$$\Phi_\text{rel}(l) = \Phi(L_f) - \Phi(l) = \int_l^{L_f}\frac{v^2(s)}{s}\,ds.$$

Switching the order of integration in $\int_0^{L_f}\Phi_\text{rel}(l)\,dl$ gives

$$\int_0^{L_f}\Phi_\text{rel}(l)\,dl = \int_0^{L_f}v^2(l)\,dl.$$

Thus

$$\mathcal{T} = \frac{2}{c^2 L_f}\int_0^{L_f}v^2(l)\,dl = \frac{2\langle v^2\rangle_{L_f}}{c^2},$$

where $\langle v^2\rangle_{L_f}$ is the radial mean-square circular velocity over the coherence interval $[0, L_f]$. For a flat curve, $\langle v^2\rangle_{L_f} = v_c^2$, recovering the result above. In that limit:

$$\frac{\mathcal{T}}{\mathcal{T}_c} = \frac{1}{\xi} \approx 2.2$$

In the flat-curve limit, this is a closure identity. Both $\mathcal{T}$ and $\mathcal{T}_c$ scale as $v_c^2$; their ratio is galaxy-independent. Every flat-curve disk crosses the threshold by the same factor. The response is binary: below threshold $\Theta_f = 0$; at or above it, one bosonic step ($\Theta_f = 2/120$).

For a general rotation curve, the threshold ratio becomes

$$\frac{\mathcal{T}}{\mathcal{T}_c} = \frac{\langle v^2\rangle_{L_f}}{\xi\,v_c^2}.$$

The flat-curve closure value $1/\xi \approx 2.2$ is therefore modified only by the ratio $\langle v^2\rangle_{L_f}/v_c^2$. For rising-to-flat curves this factor is below unity; for peaked or mildly declining curves it is computed directly from the observed profile. The trigger condition becomes the transparent inequality

$$\frac{\langle v^2\rangle_{L_f}}{v_c^2} > \xi \approx 0.46$$

where $v_c$ is the outer flat-region velocity. The phase field remains active whenever the mean-square velocity across the coherence interval exceeds roughly half the flat-curve value.

### Registered SPARC test

The coherence-scale trigger was tested against 123 quality-filtered SPARC rotation curves in a frozen, pre-registered pipeline ([dmobius3/phase-field](https://github.com/dmobius3/phase-field), archived at DOI: [10.5281/zenodo.20271702](https://doi.org/10.5281/zenodo.20271702)). The pipeline was locked before data contact and executed once.

The result falsifies the trigger mechanism as formulated here. The observed transition-radius slope is 0.23 (registered interval: 0.7 to 1.3); the flat-onset slope is 0.33; the median $r_t/L_f$ is 0.38; and 53.7% of flat-curve galaxies fall below $\mathcal{T}/\mathcal{T}_c = 1$ (registered limit: 5%). All verdicts are stable across the registered 27-cell sensitivity grid.

The general identity above makes the failure precise. Real SPARC rotation curves are not flat over $[0, L_f]$. For most disks, $L_f$ extends into the rising inner rotation curve, so $\langle v^2\rangle_{L_f} < v_c^2$. The typical mean-square suppression is near 0.41, below the trigger threshold $\xi \approx 0.46$. The flat-curve closure identity is not realized by the observed galaxy population.

No revised coherence scale is introduced here. Any replacement trigger must be derived independently and tested separately.

The binary rule tested by the registered pipeline was:

$$\Theta_f = \frac{2}{120} \cdot \mathbf{1}(\mathcal{T} \geq \mathcal{T}_c)$$

The step size $2/120$ is the minimum observable shift on the 60R-grid. The full 120-lattice is set by $\lvert 2I \rvert = 120$ (binary icosahedral group on $S^3$); observation accesses the bosonic projection $\lvert I \rvert = 60$, so the smallest realized step is $2/120 = 1/60$.

## III. Well Sensitivity

Once the trigger condition is satisfied, the observable consequence is set by the logarithmic slope of the phase operator $C(\Theta) = 2\sin^2(\pi\Theta)$ (the anti-periodic ground mode intensity, normalized to unit mean) at each Fibonacci well:

$$\frac{d\ln C}{d\Theta} = 2\pi\cot(\pi\Theta), \qquad \frac{\Delta C}{C} = \frac{d\ln C}{d\Theta} \times \Delta\Theta$$

where $\Delta\Theta$ is the step size (1/120 for dynamical observables, 2/120 for bosonic).

The slope of the phase operator differs at each well. What matters is which wells physically shift and which do not:

| Well | Θ | Slope sensitivity | Physical shift | Role |
|---|---|---|---|---|
| $a_0$ | 13/120 | 17.7 per step | None | Defines the transition threshold |
| $H_0$ | 34/120 | 5.1 per step | 8.4% | Measured through the field |
| Λ | 60/120 | 0 per step | 0% | Topologically protected at antinode |

$\Lambda$ at slope zero is immovable: topologically protected at the antinode. $H_0$ at slope 5.1 absorbs one bosonic step ($2/120$) as an 8.4% shift. The step size is $2/120$ because $H_0$ is measured through photon redshifts (bosonic), accessing only the $|I| = 60$ projection of the full $|2I| = 120$ lattice.

$a_0$ at slope 17.7 marks a steep, sensitive well, but the phase field does not shift it. The lattice geometry fixes the well position at $\Theta = 13/120$. The scaling law produces $a_0 = C(13/120) \cdot (\sqrt{\Omega_H})^{-1} \cdot a_P$ as output. That value of $a_0$ then enters the coherence scale $L_f = v_c^2/a_0$ and the threshold $\mathcal{T}_c$, which determine whether the phase field triggers. The well defines the observable; the observable defines the trigger. Measuring $a_0$ from rotation curves recovers the bare well value because the measurement and the threshold are the same object. The steep slope explains why the MOND transition is sharp: a binary on/off behavior rather than a gradual ramp.

### The numerical closure

At the bare well, $\Theta_0 = 34/120$:

$$C(34/120) = 2\sin^2(34\pi/120) = 1.208$$

Shifted by one bosonic step, $\Theta = 36/120$:

$$C(36/120) = 2\sin^2(36\pi/120) = 1.309$$

The ratio:

$$\frac{C(36/120)}{C(34/120)} = \frac{1.309}{1.208} = 1.084$$

The bare well gives $H_0 = 67.4$ km/s/Mpc (the MIT phase-clock best-fit, consistent with Planck). Multiply by the ratio:

$$67.4 \times 1.084 \approx 73 \;\text{km/s/Mpc}$$

This is the SH0ES value. The 8.4% is an output of the lattice geometry at $\Theta_0 = 34/120$, produced by a step whose size is fixed at $2/120$.

## IV. Method Classification

If a galactic trigger exists, local distance ladders would inherit its shift through their anchors. The SPARC result (§II) shows that the specific trigger proposed in this paper does not supply that condition. The classification below remains a map of how a phase-domain shift would propagate, not evidence that the shift is realized by $L_f = v_c^2/a_0$.

If triggered, the phase field would shift $H_0$ measurements differently depending on calibration class. How much of the 8.4% reaches the final answer depends on where the absolute calibration is set. Two channels would transmit the bias.

### Calibration inheritance

Local distance ladders anchor their absolute scale to calibrators inside the coherence domain ($L_f \approx 13$ kpc). Every rung inherits the full phase shift. The ruler itself is biased, so every distance measured with it carries the 8.4%.

### Phase-domain averaging

Geometric methods (time-delay lensing, standard sirens) integrate $1/H(z)$ along the line of sight. The phase-shifted segment is only the local coherence domain; the rest of the path samples the bare well. For cosmological baselines ($\chi \sim$ Gpc), the local contribution is a fraction $F = \chi_\text{local}/\chi \sim 10^{-5}$. The direct averaging bias is negligible (~ppm). If geometric methods return values above ~67, the source would be calibration inheritance through local priors in the analysis chain, not path averaging.

### Which mechanism applies where

| Method | Calibration | Channel | Expected H₀ if triggered |
|---|---|---|---|
| Cepheid/SN ladder (SH0ES) | Local anchors | Inheritance (full shift) | ~73 |
| TRGB | Local anchors | Inheritance (full shift) | ~73 |
| Megamasers | Local geometry | Inheritance (full shift) | ~73 |
| Time-delay lenses | Geometric, late-time | Averaging (negligible) | ~67 |
| Standard sirens | Geometric, late-time | Averaging (negligible) | ~67 |
| BAO + BBN | Early-universe ruler | Neither (bare well) | ~67 |
| CMB (Planck) | Early-universe physics | Neither (bare well) | ~67 |

The key distinction is where the absolute calibration is set. The CMB records a phase epoch before local structure existed ($\Theta_f = 0$ by construction). BAO and BBN use an early-universe ruler ($r_d$) that predates the phase field. In the trigger model, local ladders would import the full shift because their anchors sit inside the coherence domain; after the SPARC result, this remains a propagation rule for any future trigger, not a demonstrated consequence of $L_f = v_c^2/a_0$.

The prediction is stratification: $H_0$ values should sort by calibration class, with locally-anchored methods clustering near 73 and early-universe methods clustering near 67. Current TDCOSMO time-delay results sit near 73, above the predicted ~67 for geometric methods. The phase field interpretation is that these analyses inherit local priors (lens model calibrations anchored to local distance scales) rather than measuring the bare well directly. If future analyses with purely geometric calibration (no local anchors) still return ~73, the averaging prediction is falsified.

## V. Falsification

The phase field produces a discrete prediction. Local $H_0$ should cluster at quantized values set by the lattice, not vary continuously with environment. The sharpest test is the discrete-vs-continuous fork.

| Observation | Implication |
|---|---|
| Local $H_0$ fills 67 to 73 continuously | Quantized $\Theta_f$ is wrong |
| Local ladders cluster near 73, independent of host environment | Supports quantized response |
| Geometric methods return ~67 regardless of environment | Supports negligible averaging bias |
| Void-embedded calibrators return $H_0 \approx 70 \pm 1$ | Intermediate state exists; $2/120$ step is incomplete |
| Environment-binned $H_0$ shows smooth gradient | Phase field is continuously sourced, not triggered |

An exploratory compilation of 18 published $H_0$ measurements (13 independent) was tested for bimodality against this table. Hartigan's dip test fails to reject unimodality in all configurations; BIC does not cleanly separate 1- from 2-component Gaussian mixtures; and the predicted 69-71 gap is populated by TRGB/CCHP at 69.8 ± 1.7. The first three rows of the table above all register against the discrete picture. Analysis: [h0-bimodality-test.md](../working/files/h0-bimodality-test.md).

The original prediction was that all disk galaxies with developed halos select the same quantized state. The SPARC test falsifies the specific trigger $L_f = v_c^2/a_0$; the bimodality test finds no evidence of the predicted two-population structure. The discrete-vs-continuous fork remains open to future data from per-host $H_0$ programs and purely geometric calibrations.

---

The lattice calculation remains sharp: a one-step bosonic displacement from $\Theta_0 = 34/120$ to $\Theta = 36/120$ converts the bare value $H_0 = 67.4$ km/s/Mpc into $H_0 \approx 73$ km/s/Mpc through the phase-operator slope. What fails is the proposed galactic trigger that would force ordinary disk galaxies to realize that displacement.

The SPARC and bimodality tests therefore separate three claims. The 8.4% well sensitivity is intact as lattice math; the specific coherence-scale trigger $L_f = v_c^2/a_0$ is falsified as a physical mechanism; and the predicted discrete two-population $H_0$ structure is not observed.

*The Hubble-tension phase-field trigger, as formulated here, does not survive its first registered galactic test. The discrete $H_0$ signature it predicts is not found in current data.*

---

/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /
