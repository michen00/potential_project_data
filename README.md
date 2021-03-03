# Potential project datasets
[Rubric](https://docs.google.com/document/d/13fDCGo7mPNpuKM2na52GMLAncdZr8JCIWdjUE7QEDBI/edit) for Springboard project submission 3.5.2.
Each directory specified below contains data collected for a corresponding project idea.

See also [Springboard_capstone_project](https://github.com/michen00/Springboard_capstone_project).

---

## Submission Instructions:
For Step 2 of your Capstone, submit a link to your GitHub repository that contains the following:
1. Three datasets that you have explored - you don't need to link the entire dataset.
1. Code for how you collected the data, if applicable
1. The actual dataset — If your dataset is small enough to fit in a CSV, then include it in the repository. If it’s a big dataset or has a lot of binary files (graphics, audio), consider using the Git Large File Storage extension.
---

## Classify multilingual emotional speech audio by valence
### Directory name
[multilingual_speech_valence_class](https://github.com/michen00/Springboard/tree/main/capstone_data/multilingual_speech_valence_class)
### Application
Emotion recognition is an important part of natural language understanding. Conversational agents accepting voice input have already been deployed in many contexts such as healthcare or customer service where empathic responses improve the quality of services provided.
### Data
English audio samples with emotion labels are publicly available from the [Carnegie Mellon University Let’s Go Spoken Dialogue Corpus](https://www.ultes.eu/ressources/lego-spoken-dialogue-corpus/), [Crowd-sourced Emotional Multimodal Actors Dataset](https://github.com/CheyneyComputerScience/CREMA-D), the [Electromagnetic Articulography Database](https://span.usc.edu/owncloud/index.php/s/RTttck1EJ6Vcoyu), the [Emotional Voices Database](https://mega.nz/folder/KBp32apT#gLIgyWf9iQ-yqnWFUFuUHg), the [Interactive Emotional Dyadic Motion Capture Database](https://sail.usc.edu/iemocap/iemocap_release.htm), the [JL-Corpus](https://www.kaggle.com/tli725/jl-corpus), the [Multimodal EmotionLines Dataset](https://github.com/declare-lab/MELD/), the [Ryerson Audio-Visual Database of Emotional Speech and Song](https://zenodo.org/record/1188976), the [Surrey Audio-Visual Expressed Emotion Database](http://personal.ee.surrey.ac.uk/Personal/P.Jackson/SAVEE/Download.html), the [Toronto Emotional Speech Set](https://dataverse.scholarsportal.info/dataset.xhtml?persistentId=doi%3A10.5683%2FSP2%2FE8H2MF), and the [Variably Intense Vocalizations of Affect and Emotion Corpus](https://zenodo.org/record/4066235). Similar corpora may be freely available for Arabic ([Arabic Natural Audio Dataset](https://www.kaggle.com/suso172/arabic-natural-audio-dataset)), Canadian French ([Canadian French Emotional Speech Database](https://www.gel.usherbrooke.ca/audio/cafe.htm)), Danish ([Danish Emotional Speech Database](https://web.archive.org/web/20070223173415/http://kom.aau.dk:80/~tb/speech/Emotions/)), Estonian ([Estonian Emotional Speech Corpus](https://metashare.ut.ee/repository/download/4d42d7a8463411e2a6e4005056b40024a19021a316b54b7fb707757d43d1a889/)), French ([French Emotional Speech Database - Oréau](https://zenodo.org/record/4405783)), German ([Berlin Database of Emotional Speech](https://www.kaggle.com/piyushagni5/berlin-database-of-emotional-speech-emodb)), Greek ([Acted Emotional Speech Dynamic Database](https://mega.nz/folder/0ShVXY7C#-73kVoK05OjTPEA95UUvMw)), Persian ([Sharif Emotional Speech Database](https://github.com/mansourehk/ShEMO)), Turkish ([BAUM-1](https://archive.ics.uci.edu/ml/datasets/BAUM-1) and [BAUM-2](https://archive.ics.uci.edu/ml/datasets/BAUM-2)), and Urdu ([Urdu Language Speech Dataset](https://www.kaggle.com/bitlord/urdu-language-speech-dataset)).
### Data gathered for project submission
* English
  * [Emotional_EMA](https://github.com/michen00/Springboard/tree/main/capstone_data/multilingual_speech_valence_class/Emotional_EMA) | Electromagnetic Articulography Database
    * S. Lee, S. Yildirim, A. Kazemzadeh, and S. S. Narayanan, "An articulatory study of emotional speech production," in *Proc. InterSpeech,* Lisbon, Portugal, Sep. 2005, pp. 497–500. Accessed: Feb. 8, 2021. [Online.] Available: https://sail.usc.edu/ema_web/LeeInterSpeech2005.pdf
  * [EmoV-DB_sorted](https://github.com/michen00/Springboard/tree/main/capstone_data/multilingual_speech_valence_class/EmoV-DB_sorted) | Emotional Voices Database
    * A. Adigwe, N. Tits, K. El Haddad, S. Ostadabbas, and T. Dutoit, "The emotional voices database: Towards controlling the emotion dimension in voice generation systems," 2018, *arXiv:1806.09514*. Accessed: Feb. 8, 2021. [Online]. Available: https://arxiv.org/pdf/1806.09514.pdf
  * [jl-corpus](https://github.com/michen00/Springboard/tree/main/capstone_data/multilingual_speech_valence_class/jl-corpus) | JL-Corpus
    * J. James, L. Tian, and C. Watson, "An open source emotional speech corpus for human robot interaction applications," in *Proc. Interspeech,* Hyderabad, India, Sep. 2–6, 2018, pp. 2768–2772. Accessed: Feb. 8, 2021. doi: https://doi.org/10.21437/Interspeech.2018-1349.
  * [LEGOv2](https://github.com/michen00/Springboard/tree/main/capstone_data/multilingual_speech_valence_class/LEGOv2) | Carnegie Mellon University Let’s Go Spoken Dialogue Corpus
    * A. Schmitt, S. Ultes, and W. Minker, "A parameterized and annotated spoken dialog corpus of the CMU Let’s Go bus information system," in *Int. Conf. Lang. Resour. and Eval.,* Istanbul, Turkey, May 2012, pp. 3369–3373. Accessed: Feb. 8, 2021. Available: http://www.lrec-conf.org/proceedings/lrec2012/pdf/333_Paper.pdf
    * S. Ultes, A. Schmitt, M. J. P. Sánchez, and W. Minker, "Analysis of an extended interaction quality corpus," in *Natural Language Dialog Systems and Intelligent Assistants,* G. G. Lee, H. K. Kim, M. Jeong, and J.-H. Kim, Eds., Cham, Switzerland: Springer Int. Publishing, 2015, pp. 41–52. doi: https://doi.org/10.1007/978-3-319-19291-8_4.
  * [ravdess](https://github.com/michen00/Springboard/tree/main/capstone_data/multilingual_speech_valence_class/ravdess) | Ryerson Audio-Visual Database of Emotional Speech and Song
    * S. R. Livingstone and F. A. Russo, "The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS): A dynamic, multimodal set of facial and vocal expressions in North American English," *PLoS ONE,* vol. 13, no. 5, p. e0196391, May 16, 2018, doi: https://doi.org/10.1371/journal.pone.0196391.
  * [savee](https://github.com/michen00/Springboard/tree/main/capstone_data/multilingual_speech_valence_class/savee) | Surrey Audio-Visual Expressed Emotion Database
    * S. Haq and P. J .B. Jackson, "Multimodal emotion recognition," in *Machine Audition: Principles, Algorithms and Systems,* W. Wang, Ed., IGI Global Press, Jul. 2010, pp. 398–423. doi: https://doi.org/10.4018/978-1-61520-919-4.
  * [tess](https://github.com/michen00/Springboard/tree/main/capstone_data/multilingual_speech_valence_class/tess) | Toronto Emotional Speech Set
    * M. K. Pichora-Fuller and K. Dupuis, *Toronto Emotional Speech Set (TESS). V1.* 2020. Distributed by Scholars Portal Dataverse. Accessed: Feb. 8, 2021. doi: https://doi.org/10.5683/SP2/E8H2MF.
  * [vivae](https://github.com/michen00/Springboard/tree/main/capstone_data/multilingual_speech_valence_class/vivae) | Variably Intense Vocalizations of Affect and Emotion Corpus
    * N. Holz, P. Larrouy-Maestri, and D. Poeppel, *The Variably Intense Vocalizations of Affect and Emotion Corpus (VIVAE). V1.* Oct. 5, 2020. Distributed by Zenodo. Accessed: Feb. 8, 2021. [Dataset]. doi: https://doi.org/10.5281/zenodo.4066235.
* Non-English
  * [aesdd](https://www.github.com/michen00/Springboard/tree/main/capstone_data/multilingual_speech_valence_class/aesdd) | Acted Emotional Speech Dynamic Database [Greek]
    * N. Vryzas, R. Kotsakis, A. Liatsou, C. A. Dimoulas, and G. Kalliris, "Speech emotion recognition for performance interaction," *J. Audio Eng. Soc.,* vol. 66, no. 6, pp. 457–467, Jun. 2018, doi: https://doi.org/10.17743/jaes.2018.0036.
    * N. Vryzas, M. Matsiola, R. Kotsakis, C. Dimoulas, and G. Kalliris, "Subjective evaluation of a speech emotion recognition interaction framework," in *Proc. Audio Mostly 2018 Sound Immersion and Emotion,* North Wales, Untied Kingdom, Sep. 12–14, 2018, p. 34. Accessed: Feb. 9, 2021. doi: https://doi.org/10.1145/3243274.3243294.
  * [anad](https://github.com/michen00/Springboard/tree/main/capstone_data/multilingual_speech_valence_class/anad) | Arabic Natural Audio Dataset
    * S. Klaylat, *Arabic Natural Audio Dataset Automatic Emotion Recognition. V11.* Dec. 1, 2017. Distributed by Kaggle. Accessed: Feb. 8, 2021. [Online]. Available: https://www.kaggle.com/suso172/arabic-natural-audio-dataset/version/11
  * [cafe](https://github.com/michen00/Springboard/tree/main/capstone_data/multilingual_speech_valence_class/cafe) | Canadian French Emotional Speech Database
    * O. Lahaie and P. Gournay, *Canadian French Emotionnal Speech Database. V1.1.* 2017. Distributed by Groupe de Recherche sur la Parole et l'Audio. Accessed: Feb. 8, 2021. [Online]. Available: https://www.gel.usherbrooke.ca/audio/cafe.htm
  * [ekorpus](https://github.com/michen00/Springboard/tree/main/capstone_data/multilingual_speech_valence_class/ekorpus) | Estonian Emotional Speech Corpus
    * H. Pajupuu, H, *Eesti Emotsionaalse Kõne Korpus. V5.* Jun. 12, 2012. Distributed by Center of Estonian Language Resources. Accessed: Feb. 9, 2021. [Online]. doi: https://doi.org/10.15155/EKI.000A.
  * [EmoDB](https://github.com/michen00/Springboard/tree/main/capstone_data/multilingual_speech_valence_class/EmoDB) | Berlin Database of Emotional Speech [German]
    * F. Burkhardt, A. Paeschke, M. Rolfes, W. Sendlmeier, and B. Weiss, "A Database of German Emotional Speech," in *Proc. InterSpeech,* Lisbon, Portugal, Sep. 2005. Accessed: Feb. 9, 2021. [Online]. Available: https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.130.8506&rep=rep1&type=pdf
  * [oreau2](https://github.com/michen00/Springboard/tree/main/capstone_data/multilingual_speech_valence_class/oreau2) | French Emotional Speech Database - Oréau
    * L. Kerkeni, C. Cleder, Y. Serrestou, and K. Raoff, *French Emotional Speech Database - Oréau. V2.* Dec. 31, 2020. Distributed by Zenodo. Accessed: Feb. 9, 2021. [Dataset]. doi: https://doi.org/10.5281/zenodo.4405783.
  * [ShEMO](https://github.com/michen00/Springboard/tree/main/capstone_data/multilingual_speech_valence_class/ShEMO) | Sharif Emotional Speech Database [Persian]
    * O. M. Nezami, P. J. Lou, and M. Karami, "ShEMO: A large-scale validated database for Persian speech emotion detection," *Lang. Resour. and Eval.,* vol. 53, no. 1, pp. 1–16, Oct. 8, 2018, doi: https://doi.org/10.1007/s10579-018-9427-x.
  * [urdu](https://github.com/michen00/Springboard/tree/main/capstone_data/multilingual_speech_valence_class/urdu) | Urdu Language Speech Dataset
    * S. Latif, A. Qayyum, M. Usman, and J. Qadir, "Cross lingual speech emotion recognition: Urdu vs. Western languages," 2020, *arXiv:1812.10411*. Accessed Feb. 10, 2021. [Online]. Available: https://arxiv.org/pdf/1812.10411.pdf

## Suggest image edits based on Instagram accounts or hashtags
### Directory name
n/a
### Application
Digital marketing specialists are often tasked with batch editing of image assets to ensure a consistent look and feel. Selecting and tuning the appropriate filters/presets is key to this workflow. Image editing settings for a given input image may be suggested based on user-selected hashtags or specific Instagram accounts.
### Data
Instagram APIs can be leveraged to aggregate the account feeds or hashtag query results.
### Data gathered for project submission
I chose not to gather data for this project idea yet.

## Multimodal sentiment analysis to predict winners of creative game show competitions
### Directory name
[game_show_winner_predict](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict)
### Application
Many game shows prune competitors episode by episode for an eventual winner at the end of the season. Viewers entertained by such shows are naturally interested in predicting the winner but may be limited to making predictions based on subjective and qualitative judge feedback, especially for creative competitions (e.g., *Face Off*, *Ink Master*, *Lego Master*, *RuPaul’s Drag Race*). Multimodal sentiment analysis of judges’ comments per competitor could be leveraged alongside other indicators (e.g., numerical judge ratings, challenge wins, etc.) to predict the season winners.
### Data
Subtitle files are readily searchable for the episodes of many shows. Data for other modalities can be obtained by processing video files for spectrographs of judge audio or clips of the reviews for analysis of judges’ facial expressions. Other indicators like scores or challenge wins can be annotated as well.
### Data gathered for project submission
I downloaded subtitle files from the following web pages:
* [*Face Off*](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/face_off)
  * [S1](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/face_off/s1): http://www.tvsubtitles.net/subtitle-1589-1-en.html
  * [S2](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/face_off/s2): http://www.tvsubtitles.net/subtitle-1589-2-en.html
  * [S3](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/face_off/s3): http://www.tvsubtitles.net/subtitle-1589-3-en.html
  * [S4](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/face_off/s4): http://www.tvsubtitles.net/subtitle-1589-4-en.html
  * [S5](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/face_off/s5): http://www.tvsubtitles.net/subtitle-1589-5-en.html
  * [S6](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/face_off/s6): http://www.tvsubtitles.net/subtitle-1589-6-en.html
  * [S7](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/face_off/s7): http://www.tvsubtitles.net/subtitle-1589-7-en.html
  * [S8](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/face_off/s8): http://www.tvsubtitles.net/subtitle-1589-8-en.html
  * [S9](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/face_off/s9): http://www.tvsubtitles.net/subtitle-1589-9-en.html
* [*RuPaul's Drag Race*](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/rupauls_drag_race)
  * [S04](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/rupauls_drag_race/s04): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-1353056/season-4
  * [S08](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/rupauls_drag_race/s08): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-1353056/season-8
  * [S09](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/rupauls_drag_race/s09): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-1353056/season-9
  * [S10](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/rupauls_drag_race/s10): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-1353056/season-10
  * [S11](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/rupauls_drag_race/s11): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-1353056/season-11
  * [S12](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/rupauls_drag_race/s12): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-1353056/season-12
  * [S13](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/rupauls_drag_race/s13): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-1353056/season-13
* [*RuPaul's Drag Race All Stars*](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/rupauls_drag_race_all_stars)
  * [S2](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/rupauls_drag_race_all_stars/s2): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-2301351/season-2
  * [S3](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/rupauls_drag_race_all_stars/s3): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-2301351/season-3
  * [S4](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/rupauls_drag_race_all_stars/s4): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-2301351/season-4
  * [S5](https://github.com/michen00/Springboard/tree/main/capstone_data/game_show_winnner_predict/rupauls_drag_race_all_stars/s5): https://www.opensubtitles.org/download/s/sublanguageid-eng/pimdbid-2301351/season-5

## Predict the stock price movement of Dow Jones tickers based on sentiment analysis of yesterday’s headlines
### Directory name
[headlines_sentiment_djia_predict](https://github.com/michen00/Springboard/tree/main/capstone_data/headlines_sentiment_djia_predict)
### Application
Many traders are interested in predicting how the price of a given company or industry index may fluctuate tomorrow. Short-term investors may wish to make trades in response to news headlines mentioning company names. This information could potentially be used alongside standard technical indicators to improve prediction accuracy.
### Data
A [financial news headlines dataset](https://www.kaggle.com/notlucasp/financial-news-headlines) and [stock prices for Dow companies](https://www.kaggle.com/bigt90/stock-prices-dow-jones-companies-and-djia-dynamics) are available on Kaggle; both include data between 2017 and 2020. Various other publicly accessible datasets of headlines may be useful as well. [Technical indicators for several Dow companies](https://www.kaggle.com/nikhilkohli/us-stock-market-data-60-extracted-features) covering the same period are on Kaggle too and missing data could ostensibly be [calculated](https://stock-prediction-dashboard.herokuapp.com/).
### Data gathered for project submission
* [djia](https://github.com/michen00/Springboard/tree/main/capstone_data/headlines_sentiment_djia_predict/djia)
  * A. bigt90, *Stock Prices Dow Jones Companies and DJIA Dynamics: Info about the Oldest US Stock Market Index - Dow Jones Industrial Average. V1.* Mar. 24, 2020. Distributed by Kaggle. Accessed Feb. 6, 2021. [Online]. Available: https://www.kaggle.com/bigt90/stock-prices-dow-jones-companies-and-djia-dynamics/version/1
* [financial_news_headlines](https://github.com/michen00/Springboard/tree/main/capstone_data/headlines_sentiment_djia_predict/financial_news_headlines)
  * L. Pham, *Financial News Headline Data: Headlines Related to U.S. Businesses from CNBC, the Guardian, and Reuters.* Jul. 18, 2020.  Distributed by Kaggle. Accessed Feb. 6, 2021. [Online]. https://www.kaggle.com/notlucasp/financial-news-headlines
* [us_technicals](https://github.com/michen00/Springboard/tree/main/capstone_data/headlines_sentiment_djia_predict/us_technicals)
  * N. Kohli, *US Stock Market Data & Technical Indicators: Stock Market Technical Indicators Data for Multiple US Companies for Forecasting. V1.* Aug. 16, 2020. Distributed by Kaggle. Accessed Feb. 6, 2021. [Online]. Available: https://www.kaggle.com/nikhilkohli/us-stock-market-data-60-extracted-features/version/1

## Generate high-sentiment form poetry with topical cohesion
### Directory name
[poetry_generation](https://github.com/michen00/Springboard/tree/main/capstone_data/poetry_generation)
### Application
This is primarily an artistic endeavor. Machine-generated music could be supplemented by machine-generated lyrics.
### Data
Previous efforts have used the [English Gigaword](https://catalog.ldc.upenn.edu/LDC2003T05) corpus, [song lyrics](https://www.kaggle.com/paultimothymooney/poetry), and [samples from Wikipedia](https://www.kaggle.com/mikeortman/wikipedia-sentences) as training corpora.
### Data gathered for project submission
* [song_lyrics](https://github.com/michen00/Springboard/tree/main/capstone_data/poetry_generation/song_lyrics)
  * P. Mooney, *Song Lyrics: Poetry and Lyrics (TXT Files). V16.* Aug. 18, 2018. Distributed by Kaggle. Accessed: Feb. 6, 2021. [Online]. Available: https://www.kaggle.com/paultimothymooney/poetry/version/16
* [wikisent2.txt](https://github.com/michen00/Springboard/tree/main/capstone_data/poetry_generation)
  * M. Ortman, *Wikipedia Sentences: Collection of 7.8 million Sentences from the August 2018 English Wikipedia Dump. V3.* Aug. 24, 2018. Distributed by Kaggle. Accessed: Feb. 6, 2021. [Online]. Available: https://www.kaggle.com/mikeortman/wikipedia-sentences/version/3
