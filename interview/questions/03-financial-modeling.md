# Financial Modeling and Valuation

Financial modeling in a hedge fund interview is fundamentally different from investment banking modeling. In banking, the model is the deliverable. In hedge fund interviews, the model is a tool to support an investment thesis. Interviewers care less about whether your balance sheet balances to the penny and more about whether you understand what drives the business and how those drivers translate to valuation.

That said, you need to be technically proficient. If you cannot build a 3-statement model from a 10-K in two to three hours, you are not ready for hedge fund interviews. Technical competence is table stakes -- what separates you is how you think about the model's outputs and how quickly you can identify what matters.

The core skill being tested is not spreadsheet mechanics. It is whether you can look at a set of financial statements, identify the two or three assumptions that actually drive the business, build projections around those assumptions, and translate that into a valuation with a clear investment recommendation.

In my experience, the candidates who do best on modeling tests are not the ones with the most polished Excel skills. They are the ones who spend the first 15 minutes reading the financials and thinking before they touch the keyboard. Understanding the business comes first. The spreadsheet is just the tool you use to express that understanding.


## What interviewers evaluate

Technical accuracy. Can you build a model that works? Do the three statements link correctly? Does the cash flow statement reconcile? Are your formulas correct? Errors signal carelessness, which is disqualifying when the job involves managing real capital. A formula error in an interview model is a preview of a formula error in a model that drives a $20M position.

Speed. Hedge fund modeling tests are timed. A 3-statement model build from a 10-K typically gets two to three hours. An LBO model gets one to two hours. If you need four hours to build a basic model, you are too slow. Speed comes from repetition -- there is no shortcut. The fastest modelers are not faster typists. They are faster at identifying what matters and ignoring what does not.

Understanding of drivers. This is where hedge fund modeling diverges from banking. Interviewers want to see that you understand what actually drives the business. Can you identify the two or three key assumptions that matter most? If you are modeling a retailer, same-store sales growth and new unit openings matter far more than the depreciation schedule. If you are modeling a software company, net revenue retention and new customer acquisition cost payback periods matter more than the tax rate assumption.

Sensitivity to key assumptions. Can you quickly articulate how your valuation changes if your key assumptions are wrong? If revenue growth comes in at 6.0% instead of 10.0%, what happens to your target price? This is where a model becomes an investment tool rather than an academic exercise. The ability to instantly frame "what if I am wrong?" makes you useful to a portfolio manager.

Intellectual honesty about precision. The best candidates acknowledge that a model is a framework for thinking, not a crystal ball. Saying "my DCF gives me a price target of $47.32" implies false precision. Saying "my analysis suggests the stock is worth $42 to $52 depending on margin trajectory, with a base case around $47" demonstrates maturity. The range matters more than the point estimate.


## Types of modeling tests

3-statement model build. You receive a company's 10-K and have two to three hours to build a fully linked income statement, balance sheet, and cash flow statement with projections. This is the most common modeling test at fundamental equity funds. You are expected to project at least three years forward and produce a valuation output.

LBO model. You model a leveraged buyout with multiple tranches of debt, management incentives, and exit scenarios. Common at funds that invest in event-driven or credit situations. You typically get one to two hours. The key output is the internal rate of return at various exit multiples and the sensitivity of returns to leverage, growth, and margin assumptions.

DCF from scratch. Build a discounted cash flow analysis including explicit forecast period, terminal value, and WACC calculation. Often combined with a 3-statement model as the valuation output. Interviewers will test whether you understand the sensitivity of DCF outputs to terminal growth rate and discount rate assumptions -- which is why many practitioners prefer multiples-based valuation for more reliable anchoring.

Comps analysis. Select comparable companies, calculate relevant trading multiples, and apply them to the target company. Interviewers test whether you understand why multiples differ across companies -- growth rates, margins, returns on capital, and balance sheet risk. A company growing revenue at 15.0% with 30.0% EBITDA margins should trade at a premium to one growing at 5.0% with 15.0% margins. Can you quantify the premium?

Quick mental math valuation. "This company earns $3 per share and trades at $45. It grows earnings 10.0% per year. Is it cheap?" These quick questions test whether you can do rough valuation math in your head during a conversation. The answer involves comparing the 6.7% earnings yield to your required return and assessing the growth rate's sustainability.


## Sample questions

"Build a 3-statement model for this company using their 10-K."

"Walk me through a DCF. What is the most important assumption?"

"How do you think about terminal value?"

"When would you use EV/EBITDA versus P/E?"

"This company trades at 15x earnings. Is it cheap or expensive?"

"How does a $10M asset write-down flow through the three statements?"

"What is the difference between levered and unlevered free cash flow?"

"Walk me through an LBO model and what drives returns."

"If EBITDA margins expand by 200 basis points, what is the impact on free cash flow?"

"How do you calculate WACC? What discount rate would you use for this company?"

"Why might two companies in the same industry trade at different multiples?"

"What is the difference between enterprise value and equity value?"

"When does a DCF give you a higher value than a comparables analysis?"

"How do you project working capital for a company with seasonal revenue?"

"Walk me through how you would model a company that is transitioning from hardware to subscription revenue."

"What is the right terminal growth rate for this business and why?"

"If this company issues $500M of debt to buy back stock, what happens to EPS? What happens to the stock price?"

"How do you think about normalized earnings versus reported earnings?"

"What adjustments would you make to this company's reported EBITDA?"

"A company trades at 8x EV/EBITDA. The peer group trades at 12x. What could explain the discount?"

"How would you model the revenue impact of a price increase on a company with a subscription business?"

"Walk me through the difference between operating cash flow and free cash flow, and when each matters more."


## Key concepts to master

Revenue build. Break revenue into its component drivers. For a retailer, that is store count times average revenue per store, which you can further decompose into traffic and average transaction value. For a SaaS company, that is customer count times average contract value times net retention rate. For a bank, that is net interest income (driven by earning assets times net interest margin) plus fee income. The revenue build should reflect how the business actually generates revenue, not just the top-line number.

Margin analysis. Understand the difference between gross margin, EBITDA margin, and operating margin. Know what drives each. Can the company expand margins through operating leverage (fixed costs spread over growing revenue), pricing power (raising prices without losing volume), or mix shift (growing higher-margin segments faster)? Or are margins likely to compress due to competition, rising input costs, or investment spending? The margin trajectory is often the most important driver of stock price performance.

Working capital dynamics. Understand how changes in accounts receivable, inventory, and accounts payable affect cash flow. A company can be profitable and still run out of cash if working capital is growing faster than revenue. Rapidly growing companies often have negative free cash flow despite strong profitability because they are investing in working capital to support growth. Know how to calculate cash conversion cycle and what it implies about business quality.

Capital expenditure analysis. Distinguish between maintenance capex (required to sustain the business at its current level) and growth capex (invested to grow the business). This distinction matters for free cash flow calculation and valuation. A company spending 80.0% of its capex on growth has very different economics than one spending 80.0% on maintenance. Management rarely discloses this split, so you need to estimate it.

Return on invested capital. ROIC is the single most important metric for evaluating business quality. A company that earns 25.0% ROIC and reinvests at that rate is fundamentally more valuable than one earning 8.0% ROIC. Understand how to calculate ROIC (NOPAT divided by invested capital) and what drives it -- margin, asset turnover, and capital structure. High ROIC businesses deserve premium multiples because their reinvestment creates more value per dollar.

Depreciation versus capex spread. In many capital-intensive businesses, the relationship between depreciation and capex reveals the investment cycle. When capex significantly exceeds depreciation, the company is investing heavily for future growth. When capex roughly equals depreciation, the company is in maintenance mode. When capex falls below depreciation, the company may be underinvesting, which flatters current free cash flow but creates future problems.


## Common mistakes

Memorizing formulas without understanding drivers. Knowing that unlevered free cash flow equals EBIT times one minus tax rate plus depreciation minus capex minus change in working capital is not enough. You need to understand why each component matters and what drives it for the specific company you are modeling. An interviewer who asks "what is the most important assumption in your model?" wants to hear about business drivers, not accounting definitions.

Over-building the model. A 15-tab model with granular assumptions on every line item is not better than a focused model that nails the three key drivers. In a timed test, prioritize the assumptions that actually move the valuation. Getting the revenue build and margin trajectory right matters far more than perfectly modeling the other income line.

Anchoring to the current stock price. Do not reverse-engineer your assumptions to hit the current stock price. Build your model based on your fundamental view and let the output tell you whether the stock is cheap or expensive. If your model says the stock is worth $60 and it trades at $45, that is your investment thesis. If your model says the stock is fairly valued, that is also a valid conclusion.

Ignoring the balance sheet. Many candidates focus on the income statement and treat the balance sheet as an afterthought. The balance sheet matters -- leverage ratios affect the cost of capital and risk of financial distress, upcoming debt maturities can force dilutive refinancing, and off-balance-sheet items (operating leases, pension obligations, litigation reserves) can represent material hidden liabilities.

False precision. Projecting revenue to four decimal places or terminal value to the exact dollar suggests you do not understand the inherent uncertainty in financial projections. Use round numbers and ranges. A valuation range of $42 to $52 is more intellectually honest and more useful than a point estimate of $47.32.


## Accounting concepts that come up frequently

Stock-based compensation. Should you add back SBC when calculating free cash flow? This is a common interview question with a nuanced answer. SBC is a real economic cost because it dilutes existing shareholders, but it is a non-cash charge. Some investors add it back to free cash flow, others do not. The key is to be consistent and to account for the dilution separately. If you add back SBC to free cash flow, you should also model the share count increase from option exercises and RSU vesting.

Goodwill and impairment. When a company acquires another company for more than its book value, the excess is recorded as goodwill. Goodwill is not amortized but is tested annually for impairment. A goodwill write-down does not affect cash flow but signals that management overpaid for an acquisition. Frequent write-downs suggest poor capital allocation discipline.

Deferred revenue. Common in subscription and software businesses. Deferred revenue represents cash collected for services not yet delivered. An increase in deferred revenue is a positive signal because it means the company is collecting cash faster than it is recognizing revenue. Changes in deferred revenue are a leading indicator of future revenue growth.

Operating leases. Since ASC 842, operating leases are recorded on the balance sheet as right-of-use assets and lease liabilities. This affects leverage ratios and enterprise value calculations. When comparing companies across time periods or across accounting standards, be sure to adjust for consistent treatment of leases.

Pension obligations. For companies with defined benefit pension plans, the funded status of the plan is an off-balance-sheet liability that affects true enterprise value. Unfunded pension obligations are a form of debt that many analysts overlook. Check the footnotes for the discount rate and return assumptions, which can hide the true size of the obligation.


## Preparation

Practice building models from scratch with a timer. Download a 10-K for a company you have not analyzed before and give yourself three hours to build a 3-statement model with projections and a valuation. Do this at least five times before your interviews. Each time, you will get faster at identifying what matters and building efficient formulas.

Study business models before studying accounting. Understanding how a company makes money is more important than memorizing the accounting treatment for operating leases. Start with the business model and let the accounting follow. If you understand that a subscription software company's economics are driven by customer acquisition cost payback and net revenue retention, the accounting treatment follows logically.

Practice mental math. You should be able to quickly calculate earnings yields, growth-adjusted multiples, and back-of-the-envelope valuations during a conversation. This comes from practice. If someone tells you a company earns $5 per share, trades at $75, and grows 12.0% per year, you should instantly know it trades at 15x earnings with a 6.7% earnings yield and a PEG ratio of 1.25x.

Build a library of sector-specific modeling templates. Different sectors require different modeling approaches. Banks need a net interest income model. Retailers need a same-store sales model. Software companies need a cohort-based recurring revenue model. Insurance companies need a combined ratio model. Having pre-built mental frameworks for different business types will save you time in timed tests.

Learn the shortcuts. In a timed test, certain modeling shortcuts save significant time without sacrificing accuracy. Projecting depreciation as a percentage of gross PP&E rather than building a detailed fixed asset rollforward. Modeling working capital as days outstanding rather than individual line items. Using a plug to the revolver rather than iterating the circular reference between interest expense and debt balances. Know which shortcuts are acceptable and which cross the line into laziness.

Understand valuation methodology debates. Different valuation approaches can give wildly different answers. Be prepared to discuss why you chose a particular methodology and what its limitations are. A DCF is theoretically elegant but highly sensitive to terminal assumptions. Comparable company analysis is empirically grounded but assumes the market is pricing peers correctly. Precedent transactions reflect what acquirers have paid but may not reflect intrinsic value. Sum-of-the-parts analysis is useful for conglomerates but requires assumptions about each segment's standalone value. Knowing when each approach is most appropriate and being able to defend your choice is essential.

Build intuition for what numbers should look like. Through practice, you develop a sense for what reasonable financial metrics look like across different industries. Gross margins of 70.0% are normal for software but would be extraordinary for a retailer. Net debt to EBITDA of 4.0x is comfortable for a utility but concerning for a cyclical industrial. Revenue growth of 30.0% is expected for an early-stage SaaS company but would be suspicious for a mature consumer staples business. This intuition helps you quickly sanity-check your model outputs and catch errors.


## Interview day tips for modeling tests

Bring your own laptop if allowed. Your own keyboard shortcuts, formula conventions, and Excel setup can save 15 to 20 minutes over a 3-hour test. If you must use the fund's computer, spend the first five minutes setting up your environment -- font size, column widths, number formats.

Color-code your assumptions. Use blue font for hard-coded inputs and black for formulas. This is industry standard and makes your model easier for the evaluator to follow. It also helps you quickly identify which cells to change when running sensitivities.

Build error checks. Insert a simple check row that verifies assets equal liabilities plus equity. If this check shows an imbalance, you know immediately that something is broken. Spending two minutes on error checks can save 20 minutes of debugging later.

Do not panic if the balance sheet does not balance. In a timed test, a small imbalance is far less damaging than not finishing your model. Note the imbalance, move on to the valuation, and fix it at the end if time permits. The evaluator cares about your thesis and your understanding of the business far more than a $2M rounding difference on the balance sheet.

Narrate your thought process. If you are presenting your model live, walk the interviewer through your thought process as you build it. "I am projecting revenue by breaking it into existing store sales and new store contribution because same-store sales growth is the most important driver for this business." This demonstrates understanding even if your model has minor imperfections.


For a structured deep-dive with real hedge fund interview examples, check out [The 0 to 1 Hedge Fund Interview Playbook](https://valenx.org/books/hf).
