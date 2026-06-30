/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /

---

<img src="https://github.com/dmobius3/mode-identity-theory/blob/main/files/assets/cone%20point%20banner.png" width="100%" alt="First Eigenvalue">

We study the twisted Laplacian, the Laplace-Beltrami operator on sections of the orientation line bundle, on a constant-curvature Möbius band $M(W)$ of half-width $W$, built from a spherical band on $S^2(R)$ with the antipodal-edge identification. Its metric collapses one transverse fiber to a cone point, where the operator is not essentially self-adjoint in the constant transverse sector, so the bottom of the spectrum depends on the self-adjoint extension. For the Friedrichs extension the bottom is $0$, attained by a discontinuous piecewise-constant zero mode $\phi_0$, and the operator is unitarily equivalent to the Neumann Laplacian on a spherical lune. The sector-regular bridging realization excludes $\phi_0$ and instead carries a single cone-localized bound state $\lambda_b(\delta_0) = -4e^{-2\gamma}/\delta_0^2\,(1 + O(\delta_0^2/R^2))$ below zero, set by a renormalization length $\delta_0$; by Friedrichs maximality, no self-adjoint extension has strictly positive spectral bottom. 

The first positive eigenvalue, by contrast, is stable across these realizations: for the Friedrichs extension and for bridging with $\delta_0 > 2R/e$ it equals $2/R^2$ for $0 < W \le \pi R/2$ and $\alpha_0(\alpha_0+1)/R^2$, $\alpha_0 = \pi R/(2W)$, for $\pi R/2 < W < \pi R$, doubly degenerate at the critical width. We prove this by separating the operator into transverse Neumann sectors and solving the reduced singular Sturm-Liouville problems in closed form via Legendre functions. For $W > \pi R/2$ the first positive eigenfunction changes sign, reflecting the nontriviality of the orientation bundle.

---

## 1. Introduction

On a Möbius band the orientation line bundle has nontrivial holonomy: a section changes sign after one circuit of the core loop. We study how this twist affects the Laplacian when the metric also degenerates, the cone lying exactly where a transverse fiber collapses. On a smooth surface a nowhere-vanishing section would trivialize the bundle, so the twist already rules out a positive (nowhere-vanishing) ground eigenfunction (cf. [Shigekawa] for the magnetic spectral-positivity criterion); the cone determines how that obstruction appears in the spectrum, and the answer depends on the self-adjoint extension.

The setting is the twisted Laplacian (the Laplace-Beltrami operator on sections of the orientation bundle $\mathcal{L}$) on a constant-curvature Möbius band $M(W)$ constructed from a spherical band on $S^2(R)$ of half-width $W$. The metric $ds^2 = dy^2 + \cos^2(y/R)\,dw^2$ collapses a transverse fiber to a cone point $p_c$ at $y = \pi R/2$. At $p_c$ the operator is not essentially self-adjoint in the constant transverse sector, and a choice of self-adjoint extension is required. This choice is spectral, not cosmetic: it controls the bottom of the spectrum, and different realizations give qualitatively different bottoms. The first positive eigenvalue, by contrast, is shared by the Friedrichs extension and the bridging family with $\delta_0 > 2R/e$, and it is this invariant that we compute.

We first classify the bottom of the spectrum across realizations (Theorem 1.1), then isolate the invariant that survives the extension choice (Theorem 1.2).

> **Theorem 1.1** (Classification of the bottom of the spectrum)**.** Let $A$ be any self-adjoint extension at the cone of the twisted Laplacian on $M(W)$, $0 < W < \pi R$. Then $\inf\sigma(A) \le 0$. Equality holds if and only if $A$ is a nonnegative extension; among these the Friedrichs extension is maximal, and its bottom is attained by the discontinuous piecewise-constant zero mode $\phi_0$ (eigenvalue $0$, the constant-sector kernel). The bridging realization $A^{\mathrm{br}}_{\delta_0}$ (Definition 3.4) is not nonnegative: it carries a single cone-localized bound state $\lambda_b(\delta_0) = -4e^{-2\gamma}/\delta_0^2\,(1 + O(\delta_0^2/R^2))$, with $\gamma$ the Euler-Mascheroni constant, and zero lies in the resolvent set. In particular no self-adjoint extension has strictly positive spectral bottom.

> **Theorem 1.2** (First positive eigenvalue and width transition)**.** The first positive eigenvalue of the twisted Laplacian on $M(W)$ is shared by the Friedrichs extension $\Delta_F$ and by the bridging realization $A^{\mathrm{br}}_{\delta_0}$ (Definition 3.4) for every $\delta_0 > 2R/e$, and equals
>
> $$\lambda_1(W) = \begin{cases} 2/R^2 & 0 < W \le \pi R/2, \\ \alpha_0(\alpha_0+1)/R^2, \quad \alpha_0 = \pi R/(2W) & \pi R/2 < W < \pi R. \end{cases}$$
>
> At $W = \pi R/2$ it is doubly degenerate. Both branches are realized by explicit eigenfunctions: $\sin(y/R)$, the $\ell = 1$ zonal Legendre polynomial, for the narrow regime, and $\lvert\cos(y/R)\rvert^{\alpha_0}\sin(\pi w/2W)$, with longitudinal factor $(1-x^2)^{\alpha_0/2}$ where $x = \sin(y/R)$, which reduces to the sectoral harmonic $P_{\alpha_0}^{\alpha_0}$ at integer degree, for the wide regime.

For the Friedrichs extension the operator is unitarily equivalent to the Neumann Laplacian on a spherical lune of opening $2W/R$ (Proposition 4.2), so Theorem 1.2 is, in that case, the first nonzero Neumann eigenvalue of the lune, and its width transition is the crossing of the two lowest lune branches. What the lune does not capture is the persistence of this value across the bridging family for $\delta_0 > 2R/e$ and the extension-dependence of the bottom.

The proof separates the operator into transverse Neumann sectors and solves each reduced Sturm-Liouville problem in closed form via Legendre functions. Only the constant (zonal) sector carries the cone-condition ambiguity that separates our realizations: there the cone is a limit-circle endpoint, while every other sector is limit-point except the wide-band first odd sector, which is limit-circle but where Friedrichs and bridging both take the regular branch. In the constant sector the cone parity splits the spectrum into a symmetric tower $\{2/R^2, 12/R^2, 30/R^2, \ldots\}$, common to the Friedrichs and bridging realizations, and an antisymmetric tower where they disagree. The Friedrichs antisymmetric tower is $\{0, 6/R^2, 20/R^2, \ldots\}$ with the zero mode at its base; the bridging condition deforms it through an explicit secular function and pushes the base below zero. So the narrow-regime first positive value $2/R^2$ comes from the symmetric tower and is robust, while the zero or negative bottom comes from the antisymmetric tower and is not.

The background comes from a few directions. Cheeger [Cheeger1979, Cheeger1983] founded the spectral geometry of conic singularities, with the Friedrichs extension and its link-geometry deficiency indices. Boscain and Prandi [BP] classify the self-adjoint extensions of the model conic metric $ds^2 = dx^2 + \lvert x\rvert^{-2\alpha_{\mathrm{BP}}}\,d\theta^2$ in the cone regime $\alpha_{\mathrm{BP}} \in (-3, -1]$, which contains our $\alpha_{\mathrm{BP}} = -1$, distinguishing disjoint (Friedrichs) and bridging dynamics. The local asymptotics are regular-singular in the sense of Brüning and Seeley [BS], and the limit-point/limit-circle alternative is governed by the inverse-square theory of Kalf, Schmincke, Walter, and Wüst [KSWW, RS]. The bridging condition is a Kirchhoff-type vertex condition [BK]; its closest predecessor is the length-parametrized cone-apex extension of Kay and Studer [KayStuder], whose logarithmic bound-state branch is the analogue of ours, though without the Möbius topology or the width transition. The anti-periodic half-integer longitudinal quantization is the line-bundle holonomy spectrum of Ballmann, Brüning, and Carron [BBC].

The closest Möbius-strip predecessor is Kalvoda, Krejčiřík, and Zahradová [KKZ], who study the Laplacian on a Möbius strip embedded in $\mathbb{R}^3$ with Dirichlet boundary conditions. Their thin-strip asymptotics yield effective one-dimensional operators. Our setting differs in three respects: constant positive curvature rather than an embedded strip, Neumann boundary conditions (which supply the constant transverse mode that activates the extension ambiguity), and the cone singularity absent from the KKZ geometry. The result is an exact finite-width spectral calculation rather than a thin-strip asymptotic.

Section 2 sets up the geometric model and Section 3 the operator domain, the self-adjoint extensions, and Friedrichs maximality. We then analyze the constant sector by parity (§4) and classify the bottom of the spectrum (§5). Section 6 resolves the nonconstant sectors and the width-dependent first positive eigenvalue, and Section 7 discusses the sign-changing eigenfunction and the status of the renormalization length $\delta_0$.

---

## 2. The Geometric Model $M(W)$

Consider the round 2-sphere $S^2(R)$ of radius $R$. Throughout, $R$ is the curvature radius of this constant-curvature model. Let $C$ be a great circle, and let $y$ denote arclength along a meridian measured from $C$, so that $y = 0$ and $y = \pi R$ correspond to antipodal arcs of $C$ reached on opposite sides of the pole at $y = \pi R/2$. Let $w$ denote arclength along $C$, with $w \in [-W, W]$ for a half-width parameter $0 < W < \pi R$. The induced metric on the band $\{(y, w) : 0 \le y \le \pi R,\; \lvert w\rvert \le W\}$ is

$$ds^2 = dy^2 + \cos^2(y/R)\,dw^2.$$

The Gauss curvature is $K = 1/R^2$ on the smooth locus and the scalar curvature is $R_{\mathrm{sm}} = 2/R^2$.

The Möbius band is obtained from the rectangle $[0, \pi R] \times [-W, W]$ by the single edge identification $(0, w) \sim (\pi R, -w)$. This gluing is the restriction to the edge $\{y = 0\}$ of the isometry $\tau(y, w) = (\pi R - y, -w)$ ($D\tau = \mathrm{diag}(-1, -1)$, $\det D\tau = +1$), since $\tau(0, w) = (\pi R, -w)$. The interior $0 < y < \pi R$ carries no identification, so $M(W)$ is not the quotient of the band by the global involution $\tau$. The result is the non-orientable surface

$$M(W) = [0, \pi R] \times [-W, W] \;/\; (0, w) \sim (\pi R, -w)$$

with boundary $\partial M \cong S^1$, since the two arcs $w = \pm W$ join into a single closed curve under the identification. The non-orientability arises from the edge identification itself: transporting a frame $(\partial_y, \partial_w)$ across the seam sends $\partial_w \mapsto -\partial_w$, reversing the frame orientation.

At $y = \pi R/2$, the metric coefficient $\cos(y/R)$ vanishes, collapsing the transverse fiber $\{y = \pi R/2\} \times [-W, W]$ to a single point $p_c$ in the metric space. Both boundary arcs pass through $p_c$ (the boundary meridians meet at the pole), so $p_c \in \partial M$ and the boundary curve has a corner at the cone vertex.

The local model is the one-point union of two half-cones meeting at the apex $p_c$: a punctured neighborhood of $p_c$ is disconnected into the $y < \pi R/2$ and $y > \pi R/2$ halves, since the geodesic distance to $p_c$ equals $\lvert y - \pi R/2\rvert$ and crossing between halves requires the collapsed fiber, every point of which is $p_c$. The link is two disjoint intervals $[-W, W]$, each of angular length $2W/R$; each half-cone has opening angle $2W/R$; and the closed boundary curve passes through $p_c$ twice, a figure-eight through the apex, with a corner on each side. This two-sided structure is what the four-dimensional cone boundary space and the deficiency count of §3 already encode.

Under Neumann boundary conditions at $w = \pm W$, the transverse problem unfolds onto a circle of circumference $4W/R$ (§3.4), recovering the circle-link framework of Boscain and Prandi [BP] with parameter $\alpha_{\mathrm{BP}} = -1$. Although $p_c$ lies on $\partial M$ as a surface point, it sits at $y = \pi R/2$, interior to the longitudinal interval $(0, \pi R)$. The reduced one-dimensional eigenvalue problems of §§4 and 6 inherit this interior singular-point structure, and the extension theory of §3 applies in full.

The cone angle $2W/R$ equals $\pi$ at the critical width $W = \pi R/2$. For $W < \pi R/2$ (narrow band), the cone angle is less than $\pi$; for $W > \pi R/2$ (wide band), it exceeds $\pi$. As $W \to \pi R$, each half of the band approaches a hemisphere.

---

## 3. Twisted Sections and the Operator Domain

### 3.1 The orientation line bundle

Since $M(W)$ is non-orientable, scalar functions on it do not capture the full spectral problem. The natural domain for the Laplacian is the space of sections of the orientation line bundle $\mathcal{L}$. A smooth function on the covering band $\widetilde{M} = [0, \pi R] \times [-W, W]$ descends to a section of $\mathcal{L} \to M$ if and only if it satisfies the equivariance condition

$$\psi(\pi R, -w) = -\psi(0, w) \qquad \text{for all } w \in [-W, W].$$

This sign reversal is the defining property of sections of $\mathcal{L}$: traversing the core loop once reverses the orientation, so a section of the orientation bundle picks up a factor of $-1$.

The *twisted Laplacian* is the Laplace-Beltrami operator acting on sections of $\mathcal{L}$. It is the standard Laplace-Beltrami operator on the smooth locus; the adjective "twisted" refers to the domain (anti-equivariant sections) rather than to a modification of the operator itself. The eigenvalue problem $-\Delta\psi = \lambda\psi$ is posed for sections of $\mathcal{L}$ throughout this paper.

### 3.2 The formal operator

On the smooth locus $M^\circ = M \setminus \{p_c\}$ (where $p_c$ denotes the cone point at $y = \pi R/2$), the Laplace-Beltrami operator associated to the metric $ds^2 = dy^2 + f(y)^2\,dw^2$ with $f(y) = \cos(y/R)$ is

$$\Delta\psi = \psi_{yy} + \frac{f'}{f}\psi_y + \frac{1}{f^2}\psi_{ww} = \psi_{yy} - \frac{1}{R}\tan\!\Bigl(\frac{y}{R}\Bigr)\psi_y + \frac{1}{\cos^2(y/R)}\psi_{ww}.$$

The area element is $dA = \lvert f(y)\rvert\,dy\,dw$, and $L^2(M, dA)$ denotes the Hilbert space of square-integrable sections of $\mathcal{L}$ with respect to this measure. Although the formal operator is written using $f$ on each smooth coordinate patch, the global measure and the reduced Sturm-Liouville forms use $\lvert f\rvert$, which is nonnegative across the two sides of the collapsed fiber.

The boundary $\partial M$ consists of two geodesic arcs at $w = \pm W$. We impose Neumann boundary conditions: $\partial_w\psi\big\vert_{w = \pm W} = 0$.

### 3.3 The collapsed fiber and the cone point

The cone point $p_c$ arises from the metric degeneration alone: at $y = \pi R/2$ the coefficient $f = \cos(y/R)$ vanishes, so the whole transverse fiber $\{y = \pi R/2\} \times [-W, W]$ collapses to the single point $p_c$ of the metric completion, independently of the edge identification. The reflection $\delta \mapsto -\delta$ about this fiber ($\delta = y - \pi R/2$), that is $y \mapsto \pi R - y$, is realized by the covering isometry $\tau(y, w) = (\pi R - y, -w)$; its fixed point $(\pi R/2, 0)$ is one point of the collapsed fiber, not $p_c$ itself. Thus $\tau$ enters the construction in two distinct ways: its restriction to the edge $\{y = 0\}$ is the gluing map of §2, and the reflection $\delta \mapsto -\delta$ commutes with the reduced operator and organizes the parity decomposition of §4.

At $p_c$, $f(\pi R/2) = \cos(\pi/2) = 0$. Setting $\delta = y - \pi R/2$:

$$f(y) = \cos(y/R) = -\sin(\delta/R) \quad \Longrightarrow \quad \lvert f\rvert \sim \frac{\lvert\delta\rvert}{R} \quad \text{as } \delta \to 0.$$

The transverse fiber $[-W, W]$ has metric length $2W\lvert f(y)\rvert$, which collapses to zero. On the covering $S^2$, the coordinate $y = \pi R/2$ is a smooth pole; on the edge-identified Möbius band, the same collapse produces a conical singularity with cone angle $2W/R$.

The surface is smooth away from $p_c$, with constant Gaussian curvature $K = 1/R^2$ and smooth-locus scalar curvature $R_{\mathrm{sm}} = 2K = 2/R^2$. Distributional curvature at $p_c$ is not invoked in this paper.

### 3.4 Transverse decomposition and cone asymptotics

Separation of variables $\psi(y,w) = u(y)\,\Phi(w)$ with $-\Phi'' = \mu\,\Phi$ subject to Neumann conditions $\Phi'(\pm W) = 0$ yields two families of transverse eigenmodes on $[-W, W]$.

*Even family* (symmetric under $w \mapsto -w$):

$$\Phi_k^{\mathrm{e}}(w) = \cos(k\pi w/W), \qquad \mu_k^{\mathrm{e}} = (k\pi/W)^2, \qquad k = 0, 1, 2, \ldots$$

The case $k = 0$ is the constant mode $\Phi_0^{\mathrm{e}} \equiv 1$ with $\mu_0 = 0$.

*Odd family* (antisymmetric under $w \mapsto -w$):

$$\Phi_j^{\mathrm{o}}(w) = \sin\bigl((2j+1)\pi w/(2W)\bigr), \qquad \mu_j^{\mathrm{o}} = \bigl((2j+1)\pi/(2W)\bigr)^2, \qquad j = 0, 1, 2, \ldots$$

The Möbius identification $\psi(\pi R, -w) = -\psi(0, w)$ interacts with the transverse parity as follows. For even $\Phi(w) = \Phi(-w)$, the identification forces $u(\pi R) = -u(0)$: the longitudinal function is anti-periodic. For odd $\Phi(-w) = -\Phi(w)$, it forces $u(\pi R) = u(0)$: the longitudinal function is periodic.

A Neumann eigenmode on $[-W, W]$ extends by even reflection to a periodic function on a circle of angular circumference $4W/R$ in the variable $\theta = w/R$. Under this unfolding, the even family $\Phi_k^{\mathrm{e}}$ corresponds to Fourier modes $e^{i(2k)\theta}$ (even harmonics) and the odd family $\Phi_j^{\mathrm{o}}$ to $e^{i(2j+1)\theta}$ (odd harmonics) on that circle. The $k = 0$ constant mode is therefore the analogue of the $k = 0$ Fourier sector in [BP], and the non-essential-self-adjointness of the constant-sector reduced operator at the cone (Theorem 1.6(ii) of [BP]) is the same phenomenon in both settings.

> **Lemma 3.1** (Neumann unfolding)**.** After the change of angular variable $\theta=w/R$, even reflection at the Neumann endpoints identifies each transverse Neumann eigensector on $[-W,W]$ with a Fourier eigensector on the circle link of angular circumference $4W/R$ (unitarily, up to the harmless normalization factor coming from reflection). For each transverse sector, the reduced one-dimensional operator in $y$ has the same singular endpoint at $\delta = 0$, the same weight $\lvert\delta\rvert/R$, and the same indicial equation. Since the maximal domain, Lagrange bracket, and deficiency indices depend only on the local behavior at the singular endpoint [Weidmann], the same local boundary data appear as in the Boscain-Prandi cone model [BP]; we use [BP] for this precedent and define the Friedrichs and bridging realizations directly by these cone traces in §3.5 (Definition 3.4) rather than importing a classification.

In each sector, the reduced eigenequation for the longitudinal function $u(y)$ takes the Sturm-Liouville form

$$-\bigl(\lvert f\rvert\,u'\bigr)' + \frac{\mu}{\lvert f\rvert}\,u = \lambda\,\lvert f\rvert\,u, \qquad f(y) = \cos(y/R),$$

on $L^2\bigl((0, \pi R),\,\lvert f\rvert\,dy\bigr)$, where $\mu$ is the transverse eigenvalue of the sector. Near the cone ($\delta \to 0$, $\lvert f\rvert \sim \lvert\delta\rvert/R$), this becomes

$$-\Bigl(\frac{\lvert\delta\rvert}{R}\,u'\Bigr)' + \frac{\mu R}{\lvert\delta\rvert}\,u = \lambda\,\frac{\lvert\delta\rvert}{R}\,u.$$

Substituting $u = \lvert\delta\rvert^s$ into the leading-order balance gives the indicial equation $s^2 = \mu R^2$.

*The constant sector* ($\mu = 0$, even family $k = 0$). The indicial equation gives $s^2 = 0$ (double root). The two local solutions are

$$u_{\mathrm{reg}} = a_0 + a_2\delta^2 + O(\delta^4), \qquad u_{\mathrm{log}} = \log\lvert\delta\rvert + b_2\delta^2 + O(\delta^4).$$

Both are square-integrable against the weight $\lvert\delta\rvert/R\,d\delta$: $\int \lvert\delta\rvert^0 \cdot \lvert\delta\rvert\,d\delta < \infty$ and $\int (\log\lvert\delta\rvert)^2 \cdot \lvert\delta\rvert\,d\delta < \infty$. The cone is a limit-circle endpoint, and a self-adjoint extension must be chosen.

*Nonconstant sectors with $\alpha \ge 1$.* Write $\alpha = \sqrt{\mu}\,R$ for the indicial exponent. When $\alpha \ge 1$, the singular branch $\lvert\delta\rvert^{-\alpha}$ fails the $L^2$ condition against the weight:

$$\int u^2\,\lvert f\rvert\,d\delta \sim \int \lvert\delta\rvert^{-2\alpha} \cdot \lvert\delta\rvert\,d\delta = \int \lvert\delta\rvert^{1-2\alpha}\,d\delta = \infty \qquad \text{for } \alpha \ge 1.$$

The cone is limit-point. Self-adjointness is unique; no extension choice arises.

*Nonconstant sectors with $0 < \alpha < 1$.* This regime occurs only for wide bands: $W > \pi R/2$ for the $j = 0$ odd mode. Both branches $\lvert\delta\rvert^{\pm\alpha}$ are now $L^2$ against the weight (since $1 - 2\alpha > -1$). The cone is limit-circle. The branches are distinguished by the Dirichlet energy. For the singular branch $u = \lvert\delta\rvert^{-\alpha}$,

$$\int (u')^2\,\lvert f\rvert\,d\delta \sim \alpha^2\!\int \lvert\delta\rvert^{-2\alpha-1}\,d\delta = \infty \qquad \text{for all } \alpha > 0,$$

so the singular branch has infinite Dirichlet energy. The Friedrichs extension selects the regular branch $\lvert\delta\rvert^{+\alpha}$, the unique branch of finite Dirichlet energy, and every realization of finite Dirichlet energy in this sector coincides with it there.

The limit-point/limit-circle classification at a singular endpoint depends only on the local behavior of the coefficients [Weidmann, KSWW]. Near $p_c$, the weight $\lvert f\rvert$ vanishes linearly in $\delta$, matching the flat-cone case $\alpha_{\mathrm{BP}} = -1$ in the notation of [BP]. On the model cone of [BP] (angular period $2\pi$) only $k = 0$ has $\alpha < 1$; the unfolded period $4W/R$ adds the wide-band first odd sector, with exponent $\alpha_0 = \pi R/(2W)$, to the limit-circle list. The extension structure this produces is recorded in Lemma 3.3 below.

> **Lemma 3.2** (Vanishing of nonconstant modes at the cone)**.** Let $\psi(y,w) = u(y)\,\Phi(w)$ be a section of $\mathcal{L}$ that is continuous on $M(W)$, where $\Phi$ is any nonconstant Neumann transverse eigenmode. Then $u(\pi R/2) = 0$.

*Proof.* At the cone point $p_c$, the metric coefficient $f(y) = \cos(y/R)$ vanishes, collapsing the entire transverse fiber to a single geometric point. A continuous section must take a single well-defined value at $p_c$. Since $\Phi$ is nonconstant, a product $u(\pi R/2) \cdot \Phi(w)$ with $u(\pi R/2) \ne 0$ would assign multiple values to $p_c$, contradicting continuity. $\square$

For the constant mode $\Phi_0^{\mathrm{e}} \equiv 1$, the product $u(\pi R/2) \cdot 1$ assigns a single value to $p_c$ regardless of $w$. The constant sector is the only sector where a nonzero apex value is compatible with continuity. This explains geometrically why, once the regular branch is fixed in every nonconstant sector (Definition 3.4), the residual extension freedom lives in the constant sector. Rigorously this rests on the limit-point/limit-circle classification together with that sector-regular convention; continuity at $p_c$ is not the operative criterion, since it fails for the actual ground states (the discontinuous $\phi_0$ and the logarithmically divergent bridging mode).

> **Lemma 3.3** (Wide-band odd-sector endpoint)**.** For $0 < W \le \pi R/2$ every nonconstant transverse sector is limit-point at $p_c$ and the minimal operator has deficiency indices $(2,2)$. For $\pi R/2 < W < \pi R$ the first odd sector, with indicial exponent $\alpha_0 = \pi R/(2W) < 1$, is in addition limit-circle, and the indices are $(4,4)$. Under the Liouville substitution $v = \lvert f\rvert^{1/2}u$ the reduced operator of that sector is $-v'' + g\,\delta^{-2}v + O(1)$ near the cone, with inverse-square coupling $g = \alpha_0^2 - \tfrac14 \in (-\tfrac14, \tfrac34)$. Every sectorwise self-adjoint realization of this inverse-square endpoint is bounded below.

*Proof.* The classification follows from $\lvert f\rvert \sim \lvert\delta\rvert/R$ and the indicial equation $s^2 = \mu R^2$, whose roots are $s = \pm\alpha_0$: for $\alpha_0 \ge 1$ the singular root leaves $L^2$ (limit-point), for $0 < \alpha_0 < 1$ both roots are square-integrable (limit-circle), and at $W = \pi R/2$ exactly $\alpha_0 = 1$, so the count stays $(2,2)$. The substitution $v = \lvert f\rvert^{1/2}u$ sends $-(\lvert f\rvert\,u')' + (\mu/\lvert f\rvert)u$ to $-v'' + g\,\delta^{-2}v + O(1)$ with $g = s^2 - \tfrac14 = \alpha_0^2 - \tfrac14$. For $g > -\tfrac14$ Hardy's inequality makes the local form nonnegative, and on the finite interval with one regular (seam) endpoint the deficiency is finite, so each self-adjoint realization differs from the Friedrichs one by at most finitely many eigenvalues and is bounded below [KSWW, RS]. $\square$

Neither finite Dirichlet energy nor semiboundedness alone singles out a realization in the wide band: the constant-sector logarithmic mode of §4.4 has infinite Dirichlet energy, and by Lemma 3.3 the singular-branch odd extensions are semibounded as well. We therefore work only with realizations that select the regular (Frobenius) branch in every nonconstant sector, the Friedrichs choice there, and we do not treat realizations that couple distinct transverse sectors. The two such sector-regular realizations are defined in §3.5 (Definition 3.4).

### 3.5 The cone boundary form and the self-adjoint extensions

Once the regular Frobenius branch is fixed in every nonconstant sector (§3.4), the only remaining extension choice that distinguishes Friedrichs from bridging lies in the constant sector ($\mu = 0$), where both local solutions are $L^2$. Near the cone, the general constant-sector solution has the asymptotic form

$$u(\delta) = u_N\,\ln\frac{\lvert\delta\rvert}{2R} + u_D + o(1) \qquad (\delta \to 0),$$

with a log coefficient $u_N$ (the flux datum) and a regularized value $u_D$ (referenced to the length $2R$), independently on each side of the cone. We write $u_D^\pm$ and $u_N^\pm$ for the limits from $\delta \to 0^\pm$. The cone boundary form produced by Green's identity is

$$[u, v]_{p_c} = \frac{1}{R}\sum_{\pm}\bigl(u_D^\pm\,v_N^\pm - u_N^\pm\,v_D^\pm\bigr),$$

where the logarithmic divergences cancel pairwise: a direct computation from the near-cone reduced form gives $\lvert f\rvert(u v' - u' v) \to (\mathrm{sgn}\,\delta/R)(u_D v_N - u_N v_D)$ as $\delta \to 0$, and the two-sided Green identity sums these limits with the outward-normal orientation, yielding the boundary form above. A self-adjoint extension corresponds to a two-dimensional Lagrangian plane (a subspace on which this boundary form vanishes identically) in the four-dimensional boundary space $(u_D^+, u_N^+, u_D^-, u_N^-)$. The extension data here are the cone traces alone; the regular arcs $w = \pm W$ carry their fixed Neumann condition and enter no extension choice.

*The Friedrichs (disjoint) extension.* The Friedrichs extension [Friedrichs] is characterized by Theorem 1.8 of [BP] (applied at $\alpha_{\mathrm{BP}} = -1$): its domain requires

$$u_N^+ = 0 \qquad\text{and}\qquad u_N^- = 0,$$

with no condition relating $u_D^+$ to $u_D^-$. This is two conditions on four parameters, and the plane $\{u_N^+ = u_N^- = 0\}$ is Lagrangian: the boundary form vanishes when both fluxes are zero. The domain imposes no matching condition at $p_c$, so the two cone traces $u_D^\pm$ are unconstrained and the constant-sector form $q_0$ decomposes as $q_0^+ \oplus q_0^-$ on the two halves $M^\pm = \{\pm(y - \pi R/2) > 0\}$ (coupled only through the seam identification, not through $p_c$). This is the "disjoint dynamics" case $c^+ = c^- = 0$ of [BP].

*The bridging extension at renormalization length $\delta_0$.* Boscain and Prandi (Theorem 1.8 of [BP]) classify the conic extensions by a matrix $U \in \mathrm{SL}_2(\mathbb{R})$, and their Remark 1.9 names the $U = \mathrm{Id}$ case the bridging extension. Equipping it with a renormalization length $\delta_0 > 0$ is the standard two-dimensional point-interaction renormalization [AGHH, KayStuder], realized inside the conic framework: re-express the data relative to $\delta_0$,

$$u(\delta) = u_N\,\ln\frac{\lvert\delta\rvert}{\delta_0} + \tilde u_D + o(1), \qquad \tilde u_D = u_D + u_N\,\ln\frac{\delta_0}{2R},$$

and imposes

$$\tilde u_D^+ = \tilde u_D^- \qquad \text{(continuity of the regularized value),}$$

$$u_N^+ + u_N^- = 0 \qquad \text{(Kirchhoff flux matching).}$$

This is two conditions on four parameters. The plane is Lagrangian: since $u_D^\pm = \tilde u_D^\pm - u_N^\pm\ln(\delta_0/2R)$, the $\ln(\delta_0/2R)$ terms cancel pairwise in the boundary form, and for $u, v$ both satisfying the bridging conditions,

$$[u, v]_{p_c} = \frac{1}{R}\Bigl[\tilde u_D\bigl(v_N^+ + v_N^-\bigr) - \tilde v_D\bigl(u_N^+ + u_N^-\bigr)\Bigr] = 0.$$

The value condition is continuity across the cone; the flux condition is the sign-flipped (Kirchhoff) matching dictated by the opposite outward normals on the two sides. Different choices of $\delta_0$ yield distinct self-adjoint extensions with distinct spectra; the renormalization length is a genuine parameter, set neither by the metric nor by the bundle alone.

> **Definition 3.4** (Sector-regular realizations)**.** A self-adjoint realization of the twisted Laplacian is *sector-regular* if at $p_c$ it selects the regular (Frobenius) branch in every nonconstant transverse sector. We use two. The *Friedrichs extension* $\Delta_F$ takes the regular branch in the constant sector as well. For each $\delta_0 > 0$ the *bridging realization* $A^{\mathrm{br}}_{\delta_0}$ takes in the constant sector the logarithmic matching $\tilde u_D^+ = \tilde u_D^-$, $u_N^+ + u_N^- = 0$ at renormalization length $\delta_0$ (the condition above), and the regular branch in every nonconstant sector. These realizations are self-adjoint; $\Delta_F$ is nonnegative (§3.6), and §4.4 shows that $A^{\mathrm{br}}_{\delta_0}$ is semibounded with bottom $\lambda_b(\delta_0) < 0$. In the wide band these are the two sector-regular members of the $(4,4)$-family of Lemma 3.3; the rest activate the singular odd branch.

For any constant $c \ne 0$, the discontinuous piecewise-constant section

$$\phi_0(y, w) = \begin{cases} +c & \text{if } y < \pi R/2, \\ -c & \text{if } y > \pi R/2, \end{cases}$$

has $u_N^\pm = 0$ and $\tilde u_D^+ = -c \ne +c = \tilde u_D^-$, so it lies in the Friedrichs domain (it satisfies the Friedrichs flux conditions) but is excluded from every bridging domain (it fails value-continuity). Since $-\Delta\phi_0 = 0$ on the smooth locus and $\phi_0$ satisfies the equivariance condition, it is a genuine eigenfunction with eigenvalue $0$ for the Friedrichs extension. The constant sector is the only sector in which it lives, by Lemma 3.2.

The covering geometry constrains, but does not by itself fix, the extension. A section of $\mathcal{L}$ that lifts to a function smooth at the pole of the covering $S^2$ is regular there ($u_N = 0$) and even in $\delta$; this forces the regular branch in the symmetric subsector (§4.2) but does not determine the cone condition in the antisymmetric subsector, where the natural candidates are the Friedrichs and bridging conditions above. The remaining choice is the antisymmetric cone condition, which is what separates Friedrichs from bridging in §5.

> **Proposition 3.5** (Operator realization)**.** Because $\cos^2(y/R)$ depends on $y$ alone, the formal twisted Laplacian commutes with the transverse Neumann Laplacian. The Friedrichs extension and the sector-regular bridging realization $A^{\mathrm{br}}_{\delta_0}$ impose cone conditions sector by sector, so the transverse Neumann decomposition $L^2(M, dA) = \bigoplus_\sigma \mathcal{H}_\sigma$ reduces both operators. In each sector the reduced Sturm-Liouville operator in $y$, with the seam condition from anti-equivariance and the cone condition of Definition 3.4, is self-adjoint with compact resolvent. The sector bottoms diverge, so each direct sum is self-adjoint with compact resolvent and discrete spectrum. Thus $\Delta_F$ and $A^{\mathrm{br}}_{\delta_0}$ are these orthogonal direct sums.

*Proof.* Commutation gives the reducing decomposition. Each reduced operator is regular-singular on a finite interval with integrable weight $\lvert f\rvert$; by §3.4 the cone is limit-point in every sector except the constant one and, for $W > \pi R/2$, the first odd one (Lemma 3.3), where Definition 3.4 imposes a self-adjoint cone condition. So each sector operator is self-adjoint with compact resolvent [Weidmann], and since the sector bottoms tend to infinity the orthogonal direct sum has compact resolvent. $\square$

### 3.6 Friedrichs maximality

The constant-sector quadratic form

$$q[\psi] = \int_{M^\circ}\lvert\nabla\psi\rvert^2\,dA, \qquad M^\circ = M(W)\setminus\{p_c\},$$

is nonnegative on the core $\mathcal{C}$ of smooth anti-equivariant sections on the closed smooth locus $\overline{M^\circ}$ that are smooth up to the boundary arcs $w = \pm W$, with no condition imposed there, and whose support is compact in $\overline{M^\circ}\setminus\{p_c\}$ (excised only at the cone $p_c$). No condition is placed on $\mathcal{C}$ at $w = \pm W$: the Neumann condition $\partial_w\psi\big\vert_{w = \pm W} = 0$ is the natural (form) boundary condition there, recovered from $q$ on closure rather than imposed on the core. We do not read $C_c^\infty(M^\circ)$ as sections of support compact in the open manifold, whose energy-norm closure is $H^1_0$ off the arcs and would force Dirichlet data at $w = \pm W$, removing the constant transverse mode and with it $\phi_0$, the bound state $\lambda_b$, and the $2/R^2$ branch. The Friedrichs extension $\Delta_F$ is the self-adjoint operator associated with the closure of $q$ on $\mathcal{C}$; here "Friedrichs" designates the extension at the singular cone $p_c$, the only locus of extension ambiguity (§3.5), while the regular arcs $w = \pm W$ keep their fixed Neumann condition throughout. Its form domain $\mathcal{D}(q_F) = \overline{\mathcal{C}}^{\,\lVert\cdot\rVert_q}$ is contained in the form domain of every other self-adjoint extension at the cone that is bounded below by the lower bound of $q$.

> **Lemma 3.6** (Friedrichs maximality)**.** Let $A$ be any self-adjoint extension of the minimal twisted Laplacian on $M(W)$.
>
> **(i)** The minimal operator is nonnegative, and $\Delta_F$ is its largest nonnegative extension in the Birman-Krein-Vishik order [AlonsoSimon]: $\mathcal{D}(q_F) \subseteq \mathcal{D}(q_A)$ for every nonnegative extension $A$, so by min-max $\lambda_n(A) \le \lambda_n(\Delta_F)$ for all $n$, and in particular $\inf\sigma(A) \le \inf\sigma(\Delta_F)$.
>
> **(ii)** $\inf\sigma(\Delta_F) = 0$: the form $q \ge 0$ gives $\inf\sigma(\Delta_F) \ge 0$, and $\phi_0 \in \mathcal{D}(\Delta_F)$ with $\Delta_F\phi_0 = 0$ (Lemma 4.1) gives $\inf\sigma(\Delta_F) \le 0$.
>
> **(iii)** Consequently $\inf\sigma(A) \le 0$ for every self-adjoint extension $A$: for nonnegative $A$ by (i)–(ii), and for non-nonnegative $A$ by definition. The argument uses only nonnegativity of the minimal operator, with no parity hypothesis.

*Proof.* (i) is the Birman-Krein-Vishik characterization of the Friedrichs extension as the largest nonnegative self-adjoint extension of a nonnegative symmetric operator [AlonsoSimon]: its form domain $\mathcal{D}(q_F) = \overline{\mathcal{C}}$ is contained in $\mathcal{D}(q_A)$ for every nonnegative extension $A$, and a smaller form domain yields larger Rayleigh quotients, so $\lambda_n(A) \le \lambda_n(\Delta_F)$ by min-max. (ii) The cutoff estimate of Lemma 4.1 below shows $\phi_0 \in \mathcal{D}(\Delta_F)$ with $\Delta_F\phi_0 = 0$, so $\inf\sigma(\Delta_F) \le 0$; and $q \ge 0$ gives $\inf\sigma(\Delta_F) \ge 0$. (iii) Immediate. $\square$

Lemma 3.6 proves the part of Theorem 1.1 that needs no separation of variables: every realization has bottom at most $0$.

---

## 4. The Constant Sector by Parity

The constant transverse mode ($k = 0$ even family, $\Phi_0^{\mathrm{e}} \equiv 1$) reduces the eigenvalue problem to a single ODE in $y$ with anti-periodic boundary conditions. This is the zonal sector, where Friedrichs and bridging diverge. We analyze it by parity about the cone.

### 4.1 The reduced operator and parity reduction

On the constant-curvature band, the zonal eigenequation from §3.4 with $\mu = 0$ is

$$-\Delta u = -u'' + \frac{1}{R}\tan\!\Bigl(\frac{y}{R}\Bigr)u' = \lambda\,u \qquad \text{on } (0, \pi R),$$

with anti-periodic boundary conditions $u(\pi R) = -u(0)$ and $u'(\pi R) = -u'(0)$, and a cone condition at $y = \pi R/2$ from §3.5. Decompose the constant-sector functions into modes symmetric and antisymmetric under reflection about the cone $\delta \mapsto -\delta$. Anti-periodicity interacts with this parity as follows.

*Symmetric modes* satisfy $u(\pi R) = u(0)$ automatically, so the anti-periodic value condition forces $u(0) = 0$ (Dirichlet at the seam), while the derivative condition $u'(\pi R) = -u'(0)$ is then free. The symmetric sector is the half-interval problem on $(0, \pi R/2)$ with Dirichlet at the seam and a cone condition.

*Antisymmetric modes* satisfy $u(\pi R) = -u(0)$ automatically, so the value condition is free and the derivative condition forces $u'(0) = 0$ (Neumann at the seam). The antisymmetric sector is the half-interval problem on $(0, \pi R/2)$ with Neumann at the seam and a cone condition.

On the bridging side, a symmetric mode has equal log coefficients on the two sides, so the Kirchhoff flux condition forces the log coefficient to vanish, and the symmetric mode lies in the Friedrichs domain. An antisymmetric mode has $\tilde u_D^+ = -\tilde u_D^-$, so the value-continuity condition forces $\tilde u_D = 0$, and the log datum is active. The two subsectors decouple: the symmetric subsector gives the same spectrum for the Friedrichs and bridging extensions and is treated in §4.2; the antisymmetric subsector is where these extensions differ and is treated in §§4.3–4.4.

### 4.2 Legendre reduction and the symmetric tower

The substitution $x = \sin(y/R)$ maps $(0, \pi R/2)$ bijectively to $(0, 1)$ and converts the zonal operator to the Legendre equation. With $u(y) = v(\sin(y/R))$,

<div align="center">

$\displaystyle \frac{d}{dx}\Bigl[(1-x^2)\frac{dv}{dx}\Bigr] + \nu(\nu+1)v = 0, \qquad \lambda = \frac{\nu(\nu+1)}{R^2}$

</div>

where $\nu \ge 0$ is a continuous spectral parameter. The Legendre function of the first kind $P_\nu(x)$ is regular at $x = 1$ (the cone); the Legendre function of the second kind $Q_\nu(x)$ diverges logarithmically and supplies the log datum $u_N$. The substitution $x = \sin(y/R)$ is two-to-one ($y$ and $\pi R - y$ map to the same $x$) and produces exactly the modes symmetric about the cone.

In the symmetric subsector both the Friedrichs and bridging conditions force the regular branch (the log coefficient vanishes, by §4.1), so the admissible symmetric solutions are $P_\nu(\sin(y/R))$. The Dirichlet seam condition $u(0) = 0$ is $P_\nu(0) = 0$. Since

<div align="center">

$\displaystyle P_\nu(0) = \frac{\sqrt{\pi}}{\Gamma((1-\nu)/2)\Gamma(1+\nu/2)}$

</div>

this holds exactly when $(1-\nu)/2$ is a non-positive integer, i.e. $\nu = 1, 3, 5, \ldots$ The symmetric zonal tower is therefore

<div align="center">

$\displaystyle \sigma_{\mathrm{sym}} = \Bigl\lbrace\frac{\ell(\ell+1)}{R^2} : \ell = 1, 3, 5, \ldots\Bigr\rbrace = \Bigl\lbrace\frac{2}{R^2}, \frac{12}{R^2}, \frac{30}{R^2}, \ldots\Bigr\rbrace$

</div>

the same for the Friedrichs and bridging extensions. The lowest member is $\ell = 1$, with eigenfunction $P_1(\sin(y/R)) = \sin(y/R)$, the restriction of the zonal harmonic $Y_1^0 \propto \sin(y/R)$. It is strictly positive on $(0, \pi R)$, lies in the regular Frobenius branch at the cone, and gives

<div align="center">

$\displaystyle \frac{\ell(\ell+1)}{R^2}\Big\rvert_{\ell=1} = \frac{2}{R^2} = R_{\mathrm{sm}}$

</div>

independent of the half-width $W$.

On the flat strip (Euclidean metric, anti-periodic condition, same period $\pi R$), the lowest eigenvalue is $1/R^2 = R_{\mathrm{sm}}/2$, with the same eigenfunction $\sin(y/R)$. The curvature term $(1/R)\tan(y/R)u'$ doubles this to $2/R^2 = R_{\mathrm{sm}}$, matching the familiar $\ell = 1$ eigenvalue on $S^2(R)$.

### 4.3 The Friedrichs antisymmetric tower and the kernel

Under the Friedrichs extension, the antisymmetric subsector (Neumann seam, regular cone) admits $\mathrm{sgn}(\delta)P_\nu(\sin(y/R))$ with the regular branch at the cone, and the Neumann seam condition is $P_\nu'(0) = 0$, i.e. $\nu = 0, 2, 4, \ldots$ The Friedrichs antisymmetric tower is

<div align="center">

$\displaystyle \sigma_{\mathrm{anti}}^{\mathrm{Fr}} = \Bigl\lbrace\frac{\ell(\ell+1)}{R^2} : \ell = 0, 2, 4, \ldots\Bigr\rbrace = \Bigl\lbrace0, \frac{6}{R^2}, \frac{20}{R^2}, \ldots\Bigr\rbrace$

</div>

The $\ell = 0$ member is the zero mode $\phi_0$.

> **Lemma 4.1** (Friedrichs kernel in the constant sector)**.** In the constant transverse sector, the Friedrichs form decomposes as the direct sum of the two half-band forms on $M^+$ and $M^-$. Consequently $\phi_0$ belongs to $\mathcal{D}(\Delta_F)$ and satisfies $\Delta_F\phi_0 = 0$, and the zero eigenspace in the constant sector is one-dimensional, spanned by $\phi_0$.

*Proof.* Let $\chi_\varepsilon(\delta)$ be smooth, equal to $0$ for $\lvert\delta\rvert \le \varepsilon$, equal to $1$ for $\lvert\delta\rvert \ge \sqrt{\varepsilon}$, and satisfying $\lvert\chi_\varepsilon'(\delta)\rvert \le C/(\lvert\delta\rvert\lvert\log\varepsilon\rvert)$ for $\varepsilon < \lvert\delta\rvert < \sqrt{\varepsilon}$. Since $\lvert f(y)\rvert \sim \lvert\delta\rvert/R$ at the cone, the cutoff energy (the transverse integration contributing only the constant factor $2W$) obeys

<div align="center">

$\displaystyle \int_{\varepsilon < \lvert\delta\rvert < \sqrt{\varepsilon}} \lvert\chi_\varepsilon'(\delta)\rvert^2 \lvert f(y)\rvert d\delta \le \frac{C}{\lvert\log\varepsilon\rvert^2}\int_\varepsilon^{\sqrt\varepsilon}\frac{d\delta}{\delta} = O(\lvert\log\varepsilon\rvert^{-1}) \to 0.$

</div>

Thus the jump of $\phi_0$ across the collapsed point is invisible to the Friedrichs form closure: $\chi_\varepsilon\phi_0 \to \phi_0$ in the form norm, so $\phi_0 \in \mathcal{D}(q_F)$ and $q_F(\phi_0, \eta) = 0$ for every form-domain test section $\eta$, whence $\phi_0 \in \mathcal{D}(\Delta_F)$ and $\Delta_F\phi_0 = 0$. By contrast the logarithmic branch has $u'(\delta) \sim 1/\delta$, hence $\int \lvert u'\rvert^2\lvert f\rvert d\delta \sim \int d\delta/\lvert\delta\rvert = \infty$, and is excluded from the Friedrichs domain. Conversely, if $q_F[\psi] = 0$ in the constant sector then $\nabla\psi = 0$ a.e. on each connected half, so $\psi$ is constant on each of $M^\pm$; the anti-periodic seam condition forces the two constants to be opposite, giving a scalar multiple of $\phi_0$. $\square$

> **Proposition 4.2** (Lune equivalence)**.** For the Friedrichs extension, multiplication by the trivializing section, $U\psi = \phi_0\cdot\psi$ with $\phi_0$ the unit-modulus zero mode ($c = 1$), is a unitary operator from $L^2(M(W), \mathcal{L})$ onto $L^2$ of the spherical lune of opening angle $2W/R$, and it restricts to a unitary from the Friedrichs form domain $\mathcal{D}(q_F)$ onto the Neumann form domain $H^1$ of the lune. Consequently the Friedrichs twisted Laplacian $\Delta_F$ is unitarily equivalent to the Neumann Laplacian of the lune, with $\phi_0$ carried to the constant function. The equivalence is specific to the Friedrichs extension: no bridging extension is unitarily equivalent to the lune Neumann Laplacian under $U$.

*Proof.* *Trivialization and $L^2$ unitarity.* Over the smooth locus $M^\circ$ the bundle $\mathcal{L}$ is trivial, and $\phi_0$ (with $c = 1$) is the trivializing section. Set $\tilde\psi = \psi$ on $\lbrace y < \pi R/2\rbrace$ and $\tilde\psi = -\psi$ on $\lbrace y > \pi R/2\rbrace$; in coordinates $t = y$ on the first half and $t = y - \pi R$ on the second (with $w' = w$ and $w' = -w$ respectively), the anti-equivariance condition becomes plain continuity of $\tilde\psi$ across $t = 0$, and the metric becomes $dt^2 + \cos^2(t/R)\,dw'^2$ on the lune of opening $2W/R$ ($t \in (-\pi R/2, \pi R/2)$, $w' \in [-W, W]$). The anti-periodic seam maps to interior continuity and the Neumann edges $w = \pm W$ to the two geodesic Neumann sides of the lune, both away from the poles. Since $\lvert\phi_0\rvert = 1$ a.e., $\lVert U\psi\rVert_{L^2} = \lVert\psi\rVert_{L^2}$, and $U$ is unitary onto $L^2$ of the lune.

*Energy isometry on the smooth locus.* On $M^\circ$, $\nabla\phi_0 = 0$ and $\lvert\phi_0\rvert = 1$, so $\lvert\nabla(\phi_0\psi)\rvert = \lvert\nabla\psi\rvert$ pointwise. Hence $U$ maps the core $\mathcal{C}$ onto the corresponding core on the lune (smooth functions, free at the Neumann sides, supported away from the poles), preserving both $\lVert\cdot\rVert_{L^2}$ and the energy $q$; it is a $\lVert\cdot\rVert_q$-isometry of these test spaces.

*Form-domain identification via zero capacity.* By definition $\mathcal{D}(q_F) = \overline{\mathcal{C}}^{\,\lVert\cdot\rVert_q}$. Each pole is a single point and has zero $2$-capacity: the same logarithmic cutoff $\chi_\varepsilon$ as Lemma 4.1, whose energy is $O(\lvert\log\varepsilon\rvert^{-1}) \to 0$, shows that the smooth functions on the lune supported away from the poles are $H^1$-dense in $H^1$ of the lune. Taking $\lVert\cdot\rVert_q$-closures, $U$ is unitary from $\mathcal{D}(q_F)$ onto $H^1$ of the lune. Thus $U$ intertwines the closed forms and the associated self-adjoint operators, and $\phi_0$ maps to the constant.

*Friedrichs-specificity.* The mode $\phi_0$ is discontinuous at the cone, so it satisfies the Friedrichs flux conditions but fails the bridging value-continuity $\tilde u_D^+ = \tilde u_D^-$; and every bridging form domain contains the logarithmic mode $u' \sim 1/\delta$, whose raw Dirichlet energy $\int (u')^2\lvert f\rvert\,d\delta \sim \int d\delta/\lvert\delta\rvert$ diverges, so its image is not in $H^1$ of the lune. Hence $U$ is not unitary onto the lune Neumann form domain for any bridging extension. $\square$

The trivialization and the zero-capacity estimate are sector-independent, so the equivalence is for the full Friedrichs operator, with the sector towers organized by longitude order. The Friedrichs spectrum is therefore the lune Neumann spectrum, obtained by separation of variables: longitude Neumann modes of order $m_n = n\pi R/(2W)$ combined with colatitude Legendre functions regular at both poles give eigenvalues $(m_n + \ell')(m_n + \ell' + 1)/R^2$ for $n, \ell' \ge 0$. In particular, for the Friedrichs realization the first positive eigenvalue of Theorem 1.2 is the first nonzero Neumann eigenvalue of this lune: the $(n,\ell') = (0,1)$ and $(1,0)$ modes give $2/R^2$ and $\alpha_0(\alpha_0+1)/R^2$, crossing doubly at $W = \pi R/2$. The width transition is thus the crossing of the two lowest lune branches.

### 4.4 The deformed antisymmetric branch

The bridging extension deforms the Friedrichs antisymmetric tower. By §4.1, the antisymmetric subsector under bridging is the half-interval problem on $(0, \pi R/2)$ with Neumann at the seam and the regularized condition $\tilde u_D = 0$ at the cone. Let $u_\lambda$ denote the solution of the zonal equation on $(0,\pi R/2)$ normalized by $u_\lambda'(0) = 0$, $u_\lambda(0) = 1$. Near the cone it has the expansion

$$u_\lambda(\delta) = \mathcal{N}(\lambda)\,\ln\frac{\lvert\delta\rvert}{2R} + \mathcal{D}(\lambda) + o(1),$$

with $\mathcal{N}(\lambda)$ the log coefficient and $\mathcal{D}(\lambda)$ the regularized value, both real-analytic.

The reference length $2R$ is not a free normalization: it is fixed by the near-cone behavior of the Legendre function of the second kind. As $x \to 1^-$,

$$Q_\nu(x) = -\tfrac{1}{2}\ln\frac{1-x}{2} - \gamma - \psi(\nu+1) + O\bigl((1-x)\ln(1-x)\bigr)$$

[DLMF, Eq. 14.8.3], the Ferrers function of the second kind on $(-1, 1)$, the same convention as the $P_\nu'(0)$, $Q_\nu'(0)$ values below. With $x = \sin(y/R)$ and $\delta = y - \pi R/2$ one has $x = \cos(\delta/R)$, so $1 - x = \delta^2/(2R^2) + O(\delta^4)$ and $\tfrac{1}{2}\ln\frac{1-x}{2} = \ln\frac{\lvert\delta\rvert}{2R} + o(1)$. Hence

$$Q_\nu(\sin(y/R)) = -\ln\frac{\lvert\delta\rvert}{2R} - \gamma - \psi(\nu+1) + o(1),$$

the residual being $O\bigl((\delta^2/R^2)\ln\lvert\delta\rvert\bigr)$. This is where the length $2R$ enters the constant-sector expansion of §3.5: it is the square root of the $1/(4R^2)$ prefactor in $(1-x)/2$. The expansion is even in $\delta$, since $x = \cos(\delta/R)$ is, so the same $2R$ governs both sides $\delta \to 0^\pm$, matching the two-sided bookkeeping of §3.5. The regular branch $P_\nu(x) \to 1$ contributes only to $\mathcal{D}(\lambda)$, while $Q_\nu$ supplies the log datum $\mathcal{N}(\lambda)$ and the constant $-\gamma - \psi(\nu+1)$ in $\mathcal{D}(\lambda)$. The same $2R$ accordingly fixes the threshold $\delta_0 = 2R/e$ of Proposition 4.4 and the constant in $\lambda_b = -4e^{-2\gamma}/\delta_0^2$; a different reference length would shift these constants in lockstep, leaving the eigenvalues themselves invariant.

Define the secular function

$$G(\lambda) = -\frac{\mathcal{D}(\lambda)}{\mathcal{N}(\lambda)}.$$

Since the data referenced to $\delta_0$ satisfy $\tilde u_D = \mathcal{D}(\lambda) + \mathcal{N}(\lambda)\ln(\delta_0/2R)$ (the $\delta_0$-rescaling above), the bridging eigenvalue condition $\tilde u_D = 0$ is

$$G(\lambda) = \ln\frac{\delta_0}{2R}.$$

For $\nu > -1/2$ (equivalently $\lambda > -1/(4R^2)$), the substitution $x = \sin(y/R)$ and the Legendre closed forms give

$$G\bigl(\nu(\nu+1)/R^2\bigr) = -\gamma - \psi(\nu+1) - \frac{Q_\nu'(0)}{P_\nu'(0)},$$

where $\gamma$ is the Euler-Mascheroni constant and $\psi = \Gamma'/\Gamma$ the digamma function (distinct from the section $\psi$). The derivative values at the origin,

$$P_\nu'(0) = \frac{2\pi^{-1/2}\sin(\pi\nu/2)\,\Gamma(\tfrac{\nu}{2}+1)}{\Gamma(\tfrac{\nu}{2}+\tfrac{1}{2})}, \qquad Q_\nu'(0) = \frac{\pi^{1/2}\cos(\pi\nu/2)\,\Gamma(\tfrac{\nu}{2}+1)}{\Gamma(\tfrac{\nu}{2}+\tfrac{1}{2})}$$

[DLMF, Eqs. 14.5.2 and 14.5.4], share the same Gamma quotient, which cancels in the ratio, leaving

$$G\bigl(\nu(\nu+1)/R^2\bigr) = -\gamma - \psi(\nu+1) - \frac{\pi}{2}\cot\frac{\pi\nu}{2}.$$

The cotangent has poles at the even integers $\nu = 0, 2, 4, \ldots$, which are exactly the Friedrichs antisymmetric tower; there $G$ has simple poles.

For $\lambda < -1/(4R^2)$, write $\nu = -\tfrac{1}{2} + i\kappa$ with $\kappa = (-\lambda R^2 - \tfrac{1}{4})^{1/2}$. The closed form continues real-analytically: $\cot(-\tfrac{\pi}{4} + \tfrac{i\pi\kappa}{2}) = -\mathrm{sech}(\pi\kappa) - i\tanh(\pi\kappa)$ and $\mathrm{Im}\,\psi(\tfrac{1}{2} + i\kappa) = \tfrac{\pi}{2}\tanh(\pi\kappa)$, and the imaginary parts cancel, giving

$$G(\lambda) = -\gamma - \mathrm{Re}\,\psi\bigl(\tfrac{1}{2} + i\kappa\bigr) + \frac{\pi}{2}\,\mathrm{sech}(\pi\kappa), \qquad \lambda \le -\frac{1}{4R^2}.$$

> **Lemma 4.3** (Monotonicity)**.** $G$ is strictly increasing between consecutive poles; on each interval between consecutive poles it is a bijection onto $\mathbb{R}$, and on $(-\infty, 0)$ it has no poles and increases from $-\infty$ to $+\infty$.

*Proof.* A Green identity on $(0, \pi R/2)$ for the Neumann-normalized solutions at distinct parameters gives, after the log terms cancel in the cone bracket and the seam bracket vanishes by the shared Neumann data,

$$(\lambda' - \lambda)\int_0^{\pi R/2}\lvert f\rvert\,u_\lambda u_{\lambda'}\,dy = \frac{\mathcal{N}(\lambda')\mathcal{D}(\lambda) - \mathcal{N}(\lambda)\mathcal{D}(\lambda')}{R},$$

whence $G'(\lambda) = R\,\lVert u_\lambda\rVert^2_{\lvert f\rvert}/\mathcal{N}(\lambda)^2 > 0$ at points where $\mathcal{N}(\lambda) \ne 0$; at the even integers, where $\mathcal{N} = 0$, $G$ has simple poles, and monotonicity is asserted on each open interval between consecutive poles. The poles of $G$ are the even integers, which are nonnegative; so $G$ has no pole on $(-\infty, 0)$. The deep-negative asymptotic from $\psi(z) = \ln z - 1/(2z) + O(z^{-2})$ gives $G(\lambda) = -\gamma - \tfrac{1}{2}\ln(-\lambda R^2) + O((-\lambda R^2)^{-1}) \to -\infty$ as $\lambda \to -\infty$, while $G \to +\infty$ as $\lambda \to 0^-$ (the pole at $\nu = 0$). Strict monotonicity makes $G$ a bijection on $(-\infty, 0)$. $\square$

> **Proposition 4.4** (Bridging constant-sector spectrum)**.** For every $\delta_0 > 0$, the constant sector of $A^{\mathrm{br}}_{\delta_0}$ has exactly one negative eigenvalue
>
> $$\lambda_b(\delta_0) = -\frac{4e^{-2\gamma}}{\delta_0^2}\bigl(1 + O(\delta_0^2/R^2)\bigr) \qquad (\delta_0 \to 0^+),$$
>
> a cone-localized bound state independent of the half-width $W$ and strictly increasing in $\delta_0$ with $\lambda_b \to 0^-$ as $\delta_0 \to \infty$. Zero is not an eigenvalue: it lies in the resolvent set. The symmetric tower is unchanged, and the deformed antisymmetric eigenvalues interlace the Friedrichs tower, one in each gap. Moreover, for
>
> $$\delta_0 > \frac{2R}{e}$$
>
> the lowest positive eigenvalue of the constant sector is $2/R^2$ and simple; at $\delta_0 = 2R/e$ it is still $2/R^2$ but doubly degenerate within the constant sector, the deformed antisymmetric root coinciding with the symmetric $\ell = 1$ value (combined with the odd $j = 0$ sector this produces the threshold triple degeneracy of Corollary 6.2 when also $W = \pi R/2$), and for $\delta_0 < 2R/e$ it lies strictly below $2/R^2$.

*Proof.* By Lemma 4.3, $G$ is a bijection of $(-\infty, 0)$ onto $\mathbb{R}$, so the secular condition has exactly one negative root for every $\delta_0$; solving the deep asymptotic against $\ln(\delta_0/2R)$ gives the bound state $\lambda_b(\delta_0)$, and $G' > 0$ gives monotonicity in $\delta_0$ with $\lambda_b \to 0^-$ as $\delta_0 \to \infty$. At $\lambda = 0$ the Neumann-seam solution is $u_0 \equiv 1$, with $\mathcal{N}(0) = 0$ and $\mathcal{D}(0) = 1 \ne 0$, so $\tilde u_D = 1 \ne 0$ and the bridging condition excludes $\lambda = 0$. On each interval between consecutive poles (the Friedrichs tower) $G$ is a bijection onto $\mathbb{R}$, giving one deformed root per gap. Finally, at $\nu = 1$ ($\lambda = 2/R^2$), $\cot(\pi/2) = 0$, so $G(2/R^2) = -\gamma - \psi(2) = -\gamma - (1 - \gamma) = -1$; since $G$ is increasing on $(0, 6/R^2)$, the lowest positive deformed root exceeds $2/R^2$ for $\ln(\delta_0/2R) > -1$ and equals $2/R^2$ at $\ln(\delta_0/2R) = -1$, so for $\delta_0 > 2R/e$ the lowest positive eigenvalue of the sector is $2/R^2$ and simple, while at $\delta_0 = 2R/e$ it remains $2/R^2$ with the deformed root coincident. $\square$

Every deformed antisymmetric eigenfunction has $\mathcal{N} \ne 0$, hence diverges like $\mathcal{N}\ln(\lvert\delta\rvert/\delta_0)$ at the cone; in particular the bound state at $\lambda_b$ is nodeless on each open half (it is the lowest eigenfunction of the half-interval problem, hence positive there by oscillation theory [Weidmann]), with opposite signs on the two halves and a logarithmic divergence at $p_c$. It vanishes nowhere on the smooth locus. The constant $-4e^{-2\gamma}$ in $\lambda_b$ is the standard two-dimensional one-center point-interaction binding energy [AGHH], with $\delta_0$ in the role of the point-interaction renormalization length; the bridging family realizes this point interaction inside the Boscain-Prandi conic framework.

---

## 5. Classification of the Bottom of the Spectrum

> **Theorem 5.1** (Bottom of the spectrum across realizations)**.** Let $A$ be any self-adjoint extension of the minimal twisted Laplacian on $M(W)$, $0 < W < \pi R$. Then:
>
> **(i)** $\inf\sigma(A) \le 0$, with no self-adjoint extension having strictly positive spectral bottom.
>
> **(ii)** $\inf\sigma(A) = 0$ if and only if $A$ is nonnegative; the Friedrichs extension is the maximal such realization, with $\inf\sigma(\Delta_F) = 0$ attained by the discontinuous zero mode $\phi_0$.
>
> **(iii)** For the bridging realization $A^{\mathrm{br}}_{\delta_0}$, $\inf\sigma = \lambda_b(\delta_0) < 0$, a single cone-localized bound state; zero lies in the resolvent set.
>
> For the Friedrichs and bridging extensions the symmetric zonal tower is unchanged, and their difference lives entirely in the antisymmetric subsector; a general parity-mixing (Robin-type) cone condition can instead deform the symmetric subsector. Parts (ii)–(iii) give the explicit bottom for the nonnegative and bridging realizations, while part (i) holds for every self-adjoint extension, the parity-mixing and singular-odd-branch realizations included.

*Proof.* Part (i) is Lemma 3.6(iii), which bounds $\inf\sigma(A) \le \inf\sigma(\Delta_F) = 0$ for nonnegative $A$ and is immediate for non-nonnegative $A$. Part (ii): if $A$ is nonnegative then $\inf\sigma(A) \ge 0$; combined with (i) this forces $\inf\sigma(A) = 0$, and Lemma 3.6(i) identifies Friedrichs as the maximal nonnegative realization, with the bottom attained by $\phi_0$ (Lemma 4.1). Part (iii) is Proposition 4.4. The robustness of the symmetric tower for the Friedrichs and bridging extensions is §4.2; a general cone condition is not claimed robust. $\square$

So the cone lets the bottom escape the positivity the twist would otherwise force, and the form of the escape is set by the extension: the Friedrichs ground state $\phi_0$ is bounded but discontinuous at $p_c$, while the bridging ground state at $\lambda_b$ is continuous in regularized value but logarithmically divergent there. Each evades the obstruction only through its singular behavior at the cone, where elliptic regularity fails. No realization raises the bottom above zero.

---

## 6. Nonconstant Sectors and the First Positive Eigenvalue

The first positive eigenvalue is governed by the competition between the symmetric zonal mode at $2/R^2$, common to the Friedrichs and bridging realizations, and the nonconstant sectors, where these realizations agree. We record the bottom of each nonconstant sector and then prove Theorem 1.2.

### 6.1 The odd (periodic) sectors

The odd transverse modes ($\Phi_j^{\mathrm{o}}$, $j = 0, 1, 2, \ldots$) produce periodic longitudinal functions. The reduced Sturm-Liouville equation with $\mu_j = \bigl((2j+1)\pi/(2W)\bigr)^2$ has, in Schrödinger form, an effective potential proportional to $\sec^2(y/R)$, a symmetric Pöschl-Teller potential.

> **Claim 6.1.** The function $u = \lvert\cos(y/R)\rvert^{\alpha}$ with $\alpha = (2j+1)\pi R/(2W)$ satisfies the reduced Sturm-Liouville equation with eigenvalue $\lambda = \alpha(\alpha+1)/R^2$.

*Proof.* Set $r = \lvert\cos(y/R)\rvert$, so $\lvert f\rvert = r$ and $u = r^\alpha$. On the smooth locus, $R^2(r')^2 = 1 - r^2$ and $r'' = -r/R^2$. Then $\lvert f\rvert\,u' = \alpha\,r^\alpha r'$ and

$$(\lvert f\rvert\,u')' = \frac{\alpha}{R^2}\,r^{\alpha-1}\bigl[\alpha(1 - r^2) - r^2\bigr] = \frac{\alpha}{R^2}\,r^{\alpha-1}\bigl[\alpha - (\alpha+1)r^2\bigr],$$

so $-(\lvert f\rvert\,u')' + (\mu_j/\lvert f\rvert)\,u = r^{\alpha-1}[\alpha(\alpha+1)R^{-2}r^2 - \alpha^2 R^{-2} + \mu_j]$. With $\mu_j = \alpha^2/R^2$ the constant terms cancel, leaving $\alpha(\alpha+1)R^{-2}\,\lvert f\rvert\,u$. $\square$

Under the substitution $x = \sin(y/R)$, $\lvert\cos(y/R)\rvert^\alpha = (1-x^2)^{\alpha/2}$ is the branch regular at $x = 1$ of the associated Legendre equation of degree and order $\alpha$; for integer $\alpha$ it is proportional to the sectoral harmonic $P_\alpha^\alpha$, and at $\alpha = 1$ it reduces to $Y_1^1$ on the covering $S^2$. At both seams $\lvert\cos\rvert^\alpha = 1$ with vanishing derivative, so periodicity holds for all $\alpha$, and the spectral parameter runs continuously with $W$. Near the cone $\lvert\cos(y/R)\rvert^\alpha \sim \lvert\delta/R\rvert^\alpha \to 0$; this is the regular Frobenius branch, with finite Dirichlet energy for all $\alpha > 0$; for $\alpha \ge 1$ the cone is limit-point and it is the unique self-adjoint mode, while in the wide-band first odd sector ($\alpha_0 < 1$) it is the branch selected by the Friedrichs extension and by the bridging realization. A standard ground-state transform ($u = hv$ with $h = \lvert\cos(y/R)\rvert^\alpha$) shows $\lambda = \alpha(\alpha+1)/R^2$ is the sector ground eigenvalue, unique up to scaling. Since $\alpha_j = (2j+1)\pi R/(2W)$ is increasing in $j$, the odd-sector minimum is at $j = 0$:

$$\lambda_0^{\mathrm{odd}}(W) = \frac{\alpha_0(\alpha_0+1)}{R^2}, \qquad \alpha_0 = \frac{\pi R}{2W}, \qquad \psi_0^{\mathrm{odd}} = \lvert\cos(y/R)\rvert^{\alpha_0}\sin(\pi w/2W).$$

This is decreasing in $W$: above $2/R^2$ for $W < \pi R/2$, equal at $W = \pi R/2$, and below for $W > \pi R/2$.

### 6.2 The even nonconstant sectors

The even nonconstant modes ($\Phi_k^{\mathrm{e}}$, $k \ge 1$) produce anti-periodic longitudinal functions. The sector ground state is obtained by a sign flip across the cone,

$$u_k(y) = \mathrm{sgn}(\delta)\,\lvert\cos(y/R)\rvert^{\alpha_k}, \qquad \alpha_k = \frac{k\pi R}{W},$$

which is anti-periodic at the seams and continuous at the cone (the sign flip multiplies a vanishing factor), with vanishing weighted flux and no distributional contribution; it lies in every self-adjoint extension's domain, the cone being limit-point in these sectors. On each half, $\lvert\cos(y/R)\rvert^{\alpha_k}$ is positive and nodeless, so by the Sturm oscillation theorem for the separated half-interval problem (Neumann at the seam, regular Frobenius at the cone) it is the half-interval ground state, with eigenvalue $\alpha_k(\alpha_k+1)/R^2$. Since $\alpha_k = k\pi R/W \ge \pi R/W > 1$ for all $k \ge 1$ and $W < \pi R$, every even nonconstant sector lies strictly above $2/R^2$. The sharp $+1$ in $\alpha_k(\alpha_k+1)$ matters: a potential-only bound gives $\alpha_k^2/R^2$, which fails to clear $2/R^2$ for $\alpha_k \in (1, \sqrt{2})$, whereas $\alpha_k(\alpha_k+1)/R^2 > 2/R^2$ for all $\alpha_k > 1$.

### 6.3 The transition

*Proof of Theorem 1.2.* By Proposition 3.5 the spectrum of each realization is discrete and reduces over the transverse sectors, so the first positive eigenvalue is the minimum of the first positive sector entries. By §4.2 the constant sector contributes $2/R^2$ as its first positive value, shared by the Friedrichs extension and, by Proposition 4.4, by every bridging extension with $\delta_0 > 2R/e$. The odd sectors contribute $\alpha_0(\alpha_0+1)/R^2$ with $\alpha_0 = \pi R/(2W)$ (§6.1), and by §6.2 the even nonconstant sectors lie strictly above $2/R^2$. The function $\alpha \mapsto \alpha(\alpha+1)$ is increasing, and $\alpha_0$ is decreasing in $W$, so the first positive eigenvalue is $\min(2/R^2,\,\alpha_0(\alpha_0+1)/R^2)$: it equals $2/R^2$ when $\alpha_0 \ge 1$, i.e. $W \le \pi R/2$, and $\alpha_0(\alpha_0+1)/R^2$ when $W > \pi R/2$. At $W = \pi R/2$ both branches give $2/R^2$. $\square$

> **Corollary 6.2** (Degeneracy at the transition)**.** For the Friedrichs extension and for bridging with $\delta_0 > 2R/e$, at $W = \pi R/2$ the first-positive eigenspace is two-dimensional, spanned by $\psi_1 = \sin(y/R)$ and $\psi_2 = \lvert\cos(y/R)\rvert\,\sin(w/R)$; the next contributions ($\ell = 3$ zonal, $j = 1$ odd, $k = 1$ even) are $12/R^2$, $12/R^2$, $6/R^2$, all above. On the covering $S^2$, $\psi_1$ restricts from $Y_1^0$ while $\psi_2$ does not lift to a smooth function (the absolute value is required by equivariance, not a coordinate artifact). Away from the critical width the first positive eigenvalue is simple. At the special double threshold $W = \pi R/2$ and $\delta_0 = 2R/e$ the deformed antisymmetric constant-sector root coincides with the symmetric $\ell = 1$ value (Proposition 4.4), so the bridging first-positive eigenspace is there three-dimensional, the additional mode being $\mathrm{sgn}(\delta)\,Q_1(\sin(y/R))$, the Neumann-seam solution at $\nu = 1$, which is pure $Q_1$ (since $Q_1'(0) = 0$) and diverges logarithmically at the cone; it is antisymmetric in cone parity ($\delta \mapsto -\delta$), distinct from the transverse-odd $\psi_2$, and the three modes are mutually orthogonal, so the multiplicity there is exactly three (the next sector entries $6/R^2$ and $12/R^2$ are strictly above). For $\delta_0 > 2R/e$, the hypothesis of this corollary, this root lies strictly above $2/R^2$ and only $\psi_1, \psi_2$ remain; the Friedrichs extension, whose antisymmetric tower is $\ell = 0, 2, 4, \ldots$, carries no mode at $2/R^2$ and is two-dimensional at the threshold.

> **Corollary 6.3** (Sign-changing first positive eigenfunction)**.** For $W > \pi R/2$ the first positive eigenfunction $\lvert\cos(y/R)\rvert^{\alpha_0}\sin(\pi w/2W)$ changes sign across $w = 0$ (the core loop); for $W < \pi R/2$ the eigenfunction $\sin(y/R)$ is positive on the interior but vanishes at the seam, where the Möbius identification imposes the sign reversal. Because $\mathcal{L}$ is nontrivial, no section admits a globally positive representative, so the Perron-Frobenius nodeless-ground argument does not apply.

---

## 7. Discussion

This model separates two spectral effects. The first positive eigenvalue is the robust one: in the narrow regime it equals $2/R^2$ for the Friedrichs extension and for bridging with $\delta_0 > 2R/e$, with the width transition at $W = \pi R/2$. The bottom of the spectrum, by contrast, depends entirely on the extension: it is $0$ for every nonnegative realization (including the Friedrichs and Krein-von Neumann extensions [AlonsoSimon]) and strictly negative for every other, in particular the bridging family at finite $\delta_0$. So anti-periodicity does not force a positive spectral bottom: Friedrichs maximality (Lemma 3.6) caps the bottom at $0$, and bridging replaces the zero mode by a logarithmic bound state.

The nodal pattern also changes at the transition. For $W > \pi R/2$ the first positive eigenfunction changes sign across the core loop; for $W < \pi R/2$ it is positive in the interior and vanishes at the seam, where the twist imposes the sign reversal. On an orientable surface Perron-Frobenius and Courant's nodal domain theorem [CourantHilbert] would give a positive ground eigenfunction, but on $M(W)$ a nowhere-vanishing section would trivialize $\mathcal{L}$. This is the line-bundle analogue of Shigekawa's magnetic spectral-positivity criterion [Shigekawa]; the cone goes further, letting the bottom itself fall to zero or below.

The renormalization length $\delta_0$ is the one quantity in the model that the intrinsic geometry leaves free. The Friedrichs extension needs no such scale and is the standard conic choice [Cheeger1979, Cheeger1983]; under it the topology is spectrally invisible (Proposition 4.2) and the bottom is the zero mode. At $\alpha_{\mathrm{BP}} = -1$ it is moreover the unique Markovian realization (Theorem 1.13(ii) of [BP]), the bridging extensions being non-Markovian, and together with the generic decoupling of two-dimensional point interactions this makes Friedrichs the default; a transmitting limit would survive only if a smoothing of the cone were tuned to a zero-energy resonance. Whether a geometric regularization selects a canonical $\delta_0$, for instance as a norm-resolvent limit of smoothed-cone Laplacians [AGHH], remains open. Until then $\lambda_b$ is an extension artifact rather than an intrinsic invariant, and its leading form carries $O(\delta_0^2/R^2)$ corrections that are not small at moderate $\delta_0$.

Two directions stand out. A Lichnerowicz-type lower bound [Lichnerowicz, Obata] adapted to $M(W)$ would give a geometric reading of the narrow-regime value $2/R^2 = R_{\mathrm{sm}}$; and the higher sector spectra, the thin-strip limit ($W \to 0$), and the flat limit ($R \to \infty$) should connect the closed forms here with the asymptotic formulas of [KKZ].

---

## References

- **[AGHH]** S. Albeverio, F. Gesztesy, R. Høegh-Krohn, and H. Holden, *Solvable Models in Quantum Mechanics*. 2nd ed., AMS Chelsea Publishing, Providence, RI, 2005.
- **[AlonsoSimon]** A. Alonso and B. Simon, The Birman-Krein-Vishik theory of self-adjoint extensions of semibounded operators. *J. Operator Theory* **4** (1980), no. 2, 251–270.
- **[BBC]** W. Ballmann, J. Brüning, and G. Carron, Eigenvalues and holonomy. *Int. Math. Res. Not.* **2003** (2003), no. 12, 657–665.
- **[BK]** G. Berkolaiko and P. Kuchment, *Introduction to Quantum Graphs*. Math. Surveys Monogr. 186, Amer. Math. Soc., Providence, RI, 2013.
- **[BP]** U. Boscain and D. Prandi, Self-adjoint extensions and stochastic completeness of the Laplace-Beltrami operator on conic and anticonic surfaces. *J. Differential Equations* **260** (2016), no. 4, 3234–3269.
- **[BS]** J. Brüning and R. Seeley, Regular singular asymptotics. *Adv. Math.* **58** (1985), no. 2, 133–148.
- **[Cheeger1979]** J. Cheeger, On the spectral geometry of spaces with cone-like singularities. *Proc. Nat. Acad. Sci. U.S.A.* **76** (1979), no. 5, 2103–2106.
- **[Cheeger1983]** J. Cheeger, Spectral geometry of singular Riemannian spaces. *J. Differential Geom.* **18** (1983), no. 4, 575–657.
- **[CourantHilbert]** R. Courant and D. Hilbert, *Methods of Mathematical Physics. Vol. I*. Interscience, New York, 1953.
- **[Friedrichs]** K. Friedrichs, Spektraltheorie halbbeschränkter Operatoren und Anwendung auf die Spektralzerlegung von Differentialoperatoren. *Math. Ann.* **109** (1934), no. 1, 465–487.
- **[KSWW]** H. Kalf, U.-W. Schmincke, J. Walter, and R. Wüst, On the spectral theory of Schrödinger and Dirac operators with strongly singular potentials. In *Spectral theory and differential equations*, pp. 182–226, Lecture Notes in Math. 448, Springer, Berlin, 1975.
- **[KKZ]** T. Kalvoda, D. Krejčiřík, and K. Zahradová, Effective quantum dynamics on the Möbius strip. *J. Phys. A* **53** (2020), no. 37, 375201.
- **[KayStuder]** B. S. Kay and U. M. Studer, Boundary conditions for quantum mechanics on cones and fields around cosmic strings. *Comm. Math. Phys.* **139** (1991), no. 1, 103–139.
- **[Lichnerowicz]** A. Lichnerowicz, *Géométrie des groupes de transformations*. Dunod, Paris, 1958.
- **[Obata]** M. Obata, Certain conditions for a Riemannian manifold to be isometric with a sphere. *J. Math. Soc. Japan* **14** (1962), 333–340.
- **[DLMF]** F. W. J. Olver, A. B. Olde Daalhuis, D. W. Lozier, B. I. Schneider, R. F. Boisvert, C. W. Clark, B. R. Miller, B. V. Saunders, H. S. Cohl, and M. A. McClain (eds.), *NIST Digital Library of Mathematical Functions*. Release 1.2.6 of 2026-03-15, https://dlmf.nist.gov.
- **[RS]** M. Reed and B. Simon, *Methods of Modern Mathematical Physics. II: Fourier Analysis, Self-Adjointness*. Academic Press, New York, 1975.
- **[Shigekawa]** I. Shigekawa, Eigenvalue problems for the Schrödinger operator with the magnetic field on a compact Riemannian manifold. *J. Funct. Anal.* **75** (1987), no. 1, 92–127.
- **[Weidmann]** J. Weidmann, *Spectral Theory of Ordinary Differential Operators*. Lecture Notes in Math. 1258, Springer, Berlin, 1987.

---

/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /
