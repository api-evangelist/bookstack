---
title: "Chapter Conversion: Fixed page cached permissions not being rebuilt"
url: "https://codeberg.org/bookstack/bookstack/commit/89978409cfaae51d5c9405c8186f43405cf27b5b"
date: "2026-09-28"
author: "Dan Brown"
feed_url: "https://codeberg.org/bookstack/bookstack"
---
Chapter Conversion: Fixed page cached permissions not being rebuilt Fixes scenario where page access permissions are changed due to a change of applied permission scope (where a parent book permissions were active, but would no longer be post-promotion), but the page visibility permissions were not being rebuilt. Added test to cover. Fixes #6226
