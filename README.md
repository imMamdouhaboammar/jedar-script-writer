# 🛡️ Jedar Script Writer

[![AI Agent Skill](https://img.shields.io/badge/AI%20Skill-Claude%20%2F%20Antigravity%20%2F%20Cursor-8A2BE2.svg)](https://github.com/imMamdouhaboammar/jedar-script-writer)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Dialects](https://img.shields.io/badge/Dialects-Saudi%20%2F%20Gulf%20%7C%20Egyptian-success.svg)](#dialect-support)
[![Rhythm](https://img.shields.io/badge/Rhythm-Ping%20Pong%20System-blueviolet.svg)](#the-ping-pong-rhythm)

**Jedar Script Writer** is an AI agent skill specializing in high-impact talking-head short-form video scripts (Reels, TikTok, Shorts) for **JEDAR (جدار)** — the pioneering Saudi media crisis management and reputation defense agency.

It crafts scripts using the **Ping-Pong rhythm**, low-friction soft CTA triggers, dual-dialect delivery (Saudi/Gulf and Egyptian), and a strict "one hero proof" testing discipline.

---

## 🎥 The Ping-Pong Rhythm System

Talking-head scripts alternate rapidly between short provocative assertions and illuminating explanations:
1. **The Intrigue Hook**: Uncovers a hidden angle in executive communication or public reputation defense.
2. **Ping (Statement)**: 3–6 words delivering a counter-intuitive observation.
3. **Pong (Elaboration)**: 8–15 words explaining the real-world consequence or operational mechanism.
4. **The Single Proof**: Exactly ONE verifiable proof point per script (e.g. 15-min response SLA or strict client anonymity).
5. **Frictionless Soft CTA**: Comment keyword, save post, or WhatsApp prompt.

---

## 📂 Repository Architecture

```text
jedar-script-writer/
├── SKILL.md                          # Master agent instructions & ethical boundaries
├── LICENSE                           # MIT License
├── README.md                         # Documentation & usage guide
└── resources/
    ├── angles-bank.md                # 5 tested campaign angles for reputation management
    ├── author-approved-scripts.md    # Author's approved & award-winning scripts, verbatim + annotated
    ├── author-voice-dna.md           # Extracted voice pattern, hook families, transfer map to JEDAR
    ├── brand-context.md              # Jedar brand identity, positioning, & tone of voice
    ├── cta-triggers.md               # CRO-driven soft CTA triggers & comment keywords
    ├── dialect-rules.md              # Gulf & Egyptian dialect conversion rules
    ├── ping-pong-craft.md            # Line-by-line rhythm pacing guidelines
    └── script-exemplars.md           # Battle-tested video script exemplars
```

---

## ⚡ Installation

### 1. Claude Code
```bash
# Personal skills
mkdir -p ~/.claude/skills/jedar-script-writer
git clone https://github.com/imMamdouhaboammar/jedar-script-writer.git ~/.claude/skills/jedar-script-writer

# Project skills
mkdir -p .claude/skills/jedar-script-writer
git clone https://github.com/imMamdouhaboammar/jedar-script-writer.git .claude/skills/jedar-script-writer
```

### 2. Google Antigravity & Agent Kernel
```bash
mkdir -p ~/.gemini/antigravity/skills/jedar-script-writer
git clone https://github.com/imMamdouhaboammar/jedar-script-writer.git ~/.gemini/antigravity/skills/jedar-script-writer
```

---

## 🚀 Usage & Prompt Triggers

```text
/jedar-script-writer اكتبلي سكريبت ريلز بلهجة سعودية عن إدارة الأزمات وقت الترند السلبي
```

### Natural Triggers
- `عايز 3 سكريبتات ريلز لجدار بإيقاع البينج بونج`
- `اكتب سكريبت تيك توك موجه للمديرين التنفيذيين عن سرية إدارة الأزمات`
- `حول السكريبت ده من مصري لسعودي مع الحفاظ على نبرة جدار الهادية`

---

## 👤 Author & Credits

- **Author**: Mamdouh Aboammar ([@imMamdouhaboammar](https://github.com/imMamdouhaboammar))
- **Agency**: JEDAR Agency ([jedar-agency.com](https://jedar-agency.com))
- **License**: MIT
