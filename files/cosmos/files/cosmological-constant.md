/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /

---

# Λ Ground Mode of the Cosmic Boundary

[![Cosmological Constant](https://img.youtube.com/vi/eFzqU8KPfJ4/mqdefault.jpg)](https://www.youtube.com/watch?v=eFzqU8KPfJ4)

> **Status update (June 2026).** The coefficient derivation on this page stands: the ground eigenvalue $\lambda_0 = 2/R^2$ on the curved Möbius surface is proven, and the Gauss-equation conversion gives $\Lambda = 3/R^2$. What was withdrawn is the claim that this is an independent percent-level prediction. $\Lambda R^2 = 3$ is the de Sitter relation renarrated through boundary topology, not a blind hit; and the scale $R$ cannot be fixed from the CMB Molien gap as Section V claims, because that projection is excluded (see the CMB anomalies page). With $R$ unspecified, the 2% agreement is the de Sitter identity, not a test. The eigenvalue and the geometric renarration survive; the headline prediction and the Section V determination of $R$ are in limbo. Setting $R$ is now the framework's central open problem.

Einstein introduced Λ in 1917 to hold the universe static. When Hubble observed redshift, Einstein removed Λ, calling it his 'biggest blunder.' A century later, standard cosmology revived Λ as 'dark energy.' This note completes the arc: Λ is set by the ground-mode eigenvalue of the cosmic boundary, a static universe where redshift is phase evolution on the boundary. Einstein was right the first time, for reasons then unknown.

The Möbius band selects half-integer modes; the lowest yields $\Lambda_\text{top} = 2/R^2$, where $R$ is the curvature radius of $S^3$. The ground eigenvalue of the twisted Laplacian on the curved Möbius band equals its scalar curvature exactly; the Gauss equation under totally geodesic embedding and isotropy converts this to the observed $\Lambda_\text{obs}$, differing by a factor of 3/2.

| Quantity | Value |
|---|---|
| Derived | $\Lambda \cdot R^2 = 3$, where 3 = eigenvalue (2) $\times$ Gauss equation (3/2) |
| Measured | $R \approx 5.3$ Gpc from the Molien gap on $S^3/2I$ (independent of $\Lambda$) |
| Result | $\Lambda_\text{obs} = 3/R^2 = 1.12 \times 10^{-52}\;\text{m}^{-2}$ |
| Observed | $1.11 \times 10^{-52}\;\text{m}^{-2}$ |
| Cross-check | Standard relation $R = c/(H_0\sqrt{\Omega_\Lambda})$ returns the same $R$ |

Standard cosmology does not constrain $\Lambda \cdot R^2$. This framework derives the coefficient from topology.

## I. The Constant

In general relativity, the cosmological constant Λ appears in Einstein's field equations:

$$G_{\mu\nu} + \Lambda g_{\mu\nu} = 8\pi G \, T_{\mu\nu}$$

Einstein added Λ by hand. It multiplies the metric itself: pure geometry. General relativity does not explain why it has any particular value.

Moving Λ to the right-hand side reinterprets it as vacuum energy density:

$$\rho_\Lambda = \frac{\Lambda c^4}{8\pi G}$$

Quantum field theory estimates vacuum energy from zero-point fluctuations. The result exceeds observation by ~122 orders of magnitude. This is the cosmological constant problem: the largest discrepancy between theory and observation in physics.

Observation gives:

$$\Lambda \approx 1.11 \times 10^{-52} \; \text{m}^{-2}$$

In Planck units ($\ell_P^2 = \hbar G / c^3$):

$$\Lambda \cdot \ell_P^2 \approx 2.84 \times 10^{-122}$$

No mechanism assuming simply connected flat topology explains this value. The standard approach begins with a 4D spacetime, writes down field equations, and asks what value of Λ those equations permit. On a simply connected, non-compact spatial background, the answer is: any value, or a divergent one. The problem is upstream. General relativity is local: it describes dynamics on a domain but does not specify the domain itself. 

The 4D field equations describe dynamics on a geometry; the admissible geometry is constrained by the topology. Reversing this hierarchy, the present framework starts from the spatial topology, derives the ground eigenvalue of the boundary, and reads Λ from it. The 4D dynamics, including the Friedmann equation, are how observers inside the geometry register that eigenvalue as a curvature scale.

## II. The Topology

Eigenvalues arise from differential equations on a domain; the shape determines the spectrum. We choose the shape:

$$S^1 = \partial(\text{Mobius}) \hookrightarrow S^3, \quad \partial S^3 = \emptyset$$

| Manifold | Dim | Role |
|---|---|---|
| $S^1$ | 1D | Boundary of Möbius band |
| Möbius | 2D | Non-orientable surface; carries eigenproblem |
| $S^3$ | 3D | Space |

This is the minimal topology: $S^3$ is the unique simply connected closed 3-manifold (Poincaré); Möbius is the unique minimal non-orientable surface with $S^1$ boundary. Here "boundary" refers to the one-dimensional boundary of the Möbius carrier, $S^1 = \partial(\text{Möbius})$, not to a boundary of the ambient spatial manifold. The ambient space remains closed: $\partial S^3 = \emptyset$.

The anti-periodic boundary condition, the half-integer spectrum, and the $\mathbb{Z}_2$ holonomy all require a surface whose normal direction cannot be globally defined. An orientable annulus with $S^1$ boundary would admit the ordinary periodic sector as the natural untwisted ground sector, with no forced $\mathbb{Z}_2$ reversal. The Möbius band is the minimal surface for which the twist is geometric rather than imposed externally.

### A. The Eigenproblem

A bounded domain permits only certain modes. The eigenvalue problem identifies them: spatial patterns that the differential operator returns unchanged except for a scale factor.

On a flat surface, that operator is the Laplacian $\nabla^2$; however, the cosmic (Möbius) surface is curved, and the metric $g$ stretches and bends the coordinates. The Laplacian generalizes to the Laplace-Beltrami operator:

$$\Delta_g = \frac{1}{\sqrt{\lvert g \rvert}} \, \partial_\mu \!\left( \sqrt{\lvert g \rvert} \, g^{\mu\nu} \, \partial_\nu \right)$$

The eigenvalue problem:

$$-\Delta_{\text{Mobius}} \, \psi = \lambda \, \psi$$

The field $\psi$ is the modal amplitude on the surface; its intensity $\lvert\psi\rvert^2$ determines observable strength. The minus sign is convention, forcing a positive $\lambda$ for bound states.

The Möbius band has coordinates $(y, w)$:

| Coordinate | Range | Direction |
|---|---|---|
| $y$ | $[0, L]$ | Longitudinal (along the belt) |
| $w$ | (drops out) | Transverse (across the width) |

The Möbius identification twists the band:

$$(y + L, w) \sim\; (y, {-w})$$

The longitudinal period $L$ is set by the metric. Let $R$ denote the curvature radius of $S^3$. The boundary $S^1$ is a single closed loop traversing the band twice; its total length is $2L$. Since $g_{yy} = 1$, each meridional leg has length $\pi R$; two legs give $2L = 2\pi R$:

$$2L = 2\pi R \quad \Rightarrow \quad L = \pi R$$

One lap ($L$) brings you to the flip side. Two laps ($2L$) bring you home.

$R$ is the curvature radius of $S^3$, the single measured scale of the framework. Its value is set in §V from the harmonic spectrum of $S^3$, without using the Λ-defined de Sitter-radius relation.

The Möbius band has a single boundary traversed twice. Traversing the band once returns a field to the opposite side. The spectral sector relevant for Λ is the twisted sector:

$$\psi(L, w) = -\psi(0, {-w})$$

with free transverse boundary condition (Neumann): $\partial_w\psi\big|_{w = \pm W} = 0$.

### B. The Spectrum

With boundary conditions set, the eigenvalues follow. For the transverse ground mode, $\psi$ is constant in $w$, so the coordinate reflection drops out and the condition reduces to the longitudinal anti-periodic condition:

$$\psi(y + L) = -\psi(y)$$

Applying this anti-periodic boundary condition to the general solution $\psi \propto e^{iky}$:

$$e^{ikL} = -1$$

Satisfied when $kL = (2m + 1)\pi$ for integer $m$. The constant mode ($k = 0$) is forbidden; anti-periodicity requires at least one sign flip. The solutions give a half-integer spectrum.

## III. The Ground Mode

The cosmological background selects the ground mode:

| Argument | Mechanism |
|---|---|
| Isotropy | Higher modes ($m > 0$) have internal nodes, creating $O(1)$ anisotropy. CMB is isotropic to $10^{-5}$. |
| Orthogonality | Cosmological measurements integrate over Gpc volumes. Oscillating cross-terms cancel. |

### A. The Flat Strip Baseline

On the flat strip with Euclidean metric $ds^2 = dy^2 + dw^2$, the $w$-constant transverse ground sector reduces the Laplace-Beltrami operator to $\Delta = \partial_y^2$. The real representative $u_0 = \sin(y/R)$ is understood as the restriction to one Möbius traversal of the anti-periodic extension $u_0(y + \pi R) = -u_0(y)$. It gives $\lambda_0^\text{flat} = \pi^2/L^2 = 1/R^2$.

The scalar curvature of a constant-curvature surface with $K = 1/R^2$ is $R_\Sigma = 2K = 2/R^2$. Thus:

$$\lambda_0^\text{flat} = \frac{R_\Sigma}{2}$$

The flat strip recovers half the scalar curvature. The full curved surface will recover the other half.

### B. The Totally Geodesic Condition

The ground mode has no internal nodes. The embedding that matches this is the one with no extrinsic structure: the full extrinsic curvature tensor vanishes ($K_{ij} = 0$). This is the totally geodesic condition, the unique embedding carrying no bending information, selected by the ground mode's simplicity.

$K_{ij} = 0$ is a pointwise condition; non-orientability is a global topological property. They operate at different levels. The covering $S^2 \subset S^3$ is totally geodesic ($K_{ij} = 0$ everywhere). The Möbius band is constructed from a spherical band on this $S^2$ by the boundary-edge identification $(0, w) \sim (\pi R, -w)$ and inherits the constant-curvature metric through this construction.

A totally geodesic surface in $S^3$ of radius $R$ carries the constant-curvature metric:

$$ds^2 = dy^2 + \cos^2(y/R)\,dw^2$$

Gaussian curvature $K_G = 1/R^2$. Scalar curvature $R_\Sigma = 2K_G = 2/R^2$. The factor $\cos(y/R)$ vanishes at $y = \pi R/2$: the pole of the covering $S^2$, which becomes a cone point on the Möbius quotient.

### C. The Cone Point

At $y = \pi R/2$ the metric coefficient $\cos(y/R)$ vanishes. On the covering $S^2$ this is a smooth pole. On the edge-identified Möbius band, the same coordinate collapse produces a conical singularity with cone angle $2W/R$, equivalently angular deficit $2\pi - 2W/R$. The surface is smooth away from this single point; the Bochner identity and Gauss equation are applied on the smooth locus, with the cone point controlled by excision (§III.E).

Setting $\delta = y - \pi R/2$, the weight function satisfies $|\cos(y/R)| \sim |\delta|/R$ near $\delta = 0$. The reduced eigenequation in Sturm-Liouville form,

$$(|\delta|/R \cdot u')' + \lambda\,|\delta|/R \cdot u = 0$$

admits a Frobenius analysis. Substituting $u = \delta^s$ gives $s^2 = 0$ (double root). The two independent local solutions are $u_1 = a_0 + a_2\delta^2 + O(\delta^4)$ and $u_2 = \log|\delta| + b_2\delta^2 + O(\delta^4)$. Both are square-integrable (limit-circle endpoint). The Friedrichs extension selects the regular branch by requiring finite Dirichlet integral; the logarithmic branch fails this condition since $\int (u')^2|\cos|\,d\delta \sim \int \delta^{-1}\,d\delta = \infty$.

### D. Direct Computation and Upper Bound

For the metric $ds^2 = dy^2 + f(y)^2\,dw^2$ with $f = \cos(y/R)$, the Laplace-Beltrami operator on $y$-dependent functions is:

$$\Delta u = u'' - \frac{1}{R}\tan(y/R)\cdot u'$$

Ground eigenfunction $u_0 = \sin(y/R)$:

$$u_0' = \frac{1}{R}\cos(y/R), \qquad u_0'' = -\frac{1}{R^2}\sin(y/R)$$

$$-\Delta u_0 = \frac{1}{R^2}\sin(y/R) + \frac{1}{R}\cdot\frac{\sin(y/R)}{\cos(y/R)}\cdot\frac{\cos(y/R)}{R} = \frac{2}{R^2}\sin(y/R)$$

The eigenvalue for this eigenfunction is $2/R^2$.

**Anti-periodic boundary condition:**

$$\sin\!\left(\frac{y + \pi R}{R}\right) = \sin\!\left(\frac{y}{R} + \pi\right) = -\sin\!\left(\frac{y}{R}\right)$$

**Ground state:** $\sin(y/R) > 0$ on $(0,\,\pi R)$. No interior zeros. By Sturm-Liouville theory, an eigenfunction with no interior zeros in the anti-periodic sector is the ground state.

**Rayleigh quotient upper bound.** The Rayleigh quotient confirms:

$$\frac{\displaystyle\int_M |\nabla u_0|^2\,dA}{\displaystyle\int_M u_0^2\,dA} = \frac{8W/3R}{4WR/3} = \frac{2}{R^2}$$

Therefore $\lambda_0 \leq 2/R^2$. The transverse half-width $W$ sets the width of the carrier surface but not the cosmological scale: it cancels from the Rayleigh quotient, so the ground eigenvalue depends only on the curvature radius $R$.

*Flat-strip limit.* Near the equator ($y \approx 0$), $\tan(y/R) \to 0$ and the curvature term vanishes. The operator reduces to $-d^2/dy^2$; the eigenvalue drops to $1/R^2$; and the factor of 2 must be supplied externally. On the full curved surface, the geometry carries it automatically.

### E. The Lower Bound

The Bochner identity gives $\lambda_0 \geq R_\Sigma$ from below, independently of the direct computation.

On an eigenfunction $-\Delta u = \lambda u$, the Bochner formula in dimension 2 gives:

$$\frac{1}{2}\Delta|\nabla u|^2 = |\nabla^2 u|^2 + K_G|\nabla u|^2 - \lambda|\nabla u|^2$$

The identity is applied on the excised manifold $M_\epsilon = M \setminus \{|y - \pi R/2| < \epsilon\}$. On the excision curves: $\partial_\nu|\nabla u|^2 = O(\epsilon)$, arclength $= O(\epsilon)$, so the contribution is $O(\epsilon^2) \to 0$. This regularization is standard for Lichnerowicz-type estimates on manifolds with isolated conical singularities.

The boundary curves $w = \pm W$ are geodesics of the surface ($\kappa_g = 0$), and Neumann conditions hold ($\partial_\nu u = 0$); together these kill the boundary term identically. The bulk identity becomes:

$$\int|\nabla^2 u|^2 = (\lambda - K_G)\int|\nabla u|^2$$

Cauchy-Schwarz on the $2\times 2$ Hessian gives $|\nabla^2 u|^2 \geq (\Delta u)^2/2 = \lambda^2 u^2/2$. Integrating and using $\int|\nabla u|^2 = \lambda\int u^2$:

$$(\lambda - K_G)\lambda\int u^2 \geq \frac{\lambda^2}{2}\int u^2$$

Dividing by $\lambda\int u^2 > 0$: $\lambda - K_G \geq \lambda/2$, hence $\lambda \geq 2K_G = R_\Sigma$.

### F. The Identity

Two independent bounds establish equality:

$$\lambda_0 \leq R_\Sigma \quad \text{(direct)} \qquad \lambda_0 \geq R_\Sigma \quad \text{(Bochner)} \qquad \Rightarrow \qquad \lambda_0 = R_\Sigma \text{ uniquely}$$

$$\boxed{\Lambda_\text{top} = \lambda_0 = \frac{2}{R^2} = R_\Sigma}$$

### G. Topological Protection

$\Lambda_\text{top}$ sits at the antinode of the mode spectrum. The phase coordinate $\Theta = y/L \in [0,1]$ parameterizes position on the standing wave. The intensity profile:

$$C(\Theta) = 2\sin^2(\pi\Theta)$$

At the antinode ($\Theta = 60/120$, the midpoint of the 120-domain native to $S^3$): $C(60/120) = 2$, the same factor carried by $\lambda_0 = 2/R^2$. The logarithmic slope:

$$\frac{d \ln C}{d\Theta}\bigg\rvert_{60/120} = 2\pi \cot(\pi/2) = 0$$

The slope is exactly zero. Any position with finite slope can be shifted by environmental perturbations. The antinode cannot. $\Lambda$ is constant because it occupies the unique position on the mode spectrum where the intensity profile has vanishing derivative.

## IV. The Conversion

The topological eigenvalue $\Lambda_\text{top}$ is defined on a 2D surface. The observed $\Lambda_\text{obs}$ is inferred from 3D spatial dynamics. The Gauss equation relates them.

### A. Gauss Equation

The Gauss equation relates intrinsic curvature of an embedded surface to ambient curvature:

$$R_\Sigma = R_\text{space} - 2\,\text{Ric}(\mathbf{n},\mathbf{n}) + H^2 - A_{ij}A^{ij}$$

| Symbol | Meaning |
|---|---|
| $R_\Sigma$ | Intrinsic scalar curvature of surface |
| $R_\text{space}$ | Scalar curvature of ambient space |
| $A_{ij}$ | Second fundamental form |
| $H$ | Trace of second fundamental form ($g^{ij}A_{ij}$) |
| $\mathbf{n}$ | Unit normal to surface |

### B. Totally Geodesic Embedding

For a totally geodesic embedding ($A_{ij} = 0$, $H = 0$), the equation simplifies:

$$R_\Sigma = R_\text{space} - 2\,\text{Ric}(\mathbf{n},\mathbf{n})$$

### C. Isotropic Space

On an isotropic constant-curvature three-space, $R_\text{space} = R_\text{spatial}$ and the spatial Ricci tensor is:

$$R_{ij} = \frac{R_\text{spatial}}{3}\,g_{ij}$$

Therefore:

$$\text{Ric}(\mathbf{n},\mathbf{n}) = R_\text{spatial}/3$$

### D. The Gravity of the 3/2 Interface

Substituting into the Gauss equation:

$$R_\Sigma = R_\text{spatial} - \frac{2\,R_\text{spatial}}{3} = \frac{R_\text{spatial}}{3}$$

Inverting:

$$R_\text{spatial} = 3 \cdot R_\Sigma$$

### E. Connection to Λ

In vacuum, $G_{\mu\nu} + \Lambda g_{\mu\nu} = 0$, the maximally symmetric solution with spatial sections $S^3(R)$ gives $\Lambda_\text{obs} = 3/R^2$. Thus the ambient radius $R$ is the de Sitter curvature radius in the GR normalization. The spatial $S^3(R)$ has:

$$R_\text{spatial} = \frac{6}{R^2} = 2\Lambda_\text{obs}$$

The direction of logic is: the topology determines $R_\text{spatial} = 6/R^2$ through the Gauss equation; the Einstein equation then defines Λ as the name general relativity gives to the quantity $R_\text{spatial}/2$. The de Sitter relation is not imported as an assumption; it is how GR translates spatial curvature into the parameter Λ.

The chain closes:

$$R_\text{spatial} = 3\,R_\Sigma = 3\,\Lambda_\text{top} = 2\Lambda_\text{obs}$$

$$\Lambda_\text{obs} = \tfrac{3}{2}\,\Lambda_\text{top}$$

The 3 comes from isotropic space ($S^3$). The 2 is how General Relativity defines Λ. The 3/2 is their ratio: the Gauss equation interface between 2D surface geometry and 3D spatial curvature.

### F. Summary

| Factor | Source |
|---|---|
| 3 | Spatial Ricci trace (isotropic space) |
| 2 | de Sitter relation ($R_\text{spatial} = 2\Lambda_\text{obs}$) |
| 3/2 | Net conversion |

| Condition | Justification |
|---|---|
| Totally geodesic embedding | Ground mode correspondence ($m = 0$) |
| Isotropic space | CMB verified to $10^{-5}$ |
| de Sitter vacuum | Late-time ΛCDM limit |
| $R_\Sigma = \Lambda_\text{top}$ | Ground eigenvalue equals surface scalar curvature |

## V. The Scale

Sections III–IV derived $\Lambda_\text{obs} = 3/R^2$. The coefficient is fixed; $R$ remains. This section sets $R$ from the harmonic spectrum of $S^3$, without using the Friedmann Λ-radius relation.

### A. The Quotient Domain

The covering spatial manifold is $S^3$. Its observable harmonic domain is $S^3/2I$, where $2I$ is the binary icosahedral group, the largest exceptional finite subgroup of $\text{SU}(2) \cong S^3$, with $|2I| = 120$.

The postulate of §II specifies the minimal boundary topology. The bulk counterpart is maximal exceptional discrete symmetry. Among the finite exceptional subgroups of $\text{SU}(2)$, $2I$ is the largest. The framework pairs the simplest boundary with the most symmetric exceptional spatial quotient.

These two roles are distinct. The local curvature geometry used in §§II–IV is defined on the universal cover $S^3(R)$, where the great $S^2 \subset S^3$ and the Möbius carrier are constructed. The quotient $S^3/2I$ enters at the level of observable scalar harmonics: it restricts the allowed global shells to the $2I$-invariant sector while preserving the same curvature radius $R$. Thus $S^3$ supplies the local embedding geometry, and $S^3/2I$ supplies the large-scale harmonic selection rule.

### B. The Molien Gap

Scalar harmonics on $S^3$ have eigenvalue $N(N+2)/R^2$ and degeneracy $(N+1)^2$. On the quotient, only $2I$-invariant harmonics survive; the central element $-1 \in 2I$ restricts to even $N$. The Molien series

$$P(t) = \frac{1 - t^{60}}{(1 - t^{12})(1 - t^{20})(1 - t^{30})}$$

shows the first nontrivial invariant at $N = 12$. Shells $N = 2, 4, 6, 8, 10$ are absent. This is the Molien gap.

### C. Mapping to the CMB Sky

Each shell maps to $\ell_\text{char}(N) = \sqrt{N(N+2)}\,\chi_{*}/R$, where $\chi_{*} \approx 14.0$ Gpc is the comoving distance to last scattering (fixed by the acoustic peaks independently of $\Lambda$). The last empty shell ($N = 10$) maps to $\ell \approx 29$; the first surviving shell ($N = 12$) to $\ell \approx 34$. The transition matches the observed low-<i>ℓ</i> CMB power deficit documented across COBE, WMAP, and Planck.

### D. Determining R

Identifying the deficit boundary near $\ell \simeq 29$ with $N = 10$:

$$R = \frac{\sqrt{120} \times 14.0}{29} \approx 5.3 \text{ Gpc} = 1.64 \times 10^{26} \text{ m}$$

This sets $R$ from the CMB harmonic transition rather than from the algebraic de Sitter-radius relation $R = c/(H_0\sqrt{\Omega_\Lambda})$. As a consistency check, that standard relation with $H_0 = 67.4$ km/s/Mpc, $\Omega_\Lambda = 0.685$ gives the same scale.

## VI. The Result

The derivation yields:

$${\Lambda_\text{obs} = \frac{3}{R^2}}$$

The coefficient 3 decomposes as two factors. The curved eigenvalue $\lambda_0 = 2/R^2$: the ground mode on the curved Möbius surface carries this geometric factor directly. The Gauss equation conversion 3/2: intrinsic 2D curvature maps to observed 3D spatial curvature through the embedding interface. Their product: $2 \times 3/2 = 3$.

With $R = 5.3$ Gpc $= 1.64 \times 10^{26}$ m (§V):

$$\frac{3}{R^2} = \frac{3}{(1.64 \times 10^{26})^2} = 1.12 \times 10^{-52}\;\text{m}^{-2}$$

Observed: $\Lambda_\text{obs} = 1.11 \times 10^{-52}\;\text{m}^{-2}$. Agreement ~2%.

### The Derivation Chain

| Step | Input | Output |
|---|---|---|
| 1 | Möbius topology | Anti-periodic BC; $L = \pi R$ |
| 2 | $R$ from Molien gap (§V) | $R \approx 5.3$ Gpc |
| 3 | Even transverse mode | 1D reduction |
| 4 | Anti-periodic BC | Half-integer spectrum |
| 5 | Isotropy + orthogonality | Ground mode ($m = 0$) |
| 6 | Ground mode ($m=0$) → totally geodesic → curved metric | $\lambda_0 = 2/R^2 = R_\Sigma$ |
| 7 | Bochner identity | $\lambda_0 \geq R_\Sigma$; equality unique |
| 8 | $\lambda_0 = R_\Sigma = \Lambda_\text{top}$ | $\Lambda_\text{top} = 2/R^2$ |
| 9 | Gauss equation + totally geodesic | $R_\text{spatial} = 3R_\Sigma$ |
| 10 | de Sitter: $R_\text{spatial} = 2\Lambda_\text{obs}$ | $\Lambda_\text{obs} = \frac{3}{2}\,\Lambda_\text{top}$ |
| 11 | Result | $\Lambda_\text{obs} = 3/R^2$ |

### Derived vs. Imported

| Element | Status | Source |
|---|---|---|
| Anti-periodic BC | Derived | Möbius topology |
| $\lambda_0 = 2/R^2$ | Derived | Twisted Laplacian on curved surface |
| $\lambda_0 \geq R_\Sigma$ | Derived | Bochner bound (§III.E) |
| Gauss equation factor 3/2 | Derived | Totally geodesic embedding in isotropic $S^3$ |
| Coefficient 3 | Derived | Product: $2 \times 3/2$ |
| Scale $R$ | Imported | Molien gap + CMB multipole structure (§V) |

The coefficient 3 is the content of the derivation. Standard cosmology treats $\Lambda \cdot R^2$ as a free parameter. This framework fixes it from topology. The scale $R$ comes from the CMB independently of $\Lambda$; the prediction $\Lambda = 3/R^2$ is then a genuine output, testable against the observed value.

## VII. Compatibility with General Relativity

Einstein's field equations are unchanged:

$$G_{\mu\nu} + \Lambda g_{\mu\nu} = 8\pi G \, T_{\mu\nu}$$

This framework provides what the equation leaves undefined: the value of Λ and the reason it takes that value. The Friedmann equation:

$$H^2 = \Lambda / 3$$

is how observers inside the geometry register that eigenvalue as a curvature scale. General relativity describes dynamics in space; topology specifies the boundary condition. The topology constrains the metric the way a cavity constrains its resonant frequencies: the boundary is logically prior to the vibration. Independent evidence for this priority comes from four CMB observables that follow from the same topology at a single observer position.

The standard cosmological constant problem moves Λ to the right-hand side and identifies it with zero-point vacuum energy density. That step is a reinterpretation, not a derivation. Λ appears on the left-hand side multiplying the metric, a geometric property of the domain, not a matter source. 

Zero-point fluctuations are real and gravitate locally; they appear in $T_{\mu\nu}$ and shift masses and couplings through standard renormalization. They do not set the topological eigenvalue because that eigenvalue is a global property of the boundary, determined by the domain geometry and insensitive to local mode sums. 

The 122-order discrepancy arises from equating two objects that were never the same: a geometric boundary condition on the left and a local energy density on the right.

## VIII. Falsification

Eigenvalues of the Laplacian on fixed topology are constants. If the topology is fixed, Λ is fixed.

### Falsification Criteria

| Prediction | Serious tension | Falsified |
|---|---|---|
| Λ constant | Independent probes prefer evolving dark energy over ΛCDM at $> 3\sigma$, after accounting for known systematics | Robust multi-probe evidence requires redshift evolution of the dark-energy density at $> 5\sigma$ |
| $\Lambda_\text{obs} \cdot R^2 = 3$ | Independent determinations give a $> 3\sigma$ departure from 3 | Independent determinations give a $> 5\sigma$ departure from 3, with $R$ obtained without using the Λ-radius relation |

These predictions are stated in advance of the European Space Agency's Euclid Data Release 1, scheduled for October 2026.

---

Einstein put geometry into his equations and then took it out. A century of physics put it back in and called it energy when it was geometry all along. The blunder was not adding Λ, it was removing it.

The cosmological constant is neither a fitted parameter nor 'dark energy.' It is the ground mode of the cosmic boundary, the ground tone of a resonant universe.

*Einstein's constant, resolved.*

---

/ **[`main`](../../../README.md)** / **[`framework`](../../framework/)** / **[`cosmos`](../../cosmos/)** / **[`spectrum`](../../spectrum/)** /
