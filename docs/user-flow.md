# OmniFix — User Flow & Safety Design

## 1. Core User Journey
When a user opens **OmniFix**, they see a clean home screen with **3 primary modes** (no clutter, no mandatory sign-up wall):

### Mode A: Scan & Buy Safe (Price & Scam X-Ray)
1. **Input:** User snaps a photo of a product/bill OR pastes a suspicious website/payment link.
2. **Processing:** Vision/URL engine identifies the item or checks domain trust signals.
3. **Output:** 
   - Estimated Fair Price Range (online vs. local market baseline)
   - Fraud/Scam Risk Indicator (Safe / Suspicious / High Risk) with clear reasons.

### Mode B: Scan & Fix Physical (Visual Repair Guide)
1. **Input:** User captures a photo of a broken item (e.g., headphone wire, furniture joint, switch).
2. **Processing:** Identifies the component, fault type, and safety risk level.
3. **Output:**
   - Safety Check (Safe for DIY vs. Professional Required)
   - Step-by-step repair instructions using common household tools
   - Direct link to relevant repair tutorial videos.

### Mode C: Auto-Fix Digital (PC & Mobile Doctor)
1. **Input:** User uploads an error screenshot or describes a device issue (slow PC, Wi-Fi drop, storage full).
2. **Processing:** Diagnoses the root cause and checks against the **Red-Line Safety Filter**.
3. **Output:**
   - **Level 1 (Guided):** Highlighted step-by-step instructions on what to click.
   - **Level 2 (Permission-Based Auto-Fix):** Prompts user with exact action preview (e.g., *"Allow OmniFix to flush DNS and clear temporary cache?"*). Runs only after explicit approval.

---

## 2. Hard Safety & Ethics Boundaries
- **Illegal Request Block:** Requests involving password cracking, unauthorized access, piracy, or bypassing security are immediately refused.
- **Zero-Trust Execution:** Every system action requires one-time explicit user approval and logs what was changed.
- **Privacy Shield:** Sensitive screens (OTPs, banking apps, passwords) are masked before analysis.
