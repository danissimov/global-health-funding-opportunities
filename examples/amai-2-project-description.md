# Project description: AMAI-2 — AI-assisted WhatsApp follow-up for postpartum pelvic and mental health in Harare

> Funder-neutral master description. Paste it, with a call text, into an AI chat to draft an application for any funder.
> Built on the conference poster "AI for Recovering Moms' Physical and Mental Wellbeing in Low-Resource Settings – AMAI" (Dept. of Rehabilitation Sciences, University of Zimbabwe). Everything after the pilot results is an illustrative next step for teaching, not the authors' plan.
> Rules for this file: facts and numbers, not adjectives. "Unknown" instead of guesses. No patient-identifiable data.
> Last updated: 30 Sep 2026 · Version 1

## 1. One-line summary

A therapist-in-the-loop AI assistant on WhatsApp that gives postpartum women in Zimbabwe pelvic-floor and mental-health rehabilitation between clinic visits, tested for safety, feasibility and therapist time saved.

## 2. Problem (with numbers)

- Pregnancy and birth commonly cause low back pain, pelvic girdle pain and urinary incontinence (UI). UI affects an estimated 5–36% of postpartum women and is linked to anxiety and depression.
- In Zimbabwe, maternal care is episodic (antenatal, delivery, postnatal visits). Between visits there is little support. Rehabilitation and pelvic-health services are largely inaccessible.
- Barriers: travel cost and distance, few physiotherapists, no structured follow-up.
- Existing maternal digital tools mostly send reminders and health education; few combine rehabilitation, telehealth and referral.

## 3. What already exists: pilot (phase 1)

| Item | Value |
| --- | --- |
| Setting | Parirenyatwa Hospital, Harare (University of Zimbabwe teaching hospital) |
| Design | Single-arm feasibility pilot, therapist-led WhatsApp telehealth, no AI |
| Intervention | Live synchronous text chats with a physiotherapist; 6-week home programme (pelvic floor muscle training, breathing, functional training) |
| Screened / enrolled / completed | 37 / 12 / 12 (100% retention) |
| Adherence | > 70% |
| Usability (Telehealth Usability Questionnaire, 1–7) | overall 5.42 · ease of use 6.12 · reliability 5.42 · usefulness 5.17 |
| Clinical outcomes | Improvement in the same direction on all three outcomes (quality of life, low risk, slight UI categories: 42%→92%, 25%→83%, 17%→75% of participants); not statistically significant at n = 12 (e.g., IIQ-7 p = 0.583) |
| Status | Completed; ethics for the AI prototype not yet obtained; technical partner not yet confirmed |

## 4. Aims

1. Build a safe AI assistant for WhatsApp that handles routine questions, reminders and exercise guidance, and hands every red flag to a therapist.
2. Test whether the AI-assisted pathway is feasible, safe and acceptable compared with therapist-only WhatsApp follow-up.
3. Measure therapist time saved per patient.
4. Produce the data needed to design a definitive multi-site trial.

## 5. Research questions

- Primary: Is an AI-assisted WhatsApp pathway feasible (recruitment, retention, adherence) and safe (red flags caught) for postpartum pelvic-floor rehabilitation?
- Secondary: Does it reduce therapist minutes per patient per week? Is there a signal of benefit on incontinence, pelvic girdle pain and mood?

## 6. Methods

| Component | Detail |
| --- | --- |
| Design | Phase 2a: AI build and safety run-in (n = 20, every AI message reviewed by a therapist). Phase 2b: two-arm feasibility randomised trial, 1:1, n = 80 (40 per arm) |
| Arms | A: therapist WhatsApp + AI assistant · B: therapist-only WhatsApp (as in the pilot) |
| Population | Women 6 weeks to 12 months postpartum with UI, pelvic girdle pain or low back pain; own or shared access to a phone with WhatsApp |
| Exclusions | Unable to consent; conditions needing urgent specialist care |
| Intervention length | 6-week programme; follow-up at 12 weeks |
| Languages | English, Shona, Ndebele |
| Recruitment | Postnatal clinic and midwife referral at Parirenyatwa; pilot screened 37 in 6 weeks |
| AI assistant | Rule-based triage + a large language model restricted to an approved message library. Red-flag rules (heavy bleeding, fever, severe or new pain, suicidal thoughts, other danger signs) trigger immediate handover to a therapist. No names, phone numbers or record numbers sent to the model |
| Human oversight | Therapist reviews all flagged chats daily; weekly audit of a random 10% of AI replies |
| Analysis | Feasibility benchmarks with 95% CIs; descriptive comparison of arms; sample-size calculation for a definitive trial |
| Qualitative | Focus groups with women (2–3) and interviews with therapists (all) |

## 7. Outcomes

| Type | Measure | Target / benchmark |
| --- | --- | --- |
| Feasibility | Recruitment rate; retention at 12 weeks; adherence | ≥ 70% adherence; ≥ 80% retention |
| Safety | Red flags correctly escalated; adverse events; privacy incidents | ≥ 95% escalated in run-in |
| Efficiency | Therapist minutes per patient per week | Report difference between arms |
| Clinical (exploratory) | ICIQ-UI SF; IIQ-7; EPDS; pelvic girdle pain score | Effect size estimates |
| Experience | Telehealth Usability Questionnaire; qualitative themes | TUQ ≥ 5/7 |

## 8. Team and site

| Role | Who | Status |
| --- | --- | --- |
| Lead | Early-career lecturer in physiotherapy, Dept. of Rehabilitation Sciences, University of Zimbabwe | [qualification: MSc / PhD — fill in] |
| Clinical team | Physiotherapists and occupational therapists at Parirenyatwa | Pilot team in place |
| Midwifery | Postnatal clinic midwives (recruitment) | Informal |
| Technical partner | AI / WhatsApp Business API developer | Not confirmed |
| Statistics | Trial statistician | To be identified |
| International | Nuvance Health Global Health Program (partner-site network) | Existing partnership |

## 9. Ethics, data and governance

- Ethics: University of Zimbabwe / Parirenyatwa research ethics committee and Medical Research Council of Zimbabwe; trial registration before recruitment.
- Data protection: Zimbabwe Cyber and Data Protection Act; consent covers WhatsApp use and AI processing; de-identified prompts only; chat exports stored on a university server.
- Risk that WhatsApp is a commercial platform: documented in consent; fallback SMS channel.

## 10. Timeline (24-month core study)

| Months | Milestone |
| --- | --- |
| 1–6 | Technical partner contracted; AI assistant and message library built and translated; ethics approvals |
| 6–9 | Safety run-in (n = 20) |
| 9–20 | Feasibility RCT (n = 80) |
| 20–24 | Analysis; definitive-trial protocol; publications |

## 11. Budget modules (scale to the call)

| Module | Content | Approx. cost (USD) |
| --- | --- | --- |
| A. AI build | Developer contract, WhatsApp Business API, hosting, security review | 25,000–55,000 |
| B. Safety run-in | Therapist review time, participant data bundles | 8,000 |
| C. Feasibility RCT | Research physiotherapist (1.0 FTE), research assistant (0.5 FTE), participant data and transport | 90,000 |
| D. Methods support | Statistician, trial registration, ethics fees | 25,000 |
| E. Dissemination | Open-access fees, one conference | 8,000 |
| F. Lead's salary | Only where the funder pays salary | per scheme |

Versions: **Seed (12 months, ≈ US$20k)** = module A (minimum build) + B. **Core (24 months, ≈ US$200k)** = A–E. **Career (5 years)** = A–F plus a definitive trial.

## 12. Risks

| Risk | Mitigation |
| --- | --- |
| AI gives unsafe advice | Closed message library; therapist sign-off in run-in; automatic handover on red flags |
| Privacy with WhatsApp and cloud AI | De-identified prompts; consent; data on university server |
| Slow recruitment | Two recruitment routes; pilot rate 37 screened in 6 weeks |
| No technical partner | Use seed funding to contract and test before the main study |
| Phone access | Shared-phone option; data bundles provided |

## 13. Sustainability and scale

If therapist time per patient falls, the Ministry of Health and Child Care can extend postpartum rehabilitation without new posts. WhatsApp is already widely used; running costs are data bundles and a small AI bill. Modules can extend to antenatal exercise and other rehab pathways.

## 14. Outputs

Open message library (English, Shona, Ndebele); AI safety protocol for WhatsApp health assistants; feasibility-trial paper; definitive-trial protocol.

## 15. Fit tags (for matching calls)

maternal health · rehabilitation · digital health · AI safety · implementation research · telehealth · LMIC-led · Zimbabwe · women's health · mental health · early-career researcher

## 16. Ready-to-paste summaries

**50 words.** Postpartum incontinence and distress go untreated in Zimbabwe because rehabilitation stops at the clinic door. Our pilot (n = 12, 100% retention, >70% adherence) showed WhatsApp follow-up works. We will add a locked, multilingual AI assistant with red-flag handover and test whether it keeps care safe while cutting therapist time.

**Keywords:** postpartum rehabilitation; pelvic floor; telehealth; WhatsApp; AI assistant; Zimbabwe; feasibility randomised trial
