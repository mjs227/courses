# Graph Deep Learning for NLP

## Description

Complex pairwise relationships&mdash;which are ubiquitous in NLP&mdash;are best encoded as graph-structured data: social media networks, relations between entities, and syntactic/semantic parses (to name just a few) are all naturally expressed as graphs. However, constructing effective structural priors for neural models over graphs is considerably more difficult than for "traditional" machine learning media such as text and image data&mdash;this is to say that graph data requires highly specialized model architectures. In this seminar, we will delve into active research at the intersection of NLP and graph deep learning, with a particular focus on incorporating graph representations into language models, in order to enable them to engage with graph-structured data such as knowledge graphs and dependency parses.

## Prerequisites

This course assumes a solid background in NLP/ML and current language models: you should be familiar with transformer architectures and common methods/terminology in NLP.

You should also (at least) know what a graph is. If you don't, just read the Wikipedia page, and you should be fine: [https://en.wikipedia.org/wiki/Graph_(discrete_mathematics)](https://en.wikipedia.org/wiki/Graph_(discrete_mathematics))

You do not, however, need any background in graph deep learning: we will discuss current methodologies for modeling graph-stuctured data (i.e. graph neural networks) in class.

## Information

**Instructor:** [Michael Sullivan](https://www.acsu.buffalo.edu/~mjs227/)
- mjs227@buffalo.edu (I check this one more often)
- or msullivan@lst.uni-saarland.de

**Time/Location:** Thu 16:15 - 17:45; Building C7.2, Room 1.05

**Office Hours:** TBD

## Format/Requirements

Each week, we will meet to discuss the assigned reading (see *Schedule/Reading List* below). All students are expected to ask questions and actively engage in the discussion.

### Discussion Leader

At the beginning of the semester, each student will choose a reading for which they will lead the discussion ("Discussion Leader"): if you do not reach out to me to chose a reading, I will randomly assign you a paper. The Discussion Leader will:

- **Summarize**: Discuss the authors' approach/methods, main findings, and any relevant background on the topic
- **Critically analyze**: What is your opinion of the methods/findings of the paper? What should (or shouldn't) have been included?
- **Field questions**: While you are *not* expected to cover every minute detail of the reading in your summary/analysis, you *should* know the paper well enough to be able to answer any questions your classmates might have (within reason, of course!).

While you are not necessarily expected to create slides as Discussion Leader, sometimes visuals can help! Feel free to use a slide deck, if you would like.

The course is divided into topics/themes: if there is another paper that you would like to discuss instead of the assigned reading (that you feel falls under the same topic), come see me during office hours a few weeks before the assigned date. I will update the schedule if I find your paper appropriate for the course and topic. 

## Evaluation

For students taking the course for 4 credits:
```
Participation in class discussions: 50%
Discussion Leader: 50%
```

For students taking the course for 7 credits:
```
Participation in class discussions: 30%
Discussion Leader: 30%
Term paper: 40%
```

## Schedule/Reading List

| Topic | Date | Reading | Background Reading (Optional) | Discussion Leader |
| :--- | :--- | :--- | :--- | :--- |
| $${\color{cyan}\text{Introduction}}$$ | Oct. 17 | None (logistics and scheduling) | - | Michael |
| $${\color{cyan}\text{Introduction}}$$ | Oct. 24 | [Machine Learning on Graphs: A Model and Comprehensive Taxonomy](https://www.jmlr.org/papers/v23/20-852.html) | - | Michael |
| $${\color{violet}\text{Machine Translation}}$$ | Oct. 31 | [Document Graph for Neural Machine Translation](https://aclanthology.org/2021.emnlp-main.663) | [Semi-Supervised Classification with Graph Convolutional Networks](https://openreview.net/forum?id=SJU4ayYgl) | TBD |
| $${\color{violet}\text{Machine Translation}}$$ | Nov. 7 | [A Novel Graph-based Multi-modal Fusion Encoder for Neural Machine Translation](https://aclanthology.org/2020.acl-main.273) | - | TBD |
| $${\color{orange}\text{KG Incorporation}}$$ | Nov. 14 | [GreaseLM: Graph REASoning Enhanced Language Models](https://openreview.net/forum?id=41e9o6cQPj) | [Graph Attention Networks](https://openreview.net/forum?id=rJXMpikCZ) | TBD |
| $${\color{orange}\text{KG Incorporation}}$$ | Nov. 21 | [Deep Bidirectional Language-Knowledge Graph Pretraining](https://proceedings.neurips.cc/paper_files/paper/2022/file/f224f056694bcfe465c5d84579785761-Paper-Conference.pdf) | - | TBD |
| $${\color{orange}\text{KG Incorporation}}$$ | Nov. 28 | [Enhancing Dialogue Generation via Dynamic Graph Knowledge Aggregation](https://aclanthology.org/2023.acl-long.253/) | [Weisfeiler and Leman Go Neural: Higher-Order Graph Neural Networks](https://ojs.aaai.org/index.php/AAAI/article/view/4384) | TBD |
| $${\color{orange}\text{KG Incorporation}}$$ | Dec. 5 | [Mitigating Large Language Model Hallucinations via Autonomous Knowledge Graph-Based Retrofitting](https://ojs.aaai.org/index.php/AAAI/article/view/29770) | - | TBD |
| $${\color{lime}\text{Relation Extraction}}$$ | Dec. 12 | [Dialogue Relation Extraction with Document‑Level Heterogeneous Graph Attention Networks](https://link.springer.com/article/10.1007/s12559-023-10110-1) | - | TBD |
| $${\color{lime}\text{Relation Extraction}}$$ | Dec. 19 | [A Graph Convolutional Network With Multiple Dependency Representations for Relation Extraction](https://ieeexplore.ieee.org/abstract/document/9446853) | - | TBD |
| $${\color{red}\text{Structured-Data-to-Text}}$$ | Jan. 2 | [AMR-To-Text Generation with Graph Transformer](https://aclanthology.org/2020.tacl-1.2/) | - | TBD |
| $${\color{red}\text{Structured-Data-to-Text}}$$ | Jan. 9 | [Improving Encoder by Auxiliary Supervision Tasks for Table-to-Text Generation](https://aclanthology.org/2021.acl-long.466.pdf) | - | TBD |
| $${\color{yellow}\text{KG Construction}}$$ | Jan. 16 | [Grapher: Multi-Stage Knowledge Graph Construction using Pretrained Language Models](https://openreview.net/forum?id=N2CFXG8-pRd) | - | TBD |
| $${\color{yellow}\text{KG Construction}}$$ | Jan. 23 | [Commonsense Knowledge Base Completion with Structural and Semantic Context](https://ojs.aaai.org/index.php/AAAI/article/view/5684) | - | TBD |
| $${\color{magenta}\text{Syntactic/Semantic Parsing}}$$ | Jan. 30 | [Towards Collaborative Neural-Symbolic Graph Semantic Parsing via Uncertainty](https://aclanthology.org/2022.findings-acl.328) | - | TBD |

## Term Papers
TBD