# Spotify-Stream-Prediction
In this project, we try to use different time series model to predict Spotify Streams to see if we can see the trend of songs.
We getting data from Kaggle, and we use 2017 Spotify Stream data.

# Total Stream Prediction
We first want to predict the total streams so that we can know the ideal day and month to release a new song.


## SARIMA
After checking stationary of data, we know found the weekly seasonality in data, so we decide to use SARIMA.

![image](https://github.com/Zoesu0/Spotify-Stream-Prediction/assets/122922541/c7469988-0d48-4589-a0d1-fd2738fb8df9)
We try on difference parameters to find a better result.

![image](https://github.com/Zoesu0/Spotify-Stream-Prediction/assets/122922541/58266680-2ffb-405f-9f0a-f2f7cd78bd2b)

## LSTM
Later we try a different way LSTM
![image](https://github.com/Zoesu0/Spotify-Stream-Prediction/assets/122922541/36433e55-c44c-4a3e-a9ac-0b01fed18dd5)

# Shape of You Prediction
We later decide to predict a single song, since Shape of You publish on January 7, 2017, we think that the song is a good target to predict.

![image](https://github.com/Zoesu0/Spotify-Stream-Prediction/assets/122922541/bf196a1e-53fa-4413-9910-426624b46cdd)


## Dataset:
https://www.kaggle.com/datasets/edumucelli/spotifys-worldwide-daily-song-ranking
https://www.kaggle.com/datasets/nadintamer/top-tracks-of-2017

## SARIMA
![image](https://github.com/Zoesu0/Spotify-Stream-Prediction/assets/122922541/bf196a1e-53fa-4413-9910-426624b46cdd)
![image](https://github.com/Zoesu0/Spotify-Stream-Prediction/assets/122922541/3d61cf2c-2c72-4986-aadd-76c159f6aa64)

## LSTM
![image](https://github.com/Zoesu0/Spotify-Stream-Prediction/assets/122922541/3c2bd4d6-8603-4776-a3ac-5e00027c7ae4)

