# Practical Natural Language Processing
## A Comprehensive Guide to Building Real-World NLP Systems
#### [Sowmya Vajjala](https://www.linkedin.com/in/sowmya-vajjala-2a38734/), [Bodhisattwa P. Majumder](http://www.majumderb.com/), [Anuj Gupta](https://www.linkedin.com/in/anujgupta-82/), [Harshit Surana](http://harshitsurana.com/)


#### Endorsed by:
[Zachary Lipton](http://zacklipton.com/), [Sebastian Ruder](https://ruder.io/), [Marc Najork](http://marc.najork.org/), [Monojit Choudhury](https://www.microsoft.com/en-us/research/people/monojitc/), [Vinayak Hegde](https://www.linkedin.com/in/vinayakh/), [Mengting Wan](https://mengtingwan.github.io/), [Siddharth Sharma](https://www.linkedin.com/in/siddharth-sharma-31140210/), & [Ed Harris](https://www.linkedin.com/in/e10is/)
#### Foreword by [Julian McAuley](https://cseweb.ucsd.edu/~jmcauley/)


#### Homepage: [www.practicalnlp.ai](http://www.practicalnlp.ai)
#### Published by [O'Reilly Media, 2020](http://shop.oreilly.com/product/0636920262329.do)

-----------------------------------------------------------------------------------

```
Please note that the code repository is still under development and review.

All the notebooks will be crystalized in the coming months. 

```

🚩 Details of the repository roadmap could be found [here](roadmap.md)

-----------------------------------------------------------------------------------

<!-- ![](http://check-server.in/book/images/book.png =250x250)](http://practicalnlp.ai) -->

### Open the repository in Google Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/practical-nlp/practical-nlp/blob/master)

### Open the repository in Jupyter nbviewer: [![Open in nbviewer](https://user-images.githubusercontent.com/2791223/29387450-e5654c72-8294-11e7-95e4-090419520edb.png)](https://nbviewer.jupyter.org/github/practical-nlp/practical-nlp/tree/master/)

### Chapterwise code notebooks:

  <details>
    <summary><a href="https://github.com/practical-nlp/practical-nlp/tree/master/Ch02" > Chapter 2: NLP Pipeline </a></summary><p>
  
   1. **[Web Scraping using BeautifulSoup](/Ch02/01_WebScraping_using_BeautifulSoup.ipynb)**: Here we demostrate to scrape a web page(we use stackoverflow.com here as an example) and parse html using bs4 to find and extract relevant information.
  2. **[Web Scraping using Scrapy](/Ch02/02_WebScraping_using_scrapy/)** : Here we demonstrate how to use scrapy to scrape data from websites and save it using a pipeline.
  3. **[Text Extraction from Images](/Ch02/03_Extracting_text_from_images_tesseract.ipynb)**: Here we demostrate how we can use py-tesseract to extract text from images. 
  4. **[Common Pre-processing Steps](/Ch02/04_Tokenization_Stemming_lemmatization_stopword_postagging.ipynb)**: Here we demonstrate the most commonly performed text pre-processing steps using various libraries. 
  5. **[Data Augmentation](/Ch02/05_Data_Augmentation_Using_NLPaug.ipynb)**: Here we demonstrate data augmentation using nlpaug.
   </p>
   </details>
   
   
 <details>
    <summary><a href="/Ch03" > Chapter 3: Text Representation </a></summary><p>
  
   
   1. **[One-Hot Encoding](/Ch03/01_OneHotEncoding.ipynb)**: Here we demonstrate One-Hot encoding from first principle as well as scikit learn's implementation on our toy corpus.

   2. **[Bag of Words](/Ch30/02_Bag_of_Words.ipynb)** : Here we demostrate how to arrive at the bag of words representation for our toy corpus.


   3. **[Bag of N Grams](/Ch03/03_Bag_of_N_Grams.ipynb)**: Here we demonstrate how Bag of N Grams work using our toy corpus.

   4. **[TF-IDF](/Ch03/04_TF_IDF.ipynb)**: Here we demonstrate how to obtain the get the TF-IDF representation of a document using sklearn's TfidfVectorizer(we will be using our toy corpus). 

   5. **[Pre-trained Word Embeddings](/Ch03/05_Pre_Trained_Word_Embeddings.ipynb)**: Here we demonstrate how we can represent text using pre-trained word embedding models and how to use them to get respresentations for the full text.

   6. **[Custom Word Embeddings](/Ch03/06_Training_embeddings_using_gensim.ipynb)**: Here we demonstrate how to train a custom Word Embedding model(word2vec) using gensim on both, our toy corpus and a subset of wikipedia data.

   7. **[Vector Representations via averaging](/Ch03/07_DocVectors_using_averaging_Via_spacy.ipynb)**: Here we demonstrate averaging of Document Vectors using spaCy.

   8. **[Doc2Vec Model](/Ch03/08_Training_Dov2Vec_using_Gensim.ipynb)**: Here we demonstrate how to train your own doc2vec model.

   9. **[Visualizing Embeddings Using TSNE](/Ch03/09_Visualizing_Embeddings_Using_TSNE.ipynb)**: Here we demonstrate how we can use dimensionality reduction techniques such as TSNE to visualize embeddings.

   10. **[Visualizing Embeddings using Tensorboard](/Ch03/10_Visualizing_Embeddings_using_Tensorboard.ipynb)**: Here we demonstrate how we can visualize embeddings using Tensorboard.

   </p>
   </details>
   


  * [Chapter 4: Text Classification](https://github.com/practical-nlp/practical-nlp/tree/master/Ch4) 
  
  * [Chapter 5: Information Extraction](https://github.com/practical-nlp/practical-nlp/tree/master/Ch5) 
  
  * [Chapter 6: ChatBots](https://github.com/practical-nlp/practical-nlp/tree/master/Ch6) 
  
  * [Chapter 7: Topics in Brief](https://github.com/practical-nlp/practical-nlp/tree/master/Ch7) 
  
  * [Chapter 8: Social Media](https://github.com/practical-nlp/practical-nlp/tree/master/Ch8) 
    
  * [Chapter 9: E-commerce and Retail ](https://github.com/practical-nlp/practical-nlp/tree/master/Ch9)

  * [Chapter 10: Healthcare, Finance and Law](https://github.com/practical-nlp/practical-nlp/tree/master/Ch10) 
    
  * [Chapter 11: End-to-End NLP Process](https://github.com/practical-nlp/practical-nlp/tree/master/Ch11)

-----------------------------------------------------------------------------------

Contributors to Codebase:

* [Varun Purushotham](https://www.linkedin.com/in/varunp2k/)
* [Kartikay Bagla](https://www.linkedin.com/in/kartikay-bagla-60638a167/)
* [Taranjeet Singh](https://www.linkedin.com/in/taranjeet7114/)
* [Vishal Gupta](https://www.linkedin.com/in/vishalg8897/)
* [Shreyans Dhankhar](https://www.linkedin.com/in/shreyans-dhankhar-501b88118/)
* [Nachiketh Suresh](https://www.linkedin.com/in/nachiketh-suresh-a4955411/)
* [Jitin Kapila](https://www.linkedin.com/in/jitinkapila/)
* [Kumarjit Pathak](https://www.linkedin.com/in/kumarjitpathak/)
* [Ernest Kirubakaran Selvaraj](https://www.linkedin.com/in/ernest-s-kirubakaran/)
* [Ayush Datta](https://www.linkedin.com/in/ayushdatta/)
* [Rui Shu](https://www.linkedin.com/in/rui-shu/)

-----------------------------------------------------------------------------------

Found a Bug?

If the bug is in book text, please enter a errata here: 
[https://www.oreilly.com/catalog/errata.csp?isbn=0636920262329](https://www.oreilly.com/catalog/errata.csp?isbn=0636920262329) 

If the bug is in the codebase:
Great! Please read [this](https://github.com/practical-nlp/practical-nlp/edit/master/Contributing.md) how can you help us improve the codebase
