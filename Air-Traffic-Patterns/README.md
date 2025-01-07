# Air Traffic Patterns Analysis

**This project, developed for the DS3000 course, analyzes air traffic patterns across California, Nevada, and Arizona, focusing on flight behaviors, delays, and airline performance.**

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Objectives](#project-objectives)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)

## Introduction

The goal of this project is to analyze air traffic patterns among California, Nevada, and Arizona by comparing states, airports, and carriers. Key aspects explored include:
- Identifying the most popular airports.
- Determining which carriers have the largest share of flights and the best performance records.
- Understanding delay patterns and total flight hours across airlines.

By leveraging visualizations and statistical analysis, this project provides insights into regional air traffic trends.

## Dataset

The dataset used in this project comes from the **Bureau of Transportation Statistics** and includes flight data from 1987 onward. For this analysis, the year 2019 was selected for a focused examination. Key data features include:
- **Flight Times**: Departure and arrival times, delays, and total flight hours.
- **Airports**: Origin and destination states and airports.
- **Carriers**: Airline codes and performance records.

### Data Cleaning
- **Imputation**: Missing values for arrival and departure delays were handled.
- **Deletion**: Rows with missing or invalid elapsed times were removed.

## Project Objectives

1. Compare air traffic between California, Nevada, and Arizona, identifying the state with the highest traffic.
2. Identify the top 5 popular airport destinations in each region.
3. Analyze the proportion of flights by carrier and their delay patterns.
4. Evaluate total flight hours and performance records for the top 10 airlines.

## Features

- **State-Level Analysis**: Compares air traffic across the three states, highlighting California as the state with the most traffic.
- **Airport Insights**: Identifies major airport destinations like DEN (Denver), SFO (San Francisco), PHX (Phoenix), LAX (Los Angeles), and SEA (Seattle).
- **Airline Performance**: Examines flight proportions, average delays, and total flight hours per month for major carriers.
- **Visualization Tools**: Bar graphs and statistical summaries for clear and informative presentations.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/diya-ganesh/DS3000-Practicums.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd DS3000-Practicums/Air-Traffic-Patterns
   ```
3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Prepare the Data**:
   - Ensure the flight dataset is properly placed in the designated directory.
2. **Run Analysis**:
   ```bash
   python analyze_traffic.py
   ```
3. **View Results**:
   - Outputs will include visualizations and statistical insights into air traffic patterns.

## Contributors

- **Diya Ganesh**, **Emma Penn**, **Brianna Quinn**: Developers and analysts.

## Conclusion

This project highlights California as the region with the most significant air traffic and identifies popular airport destinations across states. Southwest Airlines emerges as a dominant carrier, with Hawaiian Airlines showcasing excellent performance in terms of minimal delays.

---

For more information, see the [project repository](https://github.com/diya-ganesh/DS3000-Practicums/tree/main/Air-Traffic-Patterns).
