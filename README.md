# Awesome-Media-Streaming-Platforms

## Top Media Streaming Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Self-Hosted Media Servers, Live TV Platforms & P2P Streaming Alternatives*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Media Streaming Platforms**. These tools enable users to host, organize, and stream personal media libraries across devices—or, in the open-source ecosystem, build alternatives to commercial streaming services without subscriptions or vendor lock-in.



**Examples** include Netflix, Plex, Disney+, Max, and the open-source leaders Jellyfin, Kodi, LibreTV, and Aliran (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding subscription fatigue, and controlling your media stack. The open-source landscape is anchored by **Jellyfin** (the fully free Plex alternative with hardware transcoding included), **Kodi** (the local-first media center standard), and emerging projects like **LibreTV** (aggregated search/playback) and **Aliran** (peer-to-peer OTT streaming), with **ErsatzTV** and **Ampache** serving live TV and music-first niches respectively.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global video streaming market is estimated at approximately **$160B – $195B** in baseline valuations and projected to expand toward **$190B – $300B+** by 2026 with a compound annual growth rate (CAGR) between 15% and 20%. The industry exhibits a **moderately concentrated, winner-take-most structure** among the top conglomerate tier (dominated by multi-trillion/hundred-billion-dollar tech and media giants competing for global scale, live sports, and tentpole content), while coexisting with fragmented niche ecosystems in specialized animation, live TV tools, and self-hosted personal media stacks.

## SaaS/Hosted Platforms

| Product | Description | Pricing | Free Tier Limit | Company Size (Revenue / Valuation) |
| :--- | :--- | :--- | :--- | :--- |
| **[Apple TV+](https://tv.apple.com/)** | Apple Originals with high production values. | **Standard**: $9.99/month or $99/year. | **7-day free trial** with full access to Apple Originals; 3 months free with eligible Apple device purchases. | **~$391B revenue (FY2024)** / **~$3.5T market cap** (Apple Inc.) |
| **[Amazon Prime Video](https://www.primevideo.com/)** | Streaming included with Amazon Prime membership. | **Prime**: $14.99/month or $139/year (with shipping perks). **Standalone Video**: $8.99/month. | **30-day free trial** of Amazon Prime with complete catalog access. | **~$638B revenue (FY2024)** / **~$2.1T market cap** (Amazon.com, Inc.) |
| **[Netflix](https://www.netflix.com/)** | The dominant commercial streaming service with original content and global catalog. | **Standard with ads**: $7.99/month. **Standard (ad-free)**: $17.99/month. **Premium**: $24.99/month. | **No free tier & no ongoing free trial** directly offered (only occasional regional promotional campaigns). | **~$39.0B revenue (FY2024)** / **~$300B+ market cap** (Netflix, Inc.) |
| **[Disney+](https://www.disneyplus.com/)** | Disney, Pixar, Marvel, Star Wars, and National Geographic content. | **Basic (with ads)**: $9.99/month. **Premium**: $15.99/month or $159.99/year. | **No direct free tier or free trial**; access occasionally bundled via select carrier/partner promotions. | **~$91.4B revenue (FY2024)** / **~$190B market cap** (The Walt Disney Company) |
| **[Peacock](https://www.peacocktv.com/)** | NBCUniversal content with live sports and news. | **Premium (with ads)**: $7.99/month or $79.99/year. **Premium Plus (ad-free)**: $13.99/month or $139.99/year. | **No free tier or trial for new direct subscribers** (legacy ad-supported free tier phased out for new sign-ups; available via Instacart+/carrier promos). | **~$123.7B revenue (FY2024)** / **~$135B+ market cap** (Parent Comcast Corporation) |
| **[Hulu](https://www.hulu.com/)** | US streaming service with next-day TV and originals. | **With ads**: $9.99/month. **No ads**: $18.99/month. **Hulu + Live TV**: $82.99/month. | **30-day free trial** for on-demand plans (With ads / No ads); **3-day free trial** periodically offered for Live TV. | **Subsidiary of The Walt Disney Company** (~$91.4B rev / ~$190B market cap); valuation assessed at **$27.5B+** during Disney buyout. |
| **[Max (HBO)](https://www.max.com/)** | HBO, Warner Bros., and DC content. | **Basic with Ads**: $9.99/month or $99.99/year. **Ad-Free**: $16.99/month or $169.99/year. **Ultimate Ad-Free**: $20.99/month or $209.99/year. | **No native direct free tier or free trial**; 7-day trials periodically available through Amazon Prime Channels or Hulu add-ons. | **~$39.3B revenue (FY2024)** / **~$22B market cap** (Warner Bros. Discovery, Inc.) |
| **[Paramount+](https://www.paramountplus.com/)** | CBS, MTV, Nickelodeon, and Paramount content. | **Essential (with ads)**: $7.99/month or $59.99/year. **Paramount+ with SHOWTIME**: $12.99/month or $119.99/year. | **7-day free trial** on all direct subscription tiers with full catalog access before billing starts. | **~$29.2B revenue (FY2024)** / **~$7.5B market cap** (Paramount Global) |
| **[Crunchyroll](https://www.crunchyroll.com/)** | Anime streaming with simulcasts and manga. | **Fan**: $7.99/month. **Mega Fan**: $9.99/month or $99.99/year. **Ultimate Fan**: $14.99/month. | **14-day free trial** on premium Fan and Mega Fan tiers with full catalog and simulcast access. | **Acquired for $1.175B** by Sony Group Corp (~$85B+ revenue); anchors Sony's Media Networks segment (~$3B+ rev). |
| **[Plex](https://www.plex.tv/)** | Polished media server with streaming channels and remote access. | **Plex Pass**: $6.99/month, $69.99/year, or $750 Lifetime Pass. | **Free forever plan**: Local personal media playback, 50,000+ free on-demand titles, and 300+ FAST live channels; mobile playback limited to 1 min without activation/Plex Pass. | **Private company** (~$130M+ total venture funding raised; $40M Series C in 2024; estimated private valuation ~$200M–$400M). |

## Open-Source GitHub Projects



- **[Jellyfin](https://github.com/jellyfin/jellyfin)** [![GitHub Stars](https://img.shields.io/github/stars/jellyfin/jellyfin?style=social&color=white)](https://github.com/jellyfin/jellyfin/stargazers)  

  **The fully free Plex alternative.** ~38k+ stars, GPL-2.0 licensed. Self-hosted media server with **no paywalled features**—hardware transcoding, remote streaming, and mobile sync are all free . **Strengths**: community-driven with no corporate telemetry; Sonarr/Radarr integration; themeable interface. **Trade-offs**: remote streaming requires manual network configuration (reverse proxy, VPN, or dynamic DNS); less polished apps than Plex . Best for privacy-conscious users who want Plex-like functionality without subscriptions or data sharing.



- **[Kodi](https://github.com/xbmc/xbmc)** [![GitHub Stars](https://img.shields.io/github/stars/xbmc/xbmc?style=social&color=white)](https://github.com/xbmc/xbmc/stargazers)  

  **The local-first media center standard.** ~21k+ stars, GPL-2.0 licensed. Transforms any computer into a full home theater PC with library organization, metadata scraping, and add-on ecosystem. **Strengths**: deep customization, TV-friendly interface, and support for local and network media. **Trade-offs**: setup overhead for library organization; add-on ecosystem varies in quality; not designed for centralized multi-device streaming . Best for home theater enthusiasts managing media on a single device or local network.



- **[LibreTV](https://github.com/LibreSpark/LibreTV)** [![GitHub Stars](https://img.shields.io/github/stars/LibreSpark/LibreTV?style=social&color=white)](https://github.com/LibreSpark/LibreTV/stargazers)  

  **The aggregated search and playback platform.** Lightweight, free online video search and viewing platform aggregating content from multiple sources . **Features**: multi-source parallel search, cross-source aggregation (same title merged into one card), HLS playback with ad-filtering, live TV/IPTV via M3U subscriptions, progress sync via IndexedDB, source health testing with auto-disable . **Deployment**: Docker, Vercel, Cloudflare Pages. **Critical caveat**: requires a `PASSWORD` environment variable; the project **does not store or host any content**—it only parses third-party public playlists, and users are responsible for source legality . Best for users wanting a self-hosted aggregated search interface with awareness of legal responsibilities.



- **[Aliran](https://github.com/AbueloSimpson/aliran)** [![GitHub Stars](https://img.shields.io/github/stars/AbueloSimpson/aliran?style=social&color=white)](https://github.com/AbueloSimpson/aliran/stargazers)  

  **The peer-to-peer OTT streaming platform.** Self-hostable, open-source streaming on the Holepunch stack—viewers re-seed live channels to each other, so delivery scales through the audience instead of central media servers, keeping bandwidth costs near zero as it grows . **Components**: panel (origin of truth), broadcaster (stream ingestion), optional repeater (keyless super-peer), and viewer apps for Android (phone+TV), Windows, and macOS. **Status**: pre-1.0, actively developed and running on live infrastructure . Best for operators wanting to run their own streaming service without bandwidth costs scaling linearly with viewers.



- **[ErsatzTV](https://github.com/ErsatzTV/legacy)** [![GitHub Stars](https://img.shields.io/github/stars/ErsatzTV/legacy?style=social&color=white)](https://github.com/ErsatzTV/legacy/stargazers)  

  **The custom live TV channel builder.** Transforms your media library into personalized live TV channels with EPG, channel scheduling, and streaming to all devices . **Features**: custom channel creation, IPTV & EPG support, hardware transcoding (NVENC, QSV, VAAPI, AMF, VideoToolbox), integration with Plex/Jellyfin/Emby. zlib licensed. Best for users wanting a "TV channel" experience from their own library rather than on-demand browsing.



- **[Ampache](https://github.com/ampache/ampache)** [![GitHub Stars](https://img.shields.io/github/stars/ampache/ampache?style=social&color=white)](https://github.com/ampache/ampache/stargazers)  

  **The audiophile's streaming server.** Dedicated music-first platform for large music libraries, free and open-source . **Features**: transcoding on the fly (FLAC to MP3 for unsupported devices), Subsonic API compatibility, offline downloads, and no third-party telemetry. Best for users whose primary streaming need is music rather than video.



### Additional Strong Open-Source Options



- **Emby** — The proprietary predecessor to Jellyfin, with a free tier and Premiere subscription ($5/mo, $54/yr, or $119 lifetime) for hardware transcoding and DVR . Best for users wanting a middle ground between Plex and Jellyfin.

- **Navidrome** — Lightweight, fast music server compatible with Subsonic API. Best for music-only libraries needing low resource usage .

- **Audiobookshelf** — Purpose-built server for audiobooks and podcasts with cross-device progress syncing. Best for spoken-word audio collections .



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **Plex's lifetime price tripled to $750** on July 1, 2026. Jellyfin offers comparable features for free, though remote streaming requires more setup .

- **LibreTV does not host or store content**: it parses third-party public playlists, and users are solely responsible for the legality of sources they add. The project explicitly states it is for learning and personal use only .

- **Commercial streaming service pricing varies by region** and changes frequently. The figures above are US list prices as of October 2026—verify current rates on official sites.

- **Self-hosted platforms require infrastructure**: Jellyfin, Kodi, and Aliran all need servers, storage, and network configuration—free software is not free operations.



---



**Made for media enthusiasts, cord-cutters, and self-hosters building their own streaming infrastructure.**  

Let's make media streaming more open, privacy-respecting, and appropriately scoped.
