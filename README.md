# 📊 One-Prompt Dashboard

> An interactive sales dashboard built from Zenith sales data.
> Change a filter and every KPI and chart updates live.

## 🤔 Why I made this

Just curious, so I gave it a shot.

I only ran one prompt and didn't do any fine-tuning, so it might not be
a perfect dashboard — but honestly it's kind of amazing that just a few
lines of a prompt produced this.

I used the same data I'd visualized by hand in Tableau last semester...
and seeing it come together this easily was a little deflating, not gonna
lie. But the fact that the work can go this much faster... maybe that's
a good thing. Maybe.

## ✨ What's inside

- KPI cards up top (total revenue · profit · margin · units · customers · YoY growth)
- 6 filters (date range · continent · product category · market tier · customer segment)
- 5 charts (monthly trend · by category · top 10 countries · market tier · customer segment)

## 🚀 How to view it

Just open `zenith_dashboard.html` in your browser.
(The chart library loads from a CDN, so you'll need an internet connection.)

## 🛠 How it was made

- Handed Claude an Excel file and said "build me a dashboard"
- HTML + Chart.js, almost no dependencies
- Data is a fictional Zenith electronics sales dataset

---
*Time spent: about one cup of coffee* ☕
