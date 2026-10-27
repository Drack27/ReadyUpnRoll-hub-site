# ReadyUpnRoll hub site

The front door for readyupnroll.com: a home page, a "Host a game" page, and a "Schedule a game" placeholder.
Plain HTML and CSS. No build step, nothing to install.

| File | Page |
|---|---|
| `index.html` | Home: "ask your host for an invite link", Host and Schedule buttons |
| `host.html` | Download button + step-by-step hosting instructions |
| `schedule.html` | Under construction |
| `404.html` | Shown for any address that doesn't exist |
| `style.css` | Look and feel for every page (colors are at the top) |

## Preview locally
Double-click `index.html`. It opens in your browser.

## Before launch
- `host.html` has a download button pointing at `WhiteSpace-Host.exe`, which doesn't exist yet. Search for `DOWNLOAD LINK` and change the address once the host app is built.

## Hosting
Served free by Cloudflare. readyupandroll.com forwards to readyupnroll.com (set up in Cloudflare, not in this code).
