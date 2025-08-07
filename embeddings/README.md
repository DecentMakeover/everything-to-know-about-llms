## Embeddings and Tokenization — Essential Papers

Static and contextual representations, plus subword tokenization methods that power modern NLP.

### Static word embeddings
- **word2vec (2013)** — Mikolov et al. [Paper](https://arxiv.org/abs/1301.3781)
- **GloVe (2014)** — Pennington et al. [Paper](https://nlp.stanford.edu/pubs/glove.pdf)
- **fastText (2017)** — Bojanowski et al. [Paper](https://arxiv.org/abs/1607.04606)

### Subword tokenization
- **Byte-Pair Encoding (BPE) for NMT (2016)** — Sennrich et al. [Paper](https://arxiv.org/abs/1508.07909)
- **SentencePiece (2018)** — Kudo & Richardson [Paper](https://arxiv.org/abs/1808.06226)
- See also: WordPiece (BERT, 2018)

### Contextual embeddings (pre-transformer)
- **ELMo (2018)** — Peters et al. [Paper](https://arxiv.org/abs/1802.05365)
- **ULMFiT (2018)** — Howard & Ruder [Paper](https://arxiv.org/abs/1801.06146)

Suggested path: word2vec → GloVe → fastText → BPE → SentencePiece → ELMo → ULMFiT.


