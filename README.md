# Energy Brain — Landing Page (HTML + CSS Only)

Premium landing page for Energy Brain hackathon project — control room at dusk design.

**Design tokens:**
- Ink 950 #0D1210, Bone 50 #F6F3EC, Amber #E0A73A (10% accent), Moss #5F8F6B, Teal #3E7C86
- Typography: Fraunces serif headings, Instrument Sans UI, JetBrains Mono numbers
- No JS, no placeholder, every button does something

**Sections:**
- Hero with KPI strip (Saved today, CO₂, Peak, Forecast error)
- Decision loop: Forecast → Uncertainty → Optimize → Act → Explain → Measure
- 7 modules (Solar, Demand, VPP, Grid Copilot, Panels, Ledger, Regions)
- Cross-border regions BD/DE/US with tariffs
- Premium checklist 12 items
- Trust + Impact KPIs
- Tech stack + CTA

**Run locally:**
```bash
# Just open index.html or
npx serve .
# or
python -m http.server 8080
```

**Deploy to Render (Static Site):**
- Root Directory: `.` or `landing` (this repo root contains index.html)
- Publish Directory: `.`
- Build Command: empty (no build)
- Or use `render.yaml` blueprint included

**Links:**
- Main App: https://hackathon-energy-brain-1.onrender.com
- API Docs: https://hackathon-energy-brain-1.onrender.com/docs
- Main Repo: https://github.com/tusher466/Hackathon-Energy-Brain

Built with pure HTML + CSS, no frameworks, no lorem ipsum.
