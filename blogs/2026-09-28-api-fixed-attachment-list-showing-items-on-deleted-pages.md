---
title: "API: Fixed attachment list showing items on deleted pages"
url: "https://codeberg.org/bookstack/bookstack/commit/a09aa8aac65e5a0aee786143c0e184cfdb2f67ea"
date: "2026-09-28"
author: "Dan Brown"
feed_url: "https://codeberg.org/bookstack/bookstack"
---
API: Fixed attachment list showing items on deleted pages List endpoint would show attachments for pages which were in the recycle bin. This adds a deleted_at filter for related pages to the core permission application query. Added test to cover.
