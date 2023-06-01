# LangChain <> Huggingface

This project is a simple template with all the necessary packages and a file to start working with LangChain and Huggingface.

## Example Use

In the main file, we are using Falcon-7B LLM model made by [Technology Innovation Institute](https://www.tii.ae/). The open source model is shared on [Hugging Face](https://huggingface.co/tiiuae/falcon-7b-instruct).

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Installed a recent version of Python (3.7 or newer) installed and a way to create virtual environments (virtualenv or conda)
- Created a Hugging Face account and obtain your API key. You could do that [here](https://huggingface.co/settings/tokens)

## Getting Started

Clone the repo

```bash
git clone https://github.com/waseemhnyc/langchain-huggingface-template
```

Create a virutalenv and source the environment

```bash
python3 -m venv myenv
source venv/bin/activate
```

Install the necessary libraries

```bash
pip install -r requirements.txt
```

Create a .env file and input your Hugging Face API Key in the file

```bash
cp .env.example .env
```

## Usage

To run the program, run the following command in the terminal:

```bash
python main.py
```

## Questions or Get in Touch

- Twitter: https://twitter.com/waseemhnyc
- Email: waseemh.nyc@gmail.com

## License

This project is licensed under the MIT License - see the LICENSE file for details.