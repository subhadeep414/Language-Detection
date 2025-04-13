🌍 Language Detection using Naive Bayes 

This is a simple command-line Python project that detects the language of a given text input. It uses Multinomial Naive Bayes and CountVectorizer to classify text into 22 different languages based on a labeled dataset.

📚 Dataset
The app uses a CSV file named language.csv which must contain:
Text: The sentence or phrase.
language: The corresponding language label.

🧠 Model
Vectorization: Uses CountVectorizer to convert text into numerical features.
Classifier: Trains a MultinomialNB model to classify text based on the language.
Training/Test Split: 67% training and 33% testing.

📂 Project Structure
language_detector.py       # Main script
language.csv               # Language dataset (Text + Language)
README.md                  # Project info

📄 License
This project is open-source and free to use under the MIT License.
