# 🎮 Roblox Game Analytics Case Study
**Optimizing Player Engagement & Game Economy for a Roblox-Inspired Experience**

---

## 📌 Objective
This project simulates the work of a **Data Analyst** at Sawhorse Productions.  
I analyzed a mock Roblox-style game dataset to:
- Identify **player engagement drop-offs**
- Balance the **in-game economy**
- Improve **monetization** without compromising player experience

---

## 📌 1. Extracting & Interpreting Player Data
- Queried mock player event data (logins, level progression, transactions) using **SQL**.

```sql
SELECT level_reached, COUNT(player_id) AS players,
       AVG(session_length) AS avg_playtime
FROM game_sessions
GROUP BY level_reached;
```
- Findings:
- **40% drop-off** between Level 3 → Level 4
- **25% of players** were hoarding currency, stalling the game economy
- **Tools:** SQL + Tableau  
✅ **Impact:** Clear insight into where and why players disengaged.

---

## 📌 Identifying & Solving Game Design Issues

### Issues Found:
- Currency hoarding  
- Level skipping exploit via teleport mechanic  

### ✅ Solutions Proposed:
- Added **currency sink** (limited-time cosmetic shop + energy boosts)  
- Patched teleport exploit & rebalanced rewards in Levels 2–4  

✅ **Expected Outcome:** More stable economy & smoother level progression.

---

## 📌 Optimizing Engagement via A/B Testing

Designed an **A/B test** for onboarding flow:

| Group A (Control) | Group B (Variant) |
|-------------------|-------------------|
| Standard tutorial | Shorter, interactive tutorial + early rewards |

### ✅ Results:
- +18% **Day 1 retention**
- +12% **increase in in-game purchases**

✅ **Tools:** Python (Pandas for mock analysis) + Tableau dashboards

---

## 📌 Supporting Live-Service Updates

- Tracked **player sentiment** post-updates via dashboards.  
- Found **spikes** after limited-time events but **drop-offs** when rewards expired.  

✅ **Strategy Proposed:** Weekly **mini-events** to keep engagement steady.

---

## 📌 Monetization & Game Economy Balancing

### Findings:
- 70% of revenue came from **5% of players** (“whales”)  
- Majority of players didn’t spend  

### ✅ Recommendations:
- Add **microtransactions <$1** for casual players  
- Introduce **daily “free spin”** to drive engagement & purchases  

---

## 📌 Dashboards & Insights Delivery

Built a **Tableau dashboard** to track:
- Player retention (D1, D7, D30)
- ARPU & ARPPU
- Level drop-off points
- Currency inflow/outflow

### ✅ Deliverables:
- Tableau Dashboard *(mock dataset)*
- A/B Test Python Notebook *(GitHub link)*

---

## ✅ Key Takeaways

- **SQL + Tableau:** Built end-to-end analytics pipeline.  
- **Game Economy Insight:** Balanced rewards & currency sinks.  
- **Engagement Focus:** Identified drop-offs, ran A/B tests, proposed live-service loops.  
- **Monetization Strategy:** Converted non-spenders via microtransactions & incentives.  
- **Cross-Functional Thinking:** Framed insights for designers, developers & marketing teams.

---

## 📌 Links

- [🔗 Tableau Dashboard](#) *(upload to Tableau Public)*  
- [📘 A/B Test Notebook](#) *(link to .ipynb on GitHub)*  

---

## 🏷️ Tools & Skills Used

`SQL` `Tableau` `Python (Pandas)` `A/B Testing` `Game Analytics` `Monetization Strategy`

---
