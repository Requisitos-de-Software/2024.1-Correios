# Matriz de Rastreabilidade

## Introdução

A matriz de rastreabilidade é uma das técnicas mais comuns para estabelecer referências cruzadas. Ela é implementada por meio de ferramentas de uso geral, como editores de texto ou planilhas eletrônicas. Essas técnicas, centralizadas em referências cruzadas, são simples de entender e utilizar, podendo ser suportadas por hipertextos, esquemas de numeração, indexação ou uso de tags.

A matriz de rastreabilidade consiste em uma tabela que estabelece correspondências entre os requisitos e outros artefatos do projeto. Seu objetivo é registrar as ligações entre as fontes e seus requisitos, componentes e artefatos de software. Essas conexões são especialmente valiosas quando ocorrem alterações no desenho, garantindo um uso adequado da rastreabilidade.

## Objetivo

Este artefato tem como objetivo criar uma matriz para organizar todos os requisitos que foram trabalhados nos documentos de pós-rastreabilidade: <a href="https://github.com/Requisitos-de-Software/2024.1-Correios/blob/main/docs/pos-rastreabilidade/backward-from.md">Backward-from</a> e <a href="https://github.com/Requisitos-de-Software/2024.1-Correios/blob/main/docs/pos-rastreabilidade/forward-from.md">Forward-from</a>. 

## Metodologia

A Tabela/Matriz criada consiste em organizar os requisitos encontrados e relacionar eles com sua respectivas técnicas elicitadas tendo como estrutura as colunas onde o *ID* é uma coluna para identificação dos requisitos, *Descrição* curta sobre o requisito, *Elicitação* mostra por meio de qual técnica os requisitos foram elicitados, *Artefato* é uma referencia para o link do artefarto e *Implementação* é para dizer se os requisitos foram ou não implemntados e por meio disso se podem ou não ser.

<font size="2"><p style="text-align: center">Tabela 1 - Modelo para a Matriz.</p></font>

<center>


| ID | Descrição | Elicitação | Artefato | Implentação | Elos |
| -- | --------- | ---------- | -------- | ---------- | -- |
| RFxx ou RNFxx | texto | abreviatura | link | Sim ou Não | id do elo |

</center> 

<font size="2"><p style="text-align: center">Fonte: [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) e [Pablo S. Costa][PabloGH], 2024.</p></font>

### Legenda

<font size="2"><p style="text-align: center">Tabela 2 - Legendas dos artefatos de requisitos.</p></font>

<center>

| Abreviação    | Descrição                            |
| -------       | ------------------------------------ |
| AD            | Anlise-documental                    |
| BS            | Brainstorming                        |
| OBS           | Observação                           |
| Q             | Questionario                         |
| UC            | Caso de Uso                          |
| CE            | Cenarios                             |
| ES            | Especificação Suplementar            |
| L - LO, LV,LE | Léxico - Objeto, Verbo, Estado       |
| FTF           | First Things First                   |
| INO           | In or Out                            |
| RF            | Requisitos Funcionais                |
| RNF           | Requisitos não Funcionais            |

</center> 

<font size="2"><p style="text-align: center">Fonte: [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes), 2024.</p></font>

## Matriz

### Requisitos Funcionais

<font size="2"><p style="text-align: center">Tabela 3 - Matriz para os Requisitos funcionais presentes no projeto.</p></font>

<center>

| ID | Descrição | Elicitação | Artefato | Implementação | Elos |
| --- | --- | --- | --- | --- | --- |
| RF01 | O usuário deve poder realizar cadastro pelo app | BS01 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Sim | ERF-backword-from01 |
| RF02 | O usuário deve poder realizar login pelo app | BS02, OBS01 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) e [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERF-backword-from02 |
| RF03 | O usuário deve poder acessar o histórico de notificações do objeto | BS03 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERF-backword-from03 |
| RF04 | O usuário deve poder ativar bloqueio do aplicativo em caso de furto | BS04 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERF-backword-from04 |
| RF05 | O usuário deve ter a opção de utilização de chip de localização | BS05 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERF-backword-from05 |
| RF06 | O usuário deve visualizar a estipulação de prazo de entrega | BS06 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Sim | ERF-backword-from06 |
| RF07 | O usuário deve visualizar a atualização do prazo de entrega | BS07 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERF-backword-from07 |
| RF08 | O usuário deve ter acesso a uma aba para contatos das empresas | BS08 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERF-backword-from08 |
| RF09 | O usuário deve receber notificação push pelo aplicativo | BS09 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Sim | ERF-backword-from09 |
| RF10 | O usuário deve receber notificação SMS | BS10 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Sim | ERF-backword-from10 |
| RF11 | O usuário deve receber notificação pelo Whatsapp | BS11 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERF-backword-from11 |
| RF12 | O usuário deve ter acesso a um Chatbot para suporte ao cliente | BS12 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERF-backword-from12 |
| RF13 | O usuário deve poder visualizar um tutorial para realizar o rastreamento | BS13 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERF-backword-from13 |
| RF14 | O usuário deve poder receber o status pelo WhatsApp | BS14 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERF-backword-from14 |
| RF15 | O usuário deve poder aumentar e diminuir a fonte | BS15 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERF-backword-from15 |
| RF16 | O usuário deve ter a opção de ser redirecionado a um atendente | BS16 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERF-backword-from16 |
| RF17 | O usuário deve ter acesso a uma página de FAQ | BS17 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERF-backword-from17 |
| RF18 | O usuário deve poder visualizar sua encomenda no mapa | BS18 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERF-backword-from18 |
| RF19 | O usuário deve poder visualizar detalhes da situação do produto | BS19 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Sim | ERF-backword-from19 |
| RF20 | O usuário deve poder realizar o rastreio por código mais simples | BS20, OBS02 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) e [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Não | ERF-backword-from20 |
| RF21 | O usuário deve poder realizar o rastreio por QR Code | BS21 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Sim | ERF-backword-from21 |
| RF22 | O usuário deve receber notificação pelo e-mail | BS22 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERF-backword-from22 |
| RF23 | O usuário deve poder realizar o pagamento de impostos/taxas | BS23, Q06 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) e [Questionário](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/) | Não | ERF-backword-from23 |
| RF24 | O usuário deve poder realizar a simulação de envio | BS24 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Sim | ERF-backword-from24 |
| RF25 | O aplicativo permite rastreamento de encomendas por código | OBS02, BS20 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) e [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Sim | ERF-backword-from25 |
| RF26 | O aplicativo permite enviar encomendas (envelope, caixa, cilindro) | OBS03 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERF-backword-from26 |
| RF27 | O aplicativo possibilita ver seus pagamentos | OBS04 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERF-backword-from27 |
| RF28 | O aplicativo oferece uma busca por agências próximas | OBS05 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERF-backword-from28 |
| RF29 | O aplicativo possibilita o cálculo de preços e prazos | OBS06 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERF-backword-from29 |
| RF30 | O aplicativo possibilita a compra de certificados digitais | OBS07 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERF-backword-from30 |
| RF31 | O aplicativo oferece o acompanhamento da sua conta | OBS08 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERF-backword-from31 |
| RF32 | O aplicativo permite visualização de mensagens | OBS09 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERF-backword-from32 |
| RF33 | O aplicativo oferece a visualização de vales postais | OBS10 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERF-backword-from33 |
| RF34 | O aplicativo oferece uma área de busca por objetos perdidos | OBS11 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERF-backword-from34 |
| RF35 | O aplicativo fornece uma área de contato sobre violência contra a mulher | OBS12 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERF-backword-from35 |
| RF36 | As informações na página de rastreio | Q01 | [Questionário](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/) | Sim | ERF-backword-from36 |
| RF37 | Filtrar o tipo de encomenda pelo tipo de entrega | Q02 | [Questionário](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/) | Não | ERF-backword-from37 |
| RF38 | Assistente virtual dos correios | Q03 | [Questionário](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/) | Não | ERF-backword-from38 |
| RF39 | Chat para se comunicar diretamente com o fornecedor e entregador | Q04, Q05 | [Questionário](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/) | Não | ERF-backword-from39 |
| RF40 | Pagamento de tributos e taxas de importação | Q06, BS23 | [Questionário](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/) e [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERF-backword-from40 |
| RF41 | O usuário deve poder escolher a opção de recebimento | AD01 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Não | ERF-backword-from41 |
| RF42 | O usuário deve escolher o método de recebimento em até 3 cliques | AD02 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Não | ERF-backword-from42 |
| RF43 | O sistema deve permitir que o usuário reserve o locker mais próximo | AD03 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Não | ERF-backword-from43 |
| RF44 | O usuário deve ser notificado quando o recebimento for efetuado | AD04 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Não | ERF-backword-from44 |
| RF45 | O usuário deve poder mudar local de recebimento | AD05 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Não | ERF-backword-from45 |
| RF46 | O usuário pode optar por retirar em uma agência ou caixa postal | AD06 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Não | ERF-backword-from46 |
| RF47 | O usuário deve ser capaz de realizar uma pré-postagem | AD09 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Sim | ERF-backword-from47 |
| RF48 | O usuário poderá pagar uma pré-postagem com cartão, boleto ou pix | AD10 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Não | ERF-backword-from48 |
| RF49 | O usuário deve ser capaz de adicionar endereços pré-cadastrados | AD11 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Não | ERF-backword-from49 |
| RF50 | O usuário deve ser perguntado sobre a confirmação de operações críticas | AD12 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Sim | ERF-backword-from50 |
| RF51 | O usuário pode salvar informações do cartão de crédito | AD13 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Sim | ERF-backword-from51 |
| RF52 | O usuário deve ser capaz de consultar achados e perdidos | AD14 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Não | ERF-backword-from52 |
| RF53 | O usuário deve ser capaz de gerenciar e visualizar histórico de situações alfandegárias | AD15, AD16, AD17 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Sim | ERF-backword-from53 |
| RF54 | O usuário deve ser capaz de inserir novas importações | AD18 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Sim | ERF-backword-from54 |
| RF55 | O usuário deve ter acesso a meios de pagamento de taxas | AD19 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Sim | ERF-backword-from55 |
| RF56 | O usuário deve ser notificado sobre atualizações de importações | AD20 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Sim | ERF-backword-from56 |
| RF57 | O usuário deve poder contestar taxas e tributações | AD21 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Sim | ERF-backword-from57 |
| RF58 | O Usuário deve ser capaz de emitir comprovante e DIS | AD22, AD23 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Sim | ERF-backword-from58 |

</center> 

<font size="2"><p style="text-align: center">Fonte: [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) e [Pablo S. Costa][PabloGH], 2024.</p></font>

### Requisitos Não Funcionais

<font size="2"><p style="text-align: center">Tabela 3 - Matriz para os Requisitos Não Funcionais presentes no projeto.</p></font>

<center>

| ID | Descrição | Elicitação | Artefato | Implementação | Elos |
| --- | --- | --- | --- | --- | --- |
| RNF01 | O app deve bloquear as funções em caso de furto/roubo | BS25 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERNF-backword-from01 |
| RNF02 | O app deverá mostrar a localização da entrega em tempo real | BS26 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERNF-backword-from02 |
| RNF03 | O app deverá identificar encomendas através de código QR Code | BS27 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Sim | ERNF-backword-from03 |
| RNF04 | O app deverá identificar encomendas através de um e-mail | BS28 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERNF-backword-from04 |
| RNF05 | O app deverá mostrar informação mais clara e menos poluída na Home | BS29 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERNF-backword-from05 |
| RNF06 | O app deverá mostrar informações de rastreio por email | BS30 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERNF-backword-from06 |
| RNF07 | O app deverá possuir um código de rastreio mais eficiente e simples | BS31 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERNF-backword-from07 |
| RNF08 | O app deverá possuir um sistema de chat bot com opção de redirecionar a um atendente | BS32 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERNF-backword-from08 |
| RNF09 | O app deverá tela de ajuda e pop-up "Precisa de ajuda?" | BS33 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERNF-backword-from09 |
| RNF10 | O app deverá possuir tutoriais e ou melhor informação sobre como rastrear uma encomenda | BS34 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERNF-backword-from10 |
| RNF11 | O app deverá ter um menor delay nas notificações de entrega | BS35 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERNF-backword-from11 |
| RNF12 | O app deverá ter uma melhor acessibilidade | BS36 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Não | ERNF-backword-from12 |
| RNF13 | O app deverá ter uma interface fluída e estável | BS37 | [Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/) | Sim | ERNF-backword-from13 |
| RNF14 | O aplicativo deve manter a privacidade dos dados do usuário | OBS13 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERNF-backword-from14 |
| RNF15 | O sistema de rastreamento de encomendas deve ser rápido e eficiente | OBS14 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERNF-backword-from15 |
| RNF16 | O sistema de envio de encomendas deve ser robusto o suficiente para lidar com diferentes tipos de objetos | OBS15 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERNF-backword-from16 |
| RNF17 | O acesso aos pagamentos deve ser protegido por autenticação do usuário | OBS16 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Não | ERNF-backword-from17 |
| RNF18 | A busca por agências deve ser precisa e baseada na localização do usuário | OBS17 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERNF-backword-from18 |
| RNF19 | O cálculo de preços e prazos de encomendas deve ser preciso e rápido | OBS18 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERNF-backword-from19 |
| RNF20 | A compra de certificados digitais deve ser segura e protegida | OBS19 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERNF-backword-from20 |
| RNF21 | O acompanhamento da conta e recargas devem ser realizados de forma segura e confiável | OBS20 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERNF-backword-from21 |
| RNF22 | A visualização de mensagens deve ser rápida e fácil de usar | OBS21 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERNF-backword-from22 |
| RNF23 | A visualização de vales postais deve ser protegida e acessível apenas pelo usuário autorizado | OBS22 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERNF-backword-from23 |
| RNF24 | A busca por objetos perdidos deve ser eficiente e precisa | OBS23 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERNF-backword-from24 |
| RNF25 | A área de contato sobre violência contra a mulher deve ser sensível e oferecer suporte adequado | OBS24 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERNF-backword-from25 |
| RNF26 | O aplicativo requer uma interface amigável e fácil de usar | OBS25 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERNF-backword-from26 |
| RNF27 | O aplicativo deve funcionar em diferentes sistemas operacionais de smartphones | OBS26 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERNF-backword-from27 |
| RNF28 | O aplicativo deve fornecer notificações sobre o status da entrega | OBS27 | [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) | Sim | ERNF-backword-from28 |
| RNF29 | A opção de filtrar encomendas deve ser de fácil acesso (até 2 frames de ajuda a partir da página de encomendas) | Q07 | [Questionário](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/) | Sim | ERNF-backword-from29 |
| RNF30 | O aplicativo deve notificar o usuário com eficácia (deve enviar uma notificação 100% das vezes em que houver uma atualização sobre qualquer encomenda) | Q08 | [Questionário](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/) | Não | ERNF-backword-from30 |
| RNF31 | As informações sobre o rastreio de encomendas devem ser precisas (fornecem data, hora e local em cada atualização da encomenda) | Q09 | [Questionário](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/) | Sim | ERNF-backword-from31 |
| RNF32 | O usuário deve estar satisfeito com a aplicação (Caso seja solicitado, mais de 70% dos usuários devem atribuir uma nota igual ou maior que 3 - em uma escala de 1 a 5 - ao recomendar o aplicativo dos Correios a um amigo) | Q10 | [Questionário](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/) | Sim | ERNF-backword-from32 |
| RNF33 | A opção de rastrear encomendas deve ser de fácil acesso (deve estar na página principal e o usuário não deve demorar mais de 2 minutos para achá-la) | Q11 | [Questionário](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/) | Sim | ERNF-backword-from33 |
| RNF34 | O chat com o entregador deve ser confiável (as mensagens devem ser arquivadas por um período de até 1 ano) | Q12 | [Questionário](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/) | Não | ERNF-backword-from34 |
| RNF35 | A interface deve ser intuitiva para fácil realização do procedimento | AD07 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Não | ERNF-backword-from35 |
| RNF36 | A funcionalidade deve ser de fácil acesso pela página principal | AD08 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Não | ERNF-backword-from36 |
| RNF37 | As informações devem ser atualizadas em tempo de execução | AD24 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Sim | ERNF-backword-from37 |
| RNF38 | A liberação das encomendas deve ser automática | AD25 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Sim | ERNF-backword-from38 |
| RNF39 | Sempre que presente o documento destinatário na encomenda, as importações devem ser inseridas automaticamente | AD26 | [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/) | Sim | ERNF-backword-from39 |

</center> 

<font size="2"><p style="text-align: center">Fonte: [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) e [Pablo S. Costa][PabloGH], 2024.</p></font>

## Bibliografia

> 1. SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 22 de julho de 2024.
> 

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| 1.0  | 24/06/2024 | Criação do documento | [Pablo S. Costa](https://github.com/pabloheika) e [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes)| [Elias F. Oliveira][EliasGH] |


[ClaudioGH]: https://github.com/claudiohsc
[DaniloGH]: https://github.com/Danilo-Carvalho-Antunes
[EliasGH]: https://github.com/EliasOliver21
[GabrielBGH]: https://github.com/Bertolazi
[GabrielFGH]: https://github.com/MMcLovin
[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo

