# epkch_test_assignment_prjctr
For this assignment I have built neural network with linear output layer. You can find the code in 'test_assignment.ipynb'

### Data preprocessing
1. Download train data set and packages 'stopwords', 'punkt', 'wordnet', 'omw-1.4'. It contains dictionaries that will help us preprocess sentences. 
2. In preprocessing we leave only alphabets, keep all lower case, tokenize sentences to words, remove stopwords, and keep all words in the inflected forms so they can be analysed as a single item.
3. Using the text vectorization convert the text into numerical representation.
4. Split the data on a train and val sets and keep it in arrays.

### Model
Next build the neural network models with rectified linear units for hidden layers and linear regression for output layer. I use 25, 10, 5, 1 units for each layer. For a cost function I use Mean Squared Error, and optinaly I use Adam algorithm in training the model. Then fit the model to the data. During training cost function gives 0.0105, on the val set MSE error is 0.58.
