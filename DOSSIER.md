# Athlete Dossier

## Identity

**Name:** [Your name]  
**Age:** [Age]  
**Location:** [Location]  
**Sport(s):** Running, Strength Training  
**Training experience:** 3 years (consistent)  
**Primary goal event:** Copenhagen Half Marathon, 2026-09-20  
**Target performance:** 1:50:00 (PB: 1:59:21, Δ: −9:21)  

---

## Physiology & Zones

### Power (Cycling/Running)

**FTP:** 248 W  
**FTP Indoor/Outdoor:** Not differentiated  

### Heart Rate

**Resting HR:** 55 bpm  
**Max HR:** 192 bpm  
**LTHR:** Not measured  

### Heart Rate Zones (from device)

| Zone | Name | Range (bpm) |
|------|------|-------------|
| Z1 | Recovery | < 137 |
| Z2 | Aerobic Endurance | 137–154 |
| Z3 | Aerobic Power | 155–162 |
| Z4 | Threshold | 163–174 |
| Z5a | Anaerobic Endurance | 175–181 |
| Z5b | Anaerobic Power | > 181 |

### Running Pace Zones (from device)

| Zone | Name | Range (min/km) |
|------|------|----------------|
| Z1 | Recovery | > 06:43 |
| Z2 | Aerobic Endurance | 05:37–06:43 |
| Z3 | Aerobic Power | 05:07–05:36 |
| Z4 | Threshold | 04:38–05:06 |
| Z5a | Anaerobic Endurance | 04:12–04:37 |
| Z5b | Anaerobic Power | < 04:12 |

---

## Training Structure

### Typical Weekly Schedule

| Day | Session | Duration | Type |
|-----|---------|----------|------|
| Mon | Strength (Upper + Core) | 45–60 min | Resistance |
| Tue | Interval Run | 50–60 min | VO₂ max / Threshold |
| Wed | Strength (Lower) | 45–60 min | Resistance |
| Thu | Easy Run | 30–40 min | Recovery / Z1–Z2 |
| Fri | Tempo / Threshold Run | 45–60 min | Z4 |
| Sat | Rest | — | Off |
| Sun | Long Run | 60–90 min | Z2 Endurance |

**Weekly volume:** 3.5–4.5 hours  
**Breakdown:** ~2.5–3 hours running + 1.0–1.5 hours strength  
**Training week start:** Monday (default, adjust if different)  

---

## Goals & Events

### Primary Goal

**Event:** Copenhagen Half Marathon (København Halvmarathon)  
**Date:** 2026-09-20  
**Target:** 1:50:00 (sub-1:50)  
**Current PB:** 1:59:21  
**Gap to close:** −9:21 (7.8%)  

### Secondary Goals

- Improve aerobic base and threshold running economy
- Build lower-body strength for injury resilience
- Maintain technical strength training consistency

### Training timeline to event

**Current date:** 2026-06-23  
**Time to race:** ~90 days (~12–13 weeks)  
Sufficient time for a solid build phase (8–10 weeks) + taper (2 weeks).

---

## Health & Limitations

### Current Status

**No acute injuries or limitations.** Training uninterrupted.

### Medical History

- **Hypertension:** Medicated with Ramipril 10 mg daily. Monitor HR response to high-intensity work; avoid excessive sympathetic loading on training + stress days. Standard aerobic training is safe; ensure adequate rest days.
- **Flat feet:** Mild, non-limiting. No current complaints.

### Past Injuries (Resolved)

- **Achilles tendinopathy:** Resolved ~2 years ago through targeted strengthening.
- **Knee pain:** Resolved ~2 years ago; likely training load issue, corrected via strength.
- **Iliopsoas tightness:** Resolved ~2 years ago via core + hip flexor work.

**Pattern:** Athlete responds well to strength intervention and load management. Proactive rehab works.

### Considerations for Coaching

1. **Ramipril (ACE inhibitor):**
   - May blunt resting HR slightly; use current 55 bpm as baseline, not comparative.
   - Generally compatible with endurance training; check with doctor before major intensity changes.
   - Ensure adequate hydration during long runs.

2. **Work schedule impact:**
   - 3–4 nights/week until 2–3 AM in rotating shifts.
   - Sleep averaging 7h 39min/year with variable timing; Deep sleep only ~13%.
   - **Coaching implication:** Expect greater fatigue variability week-to-week. Prioritize recovery protocols on night-shift days. Use CTL/TSB to guide intensity, not just planned sessions.

3. **Strength training is non-negotiable:**
   - Athlete has proven injury-prevention success with consistent lower-body + core work.
   - Do not cut strength to add running volume before race.

---

## Preferences & Constraints

### Training Preference

**Structured plan preferred.** Athlete wants specific daily prescriptions, not flexible "guidelines." Adjust only if work schedule explicitly prevents the day's session.

### Schedule Constraints

- **Rotating night shifts:** 3–4 days/week, unpredictable timing (until 2–3 AM).
- **Rest day:** Saturday (implied by schedule; lock in if possible).
- **Preferred hard days:** Tuesday (intervals), Friday (tempo) — bookend the week, allow recovery after night work.
- **Recovery day priority:** Thursday (easy run, post-shift recovery if Wednesday night is work).

### Nutrition / Recovery

- Sleep tracked (Garmin/Apple). Monitor trends.
- Hydration: Ensure adequate intake on night-shift training days.
- Fueling: Not specified; use Section 11 defaults (carb timing post-workout, electrolytes on long runs).

---

## Data Integration

### Tracking Tools

- **Primary data source:** Intervals.icu (Athlete ID: [your-athlete-id])
- **Device:** Garmin [model, if known] or similar (direct Intervals.icu sync enabled)
- **Sleep tracking:** Garmin/Apple Watch (synced to data file if available)

### Expected Data Fields in Section 11 JSON

- `latest.json`: Current week's power, HR, pace, TSS, CTL, ATL, TSB, load metrics
- `history.json`: 12+ weeks of rolling metrics for trend analysis
- `intervals.json`: Session-level interval data (if available)
- `routes.json`: Planned events with terrain/elevation (if applicable)

---

## Coach Instructions

### Prioritization (Metric Hierarchy for Running Half-Marathon Prep)

1. **Tier 1 (Primary):**
   - Threshold pace adherence (Z4 / 04:38–05:06 min/km)
   - Aerobic endurance durability (TSS trend, CTL, TSB balance)
   - Long run consistency (weekly Sunday, Z2, cumulative distance)
   - Strength training completion (lower-body + core, injury prevention)

2. **Tier 2 (Secondary):**
   - Recovery (sleep, HR variability, RHR trend)
   - Load balance (ACWR, Monotony, Ramp rate)
   - Cadence stability (target 170–180 spm for tempo/threshold)

3. **Tier 3 (Diagnostic):**
   - Decoupling (HR creep on long runs → fatigue indicator)
   - Variability Index (pacing consistency within zone)
   - Cardiac drift (if power/HR available)

### Coaching Rules for This Athlete

1. **Work schedule:** Treat night-shift days as de facto active recovery. Expect lower TSS and HR stability. Adjust expectations, don't penalize.

2. **Hypertension:** No restriction on aerobic training. Ensure warm-up before threshold work. Brief recovery periods between hard intervals.

3. **Strength is sacred:** 2 sessions/week (Mon upper, Wed lower) are non-negotiable. If volume must be cut to manage fatigue, reduce running volume first, not strength.

4. **Half-marathon specificity (Sep 20):**
   - Weeks 1–4 (Jul 1–Jul 28): Build durability and aerobic power. Increase long-run distance (+5–10% per week, max ~13 km for HM prep).
   - Weeks 5–9 (Jul 29–Sep 2): Peak threshold work (2× tempo or hard intervals/week). Introduce race-pace simulation.
   - Weeks 10–13 (Sep 3–Sep 20): Taper. Reduce volume 40–50%, maintain intensity (strides, short hard efforts) to avoid detraining.

5. **Pre-workout readiness check:**
   - HRV + RHR vs. baseline (sleep impact from night shift?)
   - TSB range (−10 to −30 is fine; < −30 needs caution; > +10 may indicate underload)
   - If night shift 8–24 hours prior, lower session intensity by 10–15%.

6. **Post-workout protocol:**
   - Long runs (Sunday): Easy recovery spin or walk Mon morning if time permits.
   - Hard sessions (Tue, Fri): 48h before next hard session (strength on Wed is fine; tempo on Fri is not immediately after Tue intervals).

---

## Notes for AI Coach

- **Be prescriptive, not suggestive.** Athlete prefers "Do this session" over "Consider this option."
- **Acknowledge work schedule.** Fatigue context matters; don't flag low TSS on a night-shift week as laziness.
- **Race is 90 days away.** Time is finite. Focus on durability (CTL buildout), threshold pace (race pace ≈ Z4), and specificity (Sunday long runs toward HM distance).
- **Check in on strength.** If athlete skips Wed legs due to scheduling, proactively suggest a make-up day and WHY (prevent injury spiral).
- **Red flags:** Resting HR spike > 5 bpm above baseline, consistent sleep < 6 hours over 3+ days, or TSB drop below −40 (overreach risk given night shifts + high intensity).

---

**Generated:** 2026-06-23  
**Protocol:** Section 11 v11.30+  
**Last updated:** [Update after first major review]
