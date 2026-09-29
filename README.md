<h1 align="center">Hi, I'm Raúl 👋</h1>

<p align="center">
  <em>MSBA Candidate · FinOps Leader · Data Analyst</em><br/>
  Passionate about supply &amp; demand, health &amp; wellness, and bringing people together.
</p>

---

## 🙋 About me

- 📊 10+ years of experience in **FinOps** and data analysis
- 🎓 Currently pursuing my **Master of Science in Business Analytics (MSBA)**
- 💡 I love turning raw data into clear, actionable insights
- 🤝 Always happy to connect, collaborate, or just chat

---

## 🛠️ Tech stack

![SQL](https://img.shields.io/badge/SQL-025E8C?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Data Studio (Looker)](https://img.shields.io/badge/Looker%20Studio-4285F4?style=flat-square&logo=google&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![dbdiagram](https://img.shields.io/badge/dbdiagram-4A90D9?style=flat-square&logo=databricks&logoColor=white)
![SAP](https://img.shields.io/badge/SAP-0FAAFF?style=flat-square&logo=sap&logoColor=white)

---

## 📈 GitHub stats

<p align="center">
  <img src="./profile/stats.svg" alt="GitHub stats" />
  <img src="./profile/top-langs.svg" alt="Top languages" />
</p>

---

## 🗂️ Featured projects

### 💼 Personal Projects

### 📌 [Do Netflix's Rankings and Wikipedia Attention Agree?](https://raulsolanavarro.github.io/intl-streaming-measurement-check/)
A reconciliation of a first-party source (Netflix's weekly Top 10) against a third-party signal (Wikipedia pageviews) across six international markets over 12 weeks, covering 378 titles and 641 title-market pairs. The pipeline maps titles across sources through Wikidata, loads the data into BigQuery, and measures agreement by market with week-level bootstrap confidence intervals, alongside coverage gaps, attention timing, and the largest discrepancies. An independent pandas recompute validates every BigQuery result. The report closes with six recommendations for a measurement team, and an interactive [Tableau Public dashboard](https://public.tableau.com/views/Netflixvs_WikipediaInternationalMeasurementCheck/Dashboard) summarizes the findings. ([Code](https://github.com/RaulSolaNavarro/intl-streaming-measurement-check))

`Python` · `BigQuery` · `SQL` · `Tableau` · `Quarto` · `Wikidata API` · `Bootstrap Inference` · `Data Reconciliation` · `Audience Measurement`

---

### 🎓 Academic Projects

#### 📅 1st Semester — Fall 2025

## *CIS 9650 · Programming Tools for Analytics*
*Team Final Project*

### 📌 [NYC Restaurant Inspection Analysis](https://raulsolanavarro.github.io/reptalytics/reptalytics_report.html)
A live-data analysis of over 160,000 NYC Department of Health restaurant inspections from 2021 to 2024, uncovering trends in violation scores, borough-level grade differences (validated with ANOVA), closure rates, and the most common health code violations across cuisine categories.

`Python` · `Quarto` · `Data Analysis` · `NYC Open Data` · `Public Health`

---

#### 📅 2nd Semester — Spring 2026

### *STA 9750 · Software Tools for Data Analysis*

## 📌 [Assessing the Impact of SFFA on Campus Diversity](https://raulsolanavarro.github.io/STA9750-2026-SPRING/mp01.html)
*Mini Project 1*

A data-driven analysis exploring how the Supreme Court's *Students for Fair Admissions* decision has shaped demographic trends across U.S. college campuses.

`R` · `Data Analysis` · `Higher Ed Policy`

## 📌 [Know Your Time: Data-Driven Profiles for a Time-Tracking App](https://raulsolanavarro.github.io/STA9750-2026-SPRING/mp02.html)
*Mini Project 2*

An exploration of two decades of American Time Use Survey data, uncovering how different demographic groups spend their days and translating those patterns into actionable profiles for a gamified time-tracking app.

`R` · `Data Analysis` · `Time Use` · `Survey Data`

## 📌 [Who Goes There? US Internal Migration and Congressional Reapportionment](https://raulsolanavarro.github.io/STA9750-2026-SPRING/mp03.html)
*Mini Project 3*

An analysis of American Community Survey migration flow data tracing where Americans are moving, which cities are driving Texas's growth, and what it all means for congressional representation after the 2030 census. The project closes with a data-driven advertising strategy to protect Texas's political footprint.

`R` · `Data Analysis` · `Demographics` · `Migration` · `Political Geography`

## 📌 [Going for the Gold: Forecasting Team USA at LA 2028](https://raulsolanavarro.github.io/STA9750-2026-SPRING/mp04.html)
*Mini Project 4*

A sports analytics project building a four-factor statistical model to forecast Team USA's gold medal count at the 2028 Los Angeles Summer Olympics. The project scrapes over 10,000 medal records from Olympedia across all modern Summer and Winter Games using a custom caching web scraper, standardizes historical country codes across 130+ years of geopolitical change, and incorporates World Bank GDP per capita data via API. The model estimates three core effects (US baseline performance, host nation advantage, and new sport bonus) using parametric and bootstrap confidence intervals via the infer package, then combines them through a 1,000,000-draw Monte Carlo simulation. Model reliability is assessed through retrospective validation on 13 past host nations. Results are delivered as a polished fundraising brief for the LA 2028 Organizing Committee.

`R` · `rvest` · `tidyverse` · `infer` · `ggplot2` · `gt` · `Monte Carlo Simulation` · `Web Scraping` · `Bootstrap Inference` · `World Bank API` · `Olympedia` · `Quarto`

### 📌 [Does Neighborhood Income Affect NYC 311 Resolution Times?](https://raulsolanavarro.github.io/STA9750-2026-SPRING/individual_report_raul.html)
*Team Final Project - Individual + Group Summary*

An analysis of 12.6 million closed NYC 311 service requests (2022–2025) spatially joined to census-tract income data, testing whether lower-income neighborhoods experience longer resolution times. The raw gap is real (43% longer for the lowest-income quintile), but after controlling for complaint type and borough via OLS, bootstrap confidence intervals, and quantile regression, the disparity is shown to be driven by what neighborhoods report rather than differential treatment. Part of a four-person capstone project on segmented prioritization in city services ([joint summary report](https://raulsolanavarro.github.io/STA9750-2026-SPRING/summary_report.html)).

`R` · `sf` · `tidycensus` · `leaflet` · `quantreg` · `Spatial Analysis` · `Regression` · `NYC Open Data`

### *CIS 9660 · Machine Learning for Business Analytics*

## 📌 [Customer Churn Prediction Analysis](https://raulsolanavarro.github.io/CIS9660-2026-SPRING/churn-report.html)
*Team Final Project*

A binary classification study on telecom customer churn using the Kaggle Telco Customer Churn dataset. The project builds and evaluates a logistic regression model with interaction terms, tunes the classification threshold to prioritize recall, and translates the findings into actionable retention strategies for marketing teams.

`Python` · `Logistic Regression` · `Classification` · `Customer Analytics` · `Telecom`

### *CIS 9440 · Data Warehousing and Analytics*

## 📌 [NYC Traffic & Road Infrastructure Analysis](https://raulsolanavarro.github.io/nyc-analytics-project-rjsn/)
*Team Final Project*

A data warehousing project integrating NYC 311 Service Requests and DOT Automated Traffic Volume Counts (2020–2025) to investigate the relationship between traffic density and road infrastructure degradation across New York City's five boroughs. The project builds a Kimball star-schema dimensional model, implements a full ELT pipeline using the Socrata API, Google Cloud Functions, BigQuery, and dbt, and delivers a Data Studio (Looker Studio) dashboard answering two core analytics questions: does traffic volume correlate with complaint frequency, and does response time vary by borough?

`SQL` · `BigQuery` · `dbt` · `Looker Studio` · `Data Warehousing` · `Kimball` · `NYC Open Data` · `Python`

---

#### 📅 Last Semester — Fall 2026

*Projects coming soon.*

---

## 📬 Connect with me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raul-sola-navarro/)
[![Twitter/X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/RaulSolaNavarro)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://raulsolanavarro.github.io/STA9750-2026-SPRING/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:raulsolanavarro@gmail.com)

---

<p align="center"><em>Thanks for stopping by! 😊</em></p>
