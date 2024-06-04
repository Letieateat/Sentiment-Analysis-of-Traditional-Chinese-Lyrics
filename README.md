<h1 align="center">Welcome to Sentiment-Analysis-on-Traditional-Chinese-Lyrics 👋</h1>
<p>
  <a href="https://opensource.org/license/mit" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
</p>

> The present study investigates the sentiment analysis of Traditional Chinese lyrics. We created a dataset containing 1,002 mandopop lyrics labeled with seven sentiments, conducting three sentiment analysis tasks in three models: BERT-based-Chinese model, CKIP BERT-based-Chinese model, and GPT 3.5. The prompt-based approach with a hand-crafted prompt was applied to the GPT model. According to the results, the CKIP model outperformed the other models on all sentiment analysis tasks. In addition, a bigger batch size may enhance the performance of models for binary tasks, but a smaller size could be better for delicate tasks.
Furthermore, sadness and anxiety could be the two challenging sentiments for models regarding classification. Moreover, GPT-3.5 could potentially distinguish delicate sentiments better as it only failed on specific sentiments based on the confusion matrices. Applying different prompting methods may be a way to enhance the GPT model’s performance, which is worth future research.



## Project Dependencies
First, make sure you have Python 3.10.12 installed. You can download it from the [Python website](https://www.python.org/downloads/) or install it via a package manager like [Anaconda](https://www.anaconda.com/products/distribution).
To run the code in this project, you'll need to install several Python libraries. 

### Installation Instructions

- `Python 3.10.12` or higher
- `Spotipy`: Library for interacting with the Spotify API.
- `Pymusixmatch`: Library for interacting with the Musixmatch API.
- `Ckip-transformers`: Library for tokenization in Traditional Chinese.
- `TCSP`: Library for Traditional Chinese text processing, providing stopwords list.
- `Pandas`: Library for data manipulation and analysis.
- `Transformers`: Library for state-of-the-art NLP models.
- `TensorFlow`: Library for deep learning models.
- `Matplotlib`: Library for creating static, animated, and interactive visualizations.
- `Seaborn`: Library for statistical data visualization.
- `Scikit-learn`: Library for machine learning tasks.
- `Torch`: Library for deep learning models.
- `OpenAI`: Library for interacting with the OpenAI API.


Once Python is installed, you can install the other dependencies using pip.

```bash
pip install spotipy
pip install pymusixmatch
pip install -U ckip-transformers
pip install TCSP
pip install pandas
pip install transformers==4.31.0
pip install tensorflow
pip install matplotlib
pip install seaborn
pip install scikit-learn
pip install torch
pip install --upgrade openai
```

## Get your necessary API keys

To use Spotipy and Musixmatch, you'll need to obtain your own API keys. Refer to the tutorials on Genius and Spotify for more information:

- `Musixmatch API`: https://developer.musixmatch.com/
- `Spotify API`: https://developer.spotify.com/documentation/web-api

## Author

👤 **Ling Yan Li**

* Github: [@Leticiaeat](https://github.com/Leticiaeat)
  
## 📝 License

Copyright © 2024 <br />
This project is [MIT](https://opensource.org/license/mit) licensed.
