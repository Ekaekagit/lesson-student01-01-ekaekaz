# lesson-student01-01-ekaekaz
lesson-student01-01-ekaekaz created by GitHub Classroom

## Comparing files against another repo

`scripts/compare_repos.py` diffs the tracked files of two git repositories by
content hash and prints a Markdown report (identical files, same-path
content changes, files unique to each side, and same content living under a
different path).

```bash
python3 scripts/compare_repos.py <repo1> <repo2> [--output report.md]
```
