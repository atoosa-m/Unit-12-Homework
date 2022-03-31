# Unit-12-Homework
## Tales from the Crypto
![sentimental](https://user-images.githubusercontent.com/93611442/160975630-922b7c00-a416-482e-87f1-2470ec4402b5.jpeg)

### Background

There's been a lot of hype in the news lately about cryptocurrency, so I want to take stock, so to speak, of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.

In this assignment, I will apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. I will also apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.  
### 1. Sentiment Analysis
In this section, I used the NewsApi to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.  
I found 8467 articles about Bitcoin and 4416 about Ethereum.  
###### Bitcoin Sentiment:  
![Bitcoin Sentiment](https://user-images.githubusercontent.com/93611442/160979841-a42be932-b568-4d90-889c-7ba6439e3d5c.jpg)  
###### Ethereum Sentiment:  
![Eth Sentiment](https://user-images.githubusercontent.com/93611442/160980059-d38c309b-9cf0-4728-8125-4a3e7790405b.jpg)  

### 2. Natural Language Processing
I used NLTK and Python to tokenize text, find n-gram counts, and create word clouds for both coins.  
#### Tokenizer  
###### Bitcoin  
![Bitcoin Tokenizer](https://user-images.githubusercontent.com/93611442/161116087-3f978299-b380-4c16-a651-746b1457e2e7.jpg)  
###### Ethereum  
![Ethereum Tokenizer](https://user-images.githubusercontent.com/93611442/161116129-5fbe6f87-3f57-4947-ac7b-054b3ea310bd.jpg)  

#### NGrams and Frequency Analysis  
##### Top 10 most common bigrams for Bitcoin:  
(march, reuters): 27   
(char, march): 8  
(char, london): 8  
(reuters, bitcoin): 7  
(london, march): 6  
(char, bitcoin): 5  
(new, york): 5  
(russias, invasion): 5  
(th, char): 5  
(char, new): 5  

##### Top 10 most common bigrams for Ethereum:  
(march, reuters): 32  
(char, march): 11  
(reuters, bitcoin): 8  
(char, london): 8  
(th, char): 8  
(char, bitcoin): 7  
(new, york): 7  
(char, cryptocurrency): 7  
(nonfungible, token): 7  
(london, march): 6  
  
 #### Word Clouds  
 ###### Bitcoin Word Cloud:  
 ![Bitcoin Word Cloud](https://user-images.githubusercontent.com/93611442/161121018-3da9e0e8-c15c-46cd-8b7d-88f56dcc1c2d.jpg)  
   
 ###### Ethereum Word Cloud:  
 ![Ethereum Word Cloud](https://user-images.githubusercontent.com/93611442/161121105-ddbcd39f-aac5-4769-a6ab-e085bbe32536.jpg)  
   
 ### 3. Named Entity Recognition  
 In this section, I built a named entity recognition model for both coins and visualized the tags using SpaCy.  
 
 ###### Bitcoin NER:  
 ![Bitcoin NER](https://user-images.githubusercontent.com/93611442/161123102-83b24fac-393b-4176-9407-cf618b7735c4.jpg)  
   
 ###### Ethereum NER:  
 ![Ethereum NER](https://user-images.githubusercontent.com/93611442/161123183-af19f8ef-65d5-4f6f-9f76-bf7a57d49840.jpg)


 




