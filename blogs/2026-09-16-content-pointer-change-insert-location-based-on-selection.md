---
title: "Content Pointer: Change insert location based on selection dir"
url: "https://codeberg.org/bookstack/bookstack/commit/47313ddc8fc7c7033a1b3a024efc7cd89e8ba869"
date: "2026-09-16"
author: "Dan Brown"
feed_url: "https://codeberg.org/bookstack/bookstack"
---
Content Pointer: Change insert location based on selection dir Updates the content pointer behaviour so it's inserted before/after the target, instead of just before, depending on selection direction, so it can stay out of the selection range. Positioning is absolute relative to a parent content so visually should be the same result as before. For #6214
