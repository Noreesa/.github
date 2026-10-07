# Noreesa Brand Assets

Central source of truth for Noreesa visual assets used across repositories and products.

## Structure

- `assets/brand/noreesa-mark.svg` — primary Noreesa symbol for light/neutral surfaces.
- `assets/brand/noreesa-wordmark-dark.svg` — Noreesa wordmark for light backgrounds.
- `assets/brand/noreesa-wordmark-light.svg` — Noreesa wordmark presentation for dark contexts.
- `assets/brand/tokens.json` — canonical color tokens and tagline.
- `assets/products/scan/noreesa-scan-mark.svg` — Noreesa Scan product/app mark.
- `assets/products/scan/noreesa-scan-wordmark.svg` — Noreesa Scan horizontal product lockup.

## Brand tokens

| Token | Value |
| --- | --- |
| Navy | `#102A43` |
| Teal | `#168C82` |
| Bright teal | `#19D3C5` |
| Blue accent | `#2563EB` |
| Ink | `#243B53` |
| Surface | `#F5F8FA` |
| Border | `#D9E2EC` |

**Positioning:** Intelligent Supply Chain Software  
**Tagline:** From demand to delivery.

## Usage

Product repositories should consume or derive their product assets from this library instead of creating unrelated branding. Platform-specific raster icons may live in the product repository because Android, iOS, web, Windows and macOS require generated sizes, but their source artwork belongs here.

Do not copy customer-specific branding (for example VHC assets) into this library.

## Products

### Noreesa Scan

Use `assets/products/scan/noreesa-scan-mark.svg` as the canonical source for launcher icons, favicons, splash marks and scanner-product identity.

Additional product directories can be added for WMS, Forecasting, Connect and future Noreesa modules while retaining the shared Noreesa brand tokens.
