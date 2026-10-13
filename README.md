# Criterion-Dependent Associations between Qwen3 Model Size and Zero-Shot Scoring of Korean Constructed Responses

Code and Aggregate Reproducibility Materials by **Taeryeong Kim**, Gyeongin National University of Education.

## Current version: 1.0.1

Permanent version archive: [Zenodo DOI 10.5281/zenodo.23345003](https://doi.org/10.5281/zenodo.23345003).

Download [paper1-rubric-scaling-v1.0.1.zip](paper1-rubric-scaling-v1.0.1.zip), **extract it**, and run the commands below from the extracted directory. The complete source tree is inside the ZIP, not at this repository root. Its SHA-256 is:

```
f019f06f69693958ab56fa0cbf065b1f7f5d154e1b69994a2007375b024f9430
```

Version 1.0.1 is a documentation-only revision. It aligns the title, citation metadata, README, provenance and Supplementary Methods S1 with the final submission. The [S1 PDF](Paper1_Applied_Sciences_Supplement_S1_20261013.pdf) is identical to the submission supplement. All 38 pre-existing files outside the six documentation/metadata/manifest files are byte-identical to v1.0.0, including all code, frozen configurations, aggregate data, expected outputs and licenses. No new inference or analysis was performed. The manuscript and cover letter are not publicly included. See [CHANGELOG.md](CHANGELOG.md).

## Offline aggregate replay

Use Python 3.11 or newer. After extracting the ZIP:

```sh
python -m pip install -r requirements-analysis.txt
python verify_manifest.py
python reproduce_aggregate.py
python reproduce_review.py
python -m unittest discover -s scripts -p "test_paper1*.py"
```

The v1.0.1 ZIP passed all **28 synthetic tests**, all **45 packaged-file checksums**, and offline replay of **six tables, two figures, and noninferiority sensitivity**. Once dependencies are installed, these commands require no network, API key, GPU or student data. They do not execute archived inference modules, some of which can make paid calls when separately configured.

## Reproducibility boundaries and data protection

The study used 4,000 constructed responses and 2,000 essays from available AI Hub Validation splits, not official Test files. Aggregate replay is not independent reconstruction of record-level ratings or historical API calls. Full reanalysis requires authorized AI Hub datasets 71818/71819, corresponding private manifests and historical predictions. JDI and post-outcome diagnostics remain exploratory. Historical configurations preserve their original wording and execution labels, not revised claims of confirmation.

Student responses, response identifiers, original text hashes, row-level human ratings/predictions, raw API logs, item-specific source rubrics, credentials, expert forms and private ethics documents are excluded. No public redistribution rights for the source AI Hub data are asserted. This is a computational-materials release, not publication of the manuscript or an independent student dataset.

On 13 October 2026, the author stated that existing exemption P01-202605-01-076 applied to the present secondary analysis. This attestation is not presented as a new institutional determination specifically covering hosted or external API processing; the private determination is not included in the public release.

## Citation, licensing and earlier versions

Use [CITATION.cff](CITATION.cff) to cite the version DOI. Author-owned code is MIT; author-owned documentation and aggregate materials are CC BY 4.0. Licenses are file-scoped, and no third-party rights are granted. See the ZIP's license notices. Substantial AI assistance and its documentation limitations are disclosed; the human author retains responsibility.

Version 1.0.0 remains preserved in this repository and at [its version DOI](https://doi.org/10.5281/zenodo.23322382). The [concept DOI](https://doi.org/10.5281/zenodo.23322381) represents all versions. Use the specific v1.0.1 DOI when citing the materials accompanying the current submission.
