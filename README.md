# Information-Rettrival-Models
This project involved comparing two different information retrieval ranking algorithms against the BM25 model. The data used was various collections of articels with a query that was only relevant to a subset of articles within the queries collection. The two other models chosen were the TF-IDF ranking and Likelihood model. The comparison of all three models was done through comparing recall, precision, F1. While F1 scores indicated that the TF-IDF and Likelihood models preformed better their recall was much higher then BM25 and their increase in precision was likely due to just returning more documents as relevant. The BM25 struggled with a few queries where the query had terms like Sport Utility Vehicle that was abbreviated to SUV in the article text. Other Queries it struggled with were when terms like U.K. were present, as these terms were typically stemmed by the stemming and stopword methods used. Further research has to establish if BM25 is actually the worse preforming as its lower recall suggest that its accuracy is more representative of a better preforming model when compared to the other two.  

The data that was used for this assignment was given under strict guidance that it only be used for this asssignment so it will not be avaliable within the GitHub.
