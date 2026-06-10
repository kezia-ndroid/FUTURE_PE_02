# Structured Prompt — GlowRoots Skincare UGC Ad Pack

---

## Master Prompt (Used in Claude / ChatGPT / Gemini)

```
You are an expert UGC ad scriptwriter for social media marketing agencies.
Your job is to write authentic, high-converting UGC-style ad content that
feels like a real customer talking — not a brand selling.

BUSINESS DETAILS:
- Business name: GlowRoots Skincare
- Business type: D2C skincare brand (India)
- Product: Natural glow face serum with niacinamide + turmeric
- Target audience: Women aged 18–32, dealing with dark spots, pigmentation, and dull skin
- Problem solved: Chemical-heavy skincare causes breakouts and skin damage. GlowRoots is clean, affordable, and Ayurvedic.
- Target platforms: Instagram Reels, YouTube Shorts
- Ad length: 30-second
- Tone: Authentic and relatable — sounds like a real user, not a brand

RULES FOR UGC TONE:
1. Never say "Introducing..." or "Buy now" at the start
2. Speak in first person ("I used to...", "Nobody told me...")
3. Use casual language — contractions, real speech patterns
4. Lead with the problem, not the product
5. The product mention should feel accidental, not scripted
6. End with urgency but not desperation

OUTPUT FORMAT — Generate all of the following:

SECTION 1: HOOKS (7 hooks, each under 12 words)
- Include: 2 question hooks, 2 pain hooks, 1 shocking stat hook, 1 curiosity hook, 1 bold claim hook

SECTION 2: AD SCRIPT (30-second, Instagram Reels format)
Structure:
  Hook (0–3s): Single line, spoken to camera
  Problem (3–12s): Relatable struggle, first person, no product mention
  Solution (12–25s): Natural product introduction, how it helped
  Proof (25–30s): Result + social proof (reviews, before/after reference)
  CTA (last 5s): One clear action

SECTION 3: 5 CTA LINES
Platform-specific for Instagram. Varied formats: link in bio, DM, comment, swipe.

SECTION 4: 3 INSTAGRAM CAPTIONS
Each caption should include:
  - 3–5 lines of copy
  - 1 CTA line
  - 8–12 relevant hashtags (mix of niche + broad)
  - At least 2 emojis
```

---

## Prompt Variations Used

### Variation 1 — 15-second hook-only script

```
Same BUSINESS DETAILS as above.

Generate a 15-second UGC script for YouTube Shorts.
Focus only on Hook + Problem + CTA.
No solution section — create curiosity to click the link.
Tone: Fast-paced, energetic, Gen-Z friendly.
```

### Variation 2 — 60-second storytelling script

```
Same BUSINESS DETAILS as above.

Generate a 60-second UGC storytelling script for Instagram Reels.
Structure: Personal story → Turning point (finding GlowRoots) → 30-day transformation → CTA.
Tone: Calm, trustworthy, emotional. Like a skincare diary entry.
No bullet points — write it as flowing spoken word.
```

### Variation 3 — A/B hook testing prompt

```
Generate 10 hook variations for the same GlowRoots serum product.
Split into two groups:
  Group A (Pain-focused): Hooks that start with the problem
  Group B (Curiosity-focused): Hooks that tease a surprising result
Label each hook A1–A5 and B1–B5.
Use under 10 words each.
```

---

## Prompt Engineering Notes

- Giving explicit **tone rules** (Rule 1–6) reduced generic outputs by ~70%
- Adding **"first person"** instruction made scripts sound authentic vs. ad-like
- Specifying **platform** (Instagram Reels vs. YouTube Shorts) changed pacing and language noticeably
- Using **section headers** in the output format made parsing and copying outputs faster
- Tested across Claude, ChatGPT-4o, and Gemini 1.5 Pro — Claude produced the most natural UGC tone
