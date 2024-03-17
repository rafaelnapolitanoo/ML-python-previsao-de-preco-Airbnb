# ML-python-previsao-de-preco-Airbnb
 Modelo de previsão de preço que permita uma pessoa comum que possui um imóvel possa saber quanto deve cobrar pela diária do seu imóvel. Ou ainda, para o locador comum, dado o imóvel que ele está buscando, ajudar a saber se aquele imóvel está com preço atrativo (abaixo da média para imóveis com as mesmas características) ou não


Modelo de previsão de preço que permita uma pessoa comum que possui um imóvel possa saber quanto deve cobrar pela diária do seu imóvel. Ou ainda, para o locador comum, dado o imóvel que ele está buscando, ajudar a saber se aquele imóvel está com preço atrativo (abaixo da média para imóveis com as mesmas características), ou não.

em portugues:

comecei tratando a base de dados retirada do keegle, ultilizando a biblioteca pandas para remover informacoes nullas. apos isso retirei colunas que pudessem atrapalhar a previsao do modelo como: politica de cancelamento, tipo de quarto e de cama,etc. logo mais eu removi os outliers dos dados que seriam ultilizados na analise, afim de deixar mais precisa a resposta entre os tres modelos de regreção:
1. RandomForest 2. LinearRegression 3. Extra Tree

o que se saiu melhor foi o Extratree com R²:97.51% RSME:41.84

O deploy foi feito com uma intregração do tkinter com um arquivo exe logo temos uma interface grafica que apos receber todas as informações solicitadas, apresenta o resultado ao usuario de maneira simples e objetiva, sem contato com nenhuma IDE ou script python (não disponibilizado no repositorio)

in english:

The initial idea of ​​the project was to create a ml that could predict fair prices for each Airbnb accommodation based on the number of rooms, bathrooms, beds, etc. The Python programming language was used to answer this question I started treating the database taken from Keegle, using the pandas library to remove null information. After that, I removed columns that could interfere with the model's prediction, such as: cancellation policy, type of room and bed, etc. I then removed the outliers from the data that would be used in the analysis, in order to make the answer more precise. between the three regression models: 1. RandomForest 2. LinearRegression 3. Extra Tree

the one that did best was Extratree with R²:97.51% RSME:41.84

The deply was done with a tkinter integration with an exe file Therefore, we have a graphical interface that, after receiving all the requested information, presents the result to the user in a simple and objective way, without contact with any IDE or Python script.
