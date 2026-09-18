# React v18.2.0 Release Reference

> Pinned dependency for the dashboard rewrite.

## Reference

- **Release name:** 18.2.0 (June 14, 2022)
- **Tag:** `v18.2.0`
- **Published:** 2022-06-14 (2022-06-14T19:54:21Z UTC)
- **Release page:** https://github.com/react/react/releases/tag/v18.2.0
- **Repository:** https://github.com/facebook/react

## Highlights (from the release notes)

### React DOM

- Provide a component stack as a second argument to `onRecoverableError` (#24591)
- Fix hydrating into `document` causing a blank page on mismatch (#24523)
- Fix false positive hydration errors with Suspense (#24480, #24532)
- Fix ignored `setState` in Safari when adding an `iframe` (#24459)

### React DOM Server

- Pass information about server errors to the client (#24551, #24591)
- Allow providing a reason when aborting the HTML stream (#24680)
- Eliminate extraneous text separators in the HTML where possible (#24630)
- Disallow complex children inside `<title>` elements to match browser constraints (#24679)
- Fix buffering in some worker environments by explicitly setting `highWaterMark` to `0` (#24641)

### Server Components (Experimental)

- Add support for `useId()` inside Server Components (#24172)
