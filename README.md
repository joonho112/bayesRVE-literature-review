# A Literature Review of Robust Variance Estimation for Bayesian Meta-Analysis with Dependent Effect Sizes

*The case for Cholesky Calibration Correction (CCC)*

A claim-anchored literature review, published as a navigable HTML [Quarto](https://quarto.org) book. It traces a single object — the marginal RVE/CHE sandwich covariance that robust variance estimation fixes for dependent-effect meta-analysis — across three literatures (frequentist robust variance estimation; Bayesian hierarchical and multilevel meta-analysis; and the calibrated-Bayes paradigm) to motivate **Cholesky Calibration Correction (CCC)**, a Bayesian calibration method for meta-analysis with dependent effect sizes.

The review **positions and motivates** CCC; the formal results are developed in companion manuscripts (in preparation) and are cited here only as motivation.

## Reading the book

The book is built for navigation rather than front-to-back reading: use the sidebar to move between chapters, the in-page table of contents to move within one, the search box to find a method or author, and the clickable DOIs to reach every cited source.

- **Ch. 1 — Introduction & the inferential mismatch:** the three literatures and the join the review proposes.
- **Ch. 2 — The frequentist RVE lineage owns the target.**
- **Ch. 3 — Bayesian meta-analysis & the missing analogue.**
- **Ch. 4 — The calibrated-Bayes lens.**
- **Ch. 5 — Why Bayesian RVE specifically.**
- **Ch. 6 — The gap, the contribution & claim-type discipline.**
- **Ch. 7 — Boundaries & open questions.**
- **Appendix A — Claim index:** the catalogued claims the review is built on.
- **Appendix B — Literature database & pillar-by-theme map:** the read corpus, each entry with a clickable DOI.

## Building locally

This is a [Quarto](https://quarto.org) book (HTML output).

```bash
quarto preview   # live preview in the browser
quarto render    # build the static HTML site into _book/
```

Citations resolve from `references.bib` (BibTeX) rendered with `apa.csl`.

## Author

JoonHo Lee (jlee296@ua.edu)

## License

The book text, figures, and tables are released under **CC BY 4.0**; the Quarto build configuration and CSS are released under the **MIT License**. (See `LICENSE`.)
