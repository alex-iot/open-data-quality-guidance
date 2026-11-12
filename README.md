# Open data best practice for portals and AI use

Version 0.1, draft for comment · 12 November 2026

A dataset on an open data portal is only useful if its data and its metadata are true, and true to each other. This repository holds a first draft of best practice guidance on that subject: where portals fall short today, ten principles that would close the gaps, and three levels that show whether a dataset states what it promises, keeps to it, and whether it continues to do so over time. A rule reference and a worked example in DCAT-AP give the detail.

It is a draft for comment. It is best practice guidance, not a standard, and a table built on it is not a legal audit.

## What comment is sought

The aim of this first release is to find out whether practitioners agree on the problem and on the principles.

- **The gaps.** Do the gaps described in the guidance match what you see on portals?
- **The principles.** Do the ten principles hold? Is one missing, or one too many?
- **The two kinds of rule.** Beyond a few basics, is it right to hold a publisher to its own statement, and to report outside norms as gaps?
- **The rules.** Are any of the detailed checks in the rule reference too strict, too loose or missing?
- **The effect.** Would closing these gaps make the data easier to use, for people and for software?

The conditions and intervals behind the levels, and the detailed checks in the rule reference, are open to debate. The check period for level 3 is a starting value and has not yet been tested in practice.

## The idea in brief

Every dataset starts at "Not stated" and earns each level by evidence.

| Level | Question it answers |
| --- | --- |
| 1. Stated | Does the entry say what can be checked? |
| 2. Consistent | Does the data match what the entry says today? |
| 3. Kept consistent | Has it stayed consistent? |

A level counts only when its checks were made and passed. It is shown with the date of the check, and it lapses when a later check fails.

A dataset entry works like a contract that people and software rely on, and the levels show whether its terms are stated and kept. Level 1 asks the publisher to state the terms: what the data is, what may be done with it and when it changes. Levels 2 and 3 hold the publisher to those terms. A publisher can change the terms at any time so that they match reality. Rules that come from an outside norm, such as law or DCAT-AP, are mostly reported as gaps and do not hold a dataset back.

## What is here

| File | What it holds | Written for |
| --- | --- | --- |
| [guidance.md](guidance.md) | The principles, the levels and what a good dataset entry looks like, in plain words, with an example scorecard and thirteen typical failures | Portal teams, data owners and policy readers |
| [rule-reference.md](rule-reference.md) | The 40 rules and ten maintenance rules, each with an identifier, its basis in law or DCAT-AP, its level and its kind, with the scorecards and typical failures in full | Whoever runs or builds the checks, and reviewers who want the detail |
| [dcat-ap-worked-example.md](dcat-ap-worked-example.md) | One DCAT-AP 3.0.1 record taken through the levels, line by line, with a minimum and a typical record for contrast | Developers who produce a portal's metadata feed |
| [examples/](examples/) | The three example records from the worked example, in Turtle | Developers who want to test them |
| [pdf/](pdf/) | All three documents as PDFs | Readers who prefer a file to print or pass on |
| [figures/](figures/) | The two example scorecards and the DCAT-AP diagram as images | Anyone who wants to reuse them |

The Markdown files are the master copies; the PDFs are built from them.

## How to comment

Open an issue. Name the document and the section and, where it applies, the principle (for example principle 2) or the rule ID from the rule reference (for example T3). Corrections to the legal and DCAT-AP references are especially welcome.

## Versions

Each release is numbered and listed in the [change log](CHANGELOG.md).

## Licence

The documents, figures and example records are licensed under the Creative Commons Attribution 4.0 International licence (CC BY 4.0). You may share and adapt them for any purpose, including commercially, as long as you give appropriate credit, provide a link to the licence and indicate if changes were made. The full legal text is in [LICENSE](LICENSE).

Suggested credit: "Alex Gluhak, Open data best practice for portals and AI use, version 0.1, 2026", with a link to this repository.

## Author

Alex Gluhak (GitHub: [alex-iot](https://github.com/alex-iot)).
