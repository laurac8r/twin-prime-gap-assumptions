# From 246 to 6 — Twin-Prime Gap Assumptions

A single-page visual guide to the assumptions that take the **bounded prime gap**
down the short ladder **246 → 12 → 6**, ranked by how tractable each one is to
*prove*.

**Live site:** https://laurac8r.github.io/twin-prime-gap-assumptions/

It's a self-contained HTML page (no build step, no network, no JavaScript) — open
`index.html` by double-clicking, or visit the link above.

## Why this exists

The Maynard–Tao / Polymath8 bounded-gaps program pushes
H₁ = lim inf (pₙ₊₁ − pₙ) down a ladder. Strip away the rigorous machinery and
only **two** conjectural assumptions are actually load-bearing — and they are the
same conjecture at two strengths:

| Bound on H₁ | Rests on | Status |
| --- | --- | --- |
| ≤ 246 | Bombieri–Vinogradov theorem only (level θ = ½) | **Proven** (1965) |
| ≤ 12 | Elliott–Halberstam conjecture (EH) | Open |
| ≤ 6 | Generalized Elliott–Halberstam (GEH) | Open — strictly stronger than EH |
| 2 | no sieve method reaches it | Blocked by the parity barrier |

Everything else — the multidimensional sieve, admissible-tuple search, the
Mₖ optimization, the ε-enlargement trick — is unconditional and already done.

## The guide, for anyone with more patience to prove these

The page ranks the inputs from *already validated* to *needs genuinely new
mathematics*:

1. **Done** — sieve machinery + Bombieri–Vinogradov (θ = ½). Yields 246.
2. **Partial (evidence for EH)** — level just past ½ for *smooth* moduli
   (Zhang ½ + 1/584; Polymath8a ½ + 7/300), via Deligne's Weil-conjecture bounds.
3. **Partial (evidence for GEH)** — level past ½ for *convolutions* α∗β
   (Bombieri–Friedlander–Iwaniec; Fouvry–Iwaniec), accessible because they are
   bilinear (Type II).
4. **Open, well-posed** — full EH and GEH (any fixed θ > ½ over *all* moduli).
   **This is the prize.**
5. **No-go for sieves** — below 6 toward 2 is *not* an equidistribution
   assumption; Selberg's parity obstruction caps every sieve method at 6, so
   gap 2 needs a new, parity-breaking idea.

The page also unpacks the **GEH paradox** (harder as a full conjecture, yet
easier in the specific instances that have actually been proven) and the
**parity wall** that explains why the ladder stops at 6.

## Sources

- J. Maynard, *Small gaps between primes*, Annals of Math. 181 (2015) — [arXiv:1311.4600](https://arxiv.org/abs/1311.4600)
- D.H.J. Polymath, *Variants of the Selberg sieve, and bounded intervals containing many primes* (Polymath8b) — [arXiv:1407.4897](https://arxiv.org/abs/1407.4897)
- D.H.J. Polymath, *New equidistribution estimates of Zhang type* (Polymath8a) — [arXiv:1402.0811](https://arxiv.org/abs/1402.0811)
- Y. Zhang, *Bounded gaps between primes*, Annals of Math. 179 (2014)
- D.H.J. Polymath, *The "bounded gaps between primes" Polymath project — a retrospective* — [arXiv:1409.8361](https://arxiv.org/abs/1409.8361)
- A. Granville, *Primes in intervals of bounded length* (survey); T. Tao's blog and Bombieri-asymptotic-sieve notes

## Accessibility & licensing

The page passes a Lighthouse accessibility audit at 100/100: semantic landmarks,
WCAG-AA+ contrast in both light and dark modes, full keyboard focus rings, a
reduced-motion guard, and a print stylesheet.

Content is free to share and adapt with attribution.
