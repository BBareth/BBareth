### BBareth

Software dev apprentice at Sunrise GmbH. I build small tools I use myself,
mostly in Rust and TypeScript: no accounts, no subscriptions, and docs that say
what actually happens.

#### Self-hosted

**[steward](https://github.com/BBareth/steward)**: a Discord admin bot that AI
coding agents drive over MCP. Describe a whole server in one YAML blueprint,
review the dry-run plan, apply it. Works with Claude Code and Codex.
`TypeScript` `MCP` `discord.js`

**[herald](https://github.com/BBareth/herald)**: a Discord bot that announces
new YouTube uploads. A dashboard per server, WebSub push with an RSS poller
behind it, so posts keep coming when Google's hub drops out.
`TypeScript` `React` `Docker`

**[media_manager](https://github.com/BBareth/media_manager)**: download,
transcode and compress media in the browser. Give it a size in MB and it gets
the file under it. Old files clean themselves up.
`Rust` `React` `ffmpeg` `yt-dlp`

**[kestrel](https://github.com/BBareth/kestrel)**: a paper-first trading desk
for Binance BTCUSDT perpetual futures. A risk engine sizes and caps every trade
before an AI layer may veto it, and every decision lands in an audit trail.
Paper trading until you say otherwise.
`Python` `FastAPI` `React` `PostgreSQL`

#### On your own machine

**[vitals](https://github.com/BBareth/vitals)**: a hotkey hardware-stats panel
for Windows. CPU, NVIDIA GPU, memory and NVMe temperatures, always on top, from
one 1 MB exe with no kernel driver. NVML runs in a supervised child process, so
a driver update can't take it down.
`Rust` `Win32` `Direct2D`

**[neo](https://github.com/BBareth/neo)**: an AI chat sidebar for Firefox on
your own API key: OpenAI-compatible, DeepSeek or Claude. Attach open tabs and
screenshots to a question. No server in between.
`JavaScript` `Firefox` `WebExtensions`

**[songcleaner](https://github.com/BBareth/songcleaner)**: a Geode mod for
Geometry Dash that deletes a level's custom song when you delete the level, so
unused mp3s stop piling up.
`C++` `Geode`

Everything here is MIT licensed. steward, herald and media_manager ship as
images on `ghcr.io`, kestrel builds with one `docker compose`, and vitals ships
as a single exe on its releases page. Issues and ideas are welcome.
