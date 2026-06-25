/ **[`main`](../../../../README.md)** / **[`framework`](../../../framework/)** / **[`working`](../)** / **[`cosmos`](../../../cosmos/)** / **[`spectrum`](../../../spectrum/)** /

---

# Fibonacci Wells: Forcing Worksheet

*Working note. Tracks the well-placement problem: where it stands, what has been ruled out, and the one residual that remains. Workbench voice (status tags, raw numbers); the [framework page](../../README.md) carries the settled version in prose.*

**Current status: STRUCTURALLY REDUCED, not DERIVED.** The old claim, "φ worst-approximability gives Fibonacci numerators on the fixed 120-grid," has been abandoned. The problem has been reduced to a sharper residual:

> Why does the post-lcm additive continuation of the icosahedral branch recurrence define the sampling wells?

The new frame is stronger because it keeps the wells internal to the locked structure. The 120-domain is already fixed by `S³/2I`; the branch orders `(2,3,5)` already live inside the icosahedral data; the Fibonacci continuation is therefore not imported from an external approximation argument. The same sequence first builds the domain, then samples it.

The Mirror note ([the-mirror.md](../../../spectrum/files/the-mirror.md)) adds two constraints that matter here:

1. the bulk spectral/character algebra is Θ-blind, so the well-selection functional cannot be a bulk spread, discrepancy, or energy functional;
2. φ is internal to `2I` through the character field `Q(√5)`, not an external Hurwitz postulate.

So the remaining target is not "find Fibonacci somehow." It is:

> define the boundary-native anti-periodic interference functional whose minima are the post-lcm recurrence positions.

---

## Dead mechanism: golden rotation / approximation (abandoned)

The old bridge is the wrong mechanism, not just unproven.

A rounded golden rotation steps by `round(120/φ) = 74`. Since `gcd(74,120) = 2`, its orbit is the 60 even residues mod 120: it misses the odd wells 13, 21, 55, and hits 34 only as one even residue among sixty. It selects a parity class, not the wells.

Structural reason: any single rotation orbit is an arithmetic progression mod 120. Nothing in an arithmetic progression prefers Fibonacci integers as positions. So the rotation/approximation framing is abandoned.

---

## Reframe: the recurrence builds, then samples

The wells are best understood as the additive continuation of the icosahedral branch orders on the locked 120-grid.

The branch/stabilizer orders are

```text
(2, 3, 5) = F₃, F₄, F₅
```

and they obey the Fibonacci recurrence:

```text
2 + 3 = 5.
```

Continuing the same recurrence gives

```text
2, 3, 5, 8, 13, 21, 34, 55, 89, ...
```

On the 120-domain, the first part of this sequence builds the domain:

```text
lcm(1, 2, 3, 5, 8) = 120.
```

The Fibonacci numbers that divide 120 are exactly

```text
{1, 2, 3, 5, 8}.
```

These are domain-building terms. They tile the grid rather than select positions on it. A divisor of 120 defines a sub-lattice or uniform partition of `Z/120`; it is not yet a genuine sampling site.

The first Fibonacci term after that divisor block is `13`. This is the lcm seam:

```text
{1, 2, 3, 5, 8}  →  build the domain
{13, 21, 34, 55} →  sample the domain
```

The upper bound comes from the observable phase operator. Since

```text
C(k) = 2 sin²(πk/120)
```

we have

```text
C(k) = C(120 − k).
```

So no new intensity well appears beyond the antinode at `k = 60`. The largest Fibonacci below the antinode is `55`; the next Fibonacci, `89`, reflects to `31` as an intensity value.

The candidate well set is therefore `{13, 21, 34, 55}`. More carefully:

> The candidate well set is forced to `{13, 21, 34, 55}` once the sampling rule is taken to be the post-lcm continuation of the icosahedral Fibonacci recurrence below the antinode.

The set follows from locked structure once the sampling rule is granted. The sampling rule itself remains the live target.

---

## Floor at 13

The old "noise floor" language is dropped: the phase weight `C(k)` rises smoothly through the early Fibonacci values (`0.012, 0.034, 0.086, 0.223` at `k = 3, 5, 8, 13`), with no intrinsic jump at 13. The floor has three cleaner characterizations.

### 1. Lcm seam (main arithmetic reason)

`13` is the first Fibonacci number that does not divide 120. The terms before it, `1, 2, 3, 5, 8`, are absorbed into the construction of the domain (`lcm(1,2,3,5,8) = 120`). They are tiling data. The first post-tiling term is `13`, so `13` is the first genuine sampling candidate.

### 2. E₈ exponent (representation-theoretic reinforcement)

The E₈ exponents are `1, 7, 11, 13, 17, 19, 23, 29`. The Fibonacci intersection is `{1, 13}`. Discarding `1` as the identity/primitive slot, `13` is the first nontrivial Fibonacci value that is also E₈-native. This does not replace the lcm seam; it reinforces it. The arithmetic seam lands exactly where the representation theory is already active.

The bridge is the modulus `30 = 2·3·5 = h(E₈)`: the same number is the reduced prime base of `120 = 2³·3·5` and the Coxeter number of E₈, and its totatives are precisely the E₈ exponents (verified). This is a structural alignment, not a logical folding: the lcm seam selects 13 arithmetically; the E₈ structure confirms the seam is representation-native.

### 3. Coprime / full-resolution (diagnostic)

Among the candidate wells, only `13` is coprime to 120. It is the full-resolution entry; the later wells each carry one branch prime and one new totative prime:

| Well | Factorization | gcd(k,120) | New prime | Reading |
|---|---:|---:|---:|---|
| 13 | 13 | 1 | 13 | full resolution |
| 21 | 3·7 | 3 | 7 | face / `Z₃` branch factor |
| 34 | 2·17 | 2 | 17 | edge / bosonic-projection factor |
| 55 | 5·11 | 5 | 11 | vertex / `Z₅` branch factor |

The first well is full-resolution; the later wells each combine one icosahedral branch prime with one new E₈/totative prime (`{7, 17, 11}`, which together with `13` are the four smallest nontrivial E₈ exponents). The set looks less accidental under this reading.

---

## Mirror constraint (where the proof must live)

The bulk character algebra supplies the arithmetic: `2I`, `E₈`, `Q(√5)`, the `{2,3,5}` prime base, the character ceiling. But Lemma 8 ([the-mirror.md](../../../spectrum/files/the-mirror.md)) says the bulk spectral side is Θ-blind: it cannot naturally recover the boundary phase coordinate.

Therefore a bulk functional cannot select the wells. Generic spread, energy, discrepancy, and circle-packing tests are the wrong arena. They prefer uniform spacing, and in the probe they do (gap-variance favors equal spacing; inverse-distance favors `{9,25,43,59}`).

The well functional has to be boundary-native, built from the anti-periodic `S¹` mode structure where Θ actually lives. The right target is not a generic minimization on `Z/120` but a signed anti-periodic interference functional measuring cancellation or cross-talk among the admissible boundary modes

```text
ψ_m(Θ) = sin((2m+1)πΘ),
```

possibly weighted by the `60/120` projection, the phase weight `C(k)`, or the stabilizer data. The candidate wells should minimize interference / maximize sign-cancellation under that boundary mode algebra.

---

## Sharp residual

The problem is reduced to one question:

> Why does the post-lcm additive continuation of the icosahedral branch recurrence define the sampling wells?

To move from STRUCTURALLY REDUCED to DERIVED, define the boundary-native mode-weighted functional and show one of two things:

1. `{13, 21, 34, 55}` is a local or global minimizer; or
2. stronger: the greedy interference-minimizing continuation from `(2,3,5)` produces `8, 13, 21, 34, 55`.

Until that functional is defined and tested, the wells stay structurally reduced, not derived.

---

## Adjacent thread (scaling-law, not wells)

The same Lemma 8 that locates the well functional on the boundary also bears on the [scaling-law factorization](scaling-law-uniqueness.md), which is currently **open** (the commutant theorem `A_obs = A_Θ ⊗ A_spec` is the named open target; the FORCED flip was walked back at the Step C gap). The mirror's character ceiling (Props 1 to 3, Lemma 7) plus Lemma 8 is a candidate closer for that theorem via a bridge lemma. Tracked separately; not part of the wells problem.

---

## Probe log (verified facts, for reference)

- Distinct Fibonacci ≤ 120: `1, 2, 3, 5, 8, 13, 21, 34, 55, 89`. Divide 120: `{1,2,3,5,8}`. First non-divisor: `13`. `lcm(1,2,3,5,8) = 120`.
- Fibonacci ∩ `(8,60)` = `{13,21,34,55}`. Linear gaps `[8,13,21]` (consecutive Fibonacci, so the set is golden self-similar, not uniform).
- Reflection: `C(k) = C(120−k)`; `89 → 31`; `55` largest Fibonacci below 60.
- `gcd(k,120)`: `13→1, 21→3, 34→2, 55→5`. New primes: `13, 7, 17, 11`.
- Totatives of 30 = `{1,7,11,13,17,19,23,29}` = E₈ exponents (verified; also in repo [r-problem.md](r-problem.md)). `30 = 2·3·5 = h(E₈)`.
- `C(k) = 2 sin²(πk/120)`: `0.012, 0.034, 0.086, 0.223` at `k = 3,5,8,13` (smooth, no floor jump).
- Golden rotation step 74: `gcd = 2`, orbit = 60 even residues; misses `13/21/55`, hits `34` at step 41.
- Generic functionals over 4-subsets of `{9..59}`: gap-variance favors equal spacing; inverse-distance favors `{9,25,43,59}`; log-energy favors `{9,23,45,59}`. The wells are never the minimizer. Generic spread is ruled out.

---

/ **[`main`](../../../../README.md)** / **[`framework`](../../../framework/)** / **[`working`](../)** / **[`cosmos`](../../../cosmos/)** / **[`spectrum`](../../../spectrum/)** /
