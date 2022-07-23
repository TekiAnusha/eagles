# eagles
# About
Phishing attacks are the practice of sending fraudulent communications that appear to come from a reputable source.Phishing URLs mainly target individuals and/or organizations through social engineering attacks by exploiting the humans' weaknesses in information security awareness. Phishing costs Internet users billions of dollars per year. It refers to luring techniques used by identity thieves to fish for personal information in a pond of unsuspecting Internet users. Phishers use spoofed e-mail, phishing software to steal personal information and financial account details such as usernames and passwords.The experiments were carried out on a dataset that originally contained 1056937 labeled URLs (phishing and legitimate). We consider various data mining algorithms for evaluation of the features in order to get a better understanding of the structure of URLs that spread phishing. 
# Introduction
Natural Language processing makes it possible for computers to understand the human language. NLP analyzes the grammatical structure of sentences and the individual meaning of words, then uses algorithms to extract meaning and deliver outputs. NLP deals with how computers understand and translate human language. With NLP, machines can make sense of written or spoken text and perform tasks like translation, keyword extraction, topic classification, and more. 
# preprocessing
Data preprocessing can refer to manipulation or dropping of data before it is used in order to ensure or enhance performance, and is an important step in the data mining process. 
NLP Contains Three Steps
    Preprocessing
    Vectorization
    Model
NLP preprocessing techniques
   Expand Contractions
   Lower Case
   Remove Punctuations
   Remove words and digits containing digits
   Remove Stopwords
   Rephrase Text
   Stemming and Lemmatization
   Remove White spaces
NLP Vectorization techniques
   Count Vectorizer
   TF-IDF
   Word2Vec
   GloVe
# Dataset Preprocessing
The given dataset consists of URL's to detect whether the given url is malicious or legitimate. 
There exists many tokens or special characters which appear most frequently in URL string of phishing sites but not in legitimate sites. This characteristic feature is used to distinguish between phishing sites and legitimate sites. These features check the presence of special characters (@, *, $, :, |, , ’,’, _), phish-hinted words either in the base URL or path of the entire URL string.
While preprocessing we replaced some special characters like (//,/,-,.) with space(' ').
   
   
