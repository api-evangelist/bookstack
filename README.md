# BookStack

BookStack is a free, open-source, self-hosted wiki and documentation platform built with PHP and Laravel. It organizes content into a hierarchical structure of shelves, books, chapters, and pages, and provides a full REST API for programmatic access to all content and configuration.

## API

The BookStack REST API supports managing books, chapters, pages, shelves, attachments, image galleries, comments, roles, users, audit logs, imports, recycle bin, search, tags, content permissions, and system information. Authentication is via API tokens scoped to user roles.

- API Documentation (demo instance): https://demo.bookstackapp.com/api/docs
- Default rate limit: 180 requests per minute per user (configurable via `API_REQUESTS_PER_MIN`)

## Resources

- Website: https://www.bookstackapp.com/
- Documentation: https://www.bookstackapp.com/docs/
- Source Code: https://codeberg.org/bookstack/bookstack
- Blog / Changelog: https://www.bookstackapp.com/blog
- Community: https://community.bookstackapp.com
- Mastodon: https://fosstodon.org/@bookstack

## License

BookStack is released under the [MIT License](https://codeberg.org/bookstack/bookstack/src/branch/development/LICENSE).

## Profile

This repository contains the APIs.json 0.19 profile for BookStack, maintained by [API Evangelist](https://apievangelist.com).
