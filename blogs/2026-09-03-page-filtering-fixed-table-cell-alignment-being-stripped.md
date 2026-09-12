---
title: "Page Filtering: Fixed table cell alignment being stripped"
url: "https://codeberg.org/bookstack/bookstack/commit/13a1883b6c0baad8912d4990f562c6ed9f0276be"
date: "2026-09-03"
author: "Dan Brown"
feed_url: "https://codeberg.org/bookstack/bookstack"
---
Page Filtering: Fixed table cell alignment being stripped Cells could have an 'align' attribute, especially when created via markdown. This updates the allow filtering to retain valid align values on table cells. For #6167
