This repository is base on the text mining course in university. 

# Text_Mining (part 1)
Text mining is using data mining techniques in text

Text mining process:
1. Pre_processing (**important step**)
2. Feature extraction indexing 
3. Weighting models
4. Feature extraction dimension reduction
5. Text/Data mining

Pre_processing step aims to extract **useful words** from the text. It contains: 
- Removing unnecessary data (images, tables,…) because textual information is more useful than images.

   In case of removing numbers, it depends on the objective of the problem
- Identify the encoding of characters to read the text

### 1.1.Noise removal tasks could include:
- Removing text file headers, footers 
- Removing HTML, XML, etc. markup and metadata 
- Extracting valuable data from other formats, such as JSON 

This step often take place prior to tokenization

### 1.2.Lexical analysis (tokenization):   Recognition of the words
It uses dictionary like **WordNet**

Note that after tokenization, we are no longer working at a text level, but now at a word level

### 1.3.syntact analysis or tagging (part of speech (pos tagging):

Associate a grammatical category to each word (noun, verb,…)


Feature extraction indexing aims to extract **a good subset of words** to represent documents.

### 2.1. Stop words elimination: remove non informative words(the, and,…)

By:
- stop word list:
   
     English stop word list and in other languages (https://dev.mysql.com/doc/refman/5.1/en/fulltext-stopwords.html)
- statistical approach

### 2.2. Stemming: cut the ends of words

Example: cars ---> car

### 2.3. Lemmatization:properly  use of a vocabulary and  morphological analysis of words  

Example:   walking ---> walk (stem = lemma)

 better ---> good (lemma based in a dictionary)
 
 
 Note: As Stemming and Lemmatization in some cases are the same it is better, first use Stemming then apply data mining methods if the results do not good enough then apply Lemmatization.
 
