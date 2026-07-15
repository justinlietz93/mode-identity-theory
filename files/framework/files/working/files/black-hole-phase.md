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

At $\Theta = 0$: the curvature term in the operator is zero. The operator reduces locally to $-d^2/dy^2$. The observer at the horizon cannot distinguish the curved Möbius band from a flat strip, because the curvature signature is zero at that location.

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

The eigenfunction $u_0 = \sin(y/R)$ passes through zero at $y = 0$ and $y = \pi R$, but its derivative is $u_0'(0) = 1/R$: finite and nonzero. The wave is in motion through the node. Slope carries the information that amplitude cannot.

| Side | Zero | Survivor (first nonvanishing order) |
|---|---|---|
| Scaling | $C(\Theta) \to 0$ (quadratic) | $C''(0) = 4\pi^2$ (curvature of $C$ at node) |
| Spectral | $Z_\sigma(0) = 0$ | $Z'_\sigma(0) = \log T^2$ (torsion) |
| Eigenfunction | $u_0(0) = 0$ | $u_0'(0) = 1/R$ (slope through node) |

In every case: value vanishes, derivative carries content through. The budget converts amplitude into slope, eigenfunction into geometry, $u_0$ into $J$.

Guitar string at the node: displacement zero, velocity maximum. Most actively in motion at the exact point where you measure nothing.

**Hawking radiation** in this picture: residual leakage of $u_0'$ back into the sampling channel at the first nonvanishing order of the double zero.

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

Both phenomena walk toward a zero-slope position. Both are stable: $dC/d\Theta = 0$ means local perturbations produce no first-order change. They walk to opposite *types* of critical point: $\Lambda$ to the maximum, horizon to the minimum.

### The Landscape

$C(\Theta)$ is a single arch. $\Lambda$ sits on top. Black holes sit at the bottom.

The log slope determines which attractor wins:

$$\frac{d\ln C}{d\Theta} = 2\pi\cot(\pi\Theta)$$

| Near... | Log slope | Behavior |
|---|---|---|
| $\Theta = 0$ (node) | $\to +\infty$ as $1/\Theta$ | Infinitely steep attractor. Runaway collapse. |
| $\Theta = 1/2$ (antinode) | $= 0$ | Flat plateau. Perturbations produce no first-order effect. |

The antinode is a gentle plateau: step onto it and stay. That is $\Lambda$, topologically protected, immovable by environment. The node is a cliff: once $\Theta$ starts approaching zero, the log slope diverges, the approach accelerates, runaway collapse. That is the black hole.

The galactic phase field (one bosonic step, 2/120) is a small perturbation on the plateau near 34/120. The gravitational potential at $\Phi/c^2 \to -1/2$ throws you off the plateau entirely into the runaway basin of the node.

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

- **Top of arch** ($\Theta = 1/2$): $\Lambda$. Topologically protected. Zero slope. Immovable. Cone point geometry ($J = 0$, $u_0 = 1$). Curvature fully expressed. Maximum sampling.
- **Bottom of arch** ($\Theta = 0$ or 1): Horizon. Runaway attractor. Zero slope. Irreversible once entered. Central circle geometry ($J = 1$, $u_0 = 0$). Curvature silent. Sampling closed.
- **Between**: Everything observed. Galaxies, particles, phase fields, Fibonacci wells.

The budget $u_0^2 + J^2 = 1$ holds everywhere. Nothing is created or destroyed on the walk from top to bottom. Amplitude converts to slope, eigenfunction to geometry, reading to room.

---

## VI. Open Questions (updated)

| Item | Status | Notes |
|---|---|---|
| $\Phi \to \Theta$ mapping | DERIVED (leading order); see Black Double Zero's §VIII.1 | $C/C_0 = 1 - r_s/r$, with $\beta=1$ forced by requiring $u_0'(0)=1/R$ stay finite and nonzero at the horizon. Weak-field check: an ordinary galactic potential gives a smooth shift $\sim 2\times10^{-7}$, far below one bosonic step, decoupled from (and not an explanation of) the separate §9 environmental $2/120$ shift |
| Quantitative Hawking temperature | Largely resolved; see Black Double Zero's §VIII.4 | $1/M$ dependence and coefficient DERIVED from $du_0/d\ell|_H \propto 1/M$; thermal (Planck) character is INHERITED through the forced mapping, not independently re-derived |
| Runaway steepening and evaporation | OPEN | Temperature coefficient now derived (§VIII.4); quantitative evaporation dynamics (back-reaction, rate) remains open |
| Spectral-physical bridge at the node | OPEN (Priority 5) | Does $Z'_\sigma(0) = \log T^2$ connect to $u_0'(0) = 1/R$ through a route other than the direct $s \leftrightarrow \Theta$ bridge (proved nonexistent)? |
| Minimum black hole mass from plateau edge | COMPUTED; see Black Double Zero's §VIII.2 | $M_\min \approx 7.42\,m_P$ (full 120-grid) or $\approx 3.70\,m_P$ (bosonic 60-grid); both deep in the quantum-gravity regime, ~$10^{38}\times$ below any astrophysical black hole |

---

*The arch holds. The wave passes through. The observer goes quiet at the bottom and speaks loudest at the top.*

---

/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /
