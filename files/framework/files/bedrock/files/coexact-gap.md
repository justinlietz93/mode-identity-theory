/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /

---

<img src="https://img1.wsimg.com/isteam/ip/21cc2ac0-6dc4-4b19-93ef-6a7079ac9d3c/Coeaxact%20Gap.png" width="100%" alt="Coexact Gap">

On a spherical space form $`S^3/\Gamma`$ with the round metric of radius $`R`$, let $`E_\tau`$ be the flat bundle with holonomy a finite-dimensional representation $`\tau`$ of $`\Gamma`$, and consider the Hodge Laplacian on coexact $`1`$-forms valued in $`E_\tau`$. Its spectral gap is $`q_\tau^2/R^2`$, where $`q_\tau \ge 2`$ is the lowest coexact level carrying a constituent of $`\tau`$. A constituent at distance $`d`$ enters at level $`d`$ for $`d \ge 2`$ and at level $`2`$ for $`d = 0`$, for any finite $`\Gamma`$; when $`-I \in \Gamma`$, equivalently when the McKay graph is bipartite, a distance-one constituent enters at level $`3`$. Here $`q_\tau`$ is the minimum of these entry levels over the constituents of $`\tau`$, so in particular the gap is $`d_\tau^2/R^2`$ whenever $`d_\tau \ge 2`$.

The adjoint bundle of an irreducible flat $`\mathrm{SU}(2)`$ connection always has $`d_\tau \ge 2`$, so its gap is the squared adjoint distance. Across the ADE classification of finite subgroups of $`\mathrm{SU}(2)`$ this gap is $`4/R^2`$ for every irreducible flat connection, with one exception: the Galois connection on the Poincaré homology sphere $`S^3/2I`$ gives $`36/R^2`$, its adjoint on the short branch of affine $`E_8`$; here $`2I`$ is the unique nontrivial perfect finite subgroup of $`\mathrm{SU}(2)`$. The ingredients are classical: the form spectra of Ikeda and Taniguchi, the representation-theoretic descent of Lauret, Miatello and Rossetti, and the McKay correspondence. The new content is the uniform expression of the coexact gap through the first coexact occurrence level $`q_\tau`$, its McKay-distance form in the bipartite cases, the adjoint application, and the icosahedral case as the one exception.

---

## 1. Introduction

Let $`\Gamma \subset \mathrm{SU}(2)`$ be finite and let $`S^3/\Gamma`$ carry the round metric of constant curvature $`1/R^2`$, with $`\Gamma`$ acting by left multiplication through the fixed inclusion, so the McKay graph is that of the inclusion. A finite-dimensional unitary representation $`\tau`$ of $`\Gamma`$ determines a flat bundle $`E_\tau`$ on $`S^3/\Gamma`$; the flat adjoint bundle of a flat $`\mathrm{SU}(2)`$ connection $`\rho`$ is the case $`\tau = \mathrm{Ad} \circ \rho`$. The twisted harmonic $`1`$-forms vanish for every $`\tau`$ (Lemma 2.1), so the Hodge Laplacian $`\Delta_\tau`$ on coexact $`E_\tau`$-valued $`1`$-forms is positive, and we study the bottom of its spectrum.

On round $`S^3`$ of radius $`R`$ the coexact $`1`$-forms have eigenvalues $`m^2/R^2`$ for integers $`m \ge 2`$, and the level-<i>m</i> space has left content $`V_m\vert_\Gamma`$ and $`V_{m-2}\vert_\Gamma`$, up to the right-factor multiplicities, with $`V_j = \mathrm{Sym}^j \mathbb{C}^2`$ [IkedaTaniguchi]. The modes on $`S^3/\Gamma`$ are the $`\Gamma`$-invariants $`(E_m \otimes \tau)^\Gamma`$, and by Peter-Weyl, Frobenius reciprocity, and the self-duality of the $`V_j`$ these are nonzero exactly when a constituent of $`\tau`$ occurs in $`V_m\vert_\Gamma`$ or $`V_{m-2}\vert_\Gamma`$. Section 3 gives this descent, already present for form spectra in Ikeda [Ikeda1989], with the Dirac analogue due to Bär [Bar1996] and the representation-equivalence form due to Lauret, Miatello and Rossetti [LauretMiatelloRossetti]. Here the descent carries an arbitrary finite-dimensional twist by the diagonal action.

For a flat bundle $`E_\tau`$, set

```math
q_\tau = \min\lbrace\, m \ge 2 :\ \mathrm{Hom}_\Gamma(\tau^*,\, V_m\vert_\Gamma \oplus V_{m-2}\vert_\Gamma) \ne 0 \,\rbrace,
```

equivalently, since the $`V_j`$ are self-dual, the least coexact level at which a constituent of $`\tau`$ meets the left content. The spectral gap of $`\Delta_\tau`$ on coexact $`1`$-forms is $`q_\tau^2/R^2`$.

When $`-I \in \Gamma`$, equivalently when the McKay graph is bipartite, the entry level is read constituentwise from the McKay distance: a constituent at distance $`d \ge 2`$ enters at $`m = d`$, a trivial constituent at $`m = 2`$, a distance-one constituent at $`m = 3`$, and $`q_\tau`$ is the minimum of these entry levels over the constituents. Thus the value $`9/R^2`$ at $`d_\tau = 1`$ requires that no distance-two constituent be present. Proposition 4.2 proves this and treats the non-bipartite case.

In particular, the untwisted bundle $`\tau = \mathbf{1}`$ has $`q_{\mathbf{1}} = 2`$ for every $`\Gamma`$, since the trivial representation lies in $`W_2`$ through its $`V_0`$ summand. The untwisted coexact $`1`$-form gap is therefore $`4/R^2`$ on every $`S^3/\Gamma`$ considered here, independently of $`\Gamma`$; when $`\Gamma \ne \lbrace 1\rbrace`$ this is also the gap of the full untwisted $`1`$-form Laplacian, since the exact summand starts at some level $`k \ge 2`$, with eigenvalue at least $`8/R^2`$ (Section 3.2).

The flat adjoint bundle is the case $`\tau = \mathrm{Ad} \circ \rho`$, with $`(\mathrm{ad}_\rho)_{\mathbb{C}} \cong \mathrm{Sym}^2 \rho`$. For an irreducible connection this representation carries no trivial summand and sits on even-distance nodes, so the adjoint distance is at least two. Proposition 4.3 then reduces the adjoint coexact gap to a McKay-distance calculation. Section 4 carries this calculation across the ADE classification: by the McKay correspondence, each finite subgroup of $`\mathrm{SU}(2)`$ has an associated affine Dynkin diagram of type $`\widetilde{A}`$, $`\widetilde{D}`$, or $`\widetilde{E}`$ (Section 2.1). The gap is $`4/R^2`$ for every irreducible flat connection, with one exception. For the binary icosahedral group $`2I`$, which is perfect, no one-dimensional character relates the defining connection $`Q`$ to its Galois conjugate $`Q^\prime`$; the adjoint $`\mathrm{Sym}^2 Q^\prime`$ sits at distance six in affine $`E_8`$, so the Galois connection on the Poincaré homology sphere $`S^3/2I`$ has gap $`36/R^2`$.

The three ingredients, the form spectra of Ikeda and Taniguchi, the representation-theoretic descent of Lauret, Miatello and Rossetti, and the McKay correspondence, are classical. They combine into a single rule: the coexact gap is the square of the first occurrence level, and the adjoint classification across the ADE list follows.

The distinguished status of $`\Sigma(2,3,5) = S^3/2I`$ is familiar in gauge theory: among spherical space forms with nontrivial fundamental group it is the unique integral homology sphere, singled out by Fintushel and Stern [FintushelStern] in the instanton-Floer setting, where adjoint-coefficient spectral-flow computations appear in Nasatyr [Nasatyr1992] and Kirk and Klassen [KirkKlassen], with the binary polyhedral character and flat-connection data recorded by Helle [Helle]. On the spectral side the nearest computations are the untwisted Hodge Laplacian on $`1`$-forms of homogeneous $`3`$-spheres [HenkelLauret2026], the $`p`$-form spectra of lens spaces [LauretLens2018], and Lauret's character-twisted Laplacian on functions over cyclic groups [LauretCyclic]; the present note fixes the round metric and treats coexact $`1`$-forms, twisted in the adjoint case by $`\mathrm{Sym}^2 \rho`$ on the nonabelian groups.

On the coexact $`1`$-form summand the operator is the square of the curl-type first-order operator $`\ast d_\nabla`$, so the gap records the square of the bottom absolute coexact curl eigenvalue; in the $`d_\tau \ge 2`$ case that eigenvalue is $`d_\tau/R`$. The bottom eigenvalue follows from the classical restricted form spectrum together with the McKay correspondence. In the adjoint case the coexact gap is the bottom eigenvalue of the gauge-fixed Laplacian on the Coulomb slice.

The objects throughout are flat bundles on spherical space forms carrying their round metrics, and the spectrum studied is that of the Hodge Laplacian on the coexact $`1`$-form summand. Section 2 fixes the metric, the bundles, and the operator. Section 3 records the $`S^3`$ coexact spectrum and the descent to $`S^3/\Gamma`$. Section 4 proves the gap for a general flat bundle and derives the adjoint comparison across the classification.

---

## 2. Setup

### 2.1 The space and the McKay graph

Identify $`S^3`$ with $`\mathrm{SU}(2)`$ carrying the bi-invariant metric of constant sectional curvature $`1/R^2`$. Let $`\Gamma \subset \mathrm{SU}(2)`$ be a finite subgroup acting on $`S^3`$ by left translation, and write $`X = S^3/\Gamma`$ for the resulting spherical space form, a closed oriented $`3`$-manifold of constant curvature $`1/R^2`$ with $`\pi_1(X) = \Gamma`$. The finite subgroups are the cyclic groups $`\mathbb{Z}_n`$, the binary dihedral groups $`D_n^*`$ of order $`4n`$, and the binary tetrahedral, octahedral, and icosahedral groups $`2T, 2O, 2I`$ of orders $`24, 48, 120`$.

Let $`V_j = \mathrm{Sym}^j \mathbb{C}^2`$ be the irreducible $`\mathrm{SU}(2)`$ representation of dimension $`j+1`$, so $`V_1`$ is the defining representation. The *McKay graph* of $`\Gamma`$ has the irreducible representations of $`\Gamma`$ as vertices, the trivial representation as distinguished vertex, and $`m_{\sigma\sigma^\prime} = \dim \mathrm{Hom}_\Gamma(\sigma^\prime,\, V_1\vert_\Gamma \otimes \sigma)`$ edges between $`\sigma`$ and $`\sigma^\prime`$. By the McKay correspondence [McKay] it is the affine Dynkin diagram attached to $`\Gamma`$. The graph is bipartite exactly when $`-I \in \Gamma`$. If $`-I \in \Gamma`$, then $`-I`$ acts by a scalar on each irreducible $`\Gamma`$-representation, and tensoring with $`V_1`$ changes this scalar; the two central characters give the bipartition, so the scalar on a vertex at distance $`d`$ from the trivial vertex is $`(-1)^d`$. The subgroups omitting $`-I`$ are exactly the odd cyclic groups $`\mathbb{Z}_n`$, since every binary family contains $`-I`$ and $`\mathbb{Z}_n`$ contains $`-I`$ if and only if $`n`$ is even; for these groups the McKay graph is the odd cycle $`\widetilde{A}_{n-1}`$. Graph distances $`d(\sigma)`$ from the trivial vertex are taken on the underlying unweighted graph, and for a representation $`\tau`$ we set

```math
d_\tau = \min\lbrace\, d(\sigma) : \sigma \text{ a constituent of } \tau \,\rbrace.
```

### 2.2 Flat bundles and the adjoint

A finite-dimensional unitary representation $`\tau \colon \Gamma \to \mathrm{U}(V)`$ determines a flat Hermitian bundle $`E_\tau = (S^3 \times V)/\Gamma`$ on $`X`$, with the flat connection $`\nabla`$ descended from the trivial connection upstairs. Gauge-equivalence classes of flat $`\mathrm{SU}(2)`$ connections on $`X`$ are identified with conjugacy classes of homomorphisms $`\rho \colon \Gamma \to \mathrm{SU}(2)`$; the real adjoint bundle $`\mathrm{ad}_\rho`$ has fibre $`\mathfrak{su}(2)`$ and holonomy $`\mathrm{Ad} \circ \rho`$. We work with the complexification, the flat bundle $`E_\tau`$ for

```math
\tau = (\mathrm{ad}_\rho)_{\mathbb{C}} \cong \mathrm{Sym}^2 \rho \quad \text{as a complex } \Gamma\text{-representation,}
```

the isomorphism being the identification of $`\mathfrak{su}(2)_{\mathbb{C}} = \mathfrak{sl}(2, \mathbb{C})`$ with the spin-1 representation $`V_2`$ of the $`\mathrm{SU}(2)`$ acting through $`\rho`$.

### 2.3 The operator and positivity

Let $`d_\nabla`$ be the flat exterior derivative of $`E_\tau`$ and $`\Delta_\tau = d_\nabla^* d_\nabla + d_\nabla d_\nabla^*`$ the twisted Hodge Laplacian. For the flat unitary connection the Hodge decomposition reads

```math
\Omega^1(X; E_\tau) = \mathrm{im} d_\nabla\ \oplus\ \mathrm{im} d_\nabla^*\ \oplus\ \mathcal{H}^1(X; E_\tau),
```

with $`\Delta_\tau`$ preserving each summand; the coexact $`1`$-forms are $`\mathrm{im} d_\nabla^*`$.

This summand carries the only part of the twisted $`1`$-form spectrum that lies beyond functions. The Laplacian preserves the three summands in the Hodge decomposition, and the exact and harmonic summands are already determined. On the exact summand $`\mathrm{im} d_\nabla`$, the identity $`\Delta_\tau(d_\nabla f) = d_\nabla(\Delta_\tau f)`$ sends each positive twisted $`0`$-form eigenvalue to the same $`1`$-form eigenvalue, while $`d_\nabla`$ annihilates the zero modes. Thus the exact summand reproduces the positive part of the twisted function spectrum. The harmonic summand $`\mathcal{H}^1(X; E_\tau)`$ vanishes for every finite-dimensional $`\tau`$, since $`\Gamma`$ is finite and the coefficients have characteristic zero, as in Lemma 2.1. The coexact summand $`\mathrm{im} d_\nabla^*`$ therefore carries the entire twisted $`1`$-form spectrum beyond functions.

On that summand the curl operator $`\ast d_\nabla`$ is formally self-adjoint and satisfies the standard three-dimensional curl identity [Bar2019, CapoferriVassiliev], which extends formally to flat unitary bundles

```math
(\ast d_\nabla)^2 = d_\nabla^* d_\nabla = \Delta_\tau \qquad \text{on coexact 1-forms},
```

so the coexact spectrum of $`\Delta_\tau`$ is the set of squares of the $`\ast d_\nabla`$ spectrum, and the bottom coexact eigenvalue is the square of the smallest $`\lvert\ast d_\nabla\rvert`$.

> **Lemma 2.1** (Vanishing of harmonic $`1`$-forms)**.** For every finite-dimensional $`\tau`$, $`H^1(X; E_\tau) = 0`$. Consequently the coexact $`1`$-forms coincide with the coclosed $`1`$-forms, and $`\Delta_\tau`$ is strictly positive on them.

*Proof.* By de Rham with local coefficients $`\mathcal{H}^1(X; E_\tau) \cong H^1(X; E_\tau)`$, and degree-one cohomology with local coefficients is computed by crossed homomorphisms, hence depends only on $`\pi_1 X = \Gamma`$; so $`H^1(X; E_\tau) \cong H^1(\Gamma; \tau)`$. Since $`\Gamma`$ is finite and the coefficients have characteristic zero, averaging over $`\Gamma`$ gives $`H^1(\Gamma; V) = 0`$ for every finite-dimensional $`\Gamma`$-module $`V`$; hence $`H^1(X; E_\tau) = \mathcal{H}^1(X; E_\tau) = 0`$. The kernel of $`\Delta_\tau`$ on $`1`$-forms is exactly $`\mathcal{H}^1`$, so $`\Delta_\tau`$ is strictly positive on $`\Omega^1(X; E_\tau)`$, and in particular on the coexact summand; and with $`\mathcal{H}^1 = 0`$ that summand $`\mathrm{im} d_\nabla^*`$ is the full space $`\ker d_\nabla^*`$ of coclosed $`1`$-forms. $`\square`$

---

## 3. The coexact spectrum and its descent

### 3.1 The coexact spectrum on $`S^3`$

Write $`L^2(S^3) = \bigoplus_{k \ge 0} V_k \boxtimes V_k^*`$ for the Peter-Weyl decomposition of functions, fixing the convention that $`\mathrm{SU}(2)_L`$ acts by left translation on the first factor and the commuting right $`\mathrm{SU}(2)`$-action on the second. Trivialize $`T^* S^3`$ by the left-invariant coframe, so $`\Omega^1(S^3; \mathbb{C}) \cong C^\infty(S^3) \otimes \mathfrak{su}(2)^*_{\mathbb{C}}`$, the coframe carrying the trivial left action and the right adjoint representation $`V_2`$. Peter-Weyl then gives

```math
\Omega^1(S^3; \mathbb{C}) \cong \bigoplus_{k \ge 0} V_k \boxtimes (V_k \otimes V_2),
```

and Clebsch-Gordan splits $`V_k \otimes V_2 \cong V_{k+2} \oplus V_k \oplus V_{k-2}`$, the last term omitted for $`k < 2`$. The exterior derivative $`d \colon C^\infty(S^3) \to \Omega^1(S^3)`$ is $`\mathrm{SU}(2)_L \times \mathrm{SU}(2)_R`$-equivariant and injective on nonconstants, and $`V_k \boxtimes V_k`$ occurs once in $`\Omega^1`$, so $`\mathrm{im} d`$ is exactly the middle summands $`V_k \boxtimes V_k`$. The harmonic $`1`$-forms vanish since $`H^1(S^3) = 0`$, so the coexact $`1`$-forms are the outer summands $`V_k \boxtimes V_{k \pm 2}`$. Reindexing, the coexact level $`m \ge 2`$ is

```math
E_m = \bigl(V_m \boxtimes V_{m-2}\bigr)\ \oplus\ \bigl(V_{m-2} \boxtimes V_m\bigr),
```

the first factor carrying left translation and the second the commuting right action. Each summand is a distinct $`\mathrm{SU}(2)_L \times \mathrm{SU}(2)_R`$ irreducible, so by Schur the curl $`\ast d`$ is scalar on each; its value is $`\pm m/R`$ by Ikeda and Taniguchi [IkedaTaniguchi], and with $`(\ast d)^2 = \Delta`$ the eigenvalue is $`m^2/R^2`$. The two summands are the $`\pm m/R`$ eigenspaces of $`\ast d`$, up to the orientation convention. The lowest level $`m = 2`$ gives $`E_2 = (V_2 \boxtimes V_0) \oplus (V_0 \boxtimes V_2)`$ and eigenvalue $`4/R^2`$.

### 3.2 Descent to $`X = S^3/\Gamma`$

Fix the associated-bundle convention $`\gamma \cdot (x, v) = (\gamma x, \tau(\gamma) v)`$ on $`E_\tau = (S^3 \times V_\tau)/\Gamma`$, so sections of $`E_\tau`$ identify with $`\Gamma`$-invariant $`V_\tau`$-valued forms on $`S^3`$ for the diagonal action, $`\Gamma`$ acting by left translation on the form and by $`\tau`$ on $`V_\tau`$. Left translation commutes with the curl and preserves each $`E_m`$. Pulling $`E_\tau`$ back to $`S^3`$ trivializes it with the product flat connection, so the lifted twisted Laplacian is $`\Delta_{S^3} \otimes 1`$ on $`V_\tau`$-valued forms. Thus the level-<i>m</i> twisted eigenspace on $`S^3/\Gamma`$ is

```math
\bigl(E_m \otimes V_\tau\bigr)^\Gamma, \qquad \text{eigenvalue }\ m^2/R^2.
```

This is the descent of the $`p`$-spectrum of a constant-curvature space form, due to Ikeda [Ikeda1989] and given its representation-equivalence form by Lauret, Miatello and Rossetti [LauretMiatelloRossetti], with the coefficient $`V_\tau`$ inserted by the diagonal action.

Under left translation only the first factor of each piece of $`E_m`$ is acted on, so the right factors are flat multiplicity spaces:

```math
E_m\big\vert_\Gamma = \bigl(V_m\big\vert_\Gamma\bigr)^{\oplus(m-1)}\ \oplus\ \bigl(V_{m-2}\big\vert_\Gamma\bigr)^{\oplus(m+1)},
```

the *left types* $`V_m\vert_\Gamma`$ and $`V_{m-2}\vert_\Gamma`$ carrying the right-factor multiplicities $`\dim V_{m-2} = m-1`$ and $`\dim V_m = m+1`$. The dimensions close, $`(m-1)(m+1) + (m+1)(m-1) = 2(m^2-1)`$, the Ikeda-Taniguchi multiplicity of the level-<i>m</i> coexact eigenvalue. Computing the invariants by restriction and the tensor-hom adjunction,

```math
\bigl(E_m \otimes V_\tau\bigr)^\Gamma \cong \mathrm{Hom}_\Gamma\!\bigl(\tau^*,\, E_m\vert_\Gamma\bigr),
```

nonzero exactly when $`\tau^*`$ shares a constituent with the left content $`W_m := V_m\vert_\Gamma \oplus V_{m-2}\vert_\Gamma`$. Each $`V_j`$ is self-dual, so $`W_m`$ is self-dual as a $`\Gamma`$-module; hence $`\tau^*`$ meets $`W_m`$ iff $`\tau`$ meets $`W_m^* = W_m`$, and the criterion reads

```math
\bigl(E_m \otimes V_\tau\bigr)^\Gamma \ne 0 \iff \text{a constituent of } \tau \text{ occurs in } W_m.
```

The reduction uses the self-duality of the left content, not of $`\tau`$, so it holds for arbitrary $`\tau`$; the adjoint case is self-dual only incidentally.

> **Proposition 3.1** (Twisted coexact spectrum)**.** For $`m \ge 2`$, the multiplicity of the eigenvalue $`m^2/R^2`$ in the $`E_\tau`$-valued coexact $`1`$-form spectrum on $`X`$ is
>
> ```math
> \mu_\tau(m) = (m-1)\dim \mathrm{Hom}_\Gamma\!\bigl(\tau^*, V_m\vert_\Gamma\bigr) + (m+1)\dim \mathrm{Hom}_\Gamma\!\bigl(\tau^*, V_{m-2}\vert_\Gamma\bigr).
> ```
>
> As a set of eigenvalues the twisted coexact spectrum is
>
> ```math
> \bigl\lbrace\, m^2/R^2 :\ m \ge 2,\ \mathrm{Hom}_\Gamma\!\bigl(\tau^*, W_m\bigr) \ne 0 \,\bigr\rbrace,
> ```
>
> equivalently those $`m`$ at which a constituent of $`\tau`$ occurs in $`W_m = V_m\vert_\Gamma \oplus V_{m-2}\vert_\Gamma`$. Its bottom is $`q_\tau^2/R^2`$, where
>
> ```math
> q_\tau = \min\bigl\lbrace\, m \ge 2 :\ \text{a constituent of } \tau \text{ occurs in } W_m \,\bigr\rbrace.
> ```

*Proof.* The multiplicity formula follows from the decomposition of $`E_m\vert_\Gamma`$ and the tensor-hom adjunction above, and the eigenvalue criterion by forgetting the right-factor multiplicities. It remains to see that the defining set for $`q_\tau`$ is nonempty: $`V_1\vert_\Gamma`$ is faithful, so by Burnside-Brauer every irreducible representation of $`\Gamma`$ occurs in some tensor power $`V_1^{\otimes k}\vert_\Gamma`$, and Clebsch-Gordan decomposes these into symmetric powers $`V_j\vert_\Gamma`$. Hence every irreducible occurs in some $`V_m\vert_\Gamma`$, and $`q_\tau`$ is finite; the sharp first occurrence, at $`m = d(\sigma)`$, is proved in Lemma 4.1. $`\square`$

For the trivial bundle, where $`\tau = \mathbf{1}`$, the descent recovers the classical untwisted coexact $`1`$-form spectrum, the $`\Gamma`$-invariant part $`(E_m)^\Gamma`$ of each round-sphere level $`E_m`$. The round-sphere levels are computed by Ikeda and Taniguchi [IkedaTaniguchi], the $`p`$-form spectra of spherical space forms by Ikeda [Ikeda1989], and those of lens spaces by Lauret [LauretLens2018]. The trivial representation occurs in $`W_2 = V_2\vert_\Gamma \oplus V_0\vert_\Gamma`$ through its $`V_0`$ summand, which is present for every $`\Gamma`$, so $`q_{\mathbf{1}} = 2`$ and the untwisted coexact gap is $`4/R^2`$ on every $`S^3/\Gamma`$ considered here.

For the full untwisted $`1`$-form spectrum we compare the coexact gap with the exact summand. The scalar level $`k`$ on $`S^3/\Gamma`$ is present precisely when $`V_k\vert_\Gamma`$ contains the trivial representation. If $`\Gamma \ne \lbrace 1\rbrace`$, then $`V_1\vert_\Gamma`$ has no nonzero invariant vector: such a vector would be fixed by every element of $`\Gamma`$, in particular by a nonidentity $`\gamma`$; but an element of $`\mathrm{SU}(2)`$ fixing a nonzero vector has eigenvalue $`1`$, and since $`\det \gamma = 1`$ both eigenvalues are $`1`$, so $`\gamma = I`$, a contradiction. The level-one scalar eigenvalue $`3/R^2`$ is therefore absent, the exact $`1`$-forms can only begin at level $`k \ge 2`$, and their eigenvalues are at least $`8/R^2`$. The coexact gap $`4/R^2`$ is thus the gap of the full untwisted $`1`$-form Laplacian for every nontrivial $`\Gamma \subset \mathrm{SU}(2)`$. For $`\Gamma = \lbrace 1\rbrace`$, the level-one scalar harmonics on $`S^3`$ give exact $`1`$-forms with eigenvalue $`3/R^2`$.

---

## 4. The gap and the ADE classification

### 4.1 First occurrence

Let $`A`$ be the McKay adjacency matrix, with entries $`A_{\sigma\sigma^\prime} = \dim \mathrm{Hom}_\Gamma(\sigma^\prime, V_1\vert_\Gamma \otimes \sigma)`$, so that multiplication by $`V_1`$ in the representation ring acts as $`A`$. The symmetric powers satisfy $`V_{a+1} = V_1 V_a - V_{a-1}`$, hence $`V_a = U_a(A)`$ applied to the trivial node, where $`U_a`$ is the degree-<i>a</i> polynomial of leading coefficient one with $`U_a(2\cos\theta) = \sin((a+1)\theta)/\sin\theta`$.

> **Lemma 4.1** (First occurrence)**.** For an irreducible $`\Gamma`$-representation $`\sigma`$ at McKay distance $`d(\sigma)`$, the least $`a`$ with $`\sigma \subset V_a\vert_\Gamma`$ is $`a = d(\sigma)`$. If moreover $`-I \in \Gamma`$, equivalently the McKay graph is bipartite, then $`\sigma \subset V_a\vert_\Gamma`$ forces $`a \equiv d(\sigma) \pmod 2`$.

*Proof.* The multiplicity of $`\sigma`$ in $`V_a\vert_\Gamma`$ is the matrix element $`(U_a(A))_{0\sigma}`$. Since $`U_a`$ has degree and parity $`a`$ and leading coefficient one, this is a combination of $`(A^a)_{0\sigma}, (A^{a-2})_{0\sigma}, \dots`$, and $`(A^k)_{0\sigma}`$ counts walks of length $`k`$ from $`0`$ to $`\sigma`$, which vanishes for $`k < d(\sigma)`$. Hence the multiplicity vanishes for $`a < d(\sigma)`$. At $`a = d(\sigma)`$ the lower terms $`(A^{d(\sigma)-2})_{0\sigma}, (A^{d(\sigma)-4})_{0\sigma}, \ldots`$ vanish, since their exponents are below $`d(\sigma)`$. The unit-coefficient leading term remains, so the multiplicity is $`(A^{d(\sigma)})_{0\sigma}`$, the positive count of walks of length $`d(\sigma)`$ from $`0`$ to $`\sigma`$. When $`-I \in \Gamma`$, the preceding bipartition gives that $`-I`$ acts on $`\sigma`$ by $`(-1)^{d(\sigma)}`$, while it acts on $`V_a\vert_\Gamma`$ by $`(-1)^a`$. Hence occurrence of $`\sigma`$ in $`V_a\vert_\Gamma`$ forces $`a \equiv d(\sigma) \pmod 2`$. $`\square`$

### 4.2 The gap

> **Proposition 4.2** (Gap from first occurrence)**.** Let $`\tau`$ be a finite-dimensional $`\Gamma`$-representation and $`d_\tau = \min\lbrace d(\sigma) : \sigma \text{ an irreducible constituent of } \tau \rbrace`$. For an irreducible constituent $`\sigma`$, let $`e(\sigma)`$ be the least $`m \ge 2`$ for which $`\sigma`$ occurs in $`W_m = V_m\vert_\Gamma \oplus V_{m-2}\vert_\Gamma`$. Then
>
> ```math
> e(\sigma) = 2 \quad \text{if } d(\sigma) = 0, \qquad e(\sigma) = d(\sigma) \quad \text{if } d(\sigma) \ge 2,
> ```
>
> with no hypothesis on $`\Gamma`$. If $`-I \in \Gamma`$, then also $`e(\sigma) = 3`$ for $`d(\sigma) = 1`$. Consequently
>
> ```math
> q_\tau = \min_{\sigma \subset \tau} e(\sigma),
> ```
>
> where the minimum runs over irreducible constituents. In particular, if $`d_\tau \ge 2`$, then $`q_\tau = d_\tau`$ and the bottom of the twisted coexact spectrum is $`d_\tau^2/R^2`$.

*Proof.* The equality $`q_\tau = \min_{\sigma \subset \tau} e(\sigma)`$ is just the definition of $`q_\tau`$. If $`d(\sigma) = 0`$, then $`\sigma`$ is the trivial representation and occurs in $`V_0`$, hence in $`W_2`$, and no level below $`2`$ is allowed. If $`d(\sigma) \ge 2`$, Lemma 4.1 places $`\sigma`$ first in $`V_{d(\sigma)}\vert_\Gamma`$, so $`W_{d(\sigma)}`$ contains $`\sigma`$ through its $`V_{d(\sigma)}`$ summand. For $`m < d(\sigma)`$, both $`m`$ and $`m-2`$ are below the first occurrence, so $`W_m`$ contains no copy of $`\sigma`$. Thus $`e(\sigma) = d(\sigma)`$. Finally assume $`-I \in \Gamma`$ and $`d(\sigma) = 1`$. The first occurrence is in $`V_1\vert_\Gamma`$, while the parity restriction excludes $`\sigma`$ from the even levels $`V_0\vert_\Gamma`$ and $`V_2\vert_\Gamma`$ appearing in $`W_2`$. Hence the first coexact level is $`m = 3`$, through the $`V_{m-2} = V_1`$ summand. $`\square`$

The bipartite hypothesis enters only for $`d_\tau \le 1`$. On $`\mathbb{Z}_3`$, where $`-I \notin \Gamma`$ and $`\widetilde{A}_2`$ is not bipartite, a nontrivial character has $`d = 1`$ but already occurs in $`V_2\vert_{\mathbb{Z}_3}`$, so $`q = 2`$ rather than $`3`$. The adjoint uses only the $`d_\tau \ge 2`$ case.

### 4.3 The adjoint

A flat $`\mathrm{SU}(2)`$ connection is irreducible precisely when $`\rho \colon \Gamma \to \mathrm{SU}(2)`$ is an irreducible $`2`$-dimensional representation. Its complexified adjoint is

```math
(\mathrm{ad}_\rho)_{\mathbb{C}} \cong \mathrm{Sym}^2 \rho,
```

a $`3`$-dimensional representation of $`\Gamma`$, irreducible for the polyhedral groups $`2T, 2O, 2I`$ and reducible for the binary dihedral groups, where $`\mathrm{Sym}^2 \tau_{2j-1}`$ contains a fixed distance-two sign character $`\varepsilon_D`$.

> **Proposition 4.3** (Adjoint gap)**.** For an irreducible flat $`\mathrm{SU}(2)`$ connection $`\rho`$ on $`X = S^3/\Gamma`$, the bottom of the adjoint coexact spectrum is $`d_{\mathrm{Sym}^2 \rho}^2/R^2`$, and $`d_{\mathrm{Sym}^2 \rho} \ge 2`$.

*Proof.* An irreducible $`2`$-dimensional $`\rho`$ forces $`\Gamma`$ nonabelian, hence binary dihedral or polyhedral, so $`-I \in \Gamma`$. Being central, $`-I`$ acts on the irreducible $`\rho`$ by a scalar, necessarily $`\pm I`$ since $`\det \rho = 1`$, so $`\mathrm{Sym}^2 \rho(-I) = I`$: the adjoint factors through $`\Gamma/\lbrace\pm I\rbrace`$, and as $`-I`$ acts on a distance-<i>d</i> node by $`(-1)^d`$, every constituent lies at even distance. The trivial is not among them: since $`\det \rho = 1`$ the representation $`\rho`$ is self-dual, so $`\mathrm{Hom}_\Gamma(\mathbf{1}, \rho \otimes \rho) \cong \mathrm{Hom}_\Gamma(\rho^*, \rho)`$ is one-dimensional by Schur, and as $`\rho \otimes \rho = \mathrm{Sym}^2 \rho \oplus \Lambda^2 \rho`$ with $`\Lambda^2 \rho = \det \rho = \mathbf{1}`$, that unique trivial summand is the determinant, lying in $`\Lambda^2`$. Even distance and no trivial constituent give $`d_{\mathrm{Sym}^2 \rho} \ge 2`$, and Proposition 4.2 returns the bottom $`d_{\mathrm{Sym}^2 \rho}^2/R^2`$. $`\square`$

### 4.4 The ADE table

The distance $`d_{\mathrm{Sym}^2 \rho}`$ is read from the McKay graph; for the binary polyhedral groups the graph and the flat $`\mathrm{SU}(2)`$ connections are tabulated by Helle [Helle]. Cyclic groups carry no irreducible flat $`\mathrm{SU}(2)`$ connection, their image being abelian. In every other case the nearest constituent of the adjoint sits at distance two, with a single exception.

The table lists only the $`2`$-dimensional irreducibles of determinant one, the flat connections valued in $`\mathrm{SU}(2)`$. For the binary dihedral groups these are the odd-index $`\tau_{2j-1}`$ with $`1 \le 2j-1 \le n-1`$, equivalently $`j = 1, \dots, \lfloor n/2 \rfloor`$; for $`2T`$ only the defining $`Q`$ qualifies, its twists by the nontrivial cube-root characters having determinant a cube root of unity; for $`2O`$ both $`Q`$ and $`Q \otimes \varepsilon`$ qualify, while the remaining $`2`$-dimensional irreducible has determinant the sign character; and $`2I`$, being perfect, has no nontrivial character to twist by, so both $`Q`$ and $`Q^\prime`$ have determinant one and appear.

The ADE classification and the labelling of flat $`\mathrm{SU}(2)`$ connections are standard. The table records the remaining datum needed here: the nearest irreducible constituent of $`\mathrm{Sym}^2 \rho`$ to the trivial node in the corresponding affine Dynkin diagram. The binary dihedral row is checked by characters below, while the binary polyhedral rows are read from the labelled diagrams and character tables, with the $`2I`$ exception verified explicitly after the table.

| $`\Gamma`$ | connection $`\rho`$ (dim, dist) | nearest adjoint constituent (dim, dist) | gap |
|---|---|---|---|
| $`\mathbb{Z}_n`$ ($`\widetilde{A}_{n-1}`$) | none | n/a | n/a |
| $`D_n^*`$ ($`\widetilde{D}_{n+2}`$) | $`\tau_{2j-1}\ (2,\, 2j-1)`$ | $`\varepsilon_D\ (1,\, 2)`$ | $`4/R^2`$ |
| $`2T`$ ($`\widetilde{E}_6`$) | $`Q\ (2, 1)`$ | $`\mathrm{Sym}^2 Q\ (3, 2)`$ | $`4/R^2`$ |
| $`2O`$ ($`\widetilde{E}_7`$) | $`Q\ (2, 1),\ Q \otimes \varepsilon\ (2, 5)`$ | $`\mathrm{Sym}^2 Q\ (3, 2)`$ | $`4/R^2`$ |
| $`2I`$ ($`\widetilde{E}_8`$) | $`Q\ (2, 1)`$ | $`\mathrm{Sym}^2 Q\ (3, 2)`$ | $`4/R^2`$ |
| $`2I`$ ($`\widetilde{E}_8`$) | $`Q^\prime\ (2, 7)`$ | $`\mathrm{Sym}^2 Q^\prime\ (3, 6)`$ | $`36/R^2`$ |

The binary dihedral row covers every odd index at once. In $`D_n^* = \langle a, b \mid a^{2n} = 1,\ b^2 = a^n,\ bab^{-1} = a^{-1}\rangle`$ the $`2`$-dimensional irreducible $`\tau_\ell`$ has $`\chi_{\tau_\ell}(a^k) = 2\cos(\pi\ell k/n)`$ and $`\chi_{\tau_\ell}(ba^k) = 0`$. From $`(ba^k)^2 = a^n`$ and $`\chi_{\tau_\ell}(a^n) = 2(-1)^\ell`$,

```math
\chi_{\mathrm{Sym}^2 \tau_\ell}(a^k) = 1 + 2\cos(2\pi\ell k/n), \qquad \chi_{\mathrm{Sym}^2 \tau_\ell}(ba^k) = (-1)^\ell.
```

For the connections $`\tau_{2j-1}`$, subtracting the distance-two sign character $`\varepsilon_D`$ ($`a \mapsto 1,\ b \mapsto -1`$) leaves a degree-two character, possibly reducible, while no constituent at distance zero or one occurs. The nearest constituent is $`\varepsilon_D`$ at distance two and the gap is $`4/R^2`$. Since $`Q`$ is the distance-one node adjacent to $`\mathbf{1}`$ in each polyhedral diagram, the decomposition $`Q \otimes Q \cong \mathbf{1} \oplus \mathrm{Sym}^2 Q`$ places the nontrivial summand $`\mathrm{Sym}^2 Q`$ at distance two. The two $`2O`$ connections share an adjoint, since $`\varepsilon^2 = \mathbf{1}`$ gives $`\mathrm{Sym}^2(Q \otimes \varepsilon) = \mathrm{Sym}^2 Q`$, again distance two. The binary icosahedral group is the exception: it is perfect, so it has no $`1`$-dimensional character to twist $`Q`$ by, and its only other irreducible $`\mathrm{SU}(2)`$ connection is the Galois conjugate $`Q^\prime`$, whose adjoint is a distinct node. The Galois adjoint $`\mathrm{Sym}^2 Q^\prime`$ sits at distance six, so the Galois connection has gap $`36/R^2`$. Explicitly, the character of $`V_a = \mathrm{Sym}^a \mathbb{C}^2`$ is

```math
\chi_a(\theta) = \frac{\sin((a+1)\theta)}{\sin\theta},
```

with the limiting values at $`\theta = 0, \pi`$. Evaluating it on the nine conjugacy classes of $`2I`$ and decomposing against the $`2I`$ character table (the nine classes have half-angles $`0, \pi/5, 2\pi/5, \pi/3, \pi/2, 2\pi/3, 3\pi/5, 4\pi/5, \pi`$, and the entries are the inner products of $`\chi_a`$ with the irreducible characters of $`2I`$ [Helle]) gives

| $`a`$ | $`\dim V_a`$ | $`V_a\vert_{2I}`$ | McKay distance(s) |
|:---:|:---:|:---:|:---:|
| 0 | 1 | $`\mathbf{1}`$ | 0 |
| 1 | 2 | $`Q`$ | 1 |
| 2 | 3 | $`\mathrm{Sym}^2 Q`$ | 2 |
| 3 | 4 | $`\mathbf{4}`$ | 3 |
| 4 | 5 | $`\mathbf{5}`$ | 4 |
| 5 | 6 | $`\mathbf{6}`$ | 5 |
| 6 | 7 | $`\mathbf{4}^\prime \oplus \mathrm{Sym}^2 Q^\prime`$ | 6, 6 |

where $`\mathbf{4}^\prime`$ denotes the second $`4`$-dimensional irreducible. Thus $`\mathrm{Sym}^2 Q`$ first occurs at level two, and $`\mathrm{Sym}^2 Q^\prime`$, the Galois conjugate of $`\mathrm{Sym}^2 Q`$, is absent from $`V_a\vert_{2I}`$ for $`a < 6`$ and first occurs in $`V_6\vert_{2I}`$.

Every irreducible flat $`\mathrm{SU}(2)`$ connection on a quotient $`S^3/\Gamma`$ with $`\Gamma \subset \mathrm{SU}(2)`$ thus has adjoint coexact gap $`4/R^2`$, with the single exception of the Galois connection on $`S^3/2I`$, whose gap is $`36/R^2 = 6^2/R^2`$.

These coexact gaps are also the gaps for the full adjoint $`1`$-form spectrum. As in Section 2.3, the Hodge decomposition splits the adjoint $`1`$-forms into exact, coexact, and harmonic parts; the harmonic part vanishes (Lemma 2.1), and the exact part carries the positive twisted function spectrum. On $`S^3`$ the scalar Laplacian has levels $`k(k+2)/R^2`$ for $`k \ge 0`$, with level-$`k`$ left content $`V_k\vert_\Gamma`$ [IkedaTaniguchi], so by Lemma 4.1 the adjoint first occurs in the function spectrum at level $`k = d_{\mathrm{Sym}^2\rho}`$, where the exact bottom is $`d_{\mathrm{Sym}^2\rho}(d_{\mathrm{Sym}^2\rho}+2)/R^2`$. Since $`d_{\mathrm{Sym}^2\rho} \ge 2`$ (Prop 4.3), this exceeds the coexact bottom $`d_{\mathrm{Sym}^2\rho}^2/R^2`$, so the coexact gap is the gap of the full adjoint $`1`$-form Laplacian:

| case | $`d_{\mathrm{Sym}^2\rho}`$ | coexact bottom | exact bottom | full $`1`$-form gap |
|---|---|---|---|---|
| ordinary ADE | $`2`$ | $`4/R^2`$ | $`8/R^2`$ | $`4/R^2`$ |
| $`2I`$ Galois | $`6`$ | $`36/R^2`$ | $`48/R^2`$ | $`36/R^2`$ |

---

## References

- **[Bar1996]** C. Bär, The Dirac operator on space forms of positive curvature. *J. Math. Soc. Japan* **48** (1996), 69–83.
- **[Bar2019]** C. Bär, The curl operator on odd-dimensional manifolds. *J. Math. Phys.* **60** (2019), no. 3, 031501.
- **[CapoferriVassiliev]** M. Capoferri and D. Vassiliev, Beyond the Hodge theorem: curl and asymmetric pseudodifferential projections. *J. Lond. Math. Soc.* **113** (2026), no. 1, e70431.
- **[FintushelStern]** R. Fintushel and R. Stern, Instanton homology of Seifert fibred homology three spheres. *Proc. London Math. Soc. (3)* **61** (1990), 109–137.
- **[Helle]** G. O. Helle, Equivariant instanton Floer homology and calculations for the binary polyhedral spaces. arXiv:2203.09471 (2022).
- **[HenkelLauret2026]** J. Henkel and E. A. Lauret, Hodge Laplacian on $`1`$-forms of homogeneous $`3`$-spheres. arXiv:2605.05406 (2026).
- **[Ikeda1989]** A. Ikeda, Riemannian manifolds $`p`$-isospectral but not $`(p+1)`$-isospectral. In *Geometry of Manifolds* (Matsumoto, 1988), Perspect. Math. **8**, Academic Press (1989), 383–417.
- **[IkedaTaniguchi]** A. Ikeda and Y. Taniguchi, Spectra and eigenforms of the Laplacian on $`S^n`$ and $`P^n(\mathbb{C})`$. *Osaka J. Math.* **15** (1978), 515–546.
- **[KirkKlassen]** P. Kirk and E. Klassen, Computing spectral flow via cup products. *J. Differential Geom.* **40** (1994), no. 3, 505–562.
- **[LauretCyclic]** E. A. Lauret, Spectra of orbifolds with cyclic fundamental groups. *Ann. Global Anal. Geom.* **50** (2016), no. 1, 1–28.
- **[LauretLens2018]** E. A. Lauret, The spectrum on $`p`$-forms of a lens space. *Geom. Dedicata* **197** (2018), 107–122.
- **[LauretMiatelloRossetti]** E. A. Lauret, R. J. Miatello and J. P. Rossetti, Representation equivalence and $`p`$-spectrum of constant curvature space forms. *J. Geom. Anal.* **25** (2015), no. 1, 564–591.
- **[McKay]** J. McKay, Graphs, singularities, and finite groups. *Proc. Sympos. Pure Math.* **37** (1980), 183–186.
- **[Nasatyr1992]** E. B. Nasatyr, Seifert-fibred homology 3-spheres, V-surfaces and the Floer index. *Math. Proc. Cambridge Philos. Soc.* **111** (1992), no. 3, 461–485.

---

/ **[`main`](/README.md)** / **[`framework`](/files/framework/)** / **[`bedrock`](/files/framework/files/bedrock/)** / **[`working`](/files/framework/files/working/)** / **[`cosmos`](/files/cosmos/)** / **[`spectrum`](/files/spectrum/)** / **[`tools`](/files/tools/)** /
