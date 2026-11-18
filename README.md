# OmniFix — One Lens, Every Solution

**Live L1 Prototype:** [https://opgamer909099-hue.github.io/omnifix/](https://opgamer909099-hue.github.io/omnifix/)

**OmniFix** is an AI-powered daily problem-solver built to remove everyday friction across three core areas of life: **money (scams & overpricing), physical objects (repairs & mechanics), and digital devices (PC & mobile troubleshooting).**

---

## 1. The Problem
In daily life, everyone faces three recurring problems where existing apps fall short:
- **Price & Scam Uncertainty:** People overpay in local markets due to a lack of real-time local pricing, or fall for fake websites and payment links.
- **Physical Repair Friction:** When everyday items break (e.g., headphone wires, furniture joints, appliances), finding exact, beginner-friendly repair steps takes too much time.
- **Tech Troubleshooting Barrier:** Non-tech users struggle with PC/mobile errors, storage issues, and broken settings, needing safe, guided, or permission-based automated help.

---

## 2. The Solution: 3 Core Pillars

### Pillar 1: Scan & Buy Safe (Price & Scam X-Ray)
- **Product & Local Price Check:** Snap a photo of any item or spare part to identify it and check estimated fair price ranges.
- **Website & Link Fraud Scanner:** Paste any suspicious URL or payment link to verify domain authenticity, SSL status, and phishing signals.

### Pillar 2: Scan & Fix Physical (Visual Repair & Mechanics)
- **Visual Fault Diagnosis:** Upload an image of a broken item to identify what went wrong internally.
- **Step-by-Step Guide & Video Match:** Get simple repair steps using everyday tools, safety warnings, and direct links to exact timestamped video tutorials.

### Pillar 3: Auto-Fix Digital (Permission-Based PC & Mobile Doctor)
- **Guided Screen Diagnosis:** Upload a screenshot of any PC/mobile error to receive visual step-by-step instructions.
- **Permission-First Auto-Fix:** With explicit user approval, run safe diagnostic and cleanup actions (e.g., network/DNS reset, temp file cleanup) while strictly blocking unsafe or illegal requests.

---

## 3. System Architecture

```mermaid
graph TD
    A[User Input: Camera / Screenshot / URL] --> B{OmniFix Core Router}
    B -->|Product / Link| C[Price & Scam X-Ray Engine]
    B -->|Broken Object| D[Visual Repair & Mechanics Guide]
    B -->|PC / Mobile Error| E[Digital Troubleshooter Agent]
    
    C --> F[Fair Price Range + Fraud Risk Score]
    D --> G[Step-by-Step Repair + Safety Check + Video]
    E --> H{User Permission Check}
    H -->|Approved| I[Safe System Fix / Guided Steps]
    H -->|Illegal / Unsafe| J[Blocked by Red-Line Safety Filter]
