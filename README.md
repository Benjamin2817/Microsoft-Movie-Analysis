# Movie Analysis for Microsoft

**Author**: Benjamin Dean

## Overview

This project is intended to display an understanding of the material covered in Phase 1 of the Flatiron School's Part Time Data Science program. Students were given the business problem Microsoft Corporation is opening their own movie studio and needs direction. Provided data is read, cleaned, and modeled to yield suggestions. The analysis performed in this project concludes that Microsoft should begin their production with movies containing the genres: action, adventure, fantasy, and sci-fi.

## Business Problem
Comptetitors Apple, Amazon and Netflix all either produce or procure their own original content. Microsoft looks to capitalize on their ability to distribute digital media and has decided to join the industry by starting their own movie studio. Microsoft has asked the students of Flatiron School to perform a data analysis and advise them on how to create a successful film studio. First we considered what it is that defines a successful movie and concluded it to be a movies longevity, it's reception, and it's profit. We therefore determined these to be most revealing question.
Which genres produce the most profit?
Which directors are best to work with?
Is there a relationship between the money invested in production and the rating of a movie?

## Data

This project explores six datasets(chosen from the eleven datasets provided) from IMDB.com, TheMovieDb.org, and the-numbers.com.  These datasets were determined best fit to answer the business problem because they contained information on production budgets, worlwide gross, director names, etc. They were also simple to merge given their common classifications. Our target variable was profit and we used data including genre, director name, and production budget to project profitability.

## Methods

We began with data preparation that included removing unwanted data and characters, renaming columns, and converting series. 

## Results

Graph 1 suggests movies containing action, adventure, fantasy, and sci-fi genres are most profitable.
However, data was limited and may not be accurate indicator.

![first_graph](../images/graph_1.png)


## Conclusions

Movies not having a primary genre made them difficult to categorize
Bringing in more data via API or webscraping could be more useful. Data that provides information about how often movies are rewatched and whether they are franchise worthy.