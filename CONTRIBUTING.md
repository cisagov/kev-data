# Contributing to kev-data

Thank you so much for your interest in making CISA's Known Exploited Vulnerabilities catalog better! This repo is a mirror of the official source of KEV data, at [https://www.cisa.gov/known-exploited-vulnerabilities-catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog) (which is short linked at [https://cisa.gov/KEV](https://cisa.gov)).

## Expected Issues

We expect most of the public activity on this repo to be in the form of issues tracked at [https://github.com/cisagov/kev-data/issues](https://github.com/cisagov/kev-data/issues). While of course we strive for an error-free experience with KEV, it's possible for the occasional bug to crop up, such as:
  * Typos or misspellings of product or vendor names
  * Mischaracterized CWE (Common Weakness Enumeration) identifiers
  * Transposed CVE IDs
  * Duplicate entries
  * JSON schema violations
  * Malformed CSV entries
  * Broken links to external resources

If you see any bugs like these, we sure would appreciate knowing about them so we can fix them!

## Unexpected Issues

On the other hand, there are some issues that we don't expect to address in this repo. Namely, we don't intend to use this repository to nominate or investigate reports of exploitation of a vulnerability, to request a CVE ID for a newly discovered vulnerability, or examine recommended patches or updates. Those kinds of requests should instead be directed to [KEV@cisa.dhs.gov](mailto:KEV@cisa.dhs.gov), which is directly monitored by the CISA employees responsible for maintaining the KEV.

In short, this repo's issues tracker is best used for technical issues involving the KEV data and its formatting. The content of the KEV and which vulnerabilities qualify for inclusion is managed directly at CISA, as required by [BOD 22-01](https://www.cisa.gov/news-events/directives/bod-22-01-reducing-significant-risk-known-exploited-vulnerabilities).

## Pull Requests

While we will make every effort to merge accepted PRs cleanly to the data files (thus, preserving GitHub credit), there will be occasions where your change will be overwritten in a future update on CISA's backend, since this repository is ultimately a copy of the official data files hosted at https://www.cisa.gov. This repo's maintainers will make the determination, on a case-by-case basis, on how to best resolve PRs as they come up. That said, we very much appreciate your efforts to make the KEV data files more accurate!