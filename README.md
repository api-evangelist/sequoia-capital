# Sequoia Capital

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

**URL:** [https://raw.githubusercontent.com/api-evangelist/sequoia-capital/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sequoia-capital/refs/heads/main/apis.yml)

Sequoia Capital is one of the world's leading venture capital firms, founded in 1972 and headquartered in Menlo Park, California. Sequoia has backed transformative companies including Apple, Google, Oracle, Cisco, LinkedIn, Instagram, WhatsApp, YouTube, Airbnb, Stripe, and many others. Sequoia operates globally through dedicated funds including Sequoia Capital US/Europe, Sequoia India/Southeast Asia, and Sequoia China. This profile tracks Sequoia's developer resources, portfolio data APIs, and investment intelligence tools.

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### Sequoia Arc Program API

Sequoia Arc is the firm's structured program for early-stage seed companies. The Arc program provides cohort-based resources, curriculum, and networking for seed-stage founders.

**Human URL:** [https://www.sequoiacap.com/arc/](https://www.sequoiacap.com/arc/)

#### Tags

Venture Capital, Seed Stage, Early Stage, Founder Resources

#### Properties

- [Documentation](https://www.sequoiacap.com/arc/)

---

### Crunchbase Investment Data API

Crunchbase provides investment and startup data including Sequoia portfolio company information, funding rounds, valuations, and investor relationships. The Crunchbase API is widely used by analysts researching Sequoia's portfolio and deal history.

**Human URL:** [https://data.crunchbase.com/](https://data.crunchbase.com/)

#### Tags

Venture Capital, Investment Data, Portfolio Research, Startup Data

#### Properties

- [Documentation](https://data.crunchbase.com/)
- [Reference](https://data.crunchbase.com/reference/get_data-entities-organizations)

---

### PitchBook Investment Data API

PitchBook provides private equity and venture capital data including comprehensive Sequoia deal history, portfolio company valuations, fund performance, and limited partner information.

**Human URL:** [https://pitchbook.com/data/pitchbook-api](https://pitchbook.com/data/pitchbook-api)

#### Tags

Venture Capital, Investment Data, Private Markets, Fund Performance

#### Properties

- [Documentation](https://pitchbook.com/data/pitchbook-api)

---

## Common Properties

- [Website](https://www.sequoiacap.com/)
- [Portfolio](https://www.sequoiacap.com/companies/)
- [Arc Program](https://www.sequoiacap.com/arc/)
- [Blog](https://www.sequoiacap.com/articles/)
- [Podcast](https://www.sequoiacap.com/podcast/)
- [GitHub](https://github.com/sequoia-capital)
- [LinkedIn](https://www.linkedin.com/company/sequoia-capital/)

## Artifacts

### JSON Schemas

| File | Description |
|------|-------------|
| [sequoia-portfolio-company-schema.json](json-schema/sequoia-portfolio-company-schema.json) | JSON Schema for a Sequoia portfolio company record including funding rounds, executives, and exit details |

### JSON Structures

| File | Description |
|------|-------------|
| [sequoia-portfolio-company-structure.json](json-structure/sequoia-portfolio-company-structure.json) | Field-by-field structural documentation for portfolio company records |

### JSON-LD Context

| File | Description |
|------|-------------|
| [sequoia-context.jsonld](json-ld/sequoia-context.jsonld) | JSON-LD context mapping Sequoia vocabulary to schema.org for linked data semantics |

### Examples

| File | Description |
|------|-------------|
| [sequoia-portfolio-company-example.json](examples/sequoia-portfolio-company-example.json) | Example portfolio company record with funding rounds, executives, and exit details |

### Vocabulary

| File | Description |
|------|-------------|
| [sequoia-vocabulary.yml](vocabulary/sequoia-vocabulary.yml) | Venture capital and investment domain vocabulary covering funding stages, deal terms, and portfolio concepts |

## Maintainers

**Email:** kin@apievangelist.com
