# Privacy Policy — Ripper Search

**Last updated:** September 2026

Ripper Search ("the Extension") is a browser extension that helps you search the Ripper.Store forum while browsing asset stores.

## Summary

- We do **not** operate our own servers or collect your personal data.
- All data stays **on your device** unless you interact with third-party sites you already use (forum.ripper.store, Booth, etc.).

## Data stored locally

The Extension uses `chrome.storage.local` to save:

- Settings (language, tags, preferences)
- Search history
- Watched threads and LF requests
- Download queue metadata

This data never leaves your browser except when you export it manually via Settings.

## Third-party services

### forum.ripper.store

When you are logged in, the Extension uses your existing browser session (cookies) to:

- Search the forum API
- Post LF requests and replies (bump)
- Upvote posts
- Fetch topic content for download links

We do not receive or store your forum password. Authentication is handled entirely by the forum in your browser.

### Supported stores (Booth, Gumroad, etc.)

The Extension reads the current page URL and product metadata to build search queries. It does not send this data to our servers — only to the forum API when you search.

## Permissions explained

| Permission | Purpose |
|------------|---------|
| `storage` | Save settings, history, and watched threads locally |
| `cookies` | Use your forum login session for API calls |
| `notifications` | Alert you when a watched thread gets a new download |
| `downloads` | Start file downloads from extracted links |
| Host permissions (stores + forum) | Inject the panel on store pages and call forum APIs |

## What we do not do

- No analytics or tracking SDKs
- No sale or sharing of user data
- No account system operated by the Extension author

## Children's privacy

The Extension is not directed at children under 13.

## Changes

We may update this policy. The latest version is always in the GitHub repository.

## Contact

Open an issue at the project GitHub repository.
