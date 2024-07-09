# **Text Preprocessing (English Language) - NLTK**

### Text preprocessing is an essential step in natural language processing (NLP) that involves cleaning and transforming unstructured text data to prepare it for analysis. It includes tokenization, stemming, lemmatization, stop-word removal, and part-of-speech tagging. 

## Features

### **Removing Punctuations**
* In Natural Language Processing (NLP), the removal of punctuation marks is a critical preprocessing step that significantly influences the outcome of various tasks and analyses. This necessity stems from the fact that punctuation, while essential for human readability and comprehension, often adds minimal semantic value when processing text through algorithms.
### **Lower Scaling**
* Converting the text into the same case, preferably lowercase, is one of Python’s most common text preprocessing steps. However, doing this step every time you work on an NLP problem is unnecessary, as lower casing can lead to a loss of information for some problems.

### **Tokenization**
* In this step, the text is split into smaller units. Based on our problem statement, we can use sentence or word tokenization.

### **Remove stop Words**
* We remove commonly used stopwords from the text because they do not add value to the analysis and carry little or no meaning. NLTK library consists of a list of stopwords considered stopwords in the English language. Some of them are : [i, me, my, myself, we, our, ours, ourselves, you, you’re, you’ve, you’ll, you’d, your, yours, yourself, yourselves, he, most, other, some, such, no, nor, not, only, own, same, so, then, too, very, s, t, can, will, just, don, don’t, should, should’ve, now, d, ll, m, o, re, ve, y, ain, aren’t, could, couldn’t, didn’t, didn’t]

### **Stemming**
* This step, known as text standardization, stems or reduces words to their root or base form. For example, we stem words like ‘programmer,’ ‘programming,’ and ‘program’ to ‘program.’

### **Lemmatization**
* It stems from the word but ensures it does not lose meaning.  Lemmatization has a pre-defined dictionary that stores the context of words and checks the word in the dictionary while diminishing.

#### Stemming VS Lemmatiation
* You can read more about those differences in [Stemming VS Lemmatization](https://www.analyticsvidhya.com/blog/2022/06/stemming-vs-lemmatization-in-nlp-must-know-differences/?utm_source=reading_list&utm_medium=https://www.analyticsvidhya.com/blog/2021/06/text-preprocessing-in-nlp-with-python-codes/)
