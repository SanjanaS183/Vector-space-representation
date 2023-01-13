A model is built to create a vector representation of a document containing dialogues of different characters in Eastenders. 
Then the representation is improved such that each character vector is maximially distinguished from the other character documents. 
The training and test data are read from csv files and dataframes are created. 
A dictionary is created from the dataframe constituting the character and their lines. 
Then the data is pre-processed and split into tokens. Feature vectorisation is then done and count of each word is returned. 
The code uses similarity scores to do a simple Information Retrieval retrieval task of retrieving the most similar document vector in the 
heldout and test data to training vector document. It also returns a mean rank performance from that. A heatmap is then plotted. 
Error analysis is done after this to see why some documents have higher similarity score.  
Later on additional meta data about scenes are included to optimize performance. Finally, the above steps are repeated  on the test data. 
