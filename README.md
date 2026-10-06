# NCDP Field Manual

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22867526.svg)](https://doi.org/10.5281/zenodo.22867526)

Field operations manual for the **National Coastal Drone Program** — a
nationally coordinated archive of UAV coastal survey data, coordinated by
Deakin University and funded by AuScope (NCRIS).

Written for citizen science volunteers and partner organisations flying RTK
drone surveys of the Australian coast. It covers equipment, site selection,
mission planning, flight operations, safety and incident reporting, and how to
upload a completed survey.

## Download

| File | |
|---|---|
| [NCDP_Field_Manual.pdf](NCDP_Field_Manual.pdf) | PDF, 61 pages — for reading and printing |
| [NCDP_Field_Manual.docx](NCDP_Field_Manual.docx) | Word version, for adapting |

These are the current working copies, including any corrections made since
the last published edition. The edition is printed on the manual's cover page
and listed in [CHANGELOG.md](CHANGELOG.md). Direct link to the latest PDF:
`https://raw.githubusercontent.com/NCDP-Australia/ncdp-field-manual/main/NCDP_Field_Manual.pdf`.

The citable, archived copy of each edition is on Zenodo:
**[doi.org/10.5281/zenodo.22867526](https://doi.org/10.5281/zenodo.22867526)**.
That DOI always resolves to the latest edition; each edition also has its own
DOI, listed on the Zenodo record and in the changelog.

The manual is free for anyone to use, share and adapt under
[CC BY 4.0](LICENSE), provided the NCDP Field Manual is credited (see below).

## How to cite

> Ierodiaconou, D., Allan, B., & Nuyts, S. (2026). *National Coastal Drone
> Program (NCDP) Field Manual*. Zenodo.
> https://doi.org/10.5281/zenodo.22867526

To cite a specific edition (for example, the one used in a study), use that
version's DOI from the Zenodo record instead.

## Authors

- Daniel Ierodiaconou, Deakin University — [0000-0002-7832-4801](https://orcid.org/0000-0002-7832-4801)
- Blake Allan, Deakin University — [0000-0003-0101-3412](https://orcid.org/0000-0003-0101-3412)
- Siegmund Nuyts, Deakin University — [0000-0001-6450-7028](https://orcid.org/0000-0001-6450-7028)

## Related

Data standards, metadata schema and templates are published separately at
[NCDP-Australia/ncdp-standards](https://github.com/NCDP-Australia/ncdp-standards).
Surveys are submitted through the intake portal at
[ncdp.auscope.org.au](https://ncdp.auscope.org.au).

The citizen science UAV approach the manual is built on is documented in
Ierodiaconou et al. (2022), *Continental Shelf Research* 244:104800,
[doi:10.1016/j.csr.2022.104800](https://doi.org/10.1016/j.csr.2022.104800).

## Versioning

The files keep the same names from edition to edition; the edition lives in
the document, the changelog and the git history. The manual is versioned
independently of the data standards — a change to the metadata schema does
not imply a new manual, and vice versa.

Current edition: **v1.0** (2026-09-15).

To publish a new edition:

1. Update the `.docx`, export the `.pdf`, and update the edition and date on
   the cover page.
2. Add the edition to [CHANGELOG.md](CHANGELOG.md), commit, and tag the commit
   `vX.Y` (`git tag -a v1.1 -m "Field Manual v1.1" && git push --tags`).
3. On the Zenodo record, use **New version**, upload the new PDF, set the
   version number to `X.Y` and publish. Paste the new edition's DOI into the
   changelog entry.

The concept DOI moves to the new edition automatically; the website's
Resources page links the concept DOI and the repository PDF, so nothing there
needs changing.

Small corrections between editions (typos, a changed URL) can be committed to
the working copy without a new edition; they are folded into the next one.

## Licence

[CC BY 4.0](LICENSE).
