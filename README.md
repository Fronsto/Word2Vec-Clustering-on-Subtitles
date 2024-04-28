# Analyzing Word2Vec embeddings of a subtitle file.

The tutorial in the [index.ipynb](index.ipynb) demonstrates clustering (with K-means algorith) over word embeddings generated using Word2Vec model trained over subtitles of the movie The Big Short.

The dependencies required are mentioned in the notebook itself.

### Movie used: The Big Short
To reasonably understand the clusters formed, the reader is advised to take a overview of the story of the movie.

The movie is about the 2008 financial crisis, where the housing market collapsed because it had become a bubble due to the massively overvalued CDOs formed by bonds over subprime morgages. These CDOs were bought up by all major finanical institutions, from the big banks like Lehman Brothers to State Pension Funds. The movie is about the story of a few fund managers within Wall Street who had known this bubble, and they shorted these CDOs - by buying Credit Default Swaps from the insurance companies, thus making huge sums off of the collapse of the housing market.

Running clustering over the word2vec embeddings of this movie, we expect words used in similar financial context (like stock-market, or morgages-CDOs-bonds, or insurance-swaps) to be clubbed together.

### References and Further Readings
- [ComputerPhile on YouTube, Word Embeddings](https://youtu.be/gQddtTdmG_8)
- [3Blue1Brown on YouTube, Embeddings Explanation](https://youtu.be/wjZofJX0v4M)
- [dylancastillo.co, Cluster documents with word2vec](https://dylancastillo.co/nlp-snippets-cluster-documents-using-word2vec/)
