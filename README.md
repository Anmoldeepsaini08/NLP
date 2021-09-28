# NLP
Natural Language Processing Projects

Work in progress for the Attention model to gain the highest accuracy. 

Pipeline for the Attention model:

Step 1: Importing the necessary keras layers from tensorflow ( tensorflow > 2.0 ). 

Step 2: Loading the txt file ( English to French ). 

Step 3: Storing the maximum length of sentence. 

Step 4: Assigning the tokens to the unique characters of input and target sentences.

Step 5: Creating the 3D tensor and initializing to Zero's.

Step 6: Adding the padding to the input sentences.

Step 7: Assigning the 1 where that particual char is present in the input and target tokens.

Step 8: Creating the Bidirectional LSTM ( Encoder ) .

Step 9: Creating the LSTM ( Decoder ).

Step 10: Adding the attention layer.

Step 11: Concating attention model output and decoder LSTM sequence output from each time-stamps.

Step 12: Adding the dense layer with output units of length of decoder_length ( decoder length  => length of target character).

Step 13: Creating model , compiling with the best optimizer fits with this model and using categorical_crossentropy.

Step 14: Train the model using .fit .

Step 15: Train model with the same pipeline which is used to train the model.

