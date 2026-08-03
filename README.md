# Azure Files (azure-file-storage)

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

Azure Files is a fully managed cloud file share service from Microsoft Azure that provides hosted SMB and NFS file shares accessible from cloud and on-premises clients using standard file system protocols and the FileREST HTTPS API. It supports identity-based authentication via Active Directory and Microsoft Entra ID, snapshots, soft delete, and Azure File Sync for hybrid scenarios. The FileREST data-plane API uses shared key, shared access signatures (SAS), or Microsoft Entra ID OAuth 2.0 bearer tokens for authentication, while the control plane uses Azure Resource Manager.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/azure-file-storage/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/azure-file-storage/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Storage
- File Storage
- File Shares
- SMB
- NFS
- Cloud
- Azure

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Azure Files FileREST API

Data-plane HTTPS REST API for operations on file shares, directories, and files in Azure Files, including create, copy, lease, list, range, and snapshot operations. Authentication uses shared key, shared access signatures (SAS), or Microsoft Entra ID OAuth 2.0 bearer tokens.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/storageservices/file-service-rest-api](https://learn.microsoft.com/en-us/rest/api/storageservices/file-service-rest-api)
- **Base URL:** `https://{account-name}.file.core.windows.net`

#### Tags

- Azure Files
- File Shares
- Data Plane
- Storage
- Azure

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/storageservices/file-service-rest-api)
- [Operations on  Shares](https://learn.microsoft.com/en-us/rest/api/storageservices/operations-on-shares--file-service-)
- [Operations on  Files](https://learn.microsoft.com/en-us/rest/api/storageservices/operations-on-files)
- [Postman Collection](collections/azure-file-storage.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-file-storage.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Storage Resource Provider API (File Services / Shares)

Azure Resource Manager REST API for managing storage accounts, FileService settings, and FileShare resources at the control-plane level. Authentication uses Microsoft Entra ID OAuth 2.0 bearer tokens.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/storagerp/file-shares](https://learn.microsoft.com/en-us/rest/api/storagerp/file-shares)
- **Base URL:** `https://management.azure.com`

#### Tags

- Storage
- Control Plane
- Resource Manager
- Azure

#### Properties

- [File  Services](https://learn.microsoft.com/en-us/rest/api/storagerp/file-services)
- [File  Shares](https://learn.microsoft.com/en-us/rest/api/storagerp/file-shares)
- [Postman Collection](collections/azure-file-storage.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-file-storage.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://azure.microsoft.com/en-us/products/storage/files/)
- [Documentation](https://learn.microsoft.com/en-us/azure/storage/files/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/storage/files/)
- [Sign Up](https://azure.microsoft.com/en-us/free/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
