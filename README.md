See the jupyter notebook Clean.ipynb for the bulk of my response to the assignment. There is also a bit of exploration in Explore.ipynb. 

The cleaned-up data is in the file health\_facility\_assessment\_cleaned.csv. 

Dealing with the partial duplicates was tricky because it wasn't clear which of the entries should have priority over the other. I therefore wrote three different functions one can choose between for handling those. One simply takes the first entry, another takes the first entry unless the first entry is null, and the last one takes the maximum value of each column. 

I turned the text data into numerical data where it seemed appropriate. I also made proper names uppercase and all other text lowercase. 

There are so many columns in the dataset that it was difficult to decide what to focus on for exploration. I plotted a correlation matrix in Explore.ipynb and the correlations seemed to be the obvious ones, like more consultations of one kind being associated with more consultations of other kinds. 
