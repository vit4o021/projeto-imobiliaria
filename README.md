# Projeto uma imobiliaria com o Pandas:
Este projeto pessoal consiste em realizar um projeto em uma empresa imobiliária, onde a minha principal função é dar suporte às demandas do time de Machine Learning e do time de desenvolvimento dessa empresa.

A base de dados que vai ser utilizada para desenvolver o projeto é uma base com dados de diferentes tipos de imóveis do Rio de Janeiro, como apartamento, casas, comércios, entre outros.
Nessa base, serão encontrados os valores dos aluguéis de cada imóvel, condomínio, IPTU e também suas características, como: quantidade de quartos, suítes, vagas de garagem, etc.

Sobre as demandas do time de Machine Learning serão feitas:
1) Importação e conhecimento da base de dados.
2) Análise exploratória dos dados (Analisar quais os valores médios de aluguel por tipo de imóvel e qual o percentual de cada tipo de imóvel na base de dados).
3) Tratar valores nulos (Visto que dados nulos não podem ser utilizados no treinamento de modelos de ML)
4) Remover registros inconsistentes (Apartamentos que possuem valor de aluguel igual a 0 e apartamentos com o valor do condomínio igual a 0).
5) Aplicar filtros (O time de ML deseja avaliar apenas imóveis em cenários específicos, como: 1. Apartamentos que possuem 1 quarto e aluguel menor que R$ 1200 e 2. Apartamentos que possuem pelo menos 2 quartos, aluguel menor que R$ 3000 e área maior que 70 m²).
6) Salvar os dados.

Sobre as demandas do time dde desenvolvimento serão feitas:
1) Criar colunas numéricas (O time de desenvolvedores do site da empresa solicitou a criação de duas novas colunas numéricas na base de dados - 1. Valores por mês, onde essa coluna deve conter os gastos mensais de cada imóvel, incluindo aluguel e condomínio. 
 e 2. Valores por ano: essa coluna deve conter os gastos anuais por imóvel, ou seja, IPTU mais 12 meses de aluguel e condomínio.)
2) Criar colunas categóricas (O time de desenvolvimento solicitou a criação de mais duas colunas. No entanto, dessa vez elas são categóricas, são elas - Descrição: essa coluna deve possuir uma sumarização das principais informações dos imóveis que serão apresentadas no site: tipo de imóvel, bairro, quantidade de quartos e vagas de garagem e a coluna possui suite: essa deve ser uma coluna que informe apenas se o imóvel possui ou não suítes, sem se importar com a quantidade).
