# Fantasy College Basketball Platform

A mobile-first application that transforms NCAA Division I men's basketball data into a fantasy basketball platform.

The project demonstrates an end-to-end data pipeline, beginning with automated web scraping in **R**, continuing through data transformation and modeling using **Google Sheets and SQL-like Query Language**, and culminating in an interactive JavaScript application deployed on **Github Pages**.

The application provides league participants with real-time standings, player analytics, draft history, transaction tracking, roster management, and daily scoring.

**Live Demo:** https://pollackelliott.github.io/fantasy-college-basketball

---

## Technologies

**Data Engineering**
- R
- Web Scraping
- Google Sheets
- Google Sheets Query Language (SQL-like)
- Data Modeling
- ETL

**Application Development**
- JavaScript
- HTML
- CSS

**Deployment**
- Github Pages

---

## Overview

Fantasy College Basketball is an end-to-end data engineering and analytics project that demonstrates how raw sports data can be transformed into a production-ready web application.

The system automatically collects NCAA Division I men's basketball statistics, processes and models the data, stores it in Google Sheets, and presents it through an interactive web application deployed with GitHub Pages.

Rather than serving as a static website, the project functions as a lightweight analytics platform that combines data engineering, business intelligence, and front-end development.

---

## Architecture

```text
NCAA Basketball Statistics
            │
            ▼
Custom R Web Scraper
            │
            ▼
Data Cleaning & Transformation
            │
            ▼
Google Sheets Data Layer
            │
            ▼
JavaScript Data Processing
            │
            ▼
Interactive Web Application
            │
            ▼
GitHub Pages Deployment
```

---

## Features

### Automated Data Pipeline

- Custom R script scrapes NCAA Division I player statistics
- Automated data cleaning and transformation
- Structured data storage in Google Sheets
- Browser-based data retrieval and processing

### Fantasy League Management

- League standings
- Daily scoreboards
- Team roster pages
- Draft board
- Transaction history
- Free agent tracking
- Player game logs

### Analytics

- Total Points + Rebounds + Assists (PRA)
- Per-game statistics
- Historical player performance
- Team and conference filtering
- Dynamic player rankings
- Drill-down player analytics

### User Experience

- Mobile-first responsive design
- Light and dark mode
- Persistent user preferences
- Interactive filtering
- Fast client-side navigation

---

## Data Engineering Concepts Demonstrated

- Automated web scraping using R
- ETL pipeline design
- Data cleaning and normalization
- SQL-like querying with Google Sheets Query language
- Multi-table data modeling
- Relational data integration
- Client-side data transformation
- Aggregation and ranking algorithms
- Derived metric calculation
- Analytics application development

---

## Technologies

### Data Engineering

- R
- Web Scraping
- Google Sheets

### Application

- JavaScript
- HTML
- CSS

### Deployment

- GitHub Pages

---

## Repository Structure

```
/
├── index.html
├── README.md
└── assets/
```

---

## Future Enhancements

- Additional historical analytics
- Expanded player visualizations
- Automated scheduled data refreshes
- Enhanced league administration tools
