# Welcome to kev-data

This repository is home to the data files that make up the Known Exploited Vulnerabilities (KEV) catalog. The data is originally sourced from https://www.cisa.gov/known-exploited-vulnerabilities-catalog, which is short linked at https://cisa.gov/kev. 

## File formats

Currently, KEV data is produced in two formats, [CSV](known_exploited_vulnerabilities.csv) (Comma-Separated Values) and [JSON](known_exploited_vulnerabilities.json) (JavaScript Object Notation).

Additionally, this repo also contains the most current [JSON schema](known_exploited_vulnerabilities_schema.json) for the KEV data.

## Update schedule

This repository is updated whenever the [KEV](https://cisa.gov/KEV) is updated. Technically, this repo is updated shortly after the canonical source at cisa.gov is updated, which typically happens weekdays during normal US Eastern business hours when there are new or updated KEV entries. Users should expect both sources ([cisa.gov](https://cisa.gov/KEV) and [github.com](https://github.com/cisagov/kev-data/blob/main/README.md)) to be synchronized within minutes of each other.

The JSON schema will also remain in sync, though that file is not expected to be updated frequently (perhaps a few times per year).

## Contributing

We welcome contribution suggestions from the public to make this repository better and more accurate. Please see this repository's [CONTRIBUTING.md](CONTRIBUTING.md) for more detail. In summary, we expect issues and pull requests to address purely technical issues like typos in prose, broken links to remediation guidance, accidental schema violations, and the like.

Notably, **this is not a repo for requesting additions or deletions of KEV entries**. The KEV is managed by CISA directly, and CISA's requirements for KEV addition are fairly strict, relying on the authority of [BOD 22-01](https://www.cisa.gov/news-events/directives/bod-22-01-reducing-significant-risk-known-exploited-vulnerabilities).

Tips or suggestions about individual entries (beyond technical bug reports) should be directed via email to [KEV@mail.cisa.dhs.gov](mailto:KEV@mail.cisa.dhs.gov).

## Usage

The purpose of this repo of KEV data is to enable easier usage of the KEV JSON and CSV files that CISA produces. GitHub provides a rich API for querying and downloading data sets, so oftentimes, code that is developed and maintained on GitHub (and beyond) has an easier time consuming data sources from GitHub than they might from US government websites.

In addition, the git commit history provided by GitHub can make tracking changes to data sources like the KEV easier and more transparent. The KEV, in particular, has no inline file revision history or log that's easily accessible after the fact. Related vulnerability tracking projects, such as the [CVE List](https://github.com/CVEProject/cvelistV5) and [Vulnrichment](https://github.com/cisagov/vulnrichment) benefit from this kind of public logging and public issue tracking functionality.

## Licensing

This data repository is licensed under the CC0 license, which allows for universal public domain use of the information here. This is identical to the licensing found at https://www.cisa.gov/sites/default/files/licenses/kev/license.txt.
