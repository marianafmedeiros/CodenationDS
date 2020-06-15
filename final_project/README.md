# **Projeto AceleraDev Data Science**

### **Objetivo**

O objetivo deste produto é fornecer um serviço automatizado que recomenda leads para um usuário dado sua atual lista de clientes (Portfólio).

### **Contextualização**

Algumas empresas gostariam de saber quem são as demais empresas em um determinado mercado (população) que tem maior probabilidade se tornarem seus próximos clientes. Ou seja, a sua solução deve encontrar no mercado quem são os leads mais aderentes dado as características dos clientes presentes no portfólio do usuário.

Além disso, sua solução deve ser agnóstica ao usuário. Qualquer usuário com uma lista de clientes que queira explorar esse mercado pode extrair valor do serviço.

Para o desafio, deverão ser consideradas as seguintes bases:

* Mercado: Base com informações sobre as empresas do Mercado a ser considerado. 
* Portfolio 1: Ids dos clientes da empresa 1 
* Portfolio 2: Ids dos clientes da empresa 2 
* Portfolio 3: Ids dos clientes da empresa 3

Obs: todas as empresas(ids) dos portfolios estão contidos no Mercado(base de população).

Link para download das bases Mercado, Portfolio 1, Portfolio 2 e Portfolio 3:

[Mercado](https://codenation-challenges.s3-us-west-1.amazonaws.com/ml-leads/estaticos_market.csv.zip)

[Portfolio 1](https://codenation-challenges.s3-us-west-1.amazonaws.com/ml-leads/estaticos_portfolio1.csv)

[Portfolio 2](https://codenation-challenges.s3-us-west-1.amazonaws.com/ml-leads/estaticos_portfolio2.csv)

[Portfolio 3](https://codenation-challenges.s3-us-west-1.amazonaws.com/ml-leads/estaticos_portfolio3.csv)

As bases de portfólio poderão ser utilizadas para testar a aderência da solução. Além disso, se a equipe desejar, poderá simular portfólios por meio de amostragens no mercado.

[Descrição de variáveis](https://s3-us-west-1.amazonaws.com/codenation-challenges/ml-leads/features_dictionary.pdf)

### **Requisitos técnicos obrigatórios**
* Utilizar técnicas de data science e machine learning para desenvolver o projeto;
* Apresentar o desenvolvimento e outputs do modelo em um Jupyter Notebook ou outra tecnologia de apresentação de Output de modelos de Machine Learning;
* A análise deve considerar os seguintes pontos: 
    1. análise exploratória dos dados, 
    2. tratamento dos dados,
    3. avaliação de algoritmos, 
    4. treinamento do modelo, 
    5. avaliação de performance do modelo e 
    6. visualização dos resultados;


* Para a apresentação do projeto, o tempo entre o treinamento do modelo e o output deve ser menor que 20 min.