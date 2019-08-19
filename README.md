# Proxy to GitHub API

Proxy to GitHub API for [display_errata](https://github.com/w3c/display_errata),
with cache and additional modification to cached results.

## Required feature

- Pass through proxy and cache including query string
- White list on target repository (return error for else)
- Cache reply from GitHub API to DB (CauchDB?) with full URL, check update before accessing to API
- Add converted HTML from GitHub markdown comment using API

- No limit to access to this proxy

## Process flow

