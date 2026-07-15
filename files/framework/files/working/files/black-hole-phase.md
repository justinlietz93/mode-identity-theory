/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /

---

# Black Hole Phase Behavior

Working notes on time, sampling, and the directional problem.

**Status:** Interpretive. Draws on derived results from Sector $\mathcal{A}$ eigenvalue paper and Black Double Zero's §§II, IV.A, VI, VIII.1, VIII.2, VIII.4. No new derivations here; this organizes structural consequences for further work.

**Dependencies:** Sector $\mathcal{A}$ eigenvalue paper; Black Double Zero's §§II, IV.A, VI, VIII.1, VIII.2, VIII.4.

**Related:** [Black Double Zero's](../../../../cosmos/files/black-hole.md).

---

## I. Time at the Horizon

Time in MIT is phase of the cosmic standing wave $\Psi = \cos(t/2)$. The observer is anchored on the temporal edge $S^1$. Observation requires $C(\Theta) > 0$.

As gravitational potential drives $\Theta \to 0$:

| What happens | GR | MIT |
|---|---|---|
| Falling toward horizon | Time slows (exterior) or proceeds normally (infalling) until singularity | Phase continues. $\Theta \to 0$ drives $C \to 0$. Wave passes through the node; observer goes silent. |
| At the horizon | Point of no return; time freezes (exterior) | Sampling channel closes. Surface geometry at maximum extent ($J = 1$). Observer can no longer read the phase. |
| Interior / singularity | Infinite density, geodesic incompleteness | Double zero: $\Theta = 0$ and $\Omega_H = 0$. Scale hierarchy dissolves. Wave content persists; filing system gone. |

The key distinction: GR has two stories depending on who watches (exterior vs. infalling). MIT has one story with two readings. The wave is one object. Phase advances uniformly. What changes is $C(\Theta)$, the capacity to sample.

There is no moment where time stops. There is a moment where reading stops.

---

## II. Local Flatness at the Horizon

The Laplace-Beltrami operator on the curved Möbius surface is:

$$\Delta u = u'' - \frac{1}{R}\tan(y/R) \cdot u'$$

The $\tan(y/R)$ term is the entire difference between curved and flat. It selects sin over cos, breaks the degeneracy, doubles the eigenvalue from $1/R^2$ to $2/R^2$, and places the zeros of $u_0$ on the central circle.

| Location | $y$ | $\tan(y/R)$ | Curvature term | $u_0$ | $J$ |
|---|---|---|---|---|---|
| Central circle (horizon) | 0 or $\pi R$ | 0 | Vanishes | 0 | 1 |
| Mid-domain | intermediate | moderate | Active | intermediate | intermediate |
| Cone point (antinode) | $\pi R/2$ | $\to \infty$ | Maximal | 1 | 0 |

At $\Theta = 0$: the curvature term's coefficient vanishes, so the operator's principal expression coincides pointwise with $u''$ (the flat one), not because of a sign flip but because the first-derivative term drops out there. This does not erase curvature nearby: expanding $\frac{1}{R}\tan(y/R) \approx \frac{y}{R^2} + O(y^3/R^3)$ near $y=0$ shows the curvature term reappears at next order immediately off the point, the same way Christoffel symbols vanish at a point in Riemann normal coordinates without curvature disappearing in the neighborhood. The accurate claim is narrower than "cannot distinguish curved from flat": at that single point the two operators agree; curvature remains present in the neighboring expansion and in the global eigenvalue $\lambda_0=2/R^2$ below.

The eigenvalue $\lambda_0 = 2/R^2$ remains a global property of the whole surface. But the local operator the observer interacts with has lost access to the curvature that produces it.

**Connection to §VII of Black Double Zero's.** At the core, $\Omega \to 0$ and the distinction between edge ($n = 1$) and surface ($n = 2$) dissolves. This is the eigenvalue-level version: the operator term that distinguishes the curved surface from the flat edge is exactly zero at the sampling boundary.

---

## III. The Budget Identity

$$u_0^2 + J^2 = 1$$

Equivalently: $C/2 + J^2 = 1$. Derived from the Sector $\mathcal{A}$ eigenfunction and the Jacobi equation on the totally geodesic $S^2 \subset S^3$. Holds at every point on the meridian.

Two channels, one budget:

| Channel | What it carries | Reads through |
|---|---|---|
| Curvature ($u_0$) | Sampling amplitude, mass, phase operator $C = 2u_0^2$, the factor of 2 distinguishing curved from flat | Eigenfunction |
| Geometric ($J$) | Transverse extent of the surface, room for the wave | Jacobi field |

At the horizon: curvature channel reads zero, geometric channel reads one. The surface is maximally wide. The Möbius band is fully intact. The wave has all the room it needs. The mode structure is complete. What's gone is the ability to read it through $u_0$.

### Information at the Node

The eigenfunction $u_0 = \sin(y/R)$ passes through zero at $y = 0$ and $y = \pi R$, but its spatial slope is $u_0'(0) = 1/R$: finite and nonzero. Slope carries the information that amplitude cannot.

| Side | Zero | Survivor (first nonvanishing order) |
|---|---|---|
| Scaling | $C(\Theta) \to 0$ (quadratic) | $C''(0) = 4\pi^2$ (curvature of $C$ at node) |
| Spectral | $Z_\sigma(0) = 0$ | $Z'_\sigma(0) = \log T^2$ (torsion) |
| Eigenfunction | $u_0(0) = 0$ | $u_0'(0) = 1/R$ (slope through node) |

In every case: value vanishes, derivative carries content through. The budget converts amplitude into slope, eigenfunction into geometry, $u_0$ into $J$.

Guitar string at a node: amplitude vanishes while spatial slope remains finite and nonzero. The eigenfunction crosses the node rather than terminating there. (A true standing-wave node has zero transverse *velocity* too, at all times, not maximum velocity; $u_0'$ here is a derivative in space, not time, and should not be read as motion.)

**Hawking radiation** in this picture: conjecturally associated with the first surviving spatial-gradient order at the node, residual leakage of $u_0'$ back into the sampling channel. Not yet a derived radiation mechanism.

---

## IV. The Directional Problem: Resolution

### The Problem as Stated (Black Double Zero's §VI)

The Hubble tension walks $\Theta$ toward the antinode (away from 0, $C$ increases). The horizon requires $\Theta \to 0$ (toward the node, $C$ decreases). These point in opposite directions on the domain coordinate.

### The Resolution

Coordinate direction was never the right variable. The right variable is proximity to a critical point of $C$.

The derivative of $C(\Theta) = 2\sin^2(\pi\Theta)$:

$$\frac{dC}{d\Theta} = 2\pi\sin(2\pi\Theta)$$

vanishes at exactly three points on the domain:

| Position | $C$ | $dC/d\Theta$ | Type |
|---|---|---|---|
| $\Theta = 0$ | 0 | 0 | Node (minimum) |
| $\Theta = 1/2$ (60/120) | 2 | 0 | Antinode (maximum) |
| $\Theta = 1$ | 0 | 0 | Node (minimum) |

Both phenomena move toward a zero-slope position of $C$: $dC/d\Theta = 0$ means the *observable* $C$ has no first-order response to a small change in $\Theta$ there, a statement about $C$'s sensitivity, not about whether $\Theta$ itself is dynamically stable or attracted to that point. Establishing the latter would need an evolution law for $\Theta$ (e.g. $\dot\Theta = F(\Theta)$), which is not written down anywhere in the framework. What is established: $\Lambda$ and the horizon sit at opposite *types* of critical point of the same function, $\Lambda$ at the maximum, the horizon at the minimum.

### The Landscape

$C(\Theta)$ is a single arch on $[0,1]$ with $\Lambda$ at the top and black holes at the bottom, opposite critical points of the same function. Whether either point is a dynamical attractor for $\Theta$, an evolution law driving $\Theta$ toward it and holding it there, is a separate, undemonstrated claim; nothing below establishes one.

The log slope:

$$\frac{d\ln C}{d\Theta} = 2\pi\cot(\pi\Theta)$$

| Near... | Log slope | What this says |
|---|---|---|
| $\Theta = 0$ (node) | $\to +\infty$ as $1/\Theta$ | $C$ is extremely *sensitive* to $\Theta$ there: a small change in $\Theta$ produces a large fractional change in $C$. Says nothing about how fast $\Theta$ itself changes. |
| $\Theta = 1/2$ (antinode) | $= 0$ | $C$ is *insensitive* to $\Theta$ to first order: small $\Theta$-perturbations leave the observed value of $\Lambda$ unchanged at leading order. This is the topological-protection argument used elsewhere for $\Lambda$; it is a statement about $C$, not about $\Theta$'s dynamics. |

That the black hole horizon has $\Theta\to0$, and that infall past it is one-way, is inherited from GR, not derived from the log-slope of $C$ here. The log-slope diverging is a real property of the phase operator; "runaway," "cliff," and "attractor" describe how $\Theta$ would have to be *moving*, which requires its own equation of motion, not supplied by this file or by Black Double Zero's.

$\Theta_0 = 34/120$, the galactic environmental shift's home well, is *not* near the antinode plateau: $C'(34/120) \approx 6.15$, within 2% of the arch's maximum possible slope $2\pi\approx6.28$, and 26 grid steps from the antinode at $60/120$. It sits near the *steepest* part of the arch, the opposite of a flat region. Whatever protects $\Lambda$ specifically (its own well sits exactly at the true zero-slope antinode) does not extend to 34/120, and the galactic $2/120$ shift should not be described as living on a plateau.

### Connection to the Complementarity

The two critical points of $C$ are the two poles of $u_0^2 + J^2 = 1$:

| Critical point | $u_0$ | $J$ | Character |
|---|---|---|---|
| Antinode (max $C$) | 1 | 0 | Cone point. Curvature dominates. |
| Node (min $C$) | 0 | 1 | Central circle. Geometry dominates. |

The coin has a curvature face and a geometry face. You can only land on one at a time.

### Spectral Mirror

The directional asymmetry appears on the spectral side too:

| Direction | Scaling side | Spectral side |
|---|---|---|
| Toward the zero | $\Theta \to 0$: structure simplifies, $C \to 0$ | $s \to 0$: Pochhammer collapses, 4 of 16 characters survive |
| Away from the zero | Interior of domain: everything participates | $s \neq 0$: full tower activates, 28-32 of 32 characters contribute |

Clean direction is toward the zero on both sides. Both are filters: the critical point strips everything except essential structure.

---

## V. Summary Picture

$C(\Theta)$ is an arch on $[0, 1]$ with one maximum and two minima.

- **Top of arch** ($\Theta = 1/2$): $\Lambda$. Topologically protected (the observable $C$ is insensitive to small $\Theta$-perturbations there, to first order). Zero slope. Cone point geometry ($J = 0$, $u_0 = 1$). Curvature fully expressed. Maximum sampling.
- **Bottom of arch** ($\Theta = 0$ or 1): Horizon. Zero slope. Central circle geometry ($J = 1$, $u_0 = 0$). Curvature silent. Sampling closed. That infall past a horizon is one-way is inherited from GR, not derived from the slope of $C$ here.
- **Between**: Everything observed. Galaxies, particles, phase fields, Fibonacci wells.

The budget $u_0^2 + J^2 = 1$ holds everywhere. Nothing is created or destroyed on the walk from top to bottom. Amplitude converts to slope, eigenfunction to geometry, reading to room.

---

## VI. Open Questions (updated)

| Item | Status | Notes |
|---|---|---|
| $\Phi \to \Theta$ mapping | DERIVED (leading order near the horizon); global form is the minimal extension, not independently forced; see Black Double Zero's §VIII.1 | $\beta=1$ forced by requiring $u_0'(0)=1/R$ stay finite and nonzero at the horizon, giving $C/C_0\sim1-r_s/r$ as $r\to r_s$. Taking that as the global form ($C/C_0=1-r_s/r$ at all $r$) is the minimal, not the only, extension; under it, an ordinary galactic potential gives a smooth shift $\sim2\times10^{-7}$, far below one bosonic step, decoupled from (and not an explanation of) the separate §9 environmental $2/120$ shift |
| Quantitative Hawking temperature | Largely resolved; see Black Double Zero's §VIII.4 | Eigenfunction-gradient $1/M$ dependence and its $\sin(\pi\Theta_0)$ coefficient DERIVED from $du_0/d\ell|_H \propto 1/M$; Hawking-temperature normalization and thermal (Planck) character INHERITED through the forced $g_{tt}$ pairing, and $\sin(\pi\Theta_0)$ does not appear in it |
| Runaway steepening and evaporation | OPEN | Temperature coefficient now derived (§VIII.4); quantitative evaporation dynamics (back-reaction, rate) remains open. "Runaway" is inherited from GR (smaller black holes radiate and shrink faster), not derived from the log-slope of $C$ (§IV) |
| Spectral-physical bridge at the node | OPEN (Priority 5) | Does $Z'_\sigma(0) = \log T^2$ connect to $u_0'(0) = 1/R$ through a route other than the direct $s \leftrightarrow \Theta$ bridge (proved nonexistent)? |
| Minimum black hole mass from grid resolution | COMPUTED; see Black Double Zero's §VIII.2 | $M_\min \approx 7.42\,m_P$ (full 120-grid) or $\approx 3.70\,m_P$ (bosonic 60-grid); both deep in the quantum-gravity regime, ~$10^{38}\times$ below any astrophysical black hole. (Relabeled from "plateau edge": the computation is discrete-shell counting between the horizon and the $H_0$ well, and does not depend on the plateau/runaway framing corrected in §IV.) |

---

*The arch holds. The wave passes through. The observer goes quiet at the bottom and speaks loudest at the top.*

---

/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /
