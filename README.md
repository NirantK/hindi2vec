# hindi2vec
State-of-the-Art Language Modeling and Text Classification in Hindi Language
---

![](/assets/images/logo.png)


## Results
We achieved State of the Art Perplexity = 46.81 for Hindi compared to 40.68 for English (lower is better)
  - To the best of my knowledge on September 18, 2018

## Downloads
- [**Pretrained Language Models**](https://www.dropbox.com/s/4xef1wcaoon1wd4/hindi2vec-models.7z?dl=0) that you can use in your classification for transfer learning
- EXCLUSIVE: [*BBC Hindi*](https://github.com/NirantK/hindi2vec/releases/download/bbc-hindi-v0.1/bbc-hindiv01.tar.gz) data of 4335 documents for text classification and text summarization. [Release Notes](https://github.com/NirantK/hindi2vec/releases/tag/bbc-hindi-v0.1)
- Raw Data for Language Model shared above: [Hindi Wikipedia](https://dumps.wikimedia.org/hiwiki/latest/hiwiki-latest-pages-articles.xml.bz2) with about 21k unique tokens for minfreq = 50
    - [Wikipedia Processed Data](https://www.dropbox.com/s/p8bx1k3rn0b964r/hindi-wiki-data.7z?dl=0) - please use this to train your model


### TODO
- [x] Language modeling based on wikipedia dump
- [x] Release Language Models: [Hindi Language Model](https://www.dropbox.com/s/4xef1wcaoon1wd4/hindi2vec-models.7z?dl=0)
- [x] Create Text classification Datasets:  [BBC Hindi](https://github.com/NirantK/hindi2vec/releases/download/bbc-hindi-v0.1/bbc-hindiv01.tar.gz)
- [ ] Benchmark text classification with FastText

#### Idea Dump
- [ ] Change the custom head to be used for transliteration instead of classification, Hindi script (Devnagri) to English script (Roman)
- [ ] MTL tasks for training and inference using custom heads
- [ ] Text to Speech - using datasets from news recordings or Hindi subtitles of dubbed movies

#### FastAI Installation

This version of the notebook uses fastai lib's v0.7, used in their Part 2 v2 course in Summer 2018. The best way to [install it via conda as mentioned here](http://forums.fast.ai/t/fastai-v0-7-install-issues-thread/24652)

**Special thanks to Jeremy, Rachel and other contributors to [fastai](https://github.com/fastai/fastai)**. This work is a reproduction of their work in English to Hindi. Thanks to @cstorm125 for [thai2vec](https://github.com/cstorm125/thai2vec) which inspired this work.

