# Example application concept: OneTube-TB — extraction-free, one-tube targeted sequencing for drug-resistant TB, India

> **Fictional teaching example.** The team, lab and preliminary numbers are invented to show what a competitive application to the Gates Foundation Grand Challenge *Innovations in Low-Cost and Simplified Pathogen Sequencing Workflows* (opened 18 Aug 2026, closed 29 Sep 2026) could look like. Public facts (disease burden, WHO guidance, RFP rules) are real; check them before reuse. The call: https://gcgh.grandchallenges.org/challenge/innovations-low-cost-and-simplified-pathogen-sequencing-workflows
> Compare with the earlier, weaker example ([west-nile-lab-stripseq.md](west-nile-lab-stripseq.md)): a lab with little R&D capacity leading a methods-development grant. This one puts an experienced genomics team in the lead and the public-health labs in the partner and validation role, which is how the call is designed.

## At a glance

| Field | Value |
| --- | --- |
| Lead applicant | Genomics and molecular microbiology lab at a medical university in central India (fictional: "Vidarbha Genomics Lab") |
| Co-leads / partners | State Intermediate Reference Laboratory for TB (validation site, link to the national TB programme) · an Indian reagent manufacturer (freeze-drying) · Asia Pathogen Genomics Initiative (technical partner, named in the RFP) · a public-health lab in Uganda (transfer site, year 2) |
| RFP category (Table 1) | Tuberculosis: targeted NGS drug-resistance testing per the WHO mutation catalogue; culture-free; < 48 h |
| Second module (adaptability) | Dengue virus serotype and genome (arbovirus row of Table 1) |
| Tier and ask | **Tier 2: US$600,000, 24 months** (preliminary feasibility data exist) |
| Platforms | Oxford Nanopore (MinION) and MGI (DNBSEQ-G99), same primers; Illumina-compatible by adapter swap |
| Target cost | ≤ US$10 per sample, sample to sequence, with every assumption stated |

## 1. Problem

- India carries about a quarter of the world's TB cases (WHO Global TB Report). Drug-resistant TB needs fast, complete resistance profiles to choose a regimen.
- WHO now recommends targeted next-generation sequencing (tNGS) for drug-resistant TB, but current workflows need DNA extraction kits, separate library preparation and cold-chain reagents. With commercial kits this typically costs on the order of US$70–150 per sample [CHECK: local quotes], so labs sequence only a small share of patients.
- Each lab also runs a different protocol for each pathogen, so switching from TB to dengue during an outbreak means new kits, new training and new validation.

## 2. Team and why it can deliver (fictional)

| Asset | Detail |
| --- | --- |
| People | PI (molecular microbiologist, 12 years in TB diagnostics); 2 postdocs in assay design; 3 bioinformaticians; 4 lab scientists trained on Nanopore and MGI |
| Equipment in use | 2 MinION Mk1D, 1 DNBSEQ-G99, thermocyclers, a pilot freeze-dryer at the reagent partner |
| Track record | Took part in national SARS-CoV-2 genomic surveillance; 9 papers on TB resistance genotyping; a 2025 state-funded pilot of amplicon sequencing |
| Samples | Partner reference lab receives about 1,500 sputum samples a month for drug-susceptibility testing; ethics approved for archived residual samples |
| Preliminary data | 60 archived sputa: extraction-free lysis + one-pot amplicon panel gave ≥ 90% target coverage at ≥ 50× in 52/60 (87%); concordance with culture-based WGS 50/52 for rifampicin and isoniazid resistance calls [fictional] |

## 3. The innovation: one backbone, swappable modules

1. **Sample prep without extraction kits.** Sputum is liquefied and heat/bead-lysed in a single tube; an inhibitor-tolerant polymerase removes the need for column extraction.
2. **One freeze-dried tube.** A multiplex amplicon panel covers the WHO-catalogue genes for rifampicin, isoniazid, fluoroquinolones, bedaquiline, linezolid, pyrazinamide, ethambutol and second-line injectables. Reagents are lyophilised at room-temperature stability (target: 6 months at 30 °C).
3. **Barcodes in the PCR, no library kit.** Tailed primers add sample barcodes and platform adapters in a second short PCR in the same strip, replacing ligation-based library preparation.
4. **Platform-agnostic.** The same amplicons go to Nanopore or MGI; only the adapter tail changes.
5. **Swappable modules.** The backbone (lysis, one-pot amplification, barcoding, pooled clean-up) stays the same; only the primer module changes. Year 2 adds a dengue module to show a lab can pivot without retooling or retraining.
6. **Offline analysis.** A one-click pipeline on a laptop produces a WHO-catalogue resistance report; no cloud dependence.

## 4. Cost model (assumptions stated, per sample)

| Step | Today (commercial tNGS workflow) | OneTube-TB target | How |
| --- | --- | --- | --- |
| Extraction | US$5–10 | US$0.30 | Heat/bead lysis, no kit |
| Amplification | US$8–15 | US$1.50 | In-house enzyme, freeze-dried, 10 µL reactions |
| Library prep | US$20–40 | US$0.80 | Barcodes and adapters added by PCR |
| Clean-up and QC | US$3–5 | US$0.40 | One pooled bead clean-up |
| **Pre-sequencing subtotal** | **US$36–70** | **≈ US$3.00** | Method changes, not volume |
| Sequencing consumables share | varies | US$4–7 | Reported at 24, 48 and 96 samples per run; 48 is typical for a state lab |
| **Total** | **US$70–150** [CHECK] | **≈ US$7–10** | |

The RFP warns that savings driven mainly by multiplexing or bulk buying will not be prioritised. The proposal therefore shows that **the pre-sequencing cost falls about 90% independent of batch size**, and reports the sequencing share separately.

## 5. Validation plan

| Item | Plan |
| --- | --- |
| Samples | 300 archived sputa (months 6–12, proof of concept); 600 prospective sputa at the reference lab (months 12–20) |
| Comparators | Phenotypic DST (MGIT) and culture-based whole-genome sequencing; a commercial tNGS kit on a subset |
| Targets | Sensitivity and specificity ≥ 95% for rifampicin and isoniazid, ≥ 90% for fluoroquinolones and bedaquiline vs the composite reference; ≥ 85% success on smear-positive samples, reported separately for low-grade samples |
| Turnaround | Sample to report < 48 h; hands-on time ≤ 2 h for 24 samples |
| Robustness | Reagent stability at 30 °C for 6 months; run by staff with standard molecular training at the reference lab and, in year 2, at the Ugandan transfer site |
| Second module | Dengue: 150 archived sera, serotype concordance ≥ 95% with RT-PCR; genome coverage ≥ 90% at Ct < 30 |

## 6. Milestones

| Month | Milestone | Success measure |
| --- | --- | --- |
| 3 | Panel v1 locked; freeze-dried batch 1 | ≥ 90% targets covered on reference strains |
| 6 | Cost model v1 audited | Pre-sequencing reagents ≤ US$4 |
| 12 | **Proof of concept** on 300 archived sputa | Concordance targets met; < 48 h |
| 15 | Dengue module working on the same backbone | No new equipment or retraining |
| 20 | Prospective evaluation at the reference lab | Performance holds with routine staff |
| 24 | Transfer kit and SOPs tested in Uganda; data and protocols shared | Second-site success ≥ 80% |

## 7. Budget outline (US$, 24 months)

| Line | Amount |
| --- | --- |
| Personnel (2 postdocs, 2 lab scientists, 1 bioinformatician, part of PI) | 230,000 |
| Reagents, primers, sequencing consumables | 160,000 |
| Freeze-drying development (reagent partner, subaward) | 60,000 |
| Reference-lab validation (subaward) | 50,000 |
| Uganda transfer site (subaward, training, shipping) | 40,000 |
| Travel, Asia PGI workshops | 15,000 |
| Data sharing, open-access publishing | 10,000 |
| Indirect costs (per Gates policy) [CHECK rate] | 35,000 |
| **Total** | **600,000** |

## 8. Why this has a chance (mapped to the RFP)

| RFP expectation | How OneTube-TB meets it |
| --- | --- |
| US$1–10 per sample via method innovation | Pre-sequencing cost ≈ US$3, independent of batch size |
| Simplicity, minimal steps | One tube, no extraction kit, no library kit |
| LMIC robustness, cold-chain independence | Freeze-dried reagents; tested at a state lab and an African transfer site |
| Modularity | Same backbone, TB and dengue modules |
| Platform-agnostic | Nanopore and MGI from the same amplicons |
| 18-month plan with proof of concept in 12 months | PoC milestone at month 12 |
| LMIC-led, partnership | Indian lead; national TB lab; Asia PGI; Uganda transfer |
| Sustainability and global access | Open protocols; local reagent manufacturing; route into national TB programme algorithms |

## 9. Risks

| Risk | Mitigation |
| --- | --- |
| Low coverage in paucibacillary sputum | Report by smear grade; optional pre-amplification step for low-grade samples |
| Freeze-dried enzyme loses activity | Two stabiliser formulations in parallel; cold-chain fallback |
| Cost target missed | Monthly cost audit; publish the real figure either way |
| Regulatory uptake slow | Engage the national programme from month 1; align with WHO catalogue updates |

## 10. Ready-to-paste summaries

**One sentence.** A one-tube, extraction-free targeted sequencing workflow that gives a full WHO-catalogue drug-resistance profile for TB from sputum in under 48 hours for about US$10, on Nanopore or MGI, with a swappable module for dengue.

**50 words.** India has a quarter of the world's TB, but sequencing for drug resistance costs too much to use routinely. We will replace extraction and library kits with one freeze-dried tube and PCR barcoding, cutting pre-sequencing cost by about 90%, validate against culture-based sequencing, and transfer the workflow to Uganda.

**Keywords:** tuberculosis; drug resistance; targeted NGS; amplicon sequencing; extraction-free; lyophilised reagents; platform-agnostic; India; Uganda; Asia PGI
