/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /

---

# Redshift and Cooling

How a static universe reddens light and cools a thermal bath, both read off the temporal budget's state $S$. Redshift is the phase-ratio mechanism; cooling is that same ratio applied to a blackbody.

**Status:** Redshift mechanism in outline (the phase ratio on the standing wave); the full derivation from the postulate to the observed $H(z)$ is partially walked. Cooling is ESTABLISHED as a kinematic equivalence with the FLRW thermal law. Both are readings of the temporal budget; the distance side rides on the Waltz clock.

**Dependencies:** Temporal budget identity $\Psi^2 + S^2 = 1$; the standing wave $\Psi = \cos(t/2)$ on the temporal edge; the Waltz clock (distances).

**Related:** [The Budget Map](budget-map.md), [The Temporal Budget Identity](temporal-budget.md), [Entropy as Realization Budget](entropy-as-realization-budget.md), [Dark Energy](../../../../cosmos/files/dark-energy.md) (the distance-redshift relation), [The Waltz](../../../../spectrum/files/the-waltz.md).

---

## I. Redshift is a phase ratio

The space is static. What advances is the observer's phase along the standing wave on the Möbius temporal edge. A photon emitted at phase $t_\text{emit}$ and observed at phase $t_\text{obs}$ is reddened by the ratio of the realization amplitude $S = \sin(t/2)$ at the two phases:

$$1 + z = \frac{S(t_\text{obs})}{S(t_\text{emit})}, \qquad \frac{E_\text{obs}}{E_\text{emit}} = \frac{\lambda_\text{emit}}{\lambda_\text{obs}} = \frac{S(t_\text{emit})}{S(t_\text{obs})} = \frac{1}{1+z}.$$

No space stretches. The reddening is the difference in phase position between emission and observation on a fixed domain, sampling rather than stretching. The mechanism is understood in outline; the full chain from the postulate to the observed $H(z)$ is partially walked (temporal budget §X).

**This is not tired light.** Tired light bleeds photon energy to scattering and smears both the image and the spectrum. Here every wavelength scales by the single factor $S(t_\text{emit})/S(t_\text{obs})$, a uniform rescaling that preserves the spectral shape and keeps point sources sharp. The blackbody stays a blackbody (§II); the image stays focused.

## II. Cooling is redshift of the bath

Cooling is the same phase ratio applied to a thermal ensemble instead of a single photon. A space-filling radiation bath in a static space at fixed volume has no exterior to radiate into, so in such a space a bath holds its temperature indefinitely: cooling has to be earned, not assumed.

The budget earns it. At early phase ($t \to 0$), $\Psi^2 \approx 1$ and $S^2 \approx 0$: nearly all budget weight resides in the standing wave, the unresolved background. As the phase advances, $S$ grows and $\Psi$ shrinks; weight transfers from $\Psi^2$ into $S^2$, from unresolved wave into realized modes. The total is conserved ($\Psi^2 + S^2 = 1$), but the partition shifts.

Because every wavelength scales by the same $S(t_\text{emit})/S(t_\text{obs})$, a blackbody at emission stays a blackbody at observation, only cooler:

$$T \propto \frac{1}{S} \propto (1 + z).$$

The cooling is internal redistribution within a closed budget, not leakage into an exterior.

**Status.** ESTABLISHED as a kinematic equivalence with the FLRW thermal redshift law, where $T \propto 1/a$ and the scale factor $a$ plays the role of $S$. At the kinematic level the equivalence is exact: if one variable governs both photon redshift and temperature, a blackbody stays a blackbody with $T \propto 1/S$. First-principles derivation from the postulate, including the photon phase-space density, remains OPEN. The entropy that accompanies the cooling is a separate reading of $S$, handled in [Entropy as Realization Budget](entropy-as-realization-budget.md).

## III. The observable side: distances

The phase ratio gives $1 + z$; turning it into observed distances and $H(z)$ needs the clock. The Waltz clock $dt/d\tau = S^{-1/2}$ converts budget phase to conformal time, the distance-redshift relation is worked out in [dark-energy §II](../../../../cosmos/files/dark-energy.md), and the joint fit to Pantheon+ and DESI DR2 BAO sits in [temporal budget §II-III](temporal-budget.md). The mechanism here supplies $1 + z$; the clock supplies the map from $1 + z$ to distance.

## IV. What this is not

**Expansion.** The space is static $S^3$. Redshift is the observer's phase advance on the standing wave, and cooling is that advance applied to the bath. Neither invokes a growing scale factor; the FLRW forms are recovered kinematically, with $S$ in the role $a$ plays.

**Tired light.** The shift is a uniform energy rescaling, not a scattering loss, so it preserves the blackbody spectrum and the sharpness of the image (§I).

## V. Where it stands

| Piece | Status |
|---|---|
| Redshift as phase ratio, $1 + z = S(t_\text{obs})/S(t_\text{emit})$ | mechanism in outline; full derivation partially walked |
| Blackbody preserved, $T \propto 1/S$ | ESTABLISHED as kinematic equivalence (FLRW thermal law) |
| Distance-redshift and $H(z)$ | ESTABLISHED at model level via the clock ($\Delta\chi^2 = +0.11$ vs ΛCDM, SN+BAO) |
| Cooling from the postulate (photon phase-space density) | OPEN |

## VI. Open questions

**Where the redshifted energy goes.** On static $S^3$ the time-translation Killing vector makes energy conservation structural, unlike FLRW, which has no global time symmetry; so every redshifted photon is an accounting entry that needs a counterparty. The budget answer is that the energy moves with the transfer $\Psi^2 \to S^2$, from the photon sector into the realized modes, which makes redshift a real energy transfer and not only a coordinate effect. Writing the realized-sector energy $E(S)$ closes this, and the same $E(S)$ feeds the entropy reading ([Entropy as Realization Budget](entropy-as-realization-budget.md) §VIII). Highest-leverage open question for the budget.

**A thermal observable: distortion or $T(z)$ deviation.** Cooling as an exactly uniform rescaling predicts no spectral distortion, a clean FIRAS-consistent claim worth stating outright. If $E(S)$ instead demands a non-adiabatic $\Psi^2 \to S^2$ energy exchange, it would leave a $\mu$ or $y$ distortion within reach of PIXIE-class experiments, or bend the temperature law to $T(z) = T_0 (1+z)^{1-\beta}$ (tested by SZ clusters and quasar absorption lines). Either way the thermal sector gains a falsifiable handle. Downstream of $E(S)$.

---

*The universe does not stretch the light. The observer reads it from farther along the wave.*

---

/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /
