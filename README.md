# Projeto de análise de inadimplência de empréstimos: impacto do estado civil e número de filhos

## Descrição do projeto

O projeto consiste em preparar um relatório para a divisão de empréstimos de um banco, a fim de determinar se o estado civil e o número de filhos de um cliente têm impacto na inadimplência de empréstimos. O objetivo é utilizar essas informações para criar uma pontuação de crédito que avalie a capacidade de um devedor potencial de pagar seu empréstimo. O banco já possui alguns dados sobre a capacidade de crédito dos clientes.

## Descrição dos dados

Os dados utilizados para o projeto estão armazenados no arquivo /datasets/credit_scoring_eng.csv. As variáveis presentes no conjunto de dados são:

* `children`: o número de crianças na família
* `days_employed`: quanto tempo o cliente trabalhou
* `dob_years`: a idade do cliente
* `education`: o nível de educação do cliente
* `education_id`: identificador da educação do cliente
* `family_status`: estado civil do cliente
* `family_status_id`: identificador do estado civil do cliente
* `gender`: o sexo do cliente
* `income_type`: o tipo de renda do cliente
* `debt`: se o cliente já deixou de pagar um empréstimo
* `total_income`: renda mensal
* `purpose`: motivo para fazer um empréstimo

## Preparação dos dados

Os dados serão pré-processados por meio da identificação e preenchimento de valores ausentes, substituição do tipo de dados de número real pelo tipo inteiro, exclusão de dados duplicados e categorização dos dados. Os métodos utilizados para cada uma dessas ações serão explicados e justificados.

## Análise dos dados

Serão respondidas perguntas relacionando a existência de filhos, estado civil, nível de renda e finalidade do empréstimo com o pagamento pontual do empréstimo. As análises serão realizadas utilizando o Jupyter Notebook, com o código nas células de código e explicações e interpretações nas células de remarcação, utilizando formatação e títulos adequados.
