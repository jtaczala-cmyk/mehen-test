# Third-party notices

The game code and content of HEFAU are © 2026 Stop60, all rights reserved (see `LICENSE`).
The game is a single self-contained `index.html`. Only the optional "Online (2 phones)" mode connects to a Supabase Realtime broadcast channel (public anon key, no database tables, no accounts, no personal data; messages contain only the game state and a random room code).
The board, pieces, logo artwork and icons are drawn procedurally (Canvas 2D / inline SVG); sounds are generated with the Web Audio API.

Embedded components (inlined as base64 / minified source inside `index.html`):

| Component | Use | Licence | Copyright |
|---|---|---|---|
| Cinzel (subset, weights 600/800, Latin + Latin Extended) | display font (buttons) | SIL Open Font License 1.1 | © 2020 The Cinzel Project Authors (https://github.com/NDISCOVER/Cinzel) |
| Cinzel Decorative Bold (subset, renamed "Hefau Deco") | heading font | SIL Open Font License 1.1 | © 2012 Natanael Gama (https://github.com/NDISCOVER/Cinzel), Reserved Font Name 'Cinzel' |
| Noto Sans Egyptian Hieroglyphs (subset: 15 glyphs) | logo cartouche ḥ-f-ꜣ-w + decorative ornaments | SIL Open Font License 1.1 | © 2022 The Noto Project Authors (https://github.com/notofonts/egyptian-hieroglyphs) |
| qrcode-generator (minified, unmodified) | in-page QR code for "Share the game" | MIT | © 2009 Kazuhiko Arase |

Full licence texts: `OFL-Cinzel.txt`, `OFL-CinzelDecorative.txt`, `OFL-NotoSansEgyptianHieroglyphs.txt`, `LICENSE-qrcode-generator.txt`.

## QR code

The QR code is generated in the browser (no external QR service, no tracking) and encodes only the game's own address.
QR Code is a registered trademark of DENSO WAVE INCORPORATED.
