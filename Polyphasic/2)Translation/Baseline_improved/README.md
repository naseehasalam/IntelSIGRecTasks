# Improved Baseline seq2seq Machine Translation model

The baseline has been optimised by the following:
- A WordPiece tokeniser for both the languages.
- Two Bidirectional GRU layers.
- SELU activation in contrast to RELU for the Dense Layers.
- A Dropout of 0.5.

This model can be made even better by the following:
These are yet to be implemented:-
- [ ] Training the tokenizers with a bigger text corpus.
- [ ] Seperating the Encoder-Decoder architecture by adding an `encoder` and `decoder` class , so as to better understand the data flow.
- [ ] Adding an Attention Layer (an `additive_attention` class.)
- many more :)