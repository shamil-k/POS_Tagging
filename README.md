
PROBLEM STAEMENT:

In this project we will be performing one of the most famous task in the field of nautal language processing i,e Parts of Speech Tagging using BERT.

DESCRIPTION OVERVIEW:

Part-Of-Speech tagging (POS tagging) is also called grammatical tagging or word-category disambiguation. It is the corpus linguistics of corpus Text data processing techniques for marking meaning and context.

Part-of-speech tagging can be done manually or by a specific algorithm. Using machine learning methods to implement part-of-speech tagging is the research content of Natural Language Processing (NLP). Common part-of-speech tagging algorithms include Hidden Markov Model (HMM), Conditional Random Fields (CRFs), and so on.

Part-of-speech tagging is mainly used in the field of text mining and NLP. It is a preprocessing step for various types of text-based machine learning tasks, such as semantic analysis and coreference resolution.


WORKFLOW DIAGRAM:


IMPLEMENTATION

1. bertlayr.py

This file consists of the the bert model architecture which will be used to train the data.
bert model which we are used:

https://tfhub.dev/google/bert_uncased_L-12_H-768_A-12/1
2. sentPosTagger.py

This file is used to train the model and to do the prediction.
<img width="815" alt="Screenshot 2021-05-19 at 9 01 59 AM" src="https://user-images.githubusercontent.com/55822384/118752551-eb6c4c80-b880-11eb-8b67-466a4c6cd3ab.png">


Preprocessing Input Text
<img width="1354" alt="Screenshot 2021-05-19 at 9 23 49 AM" src="https://user-images.githubusercontent.com/55822384/118754118-fecce700-b883-11eb-909e-b37157e6567c.png">


Predicted respected POS value:
<img width="1201" alt="Screenshot 2021-05-19 at 9 27 05 AM" src="https://user-images.githubusercontent.com/55822384/118754307-66833200-b884-11eb-82b0-789069708643.png">
<!-- 3. trainCustomPostagger.py

This file is used to train a custom pos tagging model if the user wants to train. -->
4. downLoadlibs.py

This file is used  to download dataset.

5. ClientApp.py

This is tha flask server file.
TESTING IN LOCAL/API
To do the test testing we need to run the clientApp.py and after that web server will start at http://0.0.0.0:5000/


Enter the sentence and click on predict button.

Here iam used a sentence : this is a cat


After clicking predict

Results are shown below.


<img width="1435" alt="Screenshot 2021-05-19 at 9 25 26 AM" src="https://user-images.githubusercontent.com/55822384/118754201-2ae86800-b884-11eb-93e5-e19a11c099b5.png">
<img width="1201" alt="Screenshot 2021-05-19 at 9 26 30 AM" src="https://user-images.githubusercontent.com/55822384/118754270-51a69e80-b884-11eb-861e-6fd4b98f2016.png">

Do the matching of the words with corresponding colours.


CONCLUSION


Here we successfully performed Parts of Speech tagging on the given dataset.



COMPARISION

More data or better larger dataset can be used to build a better model. We can also try out better pre trained model with fine tuning to increase the performance.





