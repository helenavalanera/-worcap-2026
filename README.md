# WorCAP 2026 — Previsão Mensal de Precipitação na América do Sul

## Objetivo
Desenvolver um algoritmo de regressão para estimar a precipitação média
do mês seguinte na América do Sul, utilizando dados históricos e variáveis
atmosféricas disponibilizadas na competição.

## Autora
Helena Valanera

## Dados
Base disponibilizada pela organização do Hackathon WorCAP 2026 no Kaggle.
Dados externos, se utilizados, serão registrados com fonte, data de acesso,
licença e justificativa de uso.

## Metodologia
- Auditoria e exploração dos dados.
- Construção de variáveis temporais e espaciais.
- Defasagens temporais e estatísticas móveis.
- Validação cronológica.
- Comparação com baselines.
- Treinamento de modelos de regressão.
- Avaliação pela métrica oficial da competição.

## Reprodutibilidade
1. Instale as dependências descritas em `requirements.txt`.
2. Baixe os dados a partir da página oficial da competição.
3. Posicione os arquivos na pasta local indicada em `data/README.md`.
4. Execute os notebooks ou scripts na ordem numérica.

## Limitações
A previsão mensal de precipitação é um problema complexo e sujeito a
incertezas climáticas, espaciais e temporais. A solução não deve ser
interpretada como previsão operacional para tomada de decisão crítica.
