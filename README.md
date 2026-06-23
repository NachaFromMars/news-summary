# news-summary — Daily news briefings from trusted international RSS feeds

> Fetch and summarize news from BBC, Reuters, NPR, and Al Jazeera via RSS. Covers world news, business, and technology — with optional voice summary output.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)

## Overview
news-summary fetches news from trusted international sources via their public RSS feeds, parses and summarizes the content by topic, and optionally converts the summary to voice audio. It covers multiple geographic and editorial perspectives — Western (BBC, Reuters, NPR) and global south (Al Jazeera) — for a balanced picture of world events.

## Features
**RSS sources:**
- **BBC** — world news, top stories, business, technology
- **Reuters** — world news
- **NPR** — US perspective
- **Al Jazeera** — global south perspective

**Output:** topic-organized text summary + optional TTS voice output

**Workflow:** fetch RSS → parse → summarize by topic → optional TTS

## Usage / Quick Start
Trigger with a news request. The skill fetches current RSS feeds, organizes by topic, and delivers a concise briefing.

## Trigger Keywords (OpenClaw)
news updates, daily briefing, what's happening, latest news, world news, news summary

## Related Skills
- [ai-news-collectors](https://github.com/NachaFromMars/ai-news-collectors) — AI-specific news aggregation with heat ranking
- [edge-tts](https://github.com/NachaFromMars/edge-tts) — voice output for the optional TTS step

---
Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.
