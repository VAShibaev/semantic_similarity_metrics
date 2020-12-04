# Style-transfer and Paraphrase: Looking for a Sensible Semantic Similarity Metric

Datsets used in AAAI's paper [Style-transfer and Paraphrase: Looking for a Sensible Semantic Similarity Metric](https://arxiv.org/abs/2004.05001) by Ivan Yamshchikov, Viacheslav Shibaev, Nikolay Khlebnikov, Alexey Tikhonov.


### Repo contains following datasets:

* [Yelp paraphrases](./Yelp/Yelp.csv) - contains paraphrases for [Yelp dataset](https://www.yelp.com/dataset)
* [Yelp random](./Yelp/Yelp_random.csv) - contains random pairs from [Yelp dataset](https://www.yelp.com/dataset)

* [Paraphrase](./Paraphrase/Paraphrase.csv) - contains paraphrases from [Paraphrase dataset](http://paraphrase.org)
* [Paraphrase random](./Paraphrase/Paraphrase_random.csv) - contains random pairs from [Paraphrase dataset](http://paraphrase.org)

* [Paralex paraphrases](./Paralex/Paralex.csv) - contains paraphrases from [Paralex dataset](http://knowitall.cs.washington.edu/paralex/)
* [Yelp random](./Paralex/Paralex_random.csv) - contains random pairs from [Paralex dataset](http://knowitall.cs.washington.edu/paralex/)

* [Bible paraphrases](./Bible/Bible.csv) - contains paraphrases from [Bible dataset](https://github.com/keithecarlson/StyleTransferBibleData)
* [Bible random](./Bible/Bible_random.csv) - contains random pairs from [Bible dataset](https://github.com/keithecarlson/StyleTransferBibleData)

* [GYAFC formal paraphrases](./GYAFC/GYAFC_formal.csv) - contains paraphrases from formal part of [GYAFC dataset](https://www.kaggle.com/quora/question-pairs-dataset)
* [GYAFC formal random](./GYAFC/GYAFC_formal_random.csv) - contains random pairs from formal part of [GYAFC dataset](https://www.kaggle.com/quora/question-pairs-dataset)
* [GYAFC informal paraphrases](./GYAFC/GYAFC_informal.csv) - contains paraphrases from informal part of [GYAFC dataset](https://www.kaggle.com/quora/question-pairs-dataset)
* [GYAFC informal random](./GYAFC/GYAFC_informal_random.csv) - contains random pairs from informal part of [GYAFC dataset](https://www.kaggle.com/quora/question-pairs-dataset)
* [GYAFC rewrites paraphrases](./GYAFC/GYAFC_rewrites.csv) - contains paraphrases from rewrites part of [GYAFC dataset](https://www.kaggle.com/quora/question-pairs-dataset)
* [GYAFC rewrites random](./GYAFC/GYAFC_rewrites_random.csv) - contains random pairs from rewrites part of [GYAFC dataset](https://www.kaggle.com/quora/question-pairs-dataset)

### All csv-files have following fields:
- text_1 - given text
- text_2 - random/real paraphrase of text_1
- label_1 - score of the first labeller
- label_2 - score of the second labeller
- label_3 - score of the third labeller
- avg_score - average labellers score

All scores are in the range from 1 to 5, where 1 - "Not Similar At All" and 5 - "Highly Similar"
