# Requisitos Elicitados

## Introdução

Essa página contém todos os requisitos funcionais e não funcionais elicitados usando as técnicas de [Análise Documental](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/#introducao), [brainstorming](tecnicas/brainstorming.md), [observação](tecnicas/observacao.md) e [questionário](tecnicas/questionario.md).

## Metodologia

A tabela 1 apresenta os requisitos funcionais e a tabela 2 os não funcionais, cada uma com uma coluna para: o ID do requisito - identificando por qual técnica ele foi elicitado - uma para sua descrição, outra para o seu código de identificação dentre a categoria de requisito (funcional ou não), uma coluna para identificar se ele está implementado ou não e mais uma coluna com a sua mais atual versão.

Legendas:

> - RFxx: Requisito Funcional n°X.
> - RNFx: Requisito Não Funcional n°X 
> - ADxx: Análise Documental n°X
> - BSxx: Brainstorm n°X
> - OBSx: Observação n°X
> - QSxx: Questionário n°X

### Requisitos Funcionais

<font size="2"><p style="text-align: center">Tabela 3 - Requisitos Funcionais Versionados.</p></font>

<Center>

| ID  | Descrição | Fonte | Implementado | Versão |
| :-: | --------- | :---: | :----------: | :----: |
| RF01 | O usuário deve poder realizar cadastro pelo app | [BS01][BSRF] | Sim | `1.0` |
| RF02 | O usuário deve poder realizar login pelo app | [BS02][BSRF] | Sim | `1.0` |
| RF03 | O usuário deve poder acessar o histórico de notificações do objeto | [BS03][BSRF] | Não | `1.0` |
| RF04 | O usuário deve poder ativar bloqueio do aplicativo em caso de furto do dispositivo | [BS04][BSRF] | Não | `1.0` |
| RF05 | O usuário deve ter a opção de utilização de chip de localização para rastreamento da encomenda | [BS05][BSRF] | Não | `1.0` |
| RF06 | O usuário deve visualizar a estipulação de prazo de entrega | [BS06][BSRF] | Sim | `1.0` |
| RF07 | O usuário deve visualizar a atualização do prazo de entrega caso ocorram variações | [BS07][BSRF] | Não | `1.0` |
| RF08 | O usuário deve ter acesso a uma aba para contatos das empresas que postaram a encomenda | [BS08][BSRF] | Não | `1.0` |
| RF09 | O usuário deve receber notificações push pelo aplicativo | [BS09][BSRF] | Sim | `1.0` |
| RF10 | O usuário deve receber notificações SMS | [BS10][BSRF] | Sim | `1.0` |
| RF11 | O usuário deve receber notificações pelo Whatsapp | [BS11][BSRF] | Não | `1.0` |
| RF12 | O usuário deve ter acesso a um Chatbot para suporte ao cliente | [BS12][BSRF] | Não | `1.0` |
| RF13 | O usuário deve poder visualizar um tutorial para realizar o rastreamento | [BS13][BSRF] | Não | `1.0` |
| RF14 | O usuário deve poder receber o status da encomenda pelo WhatsApp | [BS14][BSRF] | Não | `1.1` |
| RF15 | O usuário deve poder aumentar e diminuir a fonte | [BS15][BSRF] | Não | `1.0` |
| RF16 | O usuário deve ter a opção de falar com um atendente para obter ajuda | [BS16][BSRF] | Não | `1.1` |
| RF17 | O usuário deve ter acesso a uma página de FAQ (Perguntas Frequentes) | [BS17][BSRF] | Não | `1.0` |
| RF18 | O usuário deve poder visualizar sua encomenda no mapa | [BS18][BSRF] | Não | `1.0` |
| RF19 | O usuário deve poder visualizar detalhes da situação do produto | [BS19][BSRF] | Sim | `1.0` |
| RF20 | O usuário deve poder realizar o rastreio por código mais simples | [BS20][BSRF] | Não | `1.0` |
| RF21 | O usuário deve poder realizar o rastreio por QR Code | [BS21][BSRF] | Sim | `1.0` |
| RF22 | O usuário deve receber notificação pelo e-mail | [BS22][BSRF] | Não | `1.0` |
| RF23 | O usuário deve poder realizar o pagamento de impostos/taxas de importação pelo aplicativo | [BS23][BSRF] | Não | `1.0` |
| RF24 | O usuário deve poder realizar a simulação de envio com as informações do objeto | [BS24][BSRF] | Sim | `1.0` |
| RF25 | O aplicativo permite realizar login com sua conta | [OBS01][OBSRF] | Sim | `1.0` |
| RF26 | O aplicativo permite rastreamento de encomendas por código. | [OBS02][OBSRF] | Sim | `1.0` |
| RF27 | O aplicativo permite enviar encomendas (envelope, caixa, cilindro) | [OBS03][OBSRF] | Sim | `1.0` |
| RF28 | O aplicativo possibilite ver seus pagamentos | [OBS04][OBSRF] | Sim | `1.0` |
| RF29 | O aplicativo oferece uma busca por agências próximas ao seu endereço | [OBS05][OBSRF] | Sim | `1.0` |
| RF30 | O aplicativo possibilita o cálculo de preços e prazos de encomendas nacionais e internacionais | [OBS06][OBSRF] | Sim | `1.0` |
| RF31 | O aplicativo possibilita a compra de certificados digitais dos correios | [OBS07][OBSRF] | Sim | `1.0` |
| RF32 | O aplicativo oferece o acompanhamento da sua conta e realizar recargas pelo aplicativo | [OBS08][OBSRF] | Sim | `1.0` |
| RF33 | O aplicativo permite visualização de mensagens | [OBS09][OBSRF] | Sim | `1.0` |
| RF34 | O aplicativo oferece a visualização de vales postais | [OBS10][OBSRF] | Sim | `1.0` |
| RF35 | O aplicativo oferece uma área de busca por objetos perdidos em envios | [OBS11][OBSRF] | Sim | `1.0` |
| RF36 | O aplicativo fornece uma área de contato sobre violência contra a mulher | [OBS12][OBSRF] | Sim | `1.0` |
| RF37 | As informações das entregas ativas e completas na página de rastreio | [Q01][QRF] | Sim | `1.1` |
| RF38 | Filtrar o tipo de encomenda pelo tipo de entrega | [Q02][QRF] | Não | `1.0` |
| RF39 | Assistente virtual dos correios para ajudar a executar tarefas e achar opções muitas vezes de difícil acesso pelo site. | [Q03][QRF] | Não | `1.1` |
| RF40 | Ter um chat para se comunicar diretamente com o fornecedor, e consiga ter as informações básicas do mesmo. | [Q04][QRF] | Não | `1.1` |
| RF41 | Ter um chat para se comunicar diretamente com o entregador, e consiga ter as informações dos mesmos. | [Q05][QRF] | Não | `1.1` |
| RF42 | Poder fazer os pagamentos pagamento de tributos e taxas de importação em uma página própria para essa finalidade. | [Q06][QRF] | Não | `1.1` |
| RF43 | O usuário deve conseguir mudar a opção de recebimento dentro do aplicativo, antes que sua encomenda seja enviada. | [AD01][QRF] | Não | `1.0` |
| RF44 | O usuário deve ser notificado quando o recebimento for efetuado. | [AD03][QRF] | Não | `1.0` |
| RF45 | O sistema deve permitir que o usuário reserve o locker mais perto de sua casa baseado no CEP informado, de acordo com a disponibilidade | [AD04][QRF] | Não | `1.0` |
| RF46 | O usuário deve poder mudar local de recebimento da encomenda, antes que a mesma tenha sido enviada. | [AD05][QRF] | Não | `1.1` |
| RF47 | O usuário pode optar por retirar em uma agência ou caixa postal | [AD06][QRF] | Não | `1.0` |
| RF48 | O usuário deve ser capaz de realizar uma pré-postagem pelo aplicativo | [AD09][QRF] | Sim | `1.0` |
| RF49 | O usuário deve ser capaz de gerenciar o carrinho de pré-postagens, podendo adicionar ou excluir uma pré-postagem | [AD10][QRF] | Sim | `1.0` |
| RF50 | O usuário poderá pagar uma pré-postagem com cartão de crédito, boleto ou pix | [AD11][QRF] | Não | `1.0` |
| RF51 | O usuário deve ser capaz de adicionar endereços pré-cadastrados ao preencher uma pré-postagem | [AD12][QRF] | Não | `1.0` |
| RF52 | O usuário pode escolher salvar as informações do cartão de crédito para pagamentos futuros | [AD14][QRF] | Sim | `1.0` |
| RF53 | O usuário deve ser capaz de consultar uma seção de achados e perdidos para encontrar documentos | [AD15][QRF] | Não | `1.0` |
| RF54 | O Usuário deve ser capaz de gerenciar suas importações | [AD16][QRF] | Não | `1.0` |
| RF55 | O Usuário deve ser capaz de resolver situações alfandegárias | [AD17][QRF] | Não | `1.0` |
| RF56 | O usuário deve ser capaz de visualizar histórico de situações alfandegárias | [AD18][QRF] | Não | `1.0` |
| RF57 | O usuário deve ser capaz de inserir novas importações | [AD19][QRF] | Não | `1.0` |
| RF58 | O usuário deve ter acesso a meios de pagamento de taxas | [AD20][QRF] | Não | `1.0` |
| RF59 | O usuário deve ser notificado sobre atualizações de importações | [AD21][QRF] |   | `1.0` |
| RF60 | O usuário deve poder contestar taxas e tributações | [AD22][QRF] | Não | `1.0` |
| RF61 | O Usuário deve ser capaz de emitir comprovante | [AD23][QRF] | Não | `1.0` |
| RF62 | O usuário deve ser capaz de emitir DIS | [AD24][QRF] | Não | `1.0` |
| RF63 | A busca por itens deve ser o mais otimizada possível, com o usuário tendo a opção de filtragem para simplificar e diminuir o tempo de busca por produtos que antes se apresentariam em uma categoria única. | [AD29][QRF] | Não | `1.1` |
| RF64 | O usuário deve poder ter a total liberdade de editar suas informações e transitar pelas etapas que o sistema oferece. | [AD30][QRF] | Não | `1.1` |
| RF65 | O usuário deverá possuir uma opção para ordenar os itens de acordo com seus anseios, como: menor preço, maior preço, maior relevância ou menor. | [AD31][QRF] | Não | `1.1` |

</Center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024.</p></font>

### Requisitos Não-Funcionais

<font size="2"><p style="text-align: center">Tabela 4 - Requisitos Não-Funcionais Versionados.</p></font>

<Center>

| ID  | Descrição | Fonte | Implementado | Versão |
| :-: | --------- | :---: | :----------: | :----: |
| RNF01 | O app deve bloquear todas as funções dentro de 5 minutos após ser reportado como furtado/roubado | [BS25][BSRNF] | Não | `2.0` |
| RNF02 | O app deve mostrar a localização da entrega com atualização em tempo real, com um atraso máximo de 10 segundos | [BS26][BSRNF] | Não | `2.0` |
| RNF03 | O app deve identificar encomendas através de QR Code em menos de 2 segundos após a leitura do código | [BS27][BSRNF] | Sim | `2.0` |
| RNF04 | O app deve identificar encomendas através de um e-mail enviado em até 5 segundos após a solicitação do usuário | [BS28][BSRNF] | Não | `2.0` |
| RNF05 | O app deve mostrar informações na Home com um layout que possua no máximo 3 elementos principais por seção e texto legível (tamanho mínimo de 14pt) | [BS29][BSRNF] | Não | `2.0` |
| RNF06 | O app deve enviar informações de rastreio por email dentro de 1 minuto após qualquer atualização no status da entrega | [BS30][BSRNF] | Não | `2.0` |
| RNF07 | O app deve gerar um código de rastreio único e simples, composto por no máximo 10 caracteres alfanuméricos | [BS31][BSRNF] | Não | `2.0` |
| RNF08 | O app deve possuir um sistema de chatbot com tempo de resposta inicial de no máximo 3 segundos e deve permitir redirecionamento a um atendente humano em no máximo 2 minutos | [BS32][BSRNF] | Não | `2.0` |
| RNF09 | O app deve ter uma tela de ajuda acessível a partir de qualquer tela em no máximo 2 cliques e um pop-up "Precisa de ajuda?" visível em todas as telas principais | [BS33][BSRNF] | Não | `2.0` |
| RNF10 | O app deve possuir tutoriais interativos com duração máxima de 3 minutos cada e/ou informações claras sobre como rastrear uma encomenda, acessíveis em no máximo 2 cliques | [BS34][BSRNF] | Não | `2.0` |
| RNF11 | O app deve ter um delay nas notificações de entrega não superior a 10 segundos após qualquer atualização de status. | [BS35][BSRNF] | Não | `2.0` |
| RNF12 | O app deve estar em conformidade com as diretrizes WCAG 2.1, nível AA, para acessibilidade | [BS36][BSRNF] | Não | `2.0` |
| RNF13 | O app deve ter uma interface com tempo de resposta para qualquer interação do usuário não superior a 2 segundos e uma taxa de falha de operação inferior a 1% | [BS37][BSRNF] | Sim | `2.0` |
| RNF14 | O aplicativo deve criptografar todos os dados do usuário durante o armazenamento e transmissão. | [OBS13][OBSRNF] | Sim | `2.0` |
| RNF15 | O sistema de rastreamento de encomendas deve retornar o status da encomenda em menos de 5 segundos para 95% das consultas. | [OBS14][OBSRNF] | Sim | `2.0` |
| RNF16 | O sistema de envio de encomendas deve suportar o envio de objetos com pesos de 1 grama até 50 quilogramas e dimensões de até 200x200x200 cm. | [OBS15][OBSRNF] | Sim | `2.0` |
| RNF17 | O acesso aos pagamentos deve exigir autenticação do usuário utilizando um método de autenticação de dois fatores. | [OBS16][OBSRNF] | Não | `2.0` |
| RNF18 | A busca por agências deve retornar resultados baseados na localização do usuário com um raio de precisão de 200 metros. | [OBS17][OBSRNF] | Sim | `2.0` |
| RNF19 | O cálculo de preços e prazos de encomendas deve ser concluído em menos de 10 segundos para 95% das consultas. | [OBS18][OBSRNF] | Sim | `2.0` |
| RNF20 | A compra de certificados digitais deve utilizar protocolos HTTPS para todas as transações. | [OBS19][OBSRNF] | Sim | `2.0` |
| RNF21 | O acompanhamento da conta e recargas deve utilizar autenticação segura e confirmar a operação com um código enviado por SMS ou email. | [OBS20][OBSRNF] | Sim | `2.0` |
| RNF22 | A interface de visualização de mensagens deve carregar em menos de 5 segundos para 95% das operações. | [OBS21][OBSRNF] | Sim | `2.0` |
| RNF23 | A visualização de vales postais deve ser acessível apenas após autenticação do usuário com senha e um método adicional de autenticação. | [OBS22][OBSRNF] | Sim | `2.0` |
| RNF24 | A busca por objetos perdidos deve retornar resultados em menos de 5 segundos para 95% das consultas. | [OBS23][OBSRNF] | Sim | `2.0` |
| RNF25 | A área de contato sobre violência contra a mulher deve ter opção de chat ao vivo com tempo de resposta de menos de 10 minutos durante o horário de atendimento. | [OBS24][OBSRNF] | Sim | `2.0` |
| RNF26 | O aplicativo deve possuir uma interface que permita a navegação entre diferentes seções com no máximo 5 cliques a partir da tela inicial. | [OBS25][OBSRNF] | Sim | `2.0` |
| RNF27 | O aplicativo deve ser compatível com Android versão 8.0 ou superior e iOS versão 13.0 ou superior. | [OBS26][OBSRNF] | Sim | `2.0` |
| RNF28 | O aplicativo deve enviar notificações sobre o status da entrega via push notifications dentro de 30 minutos após a atualização do status. | [OBS27][OBSRNF] | Sim | `2.0` |
| RNF29 | A opção de filtrar encomendas deve ser de fácil acesso (até 2 frames de ajuda a partir da página de encomendas) | [Q07][QRNF] | Sim | `1.0` |
| RFN30 | O aplicativo deve notificar o usuário com eficácia (deve haver um sistema de redundância, para que a mesma notificação seja enviada por diferentes meios - SMS, email, Whatsapp e notificação pelo aplicativo -, de acordo com a preferência do usuário) | [Q08][QRNF] | Não | `1.1` |
| RNF31 | As informações sobre o rastreio de encomendas devem ser precisas (fornecem data, hora e local em cada atualização da encomenda) | [Q09][QRNF] | Sim | `1.0` |
| RNF32 | O usuário deve estar satisfeito com a aplicação (Caso seja solicitado, mais de 70% dos usuários devem atribuir uma nota igual ou maior que 3 - em uma escala de 1 a 5 - ao recomendar o aplicativo dos Correios a um amigo) | [Q10][QRNF] | Não | `1.0` |
| RNF33 | A opção de rastrear encomendas deve ser de fácil acesso (deve estar na página principal e o usuário não deve demorar mais de 2 minutos para achá-la) | [Q11][QRNF] | Não | `1.0` |
| RNF34 | O chat com o entregador deve ser protegido de acessos indevidos (de acordo com as especificações de segurança do [Art. 46](#referencias-bibliograficas) da LGPD) por meio de criptografia AES-256 | [Q12][QRNF] | Não | `1.1` |
| RNF35 | O usuário deve poder mudar o método de recebimento em até 3 cliques desde iniciar a ação. | [AD02][QRNF] | Não | `1.1` |
| RNF36 | Os ícones de opção dentro dessa funcionalidade devem ser 44x44 pixels, para melhor visualização de cada um dos ícones para pessoas com leves problemas visuais. | [AD07][QRNF] | Não | `1.1` |
| RNF37 | A funcionalidade deve ser aparente na página principal. | [AD08][QRNF] | Não | `1.1` |
| RNF38 | O usuário deve ser perguntado sobre a confirmação de operações importantes como exclusão de itens do carrinho | [AD13][QRNF] | Sim | `1.0` |
| RNF39 | As informações devem ser atualizadas em tempo de execução | [AD25][QRNF] | Não | `1.0` |
| RNF40 | A liberação das encomendas deve ser automática | [AD26][QRNF] | Não | `1.0` |
| RNF41 | Sempre que presente o documento destinatário na encomenda, as importações devem ser inseridas automaticamente | [AD27][QRNF] | Não | `1.0` |

</Center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024.</p></font>

## Bibliografia

> 1. Grupo 01 de Requisitos de Software 2023.1. **Projeto do aplicativo  Bilheteria Digital**. Disponível em :  <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/>. Acesso em: 24 de Abril de 2024

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| `1.0`    | 24/04/2024 | Criação do documento | [Gabriel F. J. Silva](https://github.com/MMcLovin)   | [Ricardo Augusto](https://www.github.com/avmricardo) |
| `1.1`    | 20/05/2024 | Adiciona requisitos da análise documental | [Gabriel F. J. Silva](https://github.com/MMcLovin)   | [Elias F. Oliveira][EliasGH] |
| `2.0`    | 01/07/2024 | Atualização da tabela | [Gabriel F. J. Silva](https://github.com/MMcLovin)   | [Ricardo Augusto][RicardoGH] |

[ClaudioGH]: https://github.com/claudiohsc
[DaniloGH]: https://github.com/Danilo-Carvalho-Antunes
[EliasGH]: https://github.com/EliasOliver21
[GabrielBGH]: https://github.com/Bertolazi
[GabrielFGH]: https://github.com/MMcLovin
[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo

<Links das seções da análise documental>
[ADRF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental
[ADRNF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental

</Links das seções do brainstorm>
[BSRF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/#requisitos-elicitados
[BSRNF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/#requisitos-elicitados

<Links das seções da observação>
[OBSRNF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/#requisitos-nao-funcionais-rnf
[OBSRF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/#requisitos-funcionais-rf

</Links das seções do questionário>
[QRF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/#funcionais
[QRNF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/#nao-funcionais