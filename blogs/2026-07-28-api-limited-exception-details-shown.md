---
title: "API: Limited exception details shown"
url: "https://codeberg.org/bookstack/bookstack/commit/2183fc7fc86c0aa183c5eb2068fc691aa97f576d"
date: "2026-07-28"
author: "Dan Brown"
feed_url: "https://codeberg.org/bookstack/bookstack"
---
API: Limited exception details shown Updated exception handler to reduce the amount of detail shown to prevent potentially sensitive details (like internal paths) being shown in the error message. Added an interface for specifically marking exceptions whos messages we may want to show. Thanks to Tanner Marks for reporting.
