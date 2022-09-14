# Informatio-Retrieval

________________________________________

1.	Develop a tool to search for Amazon reviews that are stored in a set of files (100 files). Please follow the following steps in the development process.
a.	Read each file containing a single review for a single product.
b.	Insert distinct words to an inverted index. Use an appropriate data structure for both Dictionary and Postings lists
c.	DO NOT stem your words. Come and comes become two entries in the index to keep the assignment simple.
d.	Document must have the exact match to retrieve the document as a true positive.
e.	Use the STOP words given in the stop_words.txt file and do not index the stop words found in any of the user reviews.
f.	You can implement the system as a GUI or console application.
g.	Please refer to https://www.rhymezone.com/shakespeare/ which is a system that we need to replicate.
h.	Files.zip contains 100 amazon reviews.
i.	Stop_words.txt contains stop words of English language

Functionality:
•	Users must be able to provide a search term (single) and should be able to retrieve list of file names (ID) that contains the word that the user entered.
•	BONUS (2 points): User must be able to enter two words and the system must retrieve all the documents that both words appear in it.

