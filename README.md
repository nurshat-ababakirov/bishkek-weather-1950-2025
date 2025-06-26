# Bishkek Climate Trends Analysis

This repository contains scripts and visualizations used to analyze long-term climate trends in Bishkek, Kyrgyzstan. The analysis draws on daily weather observations to evaluate changes in precipitation, snowfall, rainfall frequency, and seasonal temperature patterns from 1949 to present. It includes trend forecasting up to 2040.

## Overview

The project investigates how key climate indicators have evolved over time, with a focus on:

- Average annual precipitation (cm)
- Number of rainy days per year
- Frequency of snowfall
- Seasonal temperatures (mean, min, max)
- Trend projections through 2040

The goal is to support evidence-based awareness on climate shifts using publicly accessible weather data and reproducible methods.

## Features

- Clean preprocessing and aggregation of weather data by year and season
- Rolling average smoothing for seasonal trends
- Forecasting temperature and precipitation patterns using linear regression
- Custom visualizations with consistent styling for publication-quality plots
- Bilingual plotting support (Kyrgyz/English)

## File Structure

├── data/ # Source and cleaned weather datasets
├── notebooks/ # Jupyter notebooks for analysis and plotting
├── figures/ # Exported charts and visual outputs
├── scripts/ # Python scripts for data processing
├── README.md # Project overview and usage
