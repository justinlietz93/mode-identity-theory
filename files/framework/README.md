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

## The Firing Order

Each layer follows from the one before.

1. Topology sets what is possible.
2. Embedding defines the structure.
3. The Cosmic Wave expresses the boundary.
4. Time is phase of the wave.
5. Sampling resolves position in the domain.
6. Meaning arises only after realization.

---

## :stadium: [One Shape](https://dmobius3.github.io/mode-identity-theory/files/tools/topology.html)

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

## Ψ [One Wave](../cosmos/files/dark-energy.md)

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

## :balance_scale: [One Equation](https://dmobius3.github.io/mode-identity-theory/files/tools/calculator.html)

$$\Large {\frac{A}{A_P} \approx C(\Theta) \cdot (\sqrt{\Omega})^{-n}}$$

$C(\Theta)$ reads the position axis: where the observable sits on the mode spectrum. 

$(\sqrt{\Omega})^{-n}$ reads the time axis through $\Omega_H$ for edge modes, or the boundary condition through $\Omega_\Lambda$ for surface modes. The observer at $\sqrt{\Omega}$ is the structural midpoint where both axes resolve to finite values. 

Their product yields $A/A_P$: the modal realization; the ratio of the observable amplitude over its Planck scale reference.

**The sample occurs at** $(t, \Theta)$.

### The Phase Operator

Different positions on the standing wave carry different observable amplitude:

$$\Large C(\Theta) = 2\sin^2(\pi\Theta)$$

The anti-periodic ground state is $\psi_0(\Theta) = \sin(\pi\Theta)$. Observable intensity is $|\psi|^2$, normalized to unit mean.

| Position | $C(\Theta)$ | Slope $d\ln C/d\Theta$ | Significance |
|---|---|---|---|
| $\Theta = 0$ (boundary) | 0 | $\to \infty$ | No observable amplitude |
| $\Theta = 1/2$ (antinode) | 2 | 0 | Maximum amplitude; topologically protected |
| $\Theta = 1$ (boundary) | 0 | $\to -\infty$ | No observable amplitude |

$\Lambda_\text{top}$ sits at the antinode: slope exactly zero.

### The Hierarchy and the Observer

$\Omega_\Lambda$ is fixed by $\Lambda$ and epoch-independent. The phase-gradient scale changes with epoch:

$$\Omega_H(z) \equiv \left(\frac{\ell_\text{phase}(z)}{\ell_P}\right)^2, \quad \ell_\text{phase} = c/|d\ln\Psi/d\tau|$$

At the present epoch $\Omega_H$ and $\Omega_\Lambda$ are numerically close, both of order $10^{122}$. In the current calibration structure this coincidence is observed, not derived: $\Omega_H$ is anchored by the measured Hubble rate, $\Omega_\Lambda$ by measured $\Lambda$.

The bounded domain runs from that ceiling down to the Planck floor at $\Omega = 1$. The IR $\leftrightarrow$ UV fixed point $x = \Omega/x$ places the observer at the geometric midpoint:

$$\Large x = \sqrt{\Omega} \approx 10^{61}$$

This is where observation resolves.

### Manifold Index

Mode intensity dilutes as $(\sqrt{\Omega})^{-n}$. The manifold index $n$ specifies which scale governs the mode being sampled.

| $n$ | Manifold | $\Omega$ | $(\sqrt{\Omega})^{-n}$ | Observables |
|---|---|---|---|---|
| 0 | Planck floor | 1 | 1 | $G$ |
| 1 | Temporal edge $S^1$ | $\Omega_H$ | $10^{-61}$ | $H_0$, $a_0$ |
| 3/2 | Gauss equation | — | — | $\Lambda_\text{obs}/\Lambda_\text{top} = 3/2$ (geometric conversion) |
| 2 | Möbius surface | $\Omega_\Lambda$ | $10^{-122}$ | $\Lambda$ |
| 3 | Space $S^3$ | $\Omega_\Lambda$ | $10^{-183}$ | Null dark matter detection |

**The scale selection rule.** The index $n$ is read from where the quantity lives and whether it evolves with epoch: edge rates take $n = 1$ on the evolving $\Omega_H$, surface and space quantities take $n = 2$ and $n = 3$ on the fixed $\Omega_\Lambda$, and dimensionless couplings bypass manifold dilution at fractional $n$.

### Fibonacci Wells

Fibonacci positions minimize destructive interference on the 120 domain (Hurwitz: $\varphi$ is hardest to approximate rationally). Below $F_7$, amplitude is indistinguishable from noise. $F_7 = 13$ is the unique well satisfying Fibonacci stability, amplitude above the noise floor, and $\gcd(13, 120) = 1$.

Three constraints force the observable assignments. First, the manifold index separates edge modes ($n = 1$, epoch-dependent: $H_0$, $a_0$) from surface modes ($n = 2$, epoch-independent: $\Lambda$). Second, the bosonic projection: photon-mediated observables access only the 60-grid (even numerators survive $2I \to I$); dynamical observables access the full 120. Third, $\Lambda$ sits at the antinode (60/120) by eigenvalue identity. 

The assignments are forced given the Fibonacci-well restriction, which the Hurwitz noise-floor argument motivates but does not yet derive from the topology alone. That restriction is the open postulate beneath the wells.

| $F_n$ | Grid | Well | $C(\Theta)$ | Observable | Assignment logic |
|---|---|---|---|---|---|
| $F_7$ | 60R | 13/60 | 0.792 | $\alpha$ | Bosonic projection of 13/120; photon-mediated |
| $F_7$ | 120 | 13/120 | 0.223 | $a_0$ | Coprime ($\gcd(13,120)=1$); dynamical, full domain |
| $F_8$ | 120 | 21/120 | 0.55 | Unassigned | — |
| $F_9$ | 120 | 34/120 | 1.208 | $H_0$ | Even numerator; only remaining edge-mode well on bosonic grid |
| $F_{10}$ | 120 | 55/120 | 1.97 | Unassigned | — |
| — | 120 | 60/120 | 2.00 | $\Lambda_\text{top}$ | Antinode; ground-state maximality; slope zero |

### The Assembled Engine

| Observable | $A_P$ | Grid | $\Theta$ | $C$ | $n$ | $A/A_P$ | Role |
|---|---|---|---|---|---|---|---|
| [α](../spectrum/files/fine-structure.md) | 1 | 60R | 13/60 | 0.792 | 1/30 | $7.33 \times 10^{-3}$ | Prediction |
| [a₀](../cosmos/files/early-galaxies.md) | $a_P$ | 120 | 13/120 | 0.223 | 1 | $2.2 \times 10^{-62}$ | Prediction |
| [H₀](../cosmos/files/hubble-tension.md) | $t_P^{-1}$ | 120 | 34/120 | 1.208 | 1 | $1.2 \times 10^{-61}$ | Calibration |
| [Λ](../cosmos/files/cosmological-constant.md) | $\ell_P^{-2}$ | 120 | 60/120 | 2.00 | 2 | $2.9 \times 10^{-122}$ * | Surface calibration / geometric relation |

> * The surface eigenvalue $\Lambda_\text{top} = 2/R_\Lambda^2$ is computed directly on the curved totally geodesic metric $ds^2 = dy^2 + \cos^2(y/R_\Lambda)\,dw^2$ and confirmed from below by the Bochner identity; equality is unique. The Gauss equation conversion $\Lambda_\text{obs} = (3/2)\,\Lambda_\text{top} = 3/R_\Lambda^2$ follows under three conditions: totally geodesic embedding ($K_{ij} = 0$), isotropy (CMB-verified to $10^{-5}$), and de Sitter vacuum (late-time ΛCDM attractor).
>
> **Status:** numerical $\Lambda$ is a surface-sector calibration, not an independent prediction; the first positive eigenvalue $2/R^2$ is the geometric result (see the [cosmological constant](../cosmos/files/cosmological-constant.md) page).

**Calibration structure.** $H_0$ fixes the edge normalization $N = H_0 t_P / C(34/120)$; the other edge observables follow from $N$ as predictions, and the $\approx$ in the scaling law marks this single calibration. Any ratio of two edge-mode $C$ factors cancels $N$, so it is a zero-parameter prediction.

$\alpha$ and $a_0$ share the Fibonacci index 13 but live on different grids ($\alpha$ at 13/60, $a_0$ at 13/120), reference different scales ($\Omega_\Lambda$ vs $\Omega_H$), and carry different exponents (1/30 vs 1). The shared index reflects Fibonacci stability operating at the topological level for both. Each prediction is independent.

The $a_0/(cH_0)$ ratio is locked by well positions: $C(13/120)/C(34/120) = 0.184$. Because both are edge modes sharing the same calibrated normalization $N$, the ratio holds at every epoch: $a_0(z) \propto H(z)$.

### [The Phase Field](../cosmos/files/hubble-tension.md)

**Status:** The lattice arithmetic (the well-slope step) stands; the galactic trigger that would realize the $H_0$ shift is withdrawn (SPARC), so the 8.4% step is a topological number without an active mechanism (see the [Hubble tension](../cosmos/files/hubble-tension.md) page).

The phase position decomposes as $\Theta = \Theta_0 + \Theta_f$, where $\Theta_0$ is the Fibonacci well (fixed) and $\Theta_f$ is the local environmental shift.

| Well | Θ | Slope sensitivity | Physical shift | Reason |
|---|---|---|---|---|
| $a_0$ | 13/120 | 17.7 per step | None | Defines the transition |
| $H_0$ | 34/120 | 5.1 per step | 8.4% | Measured through the field |
| $\Lambda_\text{top}$ | 60/120 | 0 per step | 0% | Topologically protected |

The slope at each well determines its character. $\Lambda$ at slope zero is immovable: topologically protected at the antinode. $H_0$ at slope 5.1 absorbs one bosonic step (2/120) as an 8.4% shift: $C(36/120)/C(34/120) = 1.084$, giving $67.4 \times 1.084 \approx 73$ km/s/Mpc. This arithmetic is fixed by well positions and independent of any galactic mechanism.

$a_0$ at slope 17.7 marks a steep, sensitive well, but the phase field does not shift it. The acceleration scale where MOND behavior turns on IS the well position $C(13/120) \cdot (\sqrt{\Omega_H})^{-1} \cdot a_P$. The steep slope explains why the MOND transition is sharp: a binary on/off behavior rather than a gradual ramp.

### [The Gauge Ladder](../spectrum/files/fine-structure.md)

Dimensionless couplings resolve within the hierarchy at the grid level rather than the manifold level. A single principle assigns each gauge force: the phase slot inherits the grid of the carrier, the exponent slot inherits the grid of the confinement target.

| Force | Phase grid | Exponent grid | Formula | Predicted | Observed | Agreement |
|---|---|---|---|---|---|---|
| EM | 60R (bosonic carrier) | 60R (bosonic charge) | $C(13/60) \cdot \Omega_\Lambda^{-1/60}$ | 0.00733 | 0.00730 | 0.5% |
| Strong | 60R (bosonic carrier) | 120 (confined fermions) | $C(17/60) \cdot \Omega_\Lambda^{-1/120}$ | 0.1162 | 0.1179 | 1.4% |
| Weak | 120 (spinorial carrier) | 120 (fermion transitions) | $C(17/120) \cdot \Omega_\Lambda^{-1/120} \cdot \cos(\pi/10)$ | 0.0339 | 0.0338 | 0.4% |

The Coxeter pair $(13, 17)$ under $h(E_8) = 30$ is forced: all alternative conjugate pairs fail by 93% to 770%. The three forces exhaust the grid ladder (monotone in spinorial content). 

The fourth rung (spinorial carrier, bosonic target) is structurally closed: the bosonic projection $\psi \to |\psi|^2$ is non-invertible (both $\psi$ and $-\psi$ map to the same image), and the same non-invertibility grounds the spin-statistics theorem. A coupling running from spinorial carrier to bosonic target would reverse this projection.

## :atom_symbol: [One Formula](../spectrum/files/mass-spectrum.md)

### [Confinement](../spectrum/files/yang-mills.md)

Positive Ricci curvature on $S^3$ means every coexact gauge fluctuation around a flat connection has a minimum eigenvalue. The Weitzenböck identity on the Hodge Laplacian gives $\lambda \geq 2/R_\Lambda^2 > 0$. The mass gap exists and is at least $2/R_\Lambda^2$; the actual gap at the trivial and standard vacua is $4/R_\Lambda^2$. The gap exists geometrically, at the cosmological scale $4/R_\Lambda^2$ rather than a GeV confinement scale.

### Three Generations

Flat SU(2) connections on $S^3/2I$ are classified by conjugacy classes of homomorphisms from $2I$ into SU(2). Exactly three exist. Each is isolated ($H^1 = 0$): no continuous moduli, no Goldstone bridges between families.

| Vacuum | Mass gap | Source |
|---|---|---|
| Trivial | $4/R_\Lambda^2$ | Flat connection |
| Standard | $4/R_\Lambda^2$ | Irreducible connection |
| Galois | $36/R_\Lambda^2$ ($9\times$) | Galois conjugate connection |

Three topological vacua give three particle generations; the count is forced. Trivial and Standard are degenerate in gap, while Galois is distinguished by the 9× enhancement. The specific generation-to-vacuum mapping is open.

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

## :small_red_triangle: [One Identity](../spectrum/files/mass-spectrum.md)

$$\Large {|2I| = 120 = 2^3 \cdot 3 \cdot 5}$$

The binary icosahedral group is the largest exceptional discrete subgroup of SU(2). Its order factors into exactly three primes.

The icosahedron carries three stabilizer subgroups. Restricting each irrep to these subgroups assigns physical identity.

| Stabilizer | Order | Physical content | Mechanism |
|---|---|---|---|
| Face ($Z_3$) | 3 | Color: singlet (lepton) vs triplet (quark) | Generation-independent; face geometry identical from all three vacua |
| Edge ($Z_4$) | 4 | Spin-statistics: $D = 120$ (half-int) vs $D = 60$ (int) | Complex vs real $Z_4$ content |
| Vertex ($Z_5$) | 5 | Electroweak interface | Galois conjugate vacua $R_1$, $R_2$ differ in $Z_5$ content |
| Face/Edge | 3/2 | Gravity: Gauss equation conversion | Surface eigenvalue to space observable |
| Vertex $\times$ twist | $\cos(\pi/10)$ | Weak coupling correction | Dodecahedral defect $\pi/5$, halved by Möbius $\mathbb{Z}_2$ |

The three stabilizer orders are the primes dividing $|2I| = 120$. Each physical role is forced by group action on irreps: $Z_3$ uniquely produces the singlet/triplet decomposition (color); $Z_4$ contains the central element $-I$ acting as $\pm 1$ on integer vs half-integer spin irreps (spin-statistics); $Z_5$ uniquely distinguishes the Galois pair $R_1$, $R_2$ (electroweak). The mass formula computes how heavy. The stabilizer structure says what.

---

## :control_knobs: Inputs and Calibration

The scaling law is one equation with one hierarchy variable, $\Omega_\Lambda$. Every observable on the law is a different reading of that one variable. Invert any single observable and you fix $\Omega_\Lambda$, which then predicts all the others. Which observable you invert is calibration. The relationships between them are physics.

### Unit constants

| Constant | Value | Role |
|---|---|---|
| $c$ | 299,792,458 m/s | Propagation rate on the temporal boundary |
| $\hbar$ | $1.055 \times 10^{-34}$ J s | Converts dimensionless mode structure into physical action and energy |

Neither is predicted. They define the unit system, nothing more.

### The dimensionless core

In a ratio of two observables at the same depth, $\Omega_\Lambda$ cancels: no anchor enters and the number is parameter-free. These hold under every choice of anchor below.

| Quantity | Value | Status |
|---|---|---|
| Force count | 3 | exact |
| Generation count | 3 | exact |
| $T_3$ assignments | 10/10 | exact (Coxeter-Galois gate) |
| $T^2(R_3)/T^2(R_4)$ | $\varphi^{-4}$ | exact (torsion ratio) |
| $\alpha_s/\alpha_W$ | 3.43 | prediction (1.8%), $\Omega$ cancels |
| $a_0/(cH_0)$ | 0.184 | prediction, normalization cancels |

### Three readings of one hierarchy

To attach a scale you invert one observable for $\Omega_\Lambda$. Three are independent, and the framework is over-determined: each fixes the same hierarchy, and they agree to within their amplified input residuals.

| Anchor | Determines | $\Lambda$ | $\alpha$ | Precision driver |
|---|---|---|---|---|
| Measured $\Lambda$ (sets $R$) | $\Omega_\Lambda$ from $R$ | circular | 0.5% | current default |
| Measured $\alpha$ | $\Omega_\Lambda$ from the coupling | 24% (genuine) | circular | best-conditioned |
| Mass spectrum ($m_\mu/m_e$) | $\Omega_\Lambda$ from the mass ratio | ~14x (genuine) | ~few % | independent cross-check |

The headline is the second row: from one measured coupling, with no $R$ and no further calibration, the scaling law fixes the cosmological constant to 24%. The 122 orders of magnitude are not predicted here; they enter through $\Omega_\Lambda$, read from $\alpha$. What this route adds is the residual coefficient, to 24%. QFT, which does try to predict the magnitude from first principles, overshoots by $10^{120}$.

### The lever, and why the readings differ

All three are the same inversion: solve a formula that depends on $\Omega_\Lambda$ for $\Omega_\Lambda$, through the same 60-fold McKay/grid lever ($\Lambda\ell_P^2 \propto \alpha^{60}$; the mass ratio carries $\Omega_\Lambda^{1/60}$ at $\Delta\mathrm{dist}=1$). They differ only in how well-conditioned the input is: $\alpha$ matches its formula to ~0.5%, so $\Lambda$ lands at 24%; the mass ratio matches to ~4.5%, so $\Lambda$ lands ~14x off. The ~10x gap between the two genuine $\Lambda$ readings is a precision limit of the mass formula's residual scatter, not a structural inconsistency: the same lever amplifies a larger input error.

### Sector anchors

| Sector | Anchor | Role |
|---|---|---|
| Edge | measured $H_0$ | Fixes the present edge hierarchy $\Omega_H = (c/H_0\ell_P)^2$ |
| Surface / space | any one of $\Lambda$, $\alpha$, or the mass ratio | Fixes $\Omega_\Lambda$; the three readings agree to within their input residuals |
| Mass | normalization tied to $m_e$ | Fixes the absolute mass scale once ratios are known |
| Phase clock | $s_0$ from distance data | Locates the current observer phase |

Edge observables reference the evolving $\Omega_H(z)$; surface and space observables reference the fixed $\Omega_\Lambda$. The mass sector inherits $\mu_\Lambda = \rho_\Lambda^{1/4}$ from $\Omega_\Lambda$; $m_e$ is the benchmark, not a second floor.

### Predicted and calibrated

| Quantity | Status |
|---|---|
| dimensionless ratios (couplings, $a_0/cH_0$, counts, $T_3$) | parameter-free, anchor-independent |
| $\Omega_\Lambda$ | over-determined by three independent readings |
| $\Lambda$ (absolute) | prediction from the $\alpha$ reading (24%) or the mass reading (~14x); circular from the $\Lambda$ reading |
| $\alpha$, $\alpha_s$, $\alpha_W$ (absolute) | prediction from the $\Lambda$ reading (0.5%); the anchor when $\alpha$ is the input |
| first positive eigenvalue $2/R^2$ | surface spectral result |
| fermion mass ratios | structural predictions (McKay / torsion) |
| absolute fermion masses | set by the $m_e$ benchmark |
| three generations, Yang-Mills gap | structural results on $S^3/2I$ |

The hierarchy is over-determined and the dimensionless ratios are anchor-free. Which observable you treat as the input is a calibration choice, not a feature of the theory; the theory is the web of relationships that holds whichever you pick.

---

[![Resonant Universe](https://img.youtube.com/vi/I3AOKh-RRTA/mqdefault.jpg)](https://www.youtube.com/watch?v=I3AOKh-RRTA)

*Topology holds. Wave is. Particle samples.*

---

/ **[`main`](../../README.md)** / **[`working`](../working/)** / **[`cosmos`](../cosmos/)** / **[`spectrum`](../spectrum/)** /
