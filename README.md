# paper-checker

Scheduled routine that scans https://arxiv.org/list/cs.IR/recent for papers in
or applied to the legal domain and emails matches to the user.

`data/sent_papers.json` tracks which papers have already been emailed
(keyed by arXiv id) so future runs don't send duplicates, along with the
timestamp of the last run.
