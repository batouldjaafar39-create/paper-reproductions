# Paper Reproductions & Reproducibility Audits

Independent reproducibility audits of published machine learning and security research — verifying methodology, checking claims against code and results, and documenting discrepancies where found.

This is ongoing work as part of building a research track record: no institutional lab, no funding, no supervisor — just methodical verification of published work, done independently.

## Author

**Djaafar El Batoul**
University Ahmed Zabana, Algeria
ORCID: [0009-0009-7285-2994](https://orcid.org/0009-0009-7285-2994)

## Audits

### E1D3 U-Net (Brain Tumor Segmentation, BraTS 2021)
Reproducibility audit of [arXiv:2110.02519](https://arxiv.org/abs/2110.02519).
- Identified a discrepancy between the paper's stated epoch count (500) and the released repository (1000)
- Traced downstream effects on the learning-rate decay curve
- Flagged two additional items requiring code-level verification

📁 [`/e1d3-unet`](./e1d3-unet)

### Cross-Dataset Generalization in Pneumonia Detection (Zech et al., 2018)
Reproducibility audit examining cross-dataset generalization claims.
- Scoped audit methodology and justified rejecting a partial reproduction
- Documented implications for future reproduction targets and strategy

📁 [`/zech-pneumonia-generalization`](./zech-pneumonia-generalization)

## Method

Each audit generally covers:
1. **Scoping** — what exactly is being verified, and what's out of reach given available compute/data
2. **Verification** — comparing paper claims against released code, data, and (where feasible) re-run results
3. **Findings** — discrepancies, ambiguities, or confirmations, with evidence
4. **Implications** — what this means for trusting/building on the original work

## Related Work

See also: [Argus](link-to-argus-repo) — original research on evidence-grounded LLM-assisted SOC investigation.

## Contact

Open an issue or reach out via ORCID for questions about any audit.
