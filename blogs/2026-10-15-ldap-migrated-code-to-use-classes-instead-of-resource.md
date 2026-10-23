---
title: "LDAP: Migrated code to use classes instead of resource"
url: "https://codeberg.org/bookstack/bookstack/commit/b04ad353fb1576f028887b61496cb05ed0fdb7ae"
date: "2026-10-15"
author: "Dan Brown"
feed_url: "https://codeberg.org/bookstack/bookstack"
---
LDAP: Migrated code to use classes instead of resource Added readAndGetEntries, and made those individual methods protected, in the LDAP class since these were always used together, and this limits exposure of internal opaque LDAP values/classes. Closes #6203
