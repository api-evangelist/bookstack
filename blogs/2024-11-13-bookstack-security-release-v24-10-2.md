---
title: "BookStack Security Release v24.10.2"
url: "https://www.bookstackapp.com/blog/bookstack-release-v24-10-2/"
date: "2024-11-13"
feed_url: "https://www.bookstackapp.com/blog/index.xml"
---
BookStack v24.10.2 has been released. This is a security release to address a vulnerability in our dependencies where specifically formatted requests could be used to manipulate application configuration in environments where a certain PHP option (register_argc_argv) is enabled. This is not an option that’s typically enabled in production web-serving environments, but it’s advised to update where uncertain.
