# Azure Files (azure-file-storage)

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
