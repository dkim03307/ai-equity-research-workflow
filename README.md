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

### v1 — Basic Mentor Framework (`prompt.txt`)
A simple prompt that asks AI to explain earnings like a research mentor: 
key drivers, plain-language explanations, and risks to watch.

### v2 — Audit Framework (`prompt-v2-audit-framework.txt`)
A more rigorous version that enforces citation for every metric, 
distinguishes ARR from GAAP revenue, and outputs "N/A" instead of 
guessing when data is missing — reducing hallucination risk.

## Example

Applied to SK Hynix's FY2026 Q1 earnings report, this prompt surfaced 
that revenue growth was driven almost entirely by pricing (ASP), 
not shipment volume — a distinction the headline numbers alone didn't show.

## About Me

Dongwoo (David) Kim — Econ & Finance, Boston College
Twitter: [@dkim03307](https://x.com/dkim03307)
