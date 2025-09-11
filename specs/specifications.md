<div align="center">
    <img src="../assets/logo_transparent.png" alt="Fundyze's logo" width="150" height="150">
    <h1 align="center">Fundyze - Specifications</h1>
    <p align="center">
        Fundyze is an intelligent platform that helps analyze emerging companies, evaluate their potential, and identify promising investment opportunities.
    </p>
</div>

## 1. Context and Objectives

Fundyze aims to empower users with intelligent tools for **company analysis** and **investment decision-making**.  
By leveraging **Large Language Models (LLMs)** and reliable data sources (financial APIs, company filings, news, and social media), the platform provides clear and comprehensive insights into promising businesses.

The application will provide:
* A **user-friendly interface** to explore companies and their key metrics.
* Automated **analysis of financial data, management, products, and market trends**.
* A scalable and evolutive system designed to integrate new features over time.

The long-term vision is to become a **trusted digital assistant for investors**, helping them track opportunities and make informed decisions.

---

## 2. Target Audience and Use Cases

**Target audience**
* Individual investors seeking to discover emerging companies.
* Professionals looking for **decision support tools** to evaluate new opportunities.

**Use cases**
* Searching for a company and generating a detailed report (financials, hierarchy, products, news).
* Identifying **trending companies** through automated analysis.
* Comparing two companies to support investment choices.
* Receiving **alerts** when important news affects followed companies.
* Exploring tailored AI-generated insights: risks, opportunities, and growth potential.

---

## 3. Core Features (MVP vs Future Enhancements)
**Minimum Viable Product (MVP):**
* Public homepage explaining the platform’s purpose.
* User authentication and personal dashboard.
* Search bar to look up a specific company.
* Advanced search filters (by sector, risk profile, ESG factors, etc.).
* Section with ~10 **trending companies** (updated periodically).
* Detailed company reports including:
  - Financial data (revenue, profits, debts, valuation ratios, etc.).
  - Hierarchy (CEO, key executives).
  - Products and services offered.
  - Summary of recent trends (news, performance, market moves).
  - AI-generated analysis: strengths, risks, and opportunities.

**Future Enhancements:**
* **Notifications**: alerts for major news/events about followed companies.
* **Company comparison**: side-by-side reports to support investment decisions.
* Integration of a news/blog section and **mobile application**.

--- 

## 4. Architecture Overview
* Frontend: **React**-based application, with a clean and interactive UI.
* Backend: A **Rust**-based API server handling business logic and data processing.
* Database: **MongoDB** for storing user data, investment preferences, and analysis results.
* AI/LLM Integration: **Groq**
* Deployment: **Dockerized services**

> [!NOTE]  
> Fundyze, being a website developed and distributed in France, will fully comply with RGPD regulations to ensure the protection of its users’ personal data, considering the sensitive nature of this information, particularly in the financial and investment domains.