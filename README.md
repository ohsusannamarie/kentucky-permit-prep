# Dakota's Kentucky Permit Prep

A mobile-first, ADHD-friendly study app for the Kentucky learner's permit test.

**Live app:** https://ohsusannamarie.github.io/kentucky-permit-prep/

---

## What it does

Everything Dakota needs to pass the Kentucky written knowledge test in one self-contained HTML file. No install, no account, no internet required after loading.

### Study tools
- **Practice Mode** — by topic or mixed, with frequency indicators showing how likely each question is to appear on the test
- **Mock Test** — 40 questions, 30-minute timer, mirrors the real exam format
- **Most Missed Drill** — the 32 questions that trip people up most, with personalized explanations
- **Flashcards** — 37 cards across 6 topics, filterable and shuffled
- **Cheat Sheet** — key numbers and rules in one scannable reference

### Visual learning
- **Right-of-Way Visual Trainer** — 20 interactive scenarios with SVG intersection diagrams and tap-to-answer gameplay
- **Lane Markings Guide** — visual representations of every road marking type, plus a 10-question mini quiz
- **Signs & Visual Aids** — 10 road signs with SVG diagrams and explanations

### Support
- **AI Tutor** — ask any driving question, get a warm plain-English answer (powered by Claude)
- **"You've Got This, Dakota"** — dedicated encouragement section covering test expectations, anxiety tips, and what to do if you don't pass
- **Learning Videos** — curated YouTube resources organized by topic, opens in new tab
- **Beginner Mode** — 5 key lessons for someone starting from zero
- **Dakota Mode** — personal notes and a quick-start path

### Progress & planning
- **Study Plan** — 1, 3, 7, and 14-day structured study paths
- **My Progress** — readiness score, mastery by topic, weak question review
- **Susanna's Dashboard** — read-only progress view
- **Test Day** — what to bring, day-of tips, KY-specific requirements
- **Permit Process** — full 3-tab timeline: get permit, get license, didn't pass

---

## Content

- **162 questions** across 8 categories, verified against the official 2026 Kentucky Driver Manual
- All questions tagged by test frequency (🟢 Very common / 🟡 Sometimes asked / ⚫ Rarely asked)
- 32 questions include personalized wrong-answer explanations ("Susanna's take")
- **37 flashcards** across 6 topics
- **6 cheat sheet sections** with key facts and numbers
- **10 SVG road sign diagrams**
- **20 right-of-way scenarios** with custom intersection diagrams
- **10 lane marking types** with visual road diagrams

---

## Design principles

- **Mobile-first** — built for iPhone Safari, thumb-friendly tap targets
- **ADHD-friendly** — low clutter, one thing at a time, immediate feedback, no walls of text
- **No childish gamification** — no badges, no confetti storms, no points systems
- **Warm and direct** — written like a person who wants Dakota to succeed, not like a textbook
- **Single file** — everything self-contained in one HTML file, works offline after loading

---

## Technical

- React 18 + TypeScript
- Tailwind CSS + shadcn/ui
- Bundled with Parcel into a single self-contained HTML file
- All state in localStorage under key `dakota-permit-v3`
- AI Tutor uses the Anthropic API (Claude Sonnet)
- No build step required to use — just open the HTML file

---

## KY permit test facts

- **40 questions**, need **32/40 (80%)** to pass
- Vision requirement: **20/40**
- Adult BAC limit: **0.08%** | Under-21: **0.02%** | CDL: **0.04%**
- Default speed limits: interstate **65 mph**, state highway **55 mph**, residential **35 mph**
- Signal before turning: **100 feet**
- Minimum following distance: **4 seconds**
- High beam dimming: **500 ft** oncoming, **300 ft** following
- Supervising driver during permit: licensed, **21+**, front passenger seat

All content verified against the [2026 Kentucky Driver Manual](https://drive.ky.gov).

---

## Built by

Susanna — talent intelligence professional, occasional app builder, full-time believer that Dakota can do this. 💛
