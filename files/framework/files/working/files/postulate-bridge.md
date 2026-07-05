/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /

---

# The Postulate Bridge

**Status (2026-07-01):** Resolved along the staged route, as a split. The two bedrock results sit on the two pieces of the postulate $S^1 = \partial(\text{Möbius}) \hookrightarrow S^3$, $\partial S^3 = \emptyset$. The gauge dictionary is proved: the $E_8$ filling carries the boundary's Galois asymmetry exactly, on $\partial W = +\Sigma$ ($\Delta\rho = -8/5 = 4\,\Delta D$, and $k \equiv cs \bmod 1$ in all four sectors). The Möbius coupling is refuted route-specifically: on the characteristic slot, every coefficient built on $W$ restricts rank-trivially, so the surface term cancels from the Galois difference in every restriction-route identity with the canonical pullback coefficient bundle. No universal independence claim is made. The naive bridge through the shared value $2/R^2$ remains dead (a forced curvature-scale coincidence, not a spectral link). Steps 1-4 complete ([Step 4, part two](step4-coupling.md)); the split verdict is paper-ized as the third bedrock pillar, [Galois pair](../../bedrock/files/galois-pair.md); this note is the record of the route.

**Related:** [First eigenvalue](../../bedrock/files/first-eigenvalue.md), [Coexact gap](../../bedrock/files/coexact-gap.md), [Galois pair](../../bedrock/files/galois-pair.md), [bedrock README](../../bedrock/README.md).

---

## What exists

Two standalone spectral-geometry results, each proved, cited here by content.

**The surface.** The first positive eigenvalue of the twisted Laplacian on a constant-curvature Möbius band $M(W) \subset S^2(R)$ is $2/R^2$ in the narrow regime, stable across the Friedrichs and bridging self-adjoint extensions for $\delta_0 > 2R/e$. The eigenfunction is $\sin(y/R)$, the $\ell = 1$ zonal mode, on the symmetric extension-independent tower; the Friedrichs realization is unitarily equivalent to the Neumann Laplacian on a spherical lune. The framework reads $2/R^2$ as the cosmological-constant anchor.

**The space.** The coexact $1$-form gap on $S^3/\Gamma$ twisted by a flat bundle $E_\tau$ is $q_\tau^2/R^2$, with $q_\tau$ the first McKay occurrence level. For the adjoint of an irreducible flat $\mathrm{SU}(2)$ connection this is $4/R^2$ across the ADE classification, with one exception: $36/R^2$ for the Galois connection on $S^3/2I$, whose adjoint sits at McKay distance six in affine $E_8$. The framework reads the gap as the Yang-Mills mass gap.

The postulate nests the two objects: the seam $S^1 = \partial(\text{Möbius})$, the Möbius surface it bounds, and the space $S^3$ in which the seam is anchored. The papers put operators on the surface and the space. The question is whether a theorem connects them.

---

## What was tried, and why it failed

**The arch (superseded).** An attempt to connect the two through the shared value $2/R^2$: the surface eigenvalue equals the Bochner/Weitzenböck Ricci floor on $S^3$, a coincidence special to dimension three. The grand reading does not survive. The surface eigenvalue is $\Gamma$-blind, the Ricci floor is the only $\Gamma$-independent slot in the gap, so the match is forced rather than discovered: a curvature-scale coincidence, not a spectral relationship. The corpus already half-states it (the coexact paper notes the floor is numerically the surface eigenvalue but a different operator and only a loose lower bound; the eigenvalue paper records $2/R^2 = R_{\mathrm{sm}}$). The modest survivor, a rigid floor across ADE plus a dimension-three realization, is true but does not connect the two operators.

**The deeper obstruction.** The band lives upstairs on a great $S^2 \subset S^3$; the coexact gap lives downstairs on $S^3/\Gamma$. No great $S^2$ is $2I$-stable (left translation by any non-central element moves the defining $3$-plane in $\mathbb{R}^4$), so the surface does not descend to the quotient as a submanifold. "Restrict to a great $S^2$" and "take $2I$-invariants" are independent operations on the $\mathrm{SU}(2)_L \times \mathrm{SU}(2)_R$ content of $S^3$; they compose only if the surface is group-stable, and it is not.

---

## Three routes

### Route 1, spectral restriction via $\mathbb{Z}_2$ holonomy: closed

The idea was to link the band's orientation $\mathbb{Z}_2$ holonomy to a non-orientable or flat-bundle structure on the quotient. Two walls. First, $S^3/2I$ is orientable (an integral homology sphere), so there is no non-orientable structure downstairs to host the band's twist. Second, $2I$ is perfect ($H^1(2I) = 0$), so it has no $\mathbb{Z}_2$ quotient and no order-two character; the band's $\mathbb{Z}_2$ cannot be a $2I$-equivariant datum. The perfectness that makes $2I$ the unique gauge exception in the coexact paper is exactly what forbids the orientation bridge.

### Route 2, heat kernel: set aside

Heat traces relate a space to its covers and subspaces. The band is neither a cover nor a subspace of $S^3/2I$. The leading asymptotics mismatch ($t^{-1}$ for a surface versus $t^{-3/2}$ for the $3$-manifold), and the trace formula organizes the twisted spectrum by conjugacy classes and closed geodesics, with no slot for an embedded surface.

### Route 3, APS index theory on the $E_8$ plumbing: run, resolved as a split

**Why this is the route.** $S^3/2I$ bounds a compact oriented $4$-manifold $W$, the $E_8$ plumbing, whose intersection form is the $E_8$ lattice. This is not a second, coincidental $E_8$. The McKay correspondence identifies it with the one the coexact paper uses: the minimal resolution of the $\mathbb{C}^2/2I$ Kleinian singularity has eight exceptional $(-2)$-curves in bijection with the eight nontrivial irreps of $2I$, their intersection matrix is the negative of the finite $E_8$ Cartan matrix (self-intersections $-2$, off-diagonal $+1$ for $E_8$-adjacency), and the affine node of the McKay graph is the trivial irrep that the resolution drops. So the Galois node $\mathrm{Sym}^2 Q'$ at McKay distance six corresponds to a definite homology class in $H_2(W)$. The research question is whether the APS machinery respects that identification, not whether a map between two $E_8$s exists.

The boundary carries the gauge spectral data, the interior the topology. The APS index theorem relates:

- Boundary: the eta-invariant of the adjoint curl $\ast d_\nabla$ on $S^3/2I$. This is the spectral *asymmetry* of its signed first-order spectrum (eigenvalues $\pm m/R$), not the bottom eigenvalue. The coexact gap is the bottom of $(\ast d_\nabla)^2 = \Delta_\tau$, a different functional of the same operator. Both are connection-sensitive, but they are distinct features.
- Interior: signature, intersection form, characteristic classes, and the homology classes of embedded surfaces (self-intersection $[\Sigma]^2$, normal Euler number, $\mathbb{Z}_2$ class).

Fintushel-Stern is the foundational reference; Kirk-Klassen and Nasatyr compute adjoint spectral-flow and eta-invariant data on $S^3/2I$.

**The make-or-break question.** Does the APS index formula for the adjoint-twisted operator on $W$, with boundary contribution the $Q'$ eta-invariant, contain an interior term involving the homology class that the McKay correspondence assigns to the Galois node $\mathrm{Sym}^2 Q'$ (distance six)? If the boundary asymmetry distinguishing $Q'$ from $Q$ is matched in the formula by the interior class of the distance-six node, the embedding does real work and the postulate's two pieces are linked through the index. This is a computation, not a conceptual question.

**The eigenvalue question, tracked open not closed.** Whether the surface eigenvalue $2/R^2$ enters is subtler than "it cannot." The index theorem is topological on the interior, so it sees homology classes and characteristic numbers, not Laplacian eigenvalues directly. But $2/R^2$ is also the scalar curvature of $S^2(R)$, and scalar curvature enters Gauss-Bonnet and the Pontryagin/signature integrals, so a $2/R^2$ can surface in the interior term. The test is therefore not "does $2/R^2$ appear" but "is any appearance the curvature-scale coincidence again, forced because the band's eigenvalue equals its curvature by Obata, or is it tied to the specific surface class." Any appearance must clear that check before it counts as a spectral connection.

**Why it might work.** The bounding manifold is wired to the group not by a coincidence of Dynkin diagrams but by the McKay correspondence, a proved theorem: the exceptional $(-2)$-curves of the resolution are the eight nontrivial $2I$-irreps, and their intersection form is the negative $E_8$ Cartan matrix. So the $E_8$ plumbing is the structurally correct manifold and the Galois node is a definite class in it, not a numerical match to be hoped for. The question is whether any class in $H_2(W; \mathbb{Z}_2)$ carries a surface whose normal twist reproduces the Möbius band's $\mathbb{Z}_2$ holonomy and whose topological contribution constrains the boundary coexact eta.

**On the dimensional spread.** The $2$-dimensional surface, $3$-dimensional boundary, and $4$-dimensional interior are not a mismatch to explain away; they are the native operating range of APS and the G-signature theorem, which exist precisely to relate data across these dimensions. The open question is not that the dimensions differ but whether the specific surface class and the specific boundary operator land in the same formula with nontrivial coefficients. A precision question, not a structural objection.

---

## Staged plan

Ordered by decisiveness, not cost: the test that can kill the program runs first.

1. **Rho comparison, $Q$ versus $Q'$ (the gatekeeper): done, gate open.** The Step-1 boundary invariant is the APS odd-signature rho invariant for $\mathrm{ad}\,Q$ versus $\mathrm{ad}\,Q'$, equivalently the coexact adjoint-curl eta asymmetry after exact-sector cancellation and acyclicity. The difference is $8/5$, nonzero and supported entirely on the four golden ($\sqrt5$) conjugacy classes, the Galois locus that produces the $36/R^2$ gap; an independent Chern-Simons computation confirms it mod $\mathbb{Z}$ and fixes the unreduced normalization. The sign is fixed in Step 2: $\rho_{\mathrm{ad}Q'}-\rho_{\mathrm{ad}Q}=-8/5$ on the resolution-boundary orientation. Full calculation: [eta-gatekeeper](eta-gatekeeper.md).
2. **Analytic setup and sign (Step 2): done.** $W$ is simply connected, so the flat $Q'$ on $\partial W = S^3/2I$ does not extend flatly ($2I \to \mathrm{SU}(2)$ cannot factor through $\pi_1(W) = 1$). Framework: the ALE instanton on the minimal resolution of $\mathbb{C}^2/2I$ (Kronheimer-Nakajima), whose tautological bundles carry the McKay classes; the orbifold cone is demoted to a consistency check, having no interior $H_2$. Sign: on the resolution-boundary orientation $\rho_{\mathrm{ad}Q'}-\rho_{\mathrm{ad}Q}=-8/5$, with the $73/15$ magnitude anchored in print (BHKK's published $\pm 73/15$ on $X_{+1}=-\Sigma$, resolved by spectral-flow integrality). Full calculation: [Step 2](step2-analytic-setup.md).
3. **Homology of $W$ mod $2$ (Step 3): done.** $H_2(W;\mathbb{Z}_2)=\mathbb{Z}_2^8$ with the $E_8$ adjacency form: alternating and nondegenerate, unique characteristic class $0$, $W$ spin. Every class carries non-orientable embedded surfaces ($e+2\chi\equiv\mathfrak{P}\bmod 4$ under the mod-4 refinement), and the Brown/Guillou-Marin data of the characteristic-surface route is confined to the zero class. The Galois node is the short-arm curve, mod 2 one of the $120$ root classes, on which the automorphism group of the mod-2/mod-4 homology acts transitively: the interior homology is Galois-blind, and the Galois selection is carried by the McKay/tautological decoration alone. Full calculation: [Step 3](step3-interior-classes.md).
4. **The coupling identity (revised by Step 3), and the $2/R^2$ check.** Step 3 rules out the naive form of this step: the band's $\mathbb{Z}_2$ data and the Galois selection do not share a class, so there is no "insert the band's class and read the coupling." The revised test is a three-ingredient identity: write the APS index on $W$ in Step 2's framework and determine whether the boundary rho (Galois-sensitive, Step 1), the tautological distance-six data $\mathrm{ch}(\mathcal{R}_{d6})$ (Step 2), and the characteristic-slot Brown/Guillou-Marin data (where the band's normal twist lives, Step 3) appear in one identity with nontrivial coefficients. A negative at this bar is a result. Any $2/R^2$ that surfaces here still gets the curvature-scale-coincidence check. Part one (the bookkeeping) is done: the four carried items are closed and the three ingredients compute in one exact character-sum currency, with the conversion identity $\rho^{\mathrm{sign}}_\alpha=\dim\alpha+4(D_\alpha-\dim\alpha\,D_{\mathrm{triv}})$ translating the boundary rho into the KN currency (gate value $-8/5=4\,\Delta D$ on $+\Sigma$), the tautological charges reproducing the Chern-Simons web mod 1, and $\bar\mu=-1$ locked through Ruberman-Saveliev; see [Step 4, part one](step4-bookkeeping.md). Part two is done, and it decides the question: negative, route-specifically, with the positive residue proved. The triviality lemma (every coefficient built on $W$ restricts rank-trivially to the characteristic slot) makes every $F$-localized term rank-blind, so the Möbius data cancels from the Galois difference in every restriction-route identity with the canonical pullback coefficient bundle; the complementary channels are disjoint (root classes couple but carry no canonical Guillou-Marin package; orientable characteristic surfaces carry Arf, not Möbius, data). The gauge dictionary survives as theorems. No $2/R^2$ appeared; the curvature-scale-coincidence check discharges vacuously. Full calculation: [Step 4, part two](step4-coupling.md).
5. **Reading.** Atiyah-Patodi-Singer (1975), Fintushel-Stern, Kirk-Klassen, Nasatyr, Rokhlin and its non-orientable generalizations, Guillou-Marin.

---

## What the framework does and does not owe this

The framework's claim is "one shape, two consequences." The shared $S^3$ of radius $R$ is already true as a geometric fact without any theorem relating the two spectra, so this bridge would be a bonus the framework is glad to have and is undamaged by lacking. The two bedrock results stand independently.

If the index computation yields a genuine connection, the result relates the gauge eta to the band's topological embedding. If it yields a negative result, that is also a result, but state it route-specifically: the interior term is topological, and any $2/R^2$ in it reduces to the curvature-scale coincidence (provably, since the band's eigenvalue equals its curvature by Obata) rather than a spectral link to the surface paper. That route-specific negative is provable; a universal claim that the two spectra are independent is not.

This became the bedrock pillar [Galois pair](../../bedrock/files/galois-pair.md), written to that standard: no physics vocabulary, the mathematics leading, the two pillars cited by content, and the surface eigenvalue kept out of every index ingredient. The route it reports is the negative-and-positive split, not the $\Lambda \leftrightarrow$ mass-gap link, which the pillar does not claim.

---

*The computation has been run. The dictionary is proved, the coupling is refuted on its route, and the question outside that route stays open.*

---

/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /
