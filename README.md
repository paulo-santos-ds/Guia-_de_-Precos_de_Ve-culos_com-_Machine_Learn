# 🚗 Guia de Precos de Veiculos com Machine Learn


## 📋 Sobre o Projeto
Sistema de predição de preços de carros usados desenvolvido para a Rusty Bargain. O modelo visa estimar rapidamente o valor de mercado de veículos, otimizando o processo de compra e venda através de análise precisa e eficiente.

## 🎯 Objetivos do Projeto
- Desenvolver um modelo de predição com alta precisão
- Garantir velocidade na geração de previsões
- Otimizar o tempo de treinamento do modelo

## 🛠️ Ferramentas e Bibliotecas Utilizadas 
- Python: Linguagem principal utilizada para a análise
- Pandas e Numpy: Biblioteca para manipulação e análise de dados
- Sklearn: Biblioteca para construção de modelo de machine learning
- Seaborn: Biblioteca para construção de gráficos
- Matplotlib: Biblioteca para construção de gráficos
- Math: Biblioteca para calculos matematicos
- Lgbm: Biblioteca para construção de modelo de machine learning
- Catboost: Biblioteca para construção de modelo de machine learning

## 📊 Conjunto de Dados
O dataset inclui as seguintes características:

### Dados Temporais
- `DateCrawled`: Data de extração do perfil
- `DateCreated`: Data de criação do perfil
- `RegistrationYear`: Ano de matrícula do veículo
- `RegistrationMonth`: Mês de registro do veículo

### Características do Veículo
- `VehicleType`: Tipo de carroçaria
- `Gearbox`: Tipo de transmissão
- `Power`: Potência (hp)
- `Model`: Modelo do veículo
- `Mileage`: Quilometragem (km)
- `FuelType`: Tipo de combustível
- `Brand`: Marca do veículo
- `NotRepaired`: Status de reparos do veículo

### Dados Adicionais
- `NumberOfPictures`: Quantidade de fotos do anúncio
- `PostalCode`: Código postal do proprietário

## 🔍 Metodologia
1. Análise Exploratória de Dados
    Importação das bibliotecas necessárias
    Carregamento e visualização dos dados

2. Pré-processamento
    Tratamento de dados ausentes
    Remoção de dados duplicados

3. Preparação
    Codificação de rótulos
    Seleção de features e target
    Divisão entre base de teste e treino

4. Criação de Modelos
    Calibração de hiperparâmetros
    Implementação dos modelos:
        LightGBM
        Floresta Aleatória
        Árvore de Decisão
        Regressão Linear
    Análise das métricas

## 📈 Resultados

Para este projeto usamos os modelos de lightGBM, Floresta Aleatória, Árvore de Decisão e Regressão Linear para decidir qual o melhor modelo para nosso conjunto de dados. Testamos diferentes parâmetros no modelo lightGBM que variaram muito o tempo de execução do mesmo, por isso deixei o que está no projeto. Além de medir o tempo de execução de cada modelo avaliamos todos eles pelo REQM, e por isso, podemos escolher o modelo lightGBM como o melhor para essa tarefa, por mais que ele tenha o maior tempo de execução, é acetável.

## 📝 Aprendizados

- Análise de dados: Extração de insights valiosos a partir de grandes volumes de dados.
- Preparação para Machine Learning: Separação entre conjuntos de treino e teste, seleção de features.
- Aplicação de modelos de Machine Learning: Ajuste, avaliação e documentação.
- Tomada de decisões baseadas em dados: Uso de insights para decisões estratégicas.

## 🚀  Como Usar

1. Clone o repositório
```bash
 https://github.com/paulo-santos-ds/Guia_de_Precos_de_Veiculos_com_Machine_Learn
```

2. Extrair o arquivo (car.zip)
 ```bash
 https://github.com/paulo-santos-ds/analise_de_sentimentos_em_criticas_de_filmes

```
3. Instale as dependências
```bash
pip install -r requirements.txt
```

4. Execute o notebook principal
```bash
https://github.com/paulo-santos-ds/Guia_de_Precos_de_Veiculos_com_Machine_Learn/blob/main/car_data.ipynb
```

