# Localazy (localazy)

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

Localazy is a localization and translation management platform built for developers. Its REST API at https://api.localazy.com lets teams import and upload source content, export and download translated files, list and manage files, languages, and projects, and drive AI-assisted translation - all authenticated with project, translation, or organization tokens.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/localazy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/localazy/refs/heads/main/apis.yml)

## Tags

- Localization
- Translation
- Internationalization
- i18n
- L10n
- Translation Management

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Localazy Import / Upload API

Imports and uploads source and translation strings into a Localazy project from any supported file format, and lists the available import file formats and their capabilities.

- **Human URL:** [https://localazy.com/docs/api/import](https://localazy.com/docs/api/import)
- **Base URL:** `https://api.localazy.com`

#### Tags

- Import
- Upload
- Content

#### Properties

- [Documentation](https://localazy.com/docs/api/import)
- [API Reference](https://localazy.com/docs/api/import)
- [OpenAPI](openapi/localazy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/localazy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/localazy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Localazy Export API

Exports translated content by downloading a file in a specific language, returning the localized file contents ready for use in an application.

- **Human URL:** [https://localazy.com/docs/api/files](https://localazy.com/docs/api/files)
- **Base URL:** `https://api.localazy.com`

#### Tags

- Export
- Download
- Translations

#### Properties

- [Documentation](https://localazy.com/docs/api/files)
- [API Reference](https://localazy.com/docs/api/files)
- [OpenAPI](openapi/localazy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/localazy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/localazy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Localazy Files API

Lists the files in a project and reads file content as keys and translations for a given language, with pagination and metadata options.

- **Human URL:** [https://localazy.com/docs/api/files](https://localazy.com/docs/api/files)
- **Base URL:** `https://api.localazy.com`

#### Tags

- Files
- Keys
- Content

#### Properties

- [Documentation](https://localazy.com/docs/api/files)
- [API Reference](https://localazy.com/docs/api/files)
- [OpenAPI](openapi/localazy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/localazy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/localazy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Localazy Languages API

Retrieves the languages configured on a project, including the source language and per-language translation statistics, via the projects endpoint with the languages parameter.

- **Human URL:** [https://localazy.com/docs/api/projects](https://localazy.com/docs/api/projects)
- **Base URL:** `https://api.localazy.com`

#### Tags

- Languages
- Locales
- i18n

#### Properties

- [Documentation](https://localazy.com/docs/api/projects)
- [API Reference](https://localazy.com/docs/api/projects)
- [OpenAPI](openapi/localazy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/localazy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/localazy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Localazy Projects (Management) API

Lists projects accessible to a token and creates new projects under an organization, returning project identifiers, metadata, type, tone, and feature availability.

- **Human URL:** [https://localazy.com/docs/api/projects](https://localazy.com/docs/api/projects)
- **Base URL:** `https://api.localazy.com`

#### Tags

- Projects
- Management
- Organization

#### Properties

- [Documentation](https://localazy.com/docs/api/projects)
- [API Reference](https://localazy.com/docs/api/projects)
- [OpenAPI](openapi/localazy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/localazy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/localazy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/localazy)
- [LinkedIn](https://www.linkedin.com/company/localazy)
- [Website](https://localazy.com)
- [Documentation](https://localazy.com/docs/api/introduction)
- [Plans](plans/localazy-plans-pricing.yml)
- [Rate Limits](rate-limits/localazy-rate-limits.yml)
- [Fin Ops](finops/localazy-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
