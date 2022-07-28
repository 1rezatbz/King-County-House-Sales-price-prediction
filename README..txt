The code was developed in the google colab environment and should be run in the same and not in jupyter
notebooks as the indentation for the code and functions is based on the requirements of colab and running it in
jupyter will produce errors.

In order to run the code the dataset file must be uploaded so that pandas can read and load it.
After this all the cells in the notebook can be run sequentially.

The randomised search cv part is the most time consuming and the verbose is set to 0 so it may appear that nothing is happening for sometime when the cell is running but actually the execution is taking place in the background. The plots will be displayed after the execution is complete.

The report was developed based on the latest results and plots obtained.
While we have made attempts to make the results as reproducible as possible by setting the
seed wherever we could, there may be a few differences in the results and plots obtained
which is most like because of the weights are initialized differently every time the code is run
 at the beginning of training and we have considered only the first 15 epochs of training to save time in long execution.

In case you cannot open the file here is the colab link with granted access:
https://colab.research.google.com/drive/1jCj05tf02nZXTr2S8_J4fPxC_OpH059K?usp=sharing