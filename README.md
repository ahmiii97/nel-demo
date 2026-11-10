# Design preview

Client review demo prepared by Design Ally Ltd.

| File | Page |
| --- | --- |
| `index.html` | Firm homepage (Nationwide Employment Lawyers) |
| `damian.html` | Personal homepage (Damian McCarthy, Senior Advocate) |

Both files are static and self-contained: no build step and no dependencies. Fonts load from Google Fonts, and Damian's photo is embedded in `damian.html`. The enquiry and callback flows run in the browser only and send nothing.

## Deploying to the test link

1. Upload `index.html` and `damian.html` to the same folder on the test server.
2. Open `index.html`. Damian's page links back to it.
3. Keep the test link out of search engines: add `<meta name="robots" content="noindex, nofollow">` in each page's `<head>`, or protect the folder with a password.

## Notes for the dev team

- This is a design preview. The production build is a refresh of the client's existing WordPress sites, so every effect here must be reproduced in the WordPress theme with plain CSS and vanilla JavaScript.
- Still placeholder: fee figures, case outcomes, and all regulatory wording (marked `[... to be approved]`). Replace Damian's photo with a high-resolution original before launch.
- Do not change the FCA statement wording without written approval from the client.
