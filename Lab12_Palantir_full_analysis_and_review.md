# Lab 12 — Palantir Full Analysis and Review

## Current conclusion

My analysis does not support Palantir's recorded market price. The pro-forma DCF values PLTR at **$50.94 per diluted share**, compared with a recorded market price of **$191.97 at 11:49 a.m. EDT on September 24, 2026**. A separate FCFF DCF produced **$44.27 per diluted share** and a WACC/terminal-growth sensitivity range of **$35.50–$60.00**, compared with the earlier recorded market price of **$169.53**. All values are in U.S. dollars and use approximately **2,565.197 million diluted shares**.

My conditional conclusion is **watch/defer**, even though my original qualitative call was initiate-buy. I still believe defense-technology spending and customer stickiness can support strong growth, but the current price requires outcomes beyond the assumptions I can presently defend. The conclusion could change if durable demand, retention, margins, dilution, and a company-specific discount rate support materially higher cash flows than the present model.

## 1. Target selection

- I selected Palantir because it is a fast-growing software and defense-technology company whose valuation depends heavily on long-duration growth expectations.
- It is suitable for analysis because the difference between its operating momentum and market valuation creates a clear falsification question: how much growth and profitability must occur to justify the price?
- My initial view was bullish because increased defense-technology investment and customer stickiness appeared capable of supporting long-term growth.
- The analysis made my view more cautious: the business can perform strongly while the stock still trades above the value supported by my assumptions.

## 2. Company and evidence

Palantir earns money by providing software platforms to government and commercial customers. Its economics differ from the automotive training company: it reports no inventory or floor-plan debt. Contract liabilities from customer prepayments are an important source of operating financing.

Key FY2025 evidence, in USD millions:

- Revenue: **$4,475.446**
- Gross profit: **$3,686.269**, or a **82.4% gross margin**
- SG&A: **$1,714.577**, defined in my model as sales and marketing plus general and administrative expense
- Net income attributable to common stockholders: **$1,625.033**
- Stock-based compensation: **$684.033**, approximately **15.3% of revenue**
- Cash and marketable securities: **$7,177.043**
- Contract liabilities: **$812.263**
- Shareholders' equity: **$7,387.268**

The history uses Palantir's 2023–2025 10-K filings. I checked revenue and shareholders' equity directly against the 2025 10-K. One important reporting limitation is that Palantir does not disclose a single company-wide organic or same-store growth percentage.

## 3. Pro-forma

The five-year model translates history into company-specific assumptions:

- Revenue growth fades from **80% in 2026 to 18% in 2030** as the company becomes larger.
- Gross margin rises gradually from **83% to 85%**, compared with 82.4% in FY2025.
- SG&A falls from **42% to 31% of gross profit**, extending the historical operating-leverage trend at a slower pace.
- R&D falls from **14% to 10% of gross profit**, while remaining a material investment.
- Stock-based compensation falls from **12% to 6% of revenue**. Dollar SBC still rises, but it becomes less significant relative to revenue.
- Capital spending remains **0.75% of revenue** and the mature tax rate is **21%**.
- Contract liabilities remain **18.15% of revenue**; inventory and floor-plan debt remain none.

The model links the income statement, balance sheet, and cash flow. Revenue and margin assumptions determine operating profit; working-capital balances and capital spending convert profit into cash flow; cash and stock-based compensation flow into the balance sheet and equity. All five forecast years have a **zero balance-sheet gap**, cash remains above the $50 million floor, and no revolver is drawn.

Selected forecast outputs, USD millions:

| Output | FY2026E | FY2030E |
|---|---:|---:|
| Revenue | 8,055.8 | 24,061.7 |
| Operating income | 2,907.7 | 11,929.6 |
| Net income | 2,467.2 | 10,177.1 |
| FCFE | 3,281.1 | 11,447.8 |
| Cash and marketable securities | 10,383.2 | 43,131.2 |
| Balance-sheet gap | 0.0 | 0.0 |

## 4. Valuation

### Pro-forma FCFE DCF

- Cost of equity: **10%**
- Terminal growth: **3%**
- Equity value: **$130,661.90 million**
- Value per diluted share: **$50.94**
- Share of value after 2030: **80.05%**

The large terminal-value share makes the result especially dependent on the discount rate, terminal growth, and whether forecast margins and growth persist.

### Earlier FCFF DCF

- WACC: **10%**, still an unresolved training placeholder rather than a completed company-specific estimate
- Terminal growth: **3%**
- Enterprise value: **$106,374.04 million**
- Equity value: **$113,551.08 million** after the enterprise-to-equity bridge
- Value per diluted share: **$44.27**
- Terminal value: **77.70% of enterprise value**

The FCFE and FCFF values differ because they use different cash-flow definitions and forecast structures. I do not average them. Their similar direction is informative, but neither resolves the unsupported discount-rate input.

### Peer comparison

My peer work provides a market-relative check, but Palantir is difficult to compare because its growth, government exposure, margin profile, and valuation differ from conventional software peers. P/E can also be distorted when current earnings are small relative to expected future growth. I therefore treat the peer result as a check on market expectations, not a substitute for the cash-flow model.

### Reverse DCF

Using the earlier recorded price of **$169.53**, the reverse DCF could not find a solution inside the required **−5 to +10 percentage-point** uniform growth-shift range. The endpoint values were **$37.61** and **$60.77** per share while starting FCFF, WACC, terminal growth, cash, debt, and shares were held fixed.

This does not prove mispricing. It establishes only that changing explicit-period growth within that assigned bracket is insufficient to reproduce the market price while all other inputs remain fixed.

## 5. Sensitivity and drivers

The saved WACC/terminal-growth sensitivity result is:

| WACC / terminal growth | 2% | 3% | 4% |
|---:|---:|---:|---:|
| 9% | $45.72 | $51.67 | $60.00 |
| 10% | $39.96 | **$44.27** | $50.00 |
| 11% | $35.50 | $38.72 | $42.87 |

The lowest tested value is **$35.50** at 11% WACC and 2% terminal growth; the highest is **$60.00** at 9% WACC and 4% terminal growth.

The causal link is: a lower discount rate or higher perpetual-growth rate increases terminal value, which increases enterprise value, then equity value, and finally value per share. On the operating side, revenue growth increases revenue, gross profit, operating income, cash flow, and terminal value, but it also increases receivables and other operating assets. Margin improvement converts more revenue into cash flow, while continued stock-based compensation supports reported cash flow but can dilute per-share value.

The ranking depends on the ranges tested. Sensitivity shows mathematical impact inside those ranges; it does **not** show which outcome is probable or which input is most uncertain. Because roughly 78%–80% of modeled value comes after the explicit forecast, the terminal assumptions have high measured impact. The input I most need to investigate is the company-specific discount rate, followed by evidence that operating leverage and dilution will develop as forecast.

## 6. Interpretation

- **Supported recommendation:** watch/defer at the recorded market prices.
- **Reason:** even aggressive operating growth produces modeled values far below the recorded prices, and the sensitivity range does not close the gap.
- **What would change my mind:** durable government and commercial demand, stable or improving customer retention, margins reaching the forecast path, dilution slowing, and a properly sourced company-specific discount rate that materially increases supported value.
- **What changed since selection:** I remain positive on the company but became more cautious about the stock because business quality and valuation are separate questions.
- **Next research priority:** build and source Palantir's company-specific WACC/cost of equity, then test revenue growth and SBC/dilution with ranges tied to filing or guidance evidence.

## Short presentation ending

My conclusion is conditional, not absolute. Palantir can remain an excellent and rapidly growing business while its shares trade above the value supported by my present assumptions. The most important unresolved input is the discount rate, but the large price gap means I also need evidence of stronger sustainable cash-flow growth and controlled dilution before changing the watch/defer conclusion.

## Presenter review note — instructor-approved substitute questions

My assigned partner was absent. My professor approved using substitute questions for the partner-question portion.

### Selection and evidence

- **Question:** Why did you choose Palantir, and which filing supports your claim that stock-based compensation is a major company-specific risk?
- **Answer:** I chose Palantir because its rapid growth and defense-technology position create a clear tension between business quality and valuation. Palantir's FY2025 10-K reports $684.033 million of stock-based compensation, approximately 15.3% of revenue, supporting its importance to cash-flow interpretation, shareholders' equity, dilution, and per-share value.

### Model and valuation

- **Question:** Why does your FCFE model value PLTR at $50.94 while your FCFF DCF gives $44.27, and why are both substantially below the recorded market price?
- **Answer:** The methods use different cash-flow definitions and forecast structures. The FCFE model values cash available to equity directly, while the FCFF model values operations first and then uses an enterprise-to-equity bridge. I do not average the two results. Both are below the market price because even the model's strong revenue growth and margin expansion do not generate enough discounted cash flow to reproduce the expectations embedded in the recorded price.
- **Unresolved gap:** The 10% discount rate remains a training placeholder rather than a fully sourced company-specific estimate, so I need to calculate Palantir's cost of equity and WACC before treating either valuation as final.

### Sensitivity and interpretation

- **Question:** Your sensitivity range is $35.50–$60.00. How dependent is that result on the tested WACC and terminal-growth ranges, and what evidence would make you change your watch/defer conclusion?
- **Answer:** The range is conditional on only the tested 9%–11% WACC and 2%–4% terminal-growth ranges. It shows mathematical impact, not probability, and wider or differently centered ranges could change the ranking and endpoints. I would reconsider watch/defer if durable government and commercial demand, retention, margins, and lower dilution supported higher cash flows and a sourced company-specific discount rate materially increased the valuation.

### Response and revision

- **Keep:** I will keep the distinction between company quality and stock value because it explains why I can remain optimistic about Palantir's business while declining to support the recorded share price.
- **Revise:** I will change the earlier initiate-buy wording to watch/defer so the recommendation matches the valuation evidence.
- **Investigate:** I will build a company-specific cost of equity/WACC and test revenue growth and SBC/dilution using evidence-based ranges.
- **Effect on conclusion:** The substitute review does not change the watch/defer conclusion because both DCF results and every tested sensitivity value remain below the recorded market prices. It changes the research priority by making the unsupported discount rate the first issue to resolve.
- **Question that made me reconsider something:** Why are both valuation methods below the market price even though the operating forecast is already aggressive?
- **What I understand better:** A strong company forecast does not automatically support its stock price. The price can require growth, margins, duration, or financing assumptions that exceed what my current evidence supports.

## Reviewer note — complete during the partner's presentation

- Partner and company: **[name/company]**
- Selection/evidence question I asked: **[use their actual claim and source]**
- Model/valuation question I asked: **[use their actual assumption or method difference]**
- Sensitivity/interpretation question I asked: **[refer to their tested ranges]**
- Source or calculation we opened: **[exact item]**
- Check result: **[supported/not supported and why]**
- My explanation back of the conclusion: **[brief explanation]**
- Main driver: **[driver]**
- Biggest limitation: **[limitation]**
- Evidence-backed strength: **[specific strength]**
- Specific next improvement: **[actionable improvement]**

## Existing evidence files

- `Lab10_Palantir_proforma.md`
- `palantir_proforma.py`
- `Palantir_DCF_inputs_2026-09-10.md`
- `palantir_dcf.py`
- `Lab08_Palantir_comparables.md`
- `lab08_palantir_comparables.py`

Add GitHub URLs after uploading the files. The substitute-question section records the professor-approved alternative necessitated by the partner's absence; it does not claim that a partner completed the review.
