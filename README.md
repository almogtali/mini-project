# Answer Evaluation and Result Analysis

This repository contains two Jupyter notebooks for evaluating model-generated answers and analyzing their performance. It is intended for use in NLP model development and assessment tasks such as QA or LLM output validation.

## Contents

### 1. `answers_evaluation.ipynb`

This notebook:
- Loads answer data and reference answers.
- Computes evaluation metrics such as:
  - BLEU
  - ROUGE
  - METEOR
  - BERTScore
- Supports custom similarity thresholds and normalization.
- Outputs a summary table of metric scores per sample and overall averages.

#### Key Features:
- Modular structure for pluggable metrics.
- Tokenizer-based evaluation and semantic similarity scoring.
- Optional answer cleaning and formatting for better comparison.

---

### 2. `resultsAnalysis.ipynb`

This notebook:
- Loads the evaluation results from the `answers_evaluation` step.
- Performs statistical and visual analysis of performance metrics.
- Includes:
  - Histograms of metric distributions.
  - Metric comparison across different models or configurations.
  - Correlation analysis between metrics.
  - Identification of outliers or underperforming samples.

#### Key Features:
- Useful for visual insights into model evaluation.
- Can be adapted to run comparative evaluations between different model outputs.
- Designed to scale to multiple evaluation runs.

---

## Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
"# mini-project" 
