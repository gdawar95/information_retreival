# information_retreival and search engine optimization

# Aim

To get Whoosh to index the documents from a very small test collection, run a few queries (\topics") and produce output in the format expected by pytrec eval. Also to run pytrec eval, to compare your output to the human relevance judgments (\qrels").

Also aim is to improve on the baseline Whoosh configuration

# The Data

The test collection data is about 4,000 documents from US Government web sites and the topics are 15 needs for government information. Both were part of the TREC conference in 2003

# Libraries used
Whoosh, a pure-Python search engineering library, NLTK, a natural language processing toolkit and pytrec eval, an Information Retrieval evaluation tool for Python, based on the popular trec eval, the standard software for evaluating search engines with test collections.

The Whoosh documentation can be found on its website at https://whoosh.readthedocs.io/en/latest/index.html
The NLTK documentation can be found on its website at http://www.nltk.org/
