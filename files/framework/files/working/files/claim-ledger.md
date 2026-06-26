/ **[`main`](../../../../../README.md)** / **[`framework`](../../../../framework/)** / **[`working`](../)** / **[`cosmos`](../../../../cosmos/)** / **[`spectrum`](../../../../spectrum/)** /

---

# Claim Ledger: Skeptical Audit of Quantitative Claims

*Working note, 2026-06-26. This is an internal adversarial classification of every quantitative claim in the framework, not the framework's self-description. It was built by a deliberately skeptical audit (calibration anchors are not counted as successes, retrodictions are separated from forward predictions, claims sharing a calibration path are grouped rather than double-counted). Its purpose is to keep the public pages honest about what is proved, what is calibrated, what is compared, and what remains a forward bet. Read the verdicts as the prosecution's strongest case, not the final word: some flags are clean hits, a few are the lens being harsh on purpose.*

## How to read this

Every claim carries two independent axes. **Type** is what kind of statement it is. **Role** is what work it does in the framework. A statement can be a theorem (true by proof) and still be load-bearing without being an observational win; an equally-true identity can be decorative. Keeping the axes separate is the whole point: it stops a zero-freedom topological result (3 generations) from being lumped with a tunable curve-fit (a fermion mass within ×3), and stops a calibration input (R) from being counted as a prediction.

Type taxonomy, in descending order of empirical bite:

- **Forward prediction**: a value for something not yet measured. The only category that can be falsified going forward. The real exams.
- **Structural result, zero freedom**: a topological or spectral theorem that matches observation with no adjustable parameter (3 generations, 3 forces, the 4/R² mass gap). The bones. Retrodictive (the data predate the theory) but not tunable, and not circular.
- **Structural theorem, no observational contact**: proved internal mathematics with no measurement target (torsion closed forms, Mirror no-go lemmas, character ceilings). True, often load-bearing for the architecture, but empirically inert.
- **Loose comparison**: a retrodiction *with* freedom: it hits a known value but the hit was selected among Fibonacci wells, grids, exponents, or vacua, or sits inside a tolerance window. The bulk of the headline physics.
- **Calibration anchor**: a measured value taken as an input (Λ, R, m_e, Ω_Λ, H₀, a₀, s₀). Cannot count as a success no matter how it is framed.
- **Null result**: a recorded failure or a "you will not find X." The framework's strongest epistemic feature.
- **Open problem**: a named target not yet derived.

"Anchored on" names the calibration path. "web" = the MIT calibration web hub (Λ_obs → R → Ω_Λ, plus m_e and H₀ as secondary anchors).

## Executive read

A large structural framework with genuine topological content, whose quantitative contact with measurement runs through a calibration web that contains real cycles, producing a handful of genuinely falsifiable forward predictions centred on Euclid DR1 (Oct 2026).

The structural content is not circular. Three generations from three flat connections on S³/2I, the Yang-Mills mass gap at 4/R², chirality, the Molien deficit: these are retrodictions with zero adjustable freedom, theorems about the topology that happen to match the world. They are the bones. The quantitative comparisons (α to 0.5%, the couplings to ~1%, the masses to a factor of 3, a₀/cH₀ to <1%, Λ to 24%) are a different animal: each is a retrodiction inside the calibration web, hitting a number already known by choosing among wells, grids, exponents, and three vacua, with the selection rule that would remove that freedom an explicit open problem.

What the framework actually lives or dies on is a thin set of forward bets, nearly all riding on Euclid DR1: epoch-independent Λ / flat Ω_DE(z), mass-independent a₀(z) ∝ H(z) (the single cleanest discriminator, immune to the stellar-M/L freedom that wrecks the rotation-curve tests), and the sign-fixed negative (1+z)¹ term in H²(z). These are thinner than the page count suggests: a₀(z), H(z), w_eff(z), and d_L(z) are one phase-clock relation read through four channels, not four independent predictions.

The framework's strongest feature is recorded falsification. It pre-registered and lost the SPARC coherence-scale test (0.38 L_f, not 1.0), the H₀ bimodality test (unimodal), the McKay mass-residual correction (no parameter-free fix), and the signed well-functional sweep (wells never extremal), and it logs the down/tau/top mass misses and the m_e↔Λ ~11% closure rather than hiding them. That is the opposite of a protected theory.

## Reconciliation (verified 2026-06-26)

The Flags and triage items below are the audit's prosecution case. A follow-up pass verified the 13 highest-risk flags against the live text, using the standard that a caveat counts only if it is discoverable from the claim's own context. Outcome: **9 handled** (caveat already at the point of claim), **3 partial** (a real caveat exists but in a different file, not discoverable, the only items needing an edit), **1 ledger error** (`lambda_alpha_route`: the 24% window and the circularity are stated inline at every live site), **1 working-only** (`clock_age`: the 0.79 Gyr vs 13.8 Gyr tension lives only in temporal-budget.md §VIII, which already flags it open; no public page makes an age-recovery claim). None were wholly uncaveated.

Methodological lesson: the audit judged each claim stripped of its in-page caveats, which inflated the overclaim count. The live framework is markedly more honest than the Flags section below implies. Treat the flags as leads to verify, not findings to act on.

**The real residual** (the only source edits the verification justified) is three one-line cross-references:

1. **μ_Λ** (mass-spectrum.md §II.1): the Λ in μ_Λ = ρ_Λ^(1/4) is the measured CC taken as calibration input, so μ_Λ is the mass sector's anchor, not an output. **Done 2026-06-26.**
2. **α** (fine-structure.md §V scorecard): when α is the Ω_Λ anchor, its 0.5% is a consistency check, not an independent prediction. **Done 2026-06-26** (framework/README.md gauge ladder and the Desktop engine §15 carry the note now too).
3. **Phase-clock channels** (euclid-dr1.md): rows II/III/V are channels of one H²(z;s₀) relation, correlated tests not independent predictions. **Done 2026-06-26** (clearly-dated post-freeze clarification below the Prediction Summary table; touches no immutable prediction/threshold/scoring cell).

Cycle 2 (α) and Cycle 7 (R routes) named below are real tensions, but already disclosed at every live site; the α §15 "CLOSED" framing now carries a calibration note in both the repo and the Desktop engine.

## The two cycles that matter

Most of the calibration loops below are benign (definitions, or self-flagged consistency radii). Two are the framework's real internal tensions and deserve to be stated starkly:

**Cycle 2: α is both input and output.** The α route calibrates R from the measured fine-structure constant (α fixes Ω_Λ, hence R), and then the scaling law "predicts" α from that same R. So **α at 0.5% is a consistency check, not a prediction of α.** The genuinely non-circular content of that chain is downstream: α → R → Λ = 3/R² is a real ~24% prediction of the cosmological constant. State it that way. The engine's §15 "α CLOSED" tag is the top source-page fix: it should say α is the calibration input for R, making the 0.5% match a closure test, with the Λ-at-24% as the actual forward-ish content.

**Cycle 7: the two routes to R disagree by ~4×.** R from the coupling route is ≈5.3 Gpc; R from the mass-spectrum route is ≈20 Gpc, and the corresponding Λ values differ by ~14× (>1 order of magnitude). The engine honestly labels the mass route "order of magnitude," but a 4× disagreement between the framework's two independent determinations of its master length scale is a real problem, not a footnote. Until one route is shown to be the correct determination of R, every "prediction" that flows through R inherits this ambiguity.

## Calibration web

Adjacency list (X ← Y means X is anchored on Y). Measured inputs marked [obs].

```
Λ_obs [obs]
R_Λ          ← Λ_obs                  (R = √(3/Λ), back-read)
ℓ_P,t_P,m_P  ← G[obs], ℏ[obs], c[obs]
Ω_Λ          ← R_Λ, ℓ_P               (= (R/ℓ_P)² ≈ 10¹²²; the hub)
√Ω           ← Ω_Λ                    (10⁶¹ observer depth)
μ_Λ          ← Λ_obs, G               (= ρ_Λ^(1/4) ≈ 2.25 meV)
Λ_top        ← R_Λ                    (= 2/R²)
Λ (3/R²)     ← Λ_top                  (× 3/2: 3 = Ricci trace derived, ½ imported GR)
H₀ [obs, = Planck 67.4]
a₀ [obs, MOND 1.2e-10]
a₀/(cH₀)     ← a₀, H₀ ; reproduced by C(13/120)/C(34/120) = 0.184
α [obs ~1/137]
α (predicted)← C(13/60), Ω_Λ          (well/grid/exponent selected)
Ω_Λ (α-route)← α                      (α → Ω_Λ → R → Λ, 24%)  ← CYCLE 2
α_s, α_W     ← C(17/..), Ω_Λ, cos(π/10)
m_e [obs, BENCHMARK]
fermion masses ← μ_Λ, C_geom(ρ), Ω_Λ^(dist/30), T²(ρ⊗σ)   (all relative to m_e)
R (coupling) ≈ 5.3 Gpc  ← α
R (mass)     ≈ 20 Gpc   ← m_e, m_μ, McKay distances        ← CYCLE 7 (~4× / ~14× in Λ)
Ω_m          ← Ω_Λ                    (= 1 − Ω_Λ = 0.315, flatness identity)
s₀           ← SN+BAO data [obs]      (fitted phase parameter, the model's only DoF)
w_eff, (1+z)¹β, Ω_m(z), H(z), a₀(z), d_L(z)  ← s₀, Ω_Λ, one phase clock
```

The eight cycles, each named by kind:

1. **m_e ↔ Λ**: genuine closure loop, ~11% error. Reproducing m_e, Ω_m, and the masses re-uses the anchor; these are consistency, not prediction.
2. **α ↔ Λ ↔ R**: **genuine circularity** (see above). α is input and output.
3. **R ↔ Λ**: definition (R = √(3/Λ), Λ = 3/R²). Exact, self-flagged "circular: a consistency radius, not an input."
4. **Ω_Λ ↔ R ↔ ℓ_P**: definition. The 10⁶¹ / 10⁻¹²² / 10⁻¹⁸³ suppressions are one fact re-expressed.
5. **a₀ ↔ H₀ ↔ a₀/(cH₀)**: presentation double-count: one derived ratio (0.184) listed across multiple pages and re-used as a₀/a_P.
6. **n = −½ ↔ Ω_m**: one fit counted twice: the clock exponent is fitted to recover the (1+z)³ scaling, then the Ω_m recovery is cited as its validation.
7. **R(coupling) ↔ R(mass)**: **the most important tension**, ~4× disagreement (see above).
8. **8.4% H₀**: output = input by construction; mechanism withdrawn on SPARC.

## Master ledger

Notation is plain (Λ, α, Ω_Λ, a₀, √E(z)) to stay GitHub-safe inside tables. Duplicated leaf lemmas are consolidated with a count.

### Forward predictions (the real exams)

The phase-clock channels are grouped under one parent: they are independent *tests*, not independent *predictions*.

| Claim | Predicted → status | Freedom (look-elsewhere) | Anchored on | Falsifier |
|---|---|---|---|---|
| **Phase-clock relation (parent)**: one standing wave on S¹ produces H(z), a₀(z), w_eff(z), d_L(z) | n/a | s₀ is the only DoF; functional form fixed | s₀, Ω_Λ | see channels |
| ↳ a₀(z) mass/aperture-independent √E(z) = 1.74 at z=2 | awaiting Euclid lensing; dir corroborated ~30σ (non-discriminating) | a₀(0) input; lensing calib | H(z), a₀(0) | M_dyn/M_b mass-dependent (ΛCDM 0.76–1.13) ≥2σ. **Cleanest single discriminator.** |
| ↳ a₀(z=2) ≈ 3× local | awaiting hi-z rot curves | Ω_Λ/s₀ upstream | H(z) | a₀ ≈ a₀(0) at z≈2, ≥2σ |
| ↳ negative (1+z)¹ coeff β, \|β\| < 0.012 | awaiting next-gen BAO; sign firm, magnitude sub-detectable | magnitude rides fitted s₀ | s₀ | β > 0 at ≥2σ, or magnitude ≠ fitted s₀ |
| ↳ w_eff(z) > −1 (no phantom crossing) | **demote: convention-dependent, not an observable** | fiducial-vs-dressed split sets it | split choice | crossing persists across all reconstructions ≥2σ |
| Λ epoch-independence / Ω_DE(z) flat across DR1 bins | awaiting Euclid DR1 | flatness not tunable | Λ = 3/R² (web) | Ω_DE varies ≥2σ across bins |
| SMF z≳10 / JWST massive galaxies persist (a₀(z=10)≈20.5×; 4.5× g-boost; 2.1× t_ff speedup → ε_SF ~0.5) | awaiting wide-area | ε_SF, dust, selection knobs; "deferred/uncounted" escape | a₀(z=10), Ω_Λ, s₀ | abundance within Boylan-Kolchin ΛCDM ≥2σ |
| ν₂ neutrino mass 8.6 meV; gap ~7.75× | awaiting JUNO/DUNE | hierarchy + well assignment | mass formula | m(ν₂) ≠ 8.6 meV |
| Neutrino floor μ_Λ ~2.25 meV | <800 meV (KATRIN); forward | μ_Λ rides web; near oscillation scale | m_e, Ω_Λ (web) | lightest ν > 2.25 meV >1σ |
| No CMB spectral distortion, T(z) = (1+z)^(1−β) (redshift-cooling) | FIRAS-consistent; two-sided test | β=0 limit | phase clock | measured distortion / T(z) departure |
| Rank-16 / dead-zone states (~349 MeV; 6 states eV–keV) | no SM fermion (open) | "unassigned" escape hatch | mass formula | sterile/WDM searches exclude windows |

### Structural results, zero freedom (the bones)

Retrodictions that match observation with no adjustable parameter. Not circular, not tunable. These are the framework's spine.

| Claim | Value → measured | Freedom | Anchored on | Note |
|---|---|---|---|---|
| Fermion generations = 3 | 3 flat SU(2) connections, H¹=0 → 3 | "flat connection = generation" is an interpretation, cordoned off | 2I character theory | proved (Maschke + character theory) |
| Force count = 3 | Z₃,Z₄,Z₅ / 2I = 2³·3·5 | prime→force map; spin/gravity bookkeeping | 2I structure | matches EM/weak/strong |
| Yang-Mills mass gap > 0 at 4/R² | gap exists, ADE-uniform | none (spectral) | McKay graph, R | gap is a spectral necessity |
| Chirality of S³/2I (no orientation-reversing isometry) | parity route shut | none | 2I, quaternions | clean theorem; parity-grading corollary double-counts it |
| Boson/fermion split D = 60/120 | \|I\|/\|2I\| = int/half-int spin | spin-statistics mapping | 2I | structural identity |
| Color Z₃ singlet/triplet; isospin gate; eta-sign gate | 6/6, 10/10, all match | binary/bespoke gate fits known set; charm unplaced | irrep assignment | matches but gate is bespoke; see flags |

### Structural theorems, no observational contact (internal math)

Proved, often architecturally load-bearing, empirically inert. ~150+ leaf lemmas consolidated here.

| Claim (representative) | Status | Note |
|---|---|---|
| First positive eigenvalue 2/R² on twisted Möbius (~30 lemmas) | proved, **conditional** | only for narrow band W ≤ πR/2 and δ₀ > 2R/e; **first-positive, NOT a ground state** (no strictly positive ground state exists across extensions). W ≤ πR/2 is an input, not derived. |
| Coexact gap 4/R² ADE-uniform; 36/R² Galois exception; ratio 9 (~20 lemmas) | proved | "exception" is an honest carve-out; 9× = (6/2)² and 3× = √9 are arithmetic restatements (double-count) |
| Mirror: character ceiling, Dirac eta, Selberg/Ruelle/Artin no-go's, Lemma 8 Θ⊥s (~40 lemmas) | proved within admissible class | "four independent proofs" of the S¹ no-bridge overstates independence |
| Reidemeister torsion φ⁻⁴ ratios, 79-digit closed forms (~50 toolbelt rows) | exact | **φ is baked into Q(√5) then recovered as φ⁻⁴**: circular as "evidence." log-torsions = logs of the same values. |
| Molien series: N=12 first invariant, N=2–10 empty | rigid algebraic fact | restated 4+ times across pages as independent evidence (one fact) |
| C(Θ) = 2sin²(πΘ) trig identities; budget identities Ψ²+S²=1 | tautological | trig of the chosen functional form |
| Gauss factor 3 (Ricci trace) × ½ → 3/2 | 3 derived, ½ imported GR | identity with stabilizer-3/2 is OPEN |

### Loose comparisons (retrodiction with freedom, the headline physics)

| Claim | Predicted → measured | Agreement | Freedom | Anchored on |
|---|---|---|---|---|
| Fine-structure α | 0.00733 → 0.007297 | 0.5% | well(13)/grid(60)/exp(1/60); **α is also the input for R (Cycle 2)** | Ω_Λ, α (web) |
| Strong coupling α_s | 0.1162 → 0.1179 | 1.4% | well/grid/exp; α_s runs with scale | Ω_Λ (web) |
| Weak coupling α_W | 0.0339 → 0.0338 | 0.4% | + cos(π/10) "Plato twist" applied only here | Ω_Λ, cos(π/10) |
| α_s/α_W | 3.43 → 3.49 | 2% | quotient of two already-counted fits | Z₃/Z₅ |
| Λ via α route | 2.9e-122 → 2.90e-122 | within 24% window | 60-fold lever; route choice; Cycle 2 | α, Ω_Λ, R |
| Λ via mass route | 8e-54 → 1.11e-52 | **~14× off (demote: a miss)** | bar relaxed %→OoM; Cycle 7 | m_e, Ω_Λ |
| Λ_obs/Λ_top = 3/2 | 3/2 | exact (claim) vs a σ-statement | Gauss-vs-stabilizer 3/2 identity OPEN | Λ_top |
| a₀/(cH₀) | 0.184 → 0.183 | <1% | well pair (13,34) selected; known 1983 MOND coincidence; both inputs | a₀, H₀ (web) |
| Fermion masses (24 entries) | **6–7 of 8 within ×3** | comparison | ×3 window wide; assignment + 3-vacuum freedom; m_e anchor | m_e, Ω_Λ (web) |
| ↳ muon | 1.03e-1 → 1.057e-1 GeV | 3% | rank shared w/ strange; vacuum choice | m_e |
| ↳ up | 2.03e-3 → 2.16e-3 GeV | 6% | scheme-dep target; assignment | m_e |
| ↳ down | 1.51e-2 → 4.67e-3 GeV | **3.2× MISS** | vacuum carries the 3× | m_e |
| ↳ tau | 0.734 → 1.777 GeV | **2.4× MISS** (not "soft match") | Coxeter-Galois gate orphans charm | m_e |
| ↳ top | 261 / 44.5 → 172.7 GeV | **1.5× / 3.9×** (vacuum-inconsistent) | which vacuum is "top" | m_e |
| Δχ² vs ΛCDM | +0.11 (= ΛCDM, marginally worse) | tie | nested model (s₀→0 = ΛCDM); dataset choice | s₀, Ω_Λ |
| CMB low-ℓ deficit | Molien gap ℓ≈28 (coupling R) | open; route-selected | R from internal route; 2 routes straddle band | R (web), Molien |
| Ω_m = 0.315 | = 1 − Ω_Λ = 0.685 complement | exact | **flatness identity; this is an input echoed back, reclassify as anchor** | Ω_Λ (web) |

### Calibration anchors (inputs, not successes)

| Input | Value | Framed as | Reality |
|---|---|---|---|
| Λ_obs | 1.11e-52 m⁻² | observed | the hub anchor |
| R_Λ | 5.3 Gpc | derived | back-read of Λ (self-flagged circular) |
| Ω_Λ = (R/ℓ_P)² | ~10¹²² | derived/exact | definition on calibrated R (overclaim) |
| m_e | 0.511 MeV | benchmark | whole-spectrum lever; m_e↔Λ ~11% loop |
| μ_Λ = ρ_Λ^(1/4) | 2.25 meV | derived | quartic root of measured Λ (overclaim) |
| H₀ = 67.4 | "phase-clock best-fit" | consistent | = Planck value, favourable side of tension (overclaim) |
| a₀ = 1.2e-10 | MOND | calibration | the normalization the ratios then reproduce |
| s₀ < 0.19 | data constraint | awaiting | the model's only fitted DoF; prior-sensitive 0.12–0.21 |
| 122-orders span, H₀·t_P, Planck constants, GR-imported BH quantities, CMB anomaly targets | n/a | structural/derived | inputs fed in (overclaim where framed as outputs) |

### Null results (recorded failures, the credibility core)

| Result | Outcome | Note |
|---|---|---|
| SPARC L_f coherence test | **FALSIFIED**: 0.38 L_f not 1.0; tracks M_b; slope 0.23 vs [0.7,1.3] | pre-registered DOI, 27-cell stable, no rescue |
| H₀ bimodality | **NOT SUPPORTED**: unimodal; TRGB 69.8 in the predicted gap; GMM 68.4/73.5 ≠ 67/73 | all 4 configs agree |
| McKay propagator correction | **NULL**: no parameter-free fix; down/tau residual signs oppose (+0.51 vs −0.38) | route closed/archived |
| Signed well-functional sweep (fibonacci-wells) | **NEGATIVE**: wells never extremal across 8 functionals | variational route to DERIVED closed |
| Dark matter / SUSY nulls | holding | weak (absence of evidence); n=3 layer 10⁻¹⁸³ unfalsifiable |
| DESI wCDM favours w≠−1, MIT cannot reach | **disconfirmation recorded** | candid |

### Open problems

| Problem | Weight | Note |
|---|---|---|
| Selection rule for wells/exponents/grid (n=1,2,3; 1/60, 1/120; dist/30) | load-bearing | the master look-elsewhere surface; every coupling/mass cites it |
| Commutant theorem A_obs = A_Θ ⊗ A_spec (factored scaling law) | load-bearing | keystone gap; whole factored measurement form is conditional |
| R determination (coupling vs mass routes, ~4× apart) | load-bearing | Cycle 7; framework's own R off by 3.7× internally |
| Friedmann as output, not input | load-bearing | 0% progress; Ω_m recovery currently borrows GR dynamics |
| Waltz clock map t(Φ); entropy S↦N_max; energy E(S) | load-bearing | see self-inconsistencies below |
| Charm assignment; ν₂ gap; dead-zone coverage | soft | known fermions the scheme cannot place |
| energy-as-resolution, entropy-as-realization-budget, redshift-and-cooling | non-load-bearing | three speculative files: derivation candidates with unwalked steps |

## Flags

### Overclaims (page framing vs true type)

The clear hits, each a candidate source-page fix:

- **α "CLOSED" (engine §15)**: α is the calibration input for R; the 0.5% match is a consistency check, not a prediction of α. (Top priority.)
- **Ω_m = 0.315 "derived/recovered independently"**: flatness identity 1 − Ω_Λ; a pure input echoed back.
- **μ_Λ, Ω_Λ, R_Λ, H₀·t_P, H₀ = 67.4 "derived/exact/best-fit"**: inputs dressed as outputs.
- **Λ_obs = (3/2)Λ_top "derived/exact"**: carries the open Gauss-vs-stabilizer 3/2 identity; "measured" cell is a σ-claim.
- **w_eff "no phantom crossing" (physical)**: a theorem about a chosen decomposition, not an observable.
- **Hawking T_H "coefficient derived"**: only sin(πΘ₀) ≈ 0.777 is framework-side; thermal content inherited from QFT.
- **tau/top "soft match"**: 2.4× / 1.5× are misses; list at real residuals.
- **Fibonacci wells "derived/forced"**: selection rule is the framework's own open problem (already fixed in fibonacci-wells.md).
- **Spectral inaccessibility / 120-LCM / "convergent paths" listed as "exact" wins**: self-referential no-go's and one-fact-many-witnesses.

### Double-counts (one fact, many witnesses)

- **120 = \|2I\| = lcm(1,2,3,5,8) = musical LCM = Fib-divisors = 144/F₁₂ = 12²**: one divisor-structure fact sold as multiple independent witnesses (the Oort 144,000 AU "two paths" both reduce to 144 = 12²).
- **30 = h(E₈)** as mass-exponent denominator, Coxeter pair sum, Molien generator degree, shell-closure sum, one E₈ seam; "three/four convergent paths" rhetoric is the same fact.
- **φ baked into Q(√5) then "discovered" as φ⁻⁴ torsion ratio**: input feature re-presented as output.
- **9× = (6/2)² and 3× = √9; Reidemeister log-torsions = logs of closed forms**: arithmetic restatements scored as separate derived rows.
- **N=12 first invariant** restated 4+ times as independent evidence.
- **a₀/(cH₀) one coincidence listed 3× (a₀/a_P, ratio, %); 8.4% as ratio/%/slope×step.**
- **n = −½ "validation" = the Ω_m fit it powers.**

### Self-inconsistencies (surface these; do not bury)

- **Waltz clock age**: the clock inverted from the joint SN+BAO s₀ bound gives a present age **≤ 0.79 Gyr**, ~17× below 13.8 Gyr, which stellar/globular ages (~12–13 Gyr) already exclude. The t(Φ) map is the named open problem, so this is an *unsolved mapping*, not a logical contradiction, but a 17× age gap on naive inversion deserves ledger-level visibility. **Action**: every age statement in the public pages must say the clock map remains open and must not imply the current map already recovers 13.8 Gyr (the 13.8 Gyr in the epoch table is ΛCDM-borrowed pending t(Φ)).
- **Engine phase Φ_now ≈ 5.22 vs ≲ 0.3** from clock integration: the two phase parameterizations (engine Φ, budget t) are stated as distinct with the mapping open; the discrepancy is the same unsolved map, worth visibility.
- **Two routes to R disagree ~4×** (Cycle 7): the framework's most significant internal tension.

## What this changes (source-page triage queue)

Superseded by the [Reconciliation](#reconciliation-verified-2026-06-26) above. Verification trimmed the original six-item queue to three one-line cross-references, all now applied: μ_Λ (mass-spectrum.md), α (fine-structure.md), and the phase-clock correlation note on the euclid-dr1.md pre-registration card (post-freeze, no cell changed). The other original items (age statements, the rest of the inputs-dressed-as-outputs set, mass residuals, Cycle 7) verified as already disclosed in-page and need no edit. **Triage arc closed.**

---

/ **[`main`](../../../../../README.md)** / **[`framework`](../../../../framework/)** / **[`working`](../)** / **[`cosmos`](../../../../cosmos/)** / **[`spectrum`](../../../../spectrum/)** /
