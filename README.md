# Football Business Intelligence | Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Business%20Intelligence-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Analytics-1F6FEB?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Transformation-107C10?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML-Custom%20Visuals-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![SVG](https://img.shields.io/badge/SVG-Custom%20Graphics-FFB13B?style=for-the-badge)
![Portfolio](https://img.shields.io/badge/Project-Portfolio-111827?style=for-the-badge)

> A Business Intelligence solution designed to transform football operational data into an interactive analytical environment using Microsoft Power BI, DAX, Power Query, HTML and SVG.

> Uma solução de Business Intelligence desenvolvida para transformar dados operacionais do futebol em um ambiente analítico interativo utilizando Microsoft Power BI, DAX, Power Query, HTML e SVG.

---

# 🇺🇸 English

## Overview

This project is a Football Business Intelligence solution developed in Microsoft Power BI.

The objective was to transform operational and performance data into an analytical environment capable of supporting decision-making across different areas of a football organization.

The solution combines:

- Data modeling
- DAX
- Power Query
- Interactive Power BI visualizations
- HTML-based custom visual components
- SVG-based custom graphics
- Dynamic analytical elements
- Interactive tooltips
- Data-driven visualizations

The project was developed as a portfolio case to demonstrate both technical Power BI capabilities and the application of Business Intelligence concepts to a real-world football context.

---

## Business Context

Football organizations generate large volumes of data across multiple areas, including:

- Matches
- Ticket sales
- Stadium occupancy
- Revenue
- Memberships
- Players
- Squad composition
- Player characteristics
- Market value
- Performance attributes

The challenge was to organize these different data domains into an analytical structure that allows users to investigate performance through interactive dashboards rather than isolated spreadsheets or static reports.

---

## Project Objectives

The main objectives of the solution were:

- Consolidate football-related information into a structured BI environment
- Create an analytical data model suitable for Power BI
- Develop reusable DAX measures
- Analyze match and ticket performance
- Monitor stadium occupancy
- Analyze membership performance
- Analyze the active squad
- Create dynamic player profiles
- Provide interactive visual exploration
- Develop custom visual components using HTML
- Develop custom graphical components using SVG
- Transform raw data into actionable business information

---

# Dashboard Preview

## 01 — Matchday Analytics

![Matchday Analytics](screenshots/01-matchday.png)

The Matchday page provides an overview of match-related information and stadium performance.

---

## 02 — Matchday — Selected Game

![Selected Matchday](screenshots/02-matchday-selected.png)

When a match is selected, the dashboard dynamically updates its contextual information, including team logos and match-specific data.

The stadium visualization also works as a data-driven heatmap, allowing sector-level performance and occupancy to be visually explored.

---

## 03 — Membership Analytics

![Membership Analytics](screenshots/03-membership.png)

The membership analysis provides visibility into membership performance, revenue and related indicators.

---

## 04 — Squad Intelligence — Overview

![Squad Intelligence Overview](screenshots/04-squad-overview.png)

The Squad Intelligence page provides an overview of the active squad, including:

- Player distribution by position
- Age groups
- Nationalities
- Dominant foot
- Market value
- Player-level information

---

## 05 — Squad Intelligence — Player Detail

![Squad Player Detail](screenshots/06-daily-sales-tooltip.png)

The player detail experience provides a contextual profile for the selected player, including:

- Player image
- Shirt number
- Position
- Nationality
- Age
- Height
- Dominant foot
- Market value
- Performance attributes
- Dynamic visual analysis

---

## 06 — Interactive Daily Sales Tooltip

![Daily Sales Tooltip](screenshots/05-squad-player-detail.png)

An interactive tooltip designed to provide additional daily sales information without requiring a separate analytical page.

The tooltip allows additional context to be presented directly within the analytical workflow.
---

# Key Features

## Matchday Intelligence

- Match-level performance analysis
- Ticket sales analysis
- Stadium occupancy
- Revenue analysis
- Revenue by stadium sector
- Dynamic team logos based on match selection
- Data-driven stadium heatmap visualization
- Interactive filtering

## What Makes This Project Different

This project goes beyond standard Power BI visual configuration by combining native Power BI capabilities with custom HTML and SVG development.

The solution demonstrates how DAX can be used not only for analytical calculations, but also as part of the logic behind dynamic visual components.

Examples include:

- Dynamic player profile cards
- Dynamic team logos
- Data-driven stadium heatmap
- Dynamic nationality visualization
- Context-aware player analytics
- Interactive tooltips

## Membership Intelligence

- Membership revenue analysis
- Membership plan analysis
- Cancellation analysis
- Membership performance monitoring

## Squad Intelligence

- Active squad analysis
- Player profile analysis
- Position distribution
- Age distribution
- Nationality analysis
- Dominant foot analysis
- Player market value
- Player performance attributes

## Interactive Experience

The report incorporates several interactive and custom-built components, including:

- Cross-filtering
- Dynamic player profiles
- Dynamic team logos
- Dynamic nationality visualization
- Custom HTML components
- Custom SVG visualizations
- Interactive tooltips
- Context-aware KPIs
- Data-driven stadium visualization

---

# HTML & SVG Development

HTML and SVG were not used only as decorative elements.

They were applied as part of the technical development of the Power BI solution to create customized analytical components beyond the standard Power BI visual library.

## HTML

HTML was used to build customized visual components and interfaces within the Power BI report.

Applications include:

- Custom player profile cards
- Dynamic information layouts
- Custom analytical components
- Interactive-style visual structures
- Customized data presentation

## SVG

SVG was used to create custom graphical elements and data-driven visualizations.

Applications include:

- Stadium visualization
- Data-driven stadium heatmap
- Custom graphical elements
- Dynamic visual components
- Context-aware graphical representations

The combination of DAX, HTML and SVG allows the visual layer to respond dynamically to the current filter context and selected entities.

---

# Technical Architecture

The solution was developed using a structured Power BI analytical approach, separating data preparation, data modeling and analytical calculations.

## Data Preparation

Power Query was used to prepare and transform source data before loading it into the analytical model.

Main activities include:

- Data cleaning
- Data type standardization
- Attribute normalization
- Table preparation
- Analytical dimension preparation
- Fact table preparation

## Data Modeling

The model was structured around dimensions and fact tables to support:

- Match-level analysis
- Player-level analysis
- Sector-level analysis
- Membership analysis
- Time-based analysis
- Cross-filtering
- Reusable calculations

## Analytical Layer

DAX measures were developed to support the analytical logic of the report, including:

- Ticket sales
- Stadium occupancy
- Revenue
- Average ticket price
- Player counts
- Position analysis
- Age analysis
- Nationality analysis
- Market value
- Player attributes
- Dynamic visual components

## Presentation Layer

The presentation layer combines native Power BI visuals with custom HTML and SVG components.

This approach allows the solution to maintain the analytical capabilities of Power BI while providing a more customized user experience.

---

# Technology Stack

| Technology | Application |
|---|---|
| Microsoft Power BI | Data modeling, visualization and reporting |
| DAX | Analytical calculations, KPIs and dynamic visual logic |
| Power Query / M | Data transformation and preparation |
| HTML | Custom visual components and analytical interfaces |
| SVG | Custom graphics, stadium visualization and data-driven visual elements |
| Excel | Source data preparation |

---

# Advanced Power BI Features

The project demonstrates several Power BI development techniques beyond standard visual configuration.

## Dynamic Visual Logic

DAX measures are used to control visual behavior according to the current filter context.

Examples include:

- Dynamic player profiles
- Dynamic team logos
- Dynamic nationality analysis
- Dynamic player attributes
- Context-aware KPIs

## Custom HTML Components

HTML-based components were developed to create customized analytical interfaces that go beyond the standard Power BI visual library.

These components allow information to be structured and presented in a highly customized layout while remaining connected to the Power BI analytical context.

## SVG Visualizations

SVG was used to create custom graphical elements and data-driven visual components.

The stadium visualization is an example of how SVG can be combined with DAX-driven logic to create a visual representation that responds to analytical context.

## Stadium Heatmap

The stadium visualization was designed as a data-driven representation of sector performance.

The visual changes according to the underlying analytical context, allowing the user to visually identify differences between stadium sectors.

## Interactive Tooltips

Custom tooltip experiences were developed to provide additional analytical context without requiring the user to navigate away from the primary visualization.

---

# Repository Structure

```text
football-business-intelligence-powerbi/
│
├── data/
│   └── README.md
│
├── documentation/
│   ├── README.md
│   ├── data-model.md
│   ├── dax.md
│   └── power-query.md
│
├── report/
│   ├── README.md
│   └── DASHBOARD_FUTEBOL_PORTIFOLIO.pbit
│
├── screenshots/
│   ├── 01-matchday.png
│   ├── 02-matchday-selected.png
│   ├── 03-membership.png
│   ├── 04-squad-overview.png
│   ├── 05-squad-player-detail.png
│   ├── 06-daily-sales-tooltip.png
│   └── README.md
│
├── .gitignore
└── README.md
