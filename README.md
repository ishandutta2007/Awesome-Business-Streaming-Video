# Awesome-Business-Streaming-Video

# Awesome-Business-Streaming-Video

# Awesome-Business-Streaming-Video

## Top Business Streaming Video Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Enterprise Video Hosting, Live Streaming & Internal Communications*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Business Streaming Video**. These tools enable organizations to host, manage, secure, and stream video content for marketing, training, internal communications, and virtual events.



**Examples** include Salesforce+, Vimeo Enterprise, Brightcove, Wistia, Kaltura, Panopto, Vidyard, Qumu, Dacast, and IBM Video Streaming (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom streaming infrastructure, and open video delivery pipelines — ideal for enterprises, educators, and developers seeking transparent, data-sovereign video solutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global enterprise video streaming and management market is estimated at approximately **$26B – $30B** (expanding at an ~11–13% CAGR toward 2030). The sector exhibits **moderate concentration / medium fragmentation** (HHI ~850–1,050, with the top tier controlling 42–48% of market share), balanced between horizontal hyper-scalers (Salesforce, IBM, Microsoft) providing broad ecosystems and specialized video architectures (Brightcove, Kaltura, Panopto, Wistia) defending deep enterprise workflows, compliance, and eCDN delivery.

## SaaS/Hosted Platforms

| Platform | Description | Scale (Revenue / Valuation) | Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Salesforce+](https://www.salesforce.com/plus/)** | Salesforce's proprietary streaming network for series, live event broadcasts (Dreamforce), release readiness (Agentforce, Analytics, Commerce), and business thought leadership. | **~$300B+ MCap** (~$38B Annual Revenue) | **Free** ($0 / Trailblazer membership) | **Unlimited free access** with free Trailblazer.me account (no time limit, full on-demand library access) |
| **[IBM Video Streaming](https://www.ibm.com/cloud/video)** | Enterprise-grade live and VOD platform powered by Watson AI with automated captioning, multi-CDN delivery, and secure SSO portals. | **~$220B+ MCap** (~$62B Annual Revenue) | **Silver tier starting at $154/mo** (indicative entry tier; Gold at $773/mo; Enterprise at $898/mo) | **30-day free trial** with access to core streaming, Watson live captioning, and IBM ID registration |
| **[Vimeo Enterprise](https://vimeo.com/enterprise)** | Business video platform with SSO/SCIM, centralized library, private showcases, live streaming, AI dubbing, and marketing integrations. | **~$1.1B MCap** (~$415M Annual Revenue) | **Starter tier starting at $20/mo** ($12/mo billed annually; Standard at $33/mo; Enterprise custom) | **Permanent Free plan**: Up to 3 GB managed storage (private/embeddable videos), basic video player and creation tools |
| **[Brightcove](https://www.brightcove.com/)** | High-scale enterprise video streaming platform handling 207M+ weekly views with dynamic delivery, context-aware encoding, and DRM. | **~$120M MCap** (~$190M Annual Revenue) | **Custom annual contract starting at ~$499/mo** (~$6,000/yr minimum entry commitment) | **30-day guided free trial / PoC** on Video Cloud with upload limit (~10 videos) via business email verification |
| **[Kaltura](https://corp.kaltura.com/)** | Modular video platform for education and enterprise featuring virtual classrooms, lecture capture, interactive quizzes, and LMS/VLE integrations. | **~$200M MCap** (~$180M Annual Revenue) | **Media Services starting at $20/mo** base plan + usage (Virtual Classroom starting at $19/mo per organizer) | **30-day free trial**: Includes $100 developer/media platform credit to test APIs, transcoding, and streaming |
| **[Panopto](https://www.panopto.com/)** | Video knowledge and lecture management platform for enterprises and universities with automated transcription, AI search, and LMS integrations. | **~$350M Valuation** (~$30M Annual Revenue; K1 Investment backed) | **Custom annual contracts starting at ~$250/mo** (~$3,000/yr minimum entry contract) | **No enterprise free tier**; offers **Panopto Express** (permanent 100% free browser screen recorder with no time limit/watermarks) plus guided pilot trials upon request |
| **[Vidyard](https://www.vidyard.com/)** | Video marketing and sales engagement platform featuring AI Avatars, CRM pipeline attribution, and automated outbound video messaging. | **~$200M Valuation** (~$25M Annual Revenue; Bessemer backed) | **Pro tier starting at $29/seat/mo** (billed annually, or $89/seat/mo monthly; Plus tier at $89/seat/mo) | **Permanent Free plan**: Up to 5 new video recordings per month, lifetime limit of 15 AI videos, 30-min recording cap per video |
| **[Wistia](https://wistia.com/)** | Video marketing and hosting platform for businesses with lead capture forms, in-video CTAs, heatmaps, A/B testing, and CRM integration. | **~$150M Valuation** (~$32M Annual Revenue; Bootstrapped/Independent) | **Plus tier starting at $24/mo** ($19/mo billed annually; Pro tier at $79/mo billed annually) | **Permanent Free plan**: Up to 10 hosted videos/media files, 200 GB/month streaming bandwidth, 1 user seat |
| **[Qumu (Enghouse Video)](https://www.enghousevideo.com/)** | Enterprise video content management and eCDN live streaming platform with branded viewer portals and engagement analytics. | **~$18M Acquisition Value** (~$22M Annual Revenue; Enghouse Systems subsidiary) | **Enterprise subscriptions starting at ~$800/mo** (billed annually for 500+ seat organizations) | **14-day assisted proof-of-concept / demo trial** for enterprise organizations via Enghouse sales consultation |
| **[Dacast](https://www.dacast.com/)** | Professional live streaming and VOD hosting platform featuring CloudFront/Akamai CDN delivery, SRT/RTMP ingest, and paywall monetization. | **~$20M Valuation** (~$8M Annual Revenue; Bootstrapped/Private) | **Starter plan starting at $39/mo** (billed annually at $468/yr; Scale plan at $165/mo) | **14-day free trial**: Includes 10 GB total bandwidth, 2 GB video storage, 1 active channel, full HD streaming testing |



## Open-Source GitHub Projects



- **[Oryx (SRS Stack)](https://github.com/ossrs/oryx)**  

  All-in-one open-source video solution for creating online video services (Go/React/SRS/FFmpeg). Supports RTMP, WebRTC, HLS, HTTP-FLV, and SRT protocols. Features authentication, multi-platform streaming, recording, transcoding, virtual live events, and automatic HTTPS. Deploy in one Docker command .



- **[SendRec](https://github.com/sendrec/sendrec)**  

  Open-source async video messaging platform (AGPL) — a self-hosted Loom alternative. Features browser-based screen/camera recording, AI transcription (local whisper.cpp or cloud), timestamped comments, CTA buttons, viewer analytics, webhooks, and Slack notifications. GDPR-native with EU data residency .



- **[SRS (Simple Realtime Server)](https://github.com/ossrs/srs)**  

  The foundational open-source streaming server powering Oryx. High-performance, supports RTMP, HLS, WebRTC, SRT, and HTTP-FLV. Used by thousands of streaming services worldwide for live and on-demand delivery.



- **[Jellyfin](https://github.com/jellyfin/jellyfin)**  

  Free software media system (GPL) for organizing and streaming video libraries. Features transcoding, user management, DLNA, and client apps for all platforms. Widely used for internal video distribution and media management.



- **[PeerTube](https://github.com/Chocobozzz/PeerTube)**  

  Decentralized, federated video hosting platform (AGPL). Uses P2P (WebTorrent) to reduce bandwidth costs. Features live streaming, video channels, playlists, subtitles, and moderation tools. Self-hostable with Docker.



- **[MediaCMS](https://github.com/mediacms-io/mediacms)**  

  Modern, fully featured open-source video and media CMS (AGPL) built with Django and React. Features transcoding, HLS streaming, playlists, subtitles, comments, and REST API. Docker deployment available.



- **[Ant Media Server](https://github.com/ant-media/Ant-Media-Server)**  

  Ultra-low latency streaming engine (Apache-2.0) supporting WebRTC, RTMP, HLS, and CMAF. Features adaptive bitrate, WebRTC publishing, recording, and scalability for live events.



- **[Owncast](https://github.com/owncast/owncast)**  

  Self-hosted live streaming server (MIT) with chat, custom branding, and ActivityPub federation. Single-binary deployment, ideal for small-to-medium live broadcasts.



### Additional Strong Open-Source Options



- **[Restreamer](https://github.com/datarhei/restreamer)** — Open-source streaming server with web UI for restreaming to multiple platforms.

- **[ffmpeg](https://github.com/FFmpeg/FFmpeg)** — The universal multimedia framework for transcoding, recording, and streaming.

- **[OBS Studio](https://github.com/obsproject/obs-studio)** — Open-source broadcasting and recording software for live streaming.

- **[LiveKit](https://github.com/livekit/livekit)** — Open-source WebRTC platform for real-time video and audio.

- **[Janus Gateway](https://github.com/meetecho/janus-gateway)** — Open-source WebRTC server for video conferencing and streaming.

- Community **n8n** and **Webhook** workflows for automating video publishing and notifications.



**Frameworks for building custom systems**: Combine **Oryx** for streaming ingest and transcoding with **Jellyfin** or **MediaCMS** for video library management, **PeerTube** for federated distribution, and **PostgreSQL + Grafana** for analytics — creating a fully self-hosted enterprise video platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Video content must comply with copyright, privacy, and data protection regulations (GDPR, CCPA, etc.).

- Self-hosted open-source solutions require proper security hardening, CDN configuration, and infrastructure maintenance.



---



**Made for enterprises, media teams, educators, and developers building transparent video streaming solutions.**  

Let's make business streaming video more open, data-driven, and efficient.
