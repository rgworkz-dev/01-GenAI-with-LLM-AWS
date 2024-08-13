# Generative AI Use Case: Summarize Dialogue

This repository contains a Jupyter Notebook that demonstrates how to summarize dialogue using generative AI models. The notebook explores prompt engineering techniques to optimize the outputs of Large Language Models (LLMs) by experimenting with zero-shot, one-shot, and few-shot inferences.

## Table of Contents

1. **Introduction**
    - Overview of dialogue summarization using generative AI.
2. **Set up Kernel and Required Dependencies**
    - Instructions to install necessary packages and dependencies.
3. **Summarize Dialogue without Prompt Engineering**
    - Baseline approach to summarizing dialogue without any prompt modifications.
4. **Summarize Dialogue with an Instruction Prompt**
    - Techniques to guide the model's output using specific instructions.
    - Includes zero-shot and template-based inference.
5. **Summarize Dialogue with One Shot and Few Shot Inference**
    - Enhancing the model's output by providing one or more examples.
6. **Generative Configuration Parameters for Inference**
    - Tuning the parameters for optimal generative performance.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- Jupyter Notebook
- PyTorch
- Hugging Face Transformers

### Installation

Clone this repository:

```bash
git clone https://github.com/rgworkz-dev/01-GenAI-with-LLM-AWS.git
cd 01-GenAI-with-LLM-AWS
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

### Running the Notebook

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open `summarize_dialogue.ipynb` to explore the dialogue summarization use case.

## Contributing

If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.


## Acknowledgements

- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [PyTorch](https://pytorch.org/)
```