# Abstract

This project seeks to analyze the song cycle "Winterreise" by Franz Schubert. The term cycle implies being more than a random collection of pieces. In songs, one source of this supposed coherence, that is often discussed, is the lyrics, which will not be analyzed here. Instead I will focus on different musical parameters: Pitch class count and pitch class duration (for tonality), the number of different pitch classes per measure (for tonal complexity) and the total number of note events (for textural density). 

The project consists of 4 main phases: data collection, data processing, data filtering and selection, and data visulization. In the data collection phase, all music analysis functions are run on all pieces or piece sections. In the data processing phase, the raw music analysis data from the first step is run through different functions for similarity analysis e. g. Pearson correlation and cosine similarity. In the data filtering phase, the most prominent data points are selected for manual interpretation. The data visualization phase serves the purpose of adequately presentings the results/data in a way that is easily accesible for humans. 

The data used for this analysis is part of the Schubert Winterreise Dataset (version 2) curated by Christoph Weiß et al., which among other resources contains high-quality musicxml-files of Schubert's song cycle.

The goal of this project is not only to gain insight on Schubert's "Winterreise", but at the same time to explore (statistical and algorithmic) methods of similaritiy analysis of symbolic representations of music in general. The methods presented here should be able to be transfered and further developed for the use on other songs cycles or music corpora.