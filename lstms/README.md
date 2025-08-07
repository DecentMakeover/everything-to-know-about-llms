## LSTMs and RNNs — Essential Papers

Sequence modeling before transformers and where it still matters.

### Core RNNs
- **LSTM (1997)** — Hochreiter & Schmidhuber [Paper](https://www.bioinf.jku.at/publications/older/2604.pdf)
- **GRU (2014)** — Cho et al. [Paper](https://arxiv.org/abs/1406.1078)
- **Bidirectional RNNs (1997/2000)** — Schuster & Paliwal [Paper](https://ieeexplore.ieee.org/document/650093)

### Sequence-to-sequence and attention
- **Seq2Seq (2014)** — Sutskever et al. [Paper](https://arxiv.org/abs/1409.3215)
- **Neural Machine Translation by Jointly Learning to Align and Translate (2015)** — Bahdanau et al. [Paper](https://arxiv.org/abs/1409.0473)
- **Pointer Networks (2015)** — Vinyals et al. [Paper](https://arxiv.org/abs/1506.03134)

### Training/decoding
- **CTC Loss (2006)** — Graves et al. [Paper](https://www.cs.toronto.edu/~graves/icml_2006.pdf)
- **Scheduled Sampling (2015)** — Bengio et al. [Paper](https://arxiv.org/abs/1506.03099)

### Contextual embeddings built on LSTMs
- **ELMo (2018)** — Peters et al. [Paper](https://arxiv.org/abs/1802.05365)

Suggested path: LSTM → GRU → Seq2Seq → Bahdanau Attention → CTC/Pointer Networks.


