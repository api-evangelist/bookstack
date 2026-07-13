---
title: "Content filtering: Added srcset protocol filter"
url: "https://codeberg.org/bookstack/bookstack/commit/59bbf504cf1c6205c56c9c0d6c9e3c6154904ecc"
date: "2026-06-30"
author: "Dan Brown"
feed_url: "https://codeberg.org/bookstack/bookstack"
---
Content filtering: Added srcset protocol filter Upstream libraries used did not specifically treat values in srcset as URIs like other attributes, so this adds a simple filter for possible bad values. Updated tests to cover. Thanks for Gurmandeep Deol for reporting.
