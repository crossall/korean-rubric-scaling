# Korean rubric dependent model size study

Code and aggregate reproducibility materials accompanying **Rubric dependent associations between Qwen3 model size and Korean constructed response scoring**, by Taeryeong Kim, Gyeongin National University of Education.

## Version 1.0.0

The complete source tree is distributed as `paper1-rubric-scaling-v1.0.0.zip` in this repository. Download and extract the archive, then follow its README. The archive contains analysis and scoring scripts, frozen configurations, synthetic tests, non-identifying aggregate inputs and expected outputs. No student-level data are included.

Permanent version archive: [Zenodo DOI 10.5281/zenodo.23322382](https://doi.org/10.5281/zenodo.23322382).

SHA-256 of the release archive:

```text
469422a556f268d3e18ffd05d67cb6e952af9b90cc04f5cddd74e21eb8de6dfd
```

The release passed all 28 synthetic tests, archive manifest verification, and offline replay checks. Its numerical inputs and scientific scripts are byte-identical to the verified release candidate. These checks verify aggregate computational replay, not independent reconstruction of historical API generations.

## Reproduction boundaries

The study uses 4,000 constructed responses and 2,000 essays from AI Hub Validation splits, not a verified official test set. The available code recreates six tables, two figures and supplementary sensitivity results from aggregate materials. Full record-level reanalysis requires separately authorized AI Hub datasets 71818 and 71819 and the matching private predictions. Human-reference, judgment-demand and post-outcome diagnostic limitations are documented in the package.

Student responses, identifiers, row-level human ratings and model predictions, source rubric text, raw API logs, credentials, expert forms and private ethics documents are excluded. No public redistribution rights for the source AI Hub data are asserted. This release is software and computational materials, not publication of the manuscript or an independent student dataset.

## Attribution and licensing

Use `CITATION.cff` for the software citation. Original author-owned code is licensed under MIT; author-owned documentation and aggregate results are CC BY 4.0. These are file-scoped licenses, not alternative licenses covering all third-party content. See the package notices. Substantial AI assistance is disclosed in the package; the human author remains responsible for research and publication decisions.
