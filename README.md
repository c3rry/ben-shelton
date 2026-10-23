# Why Ben Shelton is the Next Big Thing: US Open Empirical Analysis

This repository contains a comprehensive, reproducible data science analysis and Jupyter Notebook investigating why **Ben Shelton** is the next big superstar in men's tennis, comparing him to all modern US Open Champions (2000–2024), and analyzing his **historic breakthrough run to the 2026 US Open Final**.

---

## 📓 The Jupyter Notebook
Open and explore:
- **[`ben_shelton_us_open_analysis.ipynb`](./ben_shelton_us_open_analysis.ipynb)**

The notebook is **fully pre-executed** with all 11 high-resolution figures, statistical tables, radar profiles, and comparative models pre-rendered.

---

## 📊 Open-Source Datasets Used
All datasets are sourced from open-source repositories and cached locally in `data/` with automatic remote fallback:
1. **Historical US Open Matches (2000–2024)**: Sourced from Jeff Sackmann's ATP Tour Archive (`tennis_atp`), providing complete match-level box scores, service statistics, break points, and hold percentages.
2. **Ben Shelton Career Matches (2022–2026)**: Full tour-level records tracking Shelton's trajectory across hard, clay, and grass surfaces.
3. **2023 US Open Point Telemetry**: Point-by-point data tracking radar serve velocity (MPH), rally lengths, break point moments, and court placement (`pt-by-pt-at-grandslams`).
4. **2026 US Open Championship Run**: Complete round-by-round logs, match durations, break point saves, and telemetry from his run to the Men's Singles Final.

---

## 🏆 Key Findings from the Analysis

| Metric | Ben Shelton (US Open) | Modern US Open Champions Benchmark | Key Comparison / Takeaway |
| :--- | :---: | :---: | :--- |
| **Peak 1st Serve Speed** | **149.0 MPH** | ~135–142 MPH (Field Avg: 104.5) | Fastest serve of 2023 US Open (hit twice in one game) |
| **Peak 2nd Serve Speed** | **143.0 MPH** | ~100–108 MPH (Field Avg: 85.7) | Faster than 98% of the field's *first* serves |
| **US Open Hold Rate** | **86.8%** | 84.8% (Cohort Average) | Out-holds Nadal (86.0%), Djokovic (86.5%), Alcaraz (82.8%), Sinner (82.3%) |
| **Aces per Match** | **15.1** | 9.3 (Cohort Average) | #2 in 21st century US Open history, behind only Andy Roddick (15.6) |
| **Break Points Saved %** | **67.1% – 72.5%** | 64.6% (Cohort Average) | Elite clutch defense alongside Roger Federer (67.9%) & Roddick (69.2%) |
| **Duress Serve Speed** | **121.0 MPH** (+2.8 MPH) | Tendency across field is to drop speed | Shelton aggressively dials *up* velocity on break points faced |
| **Quick-Strike (0–4) Win %** | **69.0%** | Dominant hard court archetype | 76% of his service points finish in ≤4 shots |
| **Age 20 Semifinalist** | **20.9 Years** | Only 7 men since 2000 | 100% of previous 6 became World No. 1 and Major Champions |
| **2026 US Open Run** | **Finalist (Runner-Up)** | No. 8 Seed to Final | 81 aces, defeated Carlos Alcaraz at 3:33 AM; climbed to World No. 5 |

---

## 🌙 The 2026 US Open Final Run: Round-by-Round Gauntlet
- **R128**: def. Tallon Griekspoor (1–6, 6–1, 7–6(3), 6–2) — 14 aces
- **R64**: def. Hubert Hurkacz (6–3, 5–7, 7–6(3), 7–5) — 16 aces, 71% first serves
- **R32**: def. Denis Shapovalov (7–6(3), 6–7(5), 6–3, 6–4) — 15 aces
- **R16**: def. Stefanos Tsitsipas (6–2, 6–3, 6–4) — Straight-sets clinic, 0 breaks conceded
- **QF**: def. **Carlos Alcaraz** (6–7(5), 6–1, 6–3, 1–6, 7–6(7)) — **4h 28m epic finishing at 3:33 AM** (latest match in US Open history). Saved 8 of 11 break points (73%) with only 2 double faults.
- **SF**: def. Frances Tiafoe (4–6, 6–3, 6–3, 7–5) — All-American primetime battle on Ashe
- **F**: lost to Alexander Zverev (3–6, 6–7(2), 7–5, 2–6) — 4-set battle; climbed to career-high **World No. 5**

---

## 🛠️ How to Run
Ensure you have Python with `pandas`, `numpy`, `matplotlib`, and `scipy`:
```bash
jupyter notebook ben_shelton_us_open_analysis.ipynb
```
or open directly in VS Code / Cursor / Google Colab.
