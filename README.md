# CrewAI Demo

[CrewAI](https://www.crewai.com/) demo.

## Prerequisites

[Python 3.12](https://github.com/pyenv/pyenv):

```sh
brew install pyenv
pyenv install
```

[Ollama](https://ollama.com/download):

```sh
brew install ollama
```

## Install

Clone the repository:

```sh
git clone https://github.com/ai-action/crewai-demo.git
cd crewai-demo
```

Create the [virtualenv](https://docs.python.org/library/venv.html):

```sh
pyenv exec python -m venv .venv
source .venv/bin/activate
```

Install the dependencies:

```sh
pip install -r requirements.txt
```

## Run

Start Ollama:

```sh
ollama serve
```

Pull model:

```sh
ollama pull gemma:2b
```

Execute hello world task:

```sh
python hello_world.py
```

## License

[MIT](LICENSE)
