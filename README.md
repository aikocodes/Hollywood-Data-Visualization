# Hollywood-Data-Visualization

Hollywood data visualization project using IMDB data to analyze film industry structure and trends. The project focuses on three core analyses: long-term production trends, genre correlations, and director–actor collaboration networks, implemented through interactive visualizations.

## Overview

This project uses large-scale IMDB datasets to explore how Hollywood films evolve over time, how genres co-occur, and how creative labor is structured through collaboration networks. The emphasis is on scalable data processing and interactive exploration.

## Features

- Interactive time-series visualization of film production over time
- Genre correlation analysis highlighting co-occurring genres
- Director–actor collaboration network built from IMDB crew data
- Network visualization with role-based coloring and connectivity patterns

## Data

The project is based on publicly available IMDB datasets:
- title.basics.tsv
- title.ratings.tsv
- title.crew.tsv
- name.basics.tsv

The data is cleaned and aggregated to support efficient analysis and visualization.

## Technologies

- Python
- Pandas
- NumPy
- Plotly
- NetworkX
- Jupyter Notebook
- PyArrow

## Setup

1. Clone the repository:
   git clone https://github.com/aikocodes/Hollywood-Data-Visualization.git
   cd Hollywood-Data-Visualization

2. Install dependencies:
   pip install -r requirements.txt

3. Launch Jupyter Notebook:
   jupyter notebook

4. Run the notebooks in order from tsk1.ipynb to tsk4.ipynb.

## Notes

- IMDB datasets are large and may not be included directly in the repository.
- Interactive visualizations are best viewed in Jupyter Notebook or exported as HTML.

## Author

Aiko Kato  
Pomona College — Computer Science & Digital Media Studies
