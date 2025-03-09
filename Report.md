
---

### `Report.md`
```md
# AI for Safer Online Spaces for Women - Performance Report

## Introduction
This report outlines the evaluation metrics and performance results of the two models developed for the **Hackathon Challenge: AI for Safer Online Spaces for Women**.

## 1. Parent-Child Conversation Reconstruction
### Metrics Used
- **BLEU Score**: Measures the similarity between reconstructed and original conversations.
- **ROUGE Score**: Evaluates summarization quality by comparing generated summaries with reference summaries.
- **Perplexity**: Assesses the fluency of generated text.
- **Semantic Similarity**: Measures the contextual closeness between the generated and reference text.

### Results
| Metric              | Score  |
|---------------------|--------|
| BLEU Score         | 0.0896 |
| ROUGE-1            | 0.1318 |
| ROUGE-2            | 0.1032 |
| ROUGE-L            | 0.1233 |
| Perplexity         | N/A    |
| Semantic Similarity| 0.3218 |

---

## 2. Subreddit-Based Topic Classification
### Metrics Used
- **Accuracy**: Measures the percentage of correctly classified subreddit topics.
- **Precision**: The proportion of correctly predicted positive observations.
- **Recall**: The ability of the classifier to find all the positive samples.
- **F1-Score**: The harmonic mean of precision and recall.

### Results
| Subreddit           | Precision | Recall | F1-Score | Support |
|---------------------|-----------|--------|----------|---------|
| KotakuInAction     | 1.00      | 1.00   | 1.00     | 1       |
| MGTOW             | 0.33      | 1.00   | 0.50     | 1       |
| PussyPass         | 0.00      | 0.00   | 0.00     | 1       |
| Trufemcels        | 0.00      | 0.00   | 0.00     | 1       |
| badwomensanatomy  | 1.00      | 1.00   | 1.00     | 1       |
| **Overall Accuracy** | **60%** |        |          | 5       |

- **Topic Coherence Score**: **0.3932**

---

## Conclusion
- The **Parent-Child Conversation Reconstruction** model shows promising results in conversation summarization, though further fine-tuning could improve BLEU and ROUGE scores.
- The **Subreddit-Based Topic Classification** model achieved **60% accuracy** on a small dataset. A larger dataset and better feature engineering may improve classification performance.
- Future improvements could include **fine-tuning models on diverse datasets**, **enhancing context-awareness in text generation**, and **improving classification robustness**.

## References
- Research Papers on NLP
- Official Transformer Model Documentation
