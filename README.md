# ADHD-Music
The code and dataset to replicate 
# Replication Files for "The Role of Music in ADHD: A Multi-Dimensional Computational and Theoretical Analysis"

This repository contains all the necessary data and code to replicate the results and figures presented in the paper titled **"The Role of Music in ADHD: A Multi-Dimensional Computational and Theoretical Analysis"**.

## 📁 Contents

- `papercode.Rmd`: R Markdown file with the complete replication code for generating all figures and results in the paper.
- `cats.csv`: Contains categorization of Reddit posts into three categories:
  - **Gneral purpose**
  - **Focus music**
  - **Stuck Songs**

- `lyricsdata.csv`: Dataset containing song lyrics scraped from Genius API. These are the lyrics of songs mentioned in Reddit comments related to ADHD and music.
- `songsdata.csv`: Dataset with audio features of songs extracted from the Spotify API. Includes attributes like:
  - Danceability
  - Energy
  - Valence
  - Tempo
  - Acousticness
  - Speechiness
  - and more.

## 📊 How to Reproduce the Analysis

1. Open `papercode.Rmd` in RStudio or any R Markdown-compatible environment.
2. Ensure all three CSV files (`cats.csv`, `lyricsdata.csv`, and `songsdata.csv`) are in the same directory as the `.Rmd` file.
3. Knit the R Markdown file (`papercode.Rmd`) to HTML or PDF to reproduce the figures and analysis presented in the paper.

## 🔧 Dependencies

The R Markdown file uses the following R packages (install them using `install.packages()` if not already installed):

```r
tidyverse
ggplot2
dplyr
stringr
readr
tidytext
tm
wordcloud
spotifyr
geniusr
knitr
