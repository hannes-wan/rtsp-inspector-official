# RTSP Inspector

[![Community Edition: Free](https://img.shields.io/badge/Community_Edition-Free-16a34a?style=for-the-badge)](https://hannes-software.com/rtsp-inspector/download/)
[![Windows](https://img.shields.io/badge/Windows-Desktop-2563eb?style=flat-square&logo=windows)](https://hannes-software.com/rtsp-inspector/download/) [![Linux](https://img.shields.io/badge/Linux-Desktop-f59e0b?style=flat-square&logo=linux)](https://hannes-software.com/rtsp-inspector/download/) [![Local first](https://img.shields.io/badge/Workflow-Local--first-7c3aed?style=flat-square)](https://hannes-software.com/rtsp-inspector/)

> Diagnose an RTSP camera stream by connecting control-plane, RTP, RTCP, timing, and codec evidence in one local case.

Free Community Edition RTSP stream tester and diagnostic tool for RTSP/RTP/RTCP/H.264 evidence, IP-camera troubleshooting, and JSON preview.

Turn camera black screens, VLC-vs-VMS mismatches, ONVIF handoff failures, blocked UDP media, RTP loss, and H.264/H.265 codec problems into a report a customer, vendor, or support team can act on.

**RTSP Inspector Community Edition is free to download and use.** Single-stream live RTSP-over-TCP diagnosis and JSON report preview.

[Download Community Edition](https://hannes-software.com/rtsp-inspector/download/) · [Product guide](https://hannes-software.com/rtsp-inspector/) · [Help](https://hannes-software.com/rtsp-inspector/help/) · [Report a bug](https://github.com/hannes-wan/rtsp-inspector-official/issues/new?template=bug_report.yml)

## Download RTSP Inspector 1.0.4

| Platform | Package | Use it when |
| --- | --- | --- |
| Linux x64 (APPIMAGE) | [rtsp-inspector-1.0.4-linux-x64.AppImage](https://github.com/hannes-wan/rtsp-inspector-official/releases/download/v1.0.4/rtsp-inspector-1.0.4-linux-x64.AppImage) | Portable Linux desktop package |
| Linux x64 (DEB) | [rtsp-inspector-1.0.4-linux-x64.deb](https://github.com/hannes-wan/rtsp-inspector-official/releases/download/v1.0.4/rtsp-inspector-1.0.4-linux-x64.deb) | Debian, Ubuntu, Mint, and compatible systems |
| Linux x64 (RPM) | [rtsp-inspector-1.0.4-linux-x64.rpm](https://github.com/hannes-wan/rtsp-inspector-official/releases/download/v1.0.4/rtsp-inspector-1.0.4-linux-x64.rpm) | Fedora, RHEL, openSUSE, and compatible systems |
| Windows x64 | [rtsp-inspector-1.0.4-windows-x64-setup.exe](https://github.com/hannes-wan/rtsp-inspector-official/releases/download/v1.0.4/rtsp-inspector-1.0.4-windows-x64-setup.exe) | Guided Windows installer |

Checksums, installation notes, and the complete platform matrix live on the [official download page](https://hannes-software.com/rtsp-inspector/download/).

## System requirements

- **Windows:** Windows 10 or Windows 11 on x64.
- **Linux:** a mainstream x64 distribution with glibc 2.35 or newer, such as Ubuntu 22.04+, Debian 12+, Fedora, or openSUSE (AppImage, DEB, and RPM packages).
- **Disk space:** a few hundred megabytes free for the application and its bundled resources.

## Why RTSP Inspector exists

Built for CCTV installers, security integrators, IP camera vendors, NVR/VMS support teams, and field engineers who need a repeatable answer they can send to a customer, vendor, or internal QA team.

> **Edition boundary:** The technical sections below describe the complete product surface and can include optional licensed workflows. The exact free Community Edition scope is listed separately below.

### Find the exact camera-stream failure boundary before the blame loop starts.

RTSP Inspector is the focused local desktop workbench for teams that need to explain CCTV and IP camera failures across RTSP/RTP/RTCP/SDP, H.264/H.265 structure, transport choice, and reportable evidence.

### RTSP request and response timeline

Inspect OPTIONS, DESCRIBE, SETUP, PLAY, status codes, headers, CSeq behavior, and redacted authentication evidence.

### SDP and control URL resolution

See tracks, codecs, payload types, clock rates, control paths, and missing or inconsistent media declarations.

### RTP and RTCP signal analysis

Surface loss, duplicate packets, reordering, jitter, SSRC changes, malformed packets, and sender-report timing.

### Control plane answers first

- RTSP OPTIONS, DESCRIBE, SETUP, and PLAY stay in one timeline with status codes, CSeq behavior, headers, and redacted authentication evidence.
- SDP track inspection exposes codecs, payload types, clock rates, control URLs, and missing media declarations before you blame the decoder.
- Bad paths, 401 loops, unsupported transport replies, ONVIF handoff mistakes, and server-side failures become visible protocol events instead of vague black-screen symptoms.

### Media flow gets measured

- RTP continuity, packet loss, duplicates, reordering, jitter, malformed packets, and SSRC changes are surfaced beside the RTSP session that produced them.
- RTCP sender reports, packet counts, timing evidence, and CNAME context help separate network delivery problems from camera timing problems.
- H264/H265 structural inspection helps prove whether the stream is missing parameter sets, fragmenting badly, or advertising a codec it does not deliver cleanly.

### Built for cases, not screenshots

- .risession save/open, Case Library, and replay workflows keep the normalized evidence reusable when a customer, vendor, or field team needs the same diagnosis later.
- Professional reports export as PDF, HTML, Markdown, and saved JSON so the answer can leave the app without rewriting notes by hand.
- The app stays local on the desktop and focused on evidence handoff, not NVR playback, generic packet browsing, or cloud upload flows.

### A focused field report beats another hour on site

- Community is enough to preview a single RTSP-over-TCP case; Optional licensing unlocks UDP unicast receive, advanced H264/H265 checks, reports, and saved sessions.
- No subscription, no account dashboard to keep alive, and no improvised VLC/Wireshark/ONVIF toolchain just to explain one broken camera stream.
- Use it when a repeatable diagnostic report is worth more than another hour of arguing between RTSP control, RTP delivery, RTCP timing, SDP metadata, codec readiness, and network ownership.

## Community Edition is genuinely useful

- Live RTSP-over-TCP inspection
- RTSP/RTP/RTCP/H264 evidence tables
- Diagnostics cockpit
- JSON report preview

Optional licensed workflows are available for people who need the expanded feature set. Licensing details belong on the website; the Community Edition remains the free way to evaluate and use the core product.

## See the real desktop workflow

### RTSP diagnostic workbench

![RTSP diagnostic workbench — RTSP Inspector](https://hannes-software.com/assets/rtsp-inspector/screenshots/workbench-overview-e805532299.webp)

A full dark-theme cockpit for camera URL, RTSP control, RTP/RTCP, codec readiness, timeline, and report handoff.

### RTSP message transcript

![RTSP message transcript — RTSP Inspector](https://hannes-software.com/assets/rtsp-inspector/screenshots/messages-transcript-4b32ddf826.webp)

Control-plane requests, responses, status codes, headers, and timing evidence.

### RTP stream evidence

![RTP stream evidence — RTSP Inspector](https://hannes-software.com/assets/rtsp-inspector/screenshots/streams-rtp-86376cf3a0.webp)

Sequence, timestamp, RTCP, SDP, and media continuity in one view.

### Codec readiness

![Codec readiness — RTSP Inspector](https://hannes-software.com/assets/rtsp-inspector/screenshots/codec-readiness-60a20bab66.webp)

H264/H265 parameter sets, codec warnings, and payload readiness checks.

### Evidence timeline

![Evidence timeline — RTSP Inspector](https://hannes-software.com/assets/rtsp-inspector/screenshots/evidence-timeline-592f7a93dc.webp)

Chronological RTSP, RTP, RTCP, codec, and diagnostic events for handoff.

### Report preview

![Report preview — RTSP Inspector](https://hannes-software.com/assets/rtsp-inspector/screenshots/report-preview-f75e319efc.webp)

Compact support reports built from protocol evidence.

## Local-first by design

RTSP Inspector is a desktop workflow. Your working files stay on the machine unless you deliberately export or share them. The product page documents the exact capability boundary so the focused workflow can be evaluated on real evidence.

## Documentation

- [Case Replay and Comparison](https://hannes-software.com/rtsp-inspector/help/case-replay/)
- [Connect to an RTSP Stream](https://hannes-software.com/rtsp-inspector/help/connect/)
- [RTSP Inspector License](https://hannes-software.com/rtsp-inspector/help/license/)
- [Export RTSP Diagnostic Reports](https://hannes-software.com/rtsp-inspector/help/reports/)
- [Troubleshooting RTSP Streams](https://hannes-software.com/rtsp-inspector/help/troubleshooting/)

## Frequently asked questions

> **Community scope:** Community Edition includes one RTSP-over-TCP session, RTSP/RTP/RTCP/H.264 evidence, the diagnostics cockpit, and JSON preview; advanced codec, UDP, saved-case, and report workflows are optional licensed capabilities.

<details>
<summary><strong>Is RTSP Inspector a video player?</strong></summary>

No. It is a diagnostic and reporting workbench for RTSP/RTP/RTCP/H.264/H.265 evidence. It does not replace VLC, an NVR, or an ONVIF manager.

</details>

<details>
<summary><strong>What's the difference between RTSP Inspector and Wireshark for RTSP debugging?</strong></summary>

Wireshark shows you every packet. RTSP Inspector shows you why the stream failed — it decodes SDP track declarations, tracks RTP continuity gaps, surfaces RTCP timing issues, inspects H.264/H.265 structure, and exports diagnostic reports as PDF evidence. See the [full comparison](https://hannes-software.com/rtsp-inspector/blogs/rtsp-inspector-vs-wireshark-vlc-onvif-device-manager/).

</details>

<details>
<summary><strong>Does it support RTP over UDP for live camera streams?</strong></summary>

Community supports RTSP-over-TCP interleaved RTP. The Community Edition is free. Optional licensed capabilities add advanced workflows; see the product page for current access details.

</details>

<details>
<summary><strong>Who uses RTSP Inspector?</strong></summary>

CCTV integrators, IP camera vendors, video platform engineers, and NVR support teams who need a repeatable, reportable answer to why a camera stream connects, glitches, freezes, or never reaches usable video.

</details>

<details>
<summary><strong>Why use RTSP Inspector if VLC can play the stream?</strong></summary>

VLC proves that one player can show video. RTSP Inspector proves why the stream succeeds or fails by exposing RTSP status, SDP tracks, transport negotiation, RTP continuity, RTCP timing, and H.264/H.265 structure. Use it when the stream must be debugged or reported, not merely watched.

</details>

<details>
<summary><strong>What is the difference between ONVIF Device Manager and RTSP Inspector?</strong></summary>

ONVIF Device Manager is useful for discovery, profiles, and finding stream URIs. RTSP Inspector starts after you have a URI and need to diagnose DESCRIBE, SETUP, PLAY, SDP, RTP, RTCP, transport, and codec evidence.

</details>

## Community, support, and security

- Bugs: [open a structured bug report](https://github.com/hannes-wan/rtsp-inspector-official/issues/new?template=bug_report.yml)
- Ideas: [request a focused workflow improvement](https://github.com/hannes-wan/rtsp-inspector-official/issues/new?template=feature_request.yml)
- Product help: [documentation and troubleshooting](https://hannes-software.com/rtsp-inspector/help/)
- Private support: [support@hannes-software.com](mailto:support@hannes-software.com)
- Security reports: follow [SECURITY.md](SECURITY.md); do not post sensitive files, credentials, patient data, or private captures in public issues.

## Official repository

This is the official public distribution and community repository for RTSP Inspector: verified release links, current screenshots, documentation routes, issue intake, and security guidance. Product development happens in a private workspace; public issues here are the right place to report reproducible product behavior and request focused improvements.
