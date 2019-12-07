#German Named Entity Recognition

Named Entity Recognition with German dataset by using GRU layers in Tensorflow.

In this project, we sought to build a deep learning model that would accurately recognize
German named entities from data in CoNLL-X format.

##Data:

A dataset comprising of approximately 82000 sentences is used. The whole dataset is divided into 10 parts. We used 8 parts for training, and 2 part for dev-set and the test set respectively. 

##Model performance:

We got precision of 61.01%, recall of 100.00%, and an F1 score of 75.78, after 10 epochs. We achieved the higher accuracy of 95.56% due to fixing a small error in the model. 

##Execution instruction:

1) To change the hyper parameters use "config.py"
2) To execute the program type "python train.py train.txt test.txt"

##Acknowledgement:

We would like to thank our professor, Daniel de Kok, for guiding us in a series of emails and for being there to answer our questions.
