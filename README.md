# DevTools — Free Online Developer Tools

A collection of **15+ fast, browser-based developer tools**. Everything runs
**100% client-side** — whatever you paste (JSON, JWTs, text, values to hash)
never leaves your browser and is never sent to a server. No ads, no sign-up,
no rate limits.

🔗 **Live site: https://devtools.fxcalc.site**

## Why

Most dev tasks involve small, repetitive transformations: pretty-printing a
JSON response, decoding a JWT to see why a request is rejected, converting a
Unix timestamp, hashing a string. This site collects those utilities in one
place — no package to install, no context switch, nothing uploaded anywhere.

## Tools

| Tool                                                         | What it does                                            |
| ------------------------------------------------------------ | ------------------------------------------------------- |
| [JSON Formatter / Validator](https://devtools.fxcalc.site/json-formatter) | Format, beautify and validate JSON; catch syntax errors |
| [Base64 Encode / Decode](https://devtools.fxcalc.site/base64-encode-decode) | Encode/decode Base64, incl. UTF-8 and URL-safe          |
| [URL Encode / Decode](https://devtools.fxcalc.site/url-encode-decode) | Percent-encode and decode URLs                          |
| [JWT Decoder](https://devtools.fxcalc.site/jwt-decoder)      | Inspect JWT header and payload locally                  |
| [UUID Generator (v4)](https://devtools.fxcalc.site/uuid-generator) | Generate single or batch v4 UUIDs                       |
| [Hash Generator](https://devtools.fxcalc.site/hash-generator) | SHA-1 / SHA-256 / SHA-512 hashes                        |
| [Unix Timestamp Converter](https://devtools.fxcalc.site/timestamp-converter) | Timestamps ↔ human-readable dates                       |
| [Cron Expression Parser](https://devtools.fxcalc.site/cron-parser) | Read a cron expression in plain English                 |
| [Regex Tester](https://devtools.fxcalc.site/regex-tester)    | Test regular expressions against sample input live      |
| [Color Converter](https://devtools.fxcalc.site/color-converter) | Convert between HEX / RGB / HSL                         |
| [Case Converter](https://devtools.fxcalc.site/case-converter) | camelCase / snake_case / kebab-case / etc.              |
| [Number Base Converter](https://devtools.fxcalc.site/number-base-converter) | Binary / octal / decimal / hex                          |
| [QR Code Generator](https://devtools.fxcalc.site/qr-code-generator) | Generate QR codes from text or URLs                     |
| [Lorem Ipsum Generator](https://devtools.fxcalc.site/lorem-ipsum-generator) | Placeholder text on demand                              |
| [Text Diff Checker](https://devtools.fxcalc.site/text-diff-checker) | Compare two blocks of text                              |

## Privacy

There is no backend that processes your input. All logic executes in your
browser, which makes these tools a safer default for decoding tokens or
hashing values you would rather not paste into an unknown remote service.

## Tech

Next.js (static export) · React · TypeScript · Tailwind CSS. Statically
rendered for speed and served over a CDN.
