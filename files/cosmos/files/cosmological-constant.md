/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /

---

<img src="https://pbs.twimg.com/media/HLlsyI3W8AAYqUP?format=jpg&name=4096x4096" width="100%" alt="Cosmological Constant">

Einstein introduced Λ in 1917 to hold the universe static. When Hubble observed redshift, Einstein removed Λ, calling it his 'biggest blunder.' A century later, standard cosmology revived Λ as 'dark energy.' This note reframes Λ as geometry: its coefficient is set by the first positive curvature mode of the cosmic boundary, in a static universe where redshift is phase evolution on the boundary. Einstein's instinct to keep Λ geometric was sound.

The Möbius band selects half-integer modes; the lowest positive eigenvalue is the surface scalar curvature $R_\Sigma = 2/R^2$, where $R$ is the curvature radius of $S^3$. The Gauss equation, under the totally geodesic embedding of the covering great-$S^2$ band (with the Möbius as its edge-identified quotient) and isotropy, converts this surface seed to the model relation $\Lambda(R) = 3/R^2$, larger by a factor of 3/2.

| Quantity | Value |
|---|---|
| Derived | $\Lambda R^2 = 3$, where 3 = eigenvalue (2) $\times$ Gauss/de Sitter (3/2) |
| Scale $R$ | Open; fixed independently by two routes: the coupling ($\alpha$) returns $\Lambda$ to ~24%, the mass spectrum gives $R \approx 20$ Gpc (order of magnitude) |
| Forward prediction | $\Lambda$ to ~24% (coupling route); $\Lambda \approx 8 \times 10^{-54}\;\text{m}^{-2}$ from the mass-spectrum $R$ (order of magnitude, ~$14\times$ below) as cross-check |
| Observed | $1.11 \times 10^{-52}\;\text{m}^{-2}$ |
| de Sitter value | $R = \sqrt{3/\Lambda_\text{obs}} \approx 5.3$ Gpc reproduces $\Lambda$ by construction (circular) |

Standard cosmology already uses the de Sitter relation $\Lambda R^2 = 3$ when $R$ is the de Sitter curvature radius. What this framework adds is a spectral origin for the coefficient: the surface seed $R_\Sigma = 2/R^2$ is the first positive curvature mode of the Möbius boundary, with the Gauss/de Sitter factor $3/2$ supplying the rest.

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

$$\Lambda \cdot \ell_P^2 \approx 2.90 \times 10^{-122}$$

No mechanism assuming simply connected flat topology explains this value. The standard approach begins with a 4D spacetime, writes down field equations, and asks what value of Λ those equations permit. On a simply connected, non-compact spatial background, the answer is: any value, or a divergent one. The problem is upstream. General relativity is local: it describes dynamics on a domain but does not specify the domain itself. 

The 4D field equations describe dynamics on a geometry; the admissible geometry is constrained by the topology. Reversing this hierarchy, the present framework starts from the spatial topology, derives the first positive eigenvalue of the boundary, and reads the $\Lambda = 3/R^2$ relation from it. The 4D dynamics, including the Friedmann equation, are how observers inside the geometry register that eigenvalue as a curvature scale.

## II. The Topology

Eigenvalues arise from differential equations on a domain; the shape determines the spectrum. We choose the shape:

$$S^1 = \partial(\text{Mobius}) \hookrightarrow S^3, \quad \partial S^3 = \emptyset$$

| Manifold | Dim | Role |
|---|---|---|
| $S^1$ | 1D | Boundary of Möbius band |
| Möbius | 2D | Non-orientable surface; carries eigenproblem |
| $S^3$ | 3D | Space |

This is the minimal topology: $S^3$ is the unique simply connected closed 3-manifold (Poincaré); Möbius is the unique minimal non-orientable surface with $S^1$ boundary. Here "boundary" refers to the one-dimensional boundary of the Möbius carrier, $S^1 = \partial(\text{Möbius})$, not to a boundary of the ambient spatial manifold. The ambient space remains closed: $\partial S^3 = \emptyset$.

The anti-periodic boundary condition, the half-integer spectrum, and the $\mathbb{Z}_2$ holonomy all require a surface whose normal direction cannot be globally defined. An orientable annulus with $S^1$ boundary would admit the ordinary periodic sector as the natural untwisted lowest sector, with no forced $\mathbb{Z}_2$ reversal. The Möbius band is the minimal surface for which the twist is geometric rather than imposed externally.

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

$R$ is the curvature radius of $S^3$, the single dimensionful scale of the framework. Determining it independently of Λ is the framework's open problem; §V gives two live routes, the coupling ($\alpha$) route (better-conditioned, returning Λ to ~24%) and the particle mass spectrum (an order-of-magnitude cross-check).

The Möbius band has a single boundary traversed twice. Traversing the band once returns a field to the opposite side. The spectral sector relevant for Λ is the twisted sector:

$$\psi(L, w) = -\psi(0, {-w})$$

with free transverse boundary condition (Neumann): $\partial_w\psi\big\vert_{w = \pm W} = 0$.

### B. The Spectrum

With boundary conditions set, the eigenvalues follow. For the constant transverse mode, $\psi$ is constant in $w$, so the coordinate reflection drops out and the condition reduces to the longitudinal anti-periodic condition:

$$\psi(y + L) = -\psi(y)$$

Applying this anti-periodic boundary condition to the general solution $\psi \propto e^{iky}$:

$$e^{ikL} = -1$$

Satisfied when $kL = (2m + 1)\pi$ for integer $m$. The constant mode ($k = 0$) is forbidden; anti-periodicity requires at least one sign flip. The solutions give a half-integer spectrum.

## III. The First Positive Mode

The cosmological coefficient rests on one curvature value: $2/R^2$, where $R$ is the curvature radius of $S^3$. The value is geometric and primary. It is twice the sectional curvature $K = 1/R^2$; equivalently the surface scalar curvature $R_\Sigma = 2K_G$; equivalently the Ricci eigenvalue on $1$-forms of $S^3$. Two independent spectral problems return it.

The Möbius surface fixes the boundary condition and selects which eigenvalue is physical. It does not supply the magnitude. The magnitude is the curvature of $S^3$.

| Möbius role | Consequence |
|---|---|
| Anti-periodic BC + $\mathbb{Z}_2$ holonomy | Half-integer longitudinal spectrum; the constant mode is forbidden. |
| Orientation twist (nontrivial line bundle) | No strictly positive ground state exists; the relevant datum is the first positive eigenvalue. |
| Isotropy (CMB to $10^{-5}$) + narrow band $W \leq \pi R/2$ | Selects the zonal $\ell = 1$ mode $\sin(y/R)$ at $2/R^2$ over the wide-band undercut. |

### A. The Totally Geodesic Condition

The metric that matches the first positive mode is the totally geodesic one, with no extrinsic structure ($K_{ij} = 0$) on the covering great-$S^2$ band. This is the totally geodesic condition. It carries no bending information, and the totally geodesic metric is the one whose curved Laplacian has the zonal first-positive mode $\sin(y/R)$ as its eigenfunction. The selection is geometric, not nodal.

$K_{ij} = 0$ is a pointwise condition; non-orientability is a global topological property. They operate at different levels. The covering $S^2 \subset S^3$ is totally geodesic ($K_{ij} = 0$ everywhere). The Möbius band is constructed from a spherical band on this $S^2$ by the boundary-edge identification $(0, w) \sim (\pi R, -w)$ and inherits the constant-curvature metric through this construction. This covering construction is forced, not a modeling choice: a totally geodesic surface in $S^3$ lies in a great $S^2$, which is orientable, so no Möbius band in $S^3$ can itself be totally geodesic.

A totally geodesic surface in $S^3$ of radius $R$ carries the constant-curvature metric

$$ds^2 = dy^2 + \cos^2(y/R)\,dw^2,$$

with Gaussian curvature $K_G = 1/R^2$ and scalar curvature $R_\Sigma = 2K_G = 2/R^2$. The factor $\cos(y/R)$ vanishes at $y = \pi R/2$: the pole of the covering $S^2$, which becomes a cone point on the Möbius quotient.

### B. The Cone Point

At $y = \pi R/2$ the metric coefficient $\cos(y/R)$ vanishes. On the covering $S^2$ this is a smooth pole. On the edge-identified Möbius band, the same coordinate collapse produces a conical singularity with cone angle $2W/R$, equivalently angular deficit $2\pi - 2W/R$. The surface is smooth away from this single point; the Bochner identity and Gauss equation are applied on the smooth locus, with the cone point controlled by excision (§III.D).

Setting $\delta = y - \pi R/2$, the weight satisfies $|\cos(y/R)| \sim |\delta|/R$ near $\delta = 0$. The reduced eigenequation in Sturm-Liouville form,

$$(|\delta|/R \cdot u')' + \lambda\,|\delta|/R \cdot u = 0,$$

has indicial equation $s^2 = 0$ (double root); the two local solutions are $u_1 = a_0 + a_2\delta^2 + O(\delta^4)$ and $u_2 = \log|\delta| + b_2\delta^2 + O(\delta^4)$. Both are square-integrable: the cone is a limit-circle endpoint in the constant sector. The Friedrichs extension selects the regular branch by finite Dirichlet integral; the logarithmic branch fails it, $\int (u')^2|\cos|\,d\delta \sim \int \delta^{-1}\,d\delta = \infty$.

Because the endpoint is limit-circle, the bottom of the spectrum is extension-dependent: zero for Friedrichs through the discontinuous zero mode, negative for bridging extensions. No self-adjoint extension has a strictly positive ground state. The quantity carried forward is therefore the first positive eigenvalue, extension-stable for $\delta_0 > 2R/e$. The Friedrichs regular branch fixes the constant sector; it does not supply a positive-bottom ground state.

### C. Direct Computation and the Two Routes

For the metric $ds^2 = dy^2 + f(y)^2\,dw^2$ with $f = \cos(y/R)$, the Laplace-Beltrami operator on $y$-dependent functions is

$$\Delta u = u'' - \frac{1}{R}\tan(y/R)\cdot u'.$$

For $u_0 = \sin(y/R)$, with $u_0' = \tfrac{1}{R}\cos(y/R)$ and $u_0'' = -\tfrac{1}{R^2}\sin(y/R)$,

$$-\Delta u_0 = \frac{1}{R^2}\sin(y/R) + \frac{1}{R}\tan(y/R)\cdot\frac{1}{R}\cos(y/R) = \frac{2}{R^2}\sin(y/R),$$

eigenvalue $2/R^2$; and $\sin((y+\pi R)/R) = -\sin(y/R)$ satisfies the anti-periodic condition.

The two terms make the flat-strip comparison explicit. The first, $-u_0'' = \sin(y/R)/R^2$, is what the same eigenfunction returns under the Euclidean Laplacian $-\partial_y^2$ on a flat strip: the bare anti-periodic wavelength scale $1/R^2$, half the scalar curvature. The curvature drift $\frac{1}{R}\tan(y/R)\,u_0'$ supplies an equal $1/R^2$, doubling the same mode to the scalar-curvature value $2/R^2 = R_\Sigma$. Topology fixes which mode is selected; curvature fixes its value.

**Why $2/R^2$ is the value.** Two independent routes return it, one extension-free and one extension-robust.

*Route 1 (extension-free).* At a flat connection on $S^3$, or on any quotient $S^3/\Gamma$, the gauge-covariant Hodge Laplacian on coexact $1$-forms obeys the Weitzenböck identity $\Delta_\text{Hodge} = \nabla_A^\ast\nabla_A + \mathrm{Ric}$. Since $\nabla_A^\ast\nabla_A \geq 0$ and $\mathrm{Ric} = (2/R^2)g$ acts on $1$-forms by multiplication by $2/R^2 > 0$, every coexact fluctuation satisfies $\lambda \geq 2/R^2$. The bound is a two-line consequence of $\mathrm{Ric} > 0$ (companion Yang-Mills paper). No cone, no Möbius, no extension choice enters.

*Route 2 (extension-robust).* The twisted anti-periodic scalar Laplacian on the curved Möbius band has first positive eigenvalue $2/R^2$, eigenfunction $\sin(y/R)$ (the $\ell = 1$ zonal tower), identical for the Friedrichs extension and for every bridging extension with $\delta_0 > 2R/e$, in the narrow band $0 < W \leq \pi R/2$ (companion spectral paper).

Both return $2/R^2 = R_\Sigma = 2K_G$.

Route 1 is a Ricci eigenvalue on $1$-forms; Route 2 is a scalar surface eigenvalue. They coincide as numbers, not as operators, because both equal twice the sectional curvature. The $1$-form floor is not the scalar eigenvalue; only the value is shared. Route 1 is unconditional; Route 2 holds under $W \leq \pi R/2$ and $\delta_0 > 2R/e$.

**Narrow-band condition.** For $W > \pi R/2$ a wide mode with longitudinal envelope $|\cos(y/R)|^{\alpha_0}$, $\alpha_0 = \pi R/(2W)$, and eigenvalue $\alpha_0(\alpha_0 + 1)/R^2$, drops below $2/R^2$; the envelope is cone-singular for $\alpha_0 < 1$. At $W = \pi R/2$, $\alpha_0 = 1$ and $\alpha_0(\alpha_0 + 1) = 2$ exactly, so the narrow band is tight. The framework takes $W \leq \pi R/2$ as a physical input on the cosmic boundary; the selection is an input, not a derived fact.

**Rayleigh upper bound.**

$$\frac{\int_M |\nabla u_0|^2\,dA}{\int_M u_0^2\,dA} = \frac{8W/3R}{4WR/3} = \frac{2}{R^2},$$

so $\lambda_1 \leq 2/R^2$. The half-width $W$ cancels: the first positive eigenvalue depends only on $R$.

### D. The Lower Bound

For the regular zonal mode, a Bochner estimate on the smooth excised surface returns the matching lower bound. On an eigenfunction $-\Delta u = \lambda u$, the Bochner formula in dimension 2 gives

$$\tfrac{1}{2}\Delta|\nabla u|^2 = |\nabla^2 u|^2 + K_G|\nabla u|^2 - \lambda|\nabla u|^2.$$

Apply it on the excised surface $M_\epsilon = M \setminus \{|y - \pi R/2| < \epsilon\}$. The zonal mode $\sin(y/R)$ is regular at the cone, so on the excision curve $\partial_\nu|\nabla u|^2 = O(\epsilon)$ over arclength $O(\epsilon)$, contributing $O(\epsilon^2) \to 0$. The boundary curves $w = \pm W$ are geodesics with $\partial_\nu u = 0$, killing that term. The bulk identity becomes $\int|\nabla^2 u|^2 = (\lambda - K_G)\int|\nabla u|^2$, and Cauchy-Schwarz $|\nabla^2 u|^2 \geq (\Delta u)^2/2 = \lambda^2 u^2/2$ with $\int|\nabla u|^2 = \lambda\int u^2$ gives $\lambda - K_G \geq \lambda/2$, hence $\lambda \geq 2K_G = R_\Sigma$.

This corroborates the value for the regular narrow-band sector: with the Rayleigh upper bound it pins $\lambda_1 = R_\Sigma$ on the smooth excised surface. It is not a universal bound. The wide-band modes $|\cos(y/R)|^{\alpha_0}$ ($\alpha_0 < 1$, §III.C) are singular at the cone, their excision contribution does not vanish, and they are correctly not excluded, consistent with their eigenvalues lying below $R_\Sigma$ for $W > \pi R/2$. The extension-free floor belongs to Route 1, not to this scalar-sector inequality.

### E. The Identity

The Rayleigh upper bound (§III.C), the Bochner lower bound for the regular sector (§III.D), and the two routes pin the value:

$$\boxed{\lambda_1 = \frac{2}{R^2} = R_\Sigma = 2K_G}$$

This is the surface scalar curvature, carried into the Gauss-Codazzi conversion of §IV. The same number is the Ricci eigenvalue on $1$-forms of $S^3$ (Route 1) and the first positive eigenvalue of the curved twisted operator (Route 2); the Weitzenböck $1$-form bound $\lambda \geq 2/R^2$ is the extension-free confirmation. The word "floor" is reserved for Route 1, the $1$-form bound; the shared seat of all three is the curvature value $R_\Sigma = 2/R^2$. This surface value carries no $\Lambda$: the cosmological constant $\Lambda = 3/R^2$ is produced from it only by the Gauss-Codazzi conversion of §IV.

## IV. The Conversion

Section III delivers a single curvature value: the surface scalar curvature $R_\Sigma = 2/R^2$, established by two independent spectral routes. This value carries no $\Lambda$. The Gauss equation converts it into the cosmological constant through the standard general-relativistic chain. Under the totally geodesic embedding of the covering great-$S^2$ band the Codazzi equation is trivially satisfied, so only the Gauss equation contributes; this is the Gauss-Codazzi conversion announced at the close of Section III. All of the new content is upstream, in the spectral identification of $R_\Sigma$; this section is the conventional conversion.

### A. What Is Imported

One ingredient in this section is imported. For a maximally symmetric de Sitter vacuum with spatial sections $S^3(R)$, the standard GR normalization gives

$$\Lambda = \frac{R_\text{spatial}}{2} \quad\Longleftrightarrow\quad R_\text{spatial} = 2\Lambda.$$

This is the de Sitter normalization imported from general relativity, not a second independently derived input; the factor of 2 is imported. The end relation $\Lambda R^2 = 3$ is then the de Sitter identity for $S^3(R)$, carrying the spectral origin of the seed $R_\Sigma$. The genuinely new content is the spectral identification of $R_\Sigma = 2/R^2$ (Section III, two routes); the present section applies the Gauss equation and the de Sitter normalization to convert that surface seed into the spacetime cosmological constant.

### B. Gauss Equation

The Gauss equation relates the intrinsic curvature of an embedded surface to the ambient curvature:

$$R_\Sigma = R_\text{spatial} - 2\,\text{Ric}(\mathbf{n},\mathbf{n}) + H^2 - A_{ij}A^{ij}$$

| Symbol | Meaning |
|---|---|
| $R_\Sigma$ | Intrinsic scalar curvature of the surface (the seed from §III) |
| $R_\text{spatial}$ | Scalar curvature of the ambient three-space |
| $A_{ij}$ | Second fundamental form |
| $H$ | Trace of the second fundamental form ($g^{ij}A_{ij}$) |
| $\mathbf{n}$ | Unit normal to the surface |

### C. Totally Geodesic Simplification

For the totally geodesic covering great-$S^2$ band ($A_{ij} = 0$, $H = 0$), the equation simplifies:

$$R_\Sigma = R_\text{spatial} - 2\,\text{Ric}(\mathbf{n},\mathbf{n})$$

### D. Isotropic Space

On an isotropic constant-curvature three-space, the spatial Ricci tensor is

$$R_{ij} = \frac{R_\text{spatial}}{3}\,g_{ij},$$

so $\text{Ric}(\mathbf{n},\mathbf{n}) = R_\text{spatial}/3$. Substituting into the reduced ($A_{ij} = 0$) Gauss equation:

$$R_\Sigma = R_\text{spatial} - \frac{2\,R_\text{spatial}}{3} = \frac{R_\text{spatial}}{3}.$$

Inverting,

$$R_\text{spatial} = 3\,R_\Sigma = \frac{6}{R^2}.$$

This step is geometry: the factor 3 is the isotropic spatial Ricci trace under the totally geodesic condition ($A_{ij} = 0$) realized on the covering great-$S^2$ band.

### E. Connection to Λ

Applying the imported de Sitter normalization $\Lambda = R_\text{spatial}/2$ of §A to the derived $R_\text{spatial} = 6/R^2$:

$$\Lambda = \frac{R_\text{spatial}}{2} = \frac{3}{2}\,R_\Sigma = \frac{3}{2}\cdot\frac{2}{R^2} = \frac{3}{R^2}.$$

The chain closes:

$$R_\text{spatial} = 3\,R_\Sigma = 2\Lambda \qquad\Longrightarrow\qquad \Lambda = \tfrac{3}{2}\,R_\Sigma.$$

The 3 comes from the isotropic spatial Ricci trace. The 2 comes from the de Sitter normalization relating $R_\text{spatial}$ to $\Lambda$. The 3/2 is their ratio: the Gauss-equation interface between 2D surface geometry and 3D spatial curvature.

### F. Summary

The numeral in $\Lambda R^2 = 3$ factors as the surface seed times the Gauss conversion:

$$\Lambda R^2 = \underbrace{(R_\Sigma R^2)}_{2}\cdot\underbrace{\tfrac{3}{2}}_{\text{Gauss}} = 3, \qquad \tfrac{3}{2} = \frac{3\ (\text{isotropic Ricci trace})}{2\ (\text{de Sitter normalization})}.$$

| Factor | Source | Status |
|---|---|---|
| 3 | Spatial Ricci trace (isotropic space) | Derived (geometry) |
| 2 | de Sitter relation ($R_\text{spatial} = 2\Lambda$) | Imported (GR normalization) |
| 3/2 | Net conversion | Derived $\times$ imported |

| Element | Status |
|---|---|
| $R_\Sigma = 2/R^2$ (two routes, §III) | Derived |
| Gauss factor 3 ($A_{ij} = 0$ on covering band + isotropy) | Derived |
| de Sitter normalization (the 2 in $\Lambda = R_\text{spatial}/2$) | Imported |

The framework supplies a geometric and spectral origin for the curvature seed $R_\Sigma$, then runs the standard de Sitter conversion. The new content is the seed; the conversion is GR.

## V. The Scale

Sections III and IV fixed the coefficient: $\Lambda = 3/R^2$. The radius $R$ remains, and $\Lambda = 3/R^2$ yields a number only with an *independent* $R$. Reading $R$ off $\Lambda$ through the de Sitter relation $R = \sqrt{3/\Lambda}$ is circular. An independent $R$ is the framework's central open problem.

### A. The Quotient Domain

The covering spatial manifold is $S^3$. Its observable harmonic domain is $S^3/2I$, where $2I$ is the binary icosahedral group, the largest exceptional finite subgroup of $\text{SU}(2) \cong S^3$, with $|2I| = 120$.

The postulate of §II specifies the minimal boundary topology. The bulk counterpart is maximal exceptional discrete symmetry. Among the finite exceptional subgroups of $\text{SU}(2)$, $2I$ is the largest. The framework pairs the simplest boundary with the most symmetric exceptional spatial quotient.

These two roles are distinct. The local curvature geometry used in §§II–IV is defined on the universal cover $S^3(R)$, where the great $S^2 \subset S^3$ and the Möbius carrier are constructed. The quotient $S^3/2I$ enters at the level of observable scalar harmonics: it restricts the allowed global shells to the $2I$-invariant sector while preserving the same curvature radius $R$. Thus $S^3$ supplies the local embedding geometry, and $S^3/2I$ supplies the large-scale harmonic selection rule.

### B. The Molien Gap

Scalar harmonics on $S^3$ have eigenvalue $N(N+2)/R^2$ and degeneracy $(N+1)^2$. On the quotient, only $2I$-invariant harmonics survive; the central element $-1 \in 2I$ restricts to even $N$. The Molien series

$$P(t) = \frac{1 - t^{60}}{(1 - t^{12})(1 - t^{20})(1 - t^{30})}$$

shows the first nontrivial invariant at $N = 12$. Shells $N = 2, 4, 6, 8, 10$ are absent. This is the Molien gap, a spectral fact about the $S^3/2I$ harmonic structure.

### C. The CMB Low-ℓ Deficit

Each invariant shell maps to a characteristic multipole $\ell_\text{char}(N) = \sqrt{N(N+2)}\,\chi_{*}/R$, where $\chi_{*} \approx 14.0$ Gpc is the comoving distance to last scattering. The Molien gap removes the low shells ($N = 2$ through $10$), thinning the mode density below $\ell \approx 30$ and producing a gradual low-ℓ power deficit in the range documented across COBE, WMAP, and Planck. This is a spectral consequence of the $S^3/2I$ harmonic structure and stands as a CMB result. It is not an independent handle on $R$: the shell-to-multipole map carries $R$ rather than fixing it, so the Molien gap does not by itself determine the scale.

### D. The Scale R: Two Live Routes

With the de Sitter relation circular and the Molien gap not independent, two routes fix $R$ independently. The better-conditioned one is the coupling ($\alpha$): the measured fine-structure constant fixes the hierarchy $\Omega_\Lambda$, hence $R$, with no input from $\Lambda$, the CMB, or the de Sitter relation, and returns $\Lambda = 3/R^2$ to within ~24%. The second is the particle mass spectrum, an independent order-of-magnitude cross-check: the fermion mass formula depends on the hierarchy factor $\Omega_\Lambda = (R/\ell_P)^2$ through the McKay-distance dilution $(\sqrt{\Omega_\Lambda})^{\text{dist}/30}$, and inverting the electron-muon mass ratio for that dependence fixes $R$ with no input from $\Lambda$, the CMB, or the de Sitter relation:

$$m_e,\ m_\mu \ \xrightarrow{\ \text{mass formula}\ }\ R \approx 20\ \text{Gpc} \ \xrightarrow{\ \Lambda = 3/R^2\ }\ \Lambda \approx 8 \times 10^{-54}\ \text{m}^{-2},$$

about $14\times$ below the observed $1.11 \times 10^{-52}\ \text{m}^{-2}$: agreement to order of magnitude, not percent. The precision floor is structural, set by the McKay lever ($60\times$ for adjacent McKay distance) amplifying the mass formula's few-percent residual scatter; no assigned fermion pair beats electron-muon. This is a genuine, independent leg under $\Lambda \sim 3/R^2$ at $R$ of order Gpc, not a percent-level prediction. Details in the working notes: [R from the mass spectrum](../../framework/files/working/files/r-from-mass-spectrum.md) and [The R Problem](../../framework/files/working/files/r-problem.md).

For reference, the de Sitter value $R = \sqrt{3/\Lambda_\text{obs}} \approx 5.3$ Gpc is the consistency radius read back from the observed $\Lambda$ (equivalently the standard $R = c/(H_0\sqrt{\Omega_\Lambda})$); it is circular and not an independent determination.


## VI. The Result

The derivation yields the model relation:

$$\Lambda(R) = \frac{3}{R^2}$$

If $R$ is read from $\Lambda_\text{obs}$ through the de Sitter relation, this is circular; if $R$ is supplied independently (§V), it becomes a test.

The coefficient 3 decomposes as two factors: the surface curvature seed $R_\Sigma = 2/R^2$ (the first positive mode on the curved Möbius surface, §III), and the Gauss/de Sitter conversion 3/2 (§IV). Their product: $2 \times 3/2 = 3$.

Turning the relation into a number requires an independent $R$. The coupling ($\alpha$) route (§V) is the better-conditioned one, returning $\Lambda = 3/R^2$ to within ~24%; the particle mass spectrum gives $R \approx 20$ Gpc and hence $\Lambda \approx 8 \times 10^{-54}\;\text{m}^{-2}$, an independent order-of-magnitude cross-check against the observed $1.11 \times 10^{-52}\;\text{m}^{-2}$. Together they are the forward prediction: real, independent legs, not a percent-level number.

### The Derivation Chain

| Step | Input | Output |
|---|---|---|
| 1 | Möbius topology | Anti-periodic BC; $L = \pi R$ |
| 2 | $R$ from the independent routes (§V) | $R$ of order Gpc (α: Λ to ~24%; mass: ~20 Gpc) |
| 3 | Even transverse mode | 1D reduction |
| 4 | Anti-periodic BC | Half-integer spectrum |
| 5 | Isotropy (CMB) | Constant transverse mode ($m = 0$) |
| 6 | Constant transverse mode ($m=0$) → totally geodesic covering band → curved metric | $\lambda_1 = 2/R^2 = R_\Sigma$ |
| 7 | Bochner (regular sector) | $\lambda_1 \geq R_\Sigma$; pins $\lambda_1 = R_\Sigma$ |
| 8 | $\lambda_1 = R_\Sigma = 2/R^2$ | surface curvature seed (no $\Lambda$) |
| 9 | Gauss equation + totally geodesic covering band | $R_\text{spatial} = 3R_\Sigma$ |
| 10 | de Sitter (GR normalization, imported): $R_\text{spatial} = 2\Lambda$ | $\Lambda(R) = \frac{3}{2}\,R_\Sigma$ |
| 11 | Model relation | $\Lambda(R) = 3/R^2$ |

### Derived vs. Imported

| Element | Status | Source |
|---|---|---|
| Anti-periodic BC | Derived | Möbius topology |
| $\lambda_1 = 2/R^2$ | Derived | Twisted Laplacian on curved surface (two routes, §III) |
| $\lambda_1 \geq R_\Sigma$ (regular sector) | Derived | Bochner bound (§III.D) |
| Gauss factor 3 | Derived | Totally geodesic covering great-$S^2$ band in isotropic $S^3$ |
| de Sitter normalization ($R_\text{spatial} = 2\Lambda$) | Imported | GR/de Sitter normalization |
| Coefficient 3 ($=2\times\tfrac{3}{2}$) | Derived $\times$ imported | Seed $\times$ Gauss/de Sitter |
| Scale $R$ | Open | The Molien gap does not fix $R$; two independent routes do: the coupling ($\alpha$) route (returns Λ to ~24%) and the particle mass spectrum (§V, order of magnitude) |

The content of the derivation is the surface seed $R_\Sigma = 2/R^2$ and its spectral origin; the conversion to $\Lambda = 3/R^2$ is standard GR. Standard cosmology treats $\Lambda R^2$ as a free parameter; here it is the fixed coefficient $\Lambda R^2 = 3$. The scale $R$ remains open, so $\Lambda = 3/R^2$ becomes a forward prediction to ~24% through the coupling route, with the mass spectrum as an order-of-magnitude cross-check (§V).

## VII. Compatibility with General Relativity

Einstein's field equations are unchanged:

$$G_{\mu\nu} + \Lambda g_{\mu\nu} = 8\pi G \, T_{\mu\nu}$$

This framework provides a geometric origin for the coefficient in $\Lambda = 3/R^2$; the numerical value still requires an independent determination of $R$. In the de Sitter limit, the Friedmann equation:

$$H^2 = \Lambda / 3$$

is how observers register the curvature scale. General relativity describes dynamics in space; topology specifies the boundary condition. The topology constrains the metric the way a cavity constrains its resonant frequencies: the boundary is logically prior to the vibration.

The standard cosmological constant problem moves Λ to the right-hand side and identifies it with zero-point vacuum energy density. That step is a reinterpretation, not a derivation. Λ appears on the left-hand side multiplying the metric, a geometric property of the domain, not a matter source. 

Zero-point fluctuations are real and gravitate locally; they appear in $T_{\mu\nu}$ and shift masses and couplings through standard renormalization. They do not set the topological eigenvalue because that eigenvalue is a global property of the boundary, determined by the domain geometry and insensitive to local mode sums. 

The 122-order discrepancy arises from equating two objects that were never the same: a geometric boundary condition on the left and a local energy density on the right.

## VIII. Falsification

Eigenvalues of the Laplacian on a fixed geometric domain are constants. In this framework, topology and curvature fix the coefficient in $\Lambda(R) = 3/R^2$. Once $R$ is fixed independently, $\Lambda$ is fixed; redshift evolution of the dark-energy density would therefore put the framework under direct pressure.

### Falsification Criteria

| Prediction | Serious tension | Falsified |
|---|---|---|
| Λ constant | Independent probes prefer evolving dark energy over ΛCDM at $> 3\sigma$, after accounting for known systematics | Robust multi-probe evidence requires redshift evolution of the dark-energy density at $> 5\sigma$ |
| $\Lambda_\text{obs} \cdot R^2 = 3$ | Independent determinations give a $> 3\sigma$ departure from 3 | Independent determinations give a $> 5\sigma$ departure from 3, with $R$ obtained without using the Λ-radius relation |

These predictions are stated in advance of the European Space Agency's Euclid Data Release 1. Both criteria are read against the spectroscopic BAO and weak-lensing analyses, which arrive with the full DR1 in mid 2027; the earlier DR1-Foundation release in November 2026 carries raw data, calibrated images, catalogues and spectra over roughly 1900 deg², but no cosmology-derived products. ESA states that its release dates are tentative and will have to be confirmed.

---

Einstein put geometry into his equations and then took it out. A century of physics put it back in and called it energy when it was geometry all along. The blunder was not adding Λ, it was removing it.

The cosmological constant enters geometrically, not as a local vacuum-energy sum. Its coefficient is the first positive curvature mode of the cosmic boundary; the remaining problem is the independent determination of $R$.

*Einstein's constant, geometrized.*

---

/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /
