# JHU JSALT Summer School IR Laboratory

This repository contains notebooks modified from 

- [CIKM 2021 Tutorial -- **IR From Bag-of-words to BERT and Beyond through Practical Experiments**](https://github.com/terrier-org/cikm2021tutorial) and
- [SIGIR 2023 Tutorial -- **Neural Methods for CLIR Tutorial**](https://github.com/hltcoe/clir-tutorial). 

Please refer to the repository of the two tutorials for more details. 

## Agenda

- Part 1: Statistical Retrieval Model with PyTerrier [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eugene-yang/ir-tutorial-notebooks/blob/main/1_pyterrier_basics.ipynb)
- Part 2: Retrieval Pipeline with PyTerrier [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eugene-yang/ir-tutorial-notebooks/blob/main/2_more_pyterrier.ipynb)
	- Part 2 Extra: More piplines using neural models [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eugene-yang/ir-tutorial-notebooks/blob/main/2.e_pyterrier_w_neural.ipynb)
- Part 2.5: CLIR BM25 with Anserini [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eugene-yang/ir-tutorial-notebooks/blob/main/2.5_anserini_bm25.ipynb)
- Part 3: Reranking using Cross-Encoder [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eugene-yang/ir-tutorial-notebooks/blob/main/3_cross_encoder_reranking.ipynb)
- Part 4: CLIR with PLAID-X [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eugene-yang/ir-tutorial-notebooks/blob/main/4_plaid-x.ipynb)
- Part 5: CLIR with BLADE [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eugene-yang/ir-tutorial-notebooks/blob/main/5_blade.ipynb)

## Citation
If you would like to cite the two tutorials, please use the following Bibtex.
```bibtex
@inproceedings{cikm2021-tut-bow2b,
  author = {MacAvaney, Sean and Macdonald, Craig and Tonellotto, Nicola},
  title = {IR From Bag-of-words to BERT and Beyond through Practical Experiments: A CIKM 2021 tutorial with PyTerrier and OpenNIR},
  booktitle = {Proceedings of CIKM 2021},
  year = {2021}
}
```

```bibtex
@inproceedings{sigir2023-clir-tutorial,
	author = {Eugene Yang and Dawn Lawrie and James Mayfield and Suraj Nair and Douglas W. Oard},
	title = {Neural Methods for Cross-Language Information Retrieval},
	booktitle = {Proceedings of the 46th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR) (Tutorial)},
	year = {2023},
}
```