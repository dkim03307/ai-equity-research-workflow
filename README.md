# AI Equity Research Workflow

A prompt-based workflow that uses AI to break down company earnings 
reports into clear, digestible insights.

## Why I Built This

Reading through dense earnings documents takes time, and it's easy 
to miss the real story behind headline numbers. This prompt asks 
AI to act as a research mentor — pulling out the key revenue drivers, 
explaining technical terms simply, and flagging risks to watch, 
all in clear bullet points.

## How to Use

1. Copy the contents of `prompt.txt`
2. Paste it into an AI chatbot (Claude, ChatGPT, etc.)
3. Attach the earnings document you want to analyze
4. The AI returns a structured breakdown: key drivers, plain-language 
   explanations, and risks to watch

## Prompts

### v1 — Basic Mentor Framework (`prompt-v1-basic-mentor.txt`)
A simple prompt that asks AI to explain earnings like a research mentor: 
key drivers, plain-language explanations, and risks to watch.

### v2 — Audit Framework (`prompt-v2-audit-framework.txt`)
A more rigorous version that enforces citation for every metric, 
distinguishes ARR from GAAP revenue, and outputs "N/A" instead of 
guessing when data is missing — reducing hallucination risk.

### v3 — Devil's Advocate (`prompt-v3-devils-advocate.txt`)
Forces AI to argue against a stated bull thesis using only the 
source document — surfaces risks a purely descriptive summary 
would miss (e.g. margin guidance trends, currency effects, 
technology mix).

## Example

**v1 (SK Hynix, FY2026 Q1):** Surfaced that revenue growth was driven 
almost entirely by pricing (ASP), not shipment volume — a distinction 
the headline numbers alone didn't show.

**v2 (Tesla, Q1 2026):** Applied the audit framework to Tesla's Q1 2026 
filing — AI extracted GAAP revenue ($22,387M) with exact page citation, 
correctly flagged "N/A" for ARR since Tesla doesn't disclose that metric 
(instead of guessing), and cited Gross Margin (21.1%) to its exact source. 
Every figure mapped to a page reference, zero extrapolation.

**v3 (TSMC, Q2 2026):** Forced to argue against the bull thesis, AI found 
that margin guidance was pointing down despite "strong demand" language, 
and that a 2.3-point gap between local-currency and USD growth was 
masking the true growth rate.

## About Me

Dongwoo (David) Kim — Econ & Finance, Boston College
Twitter: [@dkim03307](https://x.com/dkim03307)
