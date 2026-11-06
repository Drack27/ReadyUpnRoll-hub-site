# ReadyUpnRoll hub site

The front door for readyupnroll.com: a home page, a "Host a game" page, and a "Schedule a game" placeholder.
Plain HTML and CSS. No build step, nothing to install.

| File | Page |
|---|---|
| `index.html` | Home: welcome line, "ask your host for an invite link", Host and Schedule buttons, "What's a WhiteSpace?" card |
| `host.html` | Download button + step-by-step hosting instructions |
| `schedule.html` | Under construction |
| `credits.html` | Credits: people, tools, AIs, and every package Project WhiteSpace uses |
| `404.html` | Shown for any address that doesn't exist |
| `style.css` | Look and feel for every page (colors are at the top) |

## Preview locally
Double-click `index.html`. It opens in your browser.

## Before launch
- `host.html`'s download button asks GitHub for the newest release in `Drack27/WhiteSpace-Host` and links to its .exe (named after its version, e.g. `WhiteSpace-Host-v1.1.87.exe`). If GitHub can't be reached it opens that release's page instead. Search for `DOWNLOAD LINK`.

## Hosting
Served free by Cloudflare. readyupandroll.com forwards to readyupnroll.com (set up in Cloudflare, not in this code).
