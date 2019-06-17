# Causal discovery using proxy variables

Dataset for [Causal discovery using proxy variables](https://arxiv.org/abs/1702.07306), by Mateo Rojas-Carulla, Marco Baroni, and David Lopez-Paz.

The dataset was collected and voted by multiple and different workers from Amazon Mechanical Turk. Each row of the dataset file `word_pairs.txt` is formatted as follows:
```
word_a word_b num_votes_causal num_votes_anticausal num_votes_unrelated
```

Here, `num_votes_causal` workers voted for the statement "`word_a` causes `word_b`", `num_votes_anticausal` voted for the statement "`word_b` causes `word_a`", and `num_votes_unrelated` voted for the statement "`word_a` is not causally related to `word_b`".

Repository released under a Attribution-NonCommercial 4.0 International license, find out more about it [here](LICENSE).
