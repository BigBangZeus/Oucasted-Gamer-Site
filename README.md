# OucastedGamer Portfolio Website

A high-performance portfolio and community platform built for **OucastedGamer**, a content creator and Twitch streamer. The site serves as his central hub, bringing together his brand, content, community, and moderation tools under one roof with a dark, immersive gaming aesthetic.

**Live Site:** [oucastedgamer.com](https://oucastedgamer.com)

## Preview

https://github.com/user-attachments/assets/REPLACE_WITH_UPLOADED_VIDEO_ID

> Upload the screen recording to GitHub and replace the link above.

## Key Features

- **Interactive 3D Starfield** — Three.js powered animated background with performance-optimized rendering (capped FPS, low-power GPU mode, proper disposal)
- **Live Stream Detection** — Real-time YouTube and Twitch live status checks, displayed site-wide when a stream is active
- **Dynamic Video Feed** — Pulls latest videos and Shorts directly from YouTube Data API v3 with smart duration-based filtering
- **Video Preview System** — Embedded previews with countdown timers that redirect viewers to YouTube to support the channel
- **Mod Application Portal** — Multi-step application form with input sanitization, blacklist checking, rate limiting, and direct Discord submission
- **Full Admin Dashboard** — Protected admin panel with application management (approve/deny/delete), user banning, blacklist control, and question configuration
- **Discord Bot Integration** — Automated ticket creation, transcript generation, channel archiving, and application embeds via discord.js
- **Patch Notes System** — Versioned update log with public-safe and admin-detailed views, category filtering, and color-coded entries
- **Creator Code Page** — Dedicated page for Fortnite creator code promotion
- **Community Hub** — Discord integration with animated social link cards using clip-path hover effects
- **Security Hardened** — CSP headers, CORS restrictions, rate limiting on all public endpoints, input sanitization, and error message scrubbing

## Tech Stack

![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React_18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![Discord.js](https://img.shields.io/badge/Discord.js-5865F2?style=for-the-badge&logo=discord&logoColor=white)
![NextAuth.js](https://img.shields.io/badge/NextAuth.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Radix UI](https://img.shields.io/badge/Radix_UI-161618?style=for-the-badge&logo=radixui&logoColor=white)

| Layer | Tools |
|-------|-------|
| **Framework** | Next.js 15 (App Router), React 18 |
| **Language** | TypeScript |
| **Styling** | Tailwind CSS, Framer Motion, Three.js |
| **UI Components** | Radix UI, shadcn/ui, Lucide Icons, React Icons |
| **Auth** | NextAuth.js with Discord OAuth |
| **Backend** | Next.js API Routes, Discord.js bot |
| **Storage** | Vercel Blob |
| **Deployment** | Vercel |
| **Security** | CSP, HSTS, CORS, rate limiting, input sanitization |

## My Role and Achievements

I designed and built this entire platform from scratch as the sole developer. Some highlights:

- Architected the full stack from frontend UI to backend API routes and Discord bot integration
- Built a real-time moderation system where admin actions on the website create Discord tickets, manage applications, and handle bans
- Implemented a complete security layer including CORS, CSP, rate limiting, error sanitization, and admin auth
- Integrated three external APIs (YouTube Data API, Twitch API, Discord API) with proper error handling and fallback data
- Created a 3D starfield background using Three.js with performance optimizations for mobile devices
- Designed a multi-step mod application form with server-side validation, blacklist checking, and automated Discord submission
- Built a versioned patch notes system with separate public and admin views

## What I Learned

- **Next.js App Router in production** — Server components, API routes, middleware auth, and the differences between server and client rendering in a real deployment
- **Discord.js at scale** — Building a bot that handles ticket lifecycles, transcript generation, channel management, and embed formatting
- **Security in practice** — Moving beyond tutorials and actually hardening a live app: writing CSP policies, sanitizing inputs, scrubbing error messages, managing secrets across environments
- **Three.js performance** — Balancing visual quality with frame rate on lower-end devices by capping FPS, reducing pixel ratio, and properly disposing GPU resources
- **OAuth flows** — Setting up Discord OAuth with NextAuth.js, managing JWT tokens, and implementing role-based access with admin/super-admin tiers
- **API integration patterns** — Handling rate limits, fallback data, and parallel fetching across YouTube and Twitch APIs

---

> **Note:** The source code for this project is private. This README is provided for portfolio and reference purposes.

**Built by [ZootedElf](https://discord.com/users/1210736430662557698)**