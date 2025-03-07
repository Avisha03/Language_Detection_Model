Language Detection AI is a Natural Language Processing (NLP) classifier that accurately identifies the language of a given text input. It utilizes CountVectorizer to convert textual data into a numerical feature matrix and employs Multinomial Naive Bayes (MultinomialNB), a probabilistic classification algorithm widely used for text classification tasks.

Key Components & Working:
Data Preprocessing:

The dataset contains multilingual text samples labeled with their respective languages.
CountVectorizer tokenizes the text and creates a sparse matrix representation based on word frequency.
Feature Extraction:

CountVectorizer transforms the text into a Bag-of-Words (BoW) model, converting each sentence into a vector of token counts.
This numerical representation allows the model to process text efficiently.
Model Training:

The dataset is split into training (67%) and testing (33%) sets using train_test_split.
The Multinomial Naive Bayes classifier is trained on the transformed text data.
Naive Bayes assumes independence between words and calculates probabilities to classify new inputs.
Prediction & Evaluation:

The model achieves high accuracy (95.3%), proving its effectiveness in distinguishing between different languages.
When a user inputs text, it is transformed using the same CountVectorizer and classified using the trained Naive Bayes model.
Real-time Language Detection:

Users can enter any text, and the model predicts the language instantly.
The approach is lightweight, efficient, and scalable for multilingual applications.
Advantages:
✅ Fast & Efficient: Uses a simple yet powerful approach for text classification.
✅ High Accuracy: Effectively distinguishes multiple languages with minimal computation.
✅ Scalable: Can be trained on larger datasets to improve performance.
✅ Versatile: Can be extended with deep learning models like LSTMs or Transformers for enhanced accuracy.

This model demonstrates a robust approach to language detection, making it ideal for applications like chatbots, translation services, and multilingual text processing. 🚀

How to Use the Language Detection Model
Using your Language Detection Model is simple and requires just a few steps:

1️⃣ Run the Model
Ensure you have installed all dependencies and execute the Python script containing the trained model.

2️⃣ Enter a Text for Detection
When prompted, enter any text in any language.

Enter a text to detect its language: Bonjour, comment ça va?

3️⃣ Get the Prediction
The model processes the input and predicts the language:
Predicted Language: French

4️⃣ Key Notes
The model uses CountVectorizer to transform text and a Multinomial Naive Bayes classifier to predict the language.
It supports multiple languages and provides real-time detection.
You can integrate it into applications like chatbots, translation tools, or content filtering systems.
Simply run, input text, and get instant language detection! 🚀

Contributing
I welcome contributions from the community. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

Thank you for using Language_Detection_AI!













