#                                                                              Group 8
# Hate Speech Detection on Social Media Comments.
## **Problem Statement Overview** :

In the digital age, social media platforms face significant challenges in maintaining a safe and respectful online community, particularly with the proliferation of hate speech in user-generated comments. The primary objective is to develop a robust hate speech detection system using advanced natural language processing (NLP) techniques to enhance content moderation capabilities on Social Media Platforms. Efficient hate speech detection is pivotal for maintaining platform integrity and user trust, ensuring comments are following the guidelines.

## **Solution**:

This project aims to develop an AI model to detect hate speech in the Social Media comment Section. The model is trained using a labeled dataset and employs various natural language processing (NLP) techniques to identify and classify hate speech.

**Steps:**

**Data Preparation**: Collected and preprocessed data. The Preprocessing Involves various data cleaning steps and EDA for getting insights about the data quality.

**Model Development**: Developed various ML and DL models and evaluated them to select the best-performing ones from each of them. Here, we used TF-IDF embedding and built a deep-learning model involving various layers. The model was trained on the cleaned data. After testing multiple embedding techniques, TF-IDF was the best fit for our dataset.



**Performance**: The Deep Learning model's performance was then evaluated using various metrics, but the main focus was on the F1 score, which is a combination of precision and recall. The DL model was able to achieve a good F1 score, making it efficient for the next step.

**Prediction**: The DL Model is ready for real-time detection on the comments to check how the model performs on real-time data.

## **Dataset Description**:

Social media platforms have become the most prominent medium for spreading hate speech, primarily through hateful textual content. An extensive dataset containing emoticons, emojis, hashtags, slang, and contractions is required to detect hate speech on social media based on current trends. This dataset contains hate speech sentences in English and is confined into two classes, one representing hateful content and the other representing non-hateful content

The dataset used in training this model contains 10,000 entries sourced from the Hate Speech Curated Dataset on Kaggle. Given the size and complexity of the original dataset, we selected a balanced subset of 10,000 rows, ensuring an equal ratio of hate speech to non-hate speech. The dataset is straightforward, comprising text comments from various social media platforms and corresponding labels indicating whether the comment is hate speech or not.

The Content column contains the input text and the Label column contains the input label 0 and 1.

“0″ - non-hateful

“1″ - hateful

link: https://www.kaggle.com/datasets/waalbannyantudre/hate-speech-detection-curated-dataset


## Acknowledgments:

#### Under Guidence of **Infosys Internship Team**
 

 **Team 8:**

* Shreyansh Kahate

* Madhuri K

* Nikitha S

## License:

This project is licensed under the MIT License - check out the LICENSE file for more details.

## Acknowledgements

- The dataset was sourced from Kaggle.
- Special thanks to the contributors of this project.
