# Hugin Cyber

A power tool for web security testing — scanner, repeater, intruder, and AI agent in one Rust binary. No accounts, no telemetry, no cloud.

---

<img src="https://raw.githubusercontent.com/HuginCyber/Hugin/main/assets/og-card.png" alt="Hugin — a power tool for web security testing" width="100%">

## What is Hugin?

Hugin is a local-first security testing tool built in Rust. One binary, no accounts, no telemetry. You see everything and send anything.

### Core capabilities

- **Intercepting proxy** — HTTP/1.1, HTTP/2, HTTP/3, WebSocket, WebTransport. TLS fingerprint passthrough. Live tampering.
- **Active scanner** — 46 checks that send payloads and confirm real bugs. SQLi, XSS, SSTI, SSRF, JWT, OAuth, GraphQL, race conditions, request smuggling, and more.
- **Passive scanner** — 42 checks that analyze traffic without sending anything.
- **Intruder** — fuzzer with payload generators, processors, grep matching, and rate control.
- **Repeater** — capture, modify, and replay any request across HTTP/1.1, HTTP/2, and HTTP/3.
- **AI agent** — 162 MCP tools. Connect Claude, Cursor, or any MCP-compatible LLM to drive the proxy, run scans, and triage findings.
- **Race condition engine** — single-packet and last-byte sync for TOCTOU bugs.
- **OOB detection** — built-in OAST server. DNS, HTTP, HTTPS, SMTP, LDAP, FTP, SMB.
- **Crawler** — static + headless browser crawling, JS analysis, anti-fingerprinting.
- **TLS fingerprint mirage** — JA3/JA4 mimicry, H2 fingerprint, header/font/navigator spoofing.
- **JS bundle engine** — deminify, source map extraction, DOM XSS sink analysis.
- **Mobile analysis** — Android/iOS static analysis, APK decompilation, Frida dynamic instrumentation.
- **Lua extensions** — 14 hook points, permission-gated sandbox.
- **Synaps WASM modules** — community scanner modules, sandboxed via Wasmtime.

### Pricing

- **Community** — free, forever. No account required.
- **Pro** — 7 EUR/month flat. Race engine, BAC audit, smuggling, WASM modules, Lua extensions, collaboration, full MCP surface.
- **Students** — 12 months of Pro free with GitHub Student Developer Pack.

### Privacy

No telemetry. No analytics. No crash reporting. Your traffic never leaves your machine. Accounts are anonymous IDs. Payments via Stripe or Bitcoin/Monero. No KYC.

## Repositories

| Repo | Description |
|------|-------------|
| [Hugin](https://github.com/HuginCyber/Hugin) | Community hub — bug reports, feature requests, discussions, releases |
| [synaps-community](https://github.com/HuginCyber/synaps-community) | WASM vulnerability-detection modules for the Hugin scanner |

## Links

- **Website:** [hugin.nu](https://hugin.nu)
- **Documentation:** [hugin.nu/docs](https://hugin.nu/docs)
- **Download:** [hugin.nu/download](https://hugin.nu/download)
- **X / Twitter:** [@HuginCyber](https://x.com/HuginCyber)
- **LinkedIn:** [Hugin Cyber](https://www.linkedin.com/company/hugin-cyber)

## License

Hugin is proprietary software. The Community tier is free to use. See [hugin.nu/pricing](https://hugin.nu/pricing) for details.
