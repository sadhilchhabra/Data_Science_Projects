# Data Science Projects 

## Introduction

This repository showcases my projects in Data Science, where I have worked on two different datasets to build predictive models and analyze various aspects of the data. The two datasets used in these projects are:

1. **Spotify_Data** from Guvi
2. **Job_Salary_Prediction** from Kaggle 

For each dataset, I have conducted thorough data analysis, preprocessing, model development, and evaluation to make accurate predictions. Below, I provide a brief overview of each dataset and highlight key achievements in these projects.

---

## Project_1: Spotify Songs Genre Prediction

### Dataset Description:
- **Data Source**: Guvi
- **Objective**: Predict the Genre of the music based on most suitable features like speechiness, instrumentalness, danceability and more.

### Achievements:
- Conducted thorough data cleaning and feature engineering to preprocess the dataset in preparation for modeling.
- Performed comprehensive data analysis to ascertain the variables influencing the genre of music.
- Utilized feature scaling, skewness reduction, and oversampling techniques to enhance the performance of the model.
- Explored multiple machine learning algorithms and optimized hyperparameters to achieve optimal model performance.
- Developed a predictive model that accurately predicts music genre.

### Column Description:
This dataset comprises Spotify tracks spanning across 125 diverse genres. Every track includes specific audio characteristics. Presented in CSV format, the data is organized in a table-like structure, ensuring swift loading. 

- **track_id**: The Spotify ID for the track
- **artists**: The artists' names who performed the track. If there is more than one artist, they are separated by a ;
- **album_name**: The album name in which the track appears
- **track_name**: Name of the track
- **popularity**: The popularity of a track is a value between 0 and 100, with 100 being the most popular. The popularity is calculated by algorithm and is based, in the most part, on the total number of plays the track has had and how recent those plays are. Generally speaking, songs that are being played a lot now will have a higher popularity than songs that were played a lot in the past. Duplicate tracks (e.g. the same track from a single and an album) are rated independently. Artist and album popularity is derived mathematically from track popularity.
- **duration_ms**: The track length in milliseconds
- **explicit**: Whether or not the track has explicit lyrics (true = yes it does; false = no it does not OR unknown)
- **danceability**: Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable
- **energy**: Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. For example, death metal has high energy, while a Bach prelude scores low on the scale
- **key**: The key the track is in. Integers map to pitches using standard Pitch Class notation. E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key was detected, the value is -1
- **loudness**: The overall loudness of a track in decibels (dB)
- **mode**: Mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0
- **speechiness**: Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks
- **acousticness**: A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic
- **instrumentalness**: Predicts whether a track contains no vocals. "Ooh" and "aah" sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly "vocal". The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content
- **liveness**: Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live
- **valence**: A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry)
- **tempo**: The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration
- **time_signature**: An estimated time signature. The time signature (meter) is a notational convention to specify how many beats are in each bar (or measure). The time signature ranges from 3 to 7 indicating time signatures of 3/4, to 7/4.
- **track_genre**: The genre in which the track belongs

---

## Project_2: Salary Prediction for Job Posting

### Dataset Description:
- **Data Source**: Kaggle (Kaggle Competition)
- **Objective**: Predict the Salary for Job Posting based on most suitable features like Skills, Company and more.
- **Evaluation Matrix** *(as given in the description of Kaggle Competition)*: Mean Absolute Percentage Error (MAPE)

### Achievements:
- Conducted thorough data cleansing and feature engineering to preprocess the dataset in preparation for modeling.
- Performed comprehensive data analysis to ascertain the variables influencing Salary.
- Preprocessed and cleaned the dataset, addressing missing data and encoding categorical features.
- Tried to achieve as low MAPE score as possible (Evaluation Matrix of the competition : MAPE)
- Built a robust predictive model for predicting the Salary for Job Postings.

### Column Description:
The dataset consists of over 55000 job postings about Data World, including skills, salaries, companies, etc. scraped from the websites in US.

- **ID**: ID of the job posting
- **Job**: Job name
- **Jobs_Group**: Jobs grouped in a few categories
- **Profile**: Lead/Senior/Junior or none
- **Remote**: Remote/Hybrid or none
- **Company**: Company name
- **Location**: the language the book is written in
- **City**: City
- **State**: State
- **Frequency_Salary**: year/month/week/day
- **Mean_Salary**: mean salary (USD)
- **Skills**: Skills, titles, certification, etc required
- **Sector**: Sector Company
- **Sector_Group**: Sector company grouped
- **Revenue**: Revenue size of the company
- **Employee**: Number of employee size of the company
- **Company_Score**: Score given by the users
- **Reviews**: Number of reviews of the Company_Score
- **Director**: Name of the Company Director
- **Director_Score**: Score of the company Director
- **URL**: Company website

**Kaggle Competiiton Link**: <a href="https://www.kaggle.com/competitions/salary-prediction-for-job-postings/overview">Salary Prediction for Job Posting</a>

---

## Conclusion

I was able to complete two different machine learning tasks for my final project. Each one had its own challenges. The project shows that I can look at data, create features, choose the right machine learning algorithms, and tweak models so they can make accurate predictions.

You can look through the different folders in this repository to get to the code, Jupyter notebooks, and detailed documentation for each dataset. I hope this project shows how machine learning can be used to solve problems in the real world.
