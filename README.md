# SupplyAI — AI-Powered Supply Chain Intelligence

> **Predict. Optimize. Deliver.**  
> An intelligent, end-to-end supply chain visibility and decision-support platform designed for modern operations and hackathon demonstration.

---

## 1. Project Overview

**SupplyAI** is an AI-powered supply chain intelligence system designed to help businesses optimize and automate their operations. It provides an intuitive, data-driven platform to:
- Forecast customer demand with machine learning heuristics
- Manage inventory health and calculate automated reorder points
- Optimize multi-stop delivery routes to save time and fuel
- Predict delivery delays and transit risks before they occur
- Support rapid operational decision-making with an AI assistant

The platform unifies fragmented supply chain workflows into a cohesive, interactive control center.

---

## 2. Problem

Modern supply chain and logistics teams face persistent operational bottlenecks:

- **Uncertain Demand:** Fluctuating customer demand makes manual planning inaccurate and reactive.
- **Overstocking vs. Stock Shortages:** Miscalculating stock leads to capital locked in surplus inventory or lost revenue from stockouts.
- **Inefficient Delivery Routes:** Suboptimal routing increases fuel expenses, driver fatigue, and carbon footprint.
- **Delivery Delays:** Unforeseen transit congestion, vehicle capacity mismatches, and weather disruptions lead to missed SLAs.
- **Slow Decision-Making:** Critical information is scattered across spreadsheets and disparate tools, delaying rapid responses to disruptions.

---

## 3. Solution

SupplyAI eliminates operational silos by consolidating supply chain intelligence into a single unified dashboard:

- **Unified Intelligence:** Integrates demand forecasting, inventory analytics, fleet routing, delivery tracking, and purchase orders in real time.
- **Proactive Insights:** Identifies potential stockouts and transit bottlenecks before they impact customers.
- **Actionable AI Support:** Couples visual analytics with AI recommendations and guided next steps, empowering teams to act instantly.

---

## 4. Key Features

- **Executive Dashboard:** Centralized command center showcasing vital supply chain KPIs, operational alerts, and high-level trends.
- **Demand Forecasting (7, 14, and 30 Days):** Predictive forecasting across multiple time horizons using trend, moving average, and seasonality models.
- **Inventory Intelligence & Reorder Point Calculation:** Automated monitoring of stock levels, minimum safety stock, days of buffer remaining, and algorithmic Reorder Points (ROP).
- **Purchase Orders:** Instant purchase order creation and dispatch simulation directly from inventory alert recommendations.
- **Route Optimization:** Multi-node fleet routing engine that minimizes transit distance, travel time, and operational costs.
- **Delivery Delay / Risk Prediction:** Real-time delay risk scoring (Low, Medium, High) evaluating distance, priority, and traffic congestion.
- **Orders Management:** Comprehensive order tracking dashboard with search, status filtering, priority classification, and new order creation.
- **AI Assistant:** Conversational supply chain co-pilot that answers operational queries and provides context-grounded suggestions.
- **Offline Demo Mode:** Self-contained application architecture that runs reliably offline with instant response times and zero external API dependencies.

---

## 5. Our Additions / Improvements

In addition to the core architecture, we implemented four major enhancements:

1. **Supply Chain Health Score (0–100):**  
   A weighted composite metric combining inventory stability, on-time delivery rate, demand variance, and route efficiency into a single real-time health indicator.

2. **Supplier Risk & Alerts:**  
   Dedicated risk monitoring for upstream suppliers, highlighting lead-time delays, vendor raw material shortages, and geographic disruptions.

3. **Smarter Route Optimization:**  
   An enhanced optimization model that simultaneously factors in:
   - **Delivery Priority:** Ensures critical and high-priority orders are sequenced first.
   - **Traffic & Travel Time:** Avoids congested corridors to reduce overall transit hours.
   - **Vehicle Capacity:** Balances order payloads against vehicle load limits.

4. **AI Assistant with Recommended Actions:**  
   An upgraded assistant engine that pairs analytical answers with direct, executable action chips (e.g., dispatching POs, inspecting at-risk orders, or re-optimizing routes).

---

## 6. Who Can Use It

SupplyAI is designed for stakeholders across the logistics lifecycle:

- **Supply Chain Executives:** Monitor overarching performance, cost trends, and the unified Health Score.
- **Warehouse Managers:** Track stock balances, prevent stockouts, and trigger automated purchase orders.
- **Fleet Dispatchers:** Plan efficient delivery runs, monitor vehicle loads, and lower fuel consumption.
- **Logistics Coordinators:** Track order fulfillment, manage delays, and adjust delivery schedules proactively.
- **Customer Success & Operations Managers:** Maintain delivery commitments and communicate accurate delivery windows to clients.

---

## 7. How It Works

The platform follows a simple, closed-loop operational flow:

```
Demand Forecasting
       │
       ▼
Inventory Intelligence
       │
       ▼
Orders Management
       │
       ▼
Route Planning & Optimization
       │
       ▼
Delivery Risk Prediction
       │
       ▼
AI Recommendations & Actionable Insights
```

1. **Demand:** Predict future product demand over 7, 14, and 30 days.
2. **Inventory:** Compare current stock against forecasted demand and reorder thresholds.
3. **Orders:** Aggregate active customer orders across regional depots and warehouses.
4. **Route Planning:** Formulate optimized multi-stop routes factoring priority, traffic, and vehicle limits.
5. **Delivery Prediction:** Score transit risks and flag potential order delays in advance.
6. **AI Recommendations:** Provide automated root-cause explanations and suggested next steps to maintain smooth operations.

---

## 8. Technology Stack

- **Core Framework:** [React 18](https://react.dev/) with [TypeScript](https://www.typescriptlang.org/)
- **Build Tool:** [Vite](https://vitejs.dev/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Data Visualization:** [Recharts](https://recharts.org/)
- **Icons:** [Lucide React](https://lucide.dev/)
- **State & Storage:** React Hooks + Browser `localStorage` (persists state across sessions with reset capability)

---

## 9. Demo Data

- The application runs entirely on **curated, realistic demo data** simulating multi-warehouse operations, regional delivery routes, and diverse product inventories.
- **100% Offline Capability:** Requires no third-party API keys, paid credits, or external network connections to run the full demonstration.
- Includes a built-in **"Reset Demo Data"** action in Settings to quickly restore the default baseline during presentations.

---

## 10. Future Scope

Planned enhancements for future development include:

- **Real-Time IoT & Telematics Integration:** Live GPS vehicle tracking and automated warehouse sensor inputs.
- **Live Traffic API Feeds:** Dynamic rerouting powered by real-time navigation and road incident data.
- **Direct ERP & Supplier Integrations:** Webhook and EDI connectivity to enterprise systems (SAP, Oracle, NetSuite) and supplier portals.
- **Advanced Machine Learning Models:** Neural forecasting (e.g., Prophet, DeepAR) incorporating external market indicators, weather models, and promotional campaigns.
