# GoEasy Valuation Project

## Overview
1. Full valuation analysis built to estimate a company’s intrinsic value using fundamental financial data and forecasting.
2. Focuses on explaining the valuation outcome by outlining key assumptions, drivers, and risks that may impact the final estimate.
3. Structured to be readable, auditable, and intuitive for anyone with basic finance knowledge.
4. Combines three core components:
    A) Historical financial analysis to understand business performance.
    B) Forward‑looking projections to estimate future results.
    C) A valuation framework that converts those expectations into present value.
5. The Excel model performs all calculations, while the visualization file highlights and communicates the results clearly.

## Business Understanding and Historical Analysis
1. Every valuation begins with understanding the business before forecasting any numbers.
2. The model reviews historical income statements, balance sheets, and cash flow statements to see how the company actually operates.
3. This analysis reveals how the company generates revenue, what drives growth, how stable margins are, and how capital‑intensive the business is.
4. Key multi‑year trends—such as Net Income, Shares Outstanding and ROE rates are examined to establish realistic baselines.
5. Historical performance anchors future assumptions, preventing unrealistic or arbitrary growth targets.
6. The project also evaluates qualitative factors like business model strength, customer base, credit risk, and sensitivity to economic cycles.
7. These qualitative insights directly influence assumptions about growth, risk, and discount rates in the valuation model.


## The Logic of the Excel Model (The "Engine")
1. The valuation begins by calculating the Cost of Equity at approximately 10.1%, which serves as the company’s required “hurdle rate.”
2. If goeasy cannot earn more than this 10.1% on its book value, the stock should not trade at a premium.
3. Using management’s guidance, the model projects a 23.5% Return on Equity (ROE), creating a very large spread above the hurdle rate.
4. Because 23.5% significantly exceeds the 10.1% required return, goeasy functions as a strong “wealth‑creation engine.”
5. The model computes “Excess Profit,” which is the difference between the company’s actual ROE (23.5%) and the required return (10.1%).
6. These future excess profits are discounted back to their present value to reflect today’s dollars.
7. Adding the current Book Value to the present value of all future excess profits results in an estimated Intrinsic Value of roughly $278.11 per share.

The Residual Income Valuation:
![The Residual Income Valuation](<./images/The Residual Income Valuation.png>)

Here is the result of the Valuation Summary explained above:
![The Valuation Summary](<./images/The Valuation Summary.png>)

This visual is the most important part of the dashboard. It plots two different "safety lines." One line shows what the price should be based on Earnings (P/E), and the other shows what it should be based on Book Value (P/B). You’ll notice that while the Earnings line bounces around because profits can be volatile, the Book Value line moves up steadily. This shows that the company’s "floor value" is rising every single year:

![Valuation Line Chart over the years 2020-2024](<./images/Valuation Line Chart over the years 2020-2024.png>)

This chart compares EPS (Earnings Per Share) and BVPS (Book Value Per Share). It answers the question "Why is the stock worth more now than in 2020?" The bars show that the company has nearly doubled its book value in just a few years. It proves that management isn't just talking about growth; they are actually building a bigger, wealthier company:
![The P/E and P/B over the years 2020-2024](<./images/The PE and PB over the years 2020-2024.png>)



