
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
![image](https://user-images.githubusercontent.com/105249003/168425489-3cb2709e-b0ed-49c1-9567-49a5e6204ab6.png)

- Padronização e tradução das colunas
![image](https://user-images.githubusercontent.com/105249003/168425543-73dce6b2-f3cc-4425-92a1-c6f8427b6e17.png)

- Busca de valores null ou vazios e Substituição dos mesmos
![image](https://user-images.githubusercontent.com/105249003/168425561-51b8177d-12a9-41b3-9a3c-4ac0cdd9cb81.png)

![image](https://user-images.githubusercontent.com/105249003/168425611-0e5bd83b-74f3-4d9b-b9cd-59b454e32b95.png)

- Alteração dos tipos das tabelas
![image](https://user-images.githubusercontent.com/105249003/168425629-60535330-0054-431f-a2fa-8ff848462921.png)

## 🌎 Tratativa e Criações na base de dados

- Tradução dos dados
 
 * ![image](https://user-images.githubusercontent.com/105249003/168427617-276d4344-3eec-4250-9781-a81bc4f88279.png)


- Criar coluna de contas diárias
![image](https://user-images.githubusercontent.com/105249003/168427702-9269fe79-3395-4931-ab5e-00b4a22b1860.png)


## 🔍 Análise Exploratória
![image](https://user-images.githubusercontent.com/105249003/168427564-c91a9466-5fd6-43ed-a631-f77c3ed5f067.png)
![image](https://user-images.githubusercontent.com/105249003/168427572-5e9c72e2-25fe-4644-8ebb-983c931baa38.png)

- 📍 Tipo de dados no dataset

    - 📍 Dados Quantitativos: São números que representam contagens ou medidas (renda e anos de escolaridade,por exemplo). Esses dados se dividem em discretos e contínuos:
        -   Discreto: Os dados discretos são aqueles em que o número de valores possíveis são finitos ou “enumeráveis” (tal como o número de cômodos em um domicílio).
            -  MesesContrato
        - Contínuo: Os dados contínuos resultam de infinitos valores possíveis em uma escala contínua (renda per capita).
            - totalServicosMensalmente
            - totalGasto
    - 📍 Dados Qualitativos ou Categóricos: Se distinguem por alguma característica não-numérica (sexo e raça, por exemplo).
        - Nominal: Utiliza dados que informam nomes, rótulos ou categorias. Os dados não são ordenados e não devem ser usados para cálculos de médias, como é o caso de raça e código do município.


