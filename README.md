# Detection-of-Cyber-Crime-on-Social-Media
Analysis and comparison of ML algorithms to identify the offensive messages on Twitter

The proposed project uses **data mining algorithms** to process and analyse the data collected from Twitter. _NLP_ is used for cleaning the data. The tweets are processed to obtain the final judgement of being a ***threat or not*** and the ***category of threat*** using _five_ different algorithms, **Naive Bayes, SVM, Decision Tree, Random forest and Logistic Regression** using **Tfidf** and **Count vectorizers** and _accuracy_ is  calculated for every model.

Cyber-bullying and cyber-threats utilise computerised equipment and internet-based platforms, like PCs, cell phones, and other online stages in real-time. So, the proposed work mainly concentrates on ***designing and developing an effective technique to detect online abusive and bullying messages by merging natural language processing and machine learning***.

* The main objective is to **design and implement** a model of _cybercrime detection_ using _NLP and ML Algorithms_.
* To capture significant suspicious patterns of threat activity.
* To **categorize** tweets based on the keywords into six categories namely ***not bullying, ethnicity, gender, age, religion and other bullying***.

### Hardware Requirements ###
* _Processor_ – Intel core i7
* _Memory_ – 8GB RAM
* 1TB Hard Disk Drive
* Mouse 
* Keyboard
* Display device

### Software Requirements ###
* Python
* Jupyter Notebook
* Anaconda Navigator
* Windows  8 or above 

### Implementation ###
* Dataset collection
* Preparation of dataset
* Data analysis
* Data visualization
* Data preprocessing
* Vectorisation using CountVectorizer and tfidfVectorizer
* Splitting dataset into train data and test data
* Applying Machine Learning algorithms on data
* Computing accuracy for each algorithm
* Result analysis 
* Choosing the best suitable model
* Manual Testing

### Future Scope ###
* Adding _multilinguality_ to the existing model.
* Using _hybrid-model_ by combining two or more algorithms.
* _Extending_ this feature to other social media platforms like instagram, facebook e.t.c.,
* Providing additional _filtering features_ with chrome extensions.

### Conclusion ###
A comprehensive product is developed to setup a system in order protect the young generation from cyber bullying attacks. A real-time application of the developed model has been done. To achieve an effective model for cyberbullying, five machine learning algorithms have been chosen. Based on the accuracies, Logistic Regression algorithm using tfidfVectorizer has outperformed the rest.

### Code Details ###
_main.py_ has code to be run. _cyberbullting_tweets.csv_ is the dataset obtained from Kagle used to **train and test** the models. _cyber.pkl_ is the model with **highest accuracy** that is _saved_. 
