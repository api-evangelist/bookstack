---
title: "Attachments: Moved perm checks before validation"
url: "https://codeberg.org/bookstack/bookstack/commit/b7325fdf0efde6f863beed67cde488641a05ef83"
date: "2026-06-07"
author: "Dan Brown"
feed_url: "https://codeberg.org/bookstack/bookstack"
---
Attachments: Moved perm checks before validation Avoids providing responses with potential sensitive attachment info before permission checks. Added tests to cover. Thanks to Rafael Castilho for reporting.
