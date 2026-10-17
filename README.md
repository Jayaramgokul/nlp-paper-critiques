# NLP paper critiques

**Six critiques of published NLP research, written for Cornell CS 4740/5740 (Natural Language Processing), autumn 2021, during my MPS in Applied Statistics.**

Each critique is a one-page reading of a research paper. Most of them ask the
same question in different settings: does the paper's data, method or
evaluation actually support its conclusion?

| # | Paper | The question my critique raises |
|---|---|---|
| 1 | Ott, Choi, Cardie & Hancock (2011). [Finding Deceptive Opinion Spam by Any Stretch of the Imagination](https://aclanthology.org/P11-1032/). *ACL*. | Can a deception detector stay ahead once spammers learn which cues it uses? One expected cue (less use of "I") already reversed in the study. Could the way the Turkers who wrote the fake reviews were selected create correlated features? |
| 2 | Bamman & Smith (2015). [Contextualized Sarcasm Detection on Twitter](https://doi.org/10.1609/icwsm.v9i1.14655). *ICWSM*. | Is what the model detects sarcasm, or its close neighbour irony? Why logistic regression over SVMs, and L2 over L1 regularisation, without the alternatives being tested? |
| 3 | Garg, Schiebinger, Jurafsky & Zou (2018). [Word embeddings quantify 100 years of gender and ethnic stereotypes](https://doi.org/10.1073/pnas.1720347115). *PNAS* 115(16). | Does a change in word associations over a century show social change, or words changing meaning ("nice", "awful")? Do context-dependent senses ("accounting for", "kind of") distort the bias measure? |
| 4 | Li, Jia, He & Liang (2018). [Delete, Retrieve, Generate: A Simple Approach to Sentiment and Style Transfer](https://aclanthology.org/N18-1169/). *NAACL*. | Frequency-based salience can pick the wrong attribute markers: sarcasm, idioms, adjectival nouns such as "the poor". Swapping them need not reverse the sentiment. Will the retrieved attributes fit grammatically outside the training corpus? |
| 5 | Mir, Felbo, Obradovich & Rahwan (2019). [Evaluating Style Transfer for Text](https://aclanthology.org/N19-1049/). *NAACL*. | Relative metrics are only as valid as the source sentences they are relative to. A style lexicon built by logistic regression may miss style words, or be misled by sarcasm, and so distort the content-preservation and naturalness scores. |
| 6 | Du & Cardie (2020). [Event Extraction by Answering (Almost) Natural Questions](https://aclanthology.org/2020.emnlp-main.49/). *EMNLP*. | The errors in the paper's own error analysis are not random. They point to gaps in training data and representations. The best results depend on annotation guidelines, which limits how far the method transfers. |

## The critiques

1. [Deceptive opinion spam](critiques/1-deceptive-opinion-spam.pdf)
2. [Sarcasm detection](critiques/2-sarcasm-detection.pdf)
3. [Word embeddings and stereotypes](critiques/3-word-embedding-stereotypes.pdf)
4. [Delete, Retrieve, Generate](critiques/4-delete-retrieve-generate.pdf)
5. [Evaluating style transfer](critiques/5-evaluating-style-transfer.pdf)
6. [Event extraction as question answering](critiques/6-event-extraction-as-qa.pdf)

These are the final versions of the critiques, one page each. The papers
themselves are linked above rather than reproduced here.
