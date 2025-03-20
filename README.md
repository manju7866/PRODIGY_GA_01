# Text Generation with GPT-2

This project demonstrates how to use **GPT-2 (Generative Pre-trained Transformer 2)** for **text generation**. GPT-2 is a state-of-the-art language model developed by OpenAI that can generate human-like text based on a given input prompt. The notebook allows users to input a prompt, and GPT-2 generates a continuation of that text in a coherent and contextually relevant manner.

## Project Overview

The project uses **Hugging Face's `transformers` library** to load the pre-trained GPT-2 model and interactively generate text. Users can adjust parameters such as text length, temperature, and the input prompt for custom text generation.

### Key Features:
- **Text Generation with GPT-2**: Generate text based on a given prompt.
- **Adjustable Parameters**: Customize the generation with parameters like **text length**, **temperature**, and **top_k sampling**.
- **Interactive Widgets**: User-friendly interface in **Jupyter Notebook** or **Google Colab** for easy interaction.

## Requirements

To run this notebook, you need the following Python libraries:

- **Python 3.x**
- **Hugging Face Transformers**
- **ipywidgets** (for the interactive UI)
- **TensorFlow** or **PyTorch** (depending on the model backend)

You can install the required dependencies using `pip`:

```bash
pip install transformers ipywidgets tensorflow
# PRODIGY_GA_01
