# Machine Learning para prever preço justo do Airbnb

Modelo de previsão de preço que permita uma pessoa comum que possui um imóvel possa saber quanto deve cobrar pela diária do seu imóvel. Ou ainda, para o locador comum, dado o imóvel que ele está buscando, ajudar a saber se aquele imóvel está com preço atrativo (abaixo da média para imóveis com as mesmas características) ou não.

## Índice

- [Sobre](#sobre)
- [Instalação](#instalação)
- [Funcionalidades](#funcionalidades)
- [Tecnologias](#tecnologias)
- [Contribuição](#contribuição)
- [Licença](#licença)
- [Contato](#contato)

## Sobre

Comecei tratando a base de dados retirada do Kaggle, utilizando a biblioteca Pandas para remover informações nulas. Após isso, retirei colunas que pudessem atrapalhar a previsão do modelo, como: política de cancelamento, tipo de quarto e de cama, etc. Logo mais, removi os outliers dos dados que seriam utilizados na análise, a fim de deixar mais precisa a resposta entre os três modelos de regressão:

RandomForest
LinearRegression
Extra Tree
O que se saiu melhor foi o Extra Tree com R²: 97.51% e RSME: 41.84.

O deploy foi feito com uma integração do Tkinter com um arquivo EXE. Logo, temos uma interface gráfica que, após receber todas as informações solicitadas, apresenta o resultado ao usuário de maneira simples e objetiva, sem contato com nenhuma IDE ou script Python (não disponibilizado no repositório).

## Instalação

Passo a passo de como instalar e configurar o ambiente de desenvolvimento. Por exemplo:

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/nome-do-projeto.git
```

## Instale as dependências
npm install

## Funcionalidades
 Lista das principais funcionalidades do projeto:

-Previsão de preço para imóveis, ajudando proprietários a determinar a diária ideal.
-Avaliação de imóveis para locadores, indicando se o preço é atrativo ou não.
-Interface gráfica amigável para inserção de dados e visualização dos resultados.
-Integração com um arquivo executável para fácil uso sem necessidade de IDE ou scripts Python.

  
## Tecnologias
Liste as principais tecnologias usadas no projeto:

-Python
-Pandas (para manipulação e limpeza de dados)
-Scikit-learn (para modelos de regressão)
-Tkinter (para a interface gráfica)
-RandomForestRegressor
-LinearRegression
-ExtraTreesRegressor
  
## Contribuição
Como outros desenvolvedores podem contribuir para o projeto, exemplo:

<p> Faça um fork do projeto </p>
<p> Crie uma branch para sua feature (git checkout -b feature/AmazingFeature) </p>
<p> Commit suas mudanças (git commit -m 'Add some AmazingFeature') </p>
<p> Envie para a branch (git push origin feature/AmazingFeature) </p>
<p> Abra um Pull Request </p>




## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.

## Contato
Rafael Napolitano
LinkedIn: https://www.linkedin.com/in/rafaelnapolitano/
in english:

The initial idea of ​​the project was to create a ml that could predict fair prices for each Airbnb accommodation based on the number of rooms, bathrooms, beds, etc. The Python programming language was used to answer this question I started treating the database taken from Keegle, using the pandas library to remove null information. After that, I removed columns that could interfere with the model's prediction, such as: cancellation policy, type of room and bed, etc. I then removed the outliers from the data that would be used in the analysis, in order to make the answer more precise. between the three regression models: 1. RandomForest 2. LinearRegression 3. Extra Tree

the one that did best was Extratree with R²:97.51% RSME:41.84

The deply was done with a tkinter integration with an exe file Therefore, we have a graphical interface that, after receiving all the requested information, presents the result to the user in a simple and objective way, without contact with any IDE or Python script.
