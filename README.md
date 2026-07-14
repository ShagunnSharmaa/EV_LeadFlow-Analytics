# EV Lead-to-Delivery Funnel Analysis

## Business Problem
EV retail stores manage leads through a multi-stage funnel — Lead → Pre-Booking → 
Booking → Delivery — with follow-up service after. This project analyzes that 
funnel across stores to find where conversions stall, which stages cause delays, 
and what drives cancellations and customer satisfaction.

## What I Did
- Cleaned and structured lead-level data across multiple stores, tracking dates 
  across each funnel stage
- Calculated store-wise conversion rates and turnaround time (TAT) per stage 
  (Pre-Booking, Booking, Delivery)
- Analyzed cancellation patterns by reason and store
- Segmented leads by Hot/Warm/Cold and compared distribution across stores
- Analyzed customer rating distribution post-delivery
- Built a 5-panel visualization dashboard (funnel, TAT, cancellations, lead 
  distribution, ratings) using Matplotlib & Seaborn

## Key Insights
- Conversion rates were consistently strong (~80–82%) across all stores
- Book-to-Delivery was the biggest bottleneck — highest TAT of any stage
- Lead quality mix was similar across stores, meaning performance gaps came 
  from execution, not lead sourcing
- Financing issues, pricing concerns, and model unavailability were the top 
  cancellation drivers

## Recommendations
- Prioritize Hot/Warm lead follow-ups via CRM reminders; train staff on 
  objection handling
- Set internal SLAs per funnel stage to reduce delivery TAT
- Partner with more financing providers and improve upfront pricing communication
- Standardize post-delivery feedback collection across stores

## Tools
Python (Pandas, NumPy, Matplotlib, Seaborn) — Jupyter Notebook

## Dashboard Preview
<Figure size 1800x1200 with 5 Axes><img width="1784" height="1184" alt="image" src="https://github.com/user-attachments/assets/dc1b4f66-0db1-441f-b9b7-f7a94006972f" />
