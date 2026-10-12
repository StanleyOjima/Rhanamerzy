# Rhanamerzy Concepts · website

The website of Rhanamerzy Concepts Limited, [rhanamerzy.com](https://rhanamerzy.com/), in English and Simplified Chinese.

Plain HTML, CSS and JavaScript. There is no build step and no server code: Vercel serves these files as they are. The site sets no cookies and runs no analytics or advertising.

## What is here

| Path | What it is |
| --- | --- |
| `index.html` | The homepage |
| `gallery.html` | From the work: photographs by location |
| `privacy.html` | The privacy notice |
| `zh/` | The same three pages in Simplified Chinese |
| `gallery/` | The photographs, two or three sizes of each (WebP) |
| `images/` | The Leadership portrait, the clients' and partners' logos, the Mercy Alexander Foundation logo |
| `favicon.ico`, `favicon-32.png`, `apple-touch-icon.png` | The icons |
| `rhanamerzy-share.jpg`, `rhanamerzy-share-zh.jpg` | The images shown when a page is shared |

Each page links to its counterpart in the other language, and remembers the visitor's choice on their device.

## Updating the site

Replace the files in the repository with these (same names, same folders) and commit to `main`; Vercel publishes `main`.

- `og-cover.jpg` and `rhanamerzy-og-cover.jpg` (from the first version) are no longer used and can be deleted.
- GitHub's "Add files via upload" takes up to 100 files at a time. Add the photographs (`gallery/`) before the pages that show them, so the live site never points at a photograph that is not there yet. GitHub Desktop pushes everything at once.

## Still to come

- The contact form: sending from it is coming soon, and the form says so. Visitors reach the firm by the email address and numbers on the page.
- The NewCo Solutions website: its links say "Coming soon" until the address is ready.
