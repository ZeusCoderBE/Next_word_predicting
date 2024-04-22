# Building an RNN model to predict the next word that will appear in a sentence is a problem in natural language processing

## Introduce

### Basic simulation image of RNN neural network
![image](https://github.com/ZeusCoderBE/Next_word_predicting/assets/117000361/259c7bb5-703f-412c-b028-4f5edcb2c194)

### Environment setup
1. **Install Python libraries:** `numpy`,`tensorflow`,`scikit-learn`, `regex` .
2. **Dataset:**
- Text data is used from "Speech of the Rector of Ho Chi Minh City University of Technology and Education at the ceremony celebrating 50 years of Vietnam-Germany relations"
  
- Link: https://hcmute.edu.vn/?ArticleId=aead837e-8612-4ce7-80b0-6ae40dca6a53.

- The dataset includes 518 words
### Steps to build a model in the project
1. **Preprocessing:**
           - I implemented data preprocessing steps, including sentence extraction, word dictionary generation, and input sequence generation using the n-gram method.
   
2. **Word Embedding:**
           -I use a word embedding layer to reduce the representation size of words. To improve computing and learning abilities.
           -I represent words in a multidimensional vector space to capture semantic relationships.

3. **Recurrent Neural Network (RNN):**
           - I built a deep learning architecture, including embedding layers and SimpleRNN to train the model.
           - I used TensorFlow and Keras libraries to develop and evaluate the model
   
4. **Performance evaluation**
           - Used metrics such as accuracy, precision, recall, and F1 score to evaluate the performance of RNN models on the test set.

### Libraries and Technology
- **Programming language:** Python
- **Main libraries:** numpy, scikit-learn, tensorFlow, regex 
- **Model:** RNN


### Oriented development
- I will use a larger data set to build the model.
- I will use other models such as LSTM and GRU to overcome the limitation of the RNN model that the derivative in the back propagation process is exploded or vanishing.
- I will use the contextual word separation method for better performance
### Conclusion
  - This project provides an overview of different NLP techniques and how to implement them for text processing and analysis. The models were trained and evaluated on real-world text data to ensure their effectiveness in handling natural language tasks.
