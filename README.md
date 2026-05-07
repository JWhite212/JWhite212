<div align="center">

# Jamie White

### Software & Solutions Engineer · Backend · Full-stack · IoT

*Building reliable, well-designed software — from cloud APIs and full-stack web apps to embedded firmware and on-device AI.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jamie-white-swe/)
[![Portfolio](https://img.shields.io/badge/Portfolio-1A1A1A?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio.jamiewhite.site/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Jamiecs@live.co.uk)
![Location](https://img.shields.io/badge/United%20Kingdom-555555?style=for-the-badge&logo=googlemaps&logoColor=white)

</div>

---

## About

I'm a Software & Solutions Engineer at **QVCCS**, working across backend services, full-stack applications, and system integrations. I hold an **MSc in Advanced Computer Science (Distinction)** and a **BSc (Hons) in Computer Science (2:1)** from the **University of Kent** — my MSc dissertation shipped *Snackless*, a Flutter behavioural-programme app used by real participants to complete a 30-day intervention.

My work spans cloud platforms, mobile apps, IoT firmware, and increasingly on-device AI tooling. I care about clean architecture, sensible abstractions, comprehensive testing, and shipping software people actually use. Outside delivery work I sharpen technique through deliberate side projects — usually in unfamiliar stacks — and treat each one as a chance to raise the bar on quality and maintainability.

> **Open to conversations** about Graduate / Junior Software Engineer roles where I can apply this breadth, work with thoughtful teams, and keep growing.

---

## Tech stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Frameworks & runtimes**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![SvelteKit](https://img.shields.io/badge/SvelteKit-FF3E00?style=for-the-badge&logo=svelte&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)

**Data & infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle%20ORM-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

**Tools & platforms**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![macOS](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)

---

## Featured projects

### [Context Recall](https://github.com/JWhite212/context-recall)
*Privacy-first macOS meeting assistant with local transcription and AI summaries.*

A Tauri v2 desktop application backed by a Python FastAPI daemon that watches for active Teams calls, captures dual audio sources (system audio via BlackHole loopback and microphone) to separate streams, then transcribes on-device using MLX Whisper on Apple Silicon GPU and produces structured summaries via Ollama or the Claude API. No bots, no cloud audio, no manual setup per meeting. Includes speaker diarisation, full-text search across meeting history, Obsidian-compatible Markdown export, and native Notion database output.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Tauri](https://img.shields.io/badge/-Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=white)
![MLX Whisper](https://img.shields.io/badge/-MLX%20Whisper-FF6F00?style=flat-square)
![Claude](https://img.shields.io/badge/-Claude-D97757?style=flat-square)
![Ollama](https://img.shields.io/badge/-Ollama-000000?style=flat-square)
![macOS](https://img.shields.io/badge/-macOS-000000?style=flat-square&logo=apple&logoColor=white)

[`View repository →`](https://github.com/JWhite212/context-recall)

---

### [medication-tracker](https://github.com/JWhite212/medication-tracker)
*Adherence analytics for daily dosing.*

A modern SvelteKit 5 full-stack app for logging doses and tracking adherence over time. PostgreSQL on Neon with Drizzle ORM and Lucia auth; an analytics dashboard surfaces 90-day heatmaps and hourly distribution patterns. End-to-end tested with Vitest and Playwright, deployed on Vercel.

![SvelteKit](https://img.shields.io/badge/-SvelteKit-FF3E00?style=flat-square&logo=svelte&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Drizzle](https://img.shields.io/badge/-Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Lucia](https://img.shields.io/badge/-Lucia-7B68EE?style=flat-square)
![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

[`View repository →`](https://github.com/JWhite212/medication-tracker) · [`Live site ↗`](https://medication-tracker.jamiewhite.site/)

---

### [Portfolio-Website](https://github.com/JWhite212/Portfolio-Website)
*Personal site, brutalist design, long-form case studies.*

Next.js 16 portfolio with a distinctive brutalist visual identity, Framer Motion micro-interactions, Server Actions for the contact form (via Resend), generated Open Graph images, and accessibility-first semantics. Hosts case studies that walk through the technical decisions behind each project.

![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/-Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/-Framer%20Motion-0055FF?style=flat-square&logo=framer&logoColor=white)

[`View repository →`](https://github.com/JWhite212/Portfolio-Website) · [`Live site ↗`](https://portfolio.jamiewhite.site/)

---

### [Automatic IoT Plant Watering System](https://github.com/JWhite212/Automatic-IOT-Plant-Watering-System)
*Sensor-driven embedded plant care controller.*

An Arduino / ESP32 system built with PlatformIO that monitors soil moisture, ambient temperature and humidity, light level, and water-tank level via multiple sensors. Threshold-based watering logic with configurable cooldown and tank-level guards drives a pump relay; grow-light on/off times are scheduled against a DS3231 RTC with NTP sync. A cooperative task scheduler keeps all sensor reads, actuator control, and ThingSpeak cloud telemetry non-blocking.

![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/-ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![PlatformIO](https://img.shields.io/badge/-PlatformIO-F5822A?style=flat-square)

[`View repository →`](https://github.com/JWhite212/Automatic-IOT-Plant-Watering-System)

---

## GitHub activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=JWhite212&show_icons=true&hide_border=true&theme=tokyonight&include_all_commits=true&count_private=true" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JWhite212&layout=compact&hide_border=true&theme=tokyonight" alt="Top languages" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=JWhite212&theme=tokyonight&hide_border=true" alt="GitHub streak" />

<img src="https://github-profile-trophy.vercel.app/?username=JWhite212&theme=tokyonight&no-frame=true&column=7&margin-w=8" alt="GitHub trophies" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=JWhite212&theme=tokyo-night&hide_border=true&area=true" alt="Contribution activity graph" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/JWhite212/JWhite212/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/JWhite212/JWhite212/output/github-contribution-grid-snake.svg" />
  <img alt="GitHub contribution grid snake animation" src="https://raw.githubusercontent.com/JWhite212/JWhite212/output/github-contribution-grid-snake.svg" />
</picture>

[![wakatime](https://wakatime.com/badge/user/018ce40b-0939-4ca9-9936-b8700fec78e0.svg)](https://wakatime.com/@018ce40b-0939-4ca9-9936-b8700fec78e0)

</div>

---

## Currently

- Building **Context Recall** — improving speaker diarisation accuracy and shipping richer Obsidian / Notion export workflows.
- Deepening **Spring Boot** and **clean architecture** patterns to round out my JVM backend toolkit.
- Exploring **native macOS tooling** and **on-device AI** workflows for productivity software.

---

## Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jamie-white-swe/)
[![Portfolio](https://img.shields.io/badge/Portfolio-1A1A1A?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio.jamiewhite.site/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Jamiecs@live.co.uk)

<sub>Thanks for stopping by.</sub>
