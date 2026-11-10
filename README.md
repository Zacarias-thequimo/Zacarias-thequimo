# Zacarias Thequimo

Software developer in Mozambique, and founder of TechMz Solutions.

[Email](mailto:zacariasrichard85@gmail.com)

## What I work on

I build developer tools that run in the terminal or on the desktop and can be installed the
same day: a single binary, a `.deb`, no ten-step setup first.

Web products with a database, authentication, queues, local payment and WhatsApp delivery.
Some of that ships through TechMz Solutions, the agency I founded, which also does IT
consulting, cloud work and application security for local clients.

Application security work: reconnaissance, traffic interception, and reviews of exposed
surfaces. Authorised testing and CTF.

Native Linux and ARM clients where Electron is not worth the weight, packaged for amd64
and arm64.

I read a system's traffic before I write anything against it. Writing a proxy to see that
traffic and a toolkit to map an exposed surface teaches more about how a system works than
its documentation does. I also build for the constraints here: low bandwidth, little RAM, a
phone as the only computer, and mobile money as the only payment rail.

## Selected work

### Tools

[**BurpHub**](https://github.com/Zacarias-thequimo/burphub) (Go, Wails, SQLite)
HTTP and HTTPS proxy for the laptop, with a terminal UI and a native Ubuntu app on WebKitGTK
and no bundled Chromium. Interception with live editing, repeater, SQLite history, API test
collections, a decoder, a passive scanner, and its own CA with per-browser install notes.
Ships as a `.deb`.

[**zacs**](https://github.com/Zacarias-thequimo/zacs) (Rust)
Drop-in npm replacement: npm-compatible, workspace-ready, single binary.

[**FlowTools**](https://github.com/Zacarias-thequimo/flowtools) (Rust, Kotlin, Axum, Jetpack Compose)
Controls a PC from the phone without taking over the screen. A session server, a PC client
and an Android app share a state contract mirrored in Rust and Kotlin. Every tag produces
signed releases from CI.

[**Wireframe Local**](https://github.com/Zacarias-thequimo/wireframe-local) (TypeScript)
Wireframe editor that runs in the browser with no backend, account or database. Exports PNG,
SVG, JSON, plain HTML/CSS and HTML with Tailwind.

[**james-recon**](https://github.com/Zacarias-thequimo/james-recon) (Python, httpx, asyncio)
Thirteen async modules for reconnaissance and exploitation: enumeration, port scan, OSINT,
TLS analysis, SQL injection detection by boolean blind and by response time, and a JSON or
Markdown report. MIT, for CTF and authorised tests.

### Products

**TicketOn** (TypeScript, Next.js, Fastify, Prisma, BullMQ, private)
Ticketing for events in Mozambique: local payment, delivery by WhatsApp or email, entry
validated by QR code or a six-digit code.

**ScrapSend** (Python, Next.js, Evolution API, private)
Finds businesses without a website on Google Maps, qualifies them, and messages them on
WhatsApp with a demo site ready to send. Runs in production and resumes from saved state
when a batch is interrupted.

[**YT-Down API**](https://github.com/Zacarias-thequimo/yt-down-api) (Python, FastAPI, SQLAlchemy)
Video, audio and playlist downloads behind JWT auth, with several API keys per account.

**Dispara SMS** (Kotlin, Jetpack Compose, private)
Bulk SMS from the phone itself, on the carrier plan, built for low-RAM handsets on slow
networks.

### Extensions and integrations

[**skills-openclaw**](https://github.com/Zacarias-thequimo/skills-openclaw) (Python)
OpenClaw skills for DuckDuckGo search and IMAP/SMTP email, with no API keys.

[**nanomuse-slim**](https://github.com/Zacarias-thequimo/nanomuse-slim) (Swift, Tauri)
Slimmed packaging for a desktop agent, including a low-memory profile for 2 CPU / 4 GB
machines.

## How I work

I start by intercepting: real headers and responses, not what the documentation promises.
Then I take the format apart, whether that is an unnamed blob, a protocol with no spec, or a
file nobody wrote down. The tool comes after, in whichever language fits the problem: Go
for network code, Rust for binaries, Python for automation, TypeScript for product. I ship
it as something that installs in one step, with the docs in Portuguese where the audience
is local.

## Stack

Go, Rust, TypeScript, Python, Kotlin, Swift, GDScript
Postgres, Redis, Prisma, Cloudflare R2, Docker, Linux, GitHub Actions
Astro, Next.js, Svelte, GSAP, Tailwind
Traffic interception, reconnaissance and enumeration, headers/TLS/CORS, injection detection

## Contact

- Email: [zacariasrichard85@gmail.com](mailto:zacariasrichard85@gmail.com)
- GitHub: [Zacarias-thequimo](https://github.com/Zacarias-thequimo)
