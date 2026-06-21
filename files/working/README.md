/ **[`main`](../../README.md)** / **[`framework`](../framework/)** / **[`cosmos`](../cosmos/)** / **[`spectrum`](../spectrum/)** /

---

# :memo: Working Files

Research-in-progress across the framework. Organized by status: an orienting map first, then open problems (foundational upgrades, then technical gaps), then closed results and the data tests run against public datasets, then items gated on external data. Within each section, most important first.

---

## :world_map: Maps

Orienting notes that index other work.

---

### [The R Problem](./files/r-problem.md)

**Tracker:** Maps every route to an independent spatial curvature radius $R$ and where each stands. $\Lambda = 3/R^2$ becomes a forward prediction only with an $R$ not read off $\Lambda$: de Sitter is circular, the Molien gap is not independent, the CMB L-ratio factor of 8 is dead (no topological derivation), and the particle mass spectrum is the one live route (executed, order of magnitude). Includes the shared E₈ / $h = 30$ engine tying the L ratio to the mass formula, and flags the Molien sparse-zone CMB result as the independent survivor of the L work.

**Dependencies:** [R from the mass spectrum](./files/r-from-mass-spectrum.md), fermion mass formula, $\Lambda = 3/R^2$ eigenvalue relation.

---

### [The Budget Map](./files/budget-map.md)

**Tracker:** The inventory of what is a budget and what is read off one. There is a single conserved budget in this sector, the temporal $\Psi^2 + S^2 = 1$ (with the spatial $u_0^2 + J^2 = 1$ as its twin); temperature ($T \propto 1/S$) and entropy ($\Sigma = k_B \ln W_\text{micro}$) are two readings of its state $S$, not budgets, and the Waltz clock is a map from phase to time. Pins the distinction so the readings are not miscounted as parallel ledgers, the error the entropy note had to fix.

**Dependencies:** [Temporal Budget](./files/temporal-budget.md), [Energy as Resolution Amplitude](./files/energy-as-resolution-amplitude.md), [Entropy as Realization Budget](./files/entropy-as-realization-budget.md).

---

## :house: Foundation

Closing any one of these upgrades everything downstream.

---

### [Scaling Law Uniqueness](./files/scaling-law-uniqueness.md)

**Problem:** $A/A_P = C(\Theta) \cdot (\sqrt{\Omega})^{-n}$ is currently a declared measurement postulate; every downstream result inherits that status. Anti-periodic BC forces $C(\Theta)$, dimensionless output forces factorization (steps 1-4 walked). The open link is step 5: proving $(\sqrt{\Omega})^{-n}$ is the only hierarchy function on a bounded domain with observer at $\sqrt{\Omega}$. A Gleason-type result would promote the scaling law from declared to forced.

**Dependencies:** Sector $\mathcal{A}$ eigenvalue, Lemma 8 (spectral inaccessibility), Möbius topology axioms.

---

### Friedmann as Output

**Problem:** The phase-clock $H(z)$ currently uses the Friedmann equation as input. Deriving $H^2 \propto \rho$ from the postulate $S^1 = \partial(\text{Möbius}) \hookrightarrow S^3$ would close the program: the framework would produce its own dynamics rather than borrowing GR's.

**Dependencies:** Temporal budget identity, Waltz clock, Gauss-Codazzi embedding.

---

### [Calibration Structure](./files/calibration-structure.md)

**Summary:** Reframes the engine as a calibration scheme: one measured anchor per sector ($H_0$ edge, $\Lambda$ surface, $m_e$ mass-sector normalization), with the topology supplying the exponents, well assignments, and ratios. Localizes the R problem to a single demotion: $\Lambda$ moves from absolute prediction to measured calibration input, and nothing downstream collapses. Draft for a new engine section.

**Dependencies:** a0 paper Appendix A.2, Λ eigenvalue, scaling law.

---

### [Temporal Budget Identity](./files/temporal-budget.md)

**Problem:** The phase-clock derivation rests on $\Psi^2 + S^2 = 1$ and the Waltz clock $d\tau/dt = S^{1/2}$, which recovers $\Omega_m = 0.315$ at $\Delta\chi^2 = +0.11$ vs flat ΛCDM. The clock exponent $n = -1/2$ is empirically validated (integer alternatives ruled out at $\Delta\chi^2 > 60$) but not derived from the embedding. The two phase parameterizations ($\Phi$ engine phase and $t$ budget phase) are not yet reconciled.

**Dependencies:** Möbius spatial budget $u_0^2 + J^2 = 1$, Sector $\mathcal{A}$ eigenvalue.

---

### [Cone Point Coherence](./files/cone-point-coherence.md)

**Problem:** Galactic coherence (all observers measuring the same $\mathbb{R}^4$) may be the $W$-independence of a nested eigenvalue problem, guaranteed by a cone point at galactic scale. The cone point analysis (Frobenius, Friedrichs, excision) that makes the cosmic eigenvalue well-defined must be re-established at galactic scale with equal rigor. Critical fork: GR tidal curvature in the flat-curve regime is Euler-type with power-law Jacobi solutions that structurally cannot zero; the needed curvature $K_g = \pi^2 a_0^2/v_c^4$ lives at the topology-gravity interface.

**Dependencies:** Sector $\mathcal{A}$ eigenvalue, phase field coherence scale $L_f$, 120-grid scale-free projection.

---

### [Energy as Resolution Amplitude](./files/energy-as-resolution-amplitude.md)

**Problem:** $E^2 = (mc^2)^2 + (pc)^2$ may be the Pythagorean theorem on the mode decomposition of the sampling operation: temporal-mode amplitude (rest mass) orthogonal to spatial-mode amplitude (momentum). Five promotion steps unwalked: spatial-mode coupling, orthogonality proof, $c^2$ factor from $S^1$ structure, Lorentz recovery as sampling symmetry, connection to mass formula.

**Dependencies:** Standing wave $\Psi = \cos(t/2)$, scaling law, mass formula.

---

### [Redshift and Cooling](./files/redshift-and-cooling.md)

**Note:** How a static universe reddens light and cools a bath, both readings of the budget's state $S$. Redshift is the phase ratio $1 + z = S(t_\text{obs})/S(t_\text{emit})$ on the standing wave; cooling is that same ratio on a blackbody, which stays a blackbody at $T \propto 1/S$ (ESTABLISHED as a kinematic equivalence with the FLRW thermal law). Not tired light, not expansion; the distance side rides on the Waltz clock.

**Dependencies:** Temporal budget identity, standing wave $\Psi = \cos(t/2)$, Waltz clock.

---

### [Entropy as Realization Budget](./files/entropy-as-realization-budget.md)

**Problem:** A static universe cools by budget transfer $\Psi^2 \to S^2$ ([Redshift and Cooling](./files/redshift-and-cooling.md)), but the thermodynamic entropy is unsettled. Candidate: entropy is the spread of the resolution-amplitude budget over realized modes, so the second law is the transfer direction and the low past is forced by $\Psi(0) = +1$. The load-bearing open step is the shell-unlock map $S \mapsto N_\text{max}(S)$ from the $2I$ Molien shells, which sets the accessible-mode count $W_\text{modes}(S)$; entropy is the microstate count over it. Without the map the rising entropy is circular. Scoped to the realization sector, with the gravitational ledger (Penrose) left open.

**Dependencies:** Temporal budget identity, Redshift and Cooling, energy as resolution amplitude, $S^3/2I$ Molien shell spectrum.

---

## :mag_right: Open Gaps

Technical gaps with specific paths forward.

---

### dist/30 Hierarchy Exponent

**Problem:** Three convergent paths connect McKay graph distance to the Coxeter number of $E_8$ as the scaling exponent. Single-principle derivation open.

**Dependencies:** McKay correspondence, $E_8$ Coxeter number.

---

### Anti-periodic BC Selection

**Problem:** 9/10 assigned fermion masses within ×3. First-principles derivation of why anti-periodic boundary conditions are selected over periodic remains open.

**Dependencies:** Möbius non-orientability, mass formula.

---

### Scale Consistency

**Problem:** Three gauge couplings evaluated at different energy scales. $\alpha$ hits 0.5% at low energy but 6.2% at $M_Z$. The framework must commit to one evaluation scale or derive running from MIT structure.

**Dependencies:** Gauge coupling derivation (engine §15), scaling law.

---

### Grid Ladder Selection Rule

**Problem:** Three convergent paths connect interaction character to grid resolution ($D = 60$ vs $D = 120$). Formal derivation open.

**Dependencies:** Stabilizer decomposition, boson/fermion domain split.

---

### $\alpha$ Exponent

**Problem:** The $\alpha$ exponent equals the minimum grid step. Two convergent paths remain. Uniqueness scan confirms. Single-principle derivation open.

**Dependencies:** Grid structure, scaling law.

---

### Plato Twist Derivation

**Problem:** $\cos(\pi/10)$ is motivated by the dodecahedral half-defect and parity violation. The operator-level mechanism connecting $\mathbb{Z}_2$ holonomy to the multiplicative cosine projection on weak coupling is the open link.

**Dependencies:** Möbius non-orientability, stabilizer decomposition.

---

### Neutrino Mass Ratios

**Problem:** $\mu_\Lambda$ as the neutrino floor is motivated. The octave selection and multipliers (4, 22) are identified but not derived from the group theory.

**Dependencies:** Mass formula, $\Lambda$ eigenvalue.

---

### [Black Hole Phase Behavior](./files/black-hole-phase.md)

**Problem:** $\Phi \to \Theta$ mapping derived at leading order ($C/C_0 = 1 - r_s/r$, $\beta = 1$ forced). Hawking temperature $1/M$ and coefficient derived; thermal character inherited. Area entropy motivated by surface primacy; 1/4 factor not derived. Two-attractor landscape established. Global corrections and quantitative evaporation rate remain open.

**Dependencies:** Sector $\mathcal{A}$ eigenvalue, [Black Double Zero's](../cosmos/files/black-hole.md).

---

### [Oort Cloud Project: Nested Coherence Domains](./files/oort-cloud-project.md)

**Problem:** Does MIT's structure project into every gravitationally coherent scale, or only the cosmological one? If the 120-grid and 3/2 conversion nest, the Oort Cloud (~144,000 AU) is the solar-system-scale coherence boundary. Central open question: generalizing $L_f = v_c^2/a_0$ from galactic to stellar and planetary scales. Downstream predictions include CMB-ecliptic alignment as a local sampling fingerprint.

**Dependencies:** Sector $\mathcal{A}$ eigenvalue, phase field coherence scale $L_f$, 120-grid scale-free projection, 3/2 Gauss-Codazzi conversion.

---

### 240 Alternative for $\alpha_s$

**Problem:** $C(17/120) \times \Omega^{-1/240}$ sits 1% behind the primary formula. $240 = 2 \times 120$. Requires independent justification or exclusion.

**Dependencies:** Grid ladder selection rule, scaling law.

---

### $L_\text{strip}/L_\text{fund}$ Ratio

**Status:** The factor of 8 has no topological derivation, so this is a dead route to R, superseded by the mass spectrum. See [The R Problem](./files/r-problem.md). The only open remnant is the residual ~3% spectral-vs-observational gap (8.17 ± 0.1 vs 7.93).

---

## :white_check_mark: Results

Closed: executed computations and derivations with verdicts in hand.

---

### [R from the Particle Mass Spectrum](./files/r-from-mass-spectrum.md)

**Result (2026-06-15):** Determines the spatial curvature radius $R$ from the fermion mass formula's dependence on the hierarchy factor $\Omega_\Lambda$, independently of $\Lambda$, the CMB, and the de Sitter relation, breaking the R-problem circularity. Electron + muon give $R \sim 20$ Gpc and $\Lambda \sim 8 \times 10^{-54}\,\text{m}^{-2}$, about 14× (one order of magnitude) below the observed value. Precision is capped at order of magnitude by the McKay-lever amplification (60× for $\delta d = 1$) acting on the mass formula's irreducible few-percent residual scatter; a pair scan shows no fermion pair beats electron-muon. The third and only non-excluded route to $R$.

**Dependencies:** Fermion mass formula and torsion table, McKay residual scatter (sets the precision floor), $\Omega_\Lambda$ hierarchy, $\Lambda = 3/R^2$ eigenvalue relation.

---

### [McKay Propagator Correction](./files/mckay-propagator-correction.md)

**Resolved, negative (2026-06-06):** No parameter-free propagator or branch-point correction tracks the high-distance mass residuals; the route is closed and the residuals are irreducible scatter at the ~×1.8 level. The standing anomaly: two of twelve SM fermions overshoot at high McKay distance (down ×3.2, top ×3.9), vacuum-dependent (at dist 5, gal misses while triv and std hit within 6%; at dist 7, triv misses while gal hits within 28%), and separately the Coxeter-Galois gate locks all $R_4$ entries to $T_3 = -1/2$, displacing charm.

**Dependencies:** McKay graph for $2I$, $C_\text{geom}$ values for all irreps, torsion table $T^2(\rho \otimes \sigma)$ across vacua, Coxeter-Galois gate.

---

## :file_cabinet: Data Tests

Registered and exploratory tests run against public datasets, with verdicts.

---

### [Phase Field Coherence Scale (SPARC)](./files/sparc-phase-field.md)

**Test:** Does $L_f = v_c^2/a_0$ behave as a galactic coherence radius across the SPARC sample, after controlling for ordinary size scaling? Pre-registered pipeline, frozen at tag `v1.0-preregistration` (DOI 10.5281/zenodo.20271702), run once against 123 quality-filtered galaxies.

**Result (2026-05-19):** The registered predictions are not borne out. The transition radius tracks $L_f$ with slope ≈ 0.23 (registered [0.7, 1.3]); 53.7% of flat-curve galaxies fall below the closure threshold (registered limit 5%). Verdicts stable across all 27 sensitivity-grid cells. $L_f$ is not the coherence radius the framework posited, and the closure identity does not hold. The lattice arithmetic is untouched.

---

### [H₀ Bimodality (Discrete-vs-Continuous Fork)](./files/h0-bimodality-test.md)

**Test:** Do published H₀ measurements cluster into two discrete populations (~67 and ~73), as the Hubble-tension Section V fork predicts, or form a continuous spread? Hartigan dip test, Gaussian mixture, and gap test on 18 compiled measurements (13-row independent subset). Exploratory, not pre-registered.

**Result (2026-05-19):** The discrete two-cluster prediction is not supported. The dip test fails to reject unimodality in every configuration (primary p = 0.217); the Gaussian mixture's 2-component preference is statistically negligible (ΔBIC < 1.2) and points to clusters at 68.4 / 73.2 rather than 67 / 73; the predicted 69-71 gap contains TRGB / CCHP at 69.8. The data sorts by calibration class but does not quantize.

---

## :bar_chart: Waiting on External Data

---

### $\nu_2$ Mass

**Problem:** Predicted at 8.6 meV with a ratio gap of ~7.75× from the nearest entry. JUNO and DUNE are expected to resolve the neutrino mass hierarchy and test this value directly.

**Dependencies:** Mass formula, neutrino sector assignments.

---

### Black Hole Node Distribution on Static $S^3$

**Problem:** If $S^3$ is static and black holes are topological nodes (double zeros where $\Theta \to 0$ and $\Omega_H \to 0$), their spatial distribution should reflect the symmetry of the 120-cell rather than FLRW comoving evolution. Quasar catalogs (Milliquas, SDSS) provide ~900,000 angular positions and redshifts. The missing piece is the $z$-to-<i>S<sup>3</sup></i>-position map: converting redshift to location on the static 3-sphere without assuming spatial expansion. Once available, test whether supermassive black hole positions correlate with 120-cell structure.

**Dependencies:** Friedmann as Output (provides the static $S^3$ coordinate system), $z$-to-phase map from temporal budget.

---

### Dead Zone

**Problem:** 8 of 24 mass formula entries are unassigned: 6 in the dead zone ($10^{-9}$ to $10^{-6}$ GeV), 1 target (rank 16, ~349 MeV), 1 excluded (rank 3, ~0.4 eV). The dead zone is probed by sterile neutrino and warm dark matter searches.

**Dependencies:** Mass formula, full assignment table.

---

### Physical Observation Scale

**Problem:** $\sqrt{\ell_P \cdot R_\Lambda} \sim 50\,\mu\text{m}$ places the observer at the cellular scale. The geometric midpoint is derived; the dimensionless derivation connecting this to biological observation is pending.

**Dependencies:** Observer position at $\sqrt{\Omega}$, scale hierarchy.

---

### Next Cycle Initiation

**Problem:** What happens at $t = 4\pi$ is outside the current framework. The standing wave completes its period. Whether the cycle repeats, terminates, or transforms is not addressed.

**Dependencies:** None within current framework.

---

/ **[`main`](../../README.md)** / **[`framework`](../framework/)** / **[`cosmos`](../cosmos/)** / **[`spectrum`](../spectrum/)** /
