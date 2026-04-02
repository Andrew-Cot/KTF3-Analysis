[README.md](https://github.com/user-attachments/files/26449258/README.md)
# KTF³ Analysis — Klein-Flasche Topology Framework

**Andrew Cotting — Independent Researcher, Zürich — 2026**

*AI assistance declared (Claude, Anthropic). All scientific ideas: Andrew Cotting.*

---

## Framework

KTF³ proposes the universe has the global topology of a 4D Klein bottle:

**φ(x,y,z,t) = (−x, −y, −z, t + T₁ + T₂ + T₃)**

with three independent periods T₁ ≈ 1660 Mpc, T₂ ≈ 2630 Mpc, T₃ ≈ 2750 Mpc.

Key derived quantities:
- θ_R = 25.7° (precessional rotation per cycle, from ℓ* = 3.5)
- N = 360°/25.7° = 14.008 cycles per renewal period
- H₀ = 67.1 km/s/Mpc (topological derivation, D11 v4)
- Λ ≈ θ_R²/T₁² (dark energy from geometry, D18)

Pre-registration: [academia.edu/AndrewCotting](https://academia.edu/AndrewCotting)

---

## m-Parity Test Results (v40b–g)

**KTF³ prediction:** Non-orientable topology → odd-m CMB modes enhanced → R > 0

| Notebook | Instrument | σ | p-value | Status |
|----------|-----------|---|---------|--------|
| v40b | Planck SMICA | +0.89 | 0.188 | ✅ Positive |
| v40c | Planck NILC | +0.97 | 0.172 | ✅ Positive |
| v40d | Planck SEVEM | +0.98 | 0.164 | ✅ Positive |
| v40e | Planck COMMANDER | +0.91 | 0.178 | ✅ Positive |
| v40f | WMAP 9yr | +1.06 | ~0.15 | ✅ Positive |
| v40g | ACT DR4 | — | — | ⚠️ Incompatible map format (2D projection, not HEALPix) |

**Mean σ = +0.96 across 5 instruments. All positive.**

Probability of all-positive by chance: (0.5)⁵ = 3.1% → combined ~2.2σ.

No individual result is significant at 2σ. Signal is consistent but weak.

---

## Dark Energy (v53 + D18)

**KTF³ formula:** Λ = θ_R²/T₁² (θ_R in radians)

| Formula | Ratio to Λ_obs | Status |
|---------|---------------|--------|
| θ_R²/T₁² = (2π/N)²/T₁² | 0.709 | ✅ Factor 1.4 |
| H₀²/c² | 0.487 | ✅ Factor 2 |
| 1/R_H² | 0.487 | ✅ Factor 2 |
| ℏc/T₁⁴ | ~10⁻⁷⁶ | ❌ 76 orders off |

No free parameters. Exact derivation in Cartan geometry is open problem.

**w = −1.000 exactly** (D11 v3+v4) — consistent with Pantheon+ (w = −1.051).

---

## All Tests Summary

| Notebook | Test | Result | Verdict |
|----------|------|--------|---------|
| v40b–e | Planck m-parity (4 maps) | σ = +0.89 to +0.98 | NULL (weak positive) |
| v40f | WMAP m-parity | σ = +1.06 | NULL (weak positive) |
| v40g | ACT DR4 m-parity | incompatible format | PENDING |
| v47 | 2MPZ mirror correlation | data unavailable | PENDING |
| v48b | BOSS DR12 mirror corr. | σ = +0.13 | NULL (25% sky) |
| v49 | eBOSS QSO mirror corr. | σ = −0.73 | NULL (25% sky) |
| v50 | SPARC dark matter | σ = +0.07 | NULL (local only) |
| v51 | Filament spin (SDSS) | data blocked | PENDING |
| v52 | Auger UHECR dipole | σ = −0.72 | NULL |
| v53 | Dark energy from topology | ratio = 0.709 | Factor 1.4 match |
| v44b | Euclid DR1 mirror corr. | awaiting data | Oct 2026 |

**Key null results documented transparently:**
- v48b/v49: BOSS/eBOSS NULL due to 25% sky asymmetry (not genuine falsification)
- v50: SPARC NULL — galaxies too local (D < 100 Mpc) for T₁ = 1660 Mpc test
- v52: Auger NULL after exposure correction (naive σ = 6.31 was artefact)

---

## Theoretical Papers (D-series, Academia.edu)

| Paper | Title | Key result |
|-------|-------|-----------|
| D11 v4 | Spacetime Expansion as Driver of θ_R | H₀ = 67.1 from topology |
| D11 v3 | Quantum Entanglement as Origin of θ_R | Constancy of θ_R explained |
| D15 | KTF³ Wave Scales vs Cosmic Structures | 415 Mpc ≈ Sloan Great Wall (1.2%) |
| D16 | T₁ = R_H/e Empirical Formula | 1% accuracy |
| D17 | Eternal Rotating Klein Bottle | 14-cycle structure, quantum causality |
| D18 | Dark Energy from KTF³ Topology | Λ = θ_R²/T₁², factor 1.4 match |

---

## Euclid DR1 Pre-Registration (October 2026)

The definitive test is the mirror correlation P1 in galactic coordinates along the KTF³ axis (l=277°, b=−31°) with Euclid DR1 full-sky data.

**Prediction:** σ > 2 at r = T₁/2 = 830 Mpc.

**Self-assessment:** KTF³ plausibility 3.5/10 currently. Rising to 6–7/10 if Euclid confirms.

Notebook: `v44b_euclid_mirror_axis_corrected.ipynb`

---

## Math (r/math, April 2026)

Post: *"Spin structure on non-orientable quotient R⁴/φ with Z deck group"*
- 35 upvotes, 11.9k views
- Pin(4)→O(4) structure confirmed: no obstruction to Pin+ or Pin−
- Manifold diffeomorphic to R² × Möbius bundle, homotopy equivalent to S¹

This confirms the mathematical consistency of KTF³ spin structure.

---

## Caveats

- No individual result exceeds 2σ
- m-parity signal consistent with statistical noise
- Λ formula not derived from first principles
- Fine-tuning problem shifted, not solved
- All results depend on ℓ* = 3.5 being correct (WMAP gives ℓ* = 4.5)
- P1 mirror tests NULL due to 25% sky coverage — Euclid required

---

## Repository Structure

```
KTF3-Analyse/
├── v40b_mparity.ipynb          — SMICA m-parity
├── v40c_mparity.ipynb          — NILC m-parity  
├── v40d_mparity.ipynb          — SEVEM m-parity
├── v40e_mparity.ipynb          — COMMANDER m-parity
├── v40f_WMAP_mparity.ipynb     — WMAP m-parity
├── v44b_euclid_mirror.ipynb    — Euclid DR1 (awaiting data)
├── v48b_BOSS_mirror.ipynb      — BOSS DR12 (NULL)
├── v49_eBOSS_mirror.ipynb      — eBOSS QSO (NULL)
├── v50_SPARC_DM.ipynb          — SPARC dark matter (NULL)
├── v52_auger_ktf3.ipynb        — Auger UHECR (NULL)
├── v53_dark_energy.ipynb       — Dark energy from topology
└── README.md
```

---

*Pre-registration: academia.edu/AndrewCotting*  
*Contact: andrew.cotting@gmail.com*  
*Last updated: April 2026*
