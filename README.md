# Gapminder Exploratory Dashboard

Self-contained, offline interactive dashboard for the [Carpentries Gapminder dataset](https://swcarpentry.github.io/python-novice-gapminder/) — life expectancy, GDP per capita, and population across **142 countries, 1952–2007**.

## Quick start
Just open **`gapminder_dashboard.html`** in any modern browser (double-click it). No installation, no internet, no dependencies — the dataset is embedded directly in the HTML.

## Files
| File | Description |
|------|-------------|
| `gapminder_dashboard.html` | Interactive dashboard (KPI cards, scatter, trend line, bar charts, filters) |
| `gapminder_data.csv` | Original **wide** Gapminder format (3 columns per year: GDP, life expectancy, population) |
| `gapminder_long.csv` | **Tidy/long** format (one row per country-year-metric), with `continent` included |

## Dashboard features
- **KPI cards** — country count, median GDP per capita, average life expectancy, top gainer.
- **Bubble scatter** — life expectancy vs. GDP per capita; bubble size = population, color = continent, arrows show year-over-year movement, hover for details.
- **Life expectancy trend** — line chart by continent, 1952→2007.
- **Change by continent** — bar chart of Δ life expectancy.
- **Top 10 country gains** — bar chart.
- **Filters** — baseline year, current year, continent, and x-axis metric.

## Data source
Gapminder (UN, World Bank, OECD), as distributed in The Carpentries "Plotting and Programming in Python" lesson.
