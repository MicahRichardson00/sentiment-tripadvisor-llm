# Instructions

Clone this repo:
```
git clone https://github.com/MicahRichardson00/sentiment-tripadvisor-llm.git
```

# Install

Set up a virtual environment.

For Linux/MacOS:
```
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

For Windows:
```
python3 -m venv .venv
.venv\Scripts\Activate
python -m pip install -r requirements.txt
```

Be sure to [install Prodigy](https://prodi.gy/docs/install) using your local key.

# Data Preprocessing

Rerun full jupyter notebook.

# Prodigy LLM label

```
python -m prodigy textcat.llm.fetch config.cfg data/output.jsonl data/sentiment-gpt3-annotated.jsonl
```
