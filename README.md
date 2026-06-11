# Base64 and URL Encoder Decoder

This tool encodes and decodes text two ways: Base64, in the standard or URL-safe alphabet, and percent-encoding for URLs. It handles Unicode correctly by working on UTF-8 bytes, so accented and non-Latin text round-trips cleanly.

**Live demo:** https://0xelitesystem.github.io/base64-url-encoder-decoder/

## What it does

Pick Base64 or URL percent-encoding, type or paste your text, and encode or decode. For Base64 you can switch to the URL-safe alphabet, which uses dash and underscore and drops padding. A swap button moves the output back into the input for chaining, and a copy button takes the result.

Encoding is not encryption. Base64 and percent-encoding only make text safe to carry where certain characters are restricted; anyone can decode them, so do not treat encoded text as hidden or secure.

## Aesthetic

Maritime signal flags: a bunting strip of nautical flags across the top, a condensed display title, and navy and red controls for encode and decode.

## Privacy

Everything runs in your browser. Nothing you type is sent anywhere, stored, or saved. Closing the tab clears it.

## Use it

Open `index.html` in any modern browser, or host it as a static page. No build step, no dependencies, no network calls.

## License

MIT. Copyright (c) 2026 0xelitesystem.
