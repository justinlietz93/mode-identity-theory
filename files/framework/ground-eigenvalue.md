/ **[`main`](../../README.md)** / **[`framework`](../framework/)** / **[`cosmos`](../cosmos/)** / **[`spectrum`](../spectrum/)** /

---

# Ground-State Transition for the Twisted Laplacian on a Constant-Curvature Möbius Band

We study the Laplace-Beltrami operator on sections of the orientation line bundle over a constant-curvature Möbius band $M(W)$ of half-width $W$, constructed from a spherical band on $S^2(R)$ with the antipodal-edge identification. The metric degeneracy at the identification's fixed point creates a conical singularity where the operator fails to be essentially self-adjoint in the constant transverse sector. We adopt the continuous transmission extension and prove that the ground eigenvalue exhibits a width-dependent transition:

$$\lambda_0(W) = \begin{cases} 2/R^2 & 0 < W \leq \pi R/2, \\ \alpha(\alpha+1)/R^2,\quad \alpha = \pi R/(2W) & \pi R/2 < W < \pi R. \end{cases}$$

Both branches are realized by explicit eigenfunctions: the $\ell = 1$ zonal Legendre polynomial $\sin(y/R)$ for the narrow regime, and the product $|\cos(y/R)|^\alpha\sin(\pi w/2W)$ (with longitudinal factor $P_\alpha^\alpha$, a sectoral associated Legendre function of non-integer degree) for the wide regime. At $W = \pi R/2$ the ground eigenvalue is doubly degenerate, with the two modes corresponding to $Y_1^0$ and a $Y_1^1$-type harmonic on the covering sphere.

The proof is by exact separation into transverse Neumann sectors, with the reduced Sturm-Liouville problems solved in closed form via Legendre functions for all widths. The ground eigenvalue is positive because the transmission extension excludes a discontinuous zero mode that the Friedrichs extension would admit; its value and width-dependence are determined by the sector comparison. For $W > \pi R/2$, the covering representative of the ground eigenfunction changes sign, reflecting the nontriviality of the orientation bundle.

---

## 1. Introduction

The Möbius band is non-orientable: its orientation line bundle has nontrivial holonomy, so a scalar representative on the oriented double cover changes sign after one circuit of the core loop. This paper asks how that topological twist interacts with the Laplacian when the metric also degenerates, collapsing a transverse fiber to a conical singularity.

The setting is the twisted Laplacian (the Laplace-Beltrami operator on sections of the orientation bundle $\mathcal{L}$) on a constant-curvature Möbius band $M(W)$ constructed from a spherical band on $S^2(R)$ of half-width $W$. The metric $ds^2 = dy^2 + \cos^2(y/R)\,dw^2$ collapses a transverse fiber to a cone point $p_c$ at $y = \pi R/2$. At $p_c$, the operator is not essentially self-adjoint in the constant transverse sector, and a choice of self-adjoint extension is required. The Friedrichs extension admits a discontinuous piecewise-constant zero mode; the transmission extension, selected by the regularity of the covering geometry, enforces continuity and excludes it.

The main result is a closed-form ground eigenvalue that depends on the width:

**Theorem.** *On $M(W)$ with the continuous transmission extension, the ground eigenvalue of the twisted Laplacian is*

$$\lambda_0(W) = \begin{cases} 2/R^2 & 0 < W \leq \pi R/2, \\ \alpha(\alpha+1)/R^2, \quad \alpha = \pi R/(2W) & \pi R/2 < W < \pi R. \end{cases}$$

*At $W = \pi R/2$ the ground eigenvalue is doubly degenerate. Both branches are realized by explicit eigenfunctions: $\sin(y/R)$ (the $\ell = 1$ zonal Legendre polynomial) for the narrow regime, and $|\cos(y/R)|^\alpha\sin(\pi w/2W)$ for the wide regime, where the longitudinal factor $|\cos(y/R)|^\alpha$ is the sectoral associated Legendre function $P_\alpha^\alpha$ with non-integer degree.*

The proof proceeds by separation of variables into transverse Neumann sectors, followed by exact solution of the reduced Sturm-Liouville problem in each sector via Legendre functions. The constant sector yields the width-independent branch $2/R^2$; the odd (periodic) sectors yield the width-dependent branch $\alpha(\alpha+1)/R^2$; the even nonconstant sectors are shown strictly above $2/R^2$ for all admissible widths. The eigenvalues and eigenfunctions are exact and in closed form for all $W \in (0, \pi R)$.

The spectral theory of the Laplacian on spaces with conical singularities originates with Cheeger [Cheeger1979, Cheeger1983], who established self-adjointness of the Friedrichs extension and related the deficiency indices to the link geometry. Boscain and Prandi [BP] classified all self-adjoint extensions on model conic surfaces $ds^2 = dx^2 + |x|^{-2\alpha}\,d\theta^2$, identifying disjoint and bridging families; our transmission extension is their bridging extension at $\alpha_{\rm BP} = -1$. Brüning and Seeley [BS] developed the Frobenius-type asymptotics we use to analyze the cone, and the inverse-square potential theory of Kalf, Schmincke, Walter, and Wüst [KSWW; RS] governs the limit-point/limit-circle classification in the nonconstant sectors. The transmission condition at the cone is analogous to the Kirchhoff vertex condition in quantum-graph theory [BK].

The closest spectral predecessor is Kalvoda, Krejčiřík, and Zahradová [KKZ], who study the Laplacian on a Möbius strip embedded in $\mathbb{R}^3$ with Dirichlet boundary conditions. Their thin-strip asymptotics yield effective one-dimensional operators. The present paper differs in three respects: constant positive curvature (vs. the geometry of an embedded strip), Neumann boundary conditions (which supply the constant transverse mode that activates the extension ambiguity), and the cone singularity (absent from the KKZ geometry). These differences produce exact closed-form solutions for all widths, rather than thin-strip asymptotics.

After setting up the geometric model (§2) and the operator domain with its extension classification (§3), the paper computes the zonal spectrum via Legendre reduction (§4), the sectoral spectra via associated Legendre functions (§5), and proves the main theorem by sector comparison (§6). Section 7 discusses the sign-changing ground state and its relation to Perron-Frobenius theory.

---

## 2. The Geometric Model $M(W)$

Consider the round 2-sphere $S^2(R)$ of radius $R$. Let $\gamma$ be a great circle, and let $y$ denote arclength along a meridian measured from $\gamma$, so that $y = 0$ and $y = \pi R$ correspond to antipodal arcs of $\gamma$ reached on opposite sides of the pole at $y = \pi R/2$. Let $w$ denote arclength along $\gamma$, with $w \in [-W, W]$ for a half-width parameter $0 < W < \pi R$. The induced metric on the band $\{(y, w) : 0 \leq y \leq \pi R,\; |w| \leq W\}$ is

$$ds^2 = dy^2 + \cos^2(y/R)\,dw^2.$$

The Gauss curvature is $K = 1/R^2$ on the smooth locus and the scalar curvature is $R_{\rm sm} = 2/R^2$.

The map $\tau(y, w) = (\pi R - y, -w)$ is an orientation-preserving isometric involution ($D\tau = \mathrm{diag}(-1, -1)$, $\det D\tau = +1$) with a single fixed point at $(\pi R/2, 0)$. Identifying $(0, w) \sim (\pi R, -w)$ via $\tau$ produces the non-orientable surface

$$M(W) = [0, \pi R] \times [-W, W] \;/\; (0, w) \sim (\pi R, -w)$$

with boundary $\partial M \cong S^1$, since the two arcs $w = \pm W$ join into a single closed curve under the identification. The non-orientability arises from the edge identification itself: transporting a frame $(\partial_y, \partial_w)$ across the seam sends $\partial_w \mapsto -\partial_w$, reversing the frame orientation.

At $y = \pi R/2$, the metric coefficient $\cos(y/R)$ vanishes, collapsing the transverse fiber $\{y = \pi R/2\} \times [-W, W]$ to a single point $p_c$ in the metric space. Both boundary arcs pass through $p_c$ (the boundary meridians meet at the pole), so $p_c \in \partial M$ and the boundary curve has a corner at the cone vertex. The local model is a half-cone: the link at $p_c$ is the interval $[-W, W]$ of angular length $2W/R$, with the boundary arcs as its endpoints and full cone angle $2W/R$. Under Neumann boundary conditions at $w = \pm W$, the transverse problem unfolds onto a circle of circumference $4W/R$ (§3.4), recovering the circle-link framework of Boscain and Prandi [BP] with parameter $\alpha_{\rm BP} = -1$. Although $p_c$ lies on $\partial M$ as a surface point, it sits at $y = \pi R/2$, interior to the longitudinal interval $(0, \pi R)$. The reduced one-dimensional eigenvalue problems of §§4--5 inherit this interior singular-point structure, and the extension theory of §3 applies in full.

The cone angle $2W/R$ equals $\pi$ at the critical width $W = \pi R/2$. For $W < \pi R/2$ (narrow band), the cone angle is less than $\pi$; for $W > \pi R/2$ (wide band), it exceeds $\pi$. As $W \to \pi R$, each half of the band approaches a hemisphere.

---

## 3. Twisted Sections and the Operator Domain

### 3.1 The orientation line bundle

Since $M(W)$ is non-orientable, scalar functions on it do not capture the full spectral problem. The natural domain for the Laplacian is the space of sections of the orientation line bundle $\mathcal{L}$. A smooth function on the covering band $\widetilde{M} = [0, \pi R] \times [-W, W]$ descends to a section of $\mathcal{L} \to M$ if and only if it satisfies the equivariance condition

$$\psi(\pi R, -w) = -\psi(0, w) \qquad \text{for all } w \in [-W, W].$$

This sign reversal is the defining property of sections of $\mathcal{L}$: traversing the core loop once reverses the orientation, so a section of the orientation bundle picks up a factor of $-1$.

The **twisted Laplacian** is the Laplace-Beltrami operator acting on sections of $\mathcal{L}$. It is the standard Laplace-Beltrami operator on the smooth locus; the adjective "twisted" refers to the domain (anti-periodic sections) rather than to a modification of the operator itself. The eigenvalue problem $-\Delta\psi = \lambda\psi$ is posed for sections of $\mathcal{L}$ throughout this paper.

### 3.2 The formal operator

On the smooth locus $M^\circ = M \setminus \{p_c\}$ (where $p_c$ denotes the cone point at $y = \pi R/2$), the Laplace-Beltrami operator associated to the metric $ds^2 = dy^2 + f(y)^2\,dw^2$ with $f(y) = \cos(y/R)$ is

$$\Delta\psi = \psi_{yy} + \frac{f'}{f}\psi_y + \frac{1}{f^2}\psi_{ww} = \psi_{yy} - \frac{1}{R}\tan\!\left(\frac{y}{R}\right)\psi_y + \frac{1}{\cos^2(y/R)}\psi_{ww}.$$

The area element is $dA = |f(y)|\,dy\,dw$, and $L^2(M, dA)$ denotes the Hilbert space of square-integrable sections of $\mathcal{L}$ with respect to this measure. (The metric coefficient is $f^2 = \cos^2(y/R) \geq 0$ throughout; the signed function $f = \cos(y/R)$ changes sign at the cone $y = \pi R/2$, so the Riemannian density $\sqrt{\det g} = |f|$ carries the absolute value.)

The boundary $\partial M$ consists of two geodesic arcs at $w = \pm W$. We impose Neumann boundary conditions:

$$\partial_w\psi\big|_{w = \pm W} = 0.$$

These boundary arcs are geodesics of the surface ($\kappa_g = 0$).

### 3.3 The involution and the cone point

The involution $\tau(y, w) = (\pi R - y, -w)$ is an isometry of the covering band $\widetilde{M}$ with a unique fixed point at $(\pi R/2, 0)$, the cone point $p_c$. The Möbius identification restricts $\tau$ to the boundary edges $\{0\} \times [-W, W]$ and $\{\pi R\} \times [-W, W]$.

At $p_c$, $f(\pi R/2) = \cos(\pi/2) = 0$. Setting $\delta = y - \pi R/2$:

$$f(y) = \cos(y/R) = -\sin(\delta/R) \quad \Longrightarrow \quad |f| \sim \frac{|\delta|}{R} \quad \text{as } \delta \to 0.$$

The transverse fiber $[-W, W]$ has metric length $2W|f(y)|$, which collapses to zero. On the covering $S^2$, the coordinate $y = \pi R/2$ is a smooth pole; on the edge-identified Möbius band, the same collapse produces a conical singularity with cone angle $2W/R$.

The surface is smooth away from $p_c$, with constant Gaussian curvature $K = 1/R^2$ and smooth-locus scalar curvature

$$R_{\rm sm} = 2K = \frac{2}{R^2}.$$

Distributional curvature at $p_c$ is not invoked in this paper.

### 3.4 Transverse decomposition and cone asymptotics

Separation of variables $\psi(y,w) = u(y)\,\Phi(w)$ with $-\Phi'' = \mu\,\Phi$ subject to Neumann conditions $\Phi'(\pm W) = 0$ yields two families of transverse eigenmodes on $[-W, W]$.

**Even family** (symmetric under $w \mapsto -w$):

$$\Phi_k^{\rm e}(w) = \cos(k\pi w/W), \qquad \mu_k^{\rm e} = (k\pi/W)^2, \qquad k = 0, 1, 2, \ldots$$

The case $k = 0$ is the constant mode $\Phi_0^{\rm e} \equiv 1$ with $\mu_0 = 0$.

**Odd family** (antisymmetric under $w \mapsto -w$):

$$\Phi_j^{\rm o}(w) = \sin\bigl((2j+1)\pi w/(2W)\bigr), \qquad \mu_j^{\rm o} = \bigl((2j+1)\pi/(2W)\bigr)^2, \qquad j = 0, 1, 2, \ldots$$

Both families satisfy $(\Phi^{\rm e/o})'(\pm W) = 0$.

The Möbius identification $\psi(\pi R, -w) = -\psi(0, w)$ interacts with the transverse parity as follows. For even $\Phi(w) = \Phi(-w)$, the identification gives $u(\pi R)\Phi(w) = -u(0)\Phi(w)$, forcing $u(\pi R) = -u(0)$: the longitudinal function is **anti-periodic**. For odd $\Phi(-w) = -\Phi(w)$, the identification gives $u(\pi R)(-\Phi(w)) = -u(0)\Phi(w)$, forcing $u(\pi R) = u(0)$: the longitudinal function is **periodic**.

A Neumann eigenmode on $[-W, W]$ extends by even reflection to a periodic function on a circle of circumference $4W$. Under this unfolding, the even family $\Phi_k^{\rm e}$ corresponds to Fourier modes $e^{i(2k)\theta}$ (even harmonics) and the odd family $\Phi_j^{\rm o}$ to $e^{i(2j+1)\theta}$ (odd harmonics) on that circle. The $n = 0$ constant mode is therefore the analogue of the $k = 0$ Fourier sector in [BP], and the non-essential-self-adjointness of $\hat\Delta_0$ at the cone (Theorem 1.6(ii) of [BP]) is the same phenomenon in both settings. The Neumann interval replaces the circle; the local analysis at the cone is identical.

In each sector, the reduced eigenequation for the longitudinal function $u(y)$ takes the Sturm-Liouville form

$$-\bigl(|f|\,u'\bigr)' + \frac{\mu}{|f|}\,u = \lambda\,|f|\,u, \qquad f(y) = \cos(y/R),$$

on $L^2\bigl((0, \pi R),\,|f|\,dy\bigr)$, where $\mu$ is the transverse eigenvalue of the sector. Near the cone ($\delta \to 0$, $|f| \sim |\delta|/R$), this becomes

$$-\left(\frac{|\delta|}{R}\,u'\right)' + \frac{\mu R}{|\delta|}\,u = \lambda\,\frac{|\delta|}{R}\,u.$$

Substituting $u = |\delta|^s$ into the leading-order balance gives the indicial equation

$$s^2 = \mu R^2.$$

**The constant sector ($\mu = 0$, even family $k = 0$).** The indicial equation gives $s^2 = 0$ (double root). The two local solutions are

$$u_1 = a_0 + a_2\delta^2 + O(\delta^4), \qquad u_2 = \log|\delta| + b_2\delta^2 + O(\delta^4).$$

Both are square-integrable against the weight $|\delta|/R\,d\delta$: $\int |\delta|^0 \cdot |\delta|\,d\delta < \infty$ and $\int (\log|\delta|)^2 \cdot |\delta|\,d\delta < \infty$. The cone is a **limit-circle** endpoint.

**Nonconstant sectors with $\alpha \geq 1$.** Write $\alpha = \sqrt{\mu}\,R$ for the indicial exponent. For the lowest odd mode ($j = 0$), $\mu = (\pi/(2W))^2$ and $\alpha = \pi R/(2W)$; for the lowest nonconstant even mode ($k = 1$), $\alpha = \pi R/W$. Higher modes have proportionally larger $\alpha$. The threshold $\alpha = 1$ corresponds to $W = \pi R/2$ for the $j = 0$ odd mode and $W = \pi R$ for the $k = 1$ even mode. When $\alpha \geq 1$, the singular branch $|\delta|^{-\alpha}$ fails the $L^2$ condition against the weight $|\delta|/R\,d\delta$:

$$\int u^2\,|f|\,d\delta \sim \int |\delta|^{-2\alpha} \cdot |\delta|\,d\delta = \int |\delta|^{1-2\alpha}\,d\delta = \infty \qquad \text{for } \alpha \geq 1.$$

The cone is **limit-point**. Self-adjointness is unique; no extension choice arises.

**Nonconstant sectors with $0 < \alpha < 1$.** This regime occurs only for wide bands: $W > \pi R/2$ for the $j = 0$ odd mode, $W > \pi R$ (impossible) for the $k = 1$ even mode. Both branches $|\delta|^{\pm\alpha}$ are now $L^2$ against the weight (since $1 - 2\alpha > -1$). The cone is **limit-circle**. The branches are distinguished by the Dirichlet energy (the quadratic form integral). For the singular branch $u = |\delta|^{-\alpha}$, the derivative is $u' = -\alpha\,|\delta|^{-\alpha-1}\,\mathrm{sgn}(\delta)$, giving $(u')^2 = \alpha^2\,|\delta|^{-2\alpha-2}$. The Dirichlet integral is:

$$\int (u')^2\,|f|\,d\delta \sim \int \alpha^2\,|\delta|^{-2\alpha-2} \cdot |\delta|\,d\delta = \alpha^2\!\int |\delta|^{-2\alpha-1}\,d\delta = \infty \qquad \text{for all } \alpha > 0.$$

The exponent $-2\alpha - 1 < -1$ for every $\alpha > 0$, so this divergence holds throughout the limit-circle regime. The Friedrichs extension excludes the singular branch by requiring finite Dirichlet integral, selecting the regular solution $|\delta|^{+\alpha}$. The regular eigenfunction $|\delta|^{\alpha} = |\cos(y/R)|^{\alpha}$ vanishes at the cone; continuity there is automatic. The Friedrichs extension and the continuous transmission extension coincide. (The function $|\cos(y/R)|^\alpha$ for non-integer $\alpha \in (0,1)$ is the sectoral associated Legendre function $P_\alpha^\alpha$ restricted to the band; its properties are developed in §5.)

The limit-point/limit-circle classification at a singular endpoint depends only on the local behavior of the coefficients [Weidmann]. Near $p_c$, the weight $|f|$ vanishes linearly in $\delta$, matching the flat-cone case $\alpha = -1$ in the notation of Boscain and Prandi [BP]. Their Theorem 1.6(ii) establishes that for $\alpha \in (-3, -1]$ on the model cone $ds^2 = dx^2 + |x|^{-2\alpha}\,d\theta^2$, only the $k = 0$ Fourier component fails to be essentially self-adjoint. Since the limit-circle/limit-point distinction is local, the same conclusion transfers to the constant-curvature Möbius band: the global curvature $K = 1/R^2$ modifies the eigenvalues but does not alter the self-adjoint extension classification at the cone.

**Lemma (Vanishing of nonconstant modes at the cone).** Let $\psi(y,w) = u(y)\,\Phi(w)$ be a section of $\mathcal{L}$ that is continuous on $M(W)$, where $\Phi$ is any nonconstant Neumann transverse eigenmode (from either the even family $\Phi_k^{\rm e}$ with $k \geq 1$ or the odd family $\Phi_j^{\rm o}$ with $j \geq 0$). Then $u(\pi R/2) = 0$.

*Proof.* At the cone point $p_c$, the metric coefficient $f(y) = \cos(y/R)$ vanishes, collapsing the entire transverse fiber $\{y = \pi R/2\} \times [-W, W]$ to a single geometric point. A continuous section must take a single well-defined value at $p_c$. The transverse eigenfunction $\Phi(w)$ is nonconstant: it takes distinct values at distinct $w$-positions. A product $u(\pi R/2) \cdot \Phi(w)$ with $u(\pi R/2) \neq 0$ would assign multiple values to the single point $p_c$, contradicting continuity. Therefore $u(\pi R/2) = 0$.

For the constant mode $\Phi_0^{\rm e} \equiv 1$, the product $u(\pi R/2) \cdot 1$ assigns a single value to $p_c$ regardless of $w$. The constant sector is the only sector where a nonzero apex value is compatible with continuity.

This lemma is the geometric reason that the Friedrichs and transmission extensions differ only in the constant sector: for nonconstant modes, continuity at $p_c$ already forces $u(p_c) = 0$, which is guaranteed by the regular Frobenius branch ($|\delta|^{\alpha} \to 0$ for $\alpha > 0$) selected by the Friedrichs extension. The two extensions impose the same condition and therefore coincide. For the constant sector, continuity permits a nonzero apex value, and the question of whether $u$ must be continuous across $p_c$ (transmission) or may jump (Friedrichs) becomes the live distinction.

### 3.5 The continuous transmission extension

The analysis of §3.4 shows that an extension choice arises only in the constant sector ($\mu = 0$), where both local solutions are $L^2$. The two canonical choices are:

**The Friedrichs extension.** In the constant sector ($\mu = 0$), the Friedrichs extension [Friedrichs] is characterized by Theorem 1.8 of [BP] (applied at $\alpha = -1$): its domain consists of functions $u \in D_{\max}(\hat\Delta_0)$ satisfying

$$\lim_{\delta \to 0^+} \frac{|\delta|}{R}\,u'(\delta) = 0 \qquad \text{and} \qquad \lim_{\delta \to 0^-} \frac{|\delta|}{R}\,u'(\delta) = 0,$$

with no condition relating the limiting values of $u$ on the two sides. Here $|\delta|/R \cdot u'(\delta)$ is the **weighted flux** (the Sturm-Liouville momentum $p\,u'$ with $p = |f| = |\delta|/R$), and the conditions require it to vanish on each side of the cone separately. Following the convention of [BP], the coordinate $\delta$ is oriented away from the cone on each side (toward $\delta > 0$ on $M^+$, toward $\delta < 0$ on $M^-$), so the matching condition in the transmission extension below appears as $u_N^+ = u_N^-$ (equality) rather than $u_N^+ + u_N^- = 0$. The Friedrichs extension is the "disjoint dynamics" case $c^+ = c^- = 0$ in [BP, Theorem 1.8]: each half of the band evolves independently, with vanishing weighted flux at the cone on each side. The form domain is the closure of $C_c^\infty(M \setminus \{p_c\})$ in the energy norm; this closure decomposes as a direct sum over $M^+$ and $M^-$, so no section in the Friedrichs domain connects through $p_c$.

This decoupling admits discontinuous sections. In particular, the piecewise-constant anti-periodic function

$$\phi_0(y, w) = \begin{cases} +c & \text{if } y < \pi R/2, \\ -c & \text{if } y > \pi R/2, \end{cases}$$

lies in the Friedrichs domain for any constant $c$: it has $\nabla\phi_0 = 0$ on each smooth half (hence vanishing weighted flux), and it satisfies the anti-periodic condition $\phi_0(\pi R, -w) = -c = -\phi_0(0, w)$. Since $-\Delta\phi_0 = 0$ on the smooth locus, $\phi_0$ is a genuine eigenfunction with eigenvalue 0. The Friedrichs extension admits a **discontinuous zero mode** in the constant sector.

**The continuous transmission extension.** The extension choice at the constant-sector cone endpoint is governed by the boundary pairing. For $u, v \in D_{\max}(\hat\Delta_0)$, the Lagrange bracket (weighted Wronskian) is

$$[u, v](\delta) = u(\delta)\cdot\frac{|\delta|}{R}\,v'(\delta) - v(\delta)\cdot\frac{|\delta|}{R}\,u'(\delta),$$

where $|\delta|/R \cdot u'$ is the flux through the cone in the natural Sturm-Liouville pairing. Self-adjointness of an extension requires the boundary form to vanish: $[u, v](0^+) = [u, v](0^-)$ for all $u, v$ in the domain. Following [BP, Theorem 1.8], the self-adjoint extensions of $\hat\Delta_0$ are classified into disjoint dynamics (each side independent, parametrized by flux conditions $c^\pm$) and mixed dynamics (the two sides coupled by a matrix $K \in \mathrm{SL}_2(\mathbb{R})$ relating the value-flux pairs $(u_D^\pm, u_N^\pm)$, where $u_D^\pm = \lim_{\delta \to 0^\pm} u(\delta)$ and $u_N^\pm = \lim_{\delta \to 0^\pm} (|\delta|/R)\,u'(\delta)$).

The bridging extension is the mixed-dynamics case $K = \mathrm{Id}$ (Remark 1.9 of [BP]). Its domain conditions are:

$$u_D^+ = u_D^- \qquad \text{(continuity: shared apex value)}$$
$$u_N^+ = u_N^- \qquad \text{(flux matching: conserved current at the cone)}$$

The first condition excludes the discontinuous zero mode $\phi_0$. The second is the Kirchhoff condition familiar from quantum-graph vertex theory [BK].

The covering geometry selects $K = \mathrm{Id}$. The cone point $p_c$ on $M$ corresponds to a smooth pole on the covering $S^2$. Any section of $\mathcal{L}$ that lifts to a smooth function on $S^2$ is automatically regular at the pole: in the $(y, w)$ coordinates it belongs to the regular Frobenius branch ($u = a_0 + a_2\delta^2 + O(\delta^4)$, with $u' = O(\delta)$). Since $\delta = 0^+$ and $\delta = 0^-$ both correspond to the same geometric point (the pole) on the covering $S^2$, a smooth lifted function satisfies $u(0^+) = u(0^-)$ and $(|\delta|/R)\,u'(0^+) = (|\delta|/R)\,u'(0^-) = 0$. Among the self-adjoint extensions classified by [BP, Theorem 1.8], $K = \mathrm{Id}$ is the extension whose domain enforces continuity across the cone. The covering geometry selects it: any extension with $K \neq \mathrm{Id}$ would admit sections that are discontinuous at a point which is smooth on $S^2$.

### 3.6 Summary of the domain

The self-adjoint extension adopted throughout this paper is the continuous transmission extension: continuous sections across $p_c$ in every sector. For nonconstant sectors ($\mu > 0$), the transmission extension coincides with the Friedrichs extension (the repulsive potential forces vanishing or regularity at the cone). For the constant sector ($\mu = 0$), the two differ: the Friedrichs extension admits a discontinuous zero mode that the transmission extension excludes.

**Proposition (Extension classification).** On the Möbius band $M(W)$ with $0 < W < \pi R$, the continuous transmission extension of the twisted Laplacian is a self-adjoint operator on $L^2(M, dA)$ whose domain is characterized sector by sector as follows:

| Sector | Transverse eigenvalue | Indicial exponent | Endpoint type | Extension |
|---|---|---|---|---|
| Constant ($k = 0$ even) | $\mu = 0$ | $s = 0$ (double) | Limit-circle | Transmission: shared apex value. Friedrichs admits a zero mode; transmission excludes it. |
| Nonconstant, $\alpha \geq 1$ | $\mu > 0$ | $\alpha = \sqrt{\mu}\,R \geq 1$ | Limit-point | Unique. |
| Nonconstant, $0 < \alpha < 1$ | $\mu > 0$ | $\alpha = \sqrt{\mu}\,R < 1$ | Limit-circle | Friedrichs = Transmission. Singular branch has infinite form energy. |

The Friedrichs extension and the continuous transmission extension differ only in the constant sector ($\mu = 0$), where the vanishing of the angular potential removes the cone's repulsive barrier and exposes the limit-circle character of the endpoint.

---

## 4. Sector $\mathcal{A}$: Zonal Legendre Spectrum

The constant transverse mode ($k = 0$ even family, $\Phi_0^{\rm e} \equiv 1$) reduces the eigenvalue problem to a single ODE in $y$ with anti-periodic boundary conditions. This is the **zonal sector**, denoted Sector $\mathcal{A}$, whose spectrum governs the ground state in the narrow regime.

### 4.1 The reduced operator

On the constant-curvature band, the zonal eigenequation from §3.4 with $\mu = 0$ is

$$-\Delta u = -u'' + \frac{1}{R}\tan\!\left(\frac{y}{R}\right)u' = \lambda\,u \qquad \text{on } (0, \pi R),$$

with anti-periodic boundary conditions $u(\pi R) = -u(0)$ and $u'(\pi R) = -u'(0)$, and the transmission condition at the cone $y = \pi R/2$ (§3.5): continuity of $u$ and matching of the weighted flux $\lim_{\delta \to 0^+}(|\delta|/R)\,u' = \lim_{\delta \to 0^-}(|\delta|/R)\,u'$. For the regular Legendre solutions below, this common flux is zero.

### 4.2 Legendre reduction

The coordinate $y$ on the covering $S^2$ is related to the standard colatitude $\theta$ by $\theta = \pi/2 - y/R$, so that $y = 0$ corresponds to the equator ($\theta = \pi/2$) and $y = \pi R/2$ to the north pole ($\theta = 0$). The substitution

$$x = \sin(y/R) = \cos\theta$$

maps $(0, \pi R/2)$ bijectively to $(0, 1)$ and converts the zonal operator to the Legendre equation. Concretely, with $u(y) = v(\sin(y/R))$:

$$\frac{d}{dx}\!\left[(1-x^2)\frac{dv}{dx}\right] + \nu(\nu+1)\,v = 0, \qquad \lambda = \frac{\nu(\nu+1)}{R^2},$$

where $\nu \geq 0$ is a continuous spectral parameter, not a priori restricted to integers. This equation has two families of solutions: the Legendre function of the first kind $P_\nu(x)$, which satisfies $P_\nu(1) = 1$ and is regular at $x = 1$ (the cone), and the Legendre function of the second kind $Q_\nu(x)$, which diverges logarithmically as $x \to 1$.

Regularity at the cone excludes $Q_\nu$: in our coordinates, $Q_\nu(\sin(y/R)) \sim \log|\delta|$ near $\delta = 0$, which is the logarithmic Frobenius branch of §3.4 with infinite Dirichlet energy. Both the transmission and Friedrichs domains exclude it. The admissible solutions are therefore $P_\nu(\sin(y/R))$ for $\nu \geq 0$.

Since $\sin(y/R)$ maps $(0, \pi R)$ onto $(0, 1, 0)$ symmetrically about $y = \pi R/2$, each $P_\nu(\sin(y/R))$ is well-defined on the full interval and symmetric about the cone. The quantization of $\nu$ to discrete values is imposed by the anti-periodic boundary condition (§4.4).

### 4.3 The full solution space and the transmission selection

The substitution $x = \sin(y/R)$ is two-to-one: both $y$ and $\pi R - y$ map to the same $x$. It produces only solutions that are symmetric about the cone. The full solution space of the second-order zonal ODE has two branches at each eigenvalue:

| Solution family | Behavior at cone | Transmission domain? | Friedrichs domain? | Anti-periodic for |
|---|---|---|---|---|
| Symmetric: $P_\ell(\sin(y/R))$ | continuous, value $P_\ell(1) = 1$ | ✓ | ✓ | odd $\ell$ |
| Antisymmetric: $\mathrm{sgn}(\delta)\,P_\ell(\sin(y/R))$ | jumps by $2P_\ell(1) = 2$ | **excluded** | ✓ | even $\ell$ |

The antisymmetric branch satisfies the value condition $u(\pi R) = -u(0)$ for all $\ell$, but the derivative condition $u'(\pi R) = -u'(0)$ requires $P_\ell'(0) = 0$, selecting even $\ell$. The $\ell = 0$ antisymmetric row is precisely the piecewise-constant zero mode $\phi_0$ from §3.5: eigenvalue 0, anti-periodic, discontinuous at the cone. The transmission condition (continuity at $p_c$) excludes the entire antisymmetric column. A continuous antisymmetric mode would have to vanish at the cone, but both indicial exponents at $\delta = 0$ are $s = 0$ (§3.4), so no nonzero solution of the constant-sector equation vanishes there. The symmetric branch therefore exhausts the transmission spectrum of Sector $\mathcal{A}$.

In §5, the odd sectors will admit non-integer associated Legendre functions $P_\alpha^\alpha$ because the transverse potential shifts the indicial exponents away from zero, opening a fractional-power regular branch.

### 4.4 The anti-periodic selection rule

The anti-periodic condition requires $P_\nu(0) = 0$. Since $P_\nu(0) = \sqrt{\pi}/[\Gamma((1-\nu)/2)\,\Gamma(1+\nu/2)]$, this holds exactly when $(1-\nu)/2$ is a non-positive integer, giving $\nu = 1, 3, 5, \ldots$ The derivative condition $u'(\pi R) = -u'(0)$ is then automatic (the factor $\cos(y/R)/R$ in $u'$ flips sign between the two seams).

The zonal anti-periodic spectrum of Sector $\mathcal{A}$ is therefore

$$\sigma(\text{Sector } \mathcal{A}) = \left\{\frac{\ell(\ell+1)}{R^2} : \ell = 1, 3, 5, \ldots\right\}.$$

The ground eigenvalue is $\ell = 1$:

$$\lambda_0 = \frac{1 \cdot 2}{R^2} = \frac{2}{R^2} = R_{\rm sm}.$$

### 4.5 The ground eigenfunction

The $\ell = 1$ eigenfunction is $P_1(\sin(y/R)) = \sin(y/R)$, the restriction of the zonal harmonic $Y_1^0 \propto \cos\theta = \sin(y/R)$ to the band. The value condition at the seams holds because $\sin(y/R)$ vanishes there ($P_\ell(0) = 0$ for odd $\ell$, a property of odd Legendre polynomials); the derivative condition $u'(\pi R) = -u'(0) = -1/R$ is nontrivial. Within the odd-$\ell$ family, $\ell = 1$ is the smallest admissible degree, so $2/R^2$ is the sector ground eigenvalue. The eigenfunction is strictly positive on $(0, \pi R)$, belongs to the regular Frobenius branch at the cone ($u(\pi R/2) = 1$, $u'(\pi R/2) = 0$), and lies in the transmission domain of §3.5. The eigenvalue $2/R^2$ is independent of the transverse half-width $W$.

### 4.6 Comparison with the flat strip

On the flat strip (Euclidean metric, anti-periodic condition, same period $\pi R$), the ground eigenvalue is $1/R^2 = R_{\rm sm}/2$, with the same eigenfunction $\sin(y/R)$. The curvature term $(1/R)\tan(y/R)\,u'$ doubles this to $2/R^2 = R_{\rm sm}$, matching the familiar $\ell = 1$ eigenvalue on $S^2(R)$.

---

## 5. Odd Sectors and the Associated Legendre Branch

The odd transverse modes ($\Phi_j^{\rm o}$, $j = 0, 1, 2, \ldots$) produce periodic longitudinal functions (§3.4). This is the **periodic sector**, whose spectrum governs the ground state in the wide regime. In contrast to §4, the indicial exponents are nonzero and the spectral parameter is non-integer: the eigenfunctions are fractional-power associated Legendre functions rather than polynomials.

### 5.1 The reduced operator

For the $j$-th odd transverse mode with eigenvalue $\mu_j = \bigl((2j+1)\pi/(2W)\bigr)^2$, the reduced eigenequation from §3.4 is

$$-\bigl(|f|\,u'\bigr)' + \frac{\mu_j}{|f|}\,u = \lambda\,|f|\,u, \qquad f(y) = \cos(y/R),$$

on $(0, \pi R)$ with periodic boundary conditions $u(\pi R) = u(0)$, $u'(\pi R) = u'(0)$. The transmission condition at the cone (§3.5) is continuity plus matching of weighted flux; for the regular Frobenius branch at $\alpha_j > 0$, the Friedrichs and transmission extensions coincide (§3.4), and the eigenfunction vanishes at the cone.

### 5.2 The exact eigenfunction

**Claim.** The function $u = |\cos(y/R)|^{\alpha}$ with $\alpha = (2j+1)\pi R/(2W)$ satisfies the reduced equation with eigenvalue

$$\lambda = \frac{\alpha(\alpha+1)}{R^2}.$$

*Verification.* Set $r = |\cos(y/R)|$, so that $|f| = r$ and $u = r^\alpha$. On the smooth locus ($r > 0$, i.e., away from the cone), $r$ satisfies the identities

$$R^2(r')^2 = 1 - r^2, \qquad r'' = -\frac{r}{R^2},$$

which hold on both halves of the band (the absolute value introduces no sign issues because $r'' = -r/R^2$ follows from $r^2 = \cos^2(y/R)$ on each half separately). Now compute:

$$u' = \alpha\,r^{\alpha-1}\,r', \qquad |f|\,u' = \alpha\,r^{\alpha}\,r'.$$

Differentiating:

$$(|f|\,u')' = \alpha\,r^{\alpha-1}\bigl[\alpha(r')^2 + r\,r''\bigr] = \frac{\alpha}{R^2}\,r^{\alpha-1}\bigl[\alpha(1 - r^2) - r^2\bigr] = \frac{\alpha}{R^2}\,r^{\alpha-1}\bigl[\alpha - (\alpha+1)\,r^2\bigr].$$

The potential term is $\mu_j\,r^{\alpha-1}$. Assembling:

$$-\bigl(|f|\,u'\bigr)' + \frac{\mu_j}{|f|}\,u = r^{\alpha-1}\left[\frac{\alpha(\alpha+1)}{R^2}\,r^2 - \frac{\alpha^2}{R^2} + \mu_j\right].$$

With $\mu_j = \alpha^2/R^2$ (the definition $\alpha = R\sqrt{\mu_j}$), the constant terms cancel and

$$-\bigl(|f|\,u'\bigr)' + \frac{\mu_j}{|f|}\,u = \frac{\alpha(\alpha+1)}{R^2}\,r^{\alpha+1} = \frac{\alpha(\alpha+1)}{R^2}\,|f|\,u. \qquad \square$$

### 5.3 Identification as the sectoral Legendre function

Under the substitution $x = \sin(y/R)$ of §4.2, the function $|\cos(y/R)|^{\alpha} = (1 - x^2)^{\alpha/2}$ is the **sectoral associated Legendre function** $P_\alpha^\alpha(x)$ (up to a standard normalization constant depending only on $\alpha$). For non-integer $\alpha$, this is a generalized Legendre function, not a spherical harmonic in the classical sense. At the transition $\alpha = 1$, it reduces to the honest spherical harmonic $Y_1^1$ on $S^2$.

Two ingredients explain why non-integer $\alpha$ is admissible here but excluded in §4. First, the indicial exponents: in the constant sector (§4), both exponents were zero ($s^2 = 0$), and the singular $Q_\nu$ branch diverged logarithmically. In the odd sectors, the exponents are $s = \pm\alpha$ with $\alpha > 0$; the regular branch $|\delta|^{+\alpha}$ generates $P_\alpha^\alpha$, and no $Q$-type singularity arises. Second, the boundary condition: the anti-periodic condition $P_\nu(0) = 0$ in §4 forced $\nu$ to odd integers through the Gamma-function zeros. The periodic condition $u(\pi R) = u(0)$ imposes no constraint on $\alpha$, since $|\cos(y/R)|^\alpha$ evaluates to $1$ at both seams for all $\alpha$. The spectral parameter runs continuously, set by the transverse width $W$ through $\alpha = (2j+1)\pi R/(2W)$.

### 5.4 Periodicity and transmission domain

At both seams: $|\cos(0)|^\alpha = 1$ and $|\cos(\pi)|^\alpha = |-1|^\alpha = 1$, so $u(0) = u(\pi R) = 1$. The derivatives: $u'(0) = -(\alpha/R)\sin(0) = 0$ and $u'(\pi R) = -(\alpha/R)\sin(\pi) = 0$, so $u'(0) = u'(\pi R) = 0$. Both the value and derivative periodicity conditions are satisfied.

Near the cone ($\delta = y - \pi R/2 \to 0$): $|\cos(y/R)|^\alpha \sim |\delta/R|^\alpha \to 0$ for $\alpha > 0$. This is the regular Frobenius branch $|\delta|^{+\alpha}$ identified in §3.4. For all $\alpha > 0$, the eigenfunction lies in both the transmission and Friedrichs domains (§3.4, nonconstant sectors). In the wide regime ($\alpha < 1$), the eigenfunction is not $C^1$ at the cone ($|u'| \sim \alpha|\delta|^{\alpha-1}/R \to \infty$), but the Dirichlet energy $\int|f|\,(u')^2\,dy \sim \int|\delta|^{2\alpha-1}\,d\delta$ is finite for all $\alpha > 0$.

### 5.5 Ground state within the odd sectors

Set $h = r^\alpha = |\cos(y/R)|^\alpha$ and $\lambda_\alpha = \alpha(\alpha+1)/R^2$. Define the sector quadratic form $Q_j[u] = \int_0^{\pi R}\bigl(|f|\,|u'|^2 + \mu_j\,|f|^{-1}|u|^2\bigr)\,dy$. For any $u$ in the periodic form domain, writing $u = hv$ gives the identity

$$Q_j[u] - \lambda_\alpha\!\int_0^{\pi R}\!|f|\,|u|^2\,dy = \int_0^{\pi R}\!|f|\,h^2\,|v'|^2\,dy \;+\; \bigl[\text{boundary terms}\bigr].$$

The boundary terms at the seams vanish by periodicity of $u$ and $h$. At the cone, the boundary contribution is eliminated by approximating $u$ by compactly supported functions away from $p_c$ and passing to the form closure; since $|f| \to 0$ at the cone, the limiting boundary term vanishes. The right side is therefore non-negative, with equality if and only if $v' = 0$, i.e., $u \propto h$. This proves $\lambda_\alpha$ is the ground eigenvalue and $h$ is the unique ground eigenfunction (up to scalar multiples) in each odd sector.

The $j$-th odd sector has $\alpha_j = (2j+1)\pi R/(2W)$ and ground eigenvalue $\alpha_j(\alpha_j + 1)/R^2$. Since $\alpha_j$ is strictly increasing in $j$, the function $\alpha(\alpha+1)$ is increasing for $\alpha > 0$, and the global minimum across all odd sectors occurs at $j = 0$:

$$\lambda_0^{\rm odd}(W) = \frac{\alpha_0(\alpha_0 + 1)}{R^2}, \qquad \alpha_0 = \frac{\pi R}{2W}.$$

The full eigenfunction is $\psi_0^{\rm odd}(y, w) = |\cos(y/R)|^{\alpha_0}\,\sin(\pi w/2W)$.

### 5.6 The eigenvalue as a function of width

Since $\alpha_0 = \pi R/(2W)$ is decreasing in $W$ and $\alpha(\alpha+1)$ is increasing for $\alpha > 0$, the odd-sector ground eigenvalue $\alpha_0(\alpha_0+1)/R^2$ is strictly decreasing in $W$. It exceeds $2/R^2$ for $W < \pi R/2$ (where $\alpha_0 > 1$), equals $2/R^2$ at $W = \pi R/2$ (where $\alpha_0 = 1$), and falls below $2/R^2$ for $W > \pi R/2$.

At the critical width, the odd-sector eigenfunction becomes $|\cos(y/R)|\,\sin(w/R)$. On the covering $S^2$, this is the $\ell = 1$ sectoral harmonic $Y_1^1$ (up to normalization; the absolute value is an artifact of the quotient coordinates). Its eigenvalue $2/R^2$ coincides with the zonal branch $Y_1^0 \propto \sin(y/R)$: two members of the $\ell = 1$ multiplet meeting at the transition.

### 5.7 The even nonconstant sectors

The even nonconstant modes ($\Phi_k^{\rm e}$ with $k \geq 1$) produce anti-periodic longitudinal functions. The symmetric function $|\cos(y/R)|^\alpha$ is periodic, so it cannot serve these sectors directly. The correct eigenfunction is obtained by a sign flip across the cone:

$$u_k(y) = \mathrm{sgn}(\delta)\,|\cos(y/R)|^{\alpha_k}, \qquad \alpha_k = \frac{k\pi R}{W}, \qquad \delta = y - \frac{\pi R}{2}.$$

This function is anti-periodic at the seams: $u_k(0) = -1$ and $u_k(\pi R) = +1 = -u_k(0)$, with both seam derivatives vanishing. It is continuous at the cone because the sign flip multiplies a vanishing factor ($|\cos(y/R)|^{\alpha_k} \to 0$ as $\delta \to 0$), so $u_k \to 0$ from both sides; the weighted flux likewise vanishes, and no distributional contribution appears. The eigenfunction lies in the transmission domain.

On each smooth half, $|\cos(y/R)|^{\alpha_k}$ satisfies the reduced equation with eigenvalue $\alpha_k(\alpha_k + 1)/R^2$ (the same computation as §5.2, with $\mathrm{sgn}(\delta) = \pm 1$ constant on each half). To confirm minimality: restrict to the half-interval $(0, \pi R/2)$ with Neumann condition at the seam and the regular Frobenius condition at the cone. On this half, $|\cos(y/R)|^{\alpha_k}$ is positive and nodeless, so it is the ground state of the half-interval problem. The anti-periodic gluing across the cone produces the unique single-node mode, the lowest eigenfunction compatible with anti-periodic boundary conditions. (The sign change at the cone is precisely why the positive ground-state transform of §5.5 cannot be applied directly; the half-interval reduction circumvents this.) Since $k \geq 1$ and $0 < W < \pi R$, the exponent satisfies $\alpha_k = k\pi R/W \geq \pi R/W > 1$, giving $\alpha_k(\alpha_k + 1)/R^2 > 2/R^2$: every even nonconstant sector lies strictly above the zonal branch for all $W$.

### 5.8 Sector ground states

All three sector families now have closed-form ground states:

| Sector | Transverse mode | Longitudinal BC | Ground eigenfunction | $\alpha$ | Ground eigenvalue |
|---|---|---|---|---|---|
| Constant ($k = 0$) | $1$ | anti-periodic | $\sin(y/R)$ ($\ell = 1$ zonal) | — | $2/R^2$ |
| Odd ($j$) | $\sin\!\bigl(\frac{(2j+1)\pi w}{2W}\bigr)$ | periodic | $|\cos(y/R)|^{\alpha_j}$ | $\frac{(2j+1)\pi R}{2W}$ | $\frac{\alpha_j(\alpha_j+1)}{R^2}$ |
| Even nonconstant ($k \geq 1$) | $\cos\!\bigl(\frac{k\pi w}{W}\bigr)$ | anti-periodic | $\mathrm{sgn}(\delta)\,|\cos(y/R)|^{\alpha_k}$ | $\frac{k\pi R}{W}$ | $\frac{\alpha_k(\alpha_k+1)}{R^2}$ |

The sector comparison that yields the main theorem is carried out in §6.

---

## 6. The Global Ground-State Transition

**Theorem.** On the Möbius band $M(W)$ with half-width $0 < W < \pi R$ and the continuous transmission extension, the ground eigenvalue of the twisted Laplacian is

$$\lambda_0(W) = \begin{cases} 2/R^2 & \text{if } 0 < W \leq \pi R/2, \\[4pt] \dfrac{\alpha(\alpha+1)}{R^2}, \quad \alpha = \dfrac{\pi R}{2W} & \text{if } \pi R/2 < W < \pi R. \end{cases}$$

At $W = \pi R/2$ both branches give $2/R^2$, and the ground eigenvalue is doubly degenerate.

*Proof.* The metric coefficient $\cos^2(y/R)$ multiplying $\psi_{ww}$ depends on $y$ alone, so the twisted Laplacian commutes with the transverse Laplacian and the spectrum decomposes as an orthogonal direct sum over the transverse sectors of §3.4. The resolvent is compact (the surface is compact with the extension fixed), so the global ground eigenvalue equals the minimum of the sector ground eigenvalues. By the sector ground states of §5.8:

**(i) Constant sector.** Ground eigenvalue $2/R^2$, independent of $W$ (§4.5).

**(ii) Odd sectors.** Ground eigenvalue $\alpha_j(\alpha_j + 1)/R^2$ with $\alpha_j = (2j+1)\pi R/(2W)$, minimized at $j = 0$ (§5.5). The minimum is $\alpha_0(\alpha_0 + 1)/R^2$ with $\alpha_0 = \pi R/(2W)$.

**(iii) Even nonconstant sectors.** Ground eigenvalue $\alpha_k(\alpha_k + 1)/R^2$ with $\alpha_k = k\pi R/W \geq \pi R/W > 1$ for all $k \geq 1$ and $W < \pi R$. This is the exact sector minimum established by the half-interval Neumann argument of §5.7, and the sharp $+1$ in $\alpha_k(\alpha_k + 1)$ is essential: a cruder potential-only bound gives $\alpha_k^2/R^2$, which fails to clear $2/R^2$ when $\alpha_k \in (1, \sqrt{2})$. Since $\alpha_k > 1$, the exact expression gives $\alpha_k(\alpha_k + 1)/R^2 > 1 \cdot 2/R^2 = 2/R^2$.

The global ground eigenvalue is therefore $\lambda_0 = \min(2/R^2,\;\alpha_0(\alpha_0+1)/R^2)$. The function $\alpha \mapsto \alpha(\alpha+1)$ is increasing for $\alpha > 0$, and $\alpha_0 = \pi R/(2W)$ is decreasing in $W$, so $\alpha_0(\alpha_0+1)$ is strictly decreasing in $W$. The comparison:

- $W < \pi R/2 \implies \alpha_0 > 1 \implies \alpha_0(\alpha_0+1) > 2 \implies$ the zonal mode wins.
- $W = \pi R/2 \implies \alpha_0 = 1 \implies \alpha_0(\alpha_0+1) = 2 \implies$ both branches tie.
- $W > \pi R/2 \implies \alpha_0 < 1 \implies \alpha_0(\alpha_0+1) < 2 \implies$ the odd-sector mode wins.

The even nonconstant sectors are strictly above $2/R^2$ throughout and never compete. $\square$

**Corollary (Degeneracy at the transition).** At $W = \pi R/2$, the ground eigenspace is exactly two-dimensional. The only sector minima attaining $2/R^2$ are the constant sector ($\ell = 1$ zonal, §4.5) and the $j = 0$ odd sector ($\alpha_0 = 1$, §5.5); the next odd sector ($j = 1$) gives $3 \cdot 4/R^2 = 12/R^2$, and the lowest even sector ($k = 1$) gives $2 \cdot 3/R^2 = 6/R^2$. The two ground-state modes are

$$\psi_1 = \sin(y/R), \qquad \psi_2 = |\cos(y/R)|\,\sin(w/R).$$

On the smooth covering $S^2$, these correspond to $Y_1^0$ and a $Y_1^1$-type sectoral mode (the absolute value is an artifact of the quotient coordinates; the covering function is $\cos(y/R)\,\sin(w/R)$). Away from $W = \pi R/2$, the ground eigenvalue is simple.

**Corollary (Sign-changing ground state).** For $W > \pi R/2$, the ground eigenfunction $|\cos(y/R)|^{\alpha_0}\sin(\pi w/2W)$ changes sign: the transverse factor $\sin(\pi w/2W)$ is odd in $w$. This contrasts with the narrow regime ($W < \pi R/2$), where the ground eigenfunction $\sin(y/R)$ is positive on the interior. Because $\mathcal{L}$ is nontrivial, no section admits a globally positive representative, and the Perron-Frobenius nodeless-ground argument does not apply. The implications are discussed in §7.

---

## 7. Discussion

The theorem rests on the transmission extension (§3.5), which enforces continuity at the cone. The Friedrichs extension, by contrast, admits the full antisymmetric tower in the constant sector: the even-degree modes $\mathrm{sgn}(\delta)\,P_\ell(\sin(y/R))$ for $\ell = 0, 2, 4, \ldots$, with eigenvalues $\{0, 6/R^2, 20/R^2, \ldots\}$. All of these jump at the cone and are excluded by the transmission condition. Among them, only the $\ell = 0$ zero mode sits below the zonal ground $2/R^2$; the next antisymmetric mode, at $6/R^2$, already exceeds it. Continuity at the cone therefore raises the constant-sector ground from $0$ to $2/R^2$, while the nonconstant sectors, where both extensions agree, supply the width-dependent branch through the sector comparison of §6.

The sign-changing ground state in the wide regime deserves comment. On an orientable surface, the Perron-Frobenius theorem guarantees a positive ground eigenfunction. On $M(W)$, this argument is unavailable: a nowhere-vanishing section would trivialize $\mathcal{L}$, so every continuous section must vanish somewhere, and no positivity cone is preserved by the semigroup. The two regimes have different nodal structures: for $W > \pi R/2$, the ground eigenfunction changes sign across $w = 0$; for $W < \pi R/2$, the eigenfunction $\sin(y/R)$ is positive on the covering rectangle but changes sign under the Möbius identification, with the nodal set on the core loop.

Several natural directions are not pursued here. A Lichnerowicz-type lower bound adapted to the singular surface $M(W)$ would provide a geometric reinterpretation of the narrow-regime eigenvalue $2/R^2 = R_{\rm sm}$, but it is not an input to the proof. The full spectrum (higher eigenvalues within each sector and their interleaving) involves quantization conditions for the associated Legendre equation with non-integer parameters. The KKZ thin-strip limit ($W \to 0$) and the flat limit ($R \to \infty$) are asymptotic regimes where the present closed-form results should make contact with known formulas.

---

## References

- [Friedrichs] K. Friedrichs. Spektraltheorie halbbeschränkter Operatoren. *Math. Ann.* 109 (1934), 465--487.
- [KSWW] H. Kalf, U.-W. Schmincke, J. Walter, and R. Wüst. On the spectral theory of Schrödinger and Dirac operators with strongly singular potentials. *Lecture Notes in Math.* 448, Springer, 1975.
- [RS] M. Reed and B. Simon. *Methods of Modern Mathematical Physics II: Fourier Analysis, Self-Adjointness*. Academic Press, 1975.
- [Cheeger1979] J. Cheeger. On the spectral geometry of spaces with cone-like singularities. *Proc. Nat. Acad. Sci. USA* 76 (1979), 2103--2106.
- [Cheeger1983] J. Cheeger. Spectral geometry of singular Riemannian spaces. *J. Differential Geom.* 18 (1983), 575--657.
- [BS] J. Brüning and R. Seeley. Regular singular asymptotics. *Adv. Math.* 58 (1985), 133--148.
- [Weidmann] J. Weidmann. *Spectral Theory of Ordinary Differential Operators*. Springer LNM 1258, 1987.
- [BK] G. Berkolaiko and P. Kuchment. *Introduction to Quantum Graphs*. AMS, 2013.
- [BP] U. Boscain and D. Prandi. Self-adjoint extensions and stochastic completeness of the Laplace-Beltrami operator on conic and anticonic surfaces. *J. Math. Pures Appl.* 104 (2015), 1080--1114.
- [KKZ] T. Kalvoda, D. Krejčiřík, and K. Zahradová. Effective quantum dynamics on the Möbius strip. *J. Phys. A* 53 (2020), 375201.

---

/ **[`main`](../../README.md)** / **[`framework`](../framework/)** / **[`cosmos`](../cosmos/)** / **[`spectrum`](../spectrum/)** /
