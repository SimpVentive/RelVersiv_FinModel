# RelVersiv VRx · Financial Stress Tester

Interactive 5-year financial model for the RelVersiv VRx pain management platform. Drag sliders to stress-test revenue, costs, and valuation in real time.

## Live Model

**[→ Open Stress Tester](https://YOUR-USERNAME.github.io/relversiv-model/)**

*(After you deploy, replace the link above with your actual GitHub Pages URL)*

---

## What it does

- **7 revenue streams** — Hospital & Physio Therapy, Corporate Prognosis, POD Sessions, Home Rental, POD Device Rental (PaaS)
- **Full P&L** across Y1–Y5 with radio button year selector
- **DCF + Revenue Multiple valuation** with blended EV and post-money figure
- **POD Opex modelling** — asset-based (20%/yr) + per-session (₹75) — both adjustable
- **Editable salaries** per role with +/− controls
- **Export to Excel** — Parameters, P&L, and Valuation tabs in one click
- **Detailed Help tab** — all formulas, glossary, and slider reference

## Base model output (default settings)

| Year | Revenue | EBITDA | EBIT | FCF |
|------|--------:|-------:|-----:|----:|
| Y1 | ₹5.38 Cr | ₹(2.45) Cr | ₹(2.79) Cr | ₹(4.04) Cr |
| Y2 | ₹11.11 Cr | ₹(0.56) Cr | ₹(1.07) Cr | ₹(1.39) Cr |
| Y3 | ₹23.92 Cr | ₹4.53 Cr | ₹3.43 Cr | ₹1.56 Cr |
| Y4 | ₹37.88 Cr | ₹10.19 Cr | ₹8.79 Cr | ₹8.55 Cr |
| Y5 | ₹49.96 Cr | ₹15.16 Cr | ₹13.74 Cr | ₹15.04 Cr |

**Post-Money Valuation: ₹41.63 Cr** (10x revenue exit ÷ 12x VC return)

---

## How to deploy on GitHub Pages (5 minutes)

1. Go to [github.com](https://github.com) → **New repository**
2. Name it `relversiv-model` → set to **Public** → click **Create repository**
3. Upload `index.html` and `README.md` (drag and drop into the repo page)
4. Go to **Settings → Pages**
5. Under *Source*, select **Deploy from branch → main → / (root)** → Save
6. Wait ~60 seconds → your live URL:
   ```
   https://YOUR-USERNAME.github.io/relversiv-model/
   ```
7. Update the link at the top of this README and share!

---

## Files

```
relversiv-model/
├── index.html      ← Complete stress tester (self-contained, no dependencies)
└── README.md       ← This file
```

No build step. No npm. No server. Runs entirely in the browser from a single HTML file.

---

*Verified against RelVersiv_Model_v3.xlsx — 149/149 checks pass*  
*Built by UniTol / RelVersiv · For investor and internal use*
