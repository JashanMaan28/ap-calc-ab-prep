---
name: AP Calc AB Prep — Product Context
description: Strategic context for an AP Calculus AB study app aimed at the maker and their high-school classmates: three co-equal modes, warm/encouraging tone, a mascot, no SaaS-cream defaults.
type: project
---

# Product

## Register

product

## Users

High-school students preparing for the AP Calculus AB exam — specifically the maker and their friends/classmates. A small, known peer group, not a faceless public. They open the tool on a laptop or phone in study sessions: sometimes a 15-minute topic drill between classes, sometimes a full timed practice exam on a weekend, sometimes a quick lookup of a formula or theorem during homework. They are real students under real time pressure, not children. They want to feel that the tool respects their goal (a 5 on the exam) and that using it is genuinely encouraging rather than test-anxiety-inducing.

## Product Purpose

A single-surface AP Calc AB study hub with three co-equal modes:

1. **Practice Exam** — full timed exam under realistic conditions. Pacing and stamina.
2. **Topic Practice** — drill specific units with fast feedback and explanations. Concept mastery.
3. **Study Guide** — formulas, theorems, worked examples. Reference during homework.

A fourth surface — **FRQ Practice** — sits alongside as a focused mode for free-response writing.

Success looks like a classmate who actually opens the app two or three times a week between now and the exam, finishes a session, and walks away both *more confident* and *more prepared*. Not "I crammed 40 questions in panic the night before." The streak/XP loop and warm feedback exist to lower the activation energy of starting a session, not to gamify away the actual studying.

## Brand Personality

Three words: **encouraging, bold, expert.**

Voice:
- "Nice catch!" not "Correct."
- "Not quite — here's why." not "Incorrect."
- Warmth on wrong answers; explanations always show the work.
- Never baby-talk, never lecture-down. The student is preparing for a college-credit exam; talk to them as someone capable.

Visual personality:
- Bold playful color carries the identity, not generic SaaS blue.
- Geometric, slightly rounded forms.
- A recurring mascot or character with a simple identity that reacts to streaks, correct answers, and missed sessions. Not a cartoon — a confident little companion.
- Streaks, XP, and visible progress are first-class UI elements, not afterthoughts buried in a settings page.

Emotional goals: the student should feel *welcomed* on the home screen, *focused* during a question, *celebrated* (modestly) after a streak, and *understood* after a wrong answer.

## Anti-references

This must NOT look or feel like:

- **Generic SaaS blue-and-white** — the current state of the file. Stripe-ish accent blue, white cards, light gray shadows, neutral sans, sticky white nav. The AI-default training-data reflex for "study tool." We are deliberately moving away from this.
- **College Board / official AP test simulator** — navy headers, serif body, sober gray-on-white, clinical pacing. Too test-anxious for a tool meant to feel encouraging.
- **Cold and sterile** — Notion-grayscale, all-black-and-white minimalism, zero personality. Encouragement requires warmth, and warmth requires color.
- **Loud / overstimulating** — Duolingo's *worst* tendencies (confetti everywhere, neon green clashing with neon red, animated mascot in every corner, popups). Crypto-app energy. We want the *warmth* of Duolingo, not the *noise* of it.
- **Childish or dumbed-down** — cartoon equations, comic-sans-adjacent type, "math is fun!" stickers. These students are doing real calculus. Warmth must not slide into juvenile.

## Design Principles

1. **Warm, not soft.** Encouraging copy and bold color, but the math itself is rendered with the precision of a textbook. Personality wraps the content; it never competes with it.
2. **Three modes, three first-class rooms.** Practice Exam, Topic Practice, and Study Guide are co-equal. The home screen treats them as siblings, not as a hero plus two also-rans. FRQ Practice rides alongside as a focused fourth surface.
3. **Encourage progress, don't punish wrong answers.** Wrong is a learning moment, not a failure state. Red-X shaming is banned. Feedback is warm, the explanation is always visible, and retry is one click away.
4. **Concentration is the feature.** Even with personality, the question on screen must be the focal point during practice. No chrome, mascot, or streak counter steals attention from the math while a student is solving.
5. **Show the math, not the brand.** MathJax-rendered equations and prose are the core content. Typography, spacing, and color exist to make formulas legible and beautiful — never to upstage them.

## Accessibility & Inclusion

- WCAG AA compliance: contrast, focus rings, keyboard navigation through all practice flows.
- Full keyboard support for selecting answer choices, submitting, advancing, and toggling theme — students should be able to drill through a topic set without touching the mouse.
- Honor `prefers-reduced-motion`: any mascot reactions, streak celebrations, or page transitions degrade gracefully to instant or fade-only.
- Color is never the sole signal for correct/wrong; pair with icon, text, and position cues so a colorblind student loses nothing.
- Math (MathJax) must remain readable in both light and dark themes — verify SVG color inheritance on every theme change.
