# Recreational-Open-Spaces-in-Kumasi-Metropolis
# The State and Sustainable Use of Recreational Open Spaces in Kumasi Metropolis

📄 Full Report: [View Analysis](THE STATE AND SUSTAINABLE USE OF RECREATIONAL OPEN SPACES IN KUMASI METROPOLIS.html)

## Overview
This project assesses the current state of recreational open spaces (ROS) in Kumasi Metropolis, Ghana, exploring their physical conditions, factors driving decline, and sustainable management strategies to ensure long-term availability and effective use. Based on a 2025 survey of 150 residents, the analysis reveals widespread deterioration amid urbanization pressures, with 88.7% reporting conversions to commercial and residential uses, and 60% of ROS perceived as poorly maintained or abandoned. By integrating demographic insights, statistical associations, and resident preferences, the study highlights opportunities for government-led maintenance and community engagement to enhance ROS functionality and preservation, contributing to urban sustainability and public well-being in rapidly growing cities.

## Dataset Summary
- **Source**: Primary survey data from residents of Kumasi Metropolis, Ghana (2025).
- **Sample Size**: 150 respondents.
- **Key Variables**: Demographics (age, gender, education, occupation, residence length); ROS conditions (physical state, functionality, safety ratings, facilities); decline factors (conversions, deterioration causes, barriers); management preferences (sustainability measures, responsibility, support ratings).
- **Note**: Raw data is not included due to confidentiality. Please contact me for collaboration requests.


## Objectives
- Evaluate the physical state and functionality of existing recreational open spaces in Kumasi.
- Investigate the factors contributing to the decline of recreational open spaces in Kumasi.
- Identify sustainable management frameworks for the development and preservation of recreational open spaces in Kumasi.


## Methods
- Descriptive statistics (frequencies, means, cross-tabulations) and visualizations (histograms, bar plots, boxplots) for profiling demographics and ROS perceptions.
- Inferential analyses including chi-square tests for associations (e.g., gender and condition), t-tests for group differences (e.g., safety by gender), linear/logistic regressions for predictors (e.g., safety ratings, functionality).
- Hypothesis testing via chi-square, GLM, and regression models to evaluate maintenance, urbanization, and management impacts.

## Key Findings
- ROS conditions are predominantly poor, with 60% abandoned or poorly maintained, 58.7% non-functioning, and moderate safety ratings (mean 2.75); males report lower safety (p<0.001) and poorer conditions (p<0.001) than females.
- Decline is pervasive (88.7% noticed), driven by poor maintenance (26%), abandonment (20%), and conversions to commercial (52.6%) and residential (27.1%) uses; lack of facilities (77.3%) is the top barrier to use.
- Sustainable frameworks emphasize government-led maintenance (54.7% preferred, 59.3% responsible) and land-use policies (29.3%), with strong resident support for community participation (mean 4.35) and preservation (mean 4.01).
- Hypotheses: H1 partially supported (maintenance reduces deterioration, p<0.001, but functionality OR=2.03, p=0.077); H2 strongly supported (conversions linked to conditions, p<0.001); H3 strongly supported (frameworks boost utilization, p=0.018, and preservation, R²=0.680).



## How to Reproduce the Analysis
### Requirements
- R (version 4.0 or higher)
- RStudio
- R packages: tidyverse, ggplot2, dplyr, stats, broom

### Steps
1. Clone this repository.
2. Open `analysis.Rmd` in RStudio.
3. Install required packages if not already installed (e.g., `install.packages(c("tidyverse", "ggplot2"))`).
4. Knit the R Markdown file to generate the HTML report.
Data not included due to confidentiality. Please contact me for collaboration requests.

## Repository Structure
├── analysis.Rmd         # R Markdown source file  
├── analysis.html        # Knitted HTML report  
├── figures/             # Plots and visualizations  
├── README.md            # Project description  

## License / Citation
This project is for academic and research purposes. Please cite appropriately if referenced, e.g., Sei, Lawrence. (2025). The State and Sustainable Use of Recreational Open Spaces in Kumasi Metropolis.
