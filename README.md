# Chatbot_Using_Deep_Learning
Chatbot_Using_Deep_Learning

Introduction
A chatbot is a computer program designed to simulate conversation with human users, especially over the internet. They are often used in customer service,virtual assistants, and various other applications to provide information, answer questions, and assist users in completing tasks. Chatbots can be simple orcomplex, with some using artificial intelligence (AI) and natural language processing (NLP) to understand and respond to user input in a more human-like manner.They are becoming increasingly popular due to their ability to automate interactions and provide efficient and personalized customer service.

# Application on `Deep Learning` models into the `Chatbot`:

1. **Artificial Neural Network (ANN)**: The code uses a type of ANN called a Multilayer Perceptron (MLP). An MLP consists of multiple layers of nodes, each connected to nodes in the adjacent layers. These nodes, or neurons, process inputs and pass the result to the next layer. The MLP learns patterns in the input data through a process called backpropagation, adjusting the weights of connections between neurons to minimize errors in predictions.


2. **Natural Language Processing (NLP)**: NLP techniques are employed to preprocess the text data. This includes:
   - **Tokenization**: Breaking down sentences into individual words or tokens.
   - **Lemmatization**: Reducing words to their base or root form. For example, "running" becomes "run".
   - **Normalization**: Converting all text to lowercase to ensure consistency.


3. **Training the Model**: The preprocessed text data is used to train the ANN. Each sentence is represented as a "bag of words," a numerical vector indicating the presence or absence of each word in the sentence. The output layer of the ANN has neurons corresponding to different intents, and the model is trained to predict the correct intent for a given input sentence.


4. **Predicting Intents**: Once the model is trained, it can predict the intent of new user messages. The input message is preprocessed using the same NLP techniques, converted into a bag of words, and fed into the ANN. The output neuron with the highest activation represents the predicted intent, and the corresponding response is selected from the predefined responses.

