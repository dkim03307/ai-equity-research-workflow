# AI Equity Research Workflow

A prompt-based workflow that uses AI to extract key financial metrics 
from company earnings documents (10-K, 10-Q, earnings releases) 
quickly and accurately.

## Why I Built This
Default AI chatbots often hallucinate numbers or confuse concepts 
like ARR with actual GAAP revenue when analyzing financial documents.
This prompt is designed to prevent that by enforcing:
- Exact page/section citations for every metric
- Outputting "N/A" instead of guessing when data is absent
- Clear distinction between ARR and actual GAAP revenue

## How to Use
1. Copy the contents of `prompt.txt`
2. Paste it into an AI chatbot (Claude, ChatGPT, etc.)
3. Attach the earnings document (PDF) you want to analyze
4. The AI returns key metrics in a table, each mapped to its source

## Example
Applying this prompt to SK Hynix's FY2026 Q1 earnings report 
clearly separated GAAP revenue from ASP (average selling price) 
contribution — revealing the real driver behind the headline numbers.

## About Me
Dongwoo (David) Kim — Econ & Finance, Boston College
Twitter: [@dkim03307](https://x.com/dkim03307)
