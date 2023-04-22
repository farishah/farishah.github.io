## My Portfolio

---

### NLP
[Overview of NLP by Farishah](https://farishah.github.io/CS6301-NLP/Overview%20of%20NLP.pdf)

---

### Word Guessing Game
Used Python and NLTK features to explore a text file (one chapter of an anatomy textbook) to create a word guessing game.
<br><br>
<a href="https://github.com/farishah/CS6301-NLP/tree/main/FarishahNahrin_Chapter5">View Code on GitHub</a>

---

### Web Crawler

Built a web crawler function that scrapes contents from virtualbangladesh.com, determined the top terms using NLP techniques, and saved contents to a knowledge base. 
<br><br>
[My Web Crawler Report](https://farishah.github.io/CS6301-NLP/FarishahNahrin_WebCrawler/Report_FarishahNahrin.pdf)
<a href="https://github.com/farishah/CS6301-NLP/tree/main/FarishahNahrin_WebCrawler">View Code on GitHub</a>

---

### WordNet

WordNet is a "lexical database of nouns, verbs, adjectives and adverbs that provides short definitions called glosses, and use examples." Identified sysnets, hypernyms, hyponyms, etc., from nouns using WordNet and SentiWordNet

<br><br>
<a href="https://github.com/farishah/CS6301-NLP/blob/main/Farishah_Wordnet.ipynb">View Code on GitHub</a>

Summary: WordNet is a "lexical database of nouns, verbs, adjectives and adverbs that provides short definitions called glosses, and use examples." WordNet started as a project at Princeton University, organized by George Miller. The primary premise of the project was "to support theories of human semantic memory, which suggested that people organize concepts mentally in some kind of hierarchy." In NLTK, WordNet is just another NLTK corpus reader, that is created for natural language processing and can be used for translating language automatically, text similarity, to disambiguate words, as a thesaurus. 

## N-Grams
[N-Grams Project](https://github.com/farishah/CS6301-NLP/tree/main/Farishah_Ngrams)

[N-Grams Narrative](https://farishah.github.io/CS6301-NLP/Farishah_Ngrams/Farishah_Narrative_Ngrams.pdf)

Project 1 Summary: Created function to read data from the file and returns unigrams and bigrams of data. Then, I replaced the newlines with spaces and tokenized the text. Then I retrieved the unigrams and bigrams into respective lists. I used the counter class to count the bigrams and unigrams, which will process faster, and I'll also convert it to dictionary again. Then I pickled these dictionaries. 

Project 2 Summary: Created a function that unpickles a dictionary from a given file. Then, I read the unigrams and bigrams from the files. Then I had a formula, to calculate "V." to use for later computations. V = the total vocabulary size, based on the formula given in the hints (which means to: add the lengths of the 3 unigram dictionaries). Then, I created a function that calculates probability with unigrams and bigrams - i first created the unigrams and bigrams, initialzed the laplace probability to 1, since it can't equal 0, and it will be a value that's multiplied. Then, I iterated this and applied it to all the text. Then I applied this formula: p_laplace = p_laplace * ((b + 1) / (u + v)). Then I created a function that calculates the probabilty for each language, by passing their unigram and bigram into the the defined functions. Then, I created another function that calculated the probability for each language, by referencing my previous function. Then, I extracted the langnuage for the maximum probabiltiy only. Next, I read the LangId.test file, then detected the results and wrote it to a file. Then I read the LangId.sol (correct classifications files), then I got the accuracy. 

## Sentence Parsing

[Sentence Parsing - Comparing the Three Types of Sentence Parsers](https://farishah.github.io/CS6301-NLP/Farishah_Nahrin_Sentence_Parsing.pdf)

## Chatbot Project

[Chatbot Report](https://farishah.github.io/CS6301-NLP/ChatbotReport_FarishahNahrin.pdf)

[Chatbot Project](https://github.com/farishah/CS6301-NLP/tree/main/FarishahNahrin_ChatBot)

## ACL Paper Summary
[ACL Paper Summary](https://farishah.github.io/CS6301-NLP/Farishah_Nahrin_ACL_Summary.pdf)

## Text Classification 1 
[Text Classification 1](https://github.com/farishah/CS6301-NLP/tree/main/Farishah_Text_Classification_1)

## Text Classification 2
[Text Classification 2](https://github.com/farishah/CS6301-NLP/tree/main/Farishah_Text_Classification_2)


### Category Name 1 

[Project 1 Title](/sample_page)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---
[Project 2 Title](/pdf/sample_presentation.pdf)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---
[Project 3 Title](http://example.com/)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---

### Category Name 2

- [Project 1 Title](http://example.com/)
- [Project 2 Title](http://example.com/)
- [Project 3 Title](http://example.com/)
- [Project 4 Title](http://example.com/)
- [Project 5 Title](http://example.com/)

---




---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
