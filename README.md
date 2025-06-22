# Streamlit FIFA Project

<p>A Streamlit application for visualizing and exploring FIFA player data interactively. </p>

## Summary

1. [Overview](#overview)
2. [Project Structure](#project-structure)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Running](#running)

## Overview

This project provides an interactive **Streamlit dashboard** to:

- Load and explore FIFA datasets.
- Navigate through multiple pages.
- Display insights using charts, filters, and tables.

## Project Structure

📦datasets
┣ 📜CLEAN_FIFA17_official_data.csv
┣ 📜CLEAN_FIFA18_official_data.csv
┣ 📜CLEAN_FIFA19_official_data.csv
┣ 📜CLEAN_FIFA20_official_data.csv
┣ 📜CLEAN_FIFA21_official_data.csv
┣ 📜CLEAN_FIFA22_official_data.csv
┗ 📜CLEAN_FIFA23_official_data.csv

📦pages
┣ 📜2*🏋️_players.py
┗ 📜3*⚽*teams.py
1*🏠_home.py

## Requirements

Make sure you have the following installed:

- Python 3.7+
- Required libraries (typically):
  - `streamlit`
  - `pandas`
  - `pathlib`
  - `webbrowser`
  - `datetime`
  - Any other packages used in the scripts

## Installation

- pip install streamlit pandas webbrowser

## Running

- git clone https://github.com/GustavoBiscaro/streamlit_fifa_project.git
- <strong>Para rodar localmente:</strong><br>
  <em>python -m streamlit run spotify.py</em>
