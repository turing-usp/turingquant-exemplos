# Projeto de aplicação da biblioteca turingquant
Este projeto utiliza as funções da biblioteca turingquant para obter insigths do desempenho de ativos do mercado brasileiro

## 1. Criação do ambiente virtual
É recomendado criar um ambiente virtual antes de fazer a instalação da biblioteca. Desta forma evitamos interferências entre bibliotecas.

Para criar o ambiente virtual, podemos executar estes comandos no terminal:
```
python3.9 -m venv venv
source venv/bin/activate
```

## 2. Instalação da biblioteca turingquant
Para utilizar a biblioteca turingquant temos que instalar os pacotes mostrados no block code
```
!pip install turingquant
!pip install scipy
```

## 3. Importação da biblioteca turingquant

No block code embaixo se mostra um exemplo de importação da biblioteca turingquant:
```
# exemplo de importacao da funcao Markowitz da biblioteca turingquant
from turingquant.optimizers import Markowitz
# importamos a biblioteca para importar os dados com a api do yahoo finance
import yfinance as yf
```
