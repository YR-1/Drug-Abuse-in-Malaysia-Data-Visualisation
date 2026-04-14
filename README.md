# Drug Abuse in Malaysia Data Visualisation

An interactive data visualisation project exploring drug abuse patterns in Malaysia using **Vega-Lite**, **Vega**, and **vega-embed**.

The main dashboard is located in `DV2/`, with additional prototype and supporting visualisation work in `W9Homework/` and `W10Homework/`.

## Overview

This project presents multiple views of drug abuse trends in Malaysia from **2016 to 2020**, including:

- geographic distribution by state
- demographic trends by race
- education level breakdowns
- occupation based patterns
- changes in drug type usage over time

The visualisations are designed to make the data easier to explore through a combination of narrative text, interactive charts, and map based views.

## Main Visualisations

The `DV2/` dashboard includes:

1. **Choropleth Map** - drug addiction rate per 100,000 population by state
2. **Stacked Area Chart** - number of cases by race across years
3. **Lollipop Chart** - number of abusers by education level with year selection
4. **Heatmap** - number of cases by occupation and year
5. **Dumbbell Chart** - change in number of abusers by drug type between 2016 and 2020

## Project Structure

```text
3179-main/
├── DV2/
│   ├── css/
│   ├── data/
│   ├── js/
│   ├── FIT3179_A2_5DS.pdf
│   └── index.html
├── W9Homework/
│   ├── choropleth_map.vg.json
│   ├── index.html
│   ├── malaysia_states.topojson
│   ├── number_addicts_by_state.csv
│   └── styles.css
└── W10Homework/
    ├── css/
    ├── data/
    ├── js/
    └── index.html
```

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript**
- **Vega**
- **Vega-Lite**
- **vega-embed**

## Data Files

The dashboard uses datasets stored in `DV2/data/`, including:

- `number_addicts_by_state.csv`
- `number_addicts_by_race.csv`
- `number_addicts_by_education.csv`
- `number_addicts_by_occupation.csv`
- `number_addicts_by_type.csv`

Geographic boundaries are provided through `DV2/js/malaysia_states.topojson`.

## Data Sources

The project references data from:

- **AADK (National Anti-Drugs Agency, Malaysia)**
- **data.gov.my**
- **citypopulation.de**
- Malaysia state boundary data in **TopoJSON** format

Additional source details are listed in `DV2/index.html`.

## Running the Project

This is a static web project, so no build step is required.

### Open directly

Open `DV2/index.html` in a browser.

### Run with a local server

Using a local server can help avoid browser restrictions when loading local files.

```bash
cd DV2
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Author

**Liew Yun Ru**
