# Especificação Suplementar

## Introdução

A Especificação Suplementar funciona como um documento complementar aos casos de uso, fornecendo uma descrição detalhada, em linguagem natural, dos requisitos do sistema. Ela preenche as lacunas deixadas pelos casos de uso, capturando requisitos adicionais que não foram elicitados no método anterior.

Conteúdo Essencial da Especificação Suplementar:

- Requisitos Legais e Regulatórios: Detalhes sobre as leis, normas e padrões que o sistema deve seguir, incluindo padrões de aplicativos específicos.
- Atributos de Qualidade: Definição dos atributos de qualidade esperados do sistema, como usabilidade, confiabilidade, desempenho e suportabilidade.
- Requisitos Adicionais: Especificação de outros requisitos relevantes, como sistemas operacionais compatíveis, ambientes de execução, requisitos de compatibilidade e restrições de design.

## Metodologia

Para a produção desse artefato será utilizado uma versão modificada do FURPS+, que é uma metodologia na qual os requisitos são dividido nas seguintes categorias: F de Functionality (Funcionalidade), U de Usability (Usabilidade), R de Reliability (Confiabilidade), P de Performance (Desempenho), S de Supportability (Suportabilidade) e + que engloba outros requisitos não-funcionais (Requisitos de design, Requisitos de implementação, Requisitos de interface e Requisitos físicos). Nessa versão os requisitos de interface, além da seção de componentes adquiridos serão omitidos, dado que são atributos já especificados em outros artefatos, como os requisitos não-funcionais elicitados pelas técnicas de Observação, de Questionário e de Brainstorming.

## Funcionalidade

Os requisitos funcionais foram obtidos por meio de uma combinação das seguintes técnicas: [brainstorming](../elicitacao/tecnicas/brainstorming.md), [observação](../elicitacao/tecnicas/observacao.md), [questionário](../elicitacao/tecnicas/questionario.md) e [análise documental](../elicitacao/tecnicas/analise-documental.md). Eles podem ser encontrados no documento de [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md). Além disso, os casos de uso também podem ser considerados como requisitos funcionais.

## Usabilidade

Diz respeito ao quão fácil é para o usuário realizar uma tarefa com a aplicação.

Para essa categoria os requisitos identificados estão representados na tabela 1 a seguir.

<font><p style="text-align: center">**Tabela 1** - Requisitos de Usabilidade.</p></font>

<center>

| ID    | Descrição                                                                                                                                |
| ----- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| USA01 | O app deverá ter uma interface fluída e estável                         |
| USA02 | O sistema de envio de encomendas deve ser robusto o suficiente para lidar com diferentes tipos de objetos      |
| USA03 | A visualização de vales postais deve ser protegida e acessível apenas pelo usuário autorizado                                                                         |
| USA04 | O aplicativo requer uma interface amigável e fácil de usar.                                   |
| USA05 | O aplicativo deve funcionar em diferentes sistemas operacionais de smartphones. |
| USA06 | O aplicativo deve fornecer notificações sobre o status da entrega.      |
| USA07 | O usuário deve estar satisfeito com a aplicação (Caso seja solicitado, mais de 70% dos usuários devem atribuir uma nota igual ou maior que 3 - em uma escala de 1 a 5 - ao recomendar o aplicativo dos Correios a um amigo)      |
| USA08 | O app deverá possuir um sistema de chat bot com opção de redirecionar a um atendente |
| USA09 | O app deverá tela de ajuda e pop-up "Precisa de ajuda?"       |
| USA10 | O app deverá possuir tutoriais e ou melhor informação sobre como rastrear uma encomenda      |
| USA11 | O app deve bloquear as funções em caso de furto/roubo      |

</center>

<font size="3"><p style="text-align: center">Fonte: Fonte: [Danilo Carvalho Antunes][DaniloGH], 2024.</p></font>

## Confiabilidade

Diz respeito ao quão confiável é o sistema, ou seja, qual é a frequência de falhas, possibilidade de recuperação e prevenção e tempo entre as falhas.

Para essa categoria os requisitos identificados estão representados na tabela 2 a seguir.

<font><p style="text-align: center">**Tabela 2** - Requisitos de Confiabilidade.</p></font>

<center>

| ID    | Descrição                                                                                                                         |
| ----- | --------------------------------------------------------------------------------------------------------------------------------- |
| CON01 | O aplicativo deve manter a privacidade dos dados do usuário.                                                                 |
| CON02 | O acesso aos pagamentos deve ser protegido por autenticação do usuário                                                 |
| CON03 | A compra de certificados digitais deve ser segura e protegida                                          |
| CON04 | O acompanhamento da conta e recargas devem ser realizados de forma segura e confiável                            |
| CON05 | A visualização de vales postais deve ser protegida e acessível apenas pelo usuário autorizado                                 |
| CON06 | O chat com o entregador deve ser confiável (as mensagens devem ser arquivadas por um período de até 1 ano)                      |

</center>

<font size="3"><p style="text-align: center">Fonte: Fonte: [Danilo Carvalho Antunes][DaniloGH], 2024.</p></font>

## Desempenho

Diz respeito às condições que os requisitos devem operar. A velocidade, limites superiores e inferiores, tempo de resposta, restrições de interface e de funções, etc.

Para essa categoria os requisitos identificados estão representados na tabela 3 a seguir.

<font><p style="text-align: center">**Tabela 3** - Requisitos de Desempenho.</p></font>

| ID    | Descrição                                                                                          |
| ----- | -------------------------------------------------------------------------------------------------- |
| DES01 | O app deverá mostrar a localização da entrega em tempo real                              |
| DES02 | O app deverá possui um código de rastreio mais eficiente e simples                                     |
| DES03 | O app deverá ter um menor delay nas notificações de entrega                                  |
| DES04 | O sistema de rastreamento de encomendas deve ser rápido e eficiente |
| DES05 | A busca por agências deve ser precisa e baseada na localização do usuário          |
| DES06 | O cálculo de preços e prazos de encomendas deve ser preciso e rápido          |
| DES07 | A visualização de mensagens deve ser rápida e fácil de usar          |
| DES08 | A busca por objetos perdidos deve ser eficiente e precisa          |
| DES09 | O aplicativo requer uma interface amigável e fácil de usar.          |
| DES10 | A opção de filtrar encomendas deve ser de fácil acesso (até 2 frames de ajuda a partir da página de encomendas)          |
| DES11 | O aplicativo deve notificar o usuário com eficácia (deve enviar uma notificação 100% das vezes em que houver uma atualização sobre qualquer encomenda)          |
| DES12 | As informações sobre o rastreio de encomendas devem ser precisas (fornecem data, hora e local em cada atualização da encomenda)          |

<font size="3"><p style="text-align: center">Fonte: [Danilo Carvalho Antunes][DaniloGH], 2024.</p></font>

## Suportabilidade

**Suportabilidade** é a capacidade do software de fornecer suporte, tanto para si próprio quanto para o usuário. Ela engloba várias características importantes:

1. **Testabilidade**: Refere-se à facilidade com que o software pode ser testado. Um sistema testável permite a criação de casos de teste eficazes e a identificação rápida de problemas.

2. **Adaptabilidade**: Diz respeito à capacidade do software de se adaptar a diferentes ambientes, dispositivos ou contextos. Um software adaptável pode funcionar bem em diferentes sistemas operacionais, navegadores ou dispositivos.

3. **Manutenibilidade**: Refere-se à facilidade de manter e atualizar o software. Um sistema de fácil manutenção permite correções de bugs, melhorias e atualizações sem grandes dificuldades.

4. **Compatibilidade**: Envolve a capacidade do software de funcionar bem com outros sistemas, aplicativos ou componentes. Um software compatível pode interagir com outras soluções sem problemas.

5. **Instalabilidade**: Trata da facilidade de instalação do software. Um processo de instalação simples e intuitivo é essencial para uma boa experiência do usuário.

6. **Portabilidade**: Refere-se à capacidade do software de ser executado em diferentes plataformas. Um software portátil pode ser usado em diferentes sistemas operacionais ou arquiteturas sem grandes modificações.

Abaixo temos a tabela 4 que lista os requisitor de suportabilidade.

=== "`2.0`"

    <font><p style="text-align: center">**Tabela 4** - Requisitos de Suportabilidade.</p></font>

    | ID | Descrição | Versão |
    | --- | --- | --- |
    | SU01 | O aplicativo deve funcionar em diferentes sistemas de smartphones Android e IOS, de pelo menos as ultimas duas atualização. | `1.1` |
    | SU02 | O app deverá ter acessibilidade, com mapeamento para leitores de telas do Android e IOS. | `1.1` |
    | SU03 | A aplicação precisa ser responsiva se adaptando para diferentes formatos e tamanhos de tela. | `1.1` |
    | SU04 | O app deverá estar atualizado e disponível nas lojas oficiais de apps do Android e IOS. | `1.1` |
    | SU05 | O app deve conter os dados online para utilização em multiplos dispositivos. | `1.1` |

    <font size="3"><p style="text-align: center">Fonte: [Pablo S. Costa][PabloGH], 2024.</p></font>

=== "`1.0`"

    <font><p style="text-align: center">**Tabela 4** - Requisitos de Suportabilidade.</p></font>

    | ID | Descrição | Versão |
    | --- | --- | --- |
    | SU01 | O app deverá possuir um sistema de chat bot com opção de redirecionar a um atendente. | `1.0` |
    | SU02 | O app deverá ter tela de ajuda e pop-up "Precisa de ajuda?". | `1.0` |
    | SU03 | O app deverá possuir tutoriais e ou melhor informação sobre como rastrear uma encomenda | `1.0` |
    | SU04 | O app deverá ter uma melhor acessibilidade. | `1.0` |
    | SU05 | O app deverá ter uma interface fluída e estável. | `1.0` |
    | SU06 | O aplicativo requer uma interface amigável e fácil de usar. | `1.0` |
    | SU07 | O aplicativo deve funcionar em diferentes sistemas operacionais de smartphones. | `1.0` |
    | SU08 | A interface deve ser intuitiva para fácil realização do procedimento. | `1.0` |

    <font size="3"><p style="text-align: center">Fonte: [Pablo S. Costa][PabloGH], 2024.</p></font>

## + Ajuda e Documentação

A seção de Ajuda e Documentação de um aplicativo é composta por uma série de recursos projetados para instruir e informar os usuários acerca da operação, funcionalidades e práticas recomendadas para o uso do aplicativo. Esta parte é essencial para assegurar que os usuários consigam empregar o aplicativo eficientemente, esclarecer incertezas e extrair o máximo proveito de suas capacidades. Na tabela 5 temos os requitos elicitados para tal.

=== "`2.0`"

    <font><p style="text-align: center">**Tabela 5** - Requisitos + Ajuda e Documentação.</p></font>

    | ID | Descrição | Versão |
    | --- | --- | --- |
    | AD01 | O sistema de chat bot com opção de redirecionar a um atendente, deve ser de fácil acesso em menos de 2min. | `1.1` |
    | AD02 | A  tela de ajuda e pop-up "Precisa de ajuda?", deve ser de fácil acesso em menos de 2min. | `1.1` |
    | AD03 | Os tutoriais devem cobrir 80% das funções dentro do app. | `1.1` |
    | AD04 | As informações sobre o rastreio de encomendas devem ser precisas (fornecem data, hora e local em cada atualização da encomenda) | `1.0` |
    | AD05 | O chat com o entregador deve ser confiável (as mensagens devem ser arquivadas por um período de até 1 ano) | `1.0` |
    | AD06 | O app deve ser compatível com os mecanismos de leitura de tela do android e do IOS. | `1.1` |

    <font size="3"><p style="text-align: center">Fonte: [Pablo S. Costa][PabloGH], 2024.</p></font>

=== "`1.0`"

    <font><p style="text-align: center">**Tabela 5** - Requisitos + Ajuda e Documentação.</p></font>

    | ID | Descrição | Versão |
    | --- | --- | --- |
    | AD01 | O app deverá possuir um sistema de chat bot com opção de redirecionar a um atendente. | `1.0` |
    | AD02 | O app deverá ter tela de ajuda e pop-up "Precisa de ajuda?" | `1.0` |
    | AD03 | O app deverá possuir tutoriais e ou melhor informação sobre como rastrear uma encomenda | `1.0` |
    | AD04 | As informações sobre o rastreio de encomendas devem ser precisas (fornecem data, hora e local em cada atualização da encomenda) | `1.0` |
    | AD05 | O chat com o entregador deve ser confiável (as mensagens devem ser arquivadas por um período de até 1 ano) | `1.0` |

    <font size="3"><p style="text-align: center">Fonte: [Pablo S. Costa][PabloGH], 2024.</p></font>

## + Restrições de Design

**Restrições de Design** são limitações específicas e condições que devem ser consideradas durante o processo de criação e desenvolvimento de um produto, seja ele um aplicativo, um site, um objeto físico ou qualquer outro artefato de design. Essas restrições podem abranger uma variedade de áreas, incluindo aspectos técnicos, estéticos, funcionais, orçamentários, temporais, culturais, entre outros. Elas são fatores que impõem limites ou direcionam as decisões de design para atender a determinados critérios ou requisitos.

Na **tabela 6**, é possível ver os **Requisitos Não Funcionais para Restrições de Design** elicitados para o aplicativo "Correios".

=== "`2.0`"

    <font><p style="text-align: center">**Tabela 6** - Requisitos + Restrições de Design.</p></font>

    | ID | Descrição | Versão |
    | --- | --- | --- |
    | RD01 | O app deverá mostrar informação de forma clara usando conceitos de minimalismo. | `1.1` |
    | RD02 | O app deverá ter uma interface fluída, carregando a interfaces internas em menos de 300ms. | `1.1` |
    | RD03 | A visualização de mensagens deve ser rápida e minimalista, carregando em menos de 300ms. | `1.1` |
    | RD04 | A visualização de vales postais deve ser protegida com senha e usuário, sendo acessível apenas pelo usuário autorizado | `1.1` |
    | RD05 | O aplicativo requer uma interface amigável e fácil de usar, seguindo um padrão de estilo pré-estabelecido. | `1.1` |
    | RD06 | A opção de rastrear encomendas deve ser de fácil acesso (deve estar na página principal e o usuário não deve demorar mais de 2 minutos para achá-la). | `1.0` |
    | RD07 | A aplicação precisa ser responsiva se adaptando para diferentes formatos e tamanhos de tela. | `1.1` |

    <font size="3"><p style="text-align: center">Fonte: [Pablo S. Costa][PabloGH], 2024.</p></font>

=== "`1.0`"

    <font><p style="text-align: center">**Tabela 6** - Requisitos + Restrições de Design.</p></font>

    | ID | Descrição | Versão |
    | --- | --- | --- |
    | RD01 | O app deverá mostrar informação mais clara e menos poluída na Home. | `1.0` |
    | RD02 | O app deverá ter uma interface fluída e estável. | `1.0` |
    | RD03 | A visualização de mensagens deve ser rápida e fácil de usar. | `1.0` |
    | RD04 | A visualização de vales postais deve ser protegida e acessível apenas pelo usuário autorizado | `1.0` |
    | RD05 | O aplicativo requer uma interface amigável e fácil de usar. | `1.0` |
    | RD06 | A opção de rastrear encomendas deve ser de fácil acesso (deve estar na página principal e o usuário não deve demorar mais de 2 minutos para achá-la). | `1.0` |

    <font size="3"><p style="text-align: center">Fonte: [Pablo S. Costa][PabloGH], 2024.</p></font>

## Bibliografia

> 1. Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.
>
> 2. * Grupo 01 de Requisitos de Software 2023.1. Projeto do aplicativo  Bilheteria Digital. Disponível em :  <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/>. Acesso em: 20 de Maio de 2024
>
> 3. * Grupo 01 de Requisitos de Software 2023.2 Economia DF. Disponível em :  <https://github.com/Requisitos-de-Software/2023.2-Economia-DF/>. Acesso em: 20 de Maio de 2024

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| `1.0`  | 20/05/2024 | Criação do documento | [Pablo S. Costa](https://github.com/pabloheika) &  [Danilo Carvalho Antuneres](https://github.com/Danilo-Carvalho-Antunes) | [Elias F. Oliveira](https://github.com/EliasOliver21) |
| `2.0`  | 20/05/2024 | Refatoração com versionamento. | [Pablo S. Costa](https://github.com/pabloheika) |  |

[ClaudioGH]: https://github.com/claudiohsc
[DaniloGH]: https://github.com/Danilo-Carvalho-Antunes
[EliasGH]: https://github.com/EliasOliver21
[GabrielBGH]: https://github.com/Bertolazi
[GabrielFGH]: https://github.com/MMcLovin
[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo
