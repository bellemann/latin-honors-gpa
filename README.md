# Latin honors GPA requirements at US colleges, 2026-27

The GPA a student needs for cum laude, magna cum laude and summa cum laude at 296 US colleges and universities in 48
states and DC. Each row is sourced to the school's own catalog, registrar page or published policy, and was checked on
19th Oct. 2026.

Browse it as a searchable table, with a calculator that shows which honors your GPA reaches:
**[simplegpacalculator.com/latin-honors-gpa](https://simplegpacalculator.com/latin-honors-gpa/)**

## Headline numbers

- 206 schools (70%) use fixed GPA cutoffs, 57 (19%) rank students against their class (alone or mixed with a GPA
  floor), 25 award no Latin honors and 8 use another rule.
- The most common fixed set is 3.50 / 3.70 / 3.90 for cum / magna / summa (64 schools). It is also the median.
- Fixed cutoffs range from 3.00 to 3.75 for cum laude, 3.30 to 3.85 for magna cum laude and 3.70 to 4.00 for summa
  cum laude.

## Files

- [`latin-honors-gpa-2026.csv`](latin-honors-gpa-2026.csv): one row per school, UTF-8, comma-separated.
- [`datapackage.json`](datapackage.json): column types in the [Frictionless Data](https://specs.frictionlessdata.io/)
  format.

## Columns

| Column | Meaning |
|---|---|
| `institution` | School name |
| `state` | Two-letter state code (DC for Washington, DC) |
| `method` | `fixed GPA`, `percentage of class`, `mixed`, `no Latin honors` or `other` |
| `cum_laude`, `magna_cum_laude`, `summa_cum_laude` | The cutoff as the school writes it: a GPA for fixed rules, a class share (for example `top 5%` or `next 10%`) for percentage rules |
| `extra_requirements` | Residency credits, letter-graded hours and similar conditions |
| `catalog_year` | Catalog edition the rule comes from, when the source states it |
| `source_url` | The official page the row was taken from |
| `checked` | Date the source was read (YYYY-MM-DD) |
| `notes` | Anything the row needs to be read correctly |

## Method

- Schools: we started from about 380 schools (the largest US universities by enrollment, the top national
  universities and liberal arts colleges in the U.S. News rankings, and other well-known public and private colleges).
  The 296 here are the ones we could confirm.
- Sources: only the school's own pages count. No rankings sites, forums or other GPA websites. A school we could not
  confirm on an official page is left out, not estimated.
- Cutoffs are copied as written. Schools differ on rounding and on which credits count; `extra_requirements` and
  `notes` say so where the source does.

Full methodology: [simplegpacalculator.com/latin-honors-gpa](https://simplegpacalculator.com/latin-honors-gpa/#methodology).

## License and citation

[Creative Commons Attribution 4.0](LICENSE). Reuse it for anything, including commercial work; credit Simple GPA
Calculator and link to [the dataset page](https://simplegpacalculator.com/latin-honors-gpa/).

> Simple GPA Calculator. (2026). *Latin honors GPA requirements at 296 US colleges and universities, 2026-27*
> [Data set]. Checked 19th Oct. 2026. https://simplegpacalculator.com/latin-honors-gpa/

## Corrections

Found an outdated rule or a school we should add? Open an issue here or email support@simplegpacalculator.com with a
link to the official page. The CSV here mirrors the
[download on the site](https://simplegpacalculator.com/latin-honors-gpa-2026.csv); both are updated together.
