# HCDE 410 A2

This assignment explored the Wikipedia Talk corpus, looking for potential bias among who
annotated the comments.

The corpus data files, with original source, are:
* [Toxicity dataset](https://figshare.com/articles/dataset/Wikipedia_Talk_Labels_Toxicity/4563973) for toxicity_annotations.tsv, toxicity_worker_annotations.tsv, and toxicity_worker_demographics.tsv
* [Aggression dataset](https://figshare.com/articles/dataset/Wikipedia_Talk_Labels_Aggression/4267550) for aggression_worker_demographics.tsv
* [Personal attacks dataset](https://figshare.com/articles/dataset/Wikipedia_Talk_Labels_Personal_Attacks/4054689) for attack_worker_demographics.tsv

All of the above data sets are available under CC0 public domain. Attribution:

Wulczyn, Ellery; Thain, Nithum; Dixon, Lucas (2016): Wikipedia Detox. figshare. https://doi.org/10.6084/m9.figshare.4054689 Retrieved: 4/17/21.

For more information see [Wikipedia Detox](https://meta.wikimedia.org/wiki/Research:Detox).
This data has been used to train the
[Perspective API](https://github.com/conversationai/perspectiveapi) and here the corpus
was evaluated to assess its suitability for this purpose.

## hcde410-a2.ipynb

This notebook performs all of the data analysis. Worker demographics are assembled from the
three separate datasets, summary statistics are presented, and conclusions reached.
