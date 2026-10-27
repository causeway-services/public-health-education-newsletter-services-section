# The Second Day

<!-- 561-group-standards:badges:start -->
[![Causeway Services](https://img.shields.io/badge/561%20Group-Causeway%20Services-115e69)](https://github.com/causeway-services)
[![License: Apache 2.0](https://img.shields.io/badge/license-Apache%202.0-115e69)](LICENSE)
[![Indigenous data: CARE](https://img.shields.io/badge/Indigenous%20data-CARE-4b6f44)](https://github.com/causeway-services/.github/blob/main/GOVERNANCE.md)
[![Tips welcome](https://img.shields.io/badge/tips-welcome-d4a017)](https://github.com/561-group/.github/blob/main/TIPS.md)
<!-- 561-group-standards:badges:end -->

The Second Day is a health-synthesis newsletter about infection-associated chronic illness, including definitions, proposed mechanisms, and care evidence. Its canonical issue data and Markdown, paste-ready HTML, and feed renderings stay in `content/issues/`. The cited scientific corpus is shared with [the health curriculum](../health-education-curriculum-services-section/README.md) and the [medical-science material](../../../../../../../../../science-services-section/services/natural-science-services-section/services/biological-science-services-section/services/medical-science-services-section).

Draft delivery uses the shared newsletter engineering implementation and its Buttondown API capability. From this directory:

```sh
node ../../../../../../../../../engineering-services-section/services/computer-engineering-services-section/services/computer-data-engineering-services-section/services/computer-content-engineering-services-section/services/computer-documents-engineering-services-section/services/email-newsletter-engineering-services-section/scripts/publish-issue-draft.mjs content/issues/001 --feed-link https://secondday.561.group/issues/001 --data-root data
```

Set `BUTTONDOWN_API_KEY` in the environment. The operation validates and recomposes the issue, creates a Buttondown draft, and appends its returned identifier to `data/publications.jsonl`. Existing historical journal records remain available under `data/`. Sending an issue is a separate action. The paste-ready HTML also supports manual cross-posting to emsenn's personal Substack, *Letters to the Web*.

The archive name is `secondday.561.group`; this document does not establish that the archive is deployed. The historical pricing research suggested $5–10 per month, without establishing a selected price or an active subscription offer. Issue 001 exists; additional issues and sourcing/coherence review precede subscriber solicitation or payment collection.
