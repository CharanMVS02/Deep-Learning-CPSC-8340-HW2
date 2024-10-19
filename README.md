# Deep-Learning-CPSC-8340-HW2
DeepLearning CPSC-8430


To run the code, I recommend using Palmetto as I did.

First, clone the repository and transfer all the files to the Palmetto home directory.
Ensure the dataset is also in the home directory so that the testing videos can be accessed.
Place the saved model modelCharan.h in the folder SavedModel, as training a new model can take over 60 minutes.
Execute the .sh file with the following command to get the BLEU score and generate an output text file:

./hw2_seq2seq.sh

If you encounter a "permission denied" error or similar, run this command before executing the .sh file:

chmod +x hw2_seq2seq.sh

Please note, depending on your environment, you may need to adjust argument 1 and argument 2 in the .sh file, as well as update the dataset and model paths in the model_test.py and model_train.py files.
