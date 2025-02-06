# SentEmoContext: Context-Aware Metric Learning for Efficient Emotion Recognition in Conversation
Poster for the paper _SentEmoContext: Context-Aware Metric Learning for Efficient Emotion Recognition in Conversation_ accepted at WASSA@ACL 2024.  

The code for this paper is available at [this GitHub repository](https://github.com/B-Gendron/sentEmoContext/tree/main).

## Cite the paper

```
@inproceedings{gendron-guibon-2024-wassa,
    title = "{SEC}: Context-Aware Metric Learning for Efficient Emotion Recognition in Conversation",
    author = {Gendron, Barbara  and
      Guibon, Ga{\"e}l},
    editor = "De Clercq, Orph{\'e}e  and
      Barriere, Valentin  and
      Barnes, Jeremy  and
      Klinger, Roman  and
      Sedoc, Jo{\~a}o  and
      Tafreshi, Shabnam",
    booktitle = "Proceedings of the 14th Workshop on Computational Approaches to Subjectivity, Sentiment, {\&} Social Media Analysis",
    month = aug,
    year = "2024",
    address = "Bangkok, Thailand",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.wassa-1.2/",
    doi = "10.18653/v1/2024.wassa-1.2",
    pages = "11--22",
    abstract = "The advent of deep learning models has made a considerable contribution to the achievement of Emotion Recognition in Conversation (ERC). However, this task still remains an important challenge due to the plurality and subjectivity of human emotions. Previous work on ERC provides predictive models using mostly graph-based conversation representations. In this work, we propose a way to model the conversational context that we incorporate into a metric learning training strategy, with a two-step process. This allows us to perform ERC in a flexible classification scenario and end up with a lightweight yet efficient model. Using metric learning through a Siamese Network architecture, we achieve 57.71 in macro F1 score for emotion classification in conversation on DailyDialog dataset, which outperforms the related work. This state-of-the-art result is promising in terms of the use of metric learning for emotion recognition, yet perfectible compared to the micro F1 score obtained."
}
```
