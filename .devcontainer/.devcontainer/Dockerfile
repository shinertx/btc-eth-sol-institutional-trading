FROM python:3.11-slim

WORKDIR /workspace

COPY infra/requirements.txt .
RUN pip install --upgrade pip && pip install -r requirements.txt

RUN pip install black flake8 mypy pytest bandit ccxt pandas numpy ta-lib scipy
