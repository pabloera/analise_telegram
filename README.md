# Análise de Discursos Políticos no Telegram

Análise de discursos políticos, negacionistas e autoritários circulados em espaços de redes sociais e mensageiros, como o Telegram, para fomentar oposicionamentos radicalizados constituídos em torno de espaços digitais de baixo controle de liberdades, garantias de privacidade tecnológicas e fluxo intenso de informações de mídias sociais, mídias alternativas e formação discursiva intensificada por fluxos informacionais intensos.

## Instalação

```bash
# Instalar dependências
poetry install

# Ativar ambiente virtual
poetry shell
```

## Estrutura do Projeto

```
analise_telegram/
├── src/analise_telegram/    # Código principal
├── tests/                   # Testes
├── data/                    # Dados (raw, processed, external)
├── notebooks/               # Jupyter notebooks para análise
├── scripts/                 # Scripts utilitários
├── docs/                    # Documentação
├── pyproject.toml          # Configuração Poetry
└── README.md               # Este arquivo
```

## Comandos de Desenvolvimento

### Testes
```bash
poetry run pytest
poetry run pytest -v  # verbose
poetry run pytest --cov=src  # com coverage
```

### Linting e Formatação
```bash
poetry run black src/ tests/
poetry run flake8 src/ tests/
poetry run mypy src/
```

### Análise de Dados
```bash
poetry run python scripts/process_telegram_data.py
poetry run python scripts/analyze_discourse.py
```

## Diretrizes de Análise

### SEMPRE APRESENTE:
- Contagens reais de dados existentes
- Gráficos de distribuições reais
- Análise temporal baseada em timestamps reais
- Nenhum score, índice ou métrica inventada

### SEM INVENÇÕES:
- ❌ Scores de "radicalização linguística"
- ❌ "Marcadores autoritários" fictícios
- ❌ "Completude discursiva" inventada
- ❌ Listas de termos com relevância aleatória
- ❌ Qualquer métrica não solicitada