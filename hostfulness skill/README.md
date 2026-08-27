# Hostfulness Podcast — Brand Skill

A Claude Code skill that acts as the brand guardian for the Hostfulness podcast. It knows the manifesto, tone of voice, visual identity, and cardinal rules — and enforces them across everything it produces.

---

## Quick Start

In Claude Code, type:

```
/hostfulness
```

Then tell it what you need. Examples:

```
/hostfulness episode description for EP04 with Maja from Hotel & Spa & Gym Natura
/hostfulness Instagram post teasing the new episode about intentional hospitality
/hostfulness thumbnail brief for EP05 — guest is Andrej, boutique hotel in Kobarid
/hostfulness YouTube title + description for the episode with Tina about agritourism
/hostfulness pull quotes from this transcript: [paste transcript]
/hostfulness newsletter intro for March episode roundup
```

---

## What It Produces

### Written Content
| Type | What you get |
|------|-------------|
| **Episode descriptions** | Spotify/Apple-ready, SLO + EN |
| **Social media posts** | Instagram, Facebook, LinkedIn, X — on-brand, warm, never salesy |
| **Episode intros/outros** | Spoken-word scripts matching the podcast tone |
| **YouTube titles & descriptions** | Discoverable but not clickbait |
| **Pull quotes** | The most human moments from an episode, ready for graphics |
| **Newsletter copy** | Same tone, deeper format |

### Design Briefs
| Type | What you get |
|------|-------------|
| **Thumbnail briefs** | Layout, text, asset references, mood direction |
| **Social graphics briefs** | Dimensions, copy placement, color specs |
| **Banner/header briefs** | Following the established visual language |

---

## Language

- **Default:** Slovenian
- **English:** Say "in English" or "EN" and it switches
- **Bilingual:** Say "both" or "SLO + EN" for dual output (Slovenian first)

---

## Brand Essentials (What the Skill Knows)

### Tone of Voice

**Relaxed, but deep.** Four keywords in priority order:

1. **Warm** — human, genuine, caring
2. **Deep** — thoughtful, layered, not surface-level
3. **Authentic** — no pretense, no marketing speak
4. **Inviting** — draws people in, never lectures

**Never:** salesy, corporate, hype, preachy, motivational-poster, academic, cynical.

### Color Palette

**Gold gradient** (logo, accents):
`#825A3A` > `#B08960` > `#DEBA92` > `#C6A67F`

**Background gradient** (dark canvas):
`#182440` > `#000000`

**Text:** White (`#FFFFFF`) primary, muted gold (`#C6A67F`) secondary.

### Visual Rules

1. Logo = "host" in gold + "fulness" in white + "with Rok Kokalj" script below
2. Gold is accent only — never a background fill
3. Dark navy-to-black gradient is always the canvas
4. Photography over illustration. Real people, real moments.
5. Generous breathing room. Never cluttered.
6. Nevron branding appears subtle and secondary
7. No neon, no saturated colors, no busy patterns

### Cardinal Rules

These are non-negotiable for ALL Hostfulness content:

1. **Through the product, we seek the person.** The property is context — the relationship is the story.
2. **No transactional hospitality.** We don't glorify the industry for its own sake.
3. **Always seek the genuine.** Moments when a person transcends their role, when a relationship transcends a transaction.
4. **Hospitality is not limited to hotels.** It's a way of being — a kind, dignified, respectful relationship between people, everywhere.

---

## Content Rules

- Lead with the human story, not the property or credentials
- Frame properties as context for the hospitality story, not the headline
- End with an invitation (to listen, to reflect) — never a hard CTA
- No corporate buzzwords, no hype language, no luxury glorification
- Hashtags: `#hostfulness` always, `#gostoljubje` (SLO), `#hospitality` (EN), `#podcast` when relevant

---

## Brand Assets

All reusable assets are at: `J:\Produkcija\Podcast\2026\Reusables\`

| Asset | File |
|-------|------|
| Cover art (hi-res) | `HostfulnessCoverArt-3000px.png` |
| Cover art (standard) | `HostfulnessCoverArt.png` |
| Logo horizontal | `hostfulness-logo.png` |
| Logo square | `Logo_Square.png` |
| Logo mark / icon | `Hostfulness mark.png` |
| Facebook banner | `FB banner.png` |
| X banner | `X banner.png` |
| YouTube banner | `Banners/YoutubeBanner.png` |
| End screens (EN/SLO) | `In-video Screens/` |
| Lower thirds (MOGRT) | `Animations/hostfulness lower thirds.mogrt` |
| AE project | `Animations/Podcast graphics.aep` |

---

## Tips

- **Give it context.** The more you tell it about the guest and episode, the better the output. Paste a transcript excerpt, share the guest's story, mention key moments.
- **It defaults to the manifesto tone.** If you need something slightly different (e.g., a more casual Instagram story vs. a polished Spotify description), just say so.
- **Design briefs reference existing assets.** It knows what files exist and will point to them by name.
- **It will push back** if you ask for something that breaks the cardinal rules — that's by design.

---

## File Structure

```
~/.claude/skills/hostfulness/
  SKILL.md        — Brand rules, tone, visual identity, content instructions
  manifesto.md    — Full manifesto (SLO + EN)
  README.md       — This file
```

---

**Hostfulness Podcast — Nevron**
Host: Rok Kokalj | @RokKokaljHost
