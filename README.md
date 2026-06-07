# AI Australia 2030 — Interactive Economic Forecast

**Course:** ECON1626 Economics of Artificial Intelligence  
**Institution:** RMIT University  
**Assessment:** Interactive Web Essay (Assessment 3)  
**Submission Date:** June 2025
**Student Name:** Junrong Niu
**Student ID:** s4034185

---

## Overview

This repository contains an interactive web essay forecasting how artificial intelligence will reshape the Australian economy by 2027–2030. The project combines rigorous economic analysis with data-driven visualisations, interactive scenario modelling, and a policy decision tree — all presented as a public HTML website.

**Core argument:** By 2030, AI could contribute **A$115 billion annually** to Australia's economy, with the potential to reach **A$235 billion** under optimal policy settings — or fall to just **A$85 billion** without decisive action. The choices made by governments, businesses, and educational institutions over the next five years will determine which path Australia takes.

**Live site:** [View the interactive forecast on GitHub Pages](https://YOUR_USERNAME.github.io/econ1626-ai-future-forecast/)

---

## How to Navigate This Repository

| File | Description |
|------|-------------|
| `forecast.html` | **Main essay file** — the interactive web essay. Open in any browser or view via GitHub Pages. |
| `README.md` | This file — project overview and navigation guide. |
| `.nojekyll` | Ensures GitHub Pages serves the site correctly. |

### Viewing the Essay Locally

Simply open `forecast.html` in any modern web browser:

```bash
# Option 1: Double-click the file
# Option 2: Use a local server for best experience
cd /path/to/this/repo
python3 -m http.server 8000
# Then open http://localhost:8000/forecast.html
```

No build step or dependencies required — the essay is fully self-contained.

---

## Essay Structure

The interactive essay is organised into eight sections:

1. **Hero — The $115 Billion AI Question**  
   Opening statement with animated particle visualisation. Frames the central economic question.

2. **Thesis Statement**  
   Core argument: A$115B annual potential, policy-dependent outcomes, A$150B at risk if Australia delays action.

3. **Economic Channels** (3 sub-sections)  
   - **Productivity:** 44% of task hours automatable, A$80B annual gains, industry-level bar chart  
   - **Employment:** 3.5–6.5M FTE affected, toggle between "jobs at risk" and "jobs created" views  
   - **Industry Structure:** SMEs drive 55% of growth but face adoption barriers, pie chart of sectoral distribution

4. **Scenario Explorer** (Interactive Simulator)  
   Three preset scenarios (Baseline / High Growth / Stagnation) with four adjustable sliders: public AI investment, regulatory stringency, workforce training rate, and SME adoption support. Displays real-time projections for GDP impact, jobs created, productivity gain, and risk level.

5. **Policy Playbook** (Interactive Decision Tree)  
   Three branching policy pathways: accelerate adoption, build sovereign capability, or protect workers & regulate. Each branch explores sector-specific strategies with cost-benefit analysis and KPIs.

6. **Methods & Data**  
   Data sources, modelling approach (Cobb-Douglas production function with AI augmentation), AI tools disclosure, and key limitations.

7. **References**  
   12 cited sources from government, academic, and industry bodies.

8. **Footer**  
   Course attribution and submission details.

---

## Data Sources & Methodology

### Primary Sources

- **Microsoft & Tech Council of Australia (2023).** *Australia's Generative AI Opportunity* — Mandala analysis.
- **ATSE (2025).** *Unleashing Growth: Australia's AI Investment Blueprint* — ACIL Allen analysis.
- **OpenAI (2025).** *AI in Australia: Economic Blueprint*.
- **McKinsey & Company (2020).** *Australia's Automation Opportunity*.
- **Productivity Commission (2025).** *Harnessing Data and Digital Technology* (Inquiry Report).
- **OECD (2024).** *AI Adoption by Small and Medium-Sized Enterprises*.
- **Australian Government (2024).** *National Framework for the Assurance of AI in Government*.
- **CSIRO Data61 (2019).** *Australia's AI Ethics Framework*.
- **Australian Government (2024).** *Voluntary AI Safety Standard*.
- **ANAO (2025).** *Governance of AI at the Australian Taxation Office*.
- **AIIA (2025).** *Australia's AI Opportunities Report*.
- **IBM (2025).** *Global AI Adoption Index*.

### Modelling Approach

The scenario simulator uses a simplified Cobb-Douglas production function augmented with AI capital and labour variables:

- AI adoption follows an S-curve with inflection around 2027
- Productivity gains of 35% for fully-augmented tasks
- Labour transition: 38% value capture (Year 1), 83% (Year 2)
- GDP elasticity: 0.5%–3.5% annual labour productivity growth (OECD estimates)

**Important:** The scenario model is built using simplified economic relationships for **pedagogical purposes** and should not be interpreted as a formal econometric forecast.

---

## AI Tools Disclosure

This interactive essay was developed with assistance from AI-powered development tools, in accordance with RMIT's academic integrity policy and the assessment guidelines permitting unrestricted AI use.

**How AI was used:**
- Code generation and structuring (HTML, CSS, JavaScript)
- Visualisation design (particle system, charts, scenario simulator)
- Research synthesis and data organisation

**What was not AI-generated:**
- All economic data and statistics are sourced from the peer-reviewed and government publications listed in the References section
- The argument structure and policy analysis reflect original critical engagement with the sources
- The scenario modelling logic was designed based on economic principles covered in ECON1626

---

## Assessment Alignment

| Learning Outcome | How this essay addresses it |
|------------------|----------------------------|
| **CLO1:** Economic theory of AI proliferation | Productivity channels (automation dividend, task-level analysis, S-curve adoption), Cobb-Douglas augmentation |
| **CLO3:** Ethics, social & regulatory dimensions | Policy decision tree weighing enablement vs. regulation, worker protection pathways, sovereign capability trade-offs |
| **CLO4:** Evidence-based strategic responses | Scenario simulator with quantified outcomes, policy playbook with KPIs and risk assessments |
| **CLO5:** Communication & interdisciplinary knowledge | Interactive visualisations, accessible narrative, data-source transparency, uncertainty disclosure |
| **AoL4:** Digital proficiency | Interactive HTML5 Canvas, CSS3 animations, real-time scenario modelling, responsive design |
| **AoL6:** Critical engagement | Multiple scenario analysis, structural uncertainty reflection, model limitations clearly stated |

---

## Technical Implementation

- **Frontend:** Single-file HTML5 with embedded CSS3 and vanilla JavaScript
- **Visualisations:** HTML5 Canvas (particle system), SVG (pie chart), CSS animations (bar chart)
- **Interactivity:** Interactive scenario simulator, toggle views, collapsible decision tree
- **Typography:** Instrument Serif (display), Inter (body) — loaded from Google Fonts
- **Accessibility:** Keyboard navigation, focus-visible states, `prefers-reduced-motion` support

---

## License

This project was created for academic assessment purposes at RMIT University.
