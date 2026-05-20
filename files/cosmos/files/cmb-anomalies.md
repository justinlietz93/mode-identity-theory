/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /

---

# CMB Anomalies from Topology

[![CMB Anomalies](https://img.youtube.com/vi/B-cQsP-ul_E/mqdefault.jpg)](https://www.youtube.com/watch?v=B-cQsP-ul_E)

Four large-angle CMB features have persisted across COBE, WMAP, and Planck with no explanation within ΛCDM. The Möbius embedding in S³ restricts the mode spectrum at large scales through the Molien gap of the binary icosahedral group, breaks even-odd symmetry through the non-orientable identification, suppresses the quadrupole through radial projection, and defines a preferred axis as the twist normal. What has been called the "axis of evil" may be the universe revealing the geometry of its beginning.

**Four predictions, one consistency check, one locality cost**

| Feature | Predicted | Observed |
|---|---|---|
| Mode density transition | Molien gap ends at ℓ ≈ 29 | deficit below ℓ ≲ 30 |
| Quadrupole suppression | ℓ = 2 suppressed by Molien gap + radial projection | anomalously low C₂ |
| Parity sign | R<sub>TT</sub> < 1 | R<sub>TT</sub> ≈ 0.81 |
| Parity magnitude | R<sub>TT</sub> ≈ 0.81 | R<sub>TT</sub> ≈ 0.81 |
| Preferred axis | exists | Δθ₂₃ ≈ 10° |
| $\Lambda$ from CMB-constrained $R$ | $1.12 \times 10^{-52}$ m⁻² | $1.11 \times 10^{-52}$ m⁻² |

One position in S³, five observables.

---

## I. The Anomalies

The cosmic microwave background provides a remarkably clean window into the early universe. Precision measurements from COBE, WMAP, and Planck have confirmed the standard cosmological model across a wide range of angular scales. Yet at the largest angles, multipoles ℓ < 30, several unexpected features have persisted across all three missions.

**Low-ℓ boundary.** The angular power spectrum shows less power at low ℓ than the best-fit ΛCDM model predicts. The deficit below ℓ ≲ 30 has been documented since COBE and confirmed with increasing precision by each successor.

**Anomalous quadrupole.** The quadrupole (ℓ = 2) is anomalously low relative to the octupole (ℓ = 3) and higher multipoles, a feature distinct from the broad low-ℓ deficit.

**Parity asymmetry.** Odd-ℓ multipoles contain more power than even-ℓ multipoles at large scales. The Planck TT parity ratio R<sub>TT</sub>(ℓ_max = 30) ≈ 0.81 (the ratio of even-ℓ to odd-ℓ power), where unity indicates no preference.

**Quadrupole-octupole alignment.** The preferred axes of the quadrupole (ℓ = 2) and octupole (ℓ = 3) align to within approximately 10°, an arrangement expected in only 1 to 3% of statistically isotropic realizations. This feature is sometimes called the "axis of evil," as though the cosmos owed us uniformity.

Each anomaly is modest in isolation, typically 2 to 3σ. Together, they suggest correlated large-angle structure that statistical isotropy does not anticipate. For two decades, each has been documented with increasing precision and labeled a fluke.

---

## II. The Geometry

Mode Identity Theory proposes a nested topology: S¹ is the edge of the Möbius surface, which is embedded in the hypersphere S³.

$$S^1 = \partial(\text{Möbius}) \hookrightarrow S^3, \quad \partial S^3 = \emptyset$$

The hierarchy terminates at S³ because ∂S³ = ∅. S³ is the unique simply-connected closed 3-manifold. The observable domain is the quotient $S^3/2I$, where $2I$ is the binary icosahedral group ($|2I| = 120$), the largest exceptional discrete subgroup of SU(2) $\cong$ S³.

### A. Scale

The topology is a shape, not a size. The postulate fixes the nested structure ($S^1$, Möbius, $S^3/2I$) but leaves the curvature radius $R$ of $S^3$ as a free geometric parameter. $R$ is a fixed property of the manifold, not a time-dependent scale. Space does not expand; the observed redshift arises from the phase evolution of the cosmic standing wave on $S^1 = \partial(\text{Möbius})$.

The Molien gap (§II.C) constrains which harmonic modes exist on the spatial domain. Each surviving shell maps to a characteristic multipole on the CMB sky through $\ell_{\mathrm{char}}(N) = \sqrt{N(N+2)}\,\chi_*/R$, where $\chi_* \approx 14.0$ Gpc is the comoving distance to last scattering. The observed deficit boundary near $\ell \sim 30$ requires $R$ in a specific range. The parity magnitude and quadrupole ratio then fix the observer distance $d$ at that $R$. Section III derives these constraints; the resulting value is $R \approx 5.2\text{--}5.4$ Gpc. Section V shows that this CMB-constrained $R$ independently recovers the observed cosmological constant through $\Lambda = 3/R^2$ to within 2%.

The phase-clock distance-redshift relation contains no $(1+z)^2$ curvature term: $H^2/H_0^2 = \alpha(1+z)^3 - \beta(1+z) + \Omega_\Lambda$, where $\alpha$ and $\beta$ are controlled by a single parameter $s_0$ constrained to $s_0 < 0.19$ by Pantheon+ and DESI DR2 BAO at $\Delta\chi^2 = +0.11$ relative to flat ΛCDM. The absence of $(1+z)^2$ is not an inconsistency; the spatial curvature is a static boundary condition producing the mode spectrum, not a dynamical term competing with $\Lambda$. The apparent spatial curvature $\Omega_K$ inferred from standard FLRW fits is forced to zero because the true distance-redshift relation contains no $(1+z)^2$ term. The comoving distance to last scattering is $\chi_* \approx 14.0$ Gpc (dominated by the matter era, where the phase-clock and ΛCDM integrands differ by less than 0.3%; the $(1+z)^1$ correction contributes ~0.02 out of ~400 at recombination).

### B. The Möbius Surface

The covering $S^2 \subset S^3$ is totally geodesic ($K_{ij} = 0$). The quotient $S^3/2I$ is an orientable 3-manifold; the binary icosahedral group preserves orientation under left multiplication. The non-orientable structure resides on the embedded 2-dimensional surface, not on the spatial manifold itself. The Möbius band is constructed from a spherical band on this $S^2$ by the boundary-edge identification $(0, w) \sim (\pi R, -w)$. The band is a surface within $S^3/2I$; the construction does not re-quotient the spatial domain. The induced metric is $ds^2 = dy^2 + \cos^2(y/R)\,dw^2$, carrying constant Gaussian curvature $K = 1/R^2$. Fields coupled to the surface's orientation structure (sections of the orientation line bundle) satisfy anti-periodic boundary conditions: traversing the strip once flips the sign; two traversals return to the start.

The surface is not incidental to the 3D spectrum. The ground eigenfunction on the Möbius band (eigenvalue $\lambda_0 = 2/R^2$) sets the spectral floor for the entire domain: it is the lowest nontrivial mode of the twisted Laplacian, and its eigenvalue determines $\Lambda$. Fields on $S^3/2I$ decompose into representations of $2I$; representations whose restriction to the normal bundle of the totally geodesic surface is nontrivial inherit the anti-periodic boundary conditions. The even-<i>ℓ</i> suppression ($R_{TT} < 1$) follows because anti-periodic modes have a higher eigenvalue floor than periodic modes, systematically reducing even-<i>ℓ</i> power in the Gegenbauer projection onto the observer's sky.

### C. The Molien Spectrum

Scalar harmonics on $S^3$ are graded by polynomial degree $N = 0, 1, 2, \ldots$ with eigenvalue $N(N+2)/R^2$ and degeneracy $(N+1)^2$. On the quotient $S^3/2I$, only $2I$-invariant harmonics survive. The center $\{-1\} \in 2I$ acts on degree $N$ by $(-1)^N$, restricting invariants to even $N$. Among these, the Molien series for the invariant ring of $2I$:

$$P(t) = \frac{1 - t^{60}}{(1 - t^{12})(1 - t^{20})(1 - t^{30})}$$

shows the first nontrivial invariant at $N = 12$. Five even-degree shells ($N = 2, 4, 6, 8, 10$) are empty. The surviving shells are $N = 0, 12, 20, 24, 30, 32, 36, 40, \ldots$, with the generators at degrees 12, 20, and 30 corresponding to the three Klein icosahedral invariants.

The same McKay filtering that produces the Yang-Mills spectral gap on $S^3/2I$ (applied to the adjoint representation) produces the CMB mode deficit here (applied to the trivial representation). One group, one graph, two applications.

### D. Observer Position

The observer sits at geodesic distance $d$ from the center of the fundamental domain in $S^3/2I$. This is the single locality parameter. At the observer's position, each surviving shell $N$ projects onto the sky sphere as a superposition of angular multipoles $\ell = 0, 1, \ldots, N$, with the radial profile:

$$\Pi_{N\ell}(\chi) \propto (\sin\chi)^\ell \, C^{(\ell+1)}_{N-\ell}(\cos\chi)$$

where $\chi = d/R$ is the observer's angular position in $S^3$.

| Parameter | Value | Source |
|---|---|---|
| $R$ | 5.2--5.4 Gpc | Constrained by CMB observables (§III); recovers $\Lambda$ via $3/R^2$ (§V) |
| $d$ | 2.1 Gpc | Determined by four CMB observables |
| $\chi$ | 0.40 rad | $d/R$; about 25% from pole to equator of $S^3$ |
| $\chi_*$ | 14.0 Gpc | Comoving distance to last scattering |

---

## III. Predictions

### A. Low-ℓ Deficit

The Molien gap produces a mode density deficit at large angular scales. Each shell $N$ on $S^3$ maps to a characteristic multipole on the CMB sky:

$$\ell_{\mathrm{char}}(N) = \frac{\sqrt{N(N+2)}}{R}\,\chi_*$$

The last empty shell ($N = 10$) has $\ell_{\mathrm{char}} \approx 29$. The first surviving shell ($N = 12$) has $\ell_{\mathrm{char}} \approx 34$. These values follow from $R \approx 5.3$ Gpc, which is itself constrained by the observed deficit: inverting the formula, the deficit boundary at $\ell \sim 30$ requires $R = \sqrt{N(N+2)}\,\chi_*/\ell_{\mathrm{char}} \approx 5.1\text{--}5.5$ Gpc. Below $\ell \sim 30$, the scalar mode spectrum is sparse: only the constant mode ($N = 0$) exists. Above $\ell \sim 34$, modes begin to populate. This is a transition, not a wall, consistent with the observed gradual deficit.

Observed: power deficit below $\ell \lesssim 30$.

### B. Quadrupole Suppression

The quadrupole ($\ell = 2$) is suppressed by two mechanisms acting together.

The Molien gap removes shells $N = 2$ through 10 that would primarily feed power into $\ell = 2$. The first surviving shell ($N = 12$) contributes to $\ell = 2$ only through the tail of its radial profile.

The observer position amplifies the suppression. At $\chi = 0.40$ rad, the radial profile $\Pi_{12,\ell}(\chi) \propto \sin^\ell(\chi)$ peaks at $\ell = 3$ to 4, further suppressing the $\ell = 2$ component relative to $\ell = 3$.

At $d = 2.1$ Gpc, the mode sum gives $C_2/C_3 \approx 0.13$ in $\ell(\ell+1)$ normalization.

Observed: anomalously low quadrupole, $C_2/C_3 \approx 0.15$.

### C. Parity Sign

The non-orientable Möbius identification breaks even-odd symmetry. Modes symmetric under the identification (one $\ell$-parity) satisfy periodic boundary conditions; modes antisymmetric under it (the other parity) satisfy anti-periodic conditions with a higher eigenvalue floor. The net effect: R<sub>TT</sub> < 1.

This result is robust in the 3D picture. Each Molien-surviving shell projects onto both even and odd $\ell$ at generic observer positions. The Möbius boundary condition systematically suppresses one parity, while the shell-by-shell projection effects oscillate and wash out in the mode sum.

The COMPACT collaboration independently confirmed that non-orientable manifolds generically produce parity asymmetry of this sign.

### D. Alignment

The Möbius twist axis defines a preferred direction in $S^3$. The embedding of $2I$ in SU(2) $\cong S^3$ is chosen so that the twist axis (the normal to the covering $S^2$) coincides with an icosahedral symmetry axis. The $2I$-invariant modes at each surviving shell inherit axial symmetry about this direction: their $\ell = 2$ and $\ell = 3$ components point the same way. The quadrupole and octupole are aligned by construction.

The observed 10° misalignment is parallax. The observer's displacement $d$ from the domain center shifts the apparent axis on the last-scattering sphere:

$$\Delta\theta_{23} \approx \frac{d}{\chi_*} = \frac{2.1}{14.0} = 0.150 \;\text{rad} = 8.6°$$

Observed: $\Delta\theta_{23} \approx 10°$. Agreement: 14%.

### E. Parity Magnitude

The interference formula follows from the method of images on any compact manifold with a non-orientable identification, to leading order in the image amplitude:

$$R_{TT} \approx \frac{1 + 2A_{\mathrm{eff}}}{1 - 2A_{\mathrm{eff}}}, \qquad A_{\mathrm{eff}} \simeq \eta_{\mathrm{eff}} \cos(2\pi f_\parallel)$$

where $\eta_{\mathrm{eff}}$ is the effective image-sum amplitude and $f_\parallel$ encodes the observer's position along the identification direction. The formula requires three conditions: an orientation-reversing deck transformation exists, its image contribution is small ($\eta \ll 1$), and higher-order images are further suppressed.

A mode sum over the first four Molien-surviving shells ($N = 12, 20, 24, 30$), weighted by a scale-invariant primordial spectrum, gives $R_{TT} = 0.81$ at observer distance $d = 2.1$ Gpc, with extracted $\eta_{\mathrm{eff}} \approx 0.150$.

The alignment angle ($\Delta\theta_{23} \approx 8.6°$) and the parity ratio ($R_{TT} \approx 0.81$) are controlled by the same parameter: the observer's geodesic distance from the domain center. One position, two observables.

Observed: R<sub>TT</sub> ≈ 0.81.

### F. Summary

| Feature | Topology predicts | CMB measures | Agreement | Status |
|---|---|---|---|---|
| Mode density transition | Molien gap ends at $\ell \approx 29$ | deficit below $\ell \lesssim 30$ | ~1 multipole | prediction |
| Quadrupole | $C_2/C_3 \approx 0.13$ | $C_2/C_3 \approx 0.15$ | 13% | prediction |
| Parity sign | $R_{TT} < 1$ | $R_{TT} \approx 0.81$ | ✓ | prediction |
| Alignment | $\Delta\theta_{23} \approx 8.6°$ | $\Delta\theta_{23} \approx 10°$ | 14% | prediction |
| Parity magnitude | $R_{TT} \approx 0.81$ at $d = 2.1$ Gpc | $R_{TT} \approx 0.81$ | < 1% | fit (fixes $d$) |
| $\Lambda$ from $R$ | $\Lambda = 3/R^2 = 1.12 \times 10^{-52}$ m⁻² | $1.11 \times 10^{-52}$ m⁻² | 2% | consistency (§V) |

---

## IV. On Matched Circles

Standard searches for cosmic topology look for matched circles in the CMB sky. Planck found none above the noise threshold. The null result is consistent: standard matched-circle algorithms are designed for orientable gluings, where identified circles carry the same temperature pattern. Under a non-orientable identification, the relevant "matching" involves a sign flip that conventional searches would not detect.

More fundamentally, the Möbius identification constrains the eigenmode spectrum of the bounded domain rather than repeating sky patches at identified points. The CMB is not an image viewed through topology; it is the resonant pattern of the cavity.

---

## V. Discussion

A single geometric structure accounts for four persistent CMB features. The topology determines which modes exist. The observer's position determines how those modes project onto the sky.

**Mode density deficit.** The Molien series for the binary icosahedral group empties five even-degree shells ($N = 2$ through 10) after the constant mode. The gap boundary at $N = 10$ maps to $\ell \approx 29$ on the CMB sky. One group, one graph, two applications: the same McKay filtering that produces the Yang-Mills spectral gap (adjoint representation) produces the CMB mode deficit here (trivial representation).

**Quadrupole suppression.** The Molien gap removes the shells that feed the quadrupole. The observer's radial position further suppresses $\ell = 2$ relative to $\ell = 3$ through the Gegenbauer profile. The two mechanisms are independent and additive.

**Parity.** The non-orientable identification drives $R_{TT} < 1$ systematically. The method of images gives the leading-order formula; the effective attenuation $\eta_{\mathrm{eff}} \approx 0.150$ emerges from the mode sum at $d = 2.1$ Gpc.

**Alignment.** The Möbius twist axis defines the preferred direction. The embedding of $2I$ in SU(2) aligns this axis with an icosahedral symmetry axis, so the $2I$-invariant modes inherit axial symmetry about it. The observed misalignment is parallax: $d/\chi_* = 8.6°$.

**One position, five observables.** The observer sits at geodesic distance $d = 2.1$ Gpc from the domain center, corresponding to $\chi = 0.40$ rad in $S^3$. This single parameter controls the parity magnitude, the alignment angle, the quadrupole suppression, and (through the Molien gap) the low-ℓ transition scale. The CMB-constrained $R$ then recovers $\Lambda$ through the eigenvalue chain (below). Five independent measurements constrain one geometry. The over-determination is the test.

Luminet et al. proposed the Poincaré dodecahedral space to explain low-ℓ suppression, adopting $\Omega_\mathrm{tot} = 1.018$ and $R \approx 33$ Gpc. The two scales make different quantitative predictions: the Molien gap boundary falls at $\ell \approx 29$ for $R = 5.3$ Gpc and at $\ell \approx 5$ for $R = 33$ Gpc. The observed deficit boundary near $\ell \sim 30$ favors the present scale. The COMPACT collaboration systematically studied non-orientable manifolds and confirmed that they generically produce parity asymmetry of the observed sign. 

The present work differs in two ways: the Möbius surface is embedded in S³ rather than being a quotient of it, and the predictions rest on the Molien-filtered scalar spectrum of $S^3/2I$ rather than on a flat-strip eigenspectrum. The present model also differs from Luminet et al. in its treatment of spatial curvature: the curvature of $S^3$ is absorbed into $\Lambda$ through the eigenvalue identification rather than appearing as a separate Friedmann parameter $\Omega_K$, eliminating the tension that constrains near-flat dodecahedral models to $\Omega_\mathrm{tot} \approx 1.018$.

### Consistency check: the cosmological constant

The curvature radius $R$ was constrained above by CMB observables alone: the Molien gap boundary, the parity ratio, the quadrupole suppression, and the alignment angle all require $R \approx 5.2\text{--}5.4$ Gpc at observer distance $d = 2.1$ Gpc. This value was not derived from $\Lambda$.

Independently, the ground eigenvalue of the Laplace-Beltrami operator on the totally geodesic Möbius surface gives $\lambda_0 = 2/R^2$. The Gauss equation under isotropy converts to $R_{3\mathrm{D}} = 3\lambda_0 = 6/R^2$, and the de Sitter relation gives $\Lambda = R_{3\mathrm{D}}/2 = 3/R^2$. The 3/2 ratio ($\Lambda/\lambda_0$) reflects the dimensional conversion between surface and space curvature on a totally geodesic embedding.

At $R = 5.3$ Gpc: $\Lambda = 3/R^2 = 1.12 \times 10^{-52}$ m⁻², matching the Planck 2018 value $\Lambda_\mathrm{obs} = 1.11 \times 10^{-52}$ m⁻² to 2%.

The CMB anomalies constrain $R$. The eigenvalue chain converts $R$ to $\Lambda$. The agreement is a fifth observable falling out of the same geometry for free.

### What the observer contributes

The topology does not predict the observer's position. The value $d = 2.1$ Gpc is where we happen to stand. A different observer elsewhere in $S^3/2I$ would measure a different alignment angle, a different parity ratio, and a different quadrupole amplitude. The relationships between them would hold. The structure is derived. The position is measured.

---

## VI. Falsification

| Prediction | Falsified if | Threshold |
|---|---|---|
| Mode density transition at $\ell \sim 29$ | Low-ℓ power consistent with ΛCDM (no deficit) | No suppression at $\geq 2\sigma$ |
| Quadrupole suppression | $C_2/C_3$ consistent with ΛCDM | $C_2/C_3 > 0.5$ |
| $R_{TT} < 1$ | Even-ℓ excess at large angles | $R_{TT} > 1$ at $\geq 2\sigma$ |
| Preferred axis | No alignment in independent data | Quadrupole-octupole angle consistent with isotropy |
| Over-determination of $d$ | Observables require different $d$ values | Parity, alignment, quadrupole inconsistent at one $\chi$ |
| $\Lambda$ consistency | CMB-constrained $R$ fails $\Lambda = 3/R^2$ | $\Lambda(R_\mathrm{CMB})$ deviates from observed $\Lambda$ by $> 10\%$ |

The strongest test is over-determination. If the parity ratio, alignment angle, and quadrupole suppression cannot be reproduced at a single observer position in $S^3/2I$, the geometric picture fails.

A forward prediction independent of current anomaly fits: the non-orientable identification should produce correlated parity asymmetry ($R < 1$) in $TE$ and $EE$ spectra with the same sign as $TT$, and the preferred axis should be consistent across all three, testable with LiteBIRD and CMB-S4.

The primary external test is Euclid DR1 (October 2026), which probes the companion predictions: $\Lambda$ constant and $a_0(z) \propto H(z)$. The same static $S^3$, the same observer position, the same phase clock. If the broader framework falls, this paper falls with it.

---

Four anomalies. One constant. One geometry. One address. These are not noise.

*What we called the axis of evil may be the axis of light.*

---

/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /
