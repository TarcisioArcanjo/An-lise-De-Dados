# Análise de Cancelamento de Clientes

Este projeto tem como foco identificar padrões de comportamento que indicam propensão ao cancelamento de clientes.

## 🛠 Tecnologias e Bibliotecas Utilizadas
- Python
- Pandas
- Plotly

## 🔍 Etapas do Projeto
1. **Importação e limpeza dos dados**:
   - Remoção de colunas irrelevantes (`CustomerID`);
   - Exclusão de dados ausentes (`dropna`);
2. **Análise exploratória dos dados (EDA)**:
   - Contagem e proporção de cancelamentos;
   - Visualização de todas as variáveis com histogramas segmentados pela variável `cancelou`.

## 📊 Insights
- Através da visualização gráfica foi possível identificar variáveis com maior impacto no cancelamento de clientes;
- Gráficos interativos foram criados para facilitar a análise e tomada de decisão.

## 📁 Arquivos
- `cancelamentos_sample.csv`: Base de dados de clientes;
- `codigo.py`: Código do projeto com análise e visualizações.

## 🎯 Objetivo
Projeto focado em análise exploratória de dados com visualização, visando entender padrões de cancelamento de clientes.
