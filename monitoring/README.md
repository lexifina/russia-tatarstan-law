<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Republic of Tatarstan only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 06:08 UTC, Republic of Tatarstan: Official Internet Portal of Legal Information (region16): 10 addresses read; 4 added, 0 changed, 0 removed; changes found; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Republic of Tatarstan: Official Internet Portal of Legal Information (region16)](http://publication.pravo.gov.ru/documents/block/region16) | `zakony-<year>/` | daily | 2026-11-28 06:08 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 06:07](checks/2026-11.md#ru-pravo-tatarstan-20261128t060740z) | pravo-tatarstan | 10 | 4 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-tatarstan-law/compare/a0e8834ae3f8...b835c628627f) |
| [2026-11-27 05:56](checks/2026-11.md#ru-pravo-tatarstan-20261127t055622z) | pravo-tatarstan | 10 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-26 06:02](checks/2026-11.md#ru-pravo-tatarstan-20261126t060230z) | pravo-tatarstan | 10 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-25 06:39](checks/2026-11.md#ru-pravo-tatarstan-20261125t063922z) | pravo-tatarstan | 10 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 14:55](checks/2026-11.md#ru-pravo-tatarstan-20261124t145536z) | pravo-tatarstan | 10 | 10 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-tatarstan-law/compare/0c302e9251c9...fb2d0c18188c) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
