# Expand, Highlight, Generate: RL-Driven Document Generation for Passage Reranking

This repository contains the official code for the EMNLP 2023 paper, "Expand, Highlight, Generate: RL-Driven Document Generation for Passage Reranking," which has been accepted at the main track of EMNLP 2023.

If you want to cite this dataset, please use the following bibtex references:

```bibtex

@inproceedings{askari-etal-2023-expand,
    title = "Expand, Highlight, Generate: {RL}-driven Document Generation for Passage Reranking",
    author = "Askari, Arian  and
      Aliannejadi, Mohammad  and
      Meng, Chuan  and
      Kanoulas, Evangelos  and
      Verberne, Suzan",
    editor = "Bouamor, Houda  and
      Pino, Juan  and
      Bali, Kalika",
    booktitle = "Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing",
    month = dec,
    year = "2023",
    address = "Singapore",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.emnlp-main.623",
    pages = "10087--10099",
}
```

## DocGen: (1) Expand, (2) Highlight, (3) Generate

Explore the capabilities of our DocGen pipeline by running [`EMNLP23-ChatGPT-RetrievalQA-Document-Generator-Demo.ipynb`](https://github.com/arian-askari/docgen/blob/main/src/EMNLP23_ChatGPT_RetrievalQA_Document_Generator_Demo.ipynb). This notebook provides an example of the DocGen pipeline, showcasing the following steps:
1. Expanding a query.
2. Highlighting its tokens.
3. Generating a synthetic document.

Furhtermore, we provide example of experimenting with different highlighting tokens such as "<>", "*", "()".

## Generated Data

Check out the generated data, including synthetic expanded queries, highlighted queries, and generated documents, by exploring the [`generated_data`](https://github.com/arian-askari/docgen/tree/main/generated_data) directory.

## DocGen-RL

We use [RL4LM](https://github.com/allenai/RL4LMs) for this aim and release the cleaned implementation soon.
