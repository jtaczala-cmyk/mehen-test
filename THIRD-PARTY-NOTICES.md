# Third-party notices

The game code and content of HEFAU are © 2026 Stop60, all rights reserved (see `LICENSE`).
The game is a single self-contained `index.html`; no requests to external services are made at runtime.
The board, pieces, logo artwork and icons are drawn procedurally (Canvas 2D / inline SVG); sounds are generated with the Web Audio API.

Embedded components (inlined as base64 / minified source inside `index.html`):

| Component | Use | Licence | Copyright |
|---|---|---|---|
| Cinzel (subset, weights 600/800) | display font | SIL Open Font License 1.1 | © 2020 The Cinzel Project Authors (https://github.com/NDISCOVER/Cinzel) |
| Noto Sans Egyptian Hieroglyphs (subset: 7 glyphs for the logo cartouche) | hieroglyphs ḥ-f-ꜣ-w + snake determinative | SIL Open Font License 1.1 | © 2022 The Noto Project Authors (https://github.com/notofonts/egyptian-hieroglyphs) |
| qrcode-generator (minified, unmodified) | in-page QR code for "Share the game" | MIT | © 2009 Kazuhiko Arase |

Full licence texts: `OFL-Cinzel.txt`, `OFL-NotoSansEgyptianHieroglyphs.txt`, `LICENSE-qrcode-generator.txt`.

## QR code

The QR code is generated in the browser (no external QR service, no tracking) and encodes only the game's own address.
QR Code is a registered trademark of DENSO WAVE INCORPORATED.
