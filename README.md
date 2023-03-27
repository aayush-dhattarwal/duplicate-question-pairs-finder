# duplicate-questions-finder
The "Duplicate Question Pairs Finder" project is a machine learning project that is designed to identify whether a pair of questions are duplicate or not. The project utilizes the Quora Question Pairs dataset and uses various Natural Language Processing (NLP) libraries provided by NLTK (Natural Language Toolkit).
The feature engineering of the project includes several types of features such as Bag-of-words features, Token features, Length-based features, and Fuzzy features. These features are extracted from the text of the questions to help the model better understand the context and meaning of the questions. Bag-of-words features are used to represent the text as a vector of word counts, while token features identify individual words and their positions in the text. Length-based features capture the length of the questions, and Fuzzy features are used to compare the similarity of two questions based on their similarity score.
The project employs the Random Forest approach as its machine learning model. This approach has been proven to be effective in identifying duplicate questions and has achieved an accuracy of ~80%. The model uses the features extracted through the feature engineering phase to make predictions about whether a pair of questions are duplicates or not.

# Dataset used
https://www.kaggle.com/c/quora-question-pairs

# Screenshots
![firefox_Tukb2FJALy](https://user-images.githubusercontent.com/29508011/221418953-fb38cbbe-dfc6-452a-95e0-16e56dd560ae.png)
![firefox_9hp7nKpQBb](https://user-images.githubusercontent.com/29508011/221418964-31a64765-ee03-4c0f-967b-bae482f5bacb.png)
![firefox_8fSgPNVLkg](https://user-images.githubusercontent.com/29508011/221418967-ba335823-41d0-4e4a-9bf5-52b461a081d6.png)

# Tech Stack
•	Front-End: Streamlit

•	Back-End: Streamlit, Python

•	IDE: Jupyter Notebook, Pycharm

# How to run this app
1) Clone this repository

2) Create a virtual environment by using this series of commands:

 ----> pip install virtualenv > virtualenv myenv > myenv\Scripts\activate (for windows)

 ----> pip install virtualenv > virtualenv virtualenv_name > source virtualenv_name/bin/activate (for linux)

3) Copy all files from the cloned repo to newly created virtual environment folder.

4) Install all the packages by using the following command: pip install -r requirements.txt
 
5) Now for the final step. Run the app using this command: streamlit run app.py
