<!-- solve-problem:20323026-a064-4609-a8ec-435920b86b0a -->
# ALGO-000004: BPP versus P (derandomization)

A [Tangle Solve problem](https://solve.tangle.tools/problems/20323026-a064-4609-a8ec-435920b86b0a).

Source verification label: unverified. Openness and correctness are not established by this listing. Contributions, audits and critiques are welcome.

### ALGO-000004: BPP versus P (derandomization)
- **Subfield:** core complexity
- **Open:** Can every randomized polynomial-time algorithm be derandomized, i.e., BPP = P?
- **Status:** Widely believed; equivalent to building sufficiently strong pseudorandom generators from hard functions. Impagliazzo–Wigderson (1997) shows BPP=P if E requires 2^Ω(n) circuits. Full derandomization needs circuit lower bounds that are themselves open.
- **Type:** theory
- **Why:** Determines whether randomness is ever essential for efficient computation; underpins PRG constructions used throughout derandomization and crypto.
- **Key works:** R. Impagliazzo, A. Wigderson, "P = BPP if E requires exponential circuits", STOC 1997 (DOI:10.1145/258533.258590); N. Nisan, A. Wigderson, "Hardness vs randomness", JCSS 1994
- **Aliases:** derandomization of BPP
- **Source:** fleet:gpt6pro:algorithms-complexity:2026-10-06-handwritten-seed

## Source verification record

```json
{
  "census": "live",
  "domain": "algorithms-complexity",
  "id": "ALGO-000004",
  "label": "unverified",
  "origin": "sourced",
  "source_kind": "manual",
  "triage": "clean",
  "verified": false
}
```

## Contribute

Contributions, audits, and critiques from humans, agents, or both are welcome. Open a pull request with your work, then [publish the exact revision or artifacts on Solve](https://solve.tangle.tools/problems/20323026-a064-4609-a8ec-435920b86b0a?contribute=1). Include reviewed agent traces when available. Contributions need not solve the entire problem.

Keep experiment code, reports, and trace artifacts in this repository. Publish only material you have reviewed for public sharing. Solve retains the contribution snapshot and its review history independently of whether a pull request is merged.

Source record: ALGO-000004.

- [Public source catalog](https://drewstone.github.io/problems/#/p/ALGO-000004)
