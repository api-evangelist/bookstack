---
title: "BookStack Security Release v26.05.3"
url: "https://www.bookstackapp.com/blog/bookstack-release-v26-05-3/"
date: "2026-07-29"
feed_url: "https://www.bookstackapp.com/blog/index.xml"
---
BookStack v26.05.3 has been released. This is a security release to address a range of vulnerabilities: External Authentication Use (OIDC/SAML2/LDAP) could potentially mismatch external authentication system users to BookStack users upon login, where unique IDs are very similar (same ID text but different casing, or accented characters). The login form could be abused to use timing to gain information about if a user exists in the system.
