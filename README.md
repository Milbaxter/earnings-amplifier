# Earnings Amplifier

**Automate quarterly earnings into dashboards, videos, blogs, and media-ready content**

## Vision

Transform boring earnings calls into engaging, digestible content that reaches investors, media, and stakeholders. Make public company IR digitally native, meme-worthy, and accessible.

## Problem

- Quarterly earnings are locked in PDFs, analyst calls, and dense financials
- Retail investors, journalists, and stakeholders don't engage with traditional formats
- IR teams lack tools to turn data into modern content (short videos, dashboards, social posts)
- Public companies lose narrative control — only analysts and financial media tell their story

## Solution

**Automated earnings content pipeline:**
1. **Ingest:** Scrape/parse quarterly earnings PDFs, transcripts, and filings
2. **Transform:** Auto-generate dashboards, key metrics, visualizations
3. **Distribute:** Create short-form videos, blog posts, social content, memes
4. **Amplify:** Pitch media, auto-distribute to investors, push to social channels

### Deliverables per Quarter

- **Live dashboard:** Key metrics, trends, YoY/QoQ comparisons (embeddable)
- **Short-form video:** 60-90 sec highlight reel with voiceover
- **Blog post:** Plain-English summary with charts
- **Social content:** Twitter threads, LinkedIn posts, memes
- **Media outreach:** Auto-pitch to journalists with pre-written summaries

## Revenue Model

- **SaaS:** $2-5K/month per company (quarterly earnings automation)
- **Usage-based:** Add-ons for video production, media distribution
- **Enterprise:** $50-100K/year for full IR automation + white-glove service

## Target Customers

- **Nordic public companies** (small/mid-cap, <€1B market cap)
- **IR agencies** (white-label offering)
- **Family-owned businesses going public** (IPO prep, modern storytelling)

## Tech Stack (Initial)

- **Parsing:** Python (PyPDF2, BeautifulSoup for filings/transcripts)
- **Dashboards:** Observable, Streamlit, or custom React app
- **Video:** Remotion (programmatic video generation)
- **Content:** GPT-4 for blog/social copy
- **Distribution:** APIs for Twitter, LinkedIn, media databases

## Validation Plan

1. **Pick 5 Nordic public companies** (boring industries: logistics, manufacturing, utilities)
2. **Manually create Earnings Amplifier output** for their last earnings call
3. **Reach out to IR teams:** "We built this for free. Would you pay for it quarterly?"
4. **Show, don't tell:** Send dashboard link + video sample
5. **Track interest:** Pricing, objections, feature requests

## Next Steps

- [ ] Identify 5 target Nordic companies (recent earnings releases)
- [ ] Download their Q4 2024 earnings PDFs/transcripts
- [ ] Build manual v1 dashboard + video for 1 company
- [ ] Draft outreach email to IR teams
- [ ] Send samples and gauge interest
- [ ] Iterate based on feedback

## Repository Structure

```
/prototypes        # Manual v1 builds (dashboards, videos)
/parsing           # Scripts to extract earnings data
/content           # Templates for blogs, social posts
/outreach          # Email templates, target companies
/docs              # Business model, pricing, roadmap
```

---

**Status:** Prototype phase  
**Location:** Helsinki, Finland  
**Founded:** 2026
