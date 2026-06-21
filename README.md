# Localazy (localazy)

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
