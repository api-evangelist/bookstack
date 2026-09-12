---
title: "LDAP: Fixed handling of invalid group values"
url: "https://codeberg.org/bookstack/bookstack/commit/18f8469a1c72f8cc8497e9372635e6dea5028071"
date: "2026-08-31"
author: "Dan Brown"
feed_url: "https://codeberg.org/bookstack/bookstack"
---
LDAP: Fixed handling of invalid group values Updated LDAP group handling to properly handle empty group values by checking the explode's count property instead of performing a general array count. Also updated logic with DN validation/filtering before LDAP calls are made. For #6088
