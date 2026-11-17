# Awesome-Identity-Federation-Directory-Services

## Top Identity Federation & Directory Services

**Curated List of SaaS Products & Open-Source GitHub Projects**



*Focused on Identity Providers (IdP), Federation (SAML/OIDC), Directory Services, SSO & Centralized Identity Management*



**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Identity Federation & Directory Services**. These solutions provide centralized authentication, single sign-on (SSO), user directories, federation across applications, and identity lifecycle management for enterprises and cloud environments.



**Examples** include Microsoft Entra ID, Okta, PingFederate, JumpCloud, ForgeRock, OneLogin, AWS IAM Identity Center, CyberArk Identity, Auth0, and Zoho Directory / Atlassian Crowd (the category leaders).



**Open-source emphasis**: Identity federation and directory services have an excellent open-source ecosystem. **Keycloak**, **authentik**, **FreeIPA**, **Samba AD**, **OpenLDAP**, **Kanidm**, **ZITADEL**, **Casdoor**, and related projects offer production-ready alternatives for SSO, federation, and directory services. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global Identity and Access Management (IAM) and Identity Federation market is estimated at approximately **$25B–$30B in 2025–2026** and projected to exceed **$60B–$75B by the early 2030s**, growing at a compound annual growth rate (CAGR) of ~11–15%. The sector is **moderately fragmented yet increasingly concentrated** around hyper-scale cloud incumbents (Microsoft Entra ID, AWS IAM) and dedicated identity platforms (Okta/Auth0), while specialized enterprise players, PE-backed consolidations (e.g., Ping Identity + ForgeRock under Thoma Bravo), and a vibrant open-source ecosystem sustain healthy multi-vendor competition.



## SaaS/Hosted Platforms

| Company / Platform | Company Scale (Valuation / Revenue) | Starting Paid Pricing | Free Tier / Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Entra ID](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)** | ~$3.1T Market Cap / ~$245B+ Rev (Parent: Microsoft) | $6.00 / user / month (Entra ID P1); $9.00 / user / month (Entra ID P2) | **Free Forever**: Up to 50,000 directory objects, SSO across unlimited cloud apps, and core MFA. Paid editions have a 30-day free trial (up to 100 licenses). | Cloud-based IAM and directory service (formerly Azure AD) providing SSO, MFA, conditional access, and directory federation for Microsoft and third-party apps. |
| **[AWS IAM Identity Center](https://aws.amazon.com/iam/identity-center/)** | ~$2.2T Market Cap / ~$105B+ AWS Rev (Parent: Amazon) | Included at no additional cost ($0.00) | **Free Forever**: 100% free with no user or application caps for AWS accounts, built-in identity store, and SAML 2.0 federation (underlying services like managed AD incur separate standard AWS fees). | Centralized workforce identity management service for multi-account AWS environments and business cloud applications through single sign-on. |
| **[Okta](https://www.okta.com/)** | ~$13B Market Cap / ~$2.6B+ ARR | $2.00 / user / month (Single Sign-On); $3.00 / user / month (Universal Directory) | **Free Trial Only**: 30-day free trial with full access to Workforce Identity Cloud features; developer tier offers free tenant up to 7,500 monthly active users (MAU). | Leading enterprise identity platform offering workforce and customer identity, SSO, lifecycle management, and thousands of pre-built integrations. |
| **[Zoho Directory](https://www.zoho.com/directory/)** | ~$12.5B Estimated Valuation / ~$1.5B Rev | $2.00 / user / month ($1.70/mo billed annually - Standard Plan) | **Free Forever**: Up to 10 users, unlimited Zoho apps, up to 3 third-party cloud apps with SSO, Cloud RADIUS/LDAP for 10 users, and 7-day audit logs. 15-day free trial for paid plans. | Workforce identity, application access, and centralized directory service tailored for SMBs and enterprise Zoho ecosystems. |
| **[CyberArk Identity](https://www.cyberark.com/)** | ~$12B Market Cap / ~$1.0B+ ARR | ~$6.00 – $7.00 / user / month (Workforce Identity Standard; annual contract with minimum user commitments) | **Free Trial Only**: 14-day to 30-day evaluation sandbox / guided Proof of Concept (PoC) tenant upon sales request. | Identity security and access management platform integrating workforce SSO, adaptive MFA, and privileged access security controls. |
| **[OneLogin](https://www.onelogin.com/)** | ~$5.4B Valuation (Parent: Quest Software / One Identity; ~$500M+ Quest Rev) | $3.00 / user / month (Basic Plan); $6.00 / user / month (Advanced Plan) | **Free Trial Only**: 30-day free trial with full access to cloud directory, SSO, MFA, and user provisioning workflows; no credit card required. | Cloud IAM solution delivering single sign-on, MFA, directory integration, and automated user provisioning (part of One Identity / Quest). |
| **[PingFederate / Ping Identity](https://www.pingidentity.com/)** | ~$5.1B Combined Valuation ($2.8B buyout + $2.3B ForgeRock; Parent: Thoma Bravo) | $3.00 / user / month (PingOne Workforce Essential; enterprise volume minimums apply) | **Free Trial Only**: 30-day free trial with up to 1,000 active user identities and 5 sandbox environments. | Enterprise federation and access management platform specializing in SAML, OAuth, OIDC, and complex hybrid identity architectures. |
| **[JumpCloud](https://jumpcloud.com/)** | ~$2.6B Private Valuation / ~$200M ARR | $3.00 / user / month (Core Identity Plan); $9.00 / user / month (Platform Plan) | **Free Forever**: Up to 10 users and 10 devices with all platform features, plus 30 days of premium 24/7 support. | Cloud directory platform delivering identity, access, and cross-OS device management (Windows, Mac, Linux) as an alternative to on-premises AD. |
| **[ForgeRock](https://www.forgerock.com/)** | ~$2.3B Acquisition Valuation (Combined into Ping Identity / Thoma Bravo) | ~$3.00 – $5.00 / user / month (Enterprise-grade pricing via unified Ping Identity platform; enterprise quote minimums apply) | **Free Trial Only**: 30-day evaluation access / sandbox tenant via unified Ping Identity evaluation platform. | Comprehensive identity platform covering access management, identity governance, directory services, and edge identity gateway capabilities. |
| **[Auth0](https://auth0.com/)** | Acquired for $6.5B (Operating unit of Okta, Inc. - ~$13B Market Cap) | $35.00 / month (B2C Essentials Plan, includes 1,000 MAU; B2B plans start at $130.00 / month) | **Free Forever**: Up to 7,500 monthly active users (MAU), unlimited logins, up to 3 social identity providers, and basic MFA. | Developer-first identity platform specializing in Customer Identity and Access Management (CIAM), flexible token customization, and extensibility. |



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
