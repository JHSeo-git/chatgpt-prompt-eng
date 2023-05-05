# ChatGPT Prompt Engineering for Developers

https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/

## setup

### 0. openai api key and env

1. https://platform.openai.com/signup
2. https://platform.openai.com/account/api-keys

```bash
cp .env.example .env
```

copy openai api key to .env `OPENAI_API_KEY`

### 1. python venv

python venv

```bash
python3 -m venv openai
source openai/bin/activate
```

#### venv deactivate

```bash
deactivate
```

### 2. install package

```bash
pip3 install -r requirements.txt
```

#### package freeze

```bash
pip3 freeze > requirements.txt
```

## run jupyter notebook

```bash
jupyter notebook
```
