/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /

---

# The Clock-Asymmetry Fit

**Status (2026-07-05):** REGISTRATION, frozen before any run. This is the P2 measurement track of the [half-power clock](friedmann-as-output.md): one premise, one parameter, nothing else. The specification below is complete enough to execute mechanically in the Λcos pipeline at its next session; results land in a single commit filling the Results section, with no re-runs, no post-hoc priors, and no added parameters. This note cannot flip any label, and it contains no entropy, Molien, or model-building content by design.

**Related:** [The Tick Lemma](tick-lemma.md) (where the family arises as the residual of L1-L3), [The Sampling Kernel's Symmetry](sampling-kernel-symmetry.md) (the theorem track; independent, and not evidence about $\epsilon$'s value), [Temporal Budget](temporal-budget.md) (the baseline model and data), [The Half-Power Clock](friedmann-as-output.md).

---

## I. The Family, Once and Target-Free

The tick lemma's graded structure (L1-L3, with exchange symmetry removed) leaves exactly one family: the kernel-asymmetry family

$$d\mu_\epsilon = w_1^{1/2-\epsilon}\, w_2^{1/2+\epsilon}, \qquad w_1 = S,\quad w_2 = S^2, \qquad\text{so}\qquad d\mu_\epsilon = S^{3/2+\epsilon}\,dt.$$

$\epsilon = 0$ **is P2**: exchange symmetry of the elementary sampling kernel. This fit measures that premise.

The observable form, which is what the pipeline fits, follows from the budget algebra exactly as in the validated Model D+Λ and is stated here so no convention enters the likelihood: with $S = s_0/(1+z)$ and $\Omega_\Lambda = 0.685$ fixed from topology as in the baseline,

$$\frac{H^2(z)}{H_0^2} = \frac{1-\Omega_\Lambda}{1-s_0^2}\,(1+z)^{3+2\epsilon} \;-\; \frac{(1-\Omega_\Lambda)\,s_0^2}{1-s_0^2}\,(1+z)^{1+2\epsilon} \;+\; \Omega_\Lambda.$$

At $\epsilon = 0$ this is the published Model D+Λ identically. The asymmetry shifts both budget exponents rigidly by $2\epsilon$; it is not a $w_0$ clone and no template comparison is part of this registration. Convention guard: the family is defined by the tick measure and, equivalently, by this $H^2(z)$ formula; the labeling of intermediate times (which ladder rung is called proper or conformal) does not enter the likelihood and is not adjudicated here.

---

## II. The Slice Table (frozen; the family is not new)

The continuous family is the one-parameter closure of clocks already tested; it unifies the dead rows with the live one rather than being invented to rescue a result. Leading behavior of $H$ is $(1+z)^{3/2+\epsilon}$.

| $\epsilon$ | $H$ leading | Identity | Status |
|---|---|---|---|
| $-3/2$ | $(1+z)^{0}$ | Model C | dead, $+7276.6$ |
| $-1/2$ | $(1+z)^{1}$ | Model A | dead, $+218.7$ |
| $0$ | $(1+z)^{3/2}$ | Model D+Λ, the symmetric kernel | alive, $+0.11$ |
| $+1/2$ | $(1+z)^{2}$ | Model B | dead, $+1821.9$ |
| $+1$ | $(1+z)^{5/2}$ | the completing fit registered at gate (i) | expected dead |

The tabulated $\Delta\chi^2$ values are the budget page's; the Tier-1 run recomputes the full curve on the same data, so no cross-paper normalization is assumed. The run discharges the $\epsilon = +1$ registration as one of its slices; one session pays both debts.

---

## III. Data, Parameters, Priors (frozen)

Data and likelihood: identical to the published Λcos baseline (Pantheon+ 1701 SNe Ia with full covariance; DESI DR2 BAO, 13 points; same distance machinery and $r_d$ treatment). Parameters: $(H_0, s_0, \epsilon)$, with $\Omega_\Lambda = 0.685$ fixed exactly as the baseline fixed it; $\Omega_\Lambda$ variation is out of scope for this registration. Priors: $H_0$ and $s_0$ as in the baseline ($s_0$ flat on $[0, 1)$); $\epsilon$ flat on $[-1.6,\ +1.1]$, chosen once to cover every previously tested slice, with no alternate priors before or after the run.

**Two tiers, both frozen now.**

1. **Tier 1, diagnostic profile.** On a grid in $\epsilon$, profile the likelihood over $(H_0, s_0)$ and report the $\Delta\chi^2(\epsilon)$ curve, with 68% and 95% intervals read from it, plus the curve's values at the four dead slices.
2. **Tier 2, joint posterior.** Full MCMC over $(H_0, s_0, \epsilon)$ under the frozen priors; report the marginal $\epsilon$ posterior and the $(s_0, \epsilon)$ correlation structure. The strength criterion is pre-stated: $\epsilon \approx 0$ must survive marginalization over $s_0$. If $\epsilon$ is constrained only when $s_0$ is pinned by hand, the result is recorded as weaker, whatever the headline number. Expected identifiability, noted in advance: at $s_0 \to 0$ the model reduces to $(1-\Omega_\Lambda)(1+z)^{3+2\epsilon} + \Omega_\Lambda$, so $\epsilon$ remains constrained by the matter-exponent deformation even in the ΛCDM limit; degeneracy with $s_0$ is not expected to erase the measurement.

---

## IV. Registered Expectation and the Verdict Table (frozen)

**Expectation, stated before any run:** $\epsilon$ consistent with zero. Width forecast from quadratic interpolation of the walls: $\sigma_+ \approx 0.5/\sqrt{1821.9} \approx 0.012$ and $\sigma_- \approx 0.5/\sqrt{218.7} \approx 0.034$, so a 68% interval of order a few hundredths, asymmetric, tighter above than below.

**The bar, stated plainly: "zero allowed" is not enough.** A broad posterior that merely includes zero is non-falsification, not measurement. The meaningful-measurement bar is pre-set: both 68% half-widths at or below $0.05$.

| $\epsilon$ result | Verdict |
|---|---|
| zero inside the 68% interval AND both half-widths $\leq 0.05$ | P2 empirically supported as the observationally selected point of the registered family; proceed to the ledgered flip discussion |
| interval includes zero but a half-width exceeds $0.05$ | measurement inconclusive; no flip; recorded as such |
| zero excluded at 95% | P2 challenged; inspect R1 and R2 per [the chase note](sampling-kernel-symmetry.md), and downgrade the tick lemma per its own failure bar |
| $\hat\epsilon$ within $0.1$ of a dead slice, or a multimodal posterior | route failure or pipeline inconsistency; investigate before any physics claim |

---

## V. The Flip Precondition (restated, verbatim standard)

The budget page's label may change only to the ledgered form, only from the first verdict row, and only after review:

> DERIVED conditional on P1 and P2, with P1 definitional and P2 supported by the kernel-symmetry reduction plus the $\epsilon$-family constraint.

Not a bare word. This registration is the constraint's source; it is not the flip's authority.

---

## Results

*Not yet run. This section is filled by the execution commit from the Λcos session and by nothing else.*

---

*One premise, one parameter, one run. The family was always there; the fit reads the dial.*

---

/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /
