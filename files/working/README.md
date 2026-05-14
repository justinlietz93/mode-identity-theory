/ **[`main`](../../README.md)** / **[`framework`](../framework/)** / **[`cosmos`](../cosmos/)** / **[`spectrum`](../spectrum/)** /

---

# :memo: Working Files

Research-in-progress across the framework. Ordered by value: items that strengthen position before the Euclid DR1 falsification window first, foundational upgrades second, technical resolution third, data-gated items last.

---

## :telescope: Pre-Euclid

Publishable results that strengthen the framework's position before October 2026.

---

### [Phase Field Coherence Scale (SPARC)](./files/sparc-phase-field-notes.md)

**Problem:** The Hubble-tension mechanism predicts a binary phase shift inside a coherence scale $L_f = v_c^2/a_0$, but it has no test outside the cosmological distance ladder. The phase field should also reproduce the Radial Acceleration Relation (McGaugh et al. 2016) as a consequence; reproduction motivated, not derived.

**Dependencies:** Hubble-tension well assignment ($\Theta = 34/120 \to 36/120$), MOND scale $a_0$ from $C(13/120)$, closure identity $\mathcal{T}_c = 2\xi v_c^2/c^2$.

---

### [McKay Propagator Correction](./files/mckay-propagator-correction.md)

**Problem:** Two of twelve SM fermions overshoot at high McKay distance (down ×3.2, top ×3.9). The misses are vacuum-dependent: at dist 5, gal misses while triv and std hit within 6%; at dist 7, triv misses while gal hits within 28%. The reversal at the R8 branch point rules out distance-only corrections. Separately, the Coxeter-Galois gate locks all $R_4$ entries to $T_3 = -1/2$, displacing charm. The branch-point correction and charm displacement may be the same problem.

**Dependencies:** McKay graph for $2I$, $C_\text{geom}$ values for all irreps, torsion table $T^2(\rho \otimes \sigma)$ across vacua, Coxeter-Galois gate.

---

### [Temporal Budget Identity](./files/temporal-budget-notes.md)

**Problem:** The phase-clock derivation rests on $\Psi^2 + S^2 = 1$ and the Waltz clock $d\tau/dt = S^{1/2}$, which recovers $\Omega_m = 0.315$ at $\Delta\chi^2 = +0.11$ vs flat ΛCDM. The clock exponent $n = -1/2$ is empirically validated (integer alternatives ruled out at $\Delta\chi^2 > 60$) but not derived from the embedding. The two phase parameterizations ($\varphi$ engine phase and $t$ budget phase) are not yet reconciled.

**Dependencies:** Möbius spatial budget $u_0^2 + J^2 = 1$, Sector $\mathcal{A}$ eigenvalue.

---

### Discrete Snap Mechanism

**Problem:** The phase field locks to one bosonic grid step (2/120) inside a galactic coherence scale. Why a discrete snap rather than a continuous slide? The binary response is testable (H₀ bimodality), but the mechanism that enforces quantization is not derived.

**Dependencies:** 120-domain structure, phase field coherence scale $L_f$.

---

## :house: Foundation

Closing any one of these upgrades everything downstream.

---

### [Oort Cloud Project: Nested Coherence Domains](./files/oort-cloud-project.md)

**Problem:** Does MIT's structure project into every gravitationally coherent scale, or only the cosmological one? If the 120-grid and 3/2 conversion nest, the Oort Cloud (~144,000 AU) is the solar-system-scale coherence boundary. Central open question: generalizing $L_f = v_c^2/a_0$ from galactic to stellar and planetary scales. Downstream predictions include CMB-ecliptic alignment as a local sampling fingerprint.

**Dependencies:** Sector $\mathcal{A}$ eigenvalue, phase field coherence scale $L_f$, 120-grid scale-free projection, 3/2 Gauss-Codazzi conversion.

---

### [Cone Point Coherence](./files/cone-point-coherence-notes.md)

**Problem:** Galactic coherence (all observers measuring the same $\mathbb{R}^4$) may be the $W$-independence of a nested eigenvalue problem, guaranteed by a cone point at galactic scale. The cone point analysis (Frobenius, Friedrichs, excision) that makes the cosmic eigenvalue well-defined must be re-established at galactic scale with equal rigor. Critical fork: GR tidal curvature in the flat-curve regime is Euler-type with power-law Jacobi solutions that structurally cannot zero; the needed curvature $K_g = \pi^2 a_0^2/v_c^4$ lives at the topology-gravity interface.

**Dependencies:** Sector $\mathcal{A}$ eigenvalue, phase field coherence scale $L_f$, 120-grid scale-free projection.

---

### [Scaling Law Uniqueness](./files/scaling-law-uniqueness.md)

**Problem:** $A/A_P = C(\Theta) \cdot (\sqrt{\Omega})^{-n}$ is currently a declared measurement postulate; every downstream result inherits that status. Anti-periodic BC forces $C(\Theta)$, dimensionless output forces factorization (steps 1-4 walked). The open link is step 5: proving $(\sqrt{\Omega})^{-n}$ is the only hierarchy function on a bounded domain with observer at $\sqrt{\Omega}$. A Gleason-type result would promote the scaling law from declared to forced.

**Dependencies:** Sector $\mathcal{A}$ eigenvalue, Lemma 8 (spectral inaccessibility), Möbius topology axioms.

---

### Friedmann as Output

**Problem:** The phase-clock $H(z)$ currently uses the Friedmann equation as input. Deriving $H^2 \propto \rho$ from the postulate $S^1 = \partial(\text{Möbius}) \hookrightarrow S^3$ would close the program: the framework would produce its own dynamics rather than borrowing GR's.

**Dependencies:** Temporal budget identity, Waltz clock, Gauss-Codazzi embedding.

---

### Waltz Clock from Postulate

**Problem:** The exponent $n = -1/2$ is selected by matter-era scaling and empirically validated ($\Delta\chi^2 > 60$ for integer alternatives). The connection to the face/edge stabilizer ratio (3/2) is noted but not derived from the embedding without invoking GR.

**Dependencies:** $S^1 = \partial(\text{Möbius}) \hookrightarrow S^3$, stabilizer decomposition $|2I| = 2^3 \cdot 3 \cdot 5$.

---

### Vertex $Z_5$ Completion

**Problem:** The $(1+z)^1$ term in $H^2(z)$ may derive from the vertex stabilizer $Z_5$, completing the face/edge/vertex decomposition of the 3/2 accounting. Face ($Z_3$) contributes matter dilution, edge ($Z_2$) contributes the Friedmann square root. The vertex role in the temporal correction is unwalked.

**Dependencies:** Temporal budget identity, stabilizer decomposition.

---

### [Energy as Resolution Amplitude](./files/energy-as-resolution-amplitude.md)

**Problem:** $E^2 = (mc^2)^2 + (pc)^2$ may be the Pythagorean theorem on the mode decomposition of the sampling operation: temporal-mode amplitude (rest mass) orthogonal to spatial-mode amplitude (momentum). Five promotion steps unwalked: spatial-mode coupling, orthogonality proof, $c^2$ factor from $S^1$ structure, Lorentz recovery as sampling symmetry, connection to mass formula.

**Dependencies:** Standing wave $\Psi = \cos(t/2)$, scaling law, mass formula.

---

## :mag_right: Resolution

Technical gaps with specific paths forward.

---

### [Black Hole Phase Behavior](./files/black-hole-phase-notes.md)

**Problem:** $\Phi \to \Theta$ mapping derived at leading order ($C/C_0 = 1 - r_s/r$, $\beta = 1$ forced). Hawking temperature $1/M$ and coefficient derived; thermal character inherited. Area entropy motivated by surface primacy; $1/4$ factor not derived. Two-attractor landscape established. Global corrections and quantitative evaporation rate remain open.

**Dependencies:** Sector $\mathcal{A}$ eigenvalue, [Black Double Zero's](../cosmos/files/black-hole.md).

---

### Scale Consistency

**Problem:** Three gauge couplings evaluated at different energy scales. $\alpha$ hits 0.5% at low energy but 6.2% at $M_Z$. The framework must commit to one evaluation scale or derive running from MIT structure.

**Dependencies:** Gauge coupling derivation (engine §15), scaling law.

---

### Plato Twist Derivation

**Problem:** $\cos(\pi/10)$ is motivated by the dodecahedral half-defect and parity violation. The operator-level mechanism connecting $\mathbb{Z}_2$ holonomy to the multiplicative cosine projection on weak coupling is the open link.

**Dependencies:** Möbius non-orientability, stabilizer decomposition.

---

### 240 Alternative for $\alpha_s$

**Problem:** $C(17/120) \times \Omega^{-1/240}$ sits 1% behind the primary formula. $240 = 2 \times 120$. Requires independent justification or exclusion.

**Dependencies:** Grid ladder selection rule, scaling law.

---

### Neutrino Mass Ratios

**Problem:** $\mu_\Lambda$ as the neutrino floor is motivated. The octave selection and multipliers (4, 22) are identified but not derived from the group theory.

**Dependencies:** Mass formula, $\Lambda$ eigenvalue.

---

### $L_\text{strip}/L_\text{fund}$ Ratio

**Problem:** Spectral: $8.17 \pm 0.1$. Observational: $7.93$. A 3% gap that has persisted through every revision. Unresolved.

**Dependencies:** Length scale hierarchy (engine §3).

---

### $\alpha$ Exponent

**Problem:** The $\alpha$ exponent equals the minimum grid step. Two convergent paths remain. Uniqueness scan confirms. Single-principle derivation open.

**Dependencies:** Grid structure, scaling law.

---

### Anti-periodic BC Selection

**Problem:** 9/10 assigned fermion masses within ×3. First-principles derivation of why anti-periodic boundary conditions are selected over periodic remains open.

**Dependencies:** Möbius non-orientability, mass formula.

---

### dist/30 Hierarchy Exponent

**Problem:** Three convergent paths connect McKay graph distance to the Coxeter number of $E_8$ as the scaling exponent. Single-principle derivation open.

**Dependencies:** McKay correspondence, $E_8$ Coxeter number.

---

### Grid Ladder Selection Rule

**Problem:** Three convergent paths connect interaction character to grid resolution ($D = 60$ vs $D = 120$). Formal derivation open.

**Dependencies:** Stabilizer decomposition, boson/fermion domain split.

---

## :bar_chart: Waiting on External Data

---

### $\nu_2$ Mass

**Problem:** Predicted at 8.6 meV with a ratio gap of ~7.75× from the nearest entry. JUNO and DUNE are expected to resolve the neutrino mass hierarchy and test this value directly.

**Dependencies:** Mass formula, neutrino sector assignments.

---

### Dead Zone

**Problem:** 8 of 24 mass formula entries are unassigned: 6 in the dead zone ($10^{-9}$ to $10^{-6}$ GeV), 1 target (rank 16, ~349 MeV), 1 excluded (rank 3, ~0.4 eV). The dead zone is probed by sterile neutrino and warm dark matter searches.

**Dependencies:** Mass formula, full assignment table.

---

### Physical Observation Scale

**Problem:** $\sqrt{\ell_P \cdot R_\Lambda} \sim 50\,\mu$m places the observer at the cellular scale. The geometric midpoint is derived; the dimensionless derivation connecting this to biological observation is pending.

**Dependencies:** Observer position at $\sqrt{\Omega}$, scale hierarchy.

---

### Next Cycle Initiation

**Problem:** What happens at $t = 4\pi$ is outside the current framework. The standing wave completes its period. Whether the cycle repeats, terminates, or transforms is not addressed.

**Dependencies:** None within current framework.

---

/ **[`main`](../../README.md)** / **[`framework`](../framework/)** / **[`cosmos`](../cosmos/)** / **[`spectrum`](../spectrum/)** /
