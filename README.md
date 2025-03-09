# AI for Safer Online Spaces for Women

## Overview
This project was developed as part of the **Hackathon Challenge: AI for Safer Online Spaces for Women**, aimed at fostering safer and more inclusive online conversations. It leverages AI and NLP to detect and classify toxic discourse while ensuring context-awareness. The models implemented focus on:

1. **Parent-Child Conversation Reconstruction** – Rebuilding threaded discussions from fragmented conversations.
2. **Subreddit-Based Topic Classification** – Categorizing discussions based on topics within different subreddits.

## Models Implemented
### 1. Parent-Child Conversation Reconstruction
- **Objective**: Identify conversation flow, detect missing/misleading context, and summarize key points while preserving intent.
- **Approach**:
  - Used NLP-based discourse analysis.
  - Implemented transformers to reconstruct missing conversational threads.
  - Developed a summarization model to extract discussion highlights.

### 2. Subreddit-Based Topic Classification
- **Objective**: Categorize discussions into subreddit topics and analyze trends.
- **Approach**:
  - Trained a classifier using NLP techniques.
  - Implemented topic modeling for trend analysis.
  - Developed an interactive visualization of topic evolution.

## Installation and Setup
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Required Python packages (listed in respective notebooks)

### Setup
1. Clone the repository:

   git clone <repo_link>.git
   cd <repo_name>

Run Jupyter Notebook:

jupyter notebook


Open and run the notebooks:

#### Que1_1.ipynb for Parent-Child Conversation Reconstruction

#### que2.ipynb for Subreddit-Based Topic Classification


### Usage

To run the models, execute the respective notebooks. The outputs will include:

Reconstructed conversation threads for discourse analysis.

Classified subreddit topics along with visualization.

### Contributors

Revanth Reddy Avuthu

Yaswanthini Kotapuri


License

This project is licensed under MIT License.
