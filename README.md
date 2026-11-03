# Shopify Winter 2026 public frontend replica

This repository contains a static reproduction using the publicly served
Shopify Winter 2026 client, models, textures and timelines. It is not an
official Shopify site and contains no Shopify backend or private source.

GitHub Pages publishes only `static/` through the included Actions workflow.
The project root redirects to `/shopify-winter2026-replica/editions/winter2026/`; the original application
route remains `/editions/winter2026` under the configured project basename.

The original opening, WebGL scenes and reduced-motion reading fallback are
preserved. Sign-in is anonymous. Optional uncached public assets may load from
their observed original CDN URLs. Search, commerce, alternate editions and
other live Shopify services are not reproduced as local backend services.
The new rain-window video prototype is not included.

See `static/package-manifest.json` for the exact base path, file inventory and
checksums, and `static/asset-fallbacks.json` for the observed CDN fallback list.
