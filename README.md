Use PyTorch to Build a Hidden Markov Model for both Weather Prediction and whether a person is Healthy or Feverish.

This is a practical project for learning Probabilistic Graphical Models (PGM). It implements the **Viterbi**, **Forward-Backward** and the **Baum Welch** algorithms.

## Hidden Markov Model (HMM)
A Markov chain is useful when we need to compute a probability for a sequence of observable events. In many cases, however, the events we are interested in are hidden: we don’t observe them directly. For example we don’t normally observe part-of-speech tags in a text. Rather, we see words, and must infer the tags from the word sequence.

In HMM the sequences are hidden because it is not possible to tell the state merely by the output symbol.
