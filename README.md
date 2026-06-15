# Microsoft Package (microsoft-package)

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
