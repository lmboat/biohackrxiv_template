---
title: 'Oncomatch- Optimizing Oncology Combination Therapy Prediction'
title_short: 'BioITHackathon DrugCentral'
tags:
  - cheminformatics
  - proteomics
  - precision medicine
authors:
  - name: Shelby R. Kroeger*
    orcid: 0009-0009-1343-299X
    affiliation: 1
  - name: Lisa M. Boatner*
    orcid: 0000-0003-0757-4982
    affiliation: 2
  - name: Manasi Ghogare*
    orcid: 0009-0008-8765-167X
    affiliation: 3
  - name: Stanisław Giziński
    orcid: 0000-0002-3695-9809
    affiliation: 4
  - name: Ben Busby
    orcid: 0000-0001-5267-4988
    affiliation: 5
affiliations:
 - name: AbbVie Inc., North Chicago, IL, US
   index: 1
 - name: Momentum Biotechnologies, MA, US
   index: 2
 - name: Takeda Pharmaceuticals, MA, US
   index: 3
 - name: Deepflare, Warsaw, Poland
   index: 4
 - name: NVIDIA, CA, US
   index: 5
date: 26 June 2025
cito-bibliography: paper.bib
event: Bio IT World Hackathon 2025
biohackathon_name: "Bio IT World Hackathon 2025"
biohackathon_url:   " https://www.bio-itworldexpo.com/fair-data-hackathon"
biohackathon_location: "Boston, MA, US 2025"
group: DrugCentral
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/lmboat/biohackrxiv-template
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: Busby \emph{et al.}
---

<br><br/>

*co-first authors

# Introduction

As part of the BioHackathon Europe 2023, we here report...

## Author information

Information about the authors is given in the [YAML](https://en.wikipedia.org/wiki/YAML) format at the top of this template.
For authors you provide their names, their affiliations, and ideally their [ORCID](https://orcid.org/)
identifier. For affiliations, the [Research Organization Registry](https://ror.org/) (ROR) identifier can be given.
For example, this is the author information for this template:

```yaml
authors:
  - name: First Author
    affiliation: 1
  - name: Last Author
    orcid: 0000-0000-0000-0000
    affiliation: 2
affiliations:
  - name: First Affiliation
    index: 1
  - name: ELIXIR Europe
    ror: 044rwnt51
    index: 2
```

# Formatting

This document use Markdown and you can look at [this tutorial](https://www.markdowntutorial.com/).

## Subsection level 2

Please keep sections to a maximum of only two levels.

## Tables

Tables can be added in the following way, though alternatives are possible:

```markdown
Table: Note that table caption is automatically numbered and should be
given before the table itself.

| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |
```

This gives:

Table: Note that table caption is automatically numbered and should be
given before the table itself.

| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |

## Figures

A figure is added with:

```markdown
![Caption for BioHackrXiv logo figure](./biohackrxiv.png)
```

This gives:

![Caption for BioHackrXiv logo figure](./biohackrxiv.png)

Figures can be scaled by adding the width or height to the Markdown like this:

```markdown
![Caption for BioHackrXiv logo figure](./biohackrxiv.png){ width=50px }
```

# Other main section on your manuscript level 1

Lists can be added with:

1. Item 1
2. Item 2

# Citation Typing Ontology annotation

You can use [CiTO](http://purl.org/spar/cito/2018-02-12) annotations, as explained in [this BioHackathon Europe 2021 write up](https://raw.githubusercontent.com/biohackrxiv/bhxiv-metadata/main/doc/elixir_biohackathon2021/paper.md) and [this CiTO Pilot](https://www.biomedcentral.com/collections/cito).
Using this template, you can cite an article and indicate _why_ you cite that article, for instance DisGeNET-RDF [@citesAsAuthority:tothill_novel_2008].

The syntax in Markdown is as follows: a single intention annotation looks like
`[@usesMethodIn:Krewinkel2017]`; two or more intentions are separated
with colons, like `[@extends:discusses:Nielsen2017Scholia]`. When you cite two
different articles, you use this syntax: `[@citesAsDataSource:Ammar2022ETL; @citesAsDataSource:Arend2022BioHackEU22]`.

Possible CiTO typing annotation include:

* citesAsDataSource: when you point the reader to a source of data which may explain a claim
* usesDataFrom: when you reuse somehow (and elaborate on) the data in the cited entity
* usesMethodIn
* citesAsAuthority
* citesAsEvidence
* citesAsPotentialSolution
* citesAsRecommendedReading
* citesAsRelated
* citesAsSourceDocument
* citesForInformation
* confirms
* documents
* providesDataFor
* obtainsSupportFrom
* discusses
* extends
* agreesWith
* disagreesWith
* updates
* citation: generic citation


# Results


# Discussion

...

## Acknowledgements

...

## References
