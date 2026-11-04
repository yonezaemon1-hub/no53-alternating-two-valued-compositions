# Rank-Unimodality Below Alternating Two-Valued Compositions

**No.53 · Preprint v1.0 · 4 November 2026**  
**Ryutaro Yonezu — Independent Researcher**

This computer-assisted mathematics preprint proves rank-unimodality of the principal ideal below the composition `(a,b)^m` in generalized subword order, for every integer `a>b>=1` and every `m>=1`. This is a **restricted family**, not the general composition rank-unimodality conjecture.

## Publication and review disclosure

- **Publication type:** Preprint (not peer-reviewed by humans).
- **Mathematics:** MODEL, PROOF-Q2, PROOF-MIDRANK, PROOF-BASE, PROOF-TRANSFER and COMPUTATION reported PASS in an independent Claude AI re-audit of the supplied v0.4 package. The re-audit combined code reading, reproduction, independent algebraic checks and mutation tests. This report is user-supplied; AI auditing does not replace human peer review.
- **Novelty:** **INCONCLUSIVE**. The full papers of Chen (2026) and Zhang (2026) were not inspected; their publicly visible abstracts were reviewed. No guarantee of priority or originality is made.
- **License/rights:** **All rights reserved**. No open-source or reuse license is granted merely by publication.
- **Reproducibility:** Python 3.10+, free SymPy preinstalled. Runs offline once dependencies are present. Linux checks passed; Windows PowerShell 5.1 execution of v0.4 was **not independently verified**.

## Downloads

When the repository release is created, attach these files *without modifying their bytes*:

- `No53_v1.0_PREPRINT_20261104.pdf` — 5-page manuscript.
- `No53_v1.0_REPRODUCIBILITY_20261104.zip` — scripts, frozen v0.4 audit snapshot, symbolic certificate, exact integer checks, TeX source and verification notes.

No DOI or publication URLs should be added until an actual public repository/release and Zenodo record are verified.

## Reproduction

Extract the reproducibility ZIP. From the included `frozen_v0.4/` directory run:

```text
python -I verify_sha256_v0.4.py
python -I No53_independent_q2_two_kernel_v0.4.py
python -I No53_Q2_logconcavity_symbolic_verifier_v0.1.py
python -I verify_transfer_symbolic_v0.2.py
python -I independent_transfer_checks_v0.2.py
```

The two Q² verifiers rely on SymPy and share a chamber partition and computer algebra environment; they are algebraically distinct but not entirely independent formal foundations. **Do not run `python -O`**, which disables the assertions used by the certificates.

For Windows PowerShell 5.1, see the archived `run_windows_v0.4.ps1`. No Windows PASS is claimed by the authoring environment.

## Bibliographic boundaries

- Vincent Vatter (2026), arXiv:2602.16355v3, general context and conjecture.
- Lizhong Chen (2026), SSRN 7385218, public abstract only, full text uninspected.
- Zhanhe Zhang (2026), SSRN 7397439, public abstract only, full text uninspected.
- Maurice Pouzet (2008), first-half rank monotonicity; the present manuscript also gives a self-contained inclusion-operator proof.
- J. Keilson and H. Gerber (1971), discrete strong unimodality under convolution.

**Archive note:** Historical `HOLD` statements inside `frozen_v0.4/` are unmodified evidence of the prepublication audit; they are superseded by the owner's explicit authorization to issue v1.0. They do not imply that this version is human peer-reviewed or novelty-cleared.
