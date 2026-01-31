# 🚆 Railway Performance & Revenue Analytics  
*A stakeholder-driven dashboard case study*

---

## 1. Project Overview

This project presents an end-to-end **Railway Performance & Revenue Analytics** case study designed to demonstrate how data analytics and storytelling can support real stakeholder decision-making.

The objective is not only to report operational metrics, but to **answer concrete business questions** raised by executives, operations, commercial teams, and customer experience stakeholders.

The project follows data storytelling and stakeholder communication principles inspired by:

- *Effective Data Storytelling* — Brent Dykes  
- *The Stakeholder Communication Handbook* — Carisa Carlton  
- *Data Insights Delivered* — Mo Villagran  
- *Storytelling with Data* — Cole Nussbaumer Knaflic  

---

## 2. Business Context

A national railway operator faces increasing pressure due to:

- Customer dissatisfaction linked to delays and cancellations  
- Rising refund costs  
- Misalignment between operational, commercial, and executive teams  
- Fragmented reporting with no shared narrative  

Although data is available, stakeholders lack a **single, trusted view** that connects service reliability, passenger behaviour, and financial impact.

This project simulates how an analytics professional designs a dashboard that **bridges that gap**.

---

## 3. Stakeholder-Centered Problem Definition

Instead of starting with KPIs, this project starts with **stakeholder questions**.

### Key Stakeholders and Their Needs

| Stakeholder | Key Questions |
|-----------|--------------|
| Executive Leadership | How reliable is the service overall? Where are we losing money? |
| Operations Managers | Which routes and time periods underperform most? |
| Commercial & Finance | How do delays and cancellations impact net revenue and refunds? |
| Customer Experience | When and where are passengers most affected? |

These questions guided **every modelling and visualisation decision**.

---

## 4. Dashboard Structure & Purpose

The Power BI dashboard is structured into four main pages, each aligned with a stakeholder perspective.

---

### 4.1 Railway Performance

**Key Questions Answered**
- How reliable is the railway service overall?
- How does performance evolve month over month?
- What are the leading causes of delays and cancellations?

**Key Metrics**
- Planned vs On-Time vs Delayed vs Cancelled services  
- Reliability percentage  
- Monthly trends  
- Delay and cancellation root causes  

**Outcome**
Provides executives and operations leaders with a clear, high-level view of service reliability and risk areas.

---

### 4.2 Route Analysis

**Key Questions Answered**
- Which routes are most delayed or cancelled?
- Where are refunds and reliability issues concentrated?
- Which routes require operational intervention first?

**Key Metrics**
- Most delayed routes  
- Most cancelled routes  
- Route-level reliability and refund percentage  
- Journey volume by route  

**Outcome**
Enables operations teams to prioritise improvements based on impact rather than intuition.

---

### 4.3 Sales Performance

**Key Questions Answered**
- How does journey status affect net revenue?
- Which ticket types contribute most to revenue?
- What is the financial impact of delays by duration?

**Key Metrics**
- Net revenue trend  
- Revenue by journey status (On Time, Delayed, Cancelled)  
- Refunds by delay duration  
- Revenue by ticket type (Advance, Anytime, Off-Peak)  

**Outcome**
Connects operational performance directly to financial outcomes, supporting data-driven commercial decisions.

---

### 4.4 Passenger Rail Usage

**Key Questions Answered**
- When are trains busiest?
- What are the peak and off-peak travel patterns?
- Which stations handle the highest passenger volumes?
- How do passengers purchase tickets?

**Key Metrics**
- Passenger volumes by hour  
- Peak vs Off-Peak usage  
- Top departure and arrival stations  
- Ticket class, purchase channel, and railcard usage  

**Outcome**
Supports customer experience and capacity planning discussions.

---

## 5. Core Narrative & Insights

The dashboard reveals a clear and actionable narrative:

- Overall reliability is high (~91%), but not evenly distributed  
- A small number of routes and time periods drive most disruptions  
- **Short delays generate a disproportionate share of refunds**  
- On-time services generate the majority of net revenue  
- Improving punctuality by minutes can deliver meaningful financial and customer benefits  

This shifts conversations from *“We need to improve everything”* to *“We know exactly where to act.”*

---

## 6. Data & Analytics Workflow

### 6.1 Data Sources

- Railway operational dataset  
- Passenger journeys and routes  
- Ticket sales, refunds, delays, and cancellations  

Supporting documentation:
- `railway.csv`
- `railway_data_dictionary.csv`

---

### 6.2 Workflow Steps

1. **Data Understanding**
   - Reviewed the data dictionary
   - Interpreted business meaning behind each field

2. **Data Preparation & Modelling**
   - Standardised delay and cancellation categories
   - Created calculated measures:
     - Reliability %
     - Refund %
     - Net Revenue
     - Journey status breakdowns

3. **Question-Driven Design**
   - Mapped stakeholder questions to visuals
   - Removed charts that did not answer a clear question

4. **Visual Storytelling**
   - Clear hierarchy and layout
   - Minimal colour usage
   - Focus on comparison and causality

5. **Insight Validation**
   - Cross-checked insights against raw figures
   - Ensured every visual led to an actionable takeaway

---

## 7. Tools & Technologies

- Power BI  
- SQL (conceptual modelling and metric design)  
- GitHub (documentation and version control)  

---

## 8. What This Project Demonstrates

This case study showcases the ability to:

- Translate business problems into analytical questions  
- Design stakeholder-focused dashboards  
- Apply data storytelling principles effectively  
- Connect operational performance to financial impact  
- Communicate insights clearly to non-technical audiences  

---

## 🔗 Interactive Dashboard

👉 Explore the interactive Power BI dashboard here:  
https://app.powerbi.com/view?r=eyJrIjoiZjY5MmEzYWYtYTEzZi00OTMxLTljM2UtMTFmNDgzOWQ2Mzc1IiwidCI6ImNkOTA5ZjUwLTJjM2UtNDk0Mi1hNWE3LWE0Y2Y3NDUzOGVjYiIsImMiOjl9

---
