<div align="center">

<!-- ==================== 1. ANIMATED HEADER ==================== -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&custom_color_1=0D1117&custom_color_2=4C1D95&height=220&section=header&text=Pradnyesh&fontSize=44&fontColor=F8FAFC&animation=fadeIn&fontAlignY=38" width="100%" alt="Header" />

<a href="https://pradnyesh.vercel.app/">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1000&color=A78BFA&background=0D111700&center=true&vCenter=true&width=620&lines=ML+Engineer;Full-Stack+Developer;AI+Systems+Builder;Independent+Builder" alt="Typing SVG" />
</a>

<p align="center">
  <strong>Engineering intelligent products, autonomous multimodal systems, and polished digital experiences.</strong>
</p>

<p align="center">
  <a href="https://pradnyesh.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-pradnyesh.vercel.app-7C3AED?style=flat-square&logo=vercel&logoColor=white&labelColor=0D1117" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/pradnyesh-s/"><img src="https://img.shields.io/badge/LinkedIn-pradnyesh--s-4F46E5?style=flat-square&logo=linkedin&logoColor=white&labelColor=0D1117" alt="LinkedIn" /></a>
  <a href="https://x.com/Pradnyesh_25"><img src="https://img.shields.io/badge/X-@Pradnyesh__25-6366F1?style=flat-square&logo=x&logoColor=white&labelColor=0D1117" alt="Twitter" /></a>
  <a href="mailto:workspace.pradnyesh@gmail.com"><img src="https://img.shields.io/badge/Email-workspace.pradnyesh@gmail.com-8B5CF6?style=flat-square&logo=gmail&logoColor=white&labelColor=0D1117" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Location-Mumbai%20%C2%B7%20Pune%2C%20India-581C87?style=flat-square&logo=google-maps&logoColor=white&labelColor=0D1117" alt="Location" />
</p>

</div>

---

<!-- ==================== 2. ABOUT ==================== -->
## About

I am a software engineer and AI systems builder focused on the intersection of machine learning, system architecture, and product engineering. I architect and ship end-to-end applications from zero to working product — combining multimodal AI pipelines (computer vision, speech transcription, entity resolution) with robust backend engines and responsive, component-driven client interfaces.

- **Academic Foundation:** Savitribai Phule Pune University (SPPU)
  - **Degree:** Bachelor of Engineering (B.E.) in Electronics & Computer Engineering
  - **Specialization:** Honors in Artificial Intelligence and Machine Learning
- **Core Philosophy:** Engineering rigor over speculation. Build modular, provider-agnostic architectures with verifiable evidence chains and high-fidelity user ergonomics.
- **Location:** Mumbai &middot; Pune, India

---

<!-- ==================== 3. TECH STACK ==================== -->
## Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,ts,react,nextjs,fastapi,pytorch,postgres,docker,tailwind,git,githubactions,solidity&theme=dark" alt="Skill Icons" />
</div>

<br/>

| Category | Technologies & Tools |
|:---|:---|
| **Languages** | `Python` `TypeScript` `JavaScript` `SQL` `Solidity` `HTML5` `CSS3` |
| **AI / ML & Vision** | `PyTorch` `OpenCV` `Whisper` `Google Gemini Vision` `LLMs` `NLP` `LangChain` `Transformers` |
| **Frontend & Mobile** | `Next.js 14` `React 19` `React Native` `Expo (SDK 57)` `Tailwind CSS` `Framer Motion` `Expo Router` |
| **Backend & Services** | `FastAPI` `Node.js` `REST APIs` `Google Places API` `Google Maps Platform` `Cerebras API` |
| **Databases & Storage** | `PostgreSQL` `Supabase` `AsyncStorage` `Redis` |
| **Engineering & Tooling** | `Docker` `Git` `GitHub Actions` `Vercel` `EAS Build` `Linux` `Figma` `Postman` |

---

<!-- ==================== 4. AI / ML EXPERTISE ==================== -->
## AI / ML Expertise

My work centers on building real-world AI systems that reliably transform unstructured signals into structured, actionable domain intelligence:

- **Multimodal Extraction Pipelines:** Designing multi-stage ingestion architectures that extract video frames, run optical character recognition (OCR), perform speech-to-text transcription via Whisper, and parse raw metadata from real-world media streams.
- **Vision-Language Landmark Verification:** Cross-referencing visual features from short-form video frames against canonical geospatial image registries using Google Gemini Vision to verify location authenticity.
- **Semantic Analysis & Structured Synthesis:** Building LLM pipelines for sentiment parsing, customer feedback analysis, entity extraction, and prompt-engineered synthesis enforcing strict Pydantic and JSON schemas.
- **Autonomous Workflows & Defensive Engineering:** Implementing structured verification tiers (`VERIFIED`, `PARTIAL`, `FAILED`, `SKIPPED`), timeout guards, and fallback heuristics to prevent model hallucinations from contaminating application data.

---

<!-- ==================== 5. FEATURED PROJECTS ==================== -->
## Featured Projects

<details open>
<summary><strong>Travel AI — AI-Powered Multimodal Travel Intelligence Platform</strong></summary>

<br/>

AI-native travel intelligence system that transforms unstructured short-form social video (Instagram Reels) into verified real-world destinations, interactive cartography, and offline travel bookmarks.

### Technical Overview

| Category | Details |
|:---|:---|
| **Stack** | Python, FastAPI, React Native, Expo (SDK 57), TypeScript, Next.js 14, Google Gemini Vision, Google Places API, Whisper, yt-dlp, Tailwind CSS |
| **Scale** | Multi-stage pipeline processing real-world Instagram travel Reels with frame extraction, audio transcription, candidate resolution, and spatial clustering |
| **Performance** | Asynchronous media ingestion with non-blocking multimodal extraction, cached geospatial place resolution, and live pipeline stage tracking |
| **Security** | Zero invasive device permissions, server-side API key isolation, and strict input validation rejecting non-reel endpoints |
| **Impact** | Solves the "saved-for-later travel reel trap" by automating geographic disambiguation, travel budgeting, and seasonal intelligence |
| **Repository** | [25Pradnyesh/Travel-AI-](https://github.com/25Pradnyesh/Travel-AI-) |

#### Problem
Travelers frequently discover inspiring destinations through short-form social video, but creators rarely provide standardized coordinates, transit logistics, seasonal timing, or local costs. As a result, saved videos remain trapped in disorganized bookmark collections without geographic context or actionable itinerary details.

#### Solution
An end-to-end mobile and web platform that ingests Instagram Reel URLs, extracts multimodal signals (video frames, audio narration, caption text, hashtags), queries Google Places, verifies landmarks using Gemini Vision, and renders structured dossiers complete with native cartography.

```text
Instagram Reel URL
        │
        ▼
Provider Manager (yt-dlp / metadata extraction)
        │
        ▼
Multimodal Extraction (Whisper Speech-to-Text + OpenCV Video Frames + OCR)
        │
        ▼
Geographic Resolution (Google Places API + Candidate Scoring)
        │
        ▼
Multimodal AI Verification (Google Gemini Vision Cross-Reference)
        │
        ▼
Travel Intelligence Engine (Seasonality + Budget Tier + Local Tips)
        │
        ▼
ResponseBuilder (Strict Verification Status: VERIFIED / PARTIAL / FAILED)
        │
   ┌────┴───────────────────────────┐
   ▼                                ▼
FastAPI Engine                  Mobile Native Client (React Native + Expo)
(/analyze endpoint)             (Interactive MapKit / Play Maps + Offline Locker)
```

#### Engineering Decisions
- **Provider-Agnostic Abstraction:** The extraction engine abstracts media acquisition behind a provider interface, ensuring third-party platform changes do not break downstream processing.
- **Truthful Verification Status:** The system returns explicit status badges (`VERIFIED`, `PARTIAL`, `FAILED`, `SKIPPED`) rather than binary guesses, preserving user trust.
- **Zero-Delta Coordinate Safeguards:** Native maps implement automated bounding-box coordinate math with zero-delta detection, preventing native camera crashes on single-point locations.
- **Offline-First Storage:** Saved places persist locally via `@react-native-async-storage/async-storage`, allowing full itinerary browsing without network connectivity.

#### AI/ML Components
- **Whisper Integration:** Transcribes audio tracks to capture spoken local place names and creator commentary.
- **Frame-Level OCR:** Identifies textual location stamps, subtitles, and watermarks.
- **Gemini Vision Validation:** Evaluates visual fidelity between extracted video frames and verified reference photos.
- **Contextual Synthesis:** Derives optimal travel windows, daily budget tiers, recommended stay durations, and practical tips.

#### Product Thinking & Challenges
Engineered with an editorial, Swiss-inspired design system (`#F7F7F5` alabaster canvas, obsidian accents, disciplined status indicators) avoiding noisy consumer app clutter. Overcame variable video encodings, missing metadata, and external API rate limits through defensive error boundaries and transparent processing stage feedback.

#### Outcome
Shipped a modular, full-stack intelligence engine paired with an Expo SDK 57 mobile client configured with EAS cloud build profiles for iOS and Android.

</details>

<br/>

<details>
<summary><strong>Penguin Protocol — Decentralized AI Investment Syndicate</strong></summary>

<br/>

Decentralized AI investment syndicate integrating AI-assisted decision workflows with blockchain infrastructure on the high-throughput Monad network.

### Technical Overview

| Category | Details |
|:---|:---|
| **Stack** | React, TypeScript, Solidity, Smart Contracts, Web3 Wallet Integration, AI Decision Workflows, REST APIs |
| **Scale** | Syndicate prototype coordinating on-chain capital pooling, consensus voting, and automated proposal execution |
| **Performance** | High-throughput transaction execution leveraging Monad's parallelized EVM architecture |
| **Security** | Client-side wallet signing, isolated smart contract custody, and decentralized governance logic |
| **Impact** | 1st Place Winner at Monad Blitz Pune (October 2024) |
| **Repository** | [Shrysxs/monad-blitz-pune](https://github.com/Shrysxs/monad-blitz-pune) *(Hackathon Team Repository)* |

#### Problem
Traditional investment syndicates and DAOs struggle with sluggish manual research, high gas costs, fragmented governance discussions, and delayed capital deployment.

#### Solution
Penguin Protocol introduces an autonomous syndicate platform where AI agents parse protocol fundamentals, assess risk factors, and coordinate investment proposals executed directly through smart contracts.

#### Architecture & Engineering Decisions
- Engineered the frontend architecture and core product logic, translating syndicate dynamics into a functional decentralized application.
- Decoupled off-chain AI analytical reasoning from deterministic on-chain contract state transitions.
- Designed and delivered the functional MVP within an intensive 8-hour hackathon sprint.

#### AI/ML Components
- LLM-assisted decision workflows synthesizing investment theses from protocol whitepapers and tokenomics data.
- Sentiment scoring and automated risk tier categorization for incoming proposals.

#### Outcome
Awarded **1st Place / Winner** at **Monad Blitz Pune** (October 2024), demonstrating rapid technical execution and high-performance Web3 + AI architecture.

</details>

<br/>

<details>
<summary><strong>VoiceAds — Customer Feedback to Advertising Intelligence Platform</strong></summary>

<br/>

LLM-powered MarTech platform that transforms authentic customer feedback into structured advertising intelligence and high-converting marketing creative.

### Technical Overview

| Category | Details |
|:---|:---|
| **Stack** | Next.js, React, TypeScript, Python, LLMs, Tailwind CSS, REST APIs |
| **Scale** | Multi-source parsing of customer reviews, testimonials, and customer feedback streams |
| **Performance** | Streamlined semantic parsing converting bulk raw review text into structured marketing angles |
| **Security** | Sanitized text parsing pipelines and isolated API credential handling |
| **Impact** | Designed, built, and deployed as a functional prototype in under 24 hours at AIBoomi Startup Weekend Pune |
| **Live Platform** | [voiceads.vercel.app](https://voiceads.vercel.app/) *(Startup Weekend Project)* |

#### Problem
Marketing teams spend hours sifting through reviews to uncover authentic customer language, pain points, and objections needed for high-converting copywriting.

#### Solution
VoiceAds automates qualitative customer analysis by extracting thematic sentiment patterns and immediately synthesizing them into ready-to-deploy ad copy and creative briefs.

#### Architecture & Engineering Decisions
- Developed an LLM-driven semantic analysis pipeline extracting customer sentiment, recurring vocabulary, product signals, and objections.
- Built a structured feedback-to-content generation workflow outputting multi-platform copy (Meta, Google, X).
- Deployed a functional web application prototype on Vercel within 24 hours.

#### AI/ML Components
- Prompt engineering pipelines structured around proven advertising frameworks (AIDA, PAS).
- Qualitative sentiment classification preventing hallucinated marketing claims by grounding copy in real customer citations.

#### Outcome
Successfully launched live prototype at AIBoomi Startup Weekend Pune (02.2026), providing an end-to-end bridge between customer reviews and marketing ROI.

</details>

<br/>

<details>
<summary><strong>Design Resource Vault — Curated Design Intelligence Platform</strong></summary>

<br/>

Design intelligence platform for developers and designers, focused on structured discovery of curated design systems, UI resources, and interaction references.

### Technical Overview

| Category | Details |
|:---|:---|
| **Stack** | Next.js, React, TypeScript, Tailwind CSS, REST APIs, Vercel |
| **Scale** | Searchable directory cataloging established design systems, component patterns, tokens, and typography systems |
| **Performance** | Fast client-side filtering and static page optimization |
| **Repository** | [25Pradnyesh/Design-Resource-Vault](https://github.com/25Pradnyesh/Design-Resource-Vault) &middot; [Live Demo](https://design-resource-vault.vercel.app/) |

#### Overview & Outcome
Engineered content taxonomy, discovery architecture, and responsive component hierarchy to streamline high-quality interface engineering for modern product builders.

</details>

<br/>

<details>
<summary><strong>Reclaim — Contextual Digital Wellbeing Platform</strong></summary>

<br/>

AI-powered digital wellbeing platform that transforms smartphone usage patterns into contextual behavioral insights and personalized focus interventions.

### Technical Overview

| Category | Details |
|:---|:---|
| **Stack** | Next.js 14, React, TypeScript, Tailwind CSS, Supabase, PostgreSQL, Cerebras API, Llama |
| **Scale** | Collaborative Project &middot; WeMakeDevs FutureStack GenAI Hackathon (10.2025) |
| **Impact** | Built and delivered a functional end-to-end prototype within 6 days |
| **Repository** | [Shrysxs/wemakedevs](https://github.com/Shrysxs/wemakedevs) *(Hackathon Team Repository)* |

#### Overview & Outcome
Contributed to the full-stack architecture integrating Llama models via the Cerebras API with a Supabase data layer, implementing behavioral pattern analysis and focus interventions.

</details>

---

<!-- ==================== 6. EXPERIENCE ==================== -->
## Experience

- **Independent Builder & Product Development** `06.2026 — Present`
  - Architecting and shipping end-to-end applications from zero to working product.
  - Building intelligent systems with autonomous agent workflows and multimodal extraction pipelines.
  - Developing full-stack and mobile solutions across Next.js, FastAPI, Python, React Native, and modern UI engineering.

- **AI & Machine Learning Engineering** `04.2025 — Present`
  - *Projects & Research*
  - Building intelligent systems using LLMs, computer vision, and NLP extraction pipelines.
  - Developing multimodal content extraction tools from social media reels and posts for Travel AI.
  - Designing prompt engineering workflows, structured model evaluation, and autonomous agent loops.

- **Design Engineering** `07.2025 — Present`
  - *Projects & Product Development*
  - Architecting responsive, component-driven interfaces and design systems for web applications, translating product requirements into scalable UI architectures.
  - Building component-driven design systems, interaction patterns, and visual language across product surfaces.
  - Bridging design and frontend engineering through high-fidelity implementation, responsive architecture, accessibility, and reusable component primitives.

---

<!-- ==================== 7. ACHIEVEMENTS ==================== -->
## Achievements

| Event / Hackathon | Project | Recognition | Date |
|:---|:---|:---:|:---|
| **Monad Blitz Pune** | **Penguin Protocol** | 🏆 **Winner (1st Place)** | **October 2024** |

> Engineered the frontend architecture, core product logic, and on-chain coordination workflows for Penguin Protocol (a decentralized AI investment syndicate), shipping an end-to-end functional prototype in under 8 hours.

---

<!-- ==================== 8. CERTIFICATIONS ==================== -->
## Certifications

- **Verified Academic Foundation:**
  - **Bachelor of Engineering (B.E.) in Electronics & Computer Engineering** with **Honors in Artificial Intelligence and Machine Learning** — Savitribai Phule Pune University (SPPU)
- *Note:* In accordance with strict portfolio verification guidelines, external vendor certifications are unlisted as none are recorded in the portfolio source of truth.

---

<!-- ==================== 9. CODING PROFILES ==================== -->
## Coding Profiles

| Platform | Handle | Profile URL |
|:---|:---|:---|
| **GitHub** | `@25Pradnyesh` | [github.com/25Pradnyesh](https://github.com/25Pradnyesh) |

> *External competitive coding handles (e.g. LeetCode, Codeforces) are omitted to reflect verified portfolio records.*

---

<!-- ==================== 10. GITHUB ANALYTICS ==================== -->
## GitHub Analytics

<div align="center">
  <table border="0">
    <tr>
      <td align="center">
        <img src="https://github-readme-stats-fast.vercel.app/api?username=25Pradnyesh&show_icons=true&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=E2E8F0&icon_color=8B5CF6" width="390" alt="GitHub Stats" />
      </td>
      <td align="center">
        <img src="https://streak-stats.demolab.com?user=25Pradnyesh&theme=tokyonight&hide_border=true&background=0D1117&ring=8B5CF6&fire=A78BFA&currStreakLabel=8B5CF6" width="390" alt="GitHub Streak" />
      </td>
    </tr>
    <tr>
      <td colspan="2" align="center">
        <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=25Pradnyesh&layout=compact&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=E2E8F0" width="380" alt="Top Languages" />
      </td>
    </tr>
  </table>
</div>

---

<!-- ==================== 11. GITHUB TROPHIES ==================== -->
## GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy-fast.vercel.app/?username=25Pradnyesh&theme=tokyonight&no-frame=true&column=6&margin_w=15" alt="GitHub Trophies" />
</div>

---

<!-- ==================== 12. CONTRIBUTION ACTIVITY ==================== -->
## Contribution Activity

<div align="center">
  <img src="https://activity-graph.vercel.app/graph?username=25Pradnyesh&theme=react-dark&bg_color=0D1117&color=8B5CF6&line=7C3AED&point=A78BFA&hide_border=true" width="100%" alt="Activity Graph" />
</div>

---

<!-- ==================== 13. CONTRIBUTION SNAKE ==================== -->
## Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/25Pradnyesh/25Pradnyesh/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/25Pradnyesh/25Pradnyesh/output/github-contribution-grid-snake.svg">
    <img alt="Contribution Snake" src="https://raw.githubusercontent.com/25Pradnyesh/25Pradnyesh/output/github-contribution-grid-snake-dark.svg" width="100%">
  </picture>
  <p align="center"><em>Automated via <a href=".github/workflows/snake.yml">GitHub Actions</a> on the output branch.</em></p>
</div>

---

<!-- ==================== 14. CURRENT FOCUS ==================== -->
## Current Focus

```yaml
learning:
  - "Advanced multimodal vision-language architectures & spatial intelligence"
  - "Evaluation frameworks, verification harnesses, and reliability benchmarks for autonomous agents"
building:
  - "Travel AI — Multimodal travel intelligence engine (Python/FastAPI) and mobile client (React Native/Expo)"
  - "High-performance full-stack web and mobile systems"
exploring:
  - "On-device AI inference optimization and local multimodal SLMs"
  - "High-throughput parallelized EVM architectures and decentralized AI coordination"
open_to:
  - "AI Systems Engineering & Machine Learning Engineering roles"
  - "Full-Stack Development & Product Engineering opportunities"
  - "High-conviction independent building and collaborative ventures"
```

---

<!-- ==================== 15. CONNECT ==================== -->
## Connect

<div align="center">

| Platform | Channel | Link |
|:---|:---|:---|
| **Portfolio** | `pradnyesh.vercel.app` | [Visit Website](https://pradnyesh.vercel.app/) |
| **GitHub** | `@25Pradnyesh` | [Follow on GitHub](https://github.com/25Pradnyesh) |
| **LinkedIn** | `Pradnyesh S.` | [Connect on LinkedIn](https://www.linkedin.com/in/pradnyesh-s/) |
| **X / Twitter** | `@Pradnyesh_25` | [Follow on X](https://x.com/Pradnyesh_25) |
| **Email** | `workspace.pradnyesh@gmail.com` | [Send Email](mailto:workspace.pradnyesh@gmail.com) |
| **Telegram** | `@Pradnyesh_25` | [Message on Telegram](https://t.me/Pradnyesh_25) |
| **Discord** | `1397630514554212554` | [Connect on Discord](https://discord.com/users/1397630514554212554) |
| **Meeting** | `cal.com/pradnyesh` | [Book a Call](https://cal.com/pradnyesh) |

<br/>

<a href="mailto:workspace.pradnyesh@gmail.com">
  <img src="https://img.shields.io/badge/Get%20in%20Touch-workspace.pradnyesh@gmail.com-7C3AED?style=for-the-badge&logo=mail.ru&logoColor=white" alt="Get In Touch" />
</a>

</div>

---

<!-- ==================== 16. FOOTER ==================== -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&custom_color_1=4C1D95&custom_color_2=0D1117&height=120&section=footer" width="100%" alt="Footer" />
  <p align="center"><sub>Designed with precision &middot; Built with engineering rigor &middot; &copy; 2026 Pradnyesh</sub></p>
</div>
