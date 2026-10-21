# AFCON Historical Performance Analysis
### Competitive balance, national-team consistency and stadium attendance

**Bolaji Ibrahim Ajibola** | **PostgreSQL · Power BI · Excel · Power Query**

An independent analysis of the Africa Cup of Nations, connecting competitive results with regional representation, hosting patterns, player achievement and stadium attendance.

[Portfolio](https://ibrahimbolaji.framer.website/) · [All projects](https://github.com/bj985/jibol) · [Report guide](docs/report-guide.md)

## Why this project

Tournament success is not the same as participation, and total attendance is not the same as stadium utilisation. This project brings those distinctions into a dashboard and written reporting workflow so that the questions behind the visuals remain visible.

The core modern-era analysis covers **2000–2025**, with separate all-time comparisons and a broader hosting timeline. The coverage of each page must be read independently; scheduled hosting entries are not completed tournament results.

## Questions explored

| Theme | Analytical question |
| --- | --- |
| Competitive balance | How concentrated are titles and late-stage finishes? |
| Regional distribution | How do participation and achievements vary across African regions? |
| National-team consistency | Which teams sustain strong results across editions? |
| Hosting | How do hosting frequency and solo/co-hosting patterns differ? |
| Attendance | How do total crowds, spectators per match and stadium utilisation tell different stories? |
| Player achievement | What do scoring and award records add to the tournament narrative? |

## What I built

The project combines multi-source data preparation, SQL analysis, Power BI measures, interactive visuals and written interpretation. An existing five-page dashboard export covers the following areas:

| Dashboard section | Content |
| --- | --- |
| Tournament history | Hosting, eras, champions and regional title distribution |
| All-time team analysis | Participation versus performance, match records, points and scorer comparisons |
| Modern-era consistency | Podium finishes and progress into later tournament stages |
| Player analysis | Goal scoring, awards and repeated tournament achievement |
| Attendance and stadium efficiency | Attendance trends, crowds per match and capacity utilisation |

See the [report guide](docs/report-guide.md) for a reading order and the [metric definitions](docs/metric-definitions.md) for interpretation safeguards.

## Analytical approach

**Collect → clean → structure → query → model → visualise → explain.**

The analysis distinguishes scale from efficiency and frequency from achievement. A nation with many appearances has had more opportunities to accumulate wins; attendance totals are affected by the number of matches; regional comparisons depend on the country grouping used.

The wider project includes a written discussion of African football development and tournament readiness. Those arguments should be read as interpretations supported by evidence, not as causal conclusions established by a chart.

## Repository contents and status

This repository currently publishes the project overview, dashboard reading guide, metric definitions and SQL publication notes. The original dashboard export was reviewed for its structure, but the PDF itself, Power BI file and underlying working SQL have not been uploaded here in this update.

Numerical findings are deliberately not copied into the README until the selected filters, source coverage and calculations are reconciled. This is a documented portfolio project, not yet a fully reproducible data release.

## Sources and reuse

The existing project record identifies FBref, Transfermarkt and CAF material among its sources. A released dataset needs a table-level source register, extraction dates and clear definitions. The existing repository licence does not automatically grant rights to third-party datasets, photographs or footage.

## Author

**Bolaji Ibrahim Ajibola**  
Football Data Analysis and Business Intelligence  
[LinkedIn](https://www.linkedin.com/in/ajibola-bolaji/)
