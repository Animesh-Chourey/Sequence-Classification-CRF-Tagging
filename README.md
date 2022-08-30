## CRF Sequence Tagging

The NER Tagger has been trained and tested for the movie queries. The Named Entity Recognition (NER) tagger has been improved by using a pre-trained POS tagger.

The following tasks have been performed:
* Splitting the training data into 80% training the CRF and 20% development set .
* Error analysis on the false positives.
* Error analysis on the false negatives.
* Incorporating POS tags as features i.e. adding these POS tags to the words in the training data.
* Experimenting with different features to get the optimal macro average (i.e. average f-score across all classes) on the 20% dev data.