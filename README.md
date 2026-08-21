Monte Carlo Retirement Simulator

A single-file, browser-based Monte Carlo simulator for early retirement planning. Models portfolio survival across 10,000 randomized paths over a configurable horizon, with Guyton-Klinger guardrails, Social Security timing, cash bridge/shield mechanics, taxes, mortgage payoff, medical shocks, parental cost absorption, windfalls, and large one-time expenditures.

Live demo: https://jmf617.github.io/montecarlo/

What it does
Runs 10,000-iteration Monte Carlo simulations using log-normal equity/bond returns and stochastic inflation.
Applies Guyton-Klinger preservation/prosperity guardrails to adjust spending dynamically based on withdrawal rate.
Models a cash bridge (pre-72(t) years funded outside the portfolio), a cash shield (reserve drawn before equities in down years), Social Security start age/COLA, mortgage payoff, Roth conversion tax drag, medical cost shocks, optional parental cost absorption, and optional one-time windfalls or large expenditures.
Compares six built-in scenarios (Base, Conservative, Peso Shock, Tax Stress, Parent Absorption, Combined Stress) side by side.
Lets you save, load, and export named parameter sets locally in your browser (no server, no account).
Renders a portfolio fan chart (P10/median/P90), a failure-by-age histogram, and key findings — all client-side via <canvas>.
Usage

Open index.html in any modern browser, or use the live demo link above. Adjust the sliders/toggles, click Run Simulation. Everything runs locally in your browser — no data is sent anywhere, and nothing is saved unless you explicitly use the Scenario Manager (which stores to your browser's local storage only).

No build step, no dependencies, no install required.

Disclaimer

This is not financial, tax, or legal advice. This tool is a personal, educational project for exploring hypothetical retirement scenarios. It is not a recommendation, forecast, or guarantee of any future outcome, and it is not a substitute for professional advice.

All outputs depend entirely on the assumptions you enter (expected returns, volatility, inflation, spending, tax rates, life expectancy, etc.) and on randomized simulation paths. Real markets, tax law, and personal circumstances do not follow these models, and past or modeled performance is not indicative of future results.

Do not make retirement, investment, tax, or withdrawal decisions based solely on this tool. Consult a licensed financial advisor, CPA, and/or attorney for guidance specific to your situation.

This software is provided "as is," without warranty of any kind, express or implied, including but not limited to accuracy, merchantability, or fitness for a particular purpose. Use at your own risk.
