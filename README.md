# 👺 Context-Sensitive Emotion Detection in Bangla Text using Deep Learning

Emotion identification from textual data is becoming an increasingly relevant study, particularly as social media and other Web 2.0 platforms allow people to communicate a wide spectrum of emotions. Despite tremendous advances in high-resource languages such as English, emotion recognition in low-resource languages, notably Bangla, remains an unexplored subject. Combining the two publicly available datasets of UBMEC and Bengali_Banglish. We (i) examine the effectiveness of the baseline and ensemble approach for emotion detection. (ii) We presented a benchmark strategy and robustness of emotion identification in Bengali texts. (iii) Identifying difficulties and answers to identifying emotions in writing. The experiment found that the hyperparameter tuning of the CNN+LSTM had a maximum accuracy of 57% on the test data. Also, offers observations and issues that demonstrate the complexities of emotion categorization.


# Dataset 
👉 (https://github.com/Biplob1233/Emotion_Bangla_Text/tree/main/Datasets) 

In this research, the data collection process has been divided into two parts. First, we used two different datasets for experiments. The UBMEC datasets and Bengali_Banglish have been used to access the performance of the model. The UBMEC dataset contained 13072 data based on the six different classes (joy, anger, sadness, surprise, fear, and disgust), which are shown in Table I. Another dataset of Bengali_Banglish (12) contains 80000 data points based on the same six emotions. The mentioned datasets were collected from social media comments, YouTube, newspapers, and so on. Combining the two datasets of UBMEC and Bengali_
Banglish to ensure a robust and comprehensive dataset. Table I describes the class-wise data distribution for each of these datasets. Which is shown in the table.

![image](https://github.com/user-attachments/assets/86d057c6-38cd-4ed2-b960-72ba22ddfc50)

# Preprocessing
👉 (https://github.com/Biplob1233/Emotion_Bangla_Text/tree/main/Preprocessing)

Preparing the data by applying various preprocessing techniques to clean the Bangla textual data, which reduced the noise and model complexity shown in the figure. This step included text cleaning (removing punctuation and special characters, handling numbers and URLs), normalization (Unicode standardization, removing extra white spaces), tokenization (word tokenization, subword tokenization), stop word removal, handling code-mixed text and so on (mentioned on paper).

![clean data](https://github.com/user-attachments/assets/93eb882b-7cc9-453b-b130-04b129cad732)

# Approach

Investigating the baseline model and ensemble deep learning approach for detecting Bangla emotions from the textual data. This section describes how the dataset was prepared, how features were extracted, how the training procedure was carried out, and how performance was evaluated using metrics. The entire process is shown in Figure. Train the model using the 60% training sets. After that, we validated the trained model using the validation set in each epoch of the training (mentioned on paper).

![method](https://github.com/user-attachments/assets/373b643d-cffe-43ac-8c0c-d81b4691bd48)

This section describes the performance of the evaluated model. The table shows the performance of the used model. The study on Table showed that the CNN + LSTM tuning model outperformed the other model to classify the emotion in Bangla text.

![image](https://github.com/user-attachments/assets/c792a4d4-59cd-472c-92af-7f38d808332a)

# Conclusion

The paper illustrates the effectiveness of several deep learning algorithms in categorizing emotions in Bangla texts from social media comments. The testing takes place using two separate datasets that are freely available to the scientific community. Our research used a variety of models to classify emotion into six categories. Overall, among deep learning algorithms, the CNN+LSTM model exceeds other models with a 57% accuracy. This study emphasizes the possible complexities of emotion classification in the text. Future directions involve exploring other deep learning models for multimodal emotion categorization, such as voice. Also, combine the Bangla text datasets with randomized text such as Banglish.

