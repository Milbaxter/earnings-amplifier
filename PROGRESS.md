# Earnings Amplifier - Progress Tracker

**Status:** Prototype phase  
**Last updated:** 2026-01-29

---

## Autonomous Work Plan

### Phase 1: Build Manual Prototype (Week 1-2)
**What I can do autonomously:**
- [x] Market research (DONE - 2026-01-29)
- [x] Identify 5 target companies (DONE)
- [ ] **Download Q4 2024 earnings reports** for Posti + Harvia (PDFs, transcripts)
- [ ] Extract key metrics into structured format (JSON/CSV)
- [ ] Build dashboard prototype (choose tech: Observable, Streamlit, or HTML/Tailwind)
- [ ] Create 60-sec video summary script (manually edit or use Remotion)
- [ ] Write plain-English blog post with charts
- [ ] Draft social media content (Twitter thread, LinkedIn post)
- [ ] Package everything into shareable links

**Needs Mili's approval:**
- [ ] Which tech stack to use for dashboard (Observable vs Streamlit vs custom)
- [ ] Which 2 companies to prototype first (Posti + Harvia suggested)
- [ ] Video production approach (manual editing vs Remotion automation)

### Phase 2: IR Team Outreach (Week 3)
**What I can do autonomously:**
- [ ] Find IR contact details for 10 target companies (emails, LinkedIn)
- [ ] Research each company's recent earnings (notes on what makes them interesting)
- [ ] Draft personalized outreach emails (show prototype, ask for feedback)
- [ ] Create tracking spreadsheet for responses
- [ ] Prepare discovery call agenda/questions

**Needs Mili's approval:**
- [ ] Final outreach email copy before sending
- [ ] Which 10 companies to contact
- [ ] Pricing to mention (if any) in initial outreach

### Phase 3: Pilots & Iteration (Week 4-6)
**What I can do autonomously:**
- [ ] Build Q1 2025 earnings content for 3 pilot customers
- [ ] Track engagement metrics (dashboard views, video plays, social shares)
- [ ] Collect feedback and iterate on product
- [ ] Document automation workflows (what can be scripted vs manual)
- [ ] Research pricing models (SaaS, usage-based, enterprise)

**Needs Mili's approval:**
- [ ] Which 3 companies to pilot with
- [ ] Pilot terms (free for Q1, paid after?)
- [ ] Conversion strategy (free → paid)

---

## Work Log

### 2026-01-29
- ✅ Created initial README with vision, tech stack, deliverables
- ✅ Completed market research (Nordic small-caps, TAM, pricing strategy)
- ✅ Identified 5 Tier 1 targets (Posti, Aspo, Nurminen, Harvia, GRK)
- ✅ GitHub repo created and pushed

### 2026-01-30
- ✅ **Downloaded Posti Group Q4 2024 Financial Statements Bulletin (PDF)**
  - Source: https://www.posti.com/en/financial_statements_bulletin_2024
  - File: parsing/Posti_Q4_2024_Financial_Statements_Bulletin.pdf (1.5MB)
- ✅ **Extracted comprehensive metrics to JSON**
  - File: parsing/posti_q4_2024_metrics.json
  - Q4 2024: Net sales EUR 403.6M (-6.1% YoY), Adj EBITDA EUR 54.2M (13.4% margin)
  - FY 2024: Net sales EUR 1,521.4M (-4.1% YoY), Adj EBITDA EUR 207.6M (13.6% margin, +5% YoY)
  - Key story: Profitability improved despite revenue decline (10 consecutive years of margin improvement)
  - Recommerce volumes quintupled (secondhand marketplace growth)
  - EUR 150M extra dividend (December 2024)

- ✅ **Extracted Harvia Q4 2024 earnings metrics to JSON**
  - File: parsing/harvia_q4_2024_metrics.json
  - Q4 2024: Revenue EUR 51.0M (+29.3% YoY, all-time record), Adj EBIT EUR 8.7M (17.1% margin)
  - FY 2024: Revenue EUR 175.2M (+16.4% YoY), Adj EBIT EUR 37.1M (21.2% margin, met target)
  - Key story: Record growth driven by North America wellness boom, returned to growth after 2 years decline
  - ThermaSol acquisition (July 2024) strengthens steam/digital capabilities
  - Strong cash generation: 140% cash conversion in Q4
  - 75th anniversary in 2025

- ✅ **Drafted 60-sec video script for Harvia Q4 2024 earnings**
  - File: content/harvia-q4-2024-video-script.md
  - Professional, fast-paced earnings summary (Bloomberg Quicktake style)
  - Key metrics: EUR 51M revenue (+29% YoY record), North America boom, 75th anniversary
  - Includes: Full voiceover script, visual storyboard, production options
  - Revenue model: EUR 2-3K per video, EUR 6-8K annual (4 quarterly + 1 annual)
  - Use cases: Social media, IR page embeds, earnings calls, media outreach
  - Next: Produce prototype (2-3 hours) → demo to IR teams → convert to paid

- ✅ **Found IR contact emails for 5 target companies**
  - File: outreach/ir-contact-list.md
  - Harvia: Matias Järnefelt (CEO), Ari Vesterinen (CFO), ir@harvia.fi
  - Posti: Antti Jääskeläinen (CEO), Timo Karppinen (CFO), Marja Mäkinen (Head of IR)
  - Aspo: Rolf Jansson (CEO), Erkka Repo (CFO) - both direct IR contacts
  - Nurminen: Olli Pohjanvirta (CEO & Chairman)
  - GRK Infra: Mika Mäenpää (CEO), Markku Puolanne (CFO)
  - Prioritized: Harvia (40-50% close prob), Aspo (35-45%), GRK (30-40%)
  - Expected revenue: EUR 12-14K ARR from first batch (36% weighted close rate)

### Next Heartbeat Tasks (Pick One)
1. **Draft IR outreach email template** (Swedish/Finnish + English, offer free prototype)
2. **Produce Harvia Q4 2024 video prototype** (60 sec, demo tool for sales)
3. Build simple dashboard prototype structure for Posti (HTML/Tailwind template)
4. Find LinkedIn profiles for all 10 CEOs/CFOs (networking, warm intros)

---

## Blockers & Questions for Mili

**Tech Stack Decision Needed:**
- **Dashboard:** Observable (easy embeds) vs Streamlit (Python-based) vs Custom HTML/React?
- **Video:** Remotion (programmatic, scalable) vs manual editing (higher quality)?
- **Recommendation:** Start with Observable + manual video editing (fastest to ship prototype)

**Prototype Priority:**
- Should I build for Posti or Harvia first? (Or both simultaneously?)
- **Recommendation:** Posti first (more data-heavy, bigger company, harder problem)

---

## Metrics to Track
- [ ] Prototypes built
- [ ] IR teams contacted
- [ ] Reply rate
- [ ] Pilot customers signed
- [ ] Engagement metrics (dashboard views, video plays)
- [ ] Conversion to paid
