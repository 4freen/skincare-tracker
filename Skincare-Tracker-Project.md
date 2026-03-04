# Skincare Tracker Project

Goal: **simplify skincare tracking for a skincare concierge app** by reducing friction and increasing engagement/completion of daily check-ins.

## Problem
Daily check-ins are hard to sustain if they require:
- logging in on a phone every day
- repeating the same long questionnaire
- low perceived “reward” for the effort

## Proposed interventions

### 1) Calendar-based daily check-in reminders (via email)
**Idea:** Use email to create a *calendar reminder* that prompts a quick daily snapshot.

- Create **daily calendar events** for the next **8 weeks**
- Schedule at either:
  - **start of day** (to plan and set intention), or
  - **end of day** (to reflect and capture the day’s outcome)
- If a user misses a check-in, send a **follow-up nudge later the same day** to complete it

Expected impact:
- Reduced “remembering” burden (calendar does it)
- More consistent daily adherence
- Higher completion rates from a gentle second chance nudge

### 2) Photo-based condition check + contextual follow-up questions
**Idea:** Instead of asking all questions up front (e.g., 14 questions), capture face photos and ask **targeted** questions based on detected patterns.

**Capture:**
- Front profile
- Left profile
- Right profile

**Privacy / de-identification concept (as proposed):**
- Add **eye covering** and **lip covering** so the photo is less identifiable
- Then run analysis to identify where patterns show up most

**AI-assisted pattern detection → contextual questions**, for example:
- Acne concentrated around eyes → “Do you wear glasses?”
- Jawline pattern → “Could this be hormonal acne?”
- Excess facial hair pattern → “Is this hormonal-related?”
- One side of face more affected → “Do you rest/use your phone on that side?”

Expected impact:
- Less user effort than long forms
- More relevant questions (higher perceived personalization)
- Faster identification of likely contributors

## Notes / next steps
- Define the minimum viable “daily snapshot” payload (e.g., photos + 1–3 questions)
- Decide reminder timing defaults and personalization rules
- Define data storage and privacy posture for photos (retention window, encryption, consent)
- Establish model/analysis approach and how to avoid over-claiming medically

---
*Source: user voice note (2026-03-04).* 
