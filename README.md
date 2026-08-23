# Audist V4.3 isolated preview

This public repository hosts the V4.3 professional audit-package export release candidate copied from `quaintpelican/energy-audit-app` branch `audist-v4.3-professional-export`, commit `8cea9ea`.

Preview URL: https://audist-energy.github.io/

Isolation: this organization Pages hostname is a different web origin from production at https://quaintpelican.github.io/energy-audit-app/, so its Service Worker, Cache Storage, and IndexedDB data are isolated.

No customer audits, photos, credentials, tokens, or secrets belong in this repository.

## Teardown

1. In this repository, open **Settings → Pages** and click **Unpublish site**.
2. For full removal, open **Settings → General → Danger Zone → Delete this repository** and confirm `Audist-Energy/audist-energy.github.io`.
3. Optionally delete the empty `Audist-Energy` organization after the repository is removed.

Deleting or unpublishing this preview does not alter `quaintpelican/energy-audit-app`, its `main` branch, or production Pages.
