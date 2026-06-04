/ **[`main`](../../README.md)** / **[`framework`](../framework/)** / **[`cosmos`](../cosmos/)** / **[`spectrum`](../spectrum/)** /

---

# Ground-State Transition for the Twisted Laplacian on a Constant-Curvature Möbius Band

On the constant-curvature Möbius band $M(W)$ constructed from a spherical band on $S^2 \subset S^3$ with half-width $W$, the twisted Laplacian is equipped with the continuous transmission extension (continuous sections across the cone apex in every sector). The ground eigenvalue exhibits a width-dependent transition:

$$\lambda_0(W) = \begin{cases} 2/R^2 & W \leq \pi R/2 \quad \text{(cone angle} \leq \pi\text{)} \\ \alpha(\alpha+1)/R^2 & W > \pi R/2 \quad \text{(cone angle} > \pi\text{)} \end{cases}$$

where $\alpha = \pi R/(2W)$. The transition occurs at $W = \pi R/2$, where both branches give $2/R^2$ and the ground eigenvalue is doubly degenerate. Both branches are realized by explicit eigenfunctions: $\sin(y/R)$ (the $\ell = 1$ zonal harmonic) for the narrow regime, and $|\cos(y/R)|^\alpha \sin(\pi w/2W)$ (the sectoral associated Legendre function $P_\alpha^\alpha$) for the wide regime.

---

## 1. Introduction

*To be drafted. State main theorem, width transition, novelty, relation to Kalvoda-Krejčiřík-Zahradová. No cosmology.*

---

## 2. The Geometric Model $M(W)$

*To be drafted. Spherical band on $S^2 \subset S^3$, Möbius edge gluing, metric $ds^2 = dy^2 + \cos^2(y/R)\,dw^2$, boundary $\partial M = S^1$, cone point at $y = \pi R/2$, smooth-locus curvature $R_{\rm sm} = 2/R^2$, $\tau$ as involutive isometry with fixed point at apex, cone topology and local model.*

---

## 3. Twisted Sections and the Operator Domain

### 3.1 The orientation line bundle

The Möbius band $M(W)$ is non-orientable. A smooth function on the covering band $\widetilde{M} = [0, \pi R] \times [-W, W]$ descends to a section of the orientation line bundle $\mathcal{L} \to M$ if and only if it satisfies the equivariance condition

$$\psi(\pi R, -w) = -\psi(0, w) \qquad \text{for all } w \in [-W, W].$$

This sign reversal is the defining property of sections of $\mathcal{L}$: traversing the core loop once reverses the orientation, so a section of the orientation bundle picks up a factor of $-1$.

The **twisted Laplacian** is the Laplace-Beltrami operator acting on sections of $\mathcal{L}$. It is the standard Laplace-Beltrami operator on the smooth locus; the adjective "twisted" refers to the domain (anti-periodic sections) rather than to a modification of the operator itself. The eigenvalue problem $-\Delta\psi = \lambda\psi$ is posed for sections of $\mathcal{L}$ throughout this paper.

### 3.2 The formal operator

On the smooth locus $M^\circ = M \setminus \{p_c\}$ (where $p_c$ denotes the cone point at $y = \pi R/2$), the Laplace-Beltrami operator associated to the metric $ds^2 = dy^2 + f(y)^2\,dw^2$ with $f(y) = \cos(y/R)$ is

$$\Delta\psi = \psi_{yy} + \frac{f'}{f}\psi_y + \frac{1}{f^2}\psi_{ww} = \psi_{yy} - \frac{1}{R}\tan\!\left(\frac{y}{R}\right)\psi_y + \frac{1}{\cos^2(y/R)}\psi_{ww}.$$

The area element is $dA = |f(y)|\,dy\,dw$, and $L^2(M, dA)$ denotes the Hilbert space of square-integrable sections of $\mathcal{L}$ with respect to this measure. (The metric coefficient is $f^2 = \cos^2(y/R) \geq 0$ throughout; the signed function $f = \cos(y/R)$ changes sign at the cone $y = \pi R/2$, so the Riemannian density $\sqrt{\det g} = |f|$ carries the absolute value.)

The boundary $\partial M$ consists of two geodesic arcs at $w = \pm W$. We impose Neumann boundary conditions:

$$\partial_w\psi\big|_{w = \pm W} = 0.$$

These boundary arcs are geodesics of the surface: $y$-curves satisfy $\nabla_{\partial_y}\partial_y = 0$, so their geodesic curvature vanishes ($\kappa_g = 0$).

**Comparison with Kalvoda-Krejčiřík-Zahradová.** Kalvoda, Krejčiřík, and Zahradová [KKZ] study the Laplace-Beltrami operator on a Möbius strip embedded as a ruled surface in $\mathbb{R}^3$, with Dirichlet boundary conditions, in the thin-strip limit $W \to 0$. The present setting differs in three respects: the surface has constant Gaussian curvature $K = 1/R^2$ (inherited from the totally geodesic embedding $S^2 \subset S^3$), Neumann rather than Dirichlet boundary conditions are imposed, and the analysis is exact for all $0 < W < \pi R$ rather than asymptotic in the thin-strip limit.

### 3.3 The involution and the cone point

The map

$$\tau(y, w) = (\pi R - y,\; -w)$$

is an involutive isometry of the covering band $\widetilde{M}$ with a unique fixed point at $(\pi R/2, 0)$, which is the cone point $p_c$. The Möbius identification is the restriction of $\tau$ to the boundary edges $\{0\} \times [-W, W]$ and $\{\pi R\} \times [-W, W]$.

The map $\tau$ is not a deck transformation. A deck transformation of a covering space acts freely (no fixed points). Since $\tau$ fixes $p_c$, it is an involutive isometry, not a deck transformation. The orientation bundle and the anti-periodic holonomy are tied to the core loop of the Möbius band, not to $\tau$ itself.

At the cone point, $f(\pi R/2) = \cos(\pi/2) = 0$. Setting $\delta = y - \pi R/2$:

$$f(y) = \cos(y/R) = -\sin(\delta/R) \quad \Longrightarrow \quad |f| \sim \frac{|\delta|}{R} \quad \text{as } \delta \to 0.$$

The transverse circle of circumference $2W|f(y)|$ collapses to a point. On the covering $S^2 \subset S^3$, the coordinate $y = \pi R/2$ is a smooth pole; on the edge-identified Möbius band, the same collapse produces a conical singularity with cone angle $2W/R$.

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

**Parity coupling to the longitudinal condition.** The Möbius identification $\psi(\pi R, -w) = -\psi(0, w)$ interacts with the transverse parity as follows. For even $\Phi(w) = \Phi(-w)$, the identification gives $u(\pi R)\Phi(w) = -u(0)\Phi(w)$, forcing $u(\pi R) = -u(0)$: the longitudinal function is **anti-periodic**. For odd $\Phi(-w) = -\Phi(w)$, the identification gives $u(\pi R)(-\Phi(w)) = -u(0)\Phi(w)$, forcing $u(\pi R) = u(0)$: the longitudinal function is **periodic**.

**Correspondence with Boscain-Prandi.** A Neumann eigenmode on $[-W, W]$ extends by even reflection to a periodic function on a circle of circumference $4W$. Under this unfolding, the even family $\Phi_k^{\rm e}$ corresponds to Fourier modes $e^{i(2k)\theta}$ (even harmonics) and the odd family $\Phi_j^{\rm o}$ to $e^{i(2j+1)\theta}$ (odd harmonics) on that circle. The $n = 0$ constant mode is therefore the analogue of the $k = 0$ Fourier sector in [BP], and the non-essential-self-adjointness of $\hat\Delta_0$ at the cone (Theorem 1.6(ii) of [BP]) is the same phenomenon in both settings. The Neumann interval replaces the circle; the local analysis at the cone is identical.

In each sector, the reduced eigenequation for the longitudinal function $u(y)$ takes the Sturm-Liouville form

$$-\bigl(|f|\,u'\bigr)' + \frac{\mu}{|f|}\,u = \lambda\,|f|\,u, \qquad f(y) = \cos(y/R),$$

on $L^2\bigl((0, \pi R),\,|f|\,dy\bigr)$, where $\mu$ is the transverse eigenvalue of the sector. Near the cone ($\delta \to 0$, $|f| \sim |\delta|/R$), this becomes

$$-\left(\frac{|\delta|}{R}\,u'\right)' + \frac{\mu R}{|\delta|}\,u = \lambda\,\frac{|\delta|}{R}\,u.$$

**Frobenius analysis.** Substituting $u = |\delta|^s$ into the leading-order balance gives the indicial equation

$$s^2 = \mu R^2.$$

**The constant sector ($\mu = 0$, even family $k = 0$).** The indicial equation gives $s^2 = 0$ (double root). The two local solutions are

$$u_1 = a_0 + a_2\delta^2 + O(\delta^4), \qquad u_2 = \log|\delta| + b_2\delta^2 + O(\delta^4).$$

Both are square-integrable against the weight $|\delta|/R\,d\delta$: $\int |\delta|^0 \cdot |\delta|\,d\delta < \infty$ and $\int (\log|\delta|)^2 \cdot |\delta|\,d\delta < \infty$. The cone is a **limit-circle** endpoint.

**Nonconstant sectors with $\alpha \geq 1$.** Write $\alpha = \sqrt{\mu}\,R$ for the indicial exponent. For the lowest odd mode ($j = 0$), $\mu = (\pi/(2W))^2$ and $\alpha = \pi R/(2W)$; for the lowest nonconstant even mode ($k = 1$), $\alpha = \pi R/W$. Higher modes have proportionally larger $\alpha$. The threshold $\alpha = 1$ corresponds to $W = \pi R/2$ for the $j = 0$ odd mode and $W = \pi R$ for the $k = 1$ even mode. When $\alpha \geq 1$, the singular branch $|\delta|^{-\alpha}$ fails the $L^2$ condition against the weight $|\delta|/R\,d\delta$:

$$\int u^2\,|f|\,d\delta \sim \int |\delta|^{-2\alpha} \cdot |\delta|\,d\delta = \int |\delta|^{1-2\alpha}\,d\delta = \infty \qquad \text{for } \alpha \geq 1.$$

The cone is **limit-point**. Self-adjointness is unique; no extension choice arises.

**Nonconstant sectors with $0 < \alpha < 1$.** This regime occurs only for wide bands: $W > \pi R/2$ for the $j = 0$ odd mode, $W > \pi R$ (impossible) for the $k = 1$ even mode. Both branches $|\delta|^{\pm\alpha}$ are now $L^2$ against the weight (since $1 - 2\alpha > -1$). The cone is **limit-circle**. The branches are distinguished by the Dirichlet energy (the quadratic form integral). For the singular branch $u = |\delta|^{-\alpha}$, the derivative is $u' = -\alpha\,|\delta|^{-\alpha-1}\,\mathrm{sgn}(\delta)$, giving $(u')^2 = \alpha^2\,|\delta|^{-2\alpha-2}$. The Dirichlet integral is:

$$\int (u')^2\,|f|\,d\delta \sim \int \alpha^2\,|\delta|^{-2\alpha-2} \cdot |\delta|\,d\delta = \alpha^2\!\int |\delta|^{-2\alpha-1}\,d\delta = \infty \qquad \text{for all } \alpha > 0.$$

The exponent $-2\alpha - 1 < -1$ for every $\alpha > 0$, so this divergence holds throughout the limit-circle regime. The Friedrichs extension excludes the singular branch by requiring finite Dirichlet integral, selecting the regular solution $|\delta|^{+\alpha}$. The regular eigenfunction $|\delta|^{\alpha} = |\cos(y/R)|^{\alpha}$ vanishes at the cone; continuity there is automatic. The Friedrichs extension and the continuous transmission extension coincide. (The function $|\cos(y/R)|^\alpha$ for non-integer $\alpha \in (0,1)$ is the sectoral associated Legendre function $P_\alpha^\alpha$ restricted to the band; its properties are developed in §6.)

**Locality of the classification.** The limit-point/limit-circle classification at a singular endpoint depends only on the local behavior of the coefficients [Weidmann]. Near $p_c$, the weight $|f|$ vanishes linearly in $\delta$, matching the flat-cone case $\alpha = -1$ in the notation of Boscain and Prandi [BP]. Their Theorem 1.6(ii) establishes that for $\alpha \in (-3, -1]$ on the model cone $ds^2 = dx^2 + |x|^{-2\alpha}\,d\theta^2$, only the $k = 0$ Fourier component fails to be essentially self-adjoint. Since the limit-circle/limit-point distinction is local, the same conclusion transfers to the constant-curvature Möbius band: the global curvature $K = 1/R^2$ modifies the eigenvalues but does not alter the self-adjoint extension classification at the cone.

**Lemma (Vanishing of nonconstant modes at the cone).** Let $\psi(y,w) = u(y)\,\Phi(w)$ be a section of $\mathcal{L}$ that is continuous on $M(W)$, where $\Phi$ is any nonconstant Neumann transverse eigenmode (from either the even family $\Phi_k^{\rm e}$ with $k \geq 1$ or the odd family $\Phi_j^{\rm o}$ with $j \geq 0$). Then $u(\pi R/2) = 0$.

*Proof.* At the cone point $p_c$, the metric coefficient $f(y) = \cos(y/R)$ vanishes, collapsing the entire transverse fiber $\{y = \pi R/2\} \times [-W, W]$ to a single geometric point. A continuous section must take a single well-defined value at $p_c$. The transverse eigenfunction $\Phi(w)$ is nonconstant: it takes distinct values at distinct $w$-positions. A product $u(\pi R/2) \cdot \Phi(w)$ with $u(\pi R/2) \neq 0$ would assign multiple values to the single point $p_c$, contradicting continuity. Therefore $u(\pi R/2) = 0$.

For the constant mode $\Phi_0^{\rm e} \equiv 1$, the product $u(\pi R/2) \cdot 1$ assigns a single value to $p_c$ regardless of $w$. The constant sector is the only sector where a nonzero apex value is compatible with continuity.

This lemma is the geometric reason that the Friedrichs and transmission extensions differ only in the constant sector: for nonconstant modes, continuity at $p_c$ already forces $u(p_c) = 0$, which is guaranteed by the regular Frobenius branch ($|\delta|^{\alpha} \to 0$ for $\alpha > 0$) selected by the Friedrichs extension. The two extensions impose the same condition and therefore coincide. For the constant sector, continuity permits a nonzero apex value, and the question of whether $u$ must be continuous across $p_c$ (transmission) or may jump (Friedrichs) becomes the live distinction.

### 3.5 The continuous transmission extension

The analysis of §3.4 shows that an extension choice arises only in the constant sector ($\mu = 0$), where both local solutions are $L^2$. The two canonical choices are:

**The Friedrichs extension.** In the constant sector ($\mu = 0$), the Friedrichs extension is characterized by Theorem 1.8 of [BP] (applied at $\alpha = -1$): its domain consists of functions $u \in D_{\max}(\hat\Delta_0)$ satisfying

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

**Why $K = \mathrm{Id}$ is forced by the covering geometry.** The cone point $p_c$ on $M$ corresponds to a smooth pole on the covering $S^2 \subset S^3$. Any section of $\mathcal{L}$ that lifts to a smooth function on $S^2$ is automatically regular at the pole: in the $(y, w)$ coordinates it belongs to the regular Frobenius branch ($u = a_0 + a_2\delta^2 + O(\delta^4)$, with $u' = O(\delta)$). Since $\delta = 0^+$ and $\delta = 0^-$ both correspond to the same geometric point (the pole) on the covering $S^2$, a smooth lifted function satisfies $u(0^+) = u(0^-)$ and $(|\delta|/R)\,u'(0^+) = (|\delta|/R)\,u'(0^-) = 0$. These are exactly the transmission conditions with $K = \mathrm{Id}$: any other $K \in \mathrm{SL}_2(\mathbb{R})$ would force the lifted function to have either a value discontinuity or a logarithmic singularity at the pole, contradicting the smoothness of $S^2$. Moreover, the smooth $\mathcal{L}$-sections on the closed covering $S^2$ form a core for the Laplacian (their closure in the graph norm exhausts the maximal domain of the transmission extension), so the transmission extension is the unique self-adjoint extension whose domain contains all smooth lifted sections.

### 3.6 Summary of the domain

The self-adjoint extension adopted throughout this paper is the continuous transmission extension: continuous sections across $p_c$ in every sector. For nonconstant sectors ($\mu > 0$), the transmission extension coincides with the Friedrichs extension (the repulsive potential forces vanishing or regularity at the cone). For the constant sector ($\mu = 0$), the two differ: the Friedrichs extension admits a discontinuous zero mode that the transmission extension excludes.

**Proposition (Extension classification).** On the Möbius band $M(W)$ with $0 < W < \pi R$, the continuous transmission extension of the twisted Laplacian is a self-adjoint operator on $L^2(M, dA)$ whose domain is characterized sector by sector as follows:

| Sector | Transverse eigenvalue | Indicial exponent | Endpoint type | Extension |
|---|---|---|---|---|
| Constant ($k = 0$ even) | $\mu = 0$ | $s = 0$ (double) | Limit-circle | Transmission: shared apex value. Friedrichs admits a zero mode; transmission excludes it. |
| Nonconstant, $\alpha \geq 1$ | $\mu > 0$ | $\alpha = \sqrt{\mu}\,R \geq 1$ | Limit-point | Unique. |
| Nonconstant, $0 < \alpha < 1$ | $\mu > 0$ | $\alpha = \sqrt{\mu}\,R < 1$ | Limit-circle | Friedrichs = Transmission. Singular branch has infinite form energy. |

The Friedrichs extension and the continuous transmission extension differ only in the constant sector ($\mu = 0$), where the vanishing of the angular potential removes the cone's repulsive barrier and exposes the limit-circle character of the endpoint.

**Zero capacity at the cone.** The operator-theoretic reason the Friedrichs extension admits a discontinuous mode is that the cone point has **zero capacity** in the constant sector. The Liouville transform $x = \int^y dy'/|f(y')|$ converts the Sturm-Liouville equation into a standard Schrödinger form on the transformed coordinate. Near $y = \pi R/2$, $|f| = |\cos(y/R)| \sim |\delta|/R$, so

$$x = \int \frac{d\delta}{|\delta|/R} = R\log|\delta| + \text{const},$$

which diverges logarithmically as $\delta \to 0$. The Liouville transform maps the cone point to $x = +\infty$. In Sturm-Liouville theory, the capacity of a boundary point is measured by the **resistance integral** $\int_c^\infty dx/p(x)$: when this integral diverges, the boundary has zero capacity. For the constant sector with $\mu = 0$, the transformed equation has $p = 1$ and the resistance integral diverges (the cone is at $x = +\infty$). For nonconstant sectors with $\mu > 0$, the repulsive potential $\mu R/|\delta|$ in the original coordinate becomes a confining barrier in the Liouville coordinate, and the endpoint classification changes from limit-circle to limit-point (for $\alpha \geq 1$), making the extension unique.

This zero-capacity property explains why the Friedrichs form closure does not impose equality of the two one-sided apex values: the form domain decomposes over the two halves, giving the "disjoint dynamics" of [BP, Theorem 1.8].

### 3.7 Literature

**Cone singularities (Cheeger).** The foundational theory of the Laplacian on spaces with cone-like singularities is due to Cheeger [Cheeger1979, Cheeger1983], who showed that the Friedrichs extension of the Laplacian on a manifold with an isolated conical singularity is self-adjoint, and that the deficiency indices are determined by the link geometry and the cone angle. Our setting is a specific instance: a 2-dimensional surface with a single cone point whose link is a circle of length $2W/R$.

**Conic and anticonic surfaces (Boscain-Prandi).** Boscain and Prandi [BP] classify the self-adjoint extensions of the Laplace-Beltrami operator on the model surface $ds^2 = dx^2 + |x|^{-2\alpha}\,d\theta^2$, $\theta \in \mathbb{T}$. Our cone corresponds to their $\alpha = -1$ case (linear vanishing of the weight). Their Theorem 1.6(ii) establishes that only the $k = 0$ Fourier sector fails to be essentially self-adjoint, and their Theorem 1.8 classifies the extensions of that sector into disjoint and mixed families. Our continuous transmission extension is their bridging extension (Remark 1.9 of [BP]). The present paper extends their model-cone analysis to the constant-curvature setting, where the global geometry modifies the eigenvalues but the local classification at the singular point is unchanged.

**Regular singular operators (Brüning-Seeley).** Brüning and Seeley [BS] develop the Frobenius-type asymptotic theory for elliptic operators near conical singularities, establishing the structure of the maximal domain as a direct sum of the minimal domain and a finite-dimensional space spanned by the singular and regular branches. Our decomposition in §3.4 is a concrete instance of their general framework.

**Inverse-square potentials (Kalf-Schmincke-Walter-Wüst).** For nonconstant sectors ($\mu > 0$), the reduced equation near the cone takes the form of a Schrödinger operator with an inverse-distance potential $\mu R/|\delta|$. The self-adjoint extension theory for such potentials is classical; see [KSWW] and Reed-Simon [RS, Theorem X.10]. The critical coupling in the Calogero-type classification corresponds in our setting to $\alpha = \sqrt{\mu}\,R = 1$, which is the boundary between the limit-point and limit-circle regimes.

**Quantum-graph vertex conditions.** The transmission condition at the cone is analogous to the standard Kirchhoff (or free) vertex condition in quantum-graph theory [BK]: continuity of the function and conservation of current at a graph vertex. The cone point plays the role of a graph vertex connecting the two halves of the band. The Friedrichs extension, which decouples the halves, is the analogue of Dirichlet (absorbing) vertex conditions.

**What is claimed here.** The general phenomenon, that a conical singularity on a non-orientable surface can admit a discontinuous zero mode in the Friedrichs extension, is a specific instance of the theories above. What the present paper contributes is the specific realization on the constant-curvature Möbius band: an interior cone disconnecting a non-orientable surface, manufacturing a zero mode in the twisted anti-periodic setting, whose exclusion by the transmission extension determines the ground-state spectrum for all widths.

---

## 4. Separation into Transverse Sectors

*To be drafted. Neumann modes in $w$, parity coupling: even $n$ → anti-periodic $y$, odd $n$ → periodic $y$, reduced Sturm-Liouville problems.*

---

## 5. Sector $\mathcal{A}$: Zonal Legendre Spectrum

*To be drafted. Flat strip baseline as one-paragraph motivation, Legendre reduction, spectrum $\{\ell(\ell+1)/R^2 : \ell \text{ odd}\}$, ground $\ell = 1 = Y_1^0$ restricted to band, eigenvalue $2/R^2$.*

---

## 6. Odd Sectors and the Associated Legendre Branch

*To be drafted. Exact eigenfunction $|\cos|^{\alpha_n} = P_{\alpha_n}^{\alpha_n}$, eigenvalue $\alpha_n(\alpha_n+1)/R^2$, ground-state transform proof, $n = 1$ minimizes odd sectors.*

---

## 7. The Global Ground-State Transition

*To be drafted. Assemble sector comparison, even $n \geq 2$ bounded below by min-max, main theorem: $\lambda_0(W) = \min(2/R^2,\, \alpha(\alpha+1)/R^2)$, crossover at $W = \pi R/2$.*

---

## 8. Rayleigh Quotient Verification

*To be drafted. Short direct check of the zonal branch.*

---

## 9. Bochner Lower Bound

*To be drafted. Supplementary geometric confirmation for the $R_{\rm sm}$ branch via Lichnerowicz-Obata on a singular surface. Validity boundary at $\alpha = 1$ coincides with spectral transition. Not the backbone of the theorem.*

---

## 10. Equality, Degeneracy, and Sharpness

*To be drafted. Hessian equality for zonal mode, double degeneracy at $W = \pi R/2$, simplicity away from transition.*

---

## 11. Discussion

*To be drafted. $\mathbb{RP}^2$ limit discontinuity, extension phenomenon, sign-changing ground state and Perron-Frobenius, relation to prior work.*

---

## 12. Conclusion

*To be drafted.*

---

## References

- [Friedrichs] K. Friedrichs. Spektraltheorie halbbeschränkter Operatoren. *Math. Ann.* 109 (1934), 465--487.
- [Obata] M. Obata. Certain conditions for a Riemannian manifold to be isometric with a sphere. *J. Math. Soc. Japan* 14 (1962), 333--340.
- [KSWW] H. Kalf, U.-W. Schmincke, J. Walter, and R. Wüst. On the spectral theory of Schrödinger and Dirac operators with strongly singular potentials. *Lecture Notes in Math.* 448, Springer, 1975.
- [RS] M. Reed and B. Simon. *Methods of Modern Mathematical Physics II: Fourier Analysis, Self-Adjointness*. Academic Press, 1975.
- [Reilly] R.C. Reilly. Applications of the Hessian operator in a Riemannian manifold. *Indiana Univ. Math. J.* 26 (1977), 459--472.
- [Cheeger1979] J. Cheeger. On the spectral geometry of spaces with cone-like singularities. *Proc. Nat. Acad. Sci. USA* 76 (1979), 2103--2106.
- [Cheeger1983] J. Cheeger. Spectral geometry of singular Riemannian spaces. *J. Differential Geom.* 18 (1983), 575--657.
- [Chavel] I. Chavel. *Eigenvalues in Riemannian Geometry*. Academic Press, 1984.
- [BS] J. Brüning and R. Seeley. Regular singular asymptotics. *Adv. Math.* 58 (1985), 133--148.
- [Weidmann] J. Weidmann. *Spectral Theory of Ordinary Differential Operators*. Springer LNM 1258, 1987.
- [Escobar] J.F. Escobar. Uniqueness theorems on conformal deformation of metrics, Sobolev inequalities, and an eigenvalue estimate. *Comm. Pure Appl. Math.* 43 (1990), 857--883.
- [Zettl] A. Zettl. *Sturm-Liouville Theory*. AMS, 2005.
- [BK] G. Berkolaiko and P. Kuchment. *Introduction to Quantum Graphs*. AMS, 2013.
- [BP] U. Boscain and D. Prandi. Self-adjoint extensions and stochastic completeness of the Laplace-Beltrami operator on conic and anticonic surfaces. *J. Math. Pures Appl.* 104 (2015), 1080--1114.
- [KKZ] T. Kalvoda, D. Krejčiřík, and K. Zahradová. Effective quantum dynamics on the Möbius strip. *J. Phys. A* 53 (2020), 375201.

---

/ **[`main`](../../README.md)** / **[`framework`](../framework/)** / **[`cosmos`](../cosmos/)** / **[`spectrum`](../spectrum/)** /
