# ProjectMarketBasket

This project investigates the problem of frequent itemset mining on large-scale datasets through two complementary approaches: the Multistage algorithm and the Savasere–Omiecinski–Navathe (SON) algorithm implemented in Apache Spark. 

The analysis was conducted on the Amazon Books Reviews dataset, containing over three million book reviews with associated columns. Two representations of the data were explored: (1) users as baskets and book titles as items (Multistage Algorithm), and (2) reviews as baskets and words as items (SON Algorithm).

Experimental results demonstrate that the Multistage algorithm successfully identifies frequent pairs of books at low support thresholds, while higher-order itemsets are rare;on the other end, the SON implementation uncovers dominant linguistic patterns centered around the token 'book', confirming strong semantic regularities in the textual data.



[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ariannagirotto/ProjectMarketBasket/blob/main/ProjectMarketBasket.ipynb)
