# Microsoft Package (microsoft-package)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

A collection of Microsoft package management APIs covering NuGet, Windows Package Manager (WinGet), Microsoft Store, and Azure Artifacts for managing and distributing software packages across Microsoft platforms.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/microsoft-package/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/microsoft-package/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Azure Artifacts
- Microsoft
- NuGet
- Package Management
- WinGet

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-28

## APIs

### NuGet Package API

API for managing .NET packages through NuGet Gallery.

- **Human URL:** [https://www.nuget.org/](https://www.nuget.org/)
- **Base URL:** `https://api.nuget.org/v3/index.json`

#### Tags

- .NET
- Libraries
- NuGet
- Packages

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/nuget/api/overview)
- [Authentication](https://learn.microsoft.com/en-us/nuget/api/authentication)
- [Postman Collection](collections/microsoft-package.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-package.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windows Package Manager (WinGet) API

API for the Windows Package Manager client for discovering and installing applications.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/package-manager/](https://learn.microsoft.com/en-us/windows/package-manager/)
- **Base URL:** `https://winget.azureedge.net/cache`

#### Tags

- Applications
- Package Manager
- Windows
- WinGet

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows/package-manager/)
- [GitHub Organization](https://github.com/microsoft/winget-cli)
- [Postman Collection](collections/microsoft-package.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-package.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft Store API

API for managing app submissions and accessing Microsoft Store catalog.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/uwp/monetize/create-and-manage-submissions-using-windows-store-services](https://learn.microsoft.com/en-us/windows/uwp/monetize/create-and-manage-submissions-using-windows-store-services)
- **Base URL:** `https://manage.devcenter.microsoft.com/v1.0/my/`

#### Tags

- Apps
- Commercial
- Microsoft Store
- Submissions

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows/uwp/monetize/create-and-manage-submissions-using-windows-store-services)
- [Authentication](https://learn.microsoft.com/en-us/windows/uwp/monetize/create-and-manage-submissions-using-windows-store-services)
- [Postman Collection](collections/microsoft-package.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-package.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Artifacts Package API

API for managing packages in Azure Artifacts including NuGet, npm, Maven, and Python packages.

- **Human URL:** [https://azure.microsoft.com/en-us/services/devops/artifacts/](https://azure.microsoft.com/en-us/services/devops/artifacts/)
- **Base URL:** `https://pkgs.dev.azure.com/{organization}/`

#### Tags

- Artifacts
- Azure
- DevOps
- Packages

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/azure/devops/artifacts/)
- [Authentication](https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance)
- [Postman Collection](collections/microsoft-package.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-package.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://developer.microsoft.com/)
- [Terms of Service](https://www.microsoft.com/en-us/legal/terms-of-use)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Support](https://support.microsoft.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
