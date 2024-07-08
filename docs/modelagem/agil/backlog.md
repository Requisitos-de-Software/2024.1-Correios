# Backlogs

## Introdução

A metodologia ágil é uma abordagem flexível de gestão de projetos que foca na colaboração, adaptação e entrega contínua de valor ao cliente. Dentro dessa metodologia, o Product Backlog é fundamental, pois é uma lista priorizada de requisitos, funcionalidades e tarefas a serem executadas no projeto ou produto. Ele destaca a divisão de grandes tarefas em temas, épicos e histórias de usuário.

## Metodologia

A metodologia utilizada para a definição do Backlog da nossa equipe baseia-se nos [requisitos elicitados](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/requisitos_elicitados/). A partir desses requisitos, é possível agrupá-los e dividi-los em três grupos:: [Temas](#temas), [Épicos](#épicos) e [Histórias do Usuário](https://requisitos-de-software.github.io/2024.1-Correios/modelagem/agil/historias_de_usuario).Os Temas são conjuntos de épicos que se relacionam de alguma forma, enquanto os Épicos são grandes partes do trabalho que, por sua vez, são divididos em tarefas menores, chamadas Histórias de Usuário.

A partir dessa divisão, na Tabela 1, é possível ver os temas, épicos, histórias de usuário e a prioridade de cada história de usuário.

## **Temas**

* **Tema 1:** Rastreamento de Encomendas
    - Agrupa as funcionalidades de rastreio de encomendas e a forma como o usuário pode visualizar isso.

* **Tema 2:** Envio de Encomendas
    - Agrupa as funcionalidades referentes a postagem de encomendas e simulação de preços e prazos de envio.

* **Tema 3:** Notificações e Alertas
    - Esse tema reúne as funcionalidades que notificam e alertam o usuário sobre as encomendas.

* **Tema 4:** Suporte e Ajuda ao Usuário
    - Esse tema refere-se a todas as funcionalidades que promovem algum tipo de auxílio ao usuário do aplicativo.

* **Tema 5:** Serviços de Pagamento e Importação
    - Agrupa as funcionalidades de pagamentos de taxas/impostos e informações sobre importações.

* **Tema 6:** Cadastro e Login
    - Esse tema reúne as funcionalidades responsáveis pelo Login e Cadastro do usuário na aplicação.

* **Tema 7:** Busca e Contato
    - Agrupa as funcionalidades de busca e de contato de relevância para o usuário.


## **Épicos**

**EP01 - Rastreamento no Mapa**

Eu, como usuário, desejo visualizar minha encomenda no mapa para acompanhar sua localização em tempo real.


**EP02 - Informações de Entrega**

Eu, como usuário, desejo visualizar as atualizações do prazo de entrega para estar ciente de variações no tempo de entrega da minha encomenda.

**EP03 - Cálculo de Preços e Prazos**

Eu, como usuário, desejo calcular os preços e prazos de encomendas nacionais e internacionais para planejar minhas remessas.

**EP04 - Realizar uma pré-postagem**

Eu, como usuário, desejo realizar uma pré-postagem para agilizar o envio em uma agência dos Correios.

**EP05 - Alterar recebimento de encomendas**

Eu, como usuário, desejo alterar o recebimentos das minhas encomendas para mudar o endereço de entrega e receber em outro local.

**EP06 - Histórico de Notificações**

Eu, como usuário, desejo acessar o histórico de notificações do objeto para revisar as atualizações de status da minha encomenda.


**EP07 - Notificações Multicanais**

Eu, como usuário, desejo receber notificações por múltiplos canais, como WhatsApp e e-mail, para estar informado sobre o status da minha encomenda.

**EP08 - Chatbot e Suporte ao Cliente**

Eu, como usuário, desejo acessar um chatbot para suporte ao cliente para obter ajuda rápida e eficiente.

**EP09 - FAQ e Tutoriais**

Eu, como usuário, desejo acessar uma página de FAQ e tutoriais para encontrar respostas e orientações sobre o rastreamento e outros serviços.

**EP10 - Pagamento de Taxas e Impostos**

Eu, como usuário, desejo realizar o pagamento de impostos e taxas de importação pelo aplicativo para facilitar o processo de liberação da minha encomenda.

**EP11 - Cadastro e Login**

Eu, como usuário, desejo realizar cadastro e login no aplicativo para acessar funcionalidades personalizadas e seguras.

**EP12 - Busca e Contato**

Eu, como usuário, desejo buscar agências próximas e acessar contatos das empresas que postaram a encomenda para obter informações adicionais e suporte.

### Modelo da tabela:
<p align="center" > <strong> Tabela 1 - </Strong>Modelo do backlog</font> <gitbr></p>

|Tema|Épico|Histórias de Usuário|ID História de usuário|Rastreabilidade|
|:--:|:--:|:--:|:--:|:--:|
|Nome do Tema|Nome do épico|História de Usuário|identificador da História de Usuário|Código do requisito referente a História de usuário|

<font size="3"><p style="text-align: center">Fonte: [Danilo Carvalho Antunes](https://github.com/Danilo-Carvalho-Antunes) & [Claudio Henrique][ClaudioGH], 2024</p></font>

## Backlog

<p align="center" > <strong> Tabela 2 - </strong>Backlog</font></p>

|Tema|Épico|Histórias de Usuário|ID História de Usuário|Rastreabilidade|
|:--:|:--:|:--:|:--:|:--:|
|Rastreamento de Encomendas|EP01 - Rastreamento no Mapa |Visualizar Encomenda no Mapa|US01| RF18|
|Rastreamento de Encomendas|EP01 - Rastreamento no Mapa|Atualização de Localização em Tempo Real|US02| RF18|
|Rastreamento de Encomendas|EP02 - Informações de Entrega|Atualização de Prazo de Entrega|US03| RF07|
|Rastreamento de Encomendas|EP02 - Informações de Entrega|Estipulação de Prazo de Entrega|US04| RF06|
| Envio de Encomendas |EP03 - Cálculo de Preços e Prazos| Simular Preços e prazos de Encomendas Nacionais e Internacionais |US05| RF30|
| Envio de Encomendas |EP04 - Realizar uma pré-postagem| Realizar nova Postagem |US06| RF49|
| Envio de Encomendas |EP04 - Realizar uma pré-postagem| Realizar pagamento da Postagem |US07| RF50|
| Envio de Encomendas |EP05 - Alterar recebimento de encomendas| Alterar Endereço de Entrega |US08| RF47|
| Envio de Encomendas |EP05 - Alterar recebimento de encomendas| Reservar um locker |US09| RF45|
| Notificações e Alertas |EP06 - Histórico de Notificações| Acessar Histórico de Notificações |US10| RF03|
| Notificações e Alertas |EP07 - Notificações Multicanais| Receber Notificações por WhatsApp |US11| RF11|
| Notificações e Alertas |EP07 - Notificações Multicanais| Receber Notificações por E-mail |US12| RF22|
| Suporte e Ajuda ao Usuário |EP08 - Chatbot e Suporte ao Cliente| Acessar Chatbot para Suporte |US13| RF12|
| Suporte e Ajuda ao Usuário |EP09 - FAQ e Tutoriais| Acessar Página de FAQ |US14| RF17|
| Suporte e Ajuda ao Usuário |EP09 - FAQ e Tutoriais| Visualizar Tutorial de Rastreamento |US15| RF13|
| Serviços de Pagamento e Importação |EP10 - Pagamento de Taxas e Impostos| Realizar Pagamento de Impostos|US16| RF23|
| Cadastro e Login |EP11 - Cadastro e Login| Realizar Cadastro no Aplicativo|US17| RF01|
| Cadastro e Login |EP11 - Cadastro e Login| Realizar Login no Aplicativo|US18| RF25|
| Busca e Contato |EP12 - Busca e Contato| Buscar Agências Próximas |US19| RF29|
| Busca e Contato |EP12 - Busca e Contato| Acessar Contatos das Empresas |US20| RF08|
| Busca e Contato |EP12 - Busca e Contato| Buscar Objetos Perdidos |US21| RF53|
| Busca e Contato |EP12 - Busca e Contato|Acessar Área de Contato sobre Violência contra a Mulher |US22| RF36|



<font size="3"><p style="text-align: center">Fonte: [Danilo Carvalho Antunes](https://github.com/Danilo-Carvalho-Antunes) & [Claudio Henrique][ClaudioGH], 2024</p></font>

## Bibliografia

> Economia-DF. Backlog. Grupo Economia-DF da disciplina Requisitos de Software, dispoível em: <https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/agil/backlog/>. Acesso em: 24 de maio de 2024.
>
> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 015): Elicitação, Modelagem e Análise. UnB Gama, Brasília, 2024. Disponível em: https://aprender3.unb.br/pluginfile.php/2845040/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf Acesso em: 24/05/2024.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| `1.0`  | 25/05/2024 | Criação do documento | [Claudio Henrique][ClaudioGH] & [Danilo Carvalho][DaniloGH]| [Gabriel F. J. Silva][GabrielFGH]  |


[ClaudioGH]: https://github.com/claudiohsc
[DaniloGH]: https://github.com/Danilo-Carvalho-Antunes
[EliasGH]: https://github.com/EliasOliver21
[GabrielBGH]: https://github.com/Bertolazi
[GabrielFGH]: https://github.com/MMcLovin
[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo
