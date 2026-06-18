# First Rung

A single-page thinking artifact. One file, no dependencies, no build step.

## What it is
`index.html` is fully self-contained (HTML, CSS, JS, and Google Fonts via CDN). It runs by opening the file in any browser. Switching the example (Fire department / Support org / Finance ops) is handled in vanilla JS.

## Deploy to Vercel
From this folder:

```
vercel
```

Accept the defaults. Vercel detects a static site and serves `index.html` at the root. Use `vercel --prod` to promote to the production URL.

No framework, no `package.json`, no config needed. If you prefer, you can also drag this folder onto vercel.com/new.

## Editing the content
All copy lives in the `EX` object near the bottom of `index.html`, one entry per example. Each has: `prompt`, `removes`, `stays`, `note`, `rungs` (bottom-to-top), and `closeex`. The shared close line and the thesis are in the HTML body above the script.

## Before sending
- The three accounts are illustrative; the footer says so.
- The only hard numbers are Squid's published figures (52% for TicketMind, 80% for financial ops, and DealFlow by name). Confirm those read the way you want before the link goes out.
