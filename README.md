# TV Show Viewership Analysis — Person of Interest

A short data report analysing the U.S. viewership trends of the CBS drama *Person of Interest* (2011–2016), created as part of a university assignment on reproducible reporting with Quarto.

## Contents

| File | Description |
|------|-------------|
| `report.qmd` | Main Quarto source file |
| `report.html` | Rendered output (open this in a browser) |
| `poi_viewership_episodes.png` | Episode-by-episode viewership chart |
| `poi_viewership_avg.png` | Average viewership per season chart |
| `poi_viewership_change.png` | Season-to-season change chart |
| `images.jpg` | Person of Interest Poster|

## How to Render

1. Install [Quarto](https://quarto.org/docs/get-started/)
2. Install Python dependencies:
   ```bash
   pip install matplotlib pandas jupyter
   ```
3. Render the report:
   ```bash
   quarto render report.qmd
   ```
   This produces `report.html` in the same folder.

## Data Source

Viewership data sourced from [Wikipedia — List of Person of Interest episodes](https://en.wikipedia.org/wiki/List_of_Person_of_Interest_episodes), originally measured by Nielsen Media Research.

