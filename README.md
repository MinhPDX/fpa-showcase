# 📊 FP&A Portfolio & Skill Showcase

Welcome! This repository serves as a portfolio of my practical skills in Financial Planning & Analysis (FP&A). The projects contained here demonstrate my ability to perform key FP&A functions, from building integrated financial models to analyzing business performance and creating insightful reports.

The goal of this portfolio is to showcase my hands-on experience with the tools and methodologies used by modern finance professionals to drive strategic decision making.

## ✨ Core Skills Demonstrated

-   **Financial Modeling:** Building dynamic and integrated 3-statement financial models (Income Statement, Balance Sheet, Cash Flow Statement) from scratch.
-   **Capital Budgeting & DCF Analysis:** Evaluating the financial viability of major capital projects using Discounted Cash Flow (DCF) modeling. This includes building long-term forecasts based on public data and strategic assumptions to calculate project returns (NPV, IRR) and support investment decisions.
-   **Budgeting & Forecasting:** Creating detailed annual budgets and developing rolling forecasts to predict future performance.

## 📂 Repository Structure

This repository is organized into folders, with each folder corresponding to a core FP&A concept. Inside each folder, you will find the relevant Microsoft Excel file(s) for that topic.

## 🚀 Project Navigation

- [1. 3-Statement Financial Model](#1-3-statement-financial-model)
- [2. Event Profitability and Revenue Forecast](#2-event-profitability-and-revenue-forecast)
- [3. Port of Portland - T6 Capital Project Feasibility Analysis](#3-port-of-portland---t6-capital-project-feasibility-analysis)

## 📈 Projects & Analyses

Here is a summary of the projects included in this repository. Each project includes a link to the corresponding Excel workbook.

### 1. 3-Statement Financial Model

![image](https://github.com/user-attachments/assets/d2a17d8c-6d82-4537-bf93-79199185cd17)

This project showcases a dynamic and fully integrated 5-year, 3-statement financial model built from the ground up. The model begins with historical data of a fictional company and a set of core assumptions to drive a detailed forecast of the Income Statement, Balance Sheet, and Cash Flow Statement, demonstrating a comprehensive understanding of business drivers and financial reporting.

#### Scenario & Key Assumptions

To provide a realistic context for the model, it's based on a scenario for a hypothetical high-growth service company planning for significant expansion. The core assumptions driving the 5-year forecast (2025-2029) are outlined below:

- **📈 Revenue Growth & Drivers:** Modeled a strong `+20%` annual revenue increase, reflecting a significant pipeline of new clients. Other asset accounts, such as "Other Current Assets," were assumed to grow in line with this top-line expansion.
- **💼 Operating Expense Structure:**
  - **Cost of Goods Sold** was modeled as a variable expense, directly tied to sales revenue.
  - **Salaries & Wages** were projected to grow by `+15%` annually to account for the necessary headcount increase to service a larger client base.
  - **Supporting Growth Costs** like Professional Fees (`+20%`) and Advertising (`+10%`) were forecast to grow steadily to support operational scale and build brand recognition.
- **🏗️ Capital & Financing Assumptions:**
  - The forecast isolates the company's organic operational performance by assuming **no new Capital Expenditures** and **no additional Equity Injections** over the period.
  - **Depreciation and Amortization** are calculated based on the existing Capital Expenditure schedule, flowing directly from the starting Balance Sheet.

This framework of assumptions creates an integrated and logical foundation for the entire 3-statement model.

Key activities in this analysis included:

- 📊 **Income Statement Forecasting:** Projected revenue and expense line items using a combination of explicit growth assumptions and historical trend analysis. This included constructing a detailed, bottom-up depreciation schedule from a capital expenditure log using advanced Excel formulas (`SUMIFS`, `EOMONTH`).

- 🔗 **Balance Sheet Integration:** Forecasted asset and liability accounts by linking them to key drivers from the Income Statement, such as `Total Revenue Growth Rate` and `Total Expense Growth Rate`.

  - Working capital accounts (e.g., Accounts Receivable, Accounts Payable) were projected based on their relationship to revenue and expenses.
  - The Property, Plant & Equipment (PP&E) balance was rolled forward by subtracting the calculated depreciation expense each year.

- 🌊 **Cash Flow Statement Construction:** Built the Cash Flow Statement from scratch using the indirect method.

  - Started with Net Income and added back non-cash charges like Depreciation.
  - Calculated the cash impact from Changes in Working Capital by analyzing the year-over-year changes in the forecasted Balance Sheet accounts.

- ⚖️ **Balancing the Model:** Completed the final loop of the model by linking the `Ending Cash Balance` from the Cash Flow Statement back to the Cash account on the Balance Sheet. A balancing check was created and used to ensure `Total Assets = Total Liabilities & Equity`, which successfully validated the model's integrity and helped identify a formula error for correction.

- **Skills:** Financial Forecasting, 3-Statement Integration, Assumption-Driven Modeling, Working Capital Analysis, Depreciation & CapEx Scheduling, Cash Flow Reconciliation, Model Auditing & Balancing, Advanced Excel Formulas.

- **[➡️ View the Base Model (Before).xlsx](./Financial_Modeling/3_Statement_Model_Base.xlsx)** - The historical data and starting template.
- **[➡️ View the Completed Model (After).xlsx](./Financial_Modeling/3_Statement_Model_Completed.xlsx)** - The fully integrated 5-year forecast.

### 2. Event Profitability and Revenue Forecast

![image](https://github.com/user-attachments/assets/a081d4f5-90fc-4a31-829d-f5fa479f2989)

This project involves building a driver-based revenue forecast from scratch to assess the profitability of a proposed event for fictional companies. Starting with historical sales data and a list of fixed costs, the analysis projects ticket and concession revenue to build a pro forma Profit & Loss statement, culminating in a clear "go/no-go" recommendation based on the projected net margin.

#### Scenario & Key Activities

The model is built for a hypothetical scenario: an event committee needs to determine if their planned 2024 festival will be profitable.

- **Driver Identification & Analysis:** Analyzed historical data to identify key business drivers, such as the student participation rate and annual growth in ticket prices.
- **Attendance & Ticket Revenue Forecasting:** Forecasted the number of event attendees by applying an average historical participation rate to the total student population. Projected ticket price based on a consistent historical growth rate to determine total ticket revenue.
- **Concession Revenue Forecasting:** Modeled concession sales volume for various items as a percentage of total event attendees. Forecasted sales price and cost per unit based on historical trends to calculate total concession revenue and cost of goods sold.
- **P&L Construction & Profitability Analysis:** Consolidated the revenue forecasts and fixed operating expenses into a simple P&L statement. Calculated Gross Profit, Net Profit, and Net Margin to provide a clear view of the event's viability.

### 🏁 Conclusion & Recommendation

Based on the analysis, the clear recommendation is a **"Go"** for the event. The pro forma P&L projects a healthy **net margin of 32%**, indicating strong profitability. This level of profitability not only ensures financial success but also provides a significant financial cushion against unforeseen costs and generates substantial funds for the committee's future activities.

**Skills Demonstrated:** Driver-Based Forecasting, Profitability Analysis, P&L Construction, Trend Analysis, Assumption Documentation, Data-driven Decision Making, Excel (`AVERAGE`, `SUMPRODUCT`).

- **[➡️ View the Base Data (Before).xlsx](./Revenue_Forecasting/Event_Forecast_Base.xlsx)** - The historical data and list of fixed costs.
- **[➡️ View the Completed Forecast (After).xlsx](./Revenue_Forecasting/Event_Forecast_Completed.xlsx)** - The completed forecast and profitability analysis.

### 3. Port of Portland - T6 Capital Project Feasibility Analysis

![image](https://github.com/user-attachments/assets/9ab45eae-cfbd-4612-b8bd-7fc4242f6660)

This project demonstrates a real-world capital budgeting analysis for a major infrastructure investment. Using publicly available financial documents from the Port of Portland, I built a 15-year Discounted Cash Flow (DCF) model from scratch to evaluate the financial viability of a proposed $21 million capital improvement project for Marine Terminal 6 (T6). The analysis culminates in a clear recommendation based on key financial metrics like Net Present Value (NPV), Internal Rate of Return (IRR), and Payback Period.

#### Scenario & Key Activities

The scenario is based on the Port of Portland's real-world strategic goals outlined in their FY 2025-26 Adopted Budget. The Port is planning significant investments to stabilize and grow container service at Terminal 6, and this model assesses the financial return of that proposed investment.

- **📄 Data Sourcing & Extraction:** Sourced all primary data from the Port of Portland's public **[Finance & Statistics page](https://www.portofportland.com/FinanceAndStatistics)**, including the **FY 2025-26 Adopted Budget** and the **Annual Marine Terminal Statistics Report**.

- **📝 Assumption Development:** Developed a comprehensive set of assumptions to drive the 15-year forecast.

  - **Capital Expenditure:** The initial investment of **$21 million** was taken directly from the Port's budgeted capital projects list.
  - **Revenue Forecasting:** The forecast was anchored to a real-world baseline using the most recent historical container volume (TEUs). The initial growth rate of **5.1%** was taken directly from the Port's budget forecast, followed by a tapered growth assumption for future years to reflect a realistic project lifecycle.
  - **Cost Structure:** Modeled variable operating costs as a percentage of revenue (40%) and estimated fixed costs for maintenance and administration as a percentage of the initial capital investment (2.5%).
  - **Discount Rate (WACC):** Calculated a Weighted Average Cost of Capital (WACC) of **7.65%** to serve as the project's discount rate, based on assumed financing structure and market rates.

- **🌊 DCF Model Construction:** Built a detailed 15-year financial model that forecasted revenue, operating costs, and taxes to calculate the project's **Unlevered Free Cash Flow (UFCF)** for each year.

- **⚖️ Financial Evaluation & Recommendation:** Calculated the key financial metrics to determine the project's viability.
  - The project yields a strongly positive **Net Present Value (NPV) of $128.4 million**.
  - The **Internal Rate of Return (IRR) is 70.53%**, which is substantially higher than the 7.65% WACC.
  - The initial investment is recovered quickly, with a **Payback Period of 2 years**.

#### 🏁 Conclusion & Recommendation

The financial metrics provide a clear and decisive result. With a massively positive NPV and an IRR that is nearly 10x the cost of capital, the model indicates that the project is not only financially viable but exceptionally profitable. The recommendation is a strong **"Go"** for the Terminal 6 improvement project.

**Skills Demonstrated:** Discounted Cash Flow (DCF) Modeling, Net Present Value (NPV) & Internal Rate of Return (IRR) Analysis, Capital Budgeting, Financial Forecasting, Assumption Development, Data Sourcing, Python, PDF Data Extraction, Financial Statement Analysis.

- **[➡️ View the Source Documents](./Capital_Budgeting/data/)** - The source PDF reports.
- **[➡️ View the Completed Financial Model](./Capital_Budgeting/Port_of_Portland_-_T6_DCF_Model.xlsx)** - The completed 15-year DCF model.

## 🛠️ Tools & Technologies

- **Microsoft Excel:** Advanced Formulas, Pivot Tables, Charts & Graphs, Power Query, Financial Modeling Best Practices.
- **Git & GitHub:** Version control and portfolio hosting.

## 🚀 Future Enhancements

I plan to continue expanding this portfolio with additional analyses, including:

- **Advanced Modeling:** Incorporate scenario and sensitivity analysis into existing models to show how changes in key assumptions impact financial outcomes.
- **Business Intelligence Integration:** Replicate the Capital Budgeting model's final analysis in a dedicated BI tool like Power BI or Tableau, creating an interactive dashboard to showcase advanced data visualization skills.
- **Database Integration:** Re-architect a model to pull historical data directly from a SQL database using Power Query, demonstrating end-to-end data pipeline management.

## 📞 About & Contact

I am a passionate and detail-oriented finance professional seeking to apply my analytical skills to solve business challenges. I am actively seeking full-time FP&A roles.

Please feel free to connect with me:

- **💼 [LinkedIn: Minh Nguyen](https://www.linkedin.com/in/minhpdx/)**
