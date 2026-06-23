# RTSP Inspector

**IP camera stream failing? Generate a protocol-level failure report before blaming the NVR, player, network, or camera.**

Turn camera black screens, VLC-vs-VMS mismatches, ONVIF handoff failures, blocked UDP media, RTP loss, and H.264/H.265 codec problems into a report a customer, vendor, or support team can act on.

[Website](https://hannes-software.com/rtsp-inspector/) · [Download](https://hannes-software.com/rtsp-inspector/download/) · [Help](https://hannes-software.com/rtsp-inspector/help/) · [Latest release](https://github.com/hannes-wan/rtsp-inspector-official/releases/tag/v1.0.2)

## The problem it solves

**Camera black screens should not turn into a blame loop.**

Built for CCTV installers, security integrators, IP camera vendors, NVR/VMS support teams, and field engineers who need a repeatable answer they can send to a customer, vendor, or internal QA team.

## Why you should try it

- You need to prove whether RTSP control, SDP, RTP delivery, RTCP timing, codec readiness, network ownership, or the camera itself is the failure boundary.
- You want a report a customer, vendor, installer, or support team can read instead of a pile of screenshots.
- You have seen “VLC plays it” and “the VMS cannot” turn into an argument. This turns it into evidence.

## What makes it strong

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

### A cheap field report beats another hour on site

- Community is enough to preview a single RTSP-over-TCP case; Professional unlocks UDP unicast receive, advanced H264/H265 checks, reports, and saved sessions.
- No subscription, no account dashboard to keep alive, and no improvised VLC/Wireshark/ONVIF toolchain just to explain one broken camera stream.
- Buy it when a repeatable diagnostic report is worth more than another hour of arguing between RTSP control, RTP delivery, RTCP timing, SDP metadata, codec readiness, and network ownership.

## What you can do with it

- **RTSP request and response timeline** — Inspect OPTIONS, DESCRIBE, SETUP, PLAY, status codes, headers, CSeq behavior, and redacted authentication evidence.
- **SDP and control URL resolution** — See tracks, codecs, payload types, clock rates, control paths, and missing or inconsistent media declarations.
- **RTP and RTCP signal analysis** — Surface loss, duplicate packets, reordering, jitter, SSRC changes, malformed packets, and sender-report timing.

## Screenshots

### RTSP diagnostic workbench

![RTSP diagnostic workbench](https://hannes-software.com/assets/rtsp-inspector/screenshots/workbench-overview-93187c7b13.webp)

A full dark-theme cockpit for camera URL, RTSP control, RTP/RTCP, codec readiness, timeline, and report handoff.

### RTSP message transcript

![RTSP message transcript](https://hannes-software.com/assets/rtsp-inspector/screenshots/messages-transcript-7bc8e92fab.webp)

Control-plane requests, responses, status codes, headers, and timing evidence.

### RTP stream evidence

![RTP stream evidence](https://hannes-software.com/assets/rtsp-inspector/screenshots/streams-rtp-7650ff7486.webp)

Sequence, timestamp, RTCP, SDP, and media continuity in one view.

## Download packages

Latest GitHub release: **v1.0.2**

- [rtsp-inspector-1.0.2-windows-x64-setup.exe](https://github.com/hannes-wan/rtsp-inspector-official/releases/download/v1.0.2/rtsp-inspector-1.0.2-windows-x64-setup.exe)
- [rtsp-inspector-1.0.2-linux-x64.AppImage](https://github.com/hannes-wan/rtsp-inspector-official/releases/download/v1.0.2/rtsp-inspector-1.0.2-linux-x64.AppImage)
- [rtsp-inspector-1.0.2-linux-x64.deb](https://github.com/hannes-wan/rtsp-inspector-official/releases/download/v1.0.2/rtsp-inspector-1.0.2-linux-x64.deb)
- [rtsp-inspector-1.0.2-linux-x64.rpm](https://github.com/hannes-wan/rtsp-inspector-official/releases/download/v1.0.2/rtsp-inspector-1.0.2-linux-x64.rpm)

Prefer the product page if you want the full download notes, licensing details, and help articles:

- https://hannes-software.com/rtsp-inspector/download/

## Editions

- **Community** — Free: Single-stream live RTSP-over-TCP diagnosis and JSON report preview. Key features: Live RTSP-over-TCP inspection, RTSP/RTP/RTCP/H264 evidence tables, Diagnostics cockpit, JSON report preview.
- **Professional** — $19 lifetime: One-time lifetime license that unlocks every paid desktop capability. Key features: PDF, HTML, Markdown, and saved JSON diagnostic reports, .risession save/open, RTP/RTCP over UDP unicast live receive, Advanced H264/H265 structural inspection, Case Library.
- **Team** — $49 team / 3 seats: Three-seat team bundle for one product. Key features: Three machine-bound seats, All Professional features, One billing email, Website checkout activation.

## Good fit / not a good fit

Good fit: Turn camera black screens, VLC-vs-VMS mismatches, ONVIF handoff failures, blocked UDP media, RTP loss, and H.264/H.265 codec problems into a report a customer, vendor, or support team can act on.

Boundary: Not a player, VMS, NVR, ONVIF manager replacement, or surveillance suite. It is a diagnostic workbench for stream evidence.

## Search terms this product is built around

RTSP diagnostic tool, RTSP stream troubleshooting, IP camera troubleshooting, RTP packet loss, H.264/H.265 stream failure, ONVIF RTSP handoff, ip camera software, ip camera app, rtp vs rtsp, streaming protocols

## About Hannes Software

Hannes Software builds focused local-first desktop tools: protocol diagnostics, music practice/transcription utilities, and small-clinic operations software. The pattern is simple: solve a narrow workflow well, keep data on the user’s machine, and sell with one-time pricing instead of a subscription treadmill.

Website: https://hannes-software.com/
Contact: hg3328762@qq.com

## Repository note

This is the official public repository for RTSP Inspector downloads, screenshots, release links, and product information. The commercial desktop application source code is not published in this repository.
