# 🏆 Oscars Database & Analytics App

A full-stack data platform that scrapes, stores, and analyzes 96 years of Academy Awards (Oscars) data using custom-built pipelines. The system enables users to explore nominations, win patterns, and create their own hypothetical award predictions.

## Project Overview

This project involved building an end-to-end system starting from schema design to web scraping, database population, and a Flask-powered web interface.

### Key Features:
- Scrapes structured data from 96 Wikipedia pages (1st–96th Academy Awards)
- Handles nested actor/director/producer pages and inconsistent HTML formats
- Normalized relational schema in MySQL
- Flask web application for querying and displaying insights
- User registration, login, and custom nomination features
- Advanced queries (e.g. top directors by wins, non-English Oscar winners, dream team generator)

## Tech Stack

- **Python** (BeautifulSoup, Flask)
- **MySQL** (remote DB hosted via db4free.net)
- **HTML/CSS** (for frontend templates)

## Database Design

- ERD and relational model designed to represent complex relationships between:
  - Movies
  - People (actors, directors, producers, etc.)
  - Awards and categories
  - Nominations and outcomes

## Learning Outcomes

- End-to-end data pipeline construction
- Web scraping at scale and handling noisy, inconsistent sources
- Real-world database modeling and integration
- Building dynamic query-based web applications

## How to Run

1. Clone the repository
2. Inside the folder, locate and double-click the `run_oscars_app.exe"` file
3. A terminal window will open and display a local server link — usually something like: Running on http://127.0.0.1:5000
4. Copy that link from the terminal and paste it into your browser (e.g. Chrome)
5. You’ll be directed to the Oscars web app interface
