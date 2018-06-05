This project is implemented to provide recommendations, given a folder of text files to compare. Following assumptions are made as given below.
this is only a content based recommendation system and works as follows.
Prerequisites:
The current working directory must be in the folder which has the text files.
Working:
1)	All the text files will be read and stored into a dataframe. The first column will have the title of the books which will be taken from the name of the textfiles. Eg if the text file is “Othello.txt” then the title will be taken as “Othello”. The second column will have the text corresponding to that book.
2)	The similarity between two books will be based on the cosine distance between the two texts.
3)	A function is created which will take the title of the book as input and give three most similar books. The number can be edited in the code as required.
