# nassau-candy-profitability-analysis
Product Line Profitability & Margin Performance Analysis — Nassau Candy Distributor
Framework: Google PACE (Plan, Analyze, Construct, Execute)
Tech Stack: Python (Pandas, Matplotlib, Seaborn), Streamlit
Documents Included: Research Paper, PACE Strategy Document, Executive Summary
Executive Summary
In wholesale confectionery distribution, relying solely on gross sales volume obscures unit-level margin erosion and portfolio concentration risks. This project evaluates transactional order, sales, cost, and unit records for Nassau Candy Distributor ($141,783.63 total revenue; $93,442.80 gross profit; 65.91% overall gross margin) to uncover true product-line profitability and operationalize a 20.0% gross margin safety guardrail via an interactive Streamlit dashboard.
Key Empirical Findings
Severe Pareto Profit Concentration (>80%): Just five core Wonka Bar SKUs (Milk Chocolate, Triple Dazzle Caramel, Scrumdiddlyumptious, Nutty Crunch Surprise, and Fudge Mallows) generate over 80% of total gross profit.
22.60 pp Division Efficiency Gap: The Chocolate division achieves a 67.44% average gross margin, whereas the Other/Specialty division averages only 44.84%.
High-Volume / Low-Margin Risk: Margin screening below the 20.0% viability guardrail isolates high-activity SKUs such as Kazookles (7.69% gross margin) alongside Fun Dip, Nerds, SweeTARTS, and Lickable Wallpaper.
Methodology (PACE Workflow)
1. Plan: Mapped order-level fields (Order ID, Order Date, Division, Units, Sales, Cost, Profit) to stakeholder pricing and rationalization decisions; formulated H_0 vs. H_1 hypotheses.
2. Analyze: Validated data hygiene (0 nulls, removed invalid zero-sales/negative-profit records) and computed core KPIs: Gross Profit, Gross Margin (%), Profit per Unit, Profit Contribution (%), and Margin Risk Flag (GM% < 20.0%).
3. Construct: Built Pareto concentration rankings, cost-vs-sales scatter diagnostics, and an interactive Streamlit dashboard with date-range, division, product-search, and margin-threshold sliders.
4. Execute: Delivered targeted repricing, supplier cost renegotiation, SKU rationalization, and strategic bundling recommendations.
Repository Structure
app.py — Interactive Streamlit analytics dashboard
requirements.txt — Python dependencies
<img width="1920" height="1080" alt="Screenshot (15)" src="https://github.com/user-attachments/assets/8fe51d12-d8da-43ab-8de0-0097c60064e8" />

Product Line Profitability & Margin Performance Analysis - Research Paper (1).pdf — Full empirical research paper
PACE Strategy - Nassau Candy Profitability Analysis-1.pdf — Complete PACE workflow documentation
Executive Summary.pdf — One-page stakeholder summary
