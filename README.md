# BrowserExtensionPermissions

A one-page quick reference to every permission a browser extension can request in **Firefox** and **Chrome**: what it unlocks, whether each browser supports it, whether Firefox warns the user at install, and whether it can be requested later as an optional permission.

**Live page:** https://macromozilla.github.io/BrowserExtensionPermissions/

Data comes from MDN ([permissions](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/permissions), [optional_permissions](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/optional_permissions), [browser-compat-data](https://github.com/mdn/browser-compat-data)) and the [Chrome permission list](https://developer.chrome.com/docs/extensions/reference/permissions-list).

To edit, change the `DATA` array in `index.html`. Plain HTML, no build step.

MIT License.
