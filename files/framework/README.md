/ **[`main`](../../README.md)** / **[`working`](../working/)** / **[`cosmos`](../cosmos/)** / **[`spectrum`](../spectrum/)** /

---

# :triangular_ruler: The Universe from One Shape

Mode Identity Theory is a boundary-condition framework. It keeps Einstein's field equations and the Standard Model particle content unchanged, but supplies a global topological domain:

$$
S^1 = \partial(\mathrm{Möbius}) \hookrightarrow S^3,
\qquad
\partial S^3 = \emptyset .
$$

The postulate says that time is the boundary of a non-orientable surface embedded in a closed three-space. The observable domain is the Poincaré homology sphere,

$$
M = S^3/2I,
$$

where $2I$ is the binary icosahedral group of order 120. The topology fixes the mode domain, the boundary condition, the stabilizer structure, and the McKay graph. Measured anchors set absolute scales.

The framework predicts structural relations: well positions, hierarchy exponents, grid assignments, dimensionless ratios, and spectral filters. Absolute scales are calibrated by measured reference observables.

[![The Perfect Shape](https://img.youtube.com/vi/U3VtY8GZox8/mqdefault.jpg)](https://www.youtube.com/watch?v=U3VtY8GZox8)

## Current Status

| Layer | Status | Meaning |
|---|---|---|
| Topology | Active | The postulate, Möbius boundary condition, $S^3/2I$ domain, and 120-grid structure remain the framework's foundation. |
| Spectral geometry | Active | The Möbius surface eigenvalue $\lambda_0 = 2/R^2$, the compact-space Yang-Mills gap, and the three isolated flat connections remain geometric results. |
| Edge sector | Active | $H_0$ calibrates the evolving edge hierarchy $\Omega_H$; the ratio $a_0/(cH_0)$ is predicted by well positions. |
| Surface sector | Calibrated | The eigenvalue relation survives, but $R$ is not independently fixed. Measured $\Lambda$ calibrates the surface scale $R$, and hence $\Omega_\Lambda = (R/\ell_P)^2$ once the Planck scale is specified. |
| Mass sector | Active with calibration | Mass ratios and McKay/torsion structure remain active. Absolute masses require the calibrated surface hierarchy and a mass-sector normalization. |
| Gauge couplings | Active with calibration | Couplings use fractional powers of the calibrated surface hierarchy $\Omega_\Lambda$. Scale matching to conventional running remains open. |
| Inactive mechanisms | Not used | The CMB-Molien determination of $R$, the CMB-anomaly observer mechanism, and the SPARC phase-trigger mechanism are not active supports of the framework. |

The correction is local. The independent CMB-Molien determination of $R$ is no longer used. The surface eigenvalue remains geometric, while measured $\Lambda$ now calibrates the surface scale. Edge-sector predictions are unaffected because they use $\Omega_H$, not $\Omega_\Lambda$. Mass and coupling calculations continue as calibrated outputs of the surface hierarchy.

## The Firing Order

Each layer depends on the one before it.

1. Topology sets the allowed domain.
2. The embedding supplies the boundary condition.
3. The boundary condition fixes the mode structure.
4. The 120-domain fixes the grid.
5. Stabilizer subgroups assign physical identity.
6. Measured anchors set absolute scale.
7. Observables are read from the calibrated mode structure.

No observable value exists before the sampling rule and the calibration anchor are specified.

---

## Inputs and Calibration

Two constants define the physical units. Measured anchors set the scale of each sector. The topology supplies the dimensionless structure.

### Constants

| Constant | Value | Role |
|---|---|---|
| $c$ | 299,792,458 m/s | Propagation rate on the temporal boundary |
| $\hbar$ | $1.055 \times 10^{-34}$ J s | Converts dimensionless mode structure into physical action and energy |

These constants are not predicted by the framework. They define the physical unit system in which the topological relations are evaluated.

### Sector anchors

| Sector | Anchor | Role | Status |
|---|---|---|---|
| Edge | measured $H_0$ | Fixes the present edge hierarchy $\Omega_H = (c/H_0\ell_P)^2$ | Calibration |
| Surface / space | measured $\Lambda$ | Fixes the surface scale $R$ through $\Lambda = 3/R^2$, hence $\Omega_\Lambda = (R/\ell_P)^2$ once the Planck scale is set | Calibration |
| Mass | mass-sector normalization, conventionally tied to $m_e$ | Fixes the absolute mass scale once ratios are known | Calibration |
| Phase clock | $s_0$ from distance data | Locates the current observer phase | Fit parameter |

The edge sector and surface sector use different hierarchies. Edge observables such as $H_0$ and $a_0$ reference the evolving hierarchy $\Omega_H(z)$. Surface and space observables reference the fixed boundary hierarchy $\Omega_\Lambda$.

The mass sector inherits the vacuum floor

$$
\mu_\Lambda = \rho_\Lambda^{1/4}
$$

from the calibrated surface hierarchy. The electron mass is not a second vacuum floor; it is the mass-sector normalization or benchmark used to set the absolute scale of the particle spectrum.

### What is predicted and what is calibrated

| Quantity | Status |
|---|---|
| $H_0$ | Edge-sector calibration anchor |
| $a_0/H_0$ | Parameter-free edge-sector prediction |
| $a_0(z) \propto H(z)$ | Edge-sector prediction |
| $\lambda_0 = 2/R^2$ | Surface spectral result |
| numerical $\Lambda$ | Surface-sector calibration, not currently an independent prediction |
| gauge-coupling ratios | Dimensionless structural predictions |
| absolute gauge couplings | Predictions using calibrated $\Omega_\Lambda$ |
| fermion mass ratios | Structural predictions from McKay/torsion data |
| absolute fermion masses | Calibrated mass-sector outputs |
| three generations | Three isolated flat connections on $S^3/2I$ |
| compact Yang-Mills gap | Positive spectral gap on the compact curved domain |

This is the current architecture: ratios and structural filters are the anchor-free core; absolute dimensional values require calibrated sector anchors.

---

## [The Topology](https://dmobius3.github.io/mode-identity-theory/files/tools/topology.html)

$$\Large {S^1 = \partial(\text{Möbius}) \hookrightarrow S^3, \quad \partial S^3 = \emptyset}$$

A temporal edge bounds a non-orientable surface embedded in a closed space. The space has no boundary. Two uniqueness theorems force the manifold triad: the classification of compact surfaces forces the Möbius strip, and the Poincaré theorem forces $S^3$. The postulate has one realization.

### Space

$S^3$ is the only simply connected closed 3-manifold (Poincaré). It is diffeomorphic to SU(2) and admits a spin structure. The space has no boundary:

$$\Large {\partial S^3 = \emptyset}$$

The hierarchy terminates here. "What's outside?" is malformed; there is no boundary from which to observe.

### Surface

The Möbius strip is the minimal non-orientable surface with $S^1$ boundary. By the classification of compact surfaces, a connected non-orientable manifold with a single boundary component is formed by removing a disk from the connected sum of $k$ crosscaps. The Möbius strip is the minimal case ($k = 1$), unique by surface classification. Non-orientability produces three consequences:

| Consequence | Mechanism |
|---|---|
| Anti-periodic BC | Sections of the orientation bundle acquire a sign flip: $\psi(y + \pi R_\Lambda) = -\psi(y)$ |
| Half-integer spectrum | Mode numbers $\nu = 1/2, 3/2, 5/2, \ldots$; the constant mode is forbidden |
| $\mathbb{Z}_2$ holonomy | The normal direction reverses under one traversal |

Orientable surfaces produce none of these.

The eigenvalue problem $-\partial_y^2 \psi = \lambda \psi$ under the anti-periodic BC requires $e^{ik\pi R_\Lambda} = -1$, giving $k = (2m+1)/R_\Lambda$. Defining the mode number $\nu = kR_\Lambda/2$, the allowed values are $\nu = 1/2, 3/2, 5/2, \ldots$: half-integers in this normalization. The constant mode ($k = 0$) is forbidden. 

The field $\psi$ is a section of the orientation line bundle: the unique nontrivial real line bundle on a non-orientable surface, whose sections pick up a sign flip under the orientation-reversing identification. Matter is fermionic because the surface is non-orientable and the physical field couples to its orientation structure.

### Temporal Edge

$S^1$ is the boundary of the Möbius surface. The strip has longitudinal period $L = \pi R_\Lambda$ (one lap); the boundary $S^1$ traverses the strip twice before closing, giving geometric circumference $2L = 2\pi R_\Lambda$. The edge inherits the anti-periodic boundary condition. This is where time advances and where the observer is anchored.

The chronon and standing wave period operate in the phase parameter $t \in [0, 4\pi]$, not in geometric length. The factor $4\pi$ is the anti-periodic wave period (two sign-flip traversals), dimensionless.

### The Observable Domain

The physical space is $S^3/2I$: the hypersphere modulo the binary icosahedral group $2I$, with $|2I| = 120$. The discrete subgroups of SU(2) $\cong S^3$ are classified: open families (cyclic $Z_n$ and binary dihedral $2D_n$, parameterized by $n$) and three closed exceptional groups (binary tetrahedral $|2T| = 24$, binary octahedral $|2O| = 48$, binary icosahedral $|2I| = 120$). 

Open families require external choice of $n$ and are excluded by the framework's input-minimization: every free parameter is a violation of the foundation. Among the closed exceptional cases, $2I$ is terminal; largest in order and maximal under the McKay correspondence ($2I \leftrightarrow E_8$, the largest exceptional Lie algebra). The selection is forced by the framework's own principle.

Four auxiliary paths converge on this number (three independent):
1. Group theory of $S^3$ gives $|2I| = 120$ directly
2. The least common multiple of the first five Fibonacci numbers: $\text{lcm}(1,2,3,5,8) = 120$
3. The consonance ratios of musical harmony independently yield $\text{lcm} = 120$
4. The $(2,3,5)$ branch orders of the icosahedron are consecutive Fibonacci numbers satisfying $2+3=5$: the unique Platonic solid whose symmetry orders obey the Fibonacci recurrence

**The 120 domain** is the mode spectrum's resolution. Fermions see all 120 positions but observation squares the wavefunction: $|\psi(\Theta+1)|^2 = |\psi(\Theta)|^2$ erases the anti-periodic sign. The squaring projects $2I \to I$ ($|I| = 60$), halving the resolution.

| Grid | Positions | Minimum step | Observables |
|---|---|---|---|
| Full domain | 120 | 1/120 | $a_0$ (dynamical) |
| Bosonic projection | 60 | 2/120 | $H_0$, $\Lambda$, $\alpha$ (photon-mediated) |

**The chronon** is the smallest phase advance the domain can register:

$$\Delta t_{\min} = \frac{4\pi}{120} = \frac{\pi}{30}$$

**The minimum action** $\Delta S_{\min} = \hbar\pi/30$: frame-independent by construction ($\hbar$ is invariant; $\pi/30$ is a pure number set by the topology, not by a coordinate choice).

### [Confinement](../spectrum/files/yang-mills.md)

Positive Ricci curvature on $S^3$ means every coexact gauge fluctuation around a flat connection has a minimum eigenvalue. The Weitzenböck identity on the Hodge Laplacian gives $\lambda \geq 2/R_\Lambda^2 > 0$. The mass gap exists and is at least $2/R_\Lambda^2$; the actual gap at the trivial and standard vacua is $4/R_\Lambda^2$. Confinement is geometric.

### Three Generations

Flat SU(2) connections on $S^3/2I$ are classified by conjugacy classes of homomorphisms from $2I$ into SU(2). Exactly three exist. Each is isolated ($H^1 = 0$): no continuous moduli, no Goldstone bridges between families.

| Vacuum | Mass gap | Source | Role |
|---|---|---|---|
| Trivial | $4/R_\Lambda^2$ | Flat connection | Generation 1 |
| Standard | $4/R_\Lambda^2$ | Irreducible connection | Generation 2 |
| Galois | $36/R_\Lambda^2$ ($9\times$) | Galois conjugate connection | Generation 3 |

Three particle generations from three topological vacua.

### [The Mass Formula](https://dmobius3.github.io/mode-identity-theory/files/tools/calculator.html)

Four factors, each traced independently to the postulate:

$$\Large m(\rho, \sigma) = \mu_\Lambda \cdot C_{\text{geom}}(\rho) \cdot (\sqrt{\Omega_\Lambda})^{\,\text{dist}(\rho)/30} \cdot T^2(\rho \otimes \sigma)$$

| Factor | Role | Source |
|---|---|---|
| $\mu_\Lambda = \rho_\Lambda^{1/4} \approx 2.25$ meV | Vacuum energy floor; overall mass scale | Fourth root of $\Lambda$; ground mode of Möbius surface |
| $C_\text{geom}(\rho)$ | Phase position on the domain | Geometric mean of $C(e/D)$ over Kostant exponents |
| $(\sqrt{\Omega_\Lambda})^{\text{dist}/30}$ | Hierarchy; orders of magnitude from vacuum floor | McKay graph distance; $h(E_8) = 30$ as denominator |
| $T^2(\rho \otimes \sigma)$ | Fine structure within each mass shell; generation splitter | Reidemeister torsion; $T^2(R_3)/T^2(R_4) = \varphi^{-4}$ exact |

Applied to 8 nontrivial irreps across 3 vacua, the formula produces 24 mass entries. 10 map to Standard Model fermions; 9 land within a factor of 3. The electron and muon together anchor the scale through their geometric mean (closure residuals <1% and 3%); the up quark at 6% is the genuine blind prediction from the fixed topological skeleton.

### [Particle Identity](../spectrum/files/mass-spectrum.md)

The icosahedron carries three stabilizer subgroups. Restricting each irrep to these subgroups assigns physical identity.

| Stabilizer | Order | Physical content | Mechanism |
|---|---|---|---|
| Face ($Z_3$) | 3 | Color: singlet (lepton) vs triplet (quark) | Generation-independent; face geometry identical from all three vacua |
| Edge ($Z_4$) | 4 | Spin-statistics: $D = 120$ (half-int) vs $D = 60$ (int) | Complex vs real $Z_4$ content |
| Vertex ($Z_5$) | 5 | Electroweak interface | Galois conjugate vacua $R_1$, $R_2$ differ in $Z_5$ content |
| Face/Edge | 3/2 | Gravity: Gauss equation conversion | Surface eigenvalue to space observable |
| Vertex $\times$ twist | $\cos(\pi/10)$ | Weak coupling correction | Dodecahedral defect $\pi/5$, halved by Möbius $\mathbb{Z}_2$ |

The three stabilizer orders are the primes dividing $|2I| = 120$. Each physical role is forced by group action on irreps: $Z_3$ uniquely produces the singlet/triplet decomposition (color); $Z_4$ contains the central element $-I$ acting as $\pm 1$ on integer vs half-integer spin irreps (spin-statistics); $Z_5$ uniquely distinguishes the Galois pair $R_1$, $R_2$ (electroweak). The mass formula computes how heavy. The stabilizer structure says what.

## [The Cosmic Standing Wave](../cosmos/files/dark-energy.md)

Anti-periodicity, the initial-maximum condition ($\Psi(0) = +1$), and ground-state selection ($m_h = 0$) together fix:

$$\Large {\Psi = \cos(t/2)}$$

| Condition | Selects | Why |
|---|---|---|
| Anti-periodic BC | Period $4\pi$ | Two traverses to restore sign |
| $\Psi(0) = +1$ | Cosine over sine | $t = 0$ at amplitude maximum; $\partial_t\Psi\|_{t=0} = 0$ |
| Ground state $m_h = 0$ | No higher harmonics | Isotropy ($10^{-5}$) and orthogonality (Gpc integration) |

The phase parameter $s_0 = \sin(t_\text{now}/2)$ is directly constrained by distance data. The Waltz clock $dt/d\tau = S^{-1/2}$ converts budget phase to proper time; the relationship is nonlinear, with early proper time compressed in phase. The derived proper-time age is consistent with the observed ~13.8 Gyr.

[![Time](https://img.youtube.com/vi/9N6g-kDgUDc/mqdefault.jpg)](https://www.youtube.com/watch?v=9N6g-kDgUDc)

### The Present Epoch

Two phase parameterizations exist for the current epoch. The engine phase $\varphi = 4\pi\, T/T_\text{cycle}$ (linear in proper time) gives $\varphi_\text{now} \approx 5.22$ rad. The budget phase $t$ (argument of $\Psi = \cos(t/2)$, nonlinear in proper time through the Waltz clock) is constrained by distance data to $s_0 = \sin(t_\text{now}/2) < 0.19$ (95% CL). The mapping $t(\varphi)$ is OPEN; both parameterizations reproduce the same distance-redshift relation. The full $4\pi$ period and the 120-step chronon structure are topology-native and independent of which parameterization is used.

## Cosmic Scale

### The Scale Hierarchy

$\Omega_\Lambda$ is fixed by $\Lambda$ and epoch-independent. The phase-gradient scale changes with epoch:

$$\Omega_H(z) \equiv \left(\frac{\ell_\text{phase}(z)}{\ell_P}\right)^2, \quad \ell_\text{phase} = c/|d\ln\Psi/d\tau|$$

At the present epoch, $\Omega_H$ and $\Omega_\Lambda$ are numerically close, both of order $10^{122}$. In the current calibration structure this coincidence is observed, not derived: $\Omega_H$ is anchored by the measured Hubble rate, while $\Omega_\Lambda$ is anchored by measured $\Lambda$.

### [The Observer](../cosmos/files/cmb-anomalies.md)

**Status:** The CMB-anomaly mechanism is withdrawn; this section remains only as background for the scalar-harmonic/Molien structure.

The bounded domain spans from $\Omega \sim 10^{122}$ (horizon) to $10^0$ (Planck). The IR $\leftrightarrow$ UV fixed point $x = \Omega/x$ gives:

$$\Large x = \sqrt{\Omega} \approx 10^{61}$$

The geometric midpoint between Planck and cosmic scale. This is where observation resolves.

### Manifold Index

Mode intensity dilutes as $(\sqrt{\Omega})^{-n}$. The manifold index $n$ specifies which scale governs the mode being sampled.

| $n$ | Manifold | $\Omega$ | $(\sqrt{\Omega})^{-n}$ | Observables |
|---|---|---|---|---|
| 0 | Planck floor | 1 | 1 | $G$ |
| 1 | Temporal edge $S^1$ | $\Omega_H$ | $10^{-61}$ | $H_0$, $a_0$ |
| 3/2 | Gauss equation | — | — | $\Lambda_\text{obs}/\Lambda_\text{top} = 3/2$ (geometric conversion) |
| 2 | Möbius surface | $\Omega_\Lambda$ | $10^{-122}$ | $\Lambda$ |
| 3 | Space $S^3$ | $\Omega_\Lambda$ | $10^{-183}$ | Null dark matter detection |

**The scale selection rule.** Two observational properties determine the manifold index $n$: where the quantity lives in the topology, and whether it evolves with epoch. Edge quantities (rates on $S^1$) take $n = 1$ and reference $\Omega_H(z) = (c/H(z)\ell_P)^2$, which evolves. Surface quantities (eigenvalues on Möbius) take $n = 2$ and reference $\Omega_\Lambda = (R_\Lambda/\ell_P)^2$, fixed by the boundary condition. Space quantities ($S^3$ curvature only) take $n = 3$, also referencing $\Omega_\Lambda$. Dimensionless couplings bypass manifold dilution with fractional $n$. The rule reads off each quantity's $n$ from its observational character.

### Selection Rules

| Observable | Character | $n$ | $\Omega$ | $(\sqrt{\Omega})^{-n}$ |
|---|---|---|---|---|
| $\alpha$ | Epoch-independent, dimensionless | 1/30 | $\Omega_\Lambda$ | $\Omega_\Lambda^{-1/60}$ |
| $H_0$, $a_0$ | Epoch-dependent | 1 | $\Omega_H$ | $10^{-61}$ |
| $\Lambda$ | Epoch-independent, geometric | 2 | $\Omega_\Lambda$ | $10^{-122}$ |
| Dark matter | Gravity-only | 3 | $\Omega_\Lambda$ | $10^{-183}$ |

Dimensionless couplings ($A_P = 1$) bypass manifold dilution; $n$ is fractional.

## The Phase Operator

Different positions on the standing wave carry different observable amplitude:

$$\Large C(\Theta) = 2\sin^2(\pi\Theta)$$

The anti-periodic ground state is $\psi_0(\Theta) = \sin(\pi\Theta)$. Observable intensity is $|\psi|^2$, normalized to unit mean.

| Position | $C(\Theta)$ | Slope $d\ln C/d\Theta$ | Significance |
|---|---|---|---|
| $\Theta = 0$ (boundary) | 0 | $\to \infty$ | No observable amplitude |
| $\Theta = 1/2$ (antinode) | 2 | 0 | Maximum amplitude; topologically protected |
| $\Theta = 1$ (boundary) | 0 | $\to -\infty$ | No observable amplitude |

$\Lambda_\text{top}$ sits at the antinode: slope exactly zero. This fixes the surface-sector placement, not the absolute numerical value of $\Lambda$. In the current calibration structure, measured $\Lambda$ sets the surface scale.

## Fibonacci Wells

Fibonacci positions minimize destructive interference on the 120 domain (Hurwitz: $\varphi$ is hardest to approximate rationally). Below $F_7$, amplitude is indistinguishable from noise. $F_7 = 13$ is the unique well satisfying Fibonacci stability, amplitude above the noise floor, and $\gcd(13, 120) = 1$.

Three constraints force the observable assignments. First, the manifold index separates edge modes ($n = 1$, epoch-dependent: $H_0$, $a_0$) from surface modes ($n = 2$, epoch-independent: $\Lambda$). Second, the bosonic projection: photon-mediated observables access only the 60-grid (even numerators survive $2I \to I$); dynamical observables access the full 120. Third, $\Lambda$ sits at the antinode (60/120) by eigenvalue identity. 

Of the remaining wells, only 34/120 has an even numerator and is therefore visible on the bosonic grid, forcing $H_0$. The well 13/120 requires the full 120-grid ($\gcd(13,120) = 1$), making it accessible only to dynamical (non-photon-mediated) observation, forcing $a_0$. The table below summarizes these forced outcomes.

| $F_n$ | Grid | Well | $C(\Theta)$ | Observable | Assignment logic |
|---|---|---|---|---|---|
| $F_7$ | 60R | 13/60 | 0.792 | $\alpha$ | Bosonic projection of 13/120; photon-mediated |
| $F_7$ | 120 | 13/120 | 0.223 | $a_0$ | Coprime ($\gcd(13,120)=1$); dynamical, full domain |
| $F_8$ | 120 | 21/120 | 0.55 | Unassigned | — |
| $F_9$ | 120 | 34/120 | 1.208 | $H_0$ | Even numerator; only remaining edge-mode well on bosonic grid |
| $F_{10}$ | 120 | 55/120 | 1.97 | Unassigned | — |
| — | 120 | 60/120 | 2.00 | $\Lambda_\text{top}$ | Antinode; ground-state maximality; slope zero |

$H_0$ and $a_0$ occupy different wells on the same edge; their ratio is fixed by position.

$H_0$ and $\Lambda$ occupy different manifolds; their 61-order span is fixed by dimension.

## [The Phase Field](../cosmos/files/hubble-tension.md)

**Status:** The lattice arithmetic (the well-slope step) stands; the galactic trigger that would realize the $H_0$ shift is withdrawn (SPARC), so the 8.4% step is a topological number without an active mechanism (see the [Hubble tension](../cosmos/files/hubble-tension.md) page).

The phase position decomposes as $\Theta = \Theta_0 + \Theta_f$, where $\Theta_0$ is the Fibonacci well (fixed) and $\Theta_f$ is the local environmental shift.

| Well | Θ | Slope sensitivity | Physical shift | Reason |
|---|---|---|---|---|
| $a_0$ | 13/120 | 17.7 per step | None | Defines the transition |
| $H_0$ | 34/120 | 5.1 per step | 8.4% | Measured through the field |
| $\Lambda_\text{top}$ | 60/120 | 0 per step | 0% | Topologically protected |

The slope at each well determines its character. $\Lambda$ at slope zero is immovable: topologically protected at the antinode. $H_0$ at slope 5.1 absorbs one bosonic step (2/120) as an 8.4% shift: $C(36/120)/C(34/120) = 1.084$, giving $67.4 \times 1.084 \approx 73$ km/s/Mpc. This arithmetic is fixed by well positions and independent of any galactic mechanism.

$a_0$ at slope 17.7 marks a steep, sensitive well, but the phase field does not shift it. The acceleration scale where MOND behavior turns on IS the well position $C(13/120) \cdot (\sqrt{\Omega_H})^{-1} \cdot a_P$. The steep slope explains why the MOND transition is sharp: a binary on/off behavior rather than a gradual ramp.

## [The Scaling Law](https://dmobius3.github.io/mode-identity-theory/files/tools/calculator.html)

$$\Large {\frac{A}{A_P} \approx C(\Theta) \cdot (\sqrt{\Omega})^{-n}}$$

$C(\Theta)$ reads the position axis: where the observable sits on the mode spectrum. 

$(\sqrt{\Omega})^{-n}$ reads the time axis through $\Omega_H$ for edge modes, or the boundary condition through $\Omega_\Lambda$ for surface modes. The observer at $\sqrt{\Omega}$ is the structural midpoint where both axes resolve to finite values. 

Their product yields $A/A_P$: the modal realization; the ratio of the observable amplitude over its Planck scale reference.

**The sample occurs at** $(t, \Theta)$.

### The Assembled Engine

| Observable | $A_P$ | Grid | $\Theta$ | $C$ | $n$ | $A/A_P$ | Role |
|---|---|---|---|---|---|---|---|
| [α](../spectrum/files/fine-structure.md) | 1 | 60R | 13/60 | 0.792 | 1/30 | $7.33 \times 10^{-3}$ | Prediction |
| [a₀](../cosmos/files/early-galaxies.md) | $a_P$ | 120 | 13/120 | 0.223 | 1 | $2.2 \times 10^{-62}$ | Prediction |
| [H₀](../cosmos/files/hubble-tension.md) | $t_P^{-1}$ | 120 | 34/120 | 1.208 | 1 | $1.2 \times 10^{-61}$ | Calibration |
| [Λ](../cosmos/files/cosmological-constant.md) | $\ell_P^{-2}$ | 120 | 60/120 | 2.00 | 2 | $2.9 \times 10^{-122}$ * | Surface calibration / geometric relation |

> * The surface eigenvalue $\Lambda_\text{top} = 2/R_\Lambda^2$ is computed directly on the curved totally geodesic metric $ds^2 = dy^2 + \cos^2(y/R_\Lambda)\,dw^2$ and confirmed from below by the Bochner identity; equality is unique. The Gauss equation conversion $\Lambda_\text{obs} = (3/2)\,\Lambda_\text{top} = 3/R_\Lambda^2$ follows under three conditions: totally geodesic embedding ($K_{ij} = 0$), isotropy (CMB-verified to $10^{-5}$), and de Sitter vacuum (late-time ΛCDM attractor).
>
> **Status:** numerical $\Lambda$ is a surface-sector calibration, not an independent prediction; the eigenvalue $\lambda_0 = 2/R^2$ is the geometric result (see the [cosmological constant](../cosmos/files/cosmological-constant.md) page).

**Calibration structure.** $H_0$ serves as the calibration observable that fixes the universal hierarchy normalization $N$ for all edge-mode predictions. The scaling law does not derive $H$ from topology; it uses $H$ to set the scale from which $a_0$ and other edge-mode observables are predicted. The $\approx$ in the scaling law reflects this: the kinematic expression $(c/(H\ell_P))^2$ is the physical identification of $\Omega_H$, and $N = H t_P / C(34/120)$ is the precise normalization calibrated through measurement. The ratio of any two edge-mode $C$ factors is a zero-parameter prediction independent of the calibration. The $\Lambda$ relation is the separate surface-sector calibration. The eigenvalue $\lambda_0 = 2/R^2$ still holds, but the path that fixed $R$ independently is withdrawn. Measured $\Lambda$ now calibrates $\Omega_\Lambda = (R/\ell_P)^2$.

$\alpha$ and $a_0$ share the Fibonacci index 13 but live on different grids ($\alpha$ at 13/60, $a_0$ at 13/120), reference different scales ($\Omega_\Lambda$ vs $\Omega_H$), and carry different exponents (1/30 vs 1). The shared index reflects Fibonacci stability operating at the topological level for both. Each prediction is independent.

The $a_0/H_0$ ratio is locked by well positions: $C(13/120)/C(34/120) = 0.184$. Because both are edge modes sharing the same calibrated normalization $N$, the ratio holds at every epoch: $a_0(z) \propto H(z)$.

### [The Gauge Ladder](../spectrum/files/fine-structure.md)

Dimensionless couplings resolve within the hierarchy at the grid level rather than the manifold level. A single principle assigns each gauge force: the phase slot inherits the grid of the carrier, the exponent slot inherits the grid of the confinement target.

| Force | Phase grid | Exponent grid | Formula | Predicted | Observed | Agreement |
|---|---|---|---|---|---|---|
| EM | 60R (bosonic carrier) | 60R (bosonic charge) | $C(13/60) \cdot \Omega_\Lambda^{-1/60}$ | 0.00733 | 0.00730 | 0.5% |
| Strong | 60R (bosonic carrier) | 120 (confined fermions) | $C(17/60) \cdot \Omega_\Lambda^{-1/120}$ | 0.1162 | 0.1179 | 1.4% |
| Weak | 120 (spinorial carrier) | 120 (fermion transitions) | $C(17/120) \cdot \Omega_\Lambda^{-1/120} \cdot \cos(\pi/10)$ | 0.0339 | 0.0338 | 0.4% |

The Coxeter pair $(13, 17)$ under $h(E_8) = 30$ is forced: all alternative conjugate pairs fail by 93% to 770%. The three forces exhaust the grid ladder (monotone in spinorial content). 

The fourth rung (spinorial carrier, bosonic target) is structurally closed: the bosonic projection $\psi \to |\psi|^2$ is non-invertible (both $\psi$ and $-\psi$ map to the same image), and the same non-invertibility grounds the spin-statistics theorem. A coupling running from spinorial carrier to bosonic target would reverse this projection.

---

[![Resonant Universe](https://img.youtube.com/vi/I3AOKh-RRTA/mqdefault.jpg)](https://www.youtube.com/watch?v=I3AOKh-RRTA)

*Topology holds. Wave is. Particle samples.*

---

/ **[`main`](../../README.md)** / **[`working`](../working/)** / **[`cosmos`](../cosmos/)** / **[`spectrum`](../spectrum/)** /
