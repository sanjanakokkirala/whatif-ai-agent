# WhatIf

AI business scenario simulator · Demo company: Britannia-style biscuit manufacturer · 10,000 t/month baseline (synthetic, ₹ crore)

## 1 · Strategic decision

Sales growth target: %

Demand uncertainty: ±%

1,000 Monte Carlo runs with random breakdowns, absenteeism, supplier delays and logistics disruption.

## Levers

## 2 · Can each function support it?

Utilization = required volume ÷ capacity. Red = over 100%.

## 3 · Simulated outcomes

## 4 · Strategy comparison at this target

## 5 · WhatIf AI agent

## How it works (algorithm)

1\) Build a digital twin of production, workforce, raw-material supply and logistics with baseline capacities → 2) Translate the sales target into volume demand with uncertainty → 3) Apply decision levers (overtime, third shift, hiring, supplier buffer, fleet, co-packer) to each constraint’s capacity → 4) Run Monte Carlo: random demand, plant breakdowns, absenteeism, supplier delays and transport disruption → 5) Fulfilled volume = the minimum across all constraints; the most frequently binding constraint is the bottleneck → 6) Score each strategy on probability of meeting target, fill rate, extra contribution margin and lever cost → 7) Search all lever combinations for the cheapest plan that meets the target with at least 85% probability. This demo uses assumed capacities and costs; replace them with ERP, MES and TMS data.