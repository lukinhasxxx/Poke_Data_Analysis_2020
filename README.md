# Análise de Dados de Pokémon

Este projeto foi realizado no 2º semestre de 2020 na UFABC, na disciplina de BCC, utilizando apenas a documentação das bibliotecas Pandas, Seaborn, Matplotlib, etc., sem o auxílio de IA generativa. O objetivo principal foi obter insights e interpretar os dados de forma livre, com foco na limpeza e manipulação das informações do DataFrame.

## Estrutura do Projeto

### Dados de Pokémon (Parte 1)
- **Limpeza dos Dados:** 
  - Remoção de duplicatas, correção de valores inconsistentes e preenchimento de valores faltantes.
- **Principais Ações:** 
  - Análise exploratória para entender a distribuição dos tipos de Pokémon.
  - Verificação da correlação entre atributos como Vida, Ataque, Defesa, Velocidade, etc.
  - Agrupamento dos Pokémon por geração para analisar as mudanças nas características ao longo das gerações.

### Dados de Batalhas de Pokémon (Parte 2)
- **Limpeza dos Dados:**
  - Remoção de batalhas com dados incompletos ou inconsistentes.
  - Normalização de identificadores de Pokémon.
- **Principais Ações:** 
  - Análise das vitórias e derrotas de Pokémon para identificar padrões de sucesso.
  - Investigação dos Pokémon com maior frequência de vitórias.
  - Estudo dos confrontos entre tipos específicos de Pokémon e suas taxas de vitória.

## Resumo dos Principais Insights

- **Atributos Fortes:** 
  - Pokémon com altos valores de Vida, Ataque e Defesa tendem a ter melhores desempenhos em batalhas, com esses atributos correlacionados a taxas de vitória mais altas.
- **Tipos de Pokémon:** 
  - Certos tipos de Pokémon, como Dragão e Aço, demonstram vantagem significativa em batalhas devido à combinação de fortes atributos básicos e resistências naturais.
- **Impacto das Gerações:** 
  - As gerações mais recentes introduziram Pokémon com atributos mais equilibrados, mas alguns das primeiras gerações ainda dominam devido à combinação de atributos extremos, como altíssimo Ataque ou Defesa.
- **Padrões de Vitória:** 
  - Pokémon com habilidades ou combinações de movimentos que exploram as fraquezas dos adversários frequentemente superam aqueles com melhores atributos, destacando a importância da estratégia.

## Métodos Usados

- **Correlação de Atributos:** 
  - Matrizes de correlação foram utilizadas para identificar como os diferentes atributos influenciam uns aos outros e o sucesso nas batalhas.
- **Análise de Confrontos Diretos:** 
  - Avaliação das batalhas entre tipos diferentes de Pokémon para determinar as combinações mais eficazes e as vantagens naturais.
- **Agrupamento e Comparação por Geração:** 
  - Comparações entre diferentes gerações para avaliar como as características dos Pokémon evoluíram e identificar padrões dominantes.

