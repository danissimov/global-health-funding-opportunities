# AMAI-2: AI-assisted WhatsApp follow-up for postpartum pelvic and mental health in Harare

> Example project for the plenary. It builds on the conference poster *"AI for Recovering Moms' Physical and Mental Wellbeing in Low-Resource Settings – AMAI"* (Denhere, Murima, Butao, Mwanangeni, Chigweremba, Chipamaunga-Bamu, Verenga; Dept. of Rehabilitation Sciences, University of Zimbabwe). Everything past the pilot results is a proposed next step, not the authors' plan.

## At a glance

| Field | Value |
| --- | --- |
| Country / site | Zimbabwe · Parirenyatwa Hospital, Harare (University of Zimbabwe teaching hospital, a Nuvance Global Health partner site) |
| Lead | Early-career lecturer in physiotherapy / rehabilitation sciences |
| Stage | Pilot done (phase 1) → feasibility randomised trial (phase 2) |
| Condition | Postpartum urinary incontinence, pelvic girdle pain, low back pain, psychological distress |
| Method | Therapist-led WhatsApp follow-up + AI assistant (reminders, exercise questions, red-flag alerts) with the therapist always in the loop |
| Best-fit funder now | **Wellcome Early-Career Award** (rolling, Zimbabwe eligible, salary + up to £400k) |
| Seed money | GHIIC 2027 (Global Health Academy, up to US$20k, if it runs again) · Anthropic AI for Science API credits (up to US$20k) |

## Problem

- Urinary incontinence affects an estimated 5–36% of postpartum women and is linked to anxiety and depression (as cited on the poster).
- Maternal care in Zimbabwe is episodic: antenatal, delivery, postnatal visits. Pelvic-health rehabilitation is largely inaccessible between visits.
- Travel cost and distance stop follow-up. Therapists are few, so any remote model must save their time, not add to it.

## What the pilot already shows (phase 1, n = 12)

| Measure | Result |
| --- | --- |
| Screened / enrolled / completed | 37 / 12 / 12 (100% retention over 6 weeks) |
| Adherence | > 70% |
| Telehealth Usability Questionnaire | 5.42 / 7 overall · ease of use 6.12 · reliability 5.42 · usefulness 5.17 |
| Clinical outcomes | Consistent improvement in pelvic-floor and psychological measures; not significant at n = 12 (e.g., IIQ-7 p = 0.583) |

This is exactly what funders want before a bigger study: feasibility, acceptability and a signal.

## Research question

Can an AI-assisted WhatsApp pathway deliver postpartum pelvic-floor rehabilitation with the same safety and adherence as therapist-only chat, while cutting therapist time per patient?

## What we will do (24 months)

1. **Build and lock the AI assistant (months 1–6).** Rule-based triage plus an LLM limited to an approved message library in English, Shona and Ndebele. Red-flag rules (bleeding, fever, severe pain, suicidal thoughts) always hand over to a human. No patient identifiers sent to the model.
2. **Safety run-in (months 6–9).** 20 women; every AI reply reviewed by a therapist; target ≥ 95% of red flags caught.
3. **Feasibility RCT (months 9–20).** 80 women, 1:1: therapist WhatsApp + AI assistant vs therapist WhatsApp alone, 6-week programme, 12-week follow-up.
4. **Analysis and trial design (months 20–24).** Feasibility benchmarks, sample-size calculation for a definitive multi-site trial.

## Outcomes

| Type | Measure |
| --- | --- |
| Feasibility | Recruitment rate, retention, adherence (target ≥ 70%) |
| Safety | Red-flag sensitivity; adverse events; privacy incidents |
| Efficiency | Therapist minutes per patient per week |
| Clinical (exploratory) | ICIQ-UI SF, IIQ-7, EPDS; pelvic girdle pain score |
| Experience | TUQ; focus groups with women and therapists |

## Funding plan

| Step | Funder | Why it fits | Check |
| --- | --- | --- | --- |
| 1. Seed (now–mid 2027) | GHIIC (Global Health Academy innovation challenge) | Emerging tech incl. AI and telemedicine; partner-site teams; up to US$20k plus mentorship | 2026 round closed 1 June; confirm a 2027 round |
| 1. In-kind | Anthropic AI for Science (API credits) | Up to US$20k in credits for research use | Rolling |
| 2. Main grant | Wellcome Early-Career Award | Early-career researcher, LMIC host; salary + up to £400k research costs, ~5 years | Apply anytime; Zimbabwe stays eligible after 29 Oct 2026. Run Wellcome's eligibility self-check first |
| 2. Alternative | NIH R03 Dissemination & Implementation (PAR-25-233) | Up to US$50k/yr for 2 years | Heavy registration (SAM.gov, eRA Commons) |
| 3. Next | WHO AFRO/TDR Impact Grants | Up to US$15k implementation research | 2026-27 closed 15 Sep; next cycle expected |

## Budget outline (Wellcome ECA, research expenses, 24-month core study)

| Line | Amount (GBP) |
| --- | --- |
| Research physiotherapist (1.0 FTE) + research assistant (0.5 FTE) | 70,000 |
| AI assistant build, hosting, security review (technical partner) | 45,000 |
| Participant data bundles and transport refunds | 12,000 |
| Phones for therapists, printing, translation | 8,000 |
| Ethics, data management, trial registration | 5,000 |
| Statistician and trial-methods support | 15,000 |
| Dissemination and open-access fees | 6,000 |
| **Direct research costs** | **161,000** |
| Overheads (up to 20% of direct research costs) | 32,200 |
| PI salary | outside the £400k cap |

## Risks

| Risk | Mitigation |
| --- | --- |
| AI gives unsafe advice | Closed message library; therapist sign-off in run-in; automatic handover on red flags |
| Data protection (WhatsApp, cloud AI) | De-identified prompts only; consent covers WhatsApp use; Zimbabwe Cyber and Data Protection Act review |
| Low recruitment | Recruit at postnatal clinic and via midwives; 37 screened in 6 weeks in pilot |
| Technical partner not confirmed | Seed grant used to contract and test before the main application |

## Sustainability

If therapist time per patient drops, the Ministry of Health and Child Care can extend postpartum rehab without new posts. WhatsApp is already on most phones; the running cost is data bundles and a small AI bill.

## Ready-to-paste summaries

**One sentence.** A therapist-in-the-loop AI assistant on WhatsApp to give postpartum women in Zimbabwe pelvic-floor and mental-health rehabilitation between clinic visits, tested for safety and feasibility in an 80-woman randomised trial.

**50 words.** Postpartum incontinence and distress go untreated in Zimbabwe because rehabilitation stops at the clinic door. Our pilot (n = 12, 100% retention, >70% adherence) showed WhatsApp follow-up works. We will add a locked, multilingual AI assistant with red-flag handover and test whether it keeps care safe while cutting therapist time.

**Keywords:** postpartum rehabilitation, pelvic floor, telehealth, WhatsApp, AI assistant, Zimbabwe, feasibility RCT
