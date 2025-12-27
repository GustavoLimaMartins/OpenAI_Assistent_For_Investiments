# Assistente de Investimentos

Assistente inteligente para análise de ações brasileiras utilizando GPT-4 com function calling.

## Funcionalidades

- Consulta de preços atuais de ações brasileiras
- Geração de gráficos de cotação histórica (último ano)
- Interface conversacional em linguagem natural
- Integração com Yahoo Finance para dados em tempo real

## Tecnologias

- Python 3.x
- Streamlit
- OpenAI API (GPT-4)
- yfinance
- matplotlib
- pandas

## Instalação

```bash
pip install -r requirements.txt
```

Configure sua chave API da OpenAI no arquivo `.env`:
```
OPENAI_API_KEY=sua_chave_aqui
```

## Execução

```bash
python -m streamlit run agent-llm.py
```

## Uso

Digite perguntas como:
- "Qual o preço atual da VALE3?"
- "Mostre o gráfico da PETR4 no último ano"
- "Como está o Ibovespa?"

**Nota:** Use o formato Yahoo Finance para tickers brasileiros (ex: VALE3.SA, PETR4.SA, ^BVSP)
