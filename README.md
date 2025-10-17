# data-reporting-dashboard-task004
TDS generated repo


## 🌀 Round 1 (2025-10-17)

**Brief:** Create a single responsive 'Summary Card' (ID: #summary-card) for sales data. The application should internally simulate having loaded a CSV file with monthly sales figures. Calculate the 'Total Sales' (e.g., $5500) and display this value prominently inside the card. The card must use Tailwind CSS utility classes for styling (e.g., shadows, rounded corners, padding) to ensure a professional design.

**Checks:**
- !!document.querySelector('#summary-card')
- !!document.querySelector('#total-sales-value')
- document.querySelector('#total-sales-value').textContent.includes('5500') || document.querySelector('#total-sales-value').textContent.includes('5,500')
- document.querySelector('#summary-card').className.includes('shadow')

**Status:** ✅ Completed

**Pages URL:** [https://vinaysinghchaudhary1.github.io/data-reporting-dashboard-task004/](https://vinaysinghchaudhary1.github.io/data-reporting-dashboard-task004/)

---


## 🔁 Round 2 Update (2025-10-17)

**Brief:** Enhance the existing Summary Card. Immediately below the Total Sales, add a button with the ID '#toggle-chart-button' and a label 'View Monthly Trend'. When clicked, this button should toggle the visibility of a monthly sales bar chart (using simulated data: Jan: 1500, Feb: 2200, Mar: 1800) in a dedicated container (ID: #monthly-chart). The chart should have smooth CSS transitions (e.g., fade or slide) when it appears or disappears.

**Checks:**
- !!document.querySelector('#summary-card')
- !!document.querySelector('#toggle-chart-button')
- !!document.querySelector('#monthly-chart')
- document.querySelector('#monthly-chart').style.display === 'none' || document.querySelector('#monthly-chart').style.visibility === 'hidden'
- window.getComputedStyle(document.querySelector('#monthly-chart')).transition !== ''

**Status:** ✅ Redeployed

**Pages URL:** [https://VinaySinghChaudhary1.github.io/data-reporting-dashboard-task004/](https://VinaySinghChaudhary1.github.io/data-reporting-dashboard-task004/)

> ⏳ **Note:** GitHub Pages may take around 10 minutes to fully render and reflect all updates for this round.

---
