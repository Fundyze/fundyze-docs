<div align="center">
    <img src="../assets/logo_transparent.png" alt="Fundyze's logo" width="150" height="150">
    <h1 align="center">Fundyze - Specifications</h1>
    <p align="center">
        Fundyze is an intelligent investment assistant that helps analyze companies, evaluate stocks, and select promising crypto assets.
    </p>
</div>

## 1. Context and Objectives

Fundyze aims to empower users with intelligent tools for investment analysis. By leveraging **Large Language Models (LLMs)** and modern data processing techniques, the platform simplifies the investment process and enhances decision-making for both novice and experienced investors.

The application will provide:
* A **user-friendly** interface to collect user investment preferences.
* Automated **analysis of financial reports**, company filings, news articles, and social media sentiment.
* Tailored **recommendations** for stocks, cryptocurrencies, and other investment opportunities.

Fundyze is designed to be **scalable and evolutive**, allowing new features and capabilities to be added over time. The long-term vision is to become a trusted digital assistant for personal and professional investment strategies.

---

## 2. Target Audience and Use Cases

**Target audience**
* Individual investors (beginner to intermediate level).
* Enthusiasts looking to explore both traditional stocks and emerging assets like cryptocurrencies.

**Use cases**
* Conducting fundamental analysis of stocks and cryptocurrencies.
* Evaluating opportunities based on user-defined criteria (risk profile, sectors, sustainability, etc.).
* Monitoring market sentiment and the impact of news on asset prices.
* Generating personalized reports summarizing key insights and recommended actions.

---

## 3. Core Features (MVP vs Future Enhancements)
**Minimum Viable Product (MVP):**
* User authentication and cloud storage.
* User preferences for investment strategies and risk tolerance.
* Upload company financial statements or get data from public APIs.
* Analyze individual assets
* Provide simple buy/hold/sell signals based on user preferences.
* Generate summary reports in plain language.
* Export reports in various formats (PDF, PNG, etc.).

**Future Enhancements:**
* Sentiment analysis from news and social media.
* Crypto asset scoring and trend predictions.
* Portfolio tracking and diversification recommendations.
* Alerts and notifications for significant market events.
* Advanced analytics & visualization.

--- 

## 4. Architecture Overview
* Frontend: **React**-based application, with a clean and interactive UI.
* Backend: A **Rust**-based API server handling business logic and data processing.
* Database: **MongoDB** for storing user data, investment preferences, and analysis results.
* AI/LLM Integration: **Groq**
* Deployment: **Dockerized services**

> [!NOTE]  
> Fundyze, being a website developed and distributed in France, will fully comply with RGPD regulations to ensure the protection of its users’ personal data, considering the sensitive nature of this information, particularly in the financial and investment domains.