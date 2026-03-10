# Penguin Analysis

A reproducible analysis of morphological measurements from the Palmer Penguins dataset, examining variation in body dimensions across penguin species in the Palmer Archipelago, Antarctica.

<img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxMTEhUSExMVFRUVFRUVFxcVFRcVFRcVFRUXFhUVFxUYHSggGBolHRUVITEhJSkrLi4uFx8zODMtNygtLisBCgoKDg0OFxAQGC0dHR0rKy0rLS0tLS0rKy0rLS0tLS0rLS0tLS0tLS0tLS0tLS0tLS0rLS0tLS0rLSstLS0tK//AABEIAPIApQMBIgACEQEDEQH/xAAbAAACAwEBAQAAAAAAAAAAAAAAAQIDBAUGB//EADYQAAIBAwEGAwYGAgIDAAAAAAABAgMEESEFEjFBUWEGE5EiMnGBodFSYnKxweEUQoKSBxUj/8QAGQEBAAMBAQAAAAAAAAAAAAAAAAECBAMF/8QAIxEBAAMBAAMAAgIDAQAAAAAAAAECEQMSITEEQSIyUWFxE//aAAwDAQACEQMRAD8A+HAAIADAMAAAyMBAgAAwCDIAAIAAAwGQAB5EAAGAAAQDEAAAAAFlai4txfFFYCHkAwAABpo2M5a4wur0AzDwbHsyXWD+b+xRWtJxWZRa76NfQCkAGkAkW0recvdi38v5Oja2cYayWZdOS7dzRKqwOU7Cp+B/uUTg1o018TrOvjn6F0biMliaTXfivgBwQOntDZmFvQy49Oa/o5mAAYgAEABkAAAA6u14Ze8cpnVvJtp6nLkUp8X6fSHHoJI2bNpre3n/AK/u+BdRqs7bc9qSzL9v7NG9KTwk23wws/QVCjKpNQgk5N4X3fY9zsfZVOgtMOb4yx9F0Rz6dIo68+U3n/TgWnhWtNZk4w7Pj6I30fCMkta0Xnk4afuekU2TjMyz3u1x+PSHhPEPg2cUp0E5596EeWnGPbseetbWVOTlOLi1w3k1rzPr0ZFd3Z06sd2pFSXf+HyLV/In9qW/Gj9PlbrJ69SupU7/AE69z1O2PAqeZUJf8ZfxL7njL6wqUZbtSLi+64/B8zTW9bfGW/O1fqbuo9/QX+THuZAZdR2rS5xjpjn9TNtS0x7cV7L+jMlvUw9Xp9D0ezaHnW9xHjuxU0+8Xl/TIHlsAA0wAWAAAAGIDRWrZ5+nApEMAN1p7j/V+yX3MB6jwTsvzp70vdpyz8ZNLCfwxki05GprXynHofC2yPKhvtf/AEnq/wAq6fHqehhb44jc4xRmleLJ595m07L06VisZDZgN0xO9QleFMX10FTY1TfQzU75dTXTu0AuBTd2dOtHcqRUl3NraaK5U+aJ+I+vnHiTwc6OalHMoc1xlH7o8kfckzxfi/wqpJ1qKw+Mopce6NXLtvqzJ14Z7q8Cj6P4UsPLtK0pcXTnx/ScHw74ecpKUuGeZ6nxjeKjZunF61MRS7ZW8/TT5mhlfLGgQMESg0JoaEwAAYgJAHoJAM+neG7TybaMcJSl7cn3f9YR852bb+ZVhD8Ukn8M6/TJ9Lvr1R9lctDh3n1ENP41fcyp2hdNaZOXK5fUruK+WYnUZyrVotZ0VdSXMsV6+pyJTxzFVusLGGW8FP8A0x3ad8uZbC/Z5dX/AG4fA10L3JWea1euvXWO1up2aN5FnhadTmb7S8a0Oc1z46RZ7FxTK5Jric6yvMnVhPK1KLOPtCcKEXVlpFdOvRHzPb+15XNRzekVpFdF9z65fWcakJU5LMZLD+58d2vYSoVZU5LVPTo1xTNfC+xk/WH8jn4zsfJYRgBoZzgtUnwysltenHL3Xpy1RSNIBAIAPZ+KLeDpx8uMcqX+iWcY7HlZ2dT8EvQ0Kp+ZfNooc0n7/wBP5Zy5c5pXx3XXpeLzuY6Xhq2lGvGUo4UVJ/PH9nplbyqcPVnn/DOHV95t7jfDGmn3PVyvd3RI5dd134Z4q6exI/7SZohsekuWTM78Sv2ctl3yG1bNp/hQ1syjzgjIrx9Scb+Q2U5C+psG3l/ojDceFIPWE3F+qNKv2WK7kPKYRNKz+nm7mxr0PejmP4lqvn0CjepnqKN5nRnN2tsSM1vUkoz44XB/ZlotE/VZpMfErOtnDR6PZ91nRnzqjeTpTxJNNcU1g9bYbTpuG83jGPXgVvSYWpeJeinM8d/5C2apQjcJe1HEZfpfB+r+p658M+pnvbdVKcoS4STX2fqVpbxtEp6V8qzD4uycaT6M6Vex3HKMsNxbT010eCv/AB1ngvRHoQ8yYxjdu+q9SCS649fsblQ/KgdLsiUNGxrinTUt6SecYx2z1+IijyXywvoBSaRM66V6TEY0y7pemUNTa0xH/qkaXTQeWuhdzathSe9Nr8PTq19js/4rk+xi2HDCm/gv3Z1fN0MvWf5TDbxjKxJLZ8eopWcSl3bD/KbOPto9Ju2xzEqeO5W6zIuu0PaNa1SyTVCS5GWFyzoW97lYZE6mMVyt9C+1iyaqpl1GHNFdWV1dnU6kk5wTa54OZtXYCw5UnjOrjyPSRRComIvMImsShYTbglLjgti+RGEcCm9Supx4/wAXbNUaqqpe+tf1I4ToH0Ta1n5tJx58V8UeW/8ASy/EvQ3cb7Vg70y3/XEVDA/IO2tjfm+g1sb8z9Dr5Q444fkoDvLY8esvoA8oMC2XHqyUdmQ7+pvYimytkKYUFCOEuLyVTqYyaKyeDLOJnt/Zs5/0hRvFkCommQs00xTgKmy1oquoQ0yUoEUShpp1TZQujnxjgvjErMJd2hWT1NMmmjg29bB0qNfJT4t9ad7kVTxwM1evglCTYGmBy7uluya5cV8zp0zPtKHsp9P2Z05Wyccu9drv+HOBAgNTEYCGAgaIb44yAlVh7KMVaB0bgyy4GWZ2W6sZGOc4Eo0jX5Rb5WBqcZaUMF0YlyiSUURqVPlFVSiblEk6ZGmMFKPUvUehKdLBKMBohFGqjMq8tkoRZEphKsss1WxVCGTRTiRMpXDlHKa6iJRZEJmHGnBp4I4NW0FKMt5YafJ6PPZmaN1FvDyn0lp6Pn8jbWdjXnXr4zhDJbnQCyrKkXUI6oqNNtHiyLTkStSNtCVRFLgXsSiZG9XGmTUSzcGokaK1T1JeWTZJIjUobg90sUWiwjU4zuORxgX4DdGmIqmh7iJAAE6aIIsTIEgQAEqb6GY/A5coprDWV3O3x0ORWhiTXRmnjb1jH+RX3Es3kNe7OUV00a+uQLsAd2dSa6C9n4lG6jXjkc+s+nbhG21HdHuj+AsmZsOKGmR1RPJAeFxJxehBFkFghKaEsi3hogDDI0AACHoCAaY12EMCSkMiSCTRydrOaknCKeeLcsY6cjqme7hn9jpztlnPpXyrMOG/P6018pMDYBseedGGpoaMmzbTcy3OUm9PaefRGtoz9Z9tfCuV1FDUiLGkzi7pJ54agpEcdCQDLYy07lWCUexCVkWSRXGr1RLdzzAlINeYkGSA2GQQ0gBhFAS1AcX0JJkUCYEmKUcrUYZwSObc03nPUZfcSemgzvXrOM9uETOqtzdWOIZJVGQ3jnf66U9VgmLDG2CZVcIYsAA90mlwIk4y5ECcWkCXIjnn6k3EJPdQEd0aIDDHMMjQDyPJFMYEt5DRHeQ1kCSDAAEk4oYxEoYKjI5HMjk6W+udPkJsi0LI0yi5j1AQEkx5ESRAkk+OBpCgnzHgJSQ0JAyBLIYENgPAsiQ8gPJJMgiUWBLIMWRtBKAE2MIc6X8EQnNYEjtePbjyn+KSY0RAo6pDIokQHFkoyIhgC1DWGVFigiEnhj3hb+OJJPoADIrUcSAwEMAyCAALFMkmUjQFgFQAc5kuQAaOn1n4/JOIABydjiSiMCEhAgABigAAaI8hPiAEJNkYcH8QACwBAQGCAAAAABCAAl//2Q==" width=50%>


## About the Data

This project uses data collected by [Dr Kristen Gorman](https://www.uaf.edu/cfos/people/faculty/detail/kristen-gorman.php) at the [Palmer Station Long Term Ecological Research](https://pallter.marine.rutgers.edu/) site in Antarctica.

**Species studied:** Gentoo, Chinstrap, and Adelie penguins. 

**Research location:** [TODO: Which three islands were the penguins observed on? Hint: check the `island` column in `data/penguins_raw.csv`]

**Sample size:** [TODO: How many penguins are in the raw dataset? Hint: look at how the analysis script checks this]

**Years of data collection:** [TODO: What years were data collected? Hint: check the `year` column in the CSV]

## Variables Measured

The dataset includes the following morphological measurements:

| Variable | Range |
|----------|-------------|
| `bill_length_mm` | [TODO: Include range] |
| `bill_depth_mm` | [TODO: Include range] |
| `flipper_length_mm` | [TODO: Include range] |
| `body_mass_g` | [TODO: Include range] |

## What the Analysis Does

The R script `run_analysis_SOLUTIONS.R` performs the following steps:

1. **Data cleaning** -- [TODO: What does the cleaning step do to handle missing values? Hint: look at section 3 and 4 of the script]
2. **Exploratory boxplots** -- [TODO: Which variable is plotted against species in the first boxplot? Hint: look at section 5]
3. **Cluster analysis** -- [TODO: Which two measurements are used to show how species cluster? Hint: look at section 7]
4. **Regression analysis** -- [TODO: What relationship does the regression plot examine? Hint: look at section 7]

## Plots Produced

The analysis generates a multi-panel figure combining four plots:

- **Top left:** [TODO: What does this plot show?]
- **Top right:** [TODO: What does this plot show?]
- **Bottom left:** [TODO: What does this plot show?]
- **Bottom right:** [TODO: What does this plot show?]

## Project Structure

```
penguin-analysis/
├── README.md              ← You are here!
├── .gitignore             ← [TODO: What does a .gitignore file do?]
├── data/
│   └── penguins_raw.csv   ← [TODO: Describe this file in one sentence]
├── functions/
│   ├── plotting_functions.R  ← [TODO: Describe what this file contains]
│   └── saving_functions.R    ← [TODO: Describe what this file contains]
└── run_analysis_SOLUTIONS.R  ← [TODO: Describe what this file does]
```

## How to Run

1. Open `run_analysis_SOLUTIONS.R` in RStudio
2. Install required packages: `tidyverse`, `janitor`, `palmerpenguins`, `patchwork`
3. Run the script from top to bottom
4. Outputs are saved to the `figures/` folder

## Data Source

Horst AM, Hill AP, Gorman KB (2020). *palmerpenguins: Palmer Archipelago (Antarctica) penguin data.* R package version 0.1.0. https://allisonhorst.github.io/palmerpenguins/

## Authors

[TODO: Add your name here! This is a great first commit.]
#Lula:) 

Hi lula :D
