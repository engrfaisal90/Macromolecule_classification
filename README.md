# Macromolecule_classification
In this study we focused on classification of protein sequences with deep learning techniques. The study of amino acid sequence is vital in life sciences.  We used different word embedding techniques from Natural Language processing to represent the amino acid   sequence   as   vectors. Our main goal was to classify sequences to four group of classes, that are DNA, RNA, Protein and hybrid. After several tests we have achieved almost 99% of train and test accuracy. We have experimented on CNN, LSTM, Bidirectional LSTM, and GRU. 
</br>
Initially the dataset had 10 classes and wasnt normalized. Most of the data was from protein class as shown in figure below.</br>
![Screenshot](images/newplot.png)


</br>
We normalized the dataset and minimized the problem to 4 class classification problem. The normalized dataset classification is shown here.

![Screenshot](images/newplot1.png)

</br>
Different models were developed and tested. One of the model, and its results are shown here.
![Screenshot](images/Model.png)
![Screenshot](images/Loss.png)
![Screenshot](images/Accuracy.png)
![Screenshot](images/Confusion_matrix.png)
![Screenshot](images/Results.png)
