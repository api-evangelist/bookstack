---
title: "A11y: Review of #6173, ensure checkboxes are labelled"
url: "https://codeberg.org/bookstack/bookstack/commit/82b9472554f708faa72db2afc9a45fb01394a472"
date: "2026-09-15"
author: "Dan Brown"
feed_url: "https://codeberg.org/bookstack/bookstack"
---
A11y: Review of #6173, ensure checkboxes are labelled This specifically alters the checkbox label implementation to use the existing checkbox label instead of always adding an extra label to the custom checkbox element itself, unless they diverge (like for permission checkboxes).
