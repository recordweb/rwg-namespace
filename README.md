# RecordWeb Guide: Namespace Governance (RWG Namespace)

A RecordWeb Community Group guide on how organisations take responsibility for [namespaces](https://recordweb.github.io/rwt/#namespace①) in RecordWeb: who decides, who operates, how long the responsibility lasts, and what must be in place when systems, providers or organisations change.

- **Editor's Draft:** https://recordweb.github.io/rwg-namespace/
- **Version:** 0.0.1 (Draft Community Group Report)
- **Editor:** Nik Jenzer
- **Language:** German (first version). An English version will follow.

## Purpose

The RecordWeb Protocol ([RWP](https://recordweb.github.io/rwp/)) makes record identifiers technically resolvable. It does not define who is responsible for keeping a namespace resolvable over time. This guide describes that responsibility and gives organisations a basis for decisions, for procurement and for planning transitions and failures.

The guide is **informative**. It contains no requirements in the sense of RFC 2119. Normative requirements are defined in RWP. Recommendations in this guide are marked as such.

## Scope

The guide covers:

- purpose and principles of a namespace
- terms and roles (owner, operator, custodian, vendor; global and local namespaces)
- tasks and requirements for DID providers, namespace providers and namespace resolvers
- how to scope a namespace
- registration and use of the Global Namespace Registry (GNR)
- duration of responsibility
- transitions (system change, provider change, transfer to an archive, change of owner)
- disruption and failure
- a checklist of questions to settle before a procurement

It does not cover trust in agents or namespaces, access control, the deletion regimes of RWP, legal liability models, or product recommendations.

Examples from Swiss public administration appear in parentheses and are marked as examples. The text itself is general.

## Relationship to other RecordWeb documents

| Document | Relationship |
|---|---|
| [RWP](https://recordweb.github.io/rwp/) | Normative protocol. This guide does not change it. |
| [RWT](https://recordweb.github.io/rwt/) | Source of shared terms. This guide links to it. Terms used only here (owner, operator, vendor, registrant) stay in this guide until another report needs them. |
| [RWC](https://recordweb.github.io/rwc/) | Concept. A chapter proposal on namespace stewardship is under discussion. This guide deepens it and should not contradict it. |
| RWO | Ontology. Candidate classes and properties for namespaces are tracked in the RWO repository. |

## Repository contents

| File | Description |
|---|---|
| `index.bs` | Source of the guide in [Bikeshed](https://speced.github.io/bikeshed/) format |
| `README.md` | This file |

## Building the guide

The guide is written in Bikeshed. To build it locally:

```sh
pip install bikeshed
bikeshed update
bikeshed spec index.bs
```

This produces `index.html`. Links to RWT terms are defined in the `anchors` block at the top of `index.bs`. They point to the published RWT document and must be updated if RWT changes its fragment identifiers.

## Contributing

Feedback is welcome as GitHub issues in this repository. Please state the section number and, where possible, suggest wording.

Governance, contribution rules and the call-for-consensus process of the RecordWeb Community Group are described in the organisation's [`.github` repository](https://github.com/recordweb/.github). Please read them before opening a pull request.

Issues that concern other documents belong in the respective repository:

- protocol requirements and terminology in RWP: [recordweb/rwp](https://github.com/recordweb/rwp)
- shared terms: [recordweb/rwt](https://github.com/recordweb/rwt)
- the ontology: the RWO repository

## Status

This is a first draft prepared for discussion in the community. Open points are collected in Annex B of the guide. All chapters are drafted. Content, structure and terminology may change.

## License

Copyright © 2026 the Contributors to the RecordWeb Guide: Namespace Governance, published by the [RecordWeb Community Group](https://www.w3.org/community/recordweb/) under the [W3C Community Contributor License Agreement (CLA)](https://www.w3.org/community/about/process/cla/). A human-readable [summary](https://www.w3.org/community/about/process/cla-deed/) is available.