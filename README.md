# WS - Projeto busca google e buscape

- Projeto de automação web que iráautomatizar pesquisa de preços com base em uma planilha de produtos, para esse projeto iremos utilizar a biblioteca Selenium do python.

# Entendimento do negócio

- Um funcionário trabalha na área de compras de uma empresa e precisa fazer uma comparação de fornecedores para os seus insumos/produtos.

- Esse funcionário constantemente busca nos sites desses fornecedores os produtos disponíveis e o preço, afinal, cada um deles pode fazer promoção em momentos diferentes e com valores diferentes.

# Objetivo

- Seu objetivo: Criar uma pesquisa automática que, irá buscar por produtos com valor abaixo de mercado, então deve-se criar uma planilha com esses produtos, indicando o preço, nome do produto e link para compra.

- Em seguida, vai enviar um e-mail com a lista destes produtos para o setor de compra.

- OBS: No nosso caso, vamos fazer com produtos comuns em sites como Google Shopping e Buscapé, mas a ideia é a mesma para outros sites. Essa busca também pode ser feita por APIs.


### O que temos disponível?

- Planilha de Produtos, com os nomes dos produtos, o preço máximo, o preço mínimo (para evitar produtos "errados" ou "baratos de mais para ser verdade" e os termos que vamos querer evitar nas nossas buscas.

# Email enviado

- Segue abaixo o modelo do e-mail enviado, com nome do produto, preço e link, e ainda em anexo a tabela:
![Captura de tela_20230104_181424](https://user-images.githubusercontent.com/115194365/210651431-5382d10c-fbe3-4261-9705-6d8f3f90530a.png)

# Código fonte do projeto
[Clique aqui para abrir o código do projeto](https://github.com/dev-daniel-amorim/WS---Projeto-Google-e-Buscape/blob/main/DS-Automacao_web.ipynb)

