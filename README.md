# hindi2vec
State-of-the-Art Language Modeling and Text Classification in Hindi Language

## Results
- We achieved State of the Art Perplexity = 46.81 for Hindi compared to 40.68 for English (lower is better)
  - To the best of our knowledge on March 2, 2018 
- [Models and Word Embeddings](https://www.dropbox.com/s/4xef1wcaoon1wd4/hindi2vec-models.7z?dl=0)

## Data
- [Hindi Wikipedia](https://dumps.wikimedia.org/hiwiki/latest/hiwiki-latest-pages-articles.xml.bz2) with about 21k unique tokens for minfreq = 50
- [Processed Data](https://www.dropbox.com/s/p8bx1k3rn0b964r/hindi-wiki-data.7z?dl=0)

### TODO
#### Phase 1
- [x] Language modeling based on wikipedia dump
- [ ] Extract embeddings - convert to word2vec gensim format and release here
- [ ] Figure out a word embedding evaluation task for Hindi

#### Phase 2
- [ ] Benchmark text classification with FastText
- [ ] Fine-tuning model for text classification
- [ ] Add a leaderboard and allow submission, similar to SQuAD

**Special thanks to Jeremy, Rachel and other contributors to [fastai](https://github.com/fastai/fastai)**. This work is a reproduction of their work in English to Hindi. Thanks to @cstorm125 for [thai2vec](https://github.com/cstorm125/thai2vec) which inspired this work.
