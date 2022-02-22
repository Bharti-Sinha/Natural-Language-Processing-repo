# Natural-Language-Processing-repo

Libraries used:

- pandas
- re
- numpy
- nltk
- itertools
- ngrams
- random
- csv
- os
- sklearn.datasets
- RegexpTokenizer
- nltk.tokenize, sent_tokenize
- sklearn.datasets, load_files
- random
- nltk.probability
- matplotlib
- sklearn
- gensim
- seaborn
- scipy
- os
- sklearn.model_selection
- gensim.models.fasttext
- sklearn.feature_extraction.text
- gensim.downloader
- sklearn.linear_model
- sklearn.metrics
- scipy.sparse
- gensim.corpora
- gensim.models.tfidfmodel
- gensim.matutils


1. Basic_Text_Processing.ipynb

This jupyter notebook in python contains all the pre-processing steps for all the job descriptions (textual analysis ) in the provided data folder. This data folder has 8 categories of jobs spread over 55449 files. The pre-processing steps required in the assignment are  
a. tokenization,
b. removal of words of length 1, 
c. removal of stop words, 
d. converting all words to lowercase, 
e. removal of all tokens which appear only once and removal of top 50 tokens which appear the most in the documents. 

After preprocessing, extract bigrams. 

2. Document_Modeling

Generate feature representations of job description to predict (classify) jobs into one of the 8 categories such as IT, hospitality and Engineering etc. We will make use of 4 models to generate features - Bag of words, FastText, googlenews300 and Glove. Also, use these features to predict the category of each job description and compare the classification accuracy while using only 
- Document_Modeling_1.ipynb: using only description for classification
- Document_Modeling_2.ipynb: title for classification,  
- Document_Modeling_3.ipynb: and using both title and description for classification. These experiments will be used to conclude our findings.

3. website-job-description

Develop a job hunting website based on the Python Flask web development framework. The developed website will allow job hunters to browse existing job advertisements, as well as employers to create new job advertisements. The website will adopt one of the machine learning models that we built in Document_Modeling files, for the purpose of auto classifying categories for new job advertisement entries. Such functionality helps to reduce human data entry error, increase the job exposure to relevant candidates, and also improve the user experience of the job hunting site.
 
