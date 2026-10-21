# Metric definitions and interpretation

[Project overview](../README.md)

These are publication conventions for making the analysis explicit. They are not a transcription of uninspected Power BI measures. Confirm the implemented DAX and SQL against them before claiming reproducibility.

| Metric | Definition to document | Main safeguard |
| --- | --- | --- |
| Tournament appearances | Distinct editions in which the team participated | Do not count source rows as appearances without checking the grain |
| Win percentage | Wins divided by matches played, multiplied by 100 | State the match-result convention, including shootouts |
| Goals per match | Total goals divided by matches in the same scope | A simple average of edition averages gives each edition equal weight, not each match |
| Standardised points | Three times wins plus draws | Label separately from points under historical competition rules |
| Podium finishes | First-, second- or third-place finishes | Count unique team-edition placements |
| Stage appearances | Editions in which a team reached the named stage | Nested stages overlap; do not sum them as unique editions |
| Consistency score | A specified weighted combination of achievement measures | Publish weights, treatment of changing formats and sensitivity to choices |
| Average attendance | Attendance sum divided by matches with known attendance | Report how many matches are missing |
| Match-level capacity utilisation | Match attendance divided by usable capacity for that match | Use capacity valid for the match and competition |
| Weighted capacity utilisation | Sum of attendance divided by sum of usable capacity over the same covered matches | This differs from an unweighted mean of match percentages |
| Hosting count | Either editions hosted or host-country assignments | Label explicitly; co-hosting changes the relationship |

## Data model controls

Keep match, tournament, team-edition, player and award data at their intended grains. Validate keys before joins so a one-to-many country lookup cannot duplicate facts.

Record country-name changes separately from decisions to aggregate historical national teams. Geographic regions and football confederations are distinct classifications.

## Scope controls

Maintain separate labels for the modern results window, all-time histories and the hosting schedule. A scheduled edition contributes to planning analysis, not played-match totals or realised attendance.

## Source register

For each released table, record: provider, exact source URL, extraction date, competition, editions covered, row grain, field definitions, missingness and permission to redistribute. Do not substitute a provider's home page for the actual dataset reference.
