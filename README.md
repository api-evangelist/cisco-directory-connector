# Cisco Directory Connector (cisco-directory-connector)

The Cisco Directory Connector is an on-premises Windows service that synchronizes users and groups from a corporate directory (typically Microsoft Active Directory or LDAP) into Cisco Webex Control Hub. It supports full and incremental sync, attribute mapping, dry-run preview, and scheduled jobs. Programmatic management is via the related Webex People, Groups, and Organizations APIs in Control Hub; modern deployments increasingly use SCIM 2.0 provisioning from identity providers (Azure AD, Okta) as an alternative to the on-premises connector.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cisco-directory-connector/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cisco-directory-connector/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Active Directory
- Directory
- Enterprise
- Identity Management
- LDAP
- Provisioning
- SCIM
- Synchronization

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-23

## APIs

### Cisco Directory Connector Sync API

Manage and observe directory synchronization between on-premises directory services and Cisco Webex Control Hub, including sync scheduling, status, and error reporting.

- **Human URL:** [https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/cloudCollaboration/wbxt/directoryconnector/wbx_b_directory-connector-guide.html](https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/cloudCollaboration/wbxt/directoryconnector/wbx_b_directory-connector-guide.html)

#### Tags

- Directory Sync
- Group Management
- User Provisioning

#### Properties

- [Documentation](https://developer.webex.com/docs/api/guides/directory-connector)
- [OpenAPI](https://developer.webex.com/docs/api/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://developer.webex.com/docs/integrations)
- [S D Ks](https://developer.webex.com/docs/sdks)
- [Rate Limits](https://developer.webex.com/docs/api/basics#rate-limiting)
- [Postman Collection](collections/cisco-directory-connector.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-directory-connector.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Control Hub API

Administrative API for managing Webex organizations, including users, groups, licenses, and directory-sync settings.

- **Human URL:** [https://admin.webex.com](https://admin.webex.com)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Administration
- Licenses
- Organizations
- Users

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/organizations)
- [OpenAPI](https://developer.webex.com/docs/api/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Console](https://admin.webex.com)
- [Postman Collection](collections/cisco-directory-connector.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-directory-connector.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex SCIM 2.0 Provisioning

SCIM 2.0 endpoints used by identity providers such as Microsoft Entra (Azure AD) and Okta to provision users and groups into Webex as an alternative to the on-premises Directory Connector.

- **Human URL:** [https://developer.webex.com/docs/api/v1/scim2-people](https://developer.webex.com/docs/api/v1/scim2-people)
- **Base URL:** `https://webexapis.com/identity/scim`

#### Tags

- Identity
- Provisioning
- SCIM
- Standards

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/scim2-people)
- [Specification](https://datatracker.ietf.org/doc/html/rfc7644)
- [Postman Collection](collections/cisco-directory-connector.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-directory-connector.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://developer.webex.com)
- [Admin  Console](https://admin.webex.com)
- [Getting Started](https://developer.webex.com/docs/getting-started)
- [Authentication](https://developer.webex.com/docs/integrations)
- [Status Page](https://status.webex.com)
- [Blog](https://developer.webex.com/blog)
- [Support](https://help.webex.com)
- [Downloads](https://help.webex.com/en-us/article/nivpu1g/Deployment-Guide-for-Cisco-Directory-Connector)
- [Terms of Service](https://www.cisco.com/c/en/us/about/legal/terms-conditions.html)
- [Privacy Policy](https://www.cisco.com/c/en/us/about/legal/privacy-full.html)
- [JSON-LD](json-ld/cisco-directory-connector-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
