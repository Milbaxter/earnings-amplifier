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

### Next Heartbeat Tasks (Pick One)
1. **Download Harvia Q4 2024 earnings report** and extract metrics to JSON
2. Find IR contact emails for 5 target companies (LinkedIn, company websites)
3. Build simple dashboard prototype structure for Posti (HTML/Tailwind template)
4. Draft 60-sec video script for Posti Q4 2024 earnings

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
