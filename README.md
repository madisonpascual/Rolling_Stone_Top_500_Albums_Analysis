# Rolling Stone Top 500 Albums Analysis

## Overview
This project analyzes the **Rolling Stone Top 500 Albums of All Time (2020 edition)** dataset.  
The dataset includes details such as album title, artist, release year, genre, Billboard chart performance, and Spotify popularity.  

The goal of the project was to explore factors associated with chart success, including:
- Peak Billboard position (outcome variable)
- Number of weeks on Billboard charts
- Album genre
- Spotify popularity

## Methods
- **Data Cleaning & Preparation**
  - Standardized inconsistent genre labels
  - Created new variables (e.g., `peaked_yes_no`, `long_time_billboard`)  
  - Converted categorical outcomes into numeric form for correlation analysis

- **Exploratory Analysis**
  - Univariate distributions (e.g., peak positions, weeks on chart)
  - Bivariate relationships (e.g., peak position vs. genre, time on Billboard vs. #1 peak)
  - Correlation between Billboard peak position and Spotify popularity

- **Visualization**
  - Histograms, bar charts, boxplots, and scatterplots created using `ggplot2`
  - Emphasis on distribution patterns and genre-level trends

## Key Findings
- Albums peaking in the **top 5** dominate the distribution of peak Billboard positions  
- **Hip-Hop/Rap** albums had the strongest average performance, while smaller genres (e.g., Afrobeats) ranked lower due to limited representation  
- A **moderate positive correlation** exists between reaching #1 on Billboard and spending at least 20 weeks on the charts  
- A **moderate negative correlation** was observed between Billboard peak position and Spotify popularity (higher Billboard peaks tend to align with higher streaming popularity)

## Tools & Packages
- **Language**: R  
- **Libraries**: `ggplot2`, `knitr`  
- **Output**: HTML report with inline code, plots, and interactive elements  

## Future Work
- Expand predictors to include artist-level data such as social media presence, touring history, and global reach  
- Compare results across decades to reveal cultural and industry shifts in music consumption  
- Explore additional streaming platforms beyond Spotify  

## References
- Rolling Stone (2020). [*Top 500 Albums of All Time*](https://pudding.cool/2024/03/greatest-music/)  
- Billboard (2024). [*Billboard Charts*](https://www.billboard.com/charts/)  
- Artist Tools (2024). [*Spotify Popularity Index*](https://www.artist.tools/features/spotify-popularity-index)  
