# Plagiarism-Checker
Check Plagiarism between pair of text files.

In this project, we use Cosine Similiarity to find similarity in texts in a pair of text files.

Cosine Similarity is a method of calculating the similarity of two vectors by taking the dot product and dividing it by the magnitudes of each vector.

Since, cosine similarity needs vectors, we first transform the text data of all files to vectors, then we use Term Frequency Inverse Document Frequency(TFIDF) to find similarities between the vectors.

We simply use cosine similarity method on the pair of vectors corresponding to a pair of text files and we get a similarity score, telling us the ratio of similarity of the text in file1 to file2
