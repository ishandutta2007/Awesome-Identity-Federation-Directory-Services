# Awesome-Identity-Federation-Directory-Services

# Top Identity Federation & Directory Services
**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Identity Providers (IdP), Federation (SAML/OIDC), Directory Services, SSO & Centralized Identity Management*

**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Identity Federation & Directory Services**. These solutions provide centralized authentication, single sign-on (SSO), user directories, federation across applications, and identity lifecycle management for enterprises and cloud environments.

**Examples** include Microsoft Entra ID, Okta, PingFederate, JumpCloud, ForgeRock, OneLogin, AWS IAM Identity Center, CyberArk Identity, Auth0, and Zoho Directory / Atlassian Crowd (the category leaders).

**Open-source emphasis**: Identity federation and directory services have an excellent open-source ecosystem. **Keycloak**, **authentik**, **FreeIPA**, **Samba AD**, **OpenLDAP**, **Kanidm**, **ZITADEL**, **Casdoor**, and related projects offer production-ready alternatives for SSO, federation, and directory services. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Microsoft Entra ID](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)**  
  Cloud-based identity and access management service (formerly Azure Active Directory) providing SSO, MFA, conditional access, and directory services for Microsoft and third-party applications.

- **[Okta](https://www.okta.com/)**  
  Leading independent identity platform offering workforce and customer identity, SSO, lifecycle management, and extensive application integrations.

- **[PingFederate / Ping Identity](https://www.pingidentity.com/)**  
  Enterprise federation and access management platform specializing in SAML, OAuth, OIDC, and hybrid identity scenarios.

- **[JumpCloud](https://jumpcloud.com/)**  
  Cloud directory platform that provides identity, access, and device management as a modern alternative to traditional on-premises Active Directory.

- **[ForgeRock](https://www.forgerock.com/)**  
  Comprehensive identity platform covering access management, identity management, directory services, and identity gateway capabilities.

- **[OneLogin](https://www.onelogin.com/)**  
  Cloud identity and access management solution focused on SSO, MFA, and user lifecycle management (part of One Identity / Quest).

- **[AWS IAM Identity Center](https://aws.amazon.com/iam/identity-center/)**  
  AWS service for managing workforce access to multiple AWS accounts and business applications through single sign-on.

- **[CyberArk Identity](https://www.cyberark.com/)**  
  Identity security platform that combines workforce identity, privileged access, and authentication capabilities.

- **[Auth0](https://auth0.com/)**  
  Developer-friendly identity platform (part of Okta) specializing in customer identity and access management (CIAM) with extensive customization options.

- **[Zoho Directory / Atlassian Crowd](https://www.zoho.com/)**  
  Directory and SSO solutions for workforce identity, application access, and centralized user management within their respective ecosystems.

## Open-Source GitHub Projects
- **[Keycloak](https://github.com/keycloak/keycloak)**  
  Leading open-source Identity and Access Management solution. Supports SSO, identity brokering, user federation, social login, and fine-grained authorization via OpenID Connect, OAuth 2.0, and SAML 2.0.

- **[authentik](https://github.com/goauthentik/authentik)**  
  Modern, flexible open-source identity provider with an intuitive UI. Excellent for SSO, MFA, reverse-proxy authentication, and self-hosted identity needs.

- **[FreeIPA](https://www.freeipa.org/)**  
  Integrated open-source identity management system combining LDAP (389 Directory Server), Kerberos, DNS, certificate authority, and policy management — ideal for Linux/Unix environments.

- **[Samba Active Directory](https://www.samba.org/)**  
  Open-source implementation of Microsoft Active Directory domain services, allowing organizations to run domain controllers on Linux.

- **[OpenLDAP](https://www.openldap.org/)**  
  The classic open-source LDAP directory server. Lightweight, highly configurable, and widely used as a foundational user directory.

- **[Kanidm](https://github.com/kanidm/kanidm)**  
  Modern, secure open-source identity management platform written in Rust. Focuses on simplicity, security, and operational ease.

- **[ZITADEL](https://github.com/zitadel/zitadel)**  
  Open-source identity and access management platform designed for multi-tenancy and cloud-native applications, with strong support for OIDC and modern authentication.

- **[Casdoor](https://github.com/casdoor/casdoor)**  
  UI-first open-source identity and access management platform supporting OAuth 2.0, OIDC, SAML, and multiple authentication methods.

- **[Authelia](https://github.com/authelia/authelia)**  
  Open-source authentication and authorization server that provides SSO and two-factor authentication for applications protected by a reverse proxy.

- **[Ory Stack (Kratos, Hydra, etc.)](https://github.com/ory)**  
  Cloud-native, API-first open-source identity infrastructure. Ory Kratos handles user management and identity, while Hydra provides OAuth2/OIDC.

### Additional Strong Open-Source Options
- Full-featured IdPs: **Keycloak**, **authentik**, **ZITADEL**, **Casdoor**.
- Directory services: **FreeIPA**, **OpenLDAP**, **Samba AD**, **389 Directory Server**.
- Modern / lightweight identity: **Kanidm**, **Ory Kratos**.
- Reverse-proxy SSO / 2FA: **Authelia**.
- Accepting that commercial platforms (Microsoft Entra ID, Okta, Ping Identity, JumpCloud, Auth0, ForgeRock) still lead in enterprise application catalogs, advanced lifecycle management, compliance certifications, global scale, and vendor support.

**Frameworks for building custom systems**:  
Choose **Keycloak** or **authentik** as the central Identity Provider → use **FreeIPA** or **OpenLDAP**/Samba for the underlying directory → protect internal apps with **Authelia** → adopt **Ory** components for cloud-native microservices. Ideal for organizations that want open standards, data sovereignty, and freedom from per-user identity licensing.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Identity systems are a critical security control plane. Incorrect configuration can lead to widespread access issues or security breaches. Open-source solutions offer transparency and control but require operational expertise for high availability, hardening, and upgrades. Commercial platforms often provide broader application integrations, SLAs, and compliance features. This list is not security or identity architecture advice.

---
**Made for identity engineers, IAM architects, DevOps teams, and open-source advocates.**

Let's keep identity federation open, standards-based, and under your control.
