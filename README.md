# NLP Project - Song Analysis


## Coding environment details:
Coding was performed on Jupyter Notebook (localhost). However, it should work on any form of Jupyter.

## Libraries:
Necessary libraries are imported in the code.
Unless otherwise noted, library versions are the most recent versions. Any new libraries not yet used in the class were installed via pip and the latest version.

## Contributions:
Theo: Worked on the song lyric commercial performance task as shown in the file `Primary Code - Song Lyrics and Commercial Performance Task.ipynb`. Engineered features based on the lyrics data and developed a model to predict the popularity. For this task, the input is a set of lyrics and the output is the popularity. 

Sriyans: Worked primarily on the initial data analysis phase for the commercial performance task. This included generating metrics and plots. For this portion, the code is in the `Supplementary Code - Song Lyrics and Commercial Performance Task.ipynb` file. NOTE: this is a large file, so it may not render on GitHub. Please download it to see it.

Tejas: Worked on the v1 of the emotion classification `Emotion_Analysis_v1_Tejas_Hariharan.pynb`, the `Lyric_Extender.pynb`, and the final song linked below.  

Neil: Worked on "Lyric_Extender" and Genre Classification prediction with Kevin. This includes researching a feasible dataset that had the features we needed, as well as primarily coding the SVM algorithm and testing around with different chunking and test/train splits
Vedant - Worked on the sentimental analysis to classify the emotion of the song as show in the file 'Sentimental_Analysis.ipynb'. It was done by using a pretrained RoBERTa model. The input is the lyrics of the song and the output is the emotion the song potrays.

Kevin: Worked on the genre classification as well as creating a dataset for the improvement of the lyric extender. As for the genre classification I spent ample amount of time researching the ideal dataset to train our model to predict genres. I primarily worked on the genre classification python notebook that is included in the repository, designing the SVM algorithm and TF-IDF vectorizer. I also manually created a dataset of lyrics to upload to our model to create new lyrics. 
## Final results:
For the song lyric commercial performance task we achieved a RMSE of about 23.54 (the scale of predictions is 0-100).

The final song created from the Feed Foreward Lyric generator and sentiment and genre analysis is here: https://on.soundcloud.com/fuuW2eBZG72XsSp7A
Original music composed by Tejas Hariharan, lyrics genereted through the model.

## Datasets
For the commercial performance task (primary code), the following dataset was used:  
https://www.kaggle.com/datasets/imuhammad/audio-features-and-lyrics-of-spotify-songs  
Make sure to rename it to `data.csv`.
This notebook also uses the file `explicit_words.txt` to check for explicit words. It is available at the Drive link here: https://drive.google.com/drive/folders/1zs_IN5WHrJ-WsPj3IMOxn871Bt6eZ6Ia?usp=sharing


For the commercial performance task (supplementary code), we have uploaded the datasets used to the following Drive link: https://drive.google.com/drive/folders/1zs_IN5WHrJ-WsPj3IMOxn871Bt6eZ6Ia?usp=sharing. Note that some of the data used in the notebook is scraped in the notebook code.

For the V1 of the Emotion analysis, and the genre classification, these datasets were used: 
https://www.kaggle.com/datasets/parulpandey/emotion-dataset?select=validation.csv
https://www.kaggle.com/datasets/imuhammad/audio-features-and-lyrics-of-spotify-songs?resource=download




