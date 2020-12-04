# Final Project QTM 340
This GitHub repo includes all data and code necessary for replication of the "Differentiating the Humor of Long-Running Animated Comedy TV Shows" project. 

## Transcript CSVs
This folder includes all transcripts used in the analysis. The transcripts for each episode from *South Park*, *The Simpsons*, *Futurama*, *American Dad!*, and *Family Guy* are included and segmented by each line spoken by a character. 

## Stopwords
This stopwords text file is adapted from Matthew Jocker's stopwords list, found [here](https://www.matthewjockers.net/macroanalysisbook/expanded-stopwords-list/). This list was adapted by adding show specific names and places. 

## Code and Notebook
There are multiple packages that are necessary to replicate the results. These include "beautifulsoup4", "pandas", "nltk", "sklearn", and "gensim". Additionaly, some code will need to be changed. For example, the code that splits each csv into separate .txt documents requires the user to create folders such as "SouthPark_Data" or "Futur_Data" prior to running the code. 
