# Irancell Labs AI Hackathon 2023 - Final Round Solutions

Welcome to the repository for our solutions to the final round of the **Irancell Labs Artificial Intelligence Hackathon 2023**! Our team, consisting of Alireza Mirrokni and myself, participated in this challenging competition and tackled the problems presented with great effort and dedication.

Due to the Contest Code of Conduct, we are unable to share the datasets publicly. However, we provide detailed explanations of the problems and our solutions to give you insights into our approach. Enjoy exploring!

## Contents

- [Problems](#problems)
  - [Problem 1](#problem-1)
  - [Problem 2](#problem-2)
- [Repository Structure](#repository-structure)

## Problems

The contest featured two main problems judged by an automated system. Here, we describe each problem and outline our solutions.

### Problem 1

**Overview:**

**Data Structure Example:**
```
├── 2023-0-27 
│ ├── isna 
│ │ ├── 0.html
│ │ └── 1.html
│ └── afkarnews
│ │ ├── 0.html
│ │ └── 1.html
└── 2023-07-28
│ ├── borna
│ │ ├── 0.html
│ │ └── 1.html
│ ├── digiato
│ │ ├── 0.html
│ │ └── 1.html
```

The dataset provided consists of news articles collected over several days from various newspapers and blogs. The data is organized into folders named by date, and within each date folder, there are subfolders for each news source. Each news source folder contains HTML files representing individual news articles. Given this dataset, we were tasked with the following queries:

**Queries:**

1. **Unique News Sources:** How many unique news sources are in the dataset?
2. **Most News Record:** Which news source has the most news record in the dataset.
3. **Word Count in `varzesh3`:** For all HTML files related to `varzesh3`, count the occurrences of the words `کشتی`, `والیبال`, and `فوتبال` in `p` tags.
4. **Most Repeated Word in `h2` Tags:** Find the most repeated word in `h2` tags among all news collected on 2023-08-01, excluding provided stopwords.

### Problem 2

**Overview:**

The task is to build a model predicting the topic of news items. Each row in the dataset corresponds to a news item, with the topic in the `tags` column. 

**Topics and Labels:**

- Social (Label: 0)
- Economic (Label: 1)
- Iran Provinces (Label: 2)
- International (Label: 3)
- Political (Label: 4)
- Scientific/Cultural/Sports (Label: 5)

**Objectives:**

- Modify the `tags` column to fit one of the six main categories.
- Tag each news item with one main category.
- Evaluate the model using the F1 Score.

**Our Model:**

We achieved an accuracy of approximately 8% with our predictive model.

## Repository Structure

- `problems/`: Contains PDF files detailing the problems.
- `/q1.ipynb`: Code and explanations for our solution to the first problem.
- `/q2.ipynb`: Code and explanations for our solution to the second problem.

**Note:** Due to contest rules, the datasets used in this hackathon cannot be shared publicly. Please refer to the explanations provided for a comprehensive understanding of our approach.
