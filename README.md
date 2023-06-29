# Models and Practice of Neural Table Representations

In this repository, you can find more information and up to date material for the tutorial on Models and Practice of Neural Table Representations. This tutorial will be given on 23 June 2023 at SIGMOD 2023 in Seattle. More details will follow.

**Abstract**: In the last few years, the natural language processing community
witnessed advances in neural representations of free-form text with
transformer-based language models (LMs). Given the importance
of knowledge available in relational tables, recent research efforts
extend LMs by developing neural representations for tabular data.
In this tutorial, we present these proposals with three main goals.
First, we aim at introducing the potentials and limitations of current
models to a database audience. Second, we want the attendees
to see the benefit of such line of work in a large variety of data
applications. Third, we would like to empower the audience with a
new set of tools and to inspire them to tackle some of the important
directions for neural table representations, including model and
system design, evaluation, application and deployment. To achieve
these goals, the tutorial is organized in two parts. The first part
covers the background for neural table representations, including a
survey of the most important systems. The second part is designed
as a hands-on session, where attendees will use their laptop to
explore this new framework and test neural models involving text
and tabular data.


## Contents
- [Tutorial overview](#tutorial-overview)
- [Logistics](#logistics)
- [Material and sources](#code-and-sources)

---

## Tutorial overview
The tutorial will take 3 hours in total. The first part (1.5 hours)
covers the background for neural table representations.
The second part (1.5 hours) is designed as a hands-on session,
where attendees will use their laptop to explore this new framework and
test neural models involving text and tabular data.

In part 1:
- Motivation & background on Transformers and Language models.
- Survey of the key neural table models and applications.
- Overview of open challenges and future directions.

In part 2a:
- Input formats and preprocessing (serialization, tokenization, numeric)
- Understanding model architecture
- Using fine-tuned models to answer questions / verify statements

In part 2b:
- Understand self-supervised pre-training using raw tables without additional labels
- Understand different types of fine-tuning strategies for downstream tasks:
    - Token and sequence Classification: classification based on table, column, row or cell representations (e.g. column type prediction, fact verification)
    - Extractive QA: predict the start and end positions of the answer span (e.g. table QA)

---

## Logistics

Location: Seattle (at SIGMOD 2023).

Time: 1:30-5:00, 23 June.

Presenters: Madelon Hulsebos, Xiang Deng, Huan Sun, and Paolo Papotti.

---

## Material:

- Slides part 1 (by Paolo Papotti): [Tutorial slides download](assets/TutorialSIGMOD23.pdf)

- Google Colab Notebook for part 2a (by Madelon Hulsebos): [https://colab.research.google.com/drive/1trjqxE6YGvFcERyimITkZD98TRGbCWx1?usp=sharing](https://colab.research.google.com/drive/1trjqxE6YGvFcERyimITkZD98TRGbCWx1?usp=sharing)
- Google Colab Notebook for part 2b (by Xiang Deng): [https://colab.research.google.com/drive/1WTg-YnfNVX4M0P0m1mEJYDQVkWr4HKXl](https://colab.research.google.com/drive/1WTg-YnfNVX4M0P0m1mEJYDQVkWr4HKXl)

---

## Citation:

```
@inproceedings{hulsebos2023models,
  title={Models and Practice of Neural Table Representations},
  author={Hulsebos, Madelon and Deng, Xiang and Sun, Huan and Papotti, Paolo},
  booktitle={Companion of the 2023 International Conference on Management of Data},
  pages={83--89},
  year={2023}
}
