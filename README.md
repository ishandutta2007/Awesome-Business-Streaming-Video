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

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Salesforce+](https://www.salesforce.com/plus/)**  

  Salesforce's proprietary streaming platform for original series, product demos, and Trailblazer community content. Hosts release readiness episodes for Agentforce, Analytics, Commerce, and more .



- **[Vimeo Enterprise](https://vimeo.com/enterprise)**  

  Enterprise video platform with SSO/SCIM, searchable video library, private showcases, live streaming, AI-powered captions and dubbing, and integrations with Marketo and Marketing Cloud .



- **[Brightcove](https://www.brightcove.com/)**  

  Leading video hosting and streaming platform handling 207 million weekly views. Features dynamic delivery, context-aware encoding, monetization models (AVOD, SVOD, TVOD), and enterprise DRM .



- **[Wistia](https://wistia.com/)**  

  Video marketing platform for businesses with 440,000+ customers. Features lead capture, in-video CTAs, heatmaps, A/B testing, Automation Suite for HubSpot/Marketo/Pardot integration, and webinar hosting .



- **[Kaltura](https://corp.kaltura.com/)**  

  All-in-one video platform for education and enterprise. Features LMS/VLE integration, virtual classroom, lecture capture, video portal, in-video search, interactive quizzes, and advanced analytics .



- **[Panopto](https://www.panopto.com/)**  

  Video knowledge platform for learning at scale with 2,000+ customers. Automatically transcribes and indexes every recording, with AI-powered search, LMS integrations (Canvas, Blackboard, Moodle), and WCAG 2.1 AA accessibility .



- **[Vidyard](https://www.vidyard.com/)**  

  Video marketing and sales platform with AI Avatars, Video Agent automation, native HubSpot integration, and video engagement data syncing to CRM for lead scoring and pipeline attribution .



- **[Qumu (Enghouse Video)](https://www.enghousevideo.com/)**  

  Enterprise video-on-demand and live streaming platform. Features branded viewer portals, engagement analytics, smart content management, and scalable pricing for 500+ users .



- **[Dacast](https://www.dacast.com/)**  

  Professional live streaming platform with CloudFront and Akamai CDN delivery. Supports RTMP/SRT ingest, adaptive bitrate, DVR recording, white-label player, and domain access controls .



- **[IBM Video Streaming](https://www.ibm.com/cloud/video)**  

  Enterprise-grade live and on-demand video platform powered by IBM Watson AI. Features automated captioning, multi-CDN global delivery, SSO integration, and customizable branded portals .



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
