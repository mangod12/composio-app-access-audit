# 100 apps: auth is not access

Evidence-first Composio Product Ops take-home, researched 23 November 2026.

Live case study: https://mangod12.github.io/composio-app-access-audit/

Open `index.html` locally for the single-page case study: 100-app matrix, patterns, pipeline, source links and honest verification results.

## Run the research pipeline

The runnable source, canonical assessments and independent review records are embedded in `bootstrap.py` as a standard ZIP. The full public-source evidence archive accompanies the submission. Download/clone this repository, then:

```sh
python bootstrap.py
cd research
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python demo.py --ids 4,22,58,98
```

Python 3.10+ required. On Windows, activate with `.venv\Scripts\activate`.

`demo.py` actually collects current public documentation for at most ten chosen apps, with two workers, into an isolated `runs/` folder. It produces unverified evidence candidates, not automatic correctness verdicts. No app credentials, paid API or model account is needed. The full collector and HTML builder are in `src/`.

The bootstrap contains runnable scripts, canonical assessments and both independent review records. The full submission ZIP additionally contains cached source snapshots, the ledger, support spans and tests. Run the full rebuild and tests from that extracted ZIP, not from the smaller bootstrap. Frozen initial extraction and both review results are preserved.

## Verification, not invented accuracy

- Purposeful 20-question diagnostic: 6 useful, 7 misleading, 7 missing initial candidates; 18 questions later resolved, one policy conflict and one identity gap retained. Not an accuracy benchmark.
- Independent AI-assisted review, sample 1: 20 apps, 60 claim groups, 51 supported / 0 contradicted / 9 insufficient.
- Independent AI-assisted review, disjoint sample 2: 20 apps, 60 claim groups, 42 supported / 1 contradicted / 17 insufficient. Clay table entitlement was corrected by interface.
- Neither round is overall accuracy or a human benchmark. Research-status placeholders were insufficient, not claims of absence. Scores are frozen before reconciliation and are not pooled.
- Human source checks: 0. Authenticated vendor API tests: 0. The page discloses this unmet assignment criterion, remaining gates and conflicts.

The assessment layer uses AI-assisted source reading. The deterministic scripts collect, preserve, extract and validate evidence; they do not claim independent reasoning or unattended correctness. No Composio SDK integration is claimed. Source snapshots are public documentation and may change. No private application email, credentials or employer data is included.
