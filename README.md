# AI Ghostwriter

LSTM machine learning model created for UCSB's Data Science Project Series.

This project takes a song's audio features as input tensors and returns lyrics based on the training data subject's music style. We used the rapper Drake as a proof of concept, but the model should work for any artist of choosing.

Audio features were acquired using Spotify's API, LibRosa, and wav2vec. Lyric data was scraped off the Genius website using the BeautifulSoup library.