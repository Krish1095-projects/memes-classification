# Detection and classification of cyberullying using machine leanrning algorithms in memes dataset

- Cyberbullying emerged as a serious form of bullying via electronic means due to recent exponential growth of social media users. Social media networks provides an optimal environment for bullies to use these networks as vulnerable hotspots for preparation, creating plan of invasion and intrude /attack the victim’s privacy. So it is necessary to find a suitable action in order to detect and prevent cyberbullying in social media platforms.
- In this process of detection of cyberbullying, Machine learning can be helpful to detect language patterns of text messages, comments, and meme texts that are frequently used by bullies. Hence machine learning algorithms can generate a model to automatically detect cyberbullying actions from the social network sites. 
 - The project proposes a semi supervised machine learning approach for detecting and preventing cyberbullying. Several classifiers are used to train and recognize bullying actions. The evaluation of the proposed approach on collected cyberbullying dataset (from Library of Congress) shows that Support Vector Machine (SVM) achieves an accuracy of 84.93 % and Multinomial Naïve Bayes (MNB) achieves 82.28%. Finally, the conclusion is SVM outperforms Multinomial Naïve Bayes with similar working principle and same data.
 
# Descripton of dataset
The dataset is comprised of popular political meme text data which are extracted from various meme image macros. These meme images are collected from various Social media platforms during online communication or social commenting (primarily from Library of Congress's web archive) with a range of 57,652 unique memes. The extracted meme text messages are in different languages and saved in Comma Separated Values (CSV) file format. The dataset consists of a labelled column followed by ten attribute fields.

 Attribute Name	----->Description
1.	Meme-ID	------>An Identification number to identify each and every meme. 
2.	Archived URL -----> URL, where the memes are archived.( location where the memes are stored)
3.	Base Meme Name	 ------> Raw text data extracted from the meme image macros across different SM platforms
4.	Meme Page ------->URL	Origination of Meme
5.	MD5 hash	-------> Encryption hash number of each and every meme
6.	File size	------>Size of every meme in bytes
7.	Alternate Text	------> Contains the alternate meaning of the memes
8.	Display name	----->Public name for accessing the memes by different users.
9.	Upper and Lower text	Upper text contains first set of meaning of the meme and the lower text contains the second set of meaning of the meme.

 
# Tools and technologies used:
- programming language : python 3.8.3
- IDE : Jupyter Notebook ( or jupyetr lab (preferred)) 
- Tech domain : Natural Language Processing

# Required dependencies and tools:
- Anaconda Navigator (jupyter notebook) -- Latese version (https://www.anaconda.com/products/individual)
- NLTK
- NLTK.tokenize 
- NLTK.corpus (stopwords)
- NLTK.stem (WordNet Lemmatizer)
- nltk.sentiment.vader
- wordcloud
- String (Punctuations)
- Pandas and numpy
- Sklearn
- matplotlib and seaborn

# Instructions to download required dependencies:
- After installing anaconda navigator , open the navigator and install jupyter notebook or jupyter lab 
- once jupyter notebook is installed , open jupyter notebook
#### to download nltk dependency 
- Use : pip install nltk
- And use : nltk.download('punkt'),  nltk.download('stopwords'),  nltk.download('wordnet') to download the following packages.
##### using pip install to install specific dependency ( module )
- Pip install is the genreal command to download any python dependencies
- Example (pip install sklearn) 
- Installing latest anaconda navigator will install all the python modules which essential for data science.

 # How to open and use the project.ipynb file:
 1) Download and extract memes-classification.7z zip file into desired folder.
 2) Open the project.iypnb file directly if jupyter notebook is installed already.
 3) otherwise follow this instruction given in this link to install anaconda navigator first and then retry openning the file.
    - link : https://docs.anaconda.com/anaconda/user-guide/getting-started/
 4) After installing , open jupyter notebook application 
 5) find the downloaded file project.ipynb file in jupyter notebook or jupyter lab file browser and open it
 6) Since Jupyter Notebook is an open-sourced web-based application which allows you to create and share documents containing live code, equations, visualisations, and narrative text. In simple words the result of the code can be viewed in IDE itself instead using seperate terminal to view the result like in java or c or c++
 7) Use the following command to execute a block in jupyter notebook
    # shift+enter --> to run a cell or execute the code block 
 8) While reading the dataset using pandas.read_csv() , change the path to the user's system path (where teh dataset file is located).
 9) thats all done!!
 
