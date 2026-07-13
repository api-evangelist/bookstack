---
title: "Attachments: Added more extensive URL filtering"
url: "https://codeberg.org/bookstack/bookstack/commit/01dc1e71c5574ba36dabb55d9b2a3e4a234df2cc"
date: "2026-07-01"
author: "Dan Brown"
feed_url: "https://codeberg.org/bookstack/bookstack"
---
Attachments: Added more extensive URL filtering Added a central URLFilter class to check & clean URLs used for attachments, which is also used for validation, and by the purifier to standardise protocols (and to make protocol config easier in future). Thanks to mfk25 for reporting.
