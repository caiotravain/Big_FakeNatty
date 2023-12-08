# Projeto de Big Data - Detecção de contas falsas no Instagram

**Integrantes:**
Caio Travain, Joseph Kallas e Thomas Chabro

## **Introdução**

A proposta entregue aos alunoso, foi da criação de um algoritmo a partir das técnicas aprendidas em aula, que fosse capaz de análisar grandes volumes de dados, e prever algum tipo de comportamento. Ainda, a ideia é de que esta previsão fosse de fato útil e aplicável em um mundo real, tendo um impacto e uso prático na vida de um usuário.

Para isso, foi escolhido o tema de **detecção de contas falsas no Instagram**, que se torna cada vez mais relevante, dada a massiva presença e influência de contas em plataformas de redes sociais. Ainda, a detecção de contas falsas é um problema que pode ser aplicado em diversas outras plataformas, como o Twitter, Facebook, entre outros.

Este projeto aplica uma análise de dados obtidos de um dataset público, que explora as variáveis presentes e associadas a comportamentos suspeitos para então desenvolver um modelo de regressão a fim de distinguir de maneira eficaz se uma conta é verdadeira ou falsa. Para isso, criamos um script em Python, utilizando a biblioteca Dask para a leitura dos dados de maneira distribuída.

## **Problema**

No mundo atual, as redes sociais desempenham cada vez mais um papel de protagonismo na comunicação das pessoas, e como meio de informação. Dentre as principais redes, está o Instagram, que conta com mais de 2 bilhões de usuários ativos mensalmente. Desta forma, a presença de um perfil falso pode se tornar um imenso risco para a sociedade, dado que pode (e muitas vezes é) utilizado para a disseminação de notícias falsas.

O próprio Brasil já sofreu com este problema, durante eleições presidenciais, onde perfis falsos tinham o intuito de manipular a opinião pública a partir de notícias falsas. Ainda, a presença de perfis falsos pode ser utilizada para a disseminação do ódio, racismo, xenofobia, entre outros.

Diante disto, o problema central abordado pelo projeto, e que visa ser resolvido, é a identificação eficaz de contas falsas, a fim de reduzir ao máximo o impacto negativo e riscos que estes perfis apresentam para a sociedade. Por escolha do dataset, o foco da análise será no Instagram. Entretanto, nada impede que o modelo seja reaplicado em outras plataformas, talvez passando por singelos ajustes, dependendo das diretrizes de cada rede social

**Para acessar o dataset, clique [aqui](https://www.kaggle.com/datasets/rezaunderfit/instagram-fake-and-real-accounts-dataset)**
