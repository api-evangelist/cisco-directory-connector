# Cisco Directory Connector (cisco-directory-connector)

The Cisco Directory Connector is an on-premises Windows service that synchronizes users and groups from a corporate directory (typically Microsoft Active Directory or LDAP) into Cisco Webex Control Hub. It supports full and incremental sync, attribute mapping, dry-run preview, and scheduled jobs. Programmatic management is via the related Webex People, Groups, and Organizations APIs in Control Hub; modern deployments increasingly use SCIM 2.0 provisioning from identity providers (Azure AD, Okta) as an alternative to the on-premises connector.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cisco-directory-connector/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
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

**Human URL:** [https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/cloudCollaboration/wbxt/directoryconnector/wbx_b_directory-connector-guide.html](https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/cloudCollaboration/wbxt/directoryconnector/wbx_b_directory-connector-guide.html)

#### Tags

- Directory Sync, Group Management, User Provisioning

#### Properties

- [Documentation](https://developer.webex.com/docs/api/guides/directory-connector)
- [OpenAPI](https://developer.webex.com/docs/api/v1/openapi.json)
- [Authentication](https://developer.webex.com/docs/integrations)
- [SDKs](https://developer.webex.com/docs/sdks)
- [Rate Limits](https://developer.webex.com/docs/api/basics#rate-limiting)

### Webex Control Hub API
Administrative API for managing Webex organizations, including users, groups, licenses, and directory-sync settings.

**Human URL:** [https://admin.webex.com](https://admin.webex.com)

#### Tags

- Administration, Licenses, Organizations, Users

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/organizations)
- [OpenAPI](https://developer.webex.com/docs/api/v1/openapi.json)
- [Console](https://admin.webex.com)

### Webex SCIM 2.0 Provisioning
SCIM 2.0 endpoints used by identity providers such as Microsoft Entra (Azure AD) and Okta to provision users and groups into Webex as an alternative to the on-premises Directory Connector.

**Human URL:** [https://developer.webex.com/docs/api/v1/scim2-people](https://developer.webex.com/docs/api/v1/scim2-people)

#### Tags

- Identity, Provisioning, SCIM, Standards

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/scim2-people)
- [Specification (RFC 7644)](https://datatracker.ietf.org/doc/html/rfc7644)

## Common Properties

- [Developer Portal](https://developer.webex.com)
- [Admin Console](https://admin.webex.com)
- [Getting Started](https://developer.webex.com/docs/getting-started)
- [Authentication](https://developer.webex.com/docs/integrations)
- [Status](https://status.webex.com)
- [Blog](https://developer.webex.com/blog)
- [Support](https://help.webex.com)
- [Deployment Guide](https://help.webex.com/en-us/article/nivpu1g/Deployment-Guide-for-Cisco-Directory-Connector)
- [Terms of Service](https://www.cisco.com/c/en/us/about/legal/terms-conditions.html)
- [Privacy Policy](https://www.cisco.com/c/en/us/about/legal/privacy-full.html)
- [JSON-LD Context](json-ld/cisco-directory-connector-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
