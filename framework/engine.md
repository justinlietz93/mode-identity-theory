# Mode Identity Theory

MIT is a shape formed on philosophical grounds before any prediction was computed. Topology determines the structure; observation supplies the scale; every coefficient is a consequence.

## The Shape

$$\Large \boxed{S^1 = \partial(\text{Möbius}) \hookrightarrow S^3, \quad \partial S^3 = \emptyset}$$

A temporal edge bounds a non-orientable surface embedded in a closed space. The space has no boundary. Two uniqueness theorems force the structure: the classification of compact surfaces forces the Möbius strip, and the Poincaré theorem forces $S^3$. There was only one choice.

**[Visualize the Shape](https://dmobius3.github.io/mode-identity-theory/tools/topology.html)**

This single choice produces one scaling law that blindly predicts $\Lambda$, $H_0$, $a_0$, and $\alpha$ across 122 orders of magnitude, and 24 fermion mass entries covering all 12 Standard Model fermions.

## Inputs

Three primitive constants and one measured scale. Everything else is accounting.

| Input | Value | Role |
|---|---|---|
| $c$ | 299,792,458 m/s | Propagation rate on the temporal edge $S^1$ |
| $\hbar$ | $1.055 \times 10^{-34}$ J s | Action quantum; converts mode number to energy |
| $G$ | $6.674 \times 10^{-11}$ m³ kg⁻¹ s⁻² | Curvature-energy dictionary at the Planck floor ($n = 0$) |
| $R_\Lambda$ | $\approx 5.3$ Gpc | Curvature radius of $S^3$, fixed from the CMB low-$\ell$ cutoff |

### Derived

| Const. | Definition | Value |
|---|---|---|
| $\ell_P$ | $\sqrt{\hbar G/c^3}$ | $1.616 \times 10^{-35}$ m |
| $t_P$ | $\ell_P/c$ | $5.391 \times 10^{-44}$ s |
| $a_P$ | $c/t_P$ | $5.561 \times 10^{51}$ m/s² |
| $\Omega_\Lambda$ | $(R_\Lambda/\ell_P)^2$ | $\approx 10^{122}$ |

## The Firing Order

Each step depends on the one before; nothing later exists independently from what came prior.

1. Topology sets what is possible
2. Embedding defines the structure
3. The cosmic wave expresses the boundary
4. Time is phase of the wave
5. Sampling resolves position in the domain
6. Meaning arises only after realization

## The Topology

### Space

$S^3$ is the only simply connected closed 3-manifold (Poincaré). It is diffeomorphic to SU(2) and admits a spin structure. The space has no boundary:

$$\Large \boxed{\partial S^3 = \emptyset}$$

The hierarchy terminates here. "What's outside?" is malformed; there is no boundary from which to observe.

### Surface

The Möbius strip is the minimal non-orientable surface with $S^1$ boundary (surface classification). Non-orientability is required: the anti-periodic boundary condition, the half-integer spectrum, and the $\mathbb{Z}_2$ holonomy all require a surface whose normal direction cannot be globally defined. Orientable surfaces produce only periodic boundary conditions and an integer spectrum. The Möbius strip is the only surface satisfying all three requirements.

The $\mathbb{Z}_2$ holonomy imposes the sign flip:

$$\psi(y + \pi R_\Lambda) = -\psi(y)$$

One traverse of the strip returns a field to the opposite side. Two traverses restore the original sign. The eigenvalue problem $-\partial_y^2 \psi = \lambda \psi$ under this boundary condition requires $e^{ik\pi R} = -1$, giving $k\pi R = (2m+1)\pi$. Mode numbers are half-integers: $\nu = 1/2, 3/2, 5/2, \ldots$ The constant mode is forbidden. Matter is fermionic because the surface is non-orientable.

### Temporal Edge

$S^1$ is the boundary of the Möbius surface: a closed loop with geometric circumference $\pi R_\Lambda$. The edge inherits the anti-periodic boundary condition. This is where time advances and where the observer is anchored.

### The Observable Domain

The physical space is $S^3/2I$: the hypersphere modulo the binary icosahedral group $2I$, the largest exceptional discrete subgroup of SU(2), with $|2I| = 120$. 

Four auxilarrily paths converge on this number (three independent): 
1. group theory of $S^3$ gives $|2I| = 120$ directly;
2. the least common multiple of the first five Fibonacci numbers $\text{lcm}(1,2,3,5,8) = 120$;
3. the consonance ratios of musical harmony independently yield $\text{lcm} = 120$.
4. The $(2,3,5)$ branch orders of the icosahedron are consecutive Fibonacci numbers satisfying $2+3=5$: the unique Platonic solid whose symmetry orders obey the Fibonacci recurrence.

The 120 domain is the mode spectrum's resolution. The smallest phase advance the domain can register is the chronon:

$$\Delta t_{\min} = \frac{4\pi}{120} = \frac{\pi}{30}$$

The corresponding minimum action $\Delta S_{\min} = \hbar\pi/30$ is absolute: a Lorentz scalar that holds in every frame.

Fermions see all 120 positions but observation squares the wavefunction: $|\psi(\Theta+1)|^2 = |\psi(\Theta)|^2$ erases the anti-periodic sign. The squaring projects $2I \to I$ ($|I| = 60$), halving the resolution. 

The minimum step a boson-projected observable can resolve is $2/120$. Cosmographic observables ($H_0$, $\Lambda$, $\alpha$) are photon-mediated and live on this 60-position grid. Dynamical observables ($a_0$) retain full 120-domain access.

### Confinement

Positive Ricci curvature on $S^3$ means every gauge fluctuation has a minimum eigenvalue. The Weitzenböck identity gives $\lambda \geq 2/R_\Lambda^2 > 0$ for all modes. The mass gap exists and equals $2/R_\Lambda^2$. No massless gauge mode can propagate freely on the bounded space. Confinement is geometric.

### Three Generations

Flat SU(2) connections on $S^3/2I$ are classified by conjugacy classes of homomorphisms from $2I$ into SU(2). There are exactly three: trivial, standard, and Galois. Each is isolated ($H^1 = 0$): no continuous moduli, no Goldstone bridges between families. Three particle generations from three topological vacua.

### The Mass Formula

Four factors, each traced independently to the postulate:

$$m(\rho, \sigma) = \mu_\Lambda \times C_{\text{geom}}(\rho) \times (\sqrt{\Omega_\Lambda})^{\,\text{dist}(\rho)/30} \times T^2(\rho \otimes \sigma)$$

The vacuum energy floor $\mu_\Lambda = \rho_\Lambda^{1/4} \approx 2.25$ meV sets the overall scale: the fourth root of $\Lambda$, traced to the ground mode of the Möbius surface. The Kostant phase factor $C_\text{geom}$ places each irreducible representation on the domain through its spectral exponents. The McKay elevator $(\sqrt{\Omega_\Lambda})^{\text{dist}/30}$ sets orders of magnitude by graph distance from the trivial representation, with the Coxeter number $h(E_8) = 30$ as denominator. Reidemeister torsion $T^2(\rho \otimes \sigma)$ provides fine structure within each mass shell: the generation splitter. The Galois pair ratio $T^2(R_3)/T^2(R_4) = \varphi^{-4}$ is exact to 70+ digits; the golden ratio enters through the Legendre character of $\mathbb{Q}(\sqrt{5})$, the character field of $2I$.

Applied to 8 nontrivial irreps across 3 vacua, the formula produces 24 mass entries. 12 map to Standard Model fermions; 10 land within a factor of 3; three (electron, up quark, muon) land within 6%. Full predictions and assignments in [spectrum.md](spectrum.md).

### Particle Identity

The icosahedron carries three stabilizer subgroups: faces ($Z_3$, order 3), edges ($Z_4$, order 4), and vertices ($Z_5$, order 5). Restricting each irrep to these subgroups assigns physical identity. The face decomposition separates color singlets (leptons) from color triplets (quarks), and color is generation-independent: the face geometry looks identical from all three vacua, matching the Standard Model. The edge stabilizer enforces spin-statistics: half-integer irreps carry complex $Z_4$ pairs ($D = 120$), integer-spin carry real content ($D = 60$). The vertex stabilizer $Z_5$ encodes the electroweak interface; the two nontrivial vacua are themselves the Galois conjugate pair $R_1$ and $R_2$, differing precisely in their $Z_5$ content. The dodecahedral angular defect $\pi/5$, halved by the Möbius twist to $\pi/10$, enters the weak coupling as $\cos(\pi/10)$.

The three stabilizer orders are the primes dividing $|2I| = 120$. They generate color, domain, and the electroweak interface. The mass formula computes how heavy. The stabilizer structure says what.
