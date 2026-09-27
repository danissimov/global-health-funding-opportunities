# How to search for funding

[Back to the list](../README.md)

This is the six-step routine used to build this list. It takes about two hours the first time and twenty minutes a month after that.

## 1. Know which lists you are on

Most eligibility rules are written against a few public lists. Check each one for your country and write the answers down.

| List | Where to check | Why it matters |
| --- | --- | --- |
| World Bank income group | [World Bank country groups](https://datahelpdesk.worldbank.org/knowledgebase/articles/906519-world-bank-country-and-lending-groups) | Many schemes are only for low or lower-middle income countries. It changes every 1 July. |
| OECD aid (DAC) list | [OECD DAC list](https://www.oecd.org/en/topics/sub-issues/oda-eligibility-and-conditions/dac-list-of-oda-recipients.html) | UK and European aid-funded research uses this list. |
| Wellcome countries | [Wellcome country list](https://wellcome.org/research-funding/guidance/prepare-to-apply/low-and-middle-income-countries-africa-south-asia-southeast-asia) | From 29 October 2026, only Africa, South Asia and South-East Asia. |
| Horizon Europe | [EU list of participating countries](https://ec.europa.eu/info/funding-tenders/opportunities/docs/2021-2027/horizon/guidance/list-3rd-country-participation_horizon-euratom_en.pdf) | Associated countries such as Armenia can lead EU projects. |
| EDCTP membership | [Global Health EDCTP3](https://www.global-health-edctp3.europa.eu/) | Only member countries in sub-Saharan Africa receive EDCTP3 money. |
| Commonwealth | [Commonwealth Scholarship Commission](https://cscuk.fcdo.gov.uk/) | Opens UK scholarships and fellowships. |

## 2. Map who already funds health at home

Open the [IATI d-portal](https://d-portal.org/) or the [OECD CRS](https://data-explorer.oecd.org/), choose your country and filter to health. You will see which agencies and foundations spend money there, and which organisations carry out the work. These are your likeliest partners and sub-grantors.

## 3. Find people funded for similar work

Search by topic and country in [NIH RePORTER](https://reporter.nih.gov/), [Dimensions](https://app.dimensions.ai/), [Wellcome's funded grants](https://wellcome.org/research-funding/funding-portfolio/funded-grants) and [360Giving GrantNav](https://grantnav.threesixtygiving.org/). Researchers already funded in your area become mentors, co-applicants and referees. A short, specific email to one of them works better than a cold application.

## 4. Subscribe to five feeds, not fifty

- The [TDR newsletter and calls page](https://tdr.who.int/grants).
- [Fogarty global health funding news](https://www.fic.nih.gov/Funding/News/Pages/default.aspx).
- [The Global Health Network](https://tghn.org/).
- One aggregator, such as [fundsforNGOs](https://www2.fundsforngos.org/) or [Opportunity Desk](https://opportunitydesk.org/).
- Your national research council's call page (see [your country page](../README.md#start-with-your-country)).

## 5. Let AI search, then check every line

A deep-research mode (ChatGPT, Claude, Gemini or Perplexity) can build a long list in minutes. Copy the prompt below and fill in the brackets.

```text
You are a research-funding scout for a health professional in [COUNTRY].
Profile: [role, e.g. nurse / clinician / junior faculty], [institution type], [highest degree], [years since degree].
Project idea: [one sentence: population, problem, what I want to test or build].
Budget needed: [range]. Timeframe: [months].

Task:
1. Find every currently open or expected funding opportunity (grants, fellowships, small grants, in-kind training, compute credits) that I could lead or join as a named investigator.
2. Cover: my national government and councils, regional bodies, WHO/TDR and other multilaterals, foreign government funders, foundations, professional societies, and corporate programmes.
3. For each: official URL, amount, duration, eligibility (country list, degree, whether a high-income partner is required), next deadline, and whether my country's current World Bank income group qualifies.
4. Flag anything invitation-only, paused, or where eligibility changed in the last 12 months.
5. Return a table sorted by deadline, then list the three best fits and why.
Only cite official funder pages or reputable trackers. If you cannot verify a deadline or amount, write "not verified" instead of guessing.
```

Then open every official page yourself. AI models often get these wrong:

- deadlines, especially for recurring calls;
- amounts and currencies;
- country lists, which changed for many funders in 2026;
- whether a scheme is invitation-only.

## 6. Track it and register early

Keep one table with: opportunity, link, deadline, eligibility checked (yes or no), documents needed, and next action. The [CSV in this repository](../data/funding_opportunities.csv) is a good starting point.

Some registrations take weeks:

- **US federal grants** (NIH, including the K43 due 3 December 2026): SAM.gov with an NCAGE code, Grants.gov and eRA Commons.
- **EU grants:** an EU Login account and a PIC number for your institution.
- **Wellcome:** your institution must be registered on the Wellcome Funding platform.

## All the search tools

| Tool | Type | Cost | Best for | Tip |
| --- | --- | --- | --- | --- |
| [Grants.gov / Simpler.Grants.gov](https://simpler.grants.gov/) | Grant database | Free | All US federal funding notices (NIH, CDC, State Department/ECA exchange programmes such as YSEALI). | Open the full notice and check the eligibility section for 'Non-domestic (non-U.S.) entities' before investing time. |
| [NIH Guide for Grants and Contracts](https://grants.nih.gov/funding/searchguide/index.html) | Portal | Free | Official NIH funding notices (NOFOs), including Fogarty K43, D43 and global-health programme announcements. | Subscribe to the weekly NIH Guide email and search NOFOs for the phrase 'Non-domestic (non-U.S.) Entities (Foreign Institutions) are eligible'. |
| [NIH RePORTER](https://reporter.nih.gov/) | Funded-grants database | Free | Seeing who NIH already funds in your country - to find collaborators, mentors and active D43 training programmes. | Search by Organization Country (e.g., Uganda) or Agency = FIC plus activity code D43/K43 to list local PIs you can approach. |
| [Fogarty International Center funding opportunities page](https://www.fic.nih.gov/Funding/Pages/Fogarty-Funding-Opps.aspx) | Portal | Free | One-page list of Fogarty global-health research and training opportunities with dates. | Bookmark the 'Dates and Deadlines' table and cross-check with consortium sites for LAUNCH fellowship deadlines. |
| [EU Funding & Tenders Portal](https://ec.europa.eu/info/funding-tenders/opportunities/portal/) | Portal | Free | Horizon Europe and Global Health EDCTP3 calls; finding European consortium partners. | Use the Partner Search function; Armenia is associated to Horizon Europe, so Armenian teams can take part on largely the same terms as EU members. |
| [UKRI Funding Finder](https://www.ukri.org/opportunity/) | Portal | Free | UK research council calls (MRC, ESRC etc.), many of which allow LMIC co-investigators. | Filter by 'international' and read co-investigator rules - many calls need a UK lead, so use it to spot UK partners to join. |
| [NIHR funding opportunities (Global Health Research)](https://www.nihr.ac.uk/research-funding/global-health) | Portal | Free | UK-aid global health fellowships and programmes prioritising sub-Saharan Africa and South Asia. | Filter to Global Health Research; LMIC-based leads are eligible for several schemes, unlike most UK funders. |
| [Wellcome funding schemes finder](https://wellcome.org/research-funding/schemes) | Portal | Free | Personal fellowships and Discovery Awards with fixed application rounds. | Check location eligibility first - from 29 Oct 2026 only UK and LMICs in Africa, South Asia and South-East Asia qualify. |
| [Pivot-RP (Clarivate/ProQuest)](https://pivot.proquest.com/) | Grant database | Paid (institutional) | Large curated funding database with saved searches and researcher profile matching. | Ask your university library whether it subscribes; set up a saved search filtered by applicant location and get weekly alerts. |
| [GrantForward](https://www.grantforward.com/) | Grant database | Paid (institutional) | Searchable grants database with researcher-profile recommendations. | Upload your CV/profile so it auto-recommends matching calls, then filter out US-only eligibility. |
| [Research Professional (Clarivate)](https://www.researchprofessional.com/) | Grant database | Paid (institutional) | Comprehensive funding opportunities plus research-policy news, strong on UK/EU/Commonwealth funders. | Filter by 'eligible applicant country' to cut noise; check whether a partner university can share access. |
| [Instrumentl (incl. AI matching)](https://www.instrumentl.com/) | AI tool | Paid | AI-matched grant prospects and deadline tracking, mainly US foundations and federal funders. | Use the free trial to build a funder shortlist for a specific project, then verify international eligibility manually - much content is US-focused. |
| [Candid Foundation Directory (FDO)](https://fconline.foundationcenter.org/) | Grant database | Paid | Profiles of US and some international foundations and their past grants. | Search past grants by recipient country (e.g., Philippines) to see which foundations actually fund there; free access may be available at Candid Funding Information Network partner libraries. |
| [Philanthropy News Digest - RFPs (Candid)](https://philanthropynewsdigest.org/rfps) | Newsletter | Free | Free weekly list of foundation requests for proposals. | Browse the International and Health categories; many are US-only, so read eligibility first. |
| [fundsforNGOs](https://www2.fundsforngos.org/) | Newsletter | Freemium | Daily listings of grants for NGOs and researchers in developing countries. | Use its country-specific pages (e.g., Uganda, India) and the free email; premium adds deeper databases and templates. |
| [Devex (News and Devex Pro Funding)](https://www.devex.com/funding) | Grant database | Freemium | Tracking donor strategy, tenders and grants from bilateral/multilateral agencies; spotting implementing partners. | Read free Devex news on donor cuts/reallocations to anticipate where money is moving; Pro Funding search is paid. |
| [GrantWatch](https://www.grantwatch.com/) | Grant database | Freemium | Broad grant listings including an International category. | Browse free summaries to find funder names, then go to the funder site directly instead of paying for full details. |
| [ResearchConnect](https://myresearchconnect.com/) | Grant database | Paid (institutional) | Curated research funding with strong EU/UK coverage (e.g., EDCTP3 call summaries). | Its free news posts summarise big calls clearly - useful even without a subscription. |
| [EURAXESS (incl. Worldwide hubs)](https://euraxess.ec.europa.eu/) | Portal | Free | European research jobs, fellowships and funding open to international researchers. | Join the EURAXESS Worldwide hub for your region (e.g., ASEAN, India, Latin America & Caribbean) for free newsletters and info sessions. |
| [The Global Health Network (TGHN)](https://tghn.org/) | Portal | Free | Free research training, protocol tools, and funding/opportunity posts from TDR and partners. | Complete its free Global Health Training Centre courses (e.g., GCP, research ethics) - certificates strengthen fellowship applications. |
| [TDR (WHO) calls page and newsletter](https://tdr.who.int/) | Newsletter | Free | SORT IT courses, TDR scholarships, implementation research grants. | Subscribe to the TDR newsletter; SORT IT and postgraduate calls are short-window and easy to miss. |
| [Global Health Council](https://globalhealth.org/) | Newsletter | Free | US global health policy and budget updates that signal where US funding is heading. | Use its budget/advocacy updates to judge whether a US-funded programme (e.g., Fogarty, CDC) is stable before building a career plan around it. |
| [Opportunity aggregators (Opportunity Desk, Scholars4Dev, Global South Opportunities, MESA)](https://opportunitydesk.org/) | Newsletter | Free | Fast discovery of scholarships, fellowships and conference grants for LMIC applicants. | Use them for discovery only - always confirm dates and eligibility on the official funder site, as aggregators are sometimes out of date. |
| [Dimensions (Digital Science)](https://app.dimensions.ai/) | Funded-grants database | Freemium | Mining awarded grants by funder, country and topic and linking them to publications. | Filter grants by funder plus research-organisation country to identify active PIs; the grants module usually needs an institutional subscription. |
| [360Giving GrantNav](https://grantnav.threesixtygiving.org/) | Funded-grants database | Free | Open data on grants from UK funders (including major foundations like Wellcome). | Search a funder name plus your country or disease to see real award sizes and recipients before writing your budget. |
| [IATI d-portal](https://d-portal.org/) | Aid-flow data | Free | Seeing which donors and implementers fund health in a given country (e.g., Uganda, Zimbabwe). | Select your country, filter sector = Health, and list the top implementing organisations - they are potential partners or sub-grant sources. |
| [OECD Creditor Reporting System (CRS) via OECD Data Explorer](https://data-explorer.oecd.org/) | Aid-flow data | Free | Official development assistance for health by donor, recipient and sector over time. | Compare donor health spending trends for your country to spot growing funders as US funding declines. |
| [Global Fund Data Explorer](https://data.theglobalfund.org/) | Aid-flow data | Free | HIV, TB and malaria grants by country, including principal recipients. | Identify your country's principal and sub-recipients - they commission operational research and training. |
| [AI deep-research modes (ChatGPT, Claude, Gemini, Perplexity)](https://www.perplexity.ai/) | AI tool | Freemium | Scanning the web for funders matching a project, country and career stage, and summarising eligibility. | Prompt with country, career stage, topic and deadline window, and ask for official URLs - then verify every deadline and amount on the funder site, as AI can be out of date or wrong. |
| [Grantable](https://grantable.co/) | AI tool | Freemium | AI grant-writing workspace: drafting from your past documents, RFP checklists, funder prospecting. | Paste the call guidelines to generate a requirements checklist; the free tier (5 messages/day) is enough for a checklist and outline. |
| [GrantAdvisor](https://grantadvisor.org/) | Grant database | Free | Anonymous grantee reviews of foundations (what the process is really like). | Mostly US foundations - useful before approaching a US funder, less so for LMIC-specific schemes. |
| [Consensus](https://consensus.app/) | AI tool | Freemium | Quick evidence summaries from peer-reviewed papers to frame the research gap in a proposal. | Ask a yes/no research question to see how settled the evidence is, then cite the underlying papers, not the AI summary. |
| [Elicit](https://elicit.com/) | AI tool | Freemium | Semi-automated literature review and data extraction to build background and justification sections. | Use its extraction table (population, setting, outcome) to show reviewers the gap is real in LMIC settings like yours. |
| [Google NotebookLM](https://notebooklm.google.com/) | AI tool | Free | Asking questions of long call documents, guidelines and FAQs you upload. | Upload the call text, FAQ and scoring criteria, then ask 'Am I eligible if...?' and 'What do reviewers score?' - answers are cited to the source. |
