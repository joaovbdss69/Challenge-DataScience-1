
# Challenge Data Science Semana 1

Esse desafio é uma simulação de atividades do dia a dia de um profissional na área de Data
Science,o desafio consiste em tratar e modelar uma base de dados, para assim criar modelos e gráficos
para tomada de decisões.




## Desafios Semanais

- Semana 1
    - limpeza dos dados trazidos de uma API ✔️
    - Entender quais informações o conjunto de dados possui ✔️
    - Analisar quais os tipos de dados ✔️
    - Verificar quais são as inconsistências nos dados ✔️
    - Corrigir as inconsistências nos dados ✔️
    - Traduzir as colunas 
    - Criar coluna de contas diárias ✔️

- Semana 2
- Semana 3
- Semana 4




## Importações

```bash
    import pandas as pd
    import csv
    import json  
```

## 🗑️ Limpeza dos Dados

- Extração dos dados do Json para colunas

- Padronização e tradução das colunas

- Busca de valores null ou vazios

- Alteração dos tipos das tabelas

## 🌎 Tratativa e Criações na base de dados

- Tradução dos dados

- Criar coluna de contas diárias

- Validando os valores da coluna gastoTotal

## 🔍 Análise Exploratória
- 📍 Tipo de dados no dataset

    - 📍 Dados Quantitativos: São números que representam contagens ou medidas (renda e anos de escolaridade,por exemplo). Esses dados se dividem em discretos e contínuos:
        -   Discreto: Os dados discretos são aqueles em que o número de valores possíveis são finitos ou “enumeráveis” (tal como o número de cômodos em um domicílio).
            -  MesesContrato
        - Contínuo: Os dados contínuos resultam de infinitos valores possíveis em uma escala contínua (renda per capita).
            - totalServicosMensalmente
            - totalGasto
    - 📍 Dados Qualitativos ou Categóricos: Se distinguem por alguma característica não-numérica (sexo e raça, por exemplo).
        - Nominal: Utiliza dados que informam nomes, rótulos ou categorias. Os dados não são ordenados e não devem ser usados para cálculos de médias, como é o caso de raça e código do município.


