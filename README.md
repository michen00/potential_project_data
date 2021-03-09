# Potential project datasets
[Rubric](https://docs.google.com/document/d/13fDCGo7mPNpuKM2na52GMLAncdZr8JCIWdjUE7QEDBI/edit) for Springboard project submission 3.5.2.

Each directory specified below contains data collected for a corresponding project idea.

See also [social_media_food_desert_classification](https://github.com/michen00/social_media_food_desert_classification).
See also [multilingual_speech_valence_class](https://github.com/michen00/multilingual_speech_valence_classification/blob/main/DATA.md).

---

## Submission Instructions:
For Step 2 of your Capstone, submit a link to your GitHub repository that contains the following:
1. Three datasets that you have explored - you don't need to link the entire dataset.
1. Code for how you collected the data, if applicable
1. The actual dataset — If your dataset is small enough to fit in a CSV, then include it in the repository. If it’s a big dataset or has a lot of binary files (graphics, audio), consider using the Git Large File Storage extension.
---

## Multimodal sentiment analysis to predict winners of creative game show competitions
### Directory name
[game_show_winner_predict](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict)
### Application
Many game shows prune competitors episode by episode for an eventual winner at the end of the season. Viewers entertained by such shows are naturally interested in predicting the winner but may be limited to making predictions based on subjective and qualitative judge feedback, especially for creative competitions (e.g., *Face Off*, *Ink Master*, *Lego Master*, *RuPaul’s Drag Race*). Multimodal sentiment analysis of judges’ comments per competitor could be leveraged alongside other indicators (e.g., numerical judge ratings, challenge wins, etc.) to predict the season winners.
### Data
Subtitle files are readily searchable for the episodes of many shows. Data for other modalities can be obtained by processing video files for spectrographs of judge audio or clips of the reviews for analysis of judges’ facial expressions. Other indicators like scores or challenge wins can be annotated as well.
### Data gathered for project submission
I downloaded subtitle files from the following web pages:
* [*Face Off*](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/face_off)
  * [S1](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/face_off/s1): http://www.tvsubtitles.net/subtitle-1589-1-en.html
  * [S2](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/face_off/s2): http://www.tvsubtitles.net/subtitle-1589-2-en.html
  * [S3](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/face_off/s3): http://www.tvsubtitles.net/subtitle-1589-3-en.html
  * [S4](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/face_off/s4): http://www.tvsubtitles.net/subtitle-1589-4-en.html
  * [S5](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/face_off/s5): http://www.tvsubtitles.net/subtitle-1589-5-en.html
  * [S6](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/face_off/s6): http://www.tvsubtitles.net/subtitle-1589-6-en.html
  * [S7](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/face_off/s7): http://www.tvsubtitles.net/subtitle-1589-7-en.html
  * [S8](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/face_off/s8): http://www.tvsubtitles.net/subtitle-1589-8-en.html
  * [S9](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/face_off/s9): http://www.tvsubtitles.net/subtitle-1589-9-en.html
* [*RuPaul's Drag Race*](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/rupauls_drag_race)
  * [S04](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/rupauls_drag_race/s04): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-1353056/season-4
  * [S08](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/rupauls_drag_race/s08): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-1353056/season-8
  * [S09](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/rupauls_drag_race/s09): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-1353056/season-9
  * [S10](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/rupauls_drag_race/s10): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-1353056/season-10
  * [S11](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/rupauls_drag_race/s11): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-1353056/season-11
  * [S12](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/rupauls_drag_race/s12): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-1353056/season-12
  * [S13](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/rupauls_drag_race/s13): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-1353056/season-13
* [*RuPaul's Drag Race All Stars*](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/rupauls_drag_race_all_stars)
  * [S2](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/rupauls_drag_race_all_stars/s2): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-2301351/season-2
  * [S3](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/rupauls_drag_race_all_stars/s3): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-2301351/season-3
  * [S4](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/rupauls_drag_race_all_stars/s4): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-2301351/season-4
  * [S5](https://github.com/michen00/potential_project_data/tree/main/game_show_winnner_predict/rupauls_drag_race_all_stars/s5): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-2301351/season-5

## Predict the stock price movement of Dow Jones tickers based on sentiment analysis of yesterday’s headlines
### Directory name
[headlines_sentiment_djia_predict](https://github.com/michen00/potential_project_data/tree/main/headlines_sentiment_djia_predict)
### Application
Many traders are interested in predicting how the price of a given company or industry index may fluctuate tomorrow. Short-term investors may wish to make trades in response to news headlines mentioning company names. This information could potentially be used alongside standard technical indicators to improve prediction accuracy.
### Data
A [financial news headlines dataset](https://www.kaggle.com/notlucasp/financial-news-headlines) and [stock prices for Dow companies](https://www.kaggle.com/bigt90/stock-prices-dow-jones-companies-and-djia-dynamics) are available on Kaggle; both include data between 2017 and 2020. Various other publicly accessible datasets of headlines may be useful as well. [Technical indicators for several Dow companies](https://www.kaggle.com/nikhilkohli/us-stock-market-data-60-extracted-features) covering the same period are on Kaggle too and missing data could ostensibly be [calculated](https://stock-prediction-dashboard.herokuapp.com/).
### Data gathered for project submission
* [djia](https://github.com/michen00/potential_project_data/tree/main/headlines_sentiment_djia_predict/djia)
  * A. bigt90, *Stock Prices Dow Jones Companies and DJIA Dynamics: Info about the Oldest US Stock Market Index - Dow Jones Industrial Average. V1.* Mar. 24, 2020. Distributed by Kaggle. Accessed Feb. 6, 2021. [Online]. Available: https://www.kaggle.com/bigt90/stock-prices-dow-jones-companies-and-djia-dynamics/version/1
* [financial_news_headlines](https://github.com/michen00/potential_project_data/tree/main/headlines_sentiment_djia_predict/financial_news_headlines)
  * L. Pham, *Financial News Headline Data: Headlines Related to U.S. Businesses from CNBC, the Guardian, and Reuters.* Jul. 18, 2020. Distributed by Kaggle. Accessed Feb. 6, 2021. [Online]. https://www.kaggle.com/notlucasp/financial-news-headlines
* [us_technicals](https://github.com/michen00/potential_project_data/tree/main/headlines_sentiment_djia_predict/us_technicals)
  * N. Kohli, *US Stock Market Data & Technical Indicators: Stock Market Technical Indicators Data for Multiple US Companies for Forecasting. V1.* Aug. 16, 2020. Distributed by Kaggle. Accessed Feb. 6, 2021. [Online]. Available: https://www.kaggle.com/nikhilkohli/us-stock-market-data-60-extracted-features/version/1

## Generate high-sentiment form poetry with topical cohesion
### Directory name
[poetry_generation](https://github.com/michen00/potential_project_data/tree/main/poetry_generation)
### Application
This is primarily an artistic endeavor. Machine-generated music could be supplemented by machine-generated lyrics.
### Data
Previous efforts have used the [English Gigaword](https://catalog.ldc.upenn.edu/LDC2003T05) corpus, [song lyrics](https://www.kaggle.com/paultimothymooney/poetry), and [samples from Wikipedia](https://www.kaggle.com/mikeortman/wikipedia-sentences) as training corpora.
### Data gathered for project submission
* [song_lyrics](https://github.com/michen00/potential_project_data/tree/main/poetry_generation/song_lyrics)
  * P. Mooney, *Song Lyrics: Poetry and Lyrics (TXT Files). V16.* Aug. 18, 2018. Distributed by Kaggle. Accessed: Feb. 6, 2021. [Online]. Available: https://www.kaggle.com/paultimothymooney/poetry/version/16
* [wikisent2.txt](https://github.com/michen00/potential_project_data/tree/main/poetry_generation)
  * M. Ortman, *Wikipedia Sentences: Collection of 7.8 million Sentences from the August 2018 English Wikipedia Dump. V3.* Aug. 24, 2018. Distributed by Kaggle. Accessed: Feb. 6, 2021. [Online]. Available: https://www.kaggle.com/mikeortman/wikipedia-sentences/version/3

## Suggest image edits based on Instagram accounts or hashtags
### Directory name
n/a
### Application
Digital marketing specialists are often tasked with batch editing of image assets to ensure a consistent look and feel. Selecting and tuning the appropriate filters/presets is key to this workflow. Image editing settings for a given input image may be suggested based on user-selected hashtags or specific Instagram accounts.
### Data
Instagram APIs could be leveraged to aggregate the account feeds or hashtag query results.
### Data gathered for project submission
I chose not to gather data for this project idea yet.
