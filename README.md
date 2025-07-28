# SmolLM Super Weight Analysis

## Project Description

This project aims to identify and analyze super weights in the context of Large Language Models (LLMs). Super weights are defined as weights that have a significant impact on the model's performance. The project provides a Jupyter notebook for users to run the analysis on their own models. It is unoficial implementation of the paper [The Super Weight in Large Language Models](https://arxiv.org/abs/2411.07191).

## Installation

### Prerequisites

- Python 3.12
- CUDA 12.8 (for GPU support)
- UV

### Installation Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/aerubanov/SmolLMSuperWeight.git
    cd SmolLMSuperWeight
    ```

2. Install dependencies:
    ```bash
    uv sync --extra cu128
    ```
    of for cpu only
    ```bash
    uv sync --extra cpu
    ```

3. Open SmolLM-super-weight.ipynb in VSCode with Jupyter extension and run the notebook.

## Links

- Original paper: https://arxiv.org/abs/2411.07191
- Original code: https://github.com/pchizhov/hellaswag-evaluation