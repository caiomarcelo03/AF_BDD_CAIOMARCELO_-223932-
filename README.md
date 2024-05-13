# BDD - GHERKIN

Crie um BDD com seu devido Gherkin com base no texto abaixo:

Imagine que você está planejando alugar um carro para uma viagem. Para facilitar esse processo, uma
empresa de locação de carros desenvolveu um sistema com diferentes comportamentos, dependendo das
circunstâncias da locação e do cliente.
Inicialmente, considere um cliente que deseja alugar um carro de luxo. Se esse cliente realizar a reserva
com antecedência de pelo menos uma semana, o sistema deve oferecer um desconto especial no valor
total da locação. Por outro lado, suponha um cliente que necessita alugar um carro utilitário de última hora,
sem qualquer reserva prévia. Nesse caso, o sistema deve ainda ser capaz de encontrar um veículo
disponível e processar a locação rapidamente, mesmo que isso implique em um custo um pouco mais
elevado devido à demanda urgente.
Esses cenários exemplificam como o sistema de locação de carros responde às diferentes necessidades e
condições dos clientes, adaptando-se para garantir uma experiência satisfatória de locação, seja para
reservas antecipadas ou demandas de última hora.


## Gherkin
Feature: Locação de Carros

Cenário:
Cliente reserva carro de luxo com antecedência.

Given que um cliente deseja alugar um carro de luxo.

And que o cliente realiza a reserva com antecedência de pelo menos uma semana.

When o sistema processa a reserva.

Then o sistema deve oferecer um desconto especial no valor total da locação.



Cenário:

Cliente aluga carro utilitário de última hora.

Given que um cliente necessita alugar um carro utilitário.

And que não há reserva prévia.

When o sistema verifica a disponibilidade de veículos.

And o sistema processa a locação rapidamente.

Then o sistema deve encontrar um veículo disponível.

And o sistema pode aplicar um custo um pouco mais elevado devido à demanda urgente.

## Descrição
O Gherkin é uma linguagem de especificação usada principalmente em práticas de BDD (Behavior-Driven Development) e é projetada para ser legível tanto por seres humanos quanto por máquinas. É uma linguagem de formatação simples que descreve o comportamento do software em termos de cenários

## Como Testar
Para visualizar o exemplo de exercício de Gherkin adicionado, basta acessar o arquivo [nome_do_arquivo.gherkin] no diretório [caminho_do_diretório] do repositório. Você pode ler o enunciado do cenário e entender como o comportamento do software é descrito em termos de passos simples e legíveis.

## Observações Adicionais
Este exemplo foi criado com base em práticas recomendadas e padrões de escrita de Gherkin.
Sinta-se à vontade para sugerir melhorias ou fazer perguntas nos comentários do arquivo.

## Suporte
Para obter ajuda com este projeto, sinta-se à vontade para entrar em contato com o mantenedor do projeto ou abrir uma issue no repositório do GitHub.
contato: caiomarcelo.anjos@gmail.com

## Mantenedor
Este projeto é mantido por [Caio Marcelo](https://github.com/seu-usuario).
