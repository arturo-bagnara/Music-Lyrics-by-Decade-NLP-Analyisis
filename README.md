# Music-Lyrics-by-Decade-NLP-Analyisis
The presented notebooks and data are the outputs of my final project for the [Natural Language Processing course](https://didattica.unibocconi.eu/ts/tsn_anteprima.php?cod_ins=20597&anno=2022&IdPag=6162) taught by professor [Dirk Hovy](https://scholar.google.com/citations?user=7xluaTAAAAAJ&hl=it&oi=sra) and which I attended during the spring semester of 2022 at Bocconi University, Milan.
It required to apply most of the material covered in class, including basic preprocessing of raw text (tokenization, lemmatization etc.), LDA topic modeling, the vectorization of input text both in a sparse (count and TFIDF vectorization) and dense (Word2vec, Doc2vec) fashion, and finally a standard classification task and a structured prediction task. The choice of the object of the analysis was left to the students' discretion, hence I decided to analyse music lyrics from different decades (ranging from the 60s to the 10s) with the aim to uncover systematic changes in the language used and topics treated, and to unveil to what extent lyrics reflect how the meaning of certain words has evolved over time, with a focus on the role of gender in music.


Below are listed the main objectives and points explicitly required for the project.

1. Research Question
Describe what question you are investigating with the data.

2. Data, Preprocessing, and Annotation
Find a data set for text classification and a data set for structured prediction. 
Split the data into dedicated training, development, and test sets.
Briefly describe the content and type of the data set, and what you are planning to look at.
Preprocess the data and explain which preprocessing steps you chose and why, and give statistics of the number of documents, types, and tokens, before and after preprocessing.

3. Analysis
Use at least five of the following analysis methods to the data set (justify your choices and make them explicit):

- Word embeddings 
- Document embeddings
- TFIDF analysis
- Topic models
- Dimensionality reduction
- Clustering
- Language models

4. Prediction
4.1 Classification
Build a predictive model of the target label and use appropriate performance metrics. Your predictive analysis needs to involve all of the following, summarized in a table:
1. a most-frequent-label baseline
2. a LogisticRegression baseline with default parameters and 2-6 gram character TFIDF features
3. the performance of at least one more predictive model architecture, including description/justification of the optmization steps taken.
4. two bootstrap sampling significance tests of the performance difference between your best model and each of the two baselines.

4.1 Structured Prediction
Adapt the Structured Perceptron to your sequence prediction task, and note the performance as baseline.
Implement a suitable neural net architecture on the data. Compare the best performance of the  models.

5. Visualizations
Provide at least 3 visualizations of your work above. These can be in the respective sections. Use labels and legends. Be creative.
