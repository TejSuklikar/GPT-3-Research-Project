<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">

# Is GPT-3 Smarter Than a Sixth-Grader?

<em>Evaluating GPT-3’s Performance on Educational Question Answering</em>

<!-- BADGES -->
<img src="https://img.shields.io/github/last-commit/TejSuklikar/GPT-3-Research-Project?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
<img src="https://img.shields.io/github/languages/top/TejSuklikar/GPT-3-Research-Project?style=flat&color=0080ff" alt="repo-top-language">
<img src="https://img.shields.io/github/languages/count/TejSuklikar/GPT-3-Research-Project?style=flat&color=0080ff" alt="repo-language-count">

<em>Built with the tools and technologies:</em>

<img src="https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/OpenAI-412991.svg?style=flat&logo=openai&logoColor=white" alt="OpenAI">
<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style=flat&logo=Jupyter&logoColor=white" alt="Jupyter Notebook">

</div>
<br>

---

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Usage](#usage)
    - [Testing](#testing)
- [Results Summary](#results-summary)

---

## Overview

**Is GPT-3 Smarter Than a Sixth-Grader?** is a research project that evaluates the GPT-3 Davinci model's ability to answer middle school science questions using the TQA (Textbook Question Answering) dataset. The study tests GPT-3's performance across three modes: **zero-shot**, **few-shot**, and **fine-tuned** setups, aiming to understand the model’s reasoning skills and contextual learning capabilities.

### Key Features

- 🧠 **GPT-3 Model Evaluation:** Compares Davinci's behavior across different prompting strategies.
- 🧪 **Zero-Shot vs Few-Shot vs Fine-Tuned:** Measures how each method impacts accuracy and reasoning.
- 📊 **Dataset Integration:** Uses real middle school science questions from the TQA dataset.
- 🔬 **Experimental Design:** Analyzes responses to identify strengths, weaknesses, and patterns in understanding.
- 📓 **Notebook Format:** Clean, interactive Python notebooks make the project accessible and reproducible.

---

## Getting Started

### Prerequisites

This project requires the following:

- **Programming Language:** Python 3.8+
- **Tools:** Jupyter Notebook  
- **Libraries:** `openai`, `pandas`, `numpy`, `matplotlib`, `tqdm`

### Installation

1. **Clone the repository:**
```sh
git clone https://github.com/TejSuklikar/GPT-3-Research-Project
```

2. **Navigate to the project directory:**
```sh
cd GPT-3-Research-Project
```

3. **(Optional) Create a virtual environment:**
```sh
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

4. **Install the dependencies:**
```sh
pip install -r requirements.txt
```

> If you don’t have a `requirements.txt`, manually run:
```sh
pip install openai pandas numpy matplotlib tqdm jupyter
```

### Usage

1. **Launch the notebook:**
```sh
jupyter notebook
```

2. **Open and run `gpt3_tqa_experiments.ipynb`**

Make sure you have an OpenAI API key and that it is properly loaded in the notebook (e.g., using `openai.api_key`).

### Testing

This project is research-focused and does not include automated unit tests.  
If you want to add tests, you can use:
```sh
python -m unittest discover
```
Or with `pytest`:
```sh
pytest
```

---

## Results Summary

The evaluation showed that GPT-3 performed best with **few-shot prompting**, followed by **fine-tuning**, with **zero-shot** performing the worst.

- **Few-Shot:** Delivered the most accurate and contextually appropriate answers. Providing 2–3 examples before each question helped the model generalize patterns effectively, especially on multi-step reasoning problems.
- **Fine-Tuned:** Improved over zero-shot by adapting to the domain, but it lacked the general flexibility few-shot prompting achieved with minimal effort.
- **Zero-Shot:** Performed the weakest, often misinterpreting question intent or returning vague answers due to lack of prior examples.

This experiment highlights the surprising strength of few-shot prompting for educational QA tasks and the importance of context when leveraging large language models.

---

<div align="left"><a href="#top">⬆ Return</a></div>

---
