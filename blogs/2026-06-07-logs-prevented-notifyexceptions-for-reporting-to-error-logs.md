---
title: "Logs: Prevented NotifyExceptions for reporting to error logs"
url: "https://codeberg.org/bookstack/bookstack/commit/84a23fb23f8d15935521ad4f3fdc335be6d90744"
date: "2026-06-07"
author: "Dan Brown"
feed_url: "https://codeberg.org/bookstack/bookstack"
---
Logs: Prevented NotifyExceptions for reporting to error logs This is to reduce the amount of content which will be logged, since these messages don't really indicate an actual system error but advise the user of something which went wrong with their request.
