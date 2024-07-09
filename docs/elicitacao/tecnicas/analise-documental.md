# Análise Documental

## Introdução

A análise de documentos na elicitação de requisitos é uma técnica que envolve a revisão sistemática de documentação existente, tanto impressa quanto digital, identificando as necessidades de um projeto. Este método analítico requer a examinação e interpretação dos dados para derivar significados, compreensões e desenvolvimento de conhecimento empírico.

O processo começa com uma análise preliminar para selecionar os documentos mais relevantes. Entre os tipos de documentos comumente analisados estão: Documentação já existente do sistema; Documentos de outros projetos relacionados; Legislação aplicável; Editais; Planos de negócios; Contratos (Retraining Requirements Enginereeing, 2024).

## Metodologia

A partir da análise documental do projeto realizado pelo Grupo 03 da disciplina de Interação Humano-Computador, foram identificadas funcionalidades presentes no site dos correios (realizar uma pré-postagem, receber encomendas, gerenciar importações e busca por documentos perdidos) que estavam implementadas no aplicativo e passaram desapercebidas pelas técnicas de elicitação utilizadas até então ([Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/), [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) e [Questionário](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/)) e outras que não estavam implementadas no aplicativo. 

Com isso, foram elicitados requisitos relacionados às respectivas funcionalidades, seguindo a estrutura proposta por Vazquez et. al (2016), em que, presente na Tabela 02, temos uma pergunta que queremos responder, uma resposta à ela, o requisito proveniente dessa resposta e também adicionamos o ID desse requisito dentro desse artefato,o seu tipo e versão, cada seção de requisitos elicitados está separada em *tabs* que permitem vizualizar a evolução de versões de cada requisito, onde apenas os requisitos que sofreram alterações estão presentes nas versões subsequentes. Ao final da página, também temos as Tabelas 8 e 9 que, respectivamente, agrupam os requisitos funcionais e não-funcionais elicitados, em suas versões mais atuais.

Na Tabela 1 abaixo, temos os documentos analisados junto a suas versões e as datas dessas versões

<font size="2"><p style="text-align: center"><b>Tabela 1</b>: Documentos analisados. </p></font>

<center>

| Artefato | Versão | Data |
| -------- | :----: | :--: |
| [Análise Hieraquica de Tarefas (HTA)](https://interacao-humano-computador.github.io/2024.1-Correios/analise_de_requisitos/analise_tarefas/hta/) | `1.0` | 05/05/2024 |
| [CMN-GOMS ](https://interacao-humano-computador.github.io/2024.1-Correios/analise_de_requisitos/analise_tarefas/cmn_goms/) | `1.0` | 05/05/2024 |

</center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024 </p></font>

## Requisitos Elicitados

Legenda para as Tabelas:

- RF: Requisito Funcional
- RNF: Requisito Não-Funcional
- ADxx: Requisito nºx elicitado pelo questionário.


<font size="2"><p style="text-align: center"><b>Tabela 2</b>: Modelo de estrutura. </p></font>

<center>

| Pergunta | Respondida | Requisito elicitado | ID | Tipo | Versão | 
| -------- | ---------- | ------------------- | -- | ---- | ------ |
| Pergunta levantada para o requisito. | A pergunta foi respondida? Sim/Não | Expecificação do requisito. | Identificação do requisito. | Tipo do requisito. | Versão Atual | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel B. Bertolazi](https://github.com/Bertolazi) e [Pablo S. Costa][PabloGH], 2024 </p></font>


### Recebimento de encomendas

Abaixo, na Tabela 3, estão os requisitos elicitados para  o Recebimento de encomendas.

=== "`1.0`"

    <center>

    <font size="2"><p style="text-align: center"><b>Tabela 3</b>: Requisitos elicitados para o Recebimento de encomendas. </p></font>

    | Pergunta | Respondida | Requisito elicitado | ID | Tipo | Versão |
    | -------- | ---------- | ------------------- | -- | ---- | ------ |
    | Qual a importância da funcionalidade em questão? | Sim | O usuário deve conseguir mudar a opção de recebimento dentro do aplicativo, antes que sua encomenda seja enviada. | AD01 | RF | `1.0` | 
    | Essa funcionalidade tem opções dentro dela? | sim | O usuário deve poder escolher o método de recebimento em até 3 cliques desde iniciar a ação. | AD02 | RNF | `1.0` |
    | O usuário é avisado quando a entrega é realizada? | Sim | O usuário deve ser notificado quando o recebimeto for efetuado. | AD03 | RF | `1.0` |
    | A opção de locker é útil? | Sim | O sistema deve permitir que o usuário reserve o locker mais perto de sua casa baseado no CEP informado, de acordo com a disponibilidade | AD04 | RF | `1.0` |
    | É possível mudar o endereço de entrega de uma encomenda? | sim | O usuário deve poder mudar local de de rebimento da encomenda | AD05 | RF | `1.0` |
    | Existem outras opções sem ser residencial ou locker | Sim | O usuário pode optar por retirar em uma agência ou caixa postal | AD06 | RF | `1.0` |
    | Essa funcionalidade já existe no site, sua interface é útil? | Sim | Os ícones de opção dentro dessa funcionalidade devem ser 44x44 pixels, para melhor visualização de cada um dos ícones para pessoas com leves problemas visuais. | AD07 | RNF | `1.1` |
    | É simples achar essa funcionalidade no site? | Sim | A funcionalidade deve ser aparente na página principal. | AD08 | RNF | `1.1` |

    <font size="2"><p style="text-align: center">Fonte: [Gabriel B. Bertolazi](https://github.com/Bertolazi), 2024 </p></font>

    </center>

=== "`1.1`"

    <center>

    <font size="2"><p style="text-align: center"><b>Tabela 3</b>: Requisitos elicitados para o Recebimento de encomendas. </p></font>

    | Pergunta | Respondida | Requisito elicitado | ID | Tipo | Versão |
    | -------- | ---------- | ------------------- | -- | ---- | ------ |
    | Essa funcionalidade tem opções dentro dela? | Sim | O usuário deve poder mudar o método de recebimento em até 3 cliques desde iniciar a ação. | AD02 | RNF | `1.1` |
    | É possível mudar o endereço de entrega de uma encomenda? | Sim | O usuário deve poder mudar local de de rebimento da encomenda, antes que a mesma tenha sido enviada. | AD05 | RF | `1.1` |
    | Essa funcionalidade já existe no site, sua interface é útil? | Sim | Os ícones de opção dentro dessa funcionalidade devem ser 44x44 pixels, para melhor visualização de cada um dos ícones para pessoas com leves problemas visuais. | AD07 | RNF | `1.1` |
    | É simples achar essa funcionalidade no site? | Sim | A funcionalidade deve ser aparente na página principal. | AD08 | RNF | `1.1` |

    <font size="2"><p style="text-align: center">Fonte: [Gabriel B. Bertolazi](https://github.com/Bertolazi), 2024 </p></font>

    </center>

### Realizar uma pré-postagem

Na Tabela 4 estão os requisitos elicitados para a funcionalidade de Pré-postagem.

=== "`1.0`"
    <font size="2"><p style="text-align: center"> <b>Tabela 4</b>: Requisitos elicitados para realizar uma pré-postagem.</p></font>

    <center>

    | Pergunta| Respondida | Requisito elicitado | ID | Tipo | Versão |
    | ------- | ---------- | ------------------- | -- | ---- | ------ |
    | O usuário é capaz de realizar, no aplicativo, a funcionalidade presente no site?  | Sim | O usuário deve ser capaz de realizar uma pré-postagem pelo aplicativo | AD09 | RF | `1.0` |
    | O usuário é capaz de realizar, no aplicativo, a funcionalidade presente no site?  | Sim | O usuário deve ser capaz de gerenciar o carrinho de pré-postagens, podendo adicionar ou excluir uma pré-postagem | AD10 | RF | `1.0` |
    | O usuário possui mais de um meio de pagamento para a pré-postagem?  | Não | O usuário poderá pagar uma pré-postagem com cartão de crédito, boleto ou pix | AD11 | RF | `1.0` |
    | O usuário é capaz de escolher endereços pré-cadastrados para os campoos de remetente e destinatário? | Não | O usuário deve ser capaz de adicionar endereços pré-cadastrados ao preencher uma pré-postagem | AD12 | RF | `1.0` |
    | O aplicativo protege o usuário em operações criticas como exclusão de itens?  | Sim | O usuário deve ser perguntado sobre a confirmação de operações importantes como exclusão de itens do carrinho | AD13 | RNF | `1.0` |
    | O aplicativo agiliza o processo de realizar pagamento com cartão de crédito?  | Sim | O usuário pode escolher salvar as informações do cartão de crédito para pagamentos futuros | AD14 | RF | `1.0` |

    </center>

    <font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024 </p></font>


### Busca por documentos perdidos

Na Tabela 5 estão os requisitos elicitados para a funcionalidade de Busca por documentos perdidos.

=== "`1.0`"
    <font size="2"><p style="text-align: center"><b>Tabela 5</b>: Requisitos elicitados para a Busca por documentos perdidos. </p></font>

    <center>

    | Pergunta | Respondida | Requisito elicitado | ID | Tipo | Versão |
    | -------- | ---------- | ------------------- | -- | ---- | ------ |
    | O aplicativo fornece algum meio de localização de documentos perdidos? | Não | O usuário deve ser capaz de consultar uma seção de achados e perdidos para encontrar documentos | AD15 | RF | `1.0` |

    </center>

    <font size="2"><p style="text-align: center">Fonte: [Danilo Carvalho][DaniloGH], 2024 </p></font>


### Minhas importações

Na Tabela 6 estão os requisitos elicitados para a funcionalidade de Minhas Importações.

=== "`1.0`"

    <font size="2"><p style="text-align: center"><b>Tabela 6</b>: Requisitos elicitados para o Minhas Importações. </p></font>

    <center>

    | Pergunta | Respondida | Requisito elicitado | ID | Tipo | Versão |
    |----------|------------|---------------------|----|--------| ------ |
    | Como o usuário deseja organizar suas importações no sistema? Quais informações específicas o usuário precisa rastrear para cada importação? | Sim | O Usuário deve ser capaz de gerenciar suas importações? | AD16 | RF | `1.0` |
    | Quais tipos de problemas ou questões alfandegárias o usuário pode encontrar? Como o usuário espera resolver essas situações? | Sim | O Usuário deve ser capaz de resolver situações alfandegárias | AD17 | RF | `1.0` |
    | O usuário deseja visualizar um histórico completo de todas as situações anteriores? Quais detalhes específicos o usuário gostaria de ver no histórico? | Sim | O usuário deve ser capaz de visualizar histórico de situações alfandegárias | AD18 | RF | `1.0` |
    | Como o usuário pretende adicionar novas importações ao sistema? Quais campos ou informações são essenciais para cada nova importação? | Sim | O usuário deve ser capaz de inserir novas importações | AD19 | RF | `1.0` |
    | Quais métodos de pagamento o usuário espera encontrar no aplicativo? O usuário precisa de informações detalhadas sobre como efetuar os pagamentos? | Sim | O usuário deve ter acesso a meios de pagamento de taxas | AD20 | RF | `1.0` |
    | Como o usuário deseja ser notificado sobre mudanças em suas importações? Quais eventos específicos devem acionar uma notificação? | Sim | O usuário deve ser notificado sobre atualizações de importações | AD21 | RF | `1.0` |
    | Quais procedimentos o usuário gostaria de seguir para contestar taxas? Quais documentos ou evidências o usuário pode fornecer durante o processo de contestação? | Sim | O usuário deve poder contestar taxas e tributações | AD22 | RF | `1.0` |
    | Como deve ser a comprovação da situação da encomenda? | Sim | O Usuário deve ser capaz de emitir comprovante | AD23 | RF | `1.0` |
    | O usuário precisa de comprovantes impressos ou digitais? Quais informações devem constar nos comprovantes? | Sim | O usuário deve ser capaz de emitir DIS | AD24 | RF | `1.0` |
    | O usuário precisa de prontidão nas informações alfandegarias? | Sim | As informações devem ser atualizadas em tempo de execução | AD25 | RNF | `1.0` |
    | Quanto tempo leva para receber uma importação? | Sim | A liberação das encomendas deve ser automática | AD26 | RNF | `1.0` |
    | As encomendas costumam ter o documento pessoal ou empresarial? | Sim | Sempre que presente o documento destinatário na encomenda, as importações devem ser inseridas automaticamente | AD27 | RNF | `1.0` |

    </center>

    <font size="2"><p style="text-align: center">Fonte: [Pablo S. Costa][PabloGH], 2024 </p></font>

=== "`1.1`"

    <font size="2"><p style="text-align: center"><b>Tabela 6</b>: Requisitos elicitados para o Minhas Importações. </p></font>

    <center>

    | Pergunta | Respondida | Requisito elicitado | ID | Tipo | Versão |
    | --- | --- | --- | --- | --- | --- |
    | Como o usuário deseja organizar suas importações no sistema? Quais informações específicas o usuário precisa rastrear para cada importação? | Sim | O Usuário deve ser capaz de gerenciar suas importações em um só local? | AD16 | RF | `1.1` |
    | O usuário precisa de prontidão nas informações alfandegarias? | Sim | As informações devem ser atualizadas em tempo abaixo de 300ms | AD25 | RNF | `1.1` |
    | O usuário sempre quer a encomenda? | Sim | O usuário deve poder desistir do pacote. | AD32 | RF | `1.1` |
    | O precisa de um resumo da importação? | Sim | O usuário deve poder ver o status da importação. | AD33 | RF | `1.1` |

    </center>

    <font size="2"><p style="text-align: center">Fonte: [Pablo S. Costa][PabloGH], 2024 </p></font>


### Loja Online

Na Tabela 7 estão os requisitos elicitados para a loja online dos correios.

=== "1.0"

    <font size="2"><p style="text-align: center"><b>Tabela 7</b>: Requisitos elicitados para a loja online. </p></font>

    <center>

    | Pergunta | Respondida | Requisito elicitado | ID | Tipo | Versão |
    |----------|------------|---------------------|----|--------| -|
    |O usuário é avisado de quantos itens tem-se em estoque para realizar a compra?|Não|O usuário deveria ser informado da quantidade de itens disponíveis para realizar a sua compra.| AD28 |RNF| `1.0` |
    |O usuário tem uma boa experiência de utilização da loja online.|Sim|A utilização da loja deveria ser intuitiva e simples, para uma boa interação e experiência do usuário.| AD29 |RF| `1.0` |
    |O usuário consegue editar as suas informações de envio sem precisar retornar ao carrinho de compras? |Não|O usuário deve poder ter a total liberdade de editar suas informações e transitar pelas etapas que o sistema oferece. | AD30 |RF| `1.0` |

    </center>

    <font size="2"><p style="text-align: center">Fonte: [Elias F. Oliveira][EliasGH], 2024 </p></font>

=== "1.1"

    <font size="2"><p style="text-align: center"><b>Tabela 7</b>: Requisitos elicitados para a loja online. </p></font>

    <center>

    | Pergunta | Respondida | Requisito elicitado | ID | Tipo | Versão | 
    |----------|------------|---------------------|----|--------| - |
    |O usuário é avisado de quantos itens tem-se em estoque para realizar a compra?|Não|O usuário deveria ser informado da quantidade de itens disponíveis para realizar a sua compra.| AD28 |RNF| `1.1` |
    | O usuário possui uma opção para filtragem dos itens? | Não | A busca por itens deve ser o mais otimizada possível, com o usuário tendo a opção de filtragem para simplificar e diminuir o tempo de busca por produtos que antes se apresentariam em uma categoria única.| AD29 |RF| `1.1` |
    |O usuário consegue editar as suas informações de envio sem precisar retornar ao carrinho de compras? |Não|O usuário deve poder ter a total liberdade de editar suas informações e transitar pelas etapas que o sistema oferece. | AD30 |RF| `1.1` |
    | O usuário tem uma opção de ordenação dos itens? |Não| O usuário deverá possuir uma opção para ordenar os itens de acordo com seus anceios, como: menor preço, maior preço, maior relevância ou menor. | AD31 |RF| `1.1` |

    </center>

    <font size="2"><p style="text-align: center">Fonte: [Elias F. Oliveira][EliasGH], 2024 </p></font>

### Funcionais

<font size="2"><p style="text-align: center">**Tabela 8**: Requisitos funcionais elicitados. </p></font>


| ID  | Requisito elicitado | Tipo | Implementado | Versão |
| :-: | ------------------- | :--: | :----------: | :----: |
| AD01 | O usuário deve conseguir mudar a opção de recebimento dentro do aplicativo, antes que sua encomenda seja enviada. | RF | Não | `1.0` |
| AD03 | O usuário deve ser notificado quando o recebimento for efetuado. | RF | Não | `1.0` |
| AD04 | O sistema deve permitir que o usuário reserve o locker mais perto de sua casa baseado no CEP informado, de acordo com a disponibilidade | RF | Não | `1.0` |
| AD05 | O usuário deve poder mudar local de recebimento da encomenda, antes que a mesma tenha sido enviada. | RF | Não | `1.1` |
| AD06 | O usuário pode optar por retirar em uma agência ou caixa postal | RF | Não | `1.0` |
| AD09 | O usuário deve ser capaz de realizar uma pré-postagem pelo aplicativo | RF | Sim | `1.0` |
| AD10 | O usuário deve ser capaz de gerenciar o carrinho de pré-postagens, podendo adicionar ou excluir uma pré-postagem | RF | Sim | `1.0` |
| AD11 | O usuário poderá pagar uma pré-postagem com cartão de crédito, boleto ou pix | RF | Não | `1.0` |
| AD12 | O usuário deve ser capaz de adicionar endereços pré-cadastrados ao preencher uma pré-postagem | RF | Não | `1.0` |
| AD14 | O usuário pode escolher salvar as informações do cartão de crédito para pagamentos futuros | RF | Sim | `1.0` |
| AD15 | O usuário deve ser capaz de consultar uma seção de achados e perdidos para encontrar documentos | RF | Não | `1.0` |
| AD16 | O Usuário deve ser capaz de gerenciar suas importações em um só local? | RF | não | `1.1` |
| AD17 | O Usuário deve ser capaz de resolver situações alfandegárias | RF | não | `1.0` |
| AD18 | O usuário deve ser capaz de visualizar histórico de situações alfandegárias | RF | não | `1.0` |
| AD19 | O usuário deve ser capaz de inserir novas importações | RF | não | `1.0` |
| AD20 | O usuário deve ter acesso a meios de pagamento de taxas | RF | não | `1.0` |
| AD21 | O usuário deve ser notificado sobre atualizações de importações | RF | não | `1.0` |
| AD22 | O usuário deve poder contestar taxas e tributações | RF | não | `1.0` |
| AD23 | O Usuário deve ser capaz de emitir comprovante | RF | não | `1.0` |
| AD24 | O usuário deve ser capaz de emitir DIS | RF | não | `1.0` |
| AD29 | A busca por itens deve ser o mais otimizada possível, com o usuário tendo a opção de filtragem para simplificar e diminuir o tempo de busca por produtos que antes se apresentariam em uma categoria única. | RF | Não | `1.1` |
| AD30 | O usuário deve poder ter a total liberdade de editar suas informações e transitar pelas etapas que o sistema oferece. | RF | Não | `1.1` |
| AD31 | O usuário deverá possuir uma opção para ordenar os itens de acordo com seus anseios, como: menor preço, maior preço, maior relevância ou menor. | RF | Não | `1.1` |
| AD32 | O usuário deve poder desistir do pacote. | RF | não | `1.0` |
| AD33 | O usuário deve poder ver o status da importação. | RF | não | `1.0` |

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024 </p></font>

### Não-funcionais

<font size="2"><p style="text-align: center">**Tabela 9**: Requisitos não-funcionais elicitados. </p></font>

| ID  | Requisito elicitado | Tipo | Implementado | Versão |
| :-: | ------------------- | :--: | :----------: | :----: |
| AD02 | O usuário deve poder mudar o método de recebimento em até 3 cliques desde iniciar a ação. | RNF | Não | `1.1` |
| AD07 | Os ícones de opção dentro dessa funcionalidade devem ser 44x44 pixels, para melhor visualização de cada um dos ícones para pessoas com leves problemas visuais. | RNF | Não | `1.1` |
| AD08 | A funcionalidade deve ser aparente na página principal. | RNF | Não | `1.1` |
| AD13 | O usuário deve ser perguntado sobre a confirmação de operações importantes como exclusão de itens do carrinho | RNF | Sim | `1.0` |
| AD25 | As informações devem ser atualizadas em tempo abaixo de 300ms | RNF | não | `1.1` |
| AD26 | A liberação das encomendas deve ser automática | RNF | não | `1.0` |
| AD27 | Sempre que presente o documento destinatário na encomenda, as importações devem ser inseridas automaticamente | RNF | não | `1.0` |

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024 </p></font>

## Referências
> 1. Retraining Requirements Enginereeing. Análise de Documentos, 2024. Disponível em: https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-analise-de-documentos. Acesso em: 20 de maio de 2024.
> 2. Vazquez, Carlos. Simões, Guilherme. Engenharia de Requisitos. Brasport, 2016. Disponível em: .Acesso em: 20 de maio de 2024

## Bibliografia

> 1. GitHub. Disponível em: [https://docs.github.com/pt](https://docs.github.com/pt). Acesso em: 20 de Maio de 2024.
>
> 2. Microsoft Teams. Disponível em: [https://www.microsoft.com/pt-br/microsoft-teams/group-chat-software](https://www.microsoft.com/pt-br/microsoft-teams/group-chat-software). Acesso em: 20 de Maio de 2024.
>
> 3. Grupo 03 de Interação Humano-Computador 2024.1. Projeto do site Correios. Disponível em : [Correios IHC](https://github.com/Interacao-Humano-Computador/2024.1-Correios). Acesso em: 20 de Maio de 2024
>
> 4. Retraining Requirements Enginereeing. Análise de Documentos, 2024. Disponível em: [URL](https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-analise-de-documentos). Acesso em: 20 de maio de 2024.
>
> 5. Vazquez, Carlos. Simões, Guilherme. Engenharia de Requisitos. Brasport, 2016. Disponível em: .Acesso em: 20 de maio de 2024

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| `1.0`  | 20/05/2024 | Criação do documento | [Gabriel B. Bertolazi][GabrielBGH], [Gabriel F. J. Silva][GabrielFGH] e [Pablo S. Costa][PabloGH]  | [Claudio Henrique](ClaudioGH)  |
| `1.1`  | 21/06/2024 | Complementa metodologia | [Gabriel F. J. Silva][GabrielFGH] |  |
| `1.2`  | 23/06/2024 | Correção e versionamentos de requisitos | [Elias F. Oliveira][EliasGH], [Gabriel B. Bertolazi][GabrielBGH], [Gabriel F. J. Silva][GabrielFGH] e [Pablo S. Costa][PabloGH] |[Claudio Henrique][ClaudioGH]  |
| `1.3`  | 01/07/2024 | Adiciona resuma de req. elicitados | [Gabriel F. J. Silva][GabrielFGH] |   |

[ClaudioGH]: https://github.com/claudiohsc
[DaniloGH]: https://github.com/Danilo-Carvalho-Antunes
[EliasGH]: https://github.com/EliasOliver21
[GabrielBGH]: https://github.com/Bertolazi
[GabrielFGH]: https://github.com/MMcLovin
[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo
