---
title: "ZIP Imports: Validated ZIP contents actual size against reported size"
url: "https://codeberg.org/bookstack/bookstack/commit/849ed6f1ec03b9932dda83ecdcb72f43415454f0"
date: "2026-09-29"
author: "Dan Brown"
feed_url: "https://codeberg.org/bookstack/bookstack"
---
ZIP Imports: Validated ZIP contents actual size against reported size When uncompressing file data from a ZIP, limits are now placed on the amount of bytes read, based on the reported file sizes. For files, we then check and error if the read size is over the reported uncompressed file size in the ZIP, instead of relying on the reported ZIP size from metadata. Added test to cover.
