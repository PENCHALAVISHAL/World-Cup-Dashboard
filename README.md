# ⚽ FIFA World Cup Storytelling Dashboard

> An Excel-based analytical dashboard examining 50+ years of World Cup match data to uncover how tournament structure shapes goal-scoring patterns, win methods, host advantage, and pressure performance across stages.

---

##  Project Overview

Built a structured, four-part analysis of FIFA World Cup matches (1974–present) using Excel — covering goal trends, win method distribution, host advantage, and high-pressure match behavior. All analysis is consolidated into a single storytelling dashboard designed for clarity and narrative flow.

---

##  The Four Questions I Set Out to Answer

**1. Do goals dry up as the stakes get higher?**
Analyzed average goals per match across every tournament stage — from group stage through to the final — to see whether scoring patterns actually shift as pressure mounts.

**2. How does the way a match is won change by stage?**
Mapped the distribution of Normal wins, Extra Time, Golden Goals, and Penalty shootouts across each stage to understand when matches stop being decided in 90 minutes.

**3. Does hosting a World Cup actually give you an edge — and does it hold in knockout rounds?**
Compared host vs. non-host team performance across stages to see whether home advantage is real, and more importantly, whether it survives the elimination rounds.

**4. Are high-pressure matches structurally different?**
Classified matches into High Pressure (Quarter-Finals onward, StageOrder ≥ 7) and Low Pressure (earlier rounds), then compared win method distributions to find out if the finals really do play out differently.

---

## 🗂️ File Structure

The workbook contains a raw data sheet (`fact_worldcup_matches`, 900+ matches), four dedicated analysis sheets, supporting pivot tables, and a consolidated dashboard — all structured for transparency and reproducibility.

---

## 🔧 What I Built

- **Data Engineering in Excel** — Used structured table references and nested `IF`/`SEARCH` formulas to engineer new columns like `Win_Type` (categorizing win conditions into four clean labels) and `Stage_Group` (High Pressure vs. Low Pressure), keeping the logic transparent and auditable.

- **Pivot Table Analysis** — Built four separate pivot tables, each answering a distinct analytical question, with calculated fields for percentage breakdowns and averages.

- **Storytelling Dashboard** — Consolidated all four analyses into a single dashboard sheet designed to guide the viewer through a logical narrative: goals → win methods → host advantage → pressure.

---

##  Key Findings

- Goals per match don't drop as dramatically in knockout stages as you might expect — the group stage is actually among the lower-scoring phases in some editions.
- Penalty shootouts are heavily concentrated in the Quarter-Finals and Semi-Finals, not the Final itself — suggesting the Final often gets decided in normal or extra time.
- Host advantage appears meaningful in group stage matches but becomes harder to see once the tournament reaches the knockout rounds.

---

##  Tools Used

- **Microsoft Excel** — Pivot Tables, Structured Table References, Nested Formulas, Dashboard Design

---

##  How to Use It

1. Download and open `FIFA_World_Cup_Storytelling_Dashboard.xlsx`
2. Start on the `DASHBOARD` sheet for the full picture
3. Drill into individual analysis sheets (`01_` through `04_`) to explore the underlying pivot data
4. The `fact_worldcup_matches` sheet contains the full raw dataset with all engineered columns

---

## 👤 About This Project

This was a self-initiated project built to practice translating raw sports data into structured, story-driven analysis — the kind of work that turns numbers into something people actually want to read. It's part of my broader interest in using data to answer questions that feel intuitive but rarely get examined rigorously.
