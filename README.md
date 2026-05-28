# Smart Inventory Intelligence System (SIIS)

> An ML-powered inventory intelligence dashboard designed to help Kenyan supermarkets reduce fresh food waste through expiry risk detection, pricing recommendations, and operational insights.

**Status:** In active development  |  **Stage:** MVP  |  **Market:** Kenyan retail

---

## The Problem

Kenya loses an estimated **KES 72 billion (~USD 578M)** in food waste annually across the supply chain *(WRI Africa, 2025)*.

At the supermarket level:

* Fresh food inventory losses from expiry can significantly affect already thin retail profit margins
* Expiry management in many stores remains largely manual and reactive
* Discount decisions are often based on observation rather than sales patterns or demand forecasting
* Smaller and mid-sized retailers may lack access to advanced inventory optimisation systems

The result is preventable waste, lost revenue, and missed opportunities to improve operational efficiency.

---

## The Solution

SIIS is a browser-based dashboard for supermarket branch managers.

Managers upload inventory data through a CSV file and receive a prioritised action table designed to help identify products that may require intervention before expiry.

The system combines inventory, sales velocity, and calendar-based patterns to support operational decisions such as:

| Action      | Meaning                                                   |
| ----------- | --------------------------------------------------------- |
| 🔴 Donate   | Product is approaching expiry and may not clear in time   |
| 🟡 Discount | Suggested markdown may improve sell-through before expiry |
| 🟢 Keep     | Product appears to be selling within expected patterns    |

The system is designed to account for factors such as:

* sales velocity,
* day-of-week demand changes,
* seasonal or holiday shopping patterns,
* and branch-level behaviour differences over time.

No specialised hardware required — only a browser and inventory data.

---

## Why Kenya

Retail behaviour varies significantly across regions and branch locations.

For example:

* urban branches may experience faster movement of convenience and bakery products,
* while smaller towns may show different grocery purchasing patterns influenced by local markets and shopping habits.

SIIS is being designed with these local retail patterns in mind, using machine learning models that can improve over time as more branch-specific historical data becomes available.

The long-term goal is to provide an accessible inventory intelligence system tailored to the operational realities of Kenyan supermarkets.

---

## Estimated Operational Impact

Potential benefits may include:

* reduced expiry-related losses,
* earlier identification of slow-moving products,
* improved discount timing,
* and better inventory visibility for branch managers.

Actual impact will depend on:

* branch size,
* inventory quality,
* operational workflows,
* and historical sales data available.

---

## Built With

* Python
* scikit-learn
* pandas
* Flask
* Supervised and unsupervised machine learning models

---

## Market

**Primary focus:** Mid-sized Kenyan supermarket chains and regional retailers.

**Future expansion areas:** Pharmacies, hotels, school canteens, and restaurant operations where inventory expiry management is important.

---

## About

Built by a Software Engineering student in Kenya, inspired by observations of operational challenges within the local retail sector.

This project explores how machine learning and lightweight operational tooling can be applied to improve inventory decision-making in emerging retail markets.

**Contact:** jamesndungukabuga@gmail.com

**Institution:** Murang'a University of Technology

---

*Currently in active development. Feedback and collaboration discussions are welcome.*
