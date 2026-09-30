# Prompts from the talk

[Back to the list](../README.md)

Copy a prompt, fill in the [brackets], and paste it into any free AI platform. Never paste patient identifiers. Check every fact and citation the model gives you.

## 1. Idea / Goal setting

Tool: [Gemini Deep Research](https://gemini.google.com)

```text
Act as an epidemiologist who is hostile to weak generalizations.

I work in [country / hospital type]. Here is a famous paper in my field: [title].

1. Who was actually enrolled?
2. Which group I treat was missing?
3. What would a repeat study in my setting have to change?

If you do not know, say so. Do not invent citations; list every claim I must check in PubMed.
```

## 2. Literature review

Tool: [Gemini Notebook](https://notebook.google)

```text
Act as a medical researcher summarizing literature for clinical application.

Summarize these articles: key clinical takeaways and practice-changing findings. Critique the strengths and weaknesses of the methodology.

Then: where is the sample skewed (country, ethnicity, sex, age, hospital type)? How would the outcome move in patients in [country]?
```

## 3. Data collection

Tool: [Claude](https://claude.ai)

```text
Act as a skeptical ethics-committee chair and Reviewer #2.

Here is my one-page protocol: [paste, no patient data].

List three design flaws I will not be able to hide after the first participant: allocation, blinding, sample size, endpoint, generalizability to [country]. Give three fixes that cost little. Do not praise the idea.

Then draft the consent form in [language] at a 6th-grade reading level.
```

## 4. Data analysis

Tool: [Claude Code](https://claude.com/product/claude-code)

```text
Here is a de-identified table, data.csv, with columns [age, sex, arm, outcome], and my pre-specified hypothesis: [H].

Write and run a Python script that performs [test], checks its assumptions, and prints the result with a 95% CI. Save the script so I can rerun it.

Explain the clinical meaning of the printed number. Do not invent a result.
```

## 5. Paper writing

Tool: [ChatGPT](https://chatgpt.com)

```text
Act as a medical editor. Improve this text for clarity, tone, and structure without losing medical accuracy.

Keep every number, citation and claim unchanged. List each change you made in a table.

[paste one section]
```

## Fundraising

Tool: [Global Health Funding Atlas](https://danissimov.github.io/global-health-funding-opportunities/)

```text
You are a research-funding scout for a [role] in [country].

Start from this fact-checked list: https://github.com/danissimov/global-health-funding-opportunities
Read countries/[country].md first, then check details in data/funding_opportunities.csv.

Project: [one sentence]. Budget: [range].

Shortlist open or expected grants, fellowships and free compute I could lead or join, then search beyond the list. For each: official URL, amount, eligibility for my country’s World Bank income group, next deadline.

Write “not verified” instead of guessing.
```

The full version, with a country picker, is Prompt 1 in the [interactive atlas](https://danissimov.github.io/global-health-funding-opportunities/#prompt).

## Ethical AI use

Tool: [Ollama (local models)](https://ollama.com)

```text
Rewrite this case note so I can ask a methods question about it.

Remove names, dates, record numbers, villages and any rare detail that could identify the patient. Replace dates with intervals (day 0, day 3). Keep the clinical facts.

[paste note, only into a local model]
```

## Critical thinking

Tool: [Perplexity](https://www.perplexity.ai)

```text
Of these two hypotheses, which is more solid?
A: [..]
B: [..]

What single piece of evidence would reverse your answer? Cite it.

Then: what is the worst version of my conclusion, and how do you know it is not that?
```
## Prompt card: blind spot (long version)

```text
Act as an epidemiologist who is hostile to weak generalizations. I work in [country / hospital type]. Here is a paper I am tempted to apply: [title or paste]. (1) Who was actually enrolled? (2) Which skew — country, ethnicity, sex, age, facility — would move the result in my patients? (3) Of these two next studies, which is more solid: A, a repeat of their protocol in my setting; B, [your alternative]? What single fact would reverse you? If you do not know, say so. Do not invent citations; list claims I must check in PubMed.
```

## Prompt card: protocol (long version)

```text
Act as a skeptical ethics-committee chair and Reviewer #2. Here is my one-page protocol: [paste]. List three design flaws I will not be able to hide after the first participant, mapped to allocation, blinding, sample size, endpoint, and generalizability to [country]. Give three fixes that cost little. Of my design and [a named published trial], which is more solid, and why? Do not praise the idea.
```
