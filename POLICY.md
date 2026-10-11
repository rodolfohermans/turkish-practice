# Project policy

This is a standing commitment for any future change to this repository.
See [`about.html`](about.html) for the point-in-time audit of the
current state.

## No tracking, ever

No analytics, no tracking pixels, no third-party scripts, no cookies.
This includes so-called "privacy-respecting" or cookieless analytics
tools (e.g. Cloudflare Web Analytics, GoatCounter, Plausible) - the
policy is zero collection, not minimized collection. A pull request
adding any of these is rejected regardless of its other merits.

## No ads, no paywalls, no data sale

No ads, no paywalls, no affiliate links, no selling of data (there is
none to sell). The one exception is a voluntary tip jar
([Ko-fi](https://ko-fi.com/rhermans)), which never gates any feature and
is entirely optional.

## Lightweight, dependency-free

- A single HTML file, no build step, no framework, no bundler.
- No external dependencies at runtime: no CDN-hosted fonts, scripts, or
  styles. Everything the app needs ships inside the one file.
- Size budget: under 512 KB uncompressed. The app is currently about
  270 KB, so there's real headroom before this becomes a constraint on
  features.

## Why this is written down

So a contributor (or future me) can check a change against a fixed
standard instead of re-deciding it each time. If a change would violate
any of the above, the answer is no, not "let's discuss a middle ground."
