# 📺 BrightTV Viewership Analytics

A CVM (Customer Value Management) data analytics case study for BrightTV, analysing user
profiles and viewing session data to turn raw behaviour into subscriber growth actions.

<p>
  <img src="https://img.shields.io/badge/status-complete-2E9E6B" alt="status complete">
  <img src="https://img.shields.io/badge/period-Q1%202016-2B1E6B" alt="period Q1 2016">
  <img src="https://img.shields.io/badge/sessions-9%2C995-8A7FE0" alt="sessions 9995">
  <img src="https://img.shields.io/badge/users-4%2C386-F5A623" alt="users 4386">
  <a href="https://tvinsight-hub.lovable.app"><img src="https://img.shields.io/badge/dashboard-live-E8A33D" alt="live dashboard"></a>
</p>

---

## 🎯 The Brief

BrightTV's CEO set a clear objective: **grow the subscription base this financial year.**
This case study answers four questions for the CVM team:

1. What are the main user and usage trends of BrightTV?
2. What factors are associated with consumption?
3. What content should be recommended to lift low-consumption days?
4. What initiatives can further grow BrightTV's user base?

---

## 📺 Live Dashboard

**[tvinsight-hub.lovable.app](https://tvinsight-hub.lovable.app)** — an interactive
dashboard covering subscriber demographics, top channels, and viewing patterns by hour
and day, built from the analysis in this repo.

---

## 🗂️ Repository Contents

```
BrightTV_Analysis/
├── README.md
├── presentation/
│   └── BrightTV_Viewership_Analytics.pptx
├── diagrams/
│   ├── BrightTV_MindMap.png
│   ├── BrightTV_GanttChart.png
│   └── preview/presentation_preview.png
├── notebooks/
│   └── BrightTV_Analysis.ipynb
└── source-data/
    ├── BrightTV_Case_Study.pdf
    └── Bright_TV_-Dataset.xlsx
```

---

## 📊 Presentation

**`presentation/BrightTV_Viewership_Analytics.pptx`** — 18 slides with full speaker notes,
built for a 20-minute CVM walkthrough.

![Presentation preview](diagrams/preview/presentation_preview.png)

---

## 🧠 Mind Map

**`diagrams/BrightTV_MindMap.png`** — the whole case study on one page: business problem,
methodology, trends, consumption factors, the Monday opportunity, and growth initiatives.

![Mind map preview](diagrams/BrightTV_MindMap.png)

---

## 📅 Project Timeline

**`diagrams/BrightTV_GanttChart.png`** — how this case study itself was planned and
delivered, from data cleaning through to final QA (~18 working days).

![Gantt chart preview](diagrams/BrightTV_GanttChart.png)

---

## 📁 Source Data

| File | Description |
|---|---|
| `BrightTV_Case_Study.pdf` | Original case study brief and assignment instructions |
| `Bright_TV_-Dataset.xlsx` | Raw dataset — `User Profiles` (5,375 records) and `Viewership` (10,000 raw sessions) sheets |

---

## 🔑 Key Findings

- 👥 **4,386** unique users generated **9,995** valid sessions (2.28 sessions/user) in Q1 2016
- ♂️ Audience is strongly male-skewed (**84.9%**) and core-aged **25–44** (67.5%)
- 📍 **Gauteng** is the largest observed province, though the audience is national
- 📈 **Friday** (1,673 sessions) is the peak day; **Monday** (956) is the weakest
- 🕔 **17:00 SA time** is the daily peak viewing hour; live sport content leads overall
- 🎵 On Mondays specifically, music/entertainment channels (Channel O, Trace TV) outperform sport

---

## 💡 Recommendations

- Deepen engagement with the **25–44 core audience** via tailored content bundles
- Launch a **female-focused acquisition** campaign to close the gender gap
- Build **referral/advocacy programmes** around highly-engaged younger (18–34) users
- Expand **regional marketing** beyond Gauteng
- Lead growth campaigns with **major sport/event content**
- Run **Monday-specific entertainment programming** and evening-timed engagement pushes

---

## 🔬 Data & Methodology

Two source tables — `User Profiles` (5,375 records) and `Viewership` (10,000 raw session
records, 9,995 after removing exact duplicates) — were joined on `UserID`. All session
timestamps were converted from **UTC to South African time (UTC+2)** before any
day-of-week or hour-of-day analysis. Full detail is in the presentation's *Data &
Methodology* slide.

---

## ⚠️ Caveat

Findings throughout this analysis describe **observed associations** in the data, not
proven causation. Confirming what actually drives consumption (e.g. content genre, time
of day) would require controlled testing such as scheduling or content A/B trials.
