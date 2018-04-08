# hindi2vec
State-of-the-Art Language Modeling and Text Classification in Hindi Language

## Results
- We achieved State of the Art Perplexity = 46.81 for Hindi compared to 40.68 for English (lower is better)
  - To the best of our knowledge on March 2, 2018 
- **[Pretrained Language Models](https://www.dropbox.com/s/4xef1wcaoon1wd4/hindi2vec-models.7z?dl=0)**

## Data
- [Hindi Wikipedia](https://dumps.wikimedia.org/hiwiki/latest/hiwiki-latest-pages-articles.xml.bz2) with about 21k unique tokens for minfreq = 50
- [Processed Data](https://www.dropbox.com/s/p8bx1k3rn0b964r/hindi-wiki-data.7z?dl=0)

### TODO
- [x] Language modeling based on wikipedia dump
- [x] Release Language Models: [Hindi Language Model](https://www.dropbox.com/s/4xef1wcaoon1wd4/hindi2vec-models.7z?dl=0)
- [ ] Create Text classification Datasets
- [ ] Benchmark text classification with FastText
- [ ] Fine-tuning model for text classification
- [ ] Add a leaderboard and allow submission, similar to SQuAD

#### Idea Dump
- [ ] Change the custom head to be used for transliteration instead of classification, Hindi script (Devnagri) to English script (Roman)
- [ ] MTL tasks for training and inference using custom heads
- [ ] Text to Speech - using datasets from news recordings or Hindi subtitles of dubbed movies

**Special thanks to Jeremy, Rachel and other contributors to [fastai](https://github.com/fastai/fastai)**. This work is a reproduction of their work in English to Hindi. Thanks to @cstorm125 for [thai2vec](https://github.com/cstorm125/thai2vec) which inspired this work.
