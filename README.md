# 📊 Estudo de Caso: Predição de Turnover em Tecnologia

Este repositório apresenta uma análise detalhada sobre os fatores de rotatividade (turnover) de funcionários numa empresa de tecnologia. O projeto utiliza técnicas estatísticas para identificar padrões críticos e fundamentar decisões estratégicas de RH.

👉 **Confira a análise completa com os insights de negócio no [Medium](https://medium.com/@eliassss618/melhorando-a-reten%C3%A7%C3%A3o-de-funcion%C3%A1rios-em-uma-empresa-de-tecnologia-turnover-fe8cbb052c46).**

## 📋 Sobre os Dados
A base de dados utilizada neste estudo é **fictícia**, proveniente do curso *Gerando Valor com Dados* da **[Preditiva.ai](https://preditiva.ai/)**. O dataset contém registos de 1.470 funcionários com 20 variáveis (excluindo IDs), incluindo salários, horas extras e níveis de satisfação.

## 📂 Estrutura do Repositório
O projeto foi organizado para refletir o fluxo de trabalho de um analista de dados:

- **`/base`**: Contém a base original (Raw Data) utilizada como ponto de partida para o estudo.
- **`/analises`**: Ficheiros consolidados com o desenvolvimento técnico:
    - **Análise 1**: **Análise Exploratória** inicial, frequências e panorama geral dos dados.
    - **Análise 2**: Cruzamentos bidimensionais e associações entre variáveis.
    - **Análise 3**: Análise de IV (Information Value) e Weight of Evidence (WoE), focada no poder preditivo e na força de cada variável.
    - **Metadados**: Dicionário de variáveis para interpretação técnica.
- **`/imagens`**: Gráficos gerados para suporte visual aos insights.
- **`/dados`**: Ficheiro Excel original com todas as fórmulas e Tabelas Dinâmicas preservadas.

## 💡 Insights de Destaque
Através dos cálculos de **IV (Information Value)** presentes na Análise 3, identificamos os preditores mais fortes para a saída de colaboradores:
1. **Horas Extras (IV: 0.400 - Muito Forte)**: O fator com maior impacto na propensão ao turnover.
2. **Salário Mensal (IV: 0.338 - Forte)**: Níveis salariais mais baixos apresentam maior rotatividade crítica.
3. **Stock Options (IV: 0.319 - Forte)**: A ausência de planos de ações correlaciona-se com menor retenção.
   
## 🎯 Conclusão
O projeto demonstrou que a retenção de talentos não depende de um único fator, mas de um conjunto onde o equilíbrio entre vida pessoal e trabalho (horas extras) é o pilar principal. Este estudo serve de base para a criação de modelos preditivos mais complexos no futuro.
---
*Projeto desenvolvido por **Elias Santos Silva** - Estudante de Inteligência Artificial e Machine Learning.*
