# :parrot: :hugs: :robot: Langchain HuggingGPT

Implementation of [HuggingGPT](https://arxiv.org/abs/2303.17580) with [langchain](https://docs.langchain.com/docs/).

## Getting Started

Install the package with pip:

```commandline
pip install -r requirements.txt
pip install -e .
```

or with your preferred virtual environment manager (_this project uses [pdm](https://pdm.fming.dev/) for dependency management_).

Setup your OpenAI and Huggingface Hub credentials:

```commandline
cp .env.example .env
```

Then fill in the `.env` file with your credentials.

## Usage


```commandline
python main.py
```

Then converse with HuggingGPT, e.g:

```
Generate an image of a classroom
```

```
Now count the number of chairs in the image
```

To use the application in standalone mode, use the `--prompt` flag:

```commandline
python main.py --prompt "Generate an image of a classroom"
```

## Examples

TODO

## Development

### Testing

Run tests with pytest:

```commandline
pytest
```

## Credits

* [JARVIS](https://github.com/microsoft/JARVIS)

